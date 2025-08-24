---
title: Skills
# the default layout is 'page'
---
<!-- ### Coding Languages

| Skill               | Proficiency |
|---------------------|-------------|
| Python             | 🟦🟦🟦🟦🟦🟦⬜⬜⬜⬜ 60% |
| RStudio            | 🟦🟦🟦🟦🟦🟦⬜⬜⬜⬜ 60% |
| Jupyter Notebook   | 🟦🟦🟦🟦🟦⬜⬜⬜⬜⬜ 50% |
| MATLAB             | 🟦🟦🟦⬜⬜⬜⬜⬜⬜⬜ 30% |

### Computer-Aided Drafting

| Skill                  | Proficiency |
|------------------------|-------------|
| SolidWorks            | 🟦🟦🟦🟦🟦🟦🟦⬜⬜⬜ 70% |
| Autodesk Fusion 360   | 🟦🟦🟦🟦🟦🟦🟦⬜⬜⬜ 70% |
| GD&T                  | 🟦🟦🟦🟦🟦⬜⬜⬜⬜⬜ 50% |
| PDM                   | 🟦🟦🟦🟦🟦⬜⬜⬜⬜⬜ 50% |
| Engineering Drawings  | 🟦🟦🟦🟦🟦🟦🟦⬜⬜⬜ 70% |

### Manufacturing Knowledge

| Skill                        | Proficiency |
|------------------------------|-------------|
| DFM/DFA                      | 🟦🟦🟦🟦🟦🟦🟦⬜⬜⬜ 70% |
| P/D FMEA                     | 🟦🟦🟦🟦🟦🟦🟦🟦⬜⬜ 80% |
| Quality Control              | 🟦🟦🟦🟦🟦🟦🟦⬜⬜⬜ 70% |
| Machining                    | 🟦🟦🟦⬜⬜⬜⬜⬜⬜⬜ 30% |
| Welding                      | 🟦🟦🟦⬜⬜⬜⬜⬜⬜⬜ 30% |
| Hand Tools                   | 🟦🟦🟦🟦🟦🟦🟦🟦🟦⬜ 90% |
| 3D Printing                  | 🟦🟦🟦🟦🟦🟦🟦⬜⬜⬜ 70% |
| Root Cause Analysis          | 🟦🟦🟦🟦🟦🟦🟦🟦⬜⬜ 80% |
| Tolerance Stack Analysis     | 🟦🟦🟦🟦🟦🟦⬜⬜⬜⬜ 60% |
| Engineering Change Control   | 🟦🟦🟦🟦🟦🟦🟦🟦🟦⬜ 90% |
| MES/ERP                      | 🟦🟦🟦⬜⬜⬜⬜⬜⬜⬜ 30% |
| Design of Experiments        | 🟦🟦🟦🟦🟦🟦⬜⬜⬜⬜ 60% |

### Soft Skills

| Skill                        | Proficiency |
|------------------------------|-------------|
| Microsoft Project            | 🟦🟦🟦🟦🟦🟦⬜⬜⬜⬜ 60% |
| Conflict Resolution          | 🟦🟦🟦🟦🟦🟦🟦🟦🟦⬜ 90% |
| PowerPoint                   | 🟦🟦🟦🟦🟦🟦⬜⬜⬜⬜ 60% |
| Excel                        | 🟦🟦🟦🟦🟦🟦⬜⬜⬜⬜ 60% |
| Technical Report Writing     | 🟦🟦🟦⬜⬜⬜⬜⬜⬜⬜ 30% |
| Think-cell                   | 🟦🟦🟦🟦🟦🟦🟦🟦⬜⬜ 80% | -->

<style>
.skill-group {
    margin-bottom: 30px;
}

.skill-group h3 {
    margin-bottom: 15px;
    color: #333;
}

.skill {
    margin-bottom: 12px;
}

.skill span {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
}

.progress {
    background-color: #eee;
    border-radius: 8px;
    height: 22px;
    width: 100%;
    overflow: hidden;
}

.progress-bar {
    height: 100%;
    border-radius: 8px;
    width: 0; /* Start at 0 for animation */
    animation: fill-bar 2s forwards; /* Animate on load */
}

/* Color coding */
.progress-bar.coding { background-color: #306998; }
.progress-bar.cad { background-color: #ff5722; }
.progress-bar.manufacturing { background-color: #4caf50; }
.progress-bar.soft { background-color: #9c27b0; }

/* Animation keyframes */
@keyframes fill-bar {
    from { width: 0; }
    to { width: var(--bar-width); }
}
</style>

<div class="skills">
  <!-- Example for Coding Languages with sequential animation -->
  <div class="skill-group">
    <h3>Coding Languages</h3>
    <div class="skill" style="animation-delay: 0s;">
      <span>Python – 60%</span>
      <div class="progress"><div class="progress-bar coding" style="--bar-width: 60%; animation-delay: 0s;"></div></div>
    </div>
    <div class="skill" style="animation-delay: 0.3s;">
      <span>RStudio – 60%</span>
      <div class="progress"><div class="progress-bar coding" style="--bar-width: 60%; animation-delay: 0.3s;"></div></div>
    </div>
    <div class="skill" style="animation-delay: 0.6s;">
      <span>Jupyter Notebook – 50%</span>
      <div class="progress"><div class="progress-bar coding" style="--bar-width: 50%; animation-delay: 0.6s;"></div></div>
    </div>
    <div class="skill" style="animation-delay: 0.9s;">
      <span>MATLAB – 30%</span>
      <div class="progress"><div class="progress-bar coding" style="--bar-width: 30%; animation-delay: 0.9s;"></div></div>
    </div>
  </div>

  <!-- Repeat for other categories -->
  <div class="skill-group">
    <h3>Computer-Aided Drafting</h3>
    <div class="skill" style="animation-delay: 0s;"><span>SolidWorks – 70%</span><div class="progress"><div class="progress-bar cad" style="--bar-width: 70%; animation-delay: 0s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.3s;"><span>Autodesk Fusion 360 – 70%</span><div class="progress"><div class="progress-bar cad" style="--bar-width: 70%; animation-delay: 0.3s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.6s;"><span>Engineering Drawings – 70%</span><div class="progress"><div class="progress-bar cad" style="--bar-width: 70%; animation-delay: 0.6s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.9s;"><span>GD&T – 50%</span><div class="progress"><div class="progress-bar cad" style="--bar-width: 50%; animation-delay: 0.9s;"></div></div></div>
    <div class="skill" style="animation-delay: 1.2s;"><span>PDM – 50%</span><div class="progress"><div class="progress-bar cad" style="--bar-width: 50%; animation-delay: 1.2s;"></div></div></div>
  </div>

  <!-- Manufacturing Knowledge -->
  <div class="skill-group">
    <h3>Manufacturing Knowledge</h3>
    <div class="skill" style="animation-delay: 0s;"><span>Engineering Change Control – 90%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 90%; animation-delay: 0s;"></div></div></div>
    <div class="skill" style="animation-delay: 0s;"><span>Hand Tools – 90%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 90%; animation-delay: 0s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.3s;"><span>P/D FMEA – 80%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 80%; animation-delay: 0.3s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.6s;"><span>Root Cause Analysis – 80%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 80%; animation-delay: 0.6s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.9s;"><span>DFM/DFA – 70%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 70%; animation-delay: 0.9s;"></div></div></div>
    <div class="skill" style="animation-delay: 1.2s;"><span>Quality Control – 70%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 70%; animation-delay: 1.2s;"></div></div></div>
    <div class="skill" style="animation-delay: 1.5s;"><span>3D Printing – 70%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 70%; animation-delay: 1.5s;"></div></div></div>
    <div class="skill" style="animation-delay: 1.8s;"><span>Design of Experiments – 60%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 60%; animation-delay: 1.8s;"></div></div></div>
    <div class="skill" style="animation-delay: 2.1s;"><span>Tolerance Stack Analysis – 60%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 60%; animation-delay: 2.1s;"></div></div></div>
    <div class="skill" style="animation-delay: 2.7s;"><span>MES/ERP – 30%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 30%; animation-delay: 2.7s;"></div></div></div>
    <div class="skill" style="animation-delay: 3s;"><span>Machining – 30%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 30%; animation-delay: 3s;"></div></div></div>
    <div class="skill" style="animation-delay: 3.3s;"><span>Welding – 30%</span><div class="progress"><div class="progress-bar manufacturing" style="--bar-width: 30%; animation-delay: 3.3s;"></div></div></div>
  </div>

  <!-- Soft Skills -->
  <div class="skill-group">
    <h3>Soft Skills</h3>
    <div class="skill" style="animation-delay: 0s;"><span>Conflict Resolution – 90%</span><div class="progress"><div class="progress-bar soft" style="--bar-width: 90%; animation-delay: 0s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.3s;"><span>Project Management – 80%</span><div class="progress"><div class="progress-bar soft" style="--bar-width: 80%; animation-delay: 0.3s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.6s;"><span>Think-cell – 80%</span><div class="progress"><div class="progress-bar soft" style="--bar-width: 80%; animation-delay: 0.6s;"></div></div></div>
    <div class="skill" style="animation-delay: 0.9s;"><span>Microsoft Project – 60%</span><div class="progress"><div class="progress-bar soft" style="--bar-width: 60%; animation-delay: 0.9s;"></div></div></div>
    <div class="skill" style="animation-delay: 1.2s;"><span>PowerPoint – 60%</span><div class="progress"><div class="progress-bar soft" style="--bar-width: 60%; animation-delay: 1.2s;"></div></div></div>
    <div class="skill" style="animation-delay: 1.5s;"><span>Excel – 60%</span><div class="progress"><div class="progress-bar soft" style="--bar-width: 60%; animation-delay: 1.5s;"></div></div></div>
    <div class="skill" style="animation-delay: 1.8s;"><span>Technical Report Writing – 30%</span><div class="progress"><div class="progress-bar soft" style="--bar-width: 30%; animation-delay: 1.8s;"></div></div></div>
  </div>
</div>
