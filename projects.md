[Home](index.html) | [Projects](projects.html) | [Publications](publications.html) | [Skills](skills.html) | [Contact](contact.html)


<!-- Page Title -->
<h1 style="font-size:28px; font-weight:bold; margin-bottom:20px;">
  Projects
</h1>


<h3 style="margin-top:40px; margin-bottom:15px; font-weight:bold;font-size:20px;">
  Development of a Finite difference–based Diffused Interface phase-change solver
</h3>


<div style="display:flex; flex-wrap:wrap; margin-bottom:40px; align-items:flex-start;">
  <!-- Text column -->
  <div style="flex:1; min-width:250px; padding-right:20px;">
    <ul>
      <li>Developed MPI parallelized phase-changing FDM multiphase solver based on open source code FluTAS</li>
      <li>Worked on a diffuse interface algorithm that works accurtaely for boiling and evaporation problems </li>
      <li>Simulated scalar transfer from mulitple bubbles for industrial gas transfer applications</li>
    </ul>
  </div>

  <!-- Image column -->
  <div style="flex:1; min-width:250px;">
    <figure>
      <img src="assets/film_boil(1).gif" alt="Multiphase CFD" style="max-width:100%; height:auto; border-radius:6px;">
      <figcaption style="text-align:center; font-size:14px; color:#555; margin-top:5px;">
        Film boiling from a plain surface
      </figcaption>
    </figure>
  </div>
</div>

<h3 style="margin-top:40px; margin-bottom:15px; font-weight:bold;font-size:20px;">
  DNS studies of heat and mass transfer from multiple droplet/bubble in turbulent suspensions
</h3>


<div style="display:flex; flex-wrap:wrap; margin-bottom:40px; align-items:flex-start;">
  <!-- Text column -->
  <div style="flex:1; min-width:250px; padding-right:20px;">
    <ul>
      <li>Study of evaporation from multiple droplets of different sizes in a triperiodic channel, relevant to combustion scenarios </li>
      <li>Study of scalar transfer from multiple rising bubbles relevant to industrial gas exchange applications, with lower and higher bubble densities (volume fractions) </li>
    </ul>
  </div>

  <!-- Image column -->
  <div style="flex:1; min-width:250px;">
    <figure>
      <img src="assets/12drop.gif" alt="Multiphase CFD" style="max-width:100%; height:auto; border-radius:6px;">
      <figcaption style="text-align:center; font-size:14px; color:#555; margin-top:5px;">
        Multiple droplet evaporating in a channel
      </figcaption>
    </figure>
  </div>
</div>

<h3 style="margin-top:40px; margin-bottom:15px; font-weight:bold;font-size:20px;">
  Development of a phase-field LB solver for multiphase flow
</h3>


<div style="display:flex; flex-wrap:wrap; margin-bottom:40px; align-items:flex-start;">
  <!-- Text column -->
  <div style="flex:1; min-width:250px; padding-right:20px;">
    <ul>
      <li>Contributed to the OpenACC-GPU parallelized phase-field LB multiphase solver accLB</li>
      <li>Captured all bubble shapes seperately for a bubble rise problem </li>
      <li>Studied multiple droplets faliing  on a surface with different wettability</li>
      <li>Captured on and of-axis collision of water droplets in air</li>
      <li>Implementing phase-change to the solver </li>
    </ul>
  </div>

  <!-- Image column -->
  <div style="flex:1; min-width:250px;">
    <figure>
      <img src="assets/bubble_type.png" alt="Multiphase CFD" style="max-width:100%; height:auto; border-radius:6px;">
      <figcaption style="text-align:center; font-size:14px; color:#555; margin-top:5px;">
        Different bubble shapes with Eotvos and Galilei number
      </figcaption>
    </figure>
  </div>
</div>


<h3 style="margin-top:40px; margin-bottom:15px; font-weight:bold;font-size:20px;">
  Multiphase pseudopotential Lattice Boltzmann Solver Development for Phase-Change on Structured Surfaces
</h3>


<div style="display:flex; flex-wrap:wrap; margin-bottom:40px; align-items:flex-start;">
  <!-- Text column -->
  <div style="flex:1; min-width:250px; padding-right:20px;">
    <ul>
      <li>Developed OpenMP parallelized phase-changing LB multiphase solver</li>
      <li>Augmented the existing algorithm to simulate high density ratio problems, simulated all boiling regimes to plot the whole boiling curve on plain and structured surfaces with different wettability</li>
      <li>Simulated flow boiling in a narrow channel - captured bubbly and slug flow regimes</li>
      <li>Simulated condensation in micro/nano structured surfaces - captured Cassie and Wenzel droplet generation modes</li>
    </ul>
  </div>

  <!-- Image column -->
  <div style="flex:1; min-width:250px;">
    <figure>
      <img src="assets/boiling_curve.png" alt="Multiphase CFD" style="max-width:100%; height:auto; border-radius:6px;">
      <figcaption style="text-align:center; font-size:14px; color:#555; margin-top:5px;">
        Boiling curve in surfacs with different wettability
      </figcaption>
    </figure>
  </div>
</div>
