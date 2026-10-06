<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Anqi%20%28Angel%29%20Gao&fontSize=60&animation=fadeIn&fontAlignY=35&desc=Robotics%20%C2%B7%20Machine%20Learning%20%C2%B7%20Controls&descAlignY=58&descAlign=50&fontColor=ffffff" alt="Anqi (Angel) Gao: Robotics, Machine Learning, Controls" width="100%">
</p>

<h1 align="center">Hello, I'm Angel (Anqi) Gao 👋</h1>

<p align="center">
  Final-year Engineering Science (Robotics) student at the University of Toronto · Toronto, ON
</p>

<p align="center">
  <a href="https://github.com/angel-gao"><img src="https://readme-typing-svg.demolab.com/?lines=Final-year+Engineering+Science+(Robotics)+student+at+UofT;Undergraduate+thesis+with+the+TRAIL+lab+at+UTIAS;Open+to+full-time+new-grad+roles+starting+May+2027;Robotics+%7C+Machine+Learning+%7C+Perception+%7C+Controls&font=Fira+Code&color=36BCF7&width=720&height=50&center=true&vCenter=true&pause=1000&size=22&duration=3500" alt="Final-year Engineering Science (Robotics) student at UofT. Undergraduate thesis with the TRAIL lab at UTIAS. Open to full-time new-grad roles starting May 2027."></a>
</p>

<p align="center">
  <a href="mailto:anqi.gao@mail.utoronto.ca"><img src="https://img.shields.io/badge/Open%20to%20work-New%20grad%20%C2%B7%20May%202027-2EA44F?style=for-the-badge" alt="Open to work: new grad, May 2027"></a>
  <img src="https://img.shields.io/badge/Toronto%2C%20ON-Canada-C8102E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Toronto, ON, Canada">
  <a href="mailto:anqi.gao@mail.utoronto.ca"><img src="https://img.shields.io/badge/Email-anqi.gao%40mail.utoronto.ca-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email anqi.gao@mail.utoronto.ca"></a>
</p>

> [!IMPORTANT]
> **Looking for a full-time new-grad engineering role starting May 2027.**
>
> - **Roles:** robotics, machine learning, perception and computer vision, controls and autonomy, embedded systems, and research engineering.
> - **Interests:** reinforcement learning, model predictive control, robot manipulation, sim-to-real transfer, SLAM and control theory.
> - **Availability:** graduating in May 2027 with a B.A.Sc. in Engineering Science (Robotics major, Artificial Intelligence minor); based in Toronto.
> - **Contact:** [anqi.gao@mail.utoronto.ca](mailto:anqi.gao@mail.utoronto.ca)

## 🧭 Now

- **Final year** of the B.A.Sc. in Engineering Science with PEY at the University of Toronto (Sept 2022 to Apr 2027): Robotics major, Artificial Intelligence minor, Engineering Leadership Certificate.
- **Undergraduate thesis (ESC499, 2026–27)** with Prof. Steven Waslander's [TRAIL lab](https://www.trailab.utias.utoronto.ca/) at UTIAS: monocular 3D lane detection under domain shift, from clear weather to winter snow, on the Boreas dataset. The current stage is an Unreal Engine 5 pipeline that renders synthetic snow onto clear Boreas frames, with the virtual camera matched to the dataset's camera.
- **Just finished** a 16-month PEY research term at the National Research Council of Canada's Propulsion and Power Laboratory in Ottawa (May 2025 to Aug 2026). Details below.

<sub>Courses: Control Systems · Electronics · Optimization for Robotics · Probability Reasoning · Computer Algorithms · Microprocessors and Embedded Microcontrollers · Partial Differential Equations</sub>

## 🔬 Research experience

```mermaid
timeline
    title Research and milestones, 2024 to 2027
    Summer 2024 : ML for materials property prediction (Prof. Kangming Li)
                : AI for physics (Prof. Kristen Menou)
    2025 : NRC Propulsion and Power Laboratory, Ottawa, May 2025 to Aug 2026
         : LEAF Laboratory, UofT, world-model RL, Jul to Dec 2025 (Prof. Nick Rhinehart)
    2026 : ESC499 undergraduate thesis, TRAIL lab, UTIAS (Prof. Steven Waslander)
    May 2027 : B.A.Sc. graduation, available for full-time work
```

**National Research Council of Canada, Propulsion and Power Laboratory** · Ottawa · Research Assistant (PEY) · May 2025 to Aug 2026 · supervised by Sangsig Yun
- Investigated a frequency-dependent Rayleigh Index method that segments pressure and heat-release-rate time series and computes FFT-based spectral contributions to characterize thermoacoustic instability. In transient test cases it showed better diagnostic power than pressure variance and the coherence factor, and I co-authored the resulting manuscript, submitted as an NRC internal technical report.
- Filed an invention disclosure for a real-time thermoacoustic instability detection method under the Public Servants Inventions Act, and presented it with supporting market research to an internal NRC review committee.
- Built machine-learning models on the NJFCP fuel-property dataset to predict lean blow-out limits, validated with leave-one-out cross-validation and checked against known combustion physics with SHAP.
- Wrote a 60-reference technical review linking sustainable aviation fuel properties to spray atomization, lean blowout, altitude relight and emissions across the eight ASTM D7566-certified fuel pathways.

**LEAF Laboratory, University of Toronto** · Research Assistant · Jul 2025 to Dec 2025 · supervised by Prof. Nick Rhinehart
- Established a working TD-MPC2 baseline on POPGym benchmarks for research on belief-state representations in partially observable world-model reinforcement learning.
- Designed the interface layer between TD-MPC2's continuous observation and action format and POPGym's discrete and multi-discrete environments (one-hot encoding, concatenation, argmax action decoding), then trained end to end across the targeted environments.
- Analysed failure modes on exploration-heavy tasks such as maze navigation and Battleship under full and partial observability, helping separate memory limits from exploration problems.

**ML for Materials Property Prediction, Summer Research Program** · May 2024 to Aug 2024 · supervised by Prof. Kangming Li (now at KAUST)
- Trained and benchmarked the ALIGNN graph neural network and the SNAP, GAP and MTP potentials on JARVIS/M3GNet datasets for energy and atomic-force prediction, with custom training pipelines and dataset conversion in Python (MAML, pymatgen). MAE trends on six single-element datasets were comparable to the reported JARVIS leaderboard results.
- In element-removal experiments, leaving out common elements such as H, F and O raised energy and force MAE by up to 60×, while removing Rb had a negligible effect.

**AI for Physics, Summer Research Program** · May 2024 to Aug 2024 · supervised by Prof. Kristen Menou
- Prompt engineering on large language models for undergraduate physics multiple-choice questions and counterfactuals. I hand-verified a dataset of about 120 questions with truth labels, used five-shot and chain-of-thought prompting to keep answers in a consistent format, and analysed how performance differed across three answer types.

## 🤖 Featured projects

<table>
  <tr>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/angel-gao/Arctos-Robotic-Arm"><img src="https://raw.githubusercontent.com/angel-gao/Arctos-Robotic-Arm/main/docs/media/gif/demo-arm-wrist.gif" width="190" alt="The Arctos six-axis arm tipping its open gripper upward"></a>
      <br><br>
      <a href="https://github.com/angel-gao/Arctos-Robotic-Arm"><b>Arctos Six-Axis Robotic Arm</b></a>
      <br>
      <sub>Winter 2026 · personal build</sub>
      <br><br>
      A 3D-printed desktop arm from the Arctos kit that I assembled and wired by hand: six steppers, nine hall-effect limit sensors and a servo gripper on an Arduino Mega running six-axis GRBL (clip: a March 2026 hardware demo). Six hand-written bring-up sketches, plus a ~2,900-line PyQt6 control app with button and gamepad modes and an experimental webcam-gesture mode, generated with Claude Code to my spec and debugged on the arm.
      <br><br>
      <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/GRBL-555555?style=flat-square" alt="GRBL">
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/angel-gao/Intro-to-Robotics"><img src="https://skillicons.dev/icons?i=ros,raspberrypi,python" alt="ROS, Raspberry Pi, Python"></a>
      <br><br>
      <a href="https://github.com/angel-gao/Intro-to-Robotics"><b>TurtleBot3 Mail Delivery</b></a>
      <br>
      <sub>Sept to Dec 2024 · course project</sub>
      <br><br>
      A TurtleBot3 on a Raspberry Pi with ROS simulates mail delivery to 3 of 12 offices. Bayesian localization reaches over 90 % confidence after about five colour measurements, with PID line following between offices and RGB colour detection at a tolerance of 25.
      <br><br>
      <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS">
      <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/angel-gao/Line2Live"><img src="https://raw.githubusercontent.com/angel-gao/Line2Live/main/train_gen_examples/Student_AddNoiseD_Triple_NoDataAug/y_genColorTWO_199.jpg" width="240" alt="A grid of faces generated by Line2Live from training-set sketches"></a>
      <br><br>
      <a href="https://github.com/angel-gao/Line2Live"><b>Line2Live</b></a>
      <br>
      <sub>May to Aug 2024 · APS360 team course project</sub>
      <br><br>
      A stacked conditional GAN (U-Net generators, PatchGAN discriminator) that turns face sketches into photos. Three generators split the job into face structure, basic colouring and colour balancing. On a 2,520-image sketch-photo dataset (augmentation included), its three generator stages average 25.1 % lower L1, 16.2 % lower L2 and 3.2 % higher SSIM than a pix2pix baseline on held-out sketches.
      <br><br>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/angel-gao/AI-VS-Human-Battleship"><img src="https://raw.githubusercontent.com/angel-gao/AI-VS-Human-Battleship/main/readme_images/Picture1.png" width="200" alt="Battleship game title screen"></a>
      <br><br>
      <a href="https://github.com/angel-gao/AI-VS-Human-Battleship"><b>AI vs Human Battleship</b></a>
      <br>
      <sub>Java + JavaFX</sub>
      <br><br>
      Battleship against an AI opponent, with a JavaFX interface, sound and save/load. Targeting based on a probability density function raised the AI's win rate against human players to about 60 %.
      <br><br>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/angel-gao/Seam-Carving"><img src="https://skillicons.dev/icons?i=c" alt="C"></a>
      <br><br>
      <a href="https://github.com/angel-gao/Seam-Carving"><b>Seam-Carving</b></a>
      <br>
      <sub>C</sub>
      <br><br>
      Seam carving, the content-aware image-resizing algorithm, implemented in C. The core is in <code>seamcarving.c</code> and <code>seamcarving.h</code>.
      <br><br>
      <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C">
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/angel-gao?tab=repositories"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"></a>
      <br><br>
      <a href="https://github.com/angel-gao?tab=repositories"><b>More repositories</b></a>
      <br>
      <sub>all public work</sub>
      <br><br>
      The full list of my public repositories, sorted by most recent update.
    </td>
  </tr>
</table>

## 📄 Publications

1. Gao, A. & Yun, S. (2026). *Development of a Real-Time Detection Model for Thermoacoustic Instability.* Submitted as an NRC internal technical report.
2. Gao, A. (2024). *Level of Agreement of Damped Harmonic Oscillator Model with the Experimental Pendulum Setup.* 4th International Conference on Mechanical Engineering, Industrial Materials, and Industrial Electronics (MEIMIE 2024), Article 011. DOI: 10.25236/meimie.2024.011. [PDF](https://webofproceedings.org/proceedings_series/ESR/MEIMIE%202024/ME11.pdf)

## 🛠️ Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,java,js,r,matlab,latex&perline=8" alt="Python, C++, C, Java, JavaScript, R, MATLAB, LaTeX">
  <br>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,ros,opencv,unreal,arduino,raspberrypi,git,github,vscode,idea&perline=12" alt="PyTorch, TensorFlow, scikit-learn, ROS, OpenCV, Unreal Engine, Arduino, Raspberry Pi, Git, GitHub, VS Code, IntelliJ IDEA">
</p>

<table>
  <tr>
    <td align="right" valign="top"><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C/C++">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
      <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R">
      <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge" alt="MATLAB">
      <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX">
      <img src="https://img.shields.io/badge/Verilog-1A1A1A?style=for-the-badge" alt="Verilog">
      <img src="https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white" alt="RISC-V">
    </td>
  </tr>
  <tr>
    <td align="right" valign="top"><b>ML and data</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
      <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
      <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy">
      <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
      <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" alt="Matplotlib">
    </td>
  </tr>
  <tr>
    <td align="right" valign="top"><b>Robotics and embedded</b></td>
    <td>
      <img src="https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS">
      <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino">
      <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
      <img src="https://img.shields.io/badge/GRBL%20%2F%20G--code-555555?style=for-the-badge" alt="GRBL / G-code">
      <img src="https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine 5">
    </td>
  </tr>
  <tr>
    <td align="right" valign="top"><b>CAD and EDA</b></td>
    <td>
      <img src="https://img.shields.io/badge/Fusion%20360-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="Fusion 360">
      <img src="https://img.shields.io/badge/Ansys-FFB71B?style=for-the-badge&logo=ansys&logoColor=black" alt="Ansys">
      <img src="https://img.shields.io/badge/ModelSim-1F6FB2?style=for-the-badge" alt="ModelSim">
      <img src="https://img.shields.io/badge/Quartus-0071C5?style=for-the-badge" alt="Quartus">
    </td>
  </tr>
  <tr>
    <td align="right" valign="top"><b>Dev tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge" alt="VS Code">
      <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" alt="IntelliJ IDEA">
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
      <img src="https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=rstudioide&logoColor=white" alt="RStudio">
    </td>
  </tr>
</table>

## 📊 Top languages

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=angel-gao&layout=compact&theme=tokyonight&hide_border=true&hide=html,jupyter%20notebook&disable_animations=true">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=angel-gao&layout=compact&theme=default&hide_border=true&hide=html,jupyter%20notebook&disable_animations=true" alt="Top languages for angel-gao" height="165">
  </picture>
</p>

## 📫 Contact

<p align="center">
  <a href="mailto:anqi.gao@mail.utoronto.ca"><img src="https://img.shields.io/badge/Email-anqi.gao%40mail.utoronto.ca-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email anqi.gao@mail.utoronto.ca"></a>
  <a href="https://github.com/angel-gao"><img src="https://img.shields.io/badge/GitHub-angel--gao-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub angel-gao"></a>
</p>

<p align="center">
  Toronto, Ontario · available for full-time roles from May 2027
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" alt="" width="100%">
</p>
