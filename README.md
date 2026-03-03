<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Vaibhav%20Krishna%20V&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=55&desc=Electronics%20%7C%20AI%20%7C%20Biomedical%20%7C%20Embedded%20Systems&descAlignY=75&descSize=18&descColor=a78bfa"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=750&lines=Electronics+%26+Communication+Engineer;PyTorch+%7C+TensorFlow+%7C+Flask+%7C+Plotly;Biomedical+AI+%7C+Deep+RL+%7C+SCADA+Systems;Japanese+%F0%9F%87%AF%F0%9F%87%B5+N4+Certified+%E2%86%92+Targeting+N2" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vaibhav-krishna-v)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vaibhavkv078@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=vaibhav-krishna-v&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)](https://github.com/vaibhav-krishna-v)

</div>

---

## About Me

I build systems that have to work in the real world cardiac monitors, thermal controllers, traffic signal agents, water management SCADA. Most of my projects involve AI running inside a live loop, not offline on a dataset.

My stack is PyTorch and TensorFlow for AI, Flask and Plotly for deployed dashboards, and SciPy for signal work. On the hardware side I have worked with FPGAs, microcontrollers, and EDA tools across multiple semesters covering VLSI, power electronics, and communication systems. I am also learning Japanese and currently preparing for N3 after clearing N4.

- 🔬 Biomedical signal processing, CNN inference, clinical logic layers
- 🤖 Deep RL, live training agents, multi-agent grid control
- 🏭 SCADA digital twins, Flask deployed monitoring systems
- 🇯🇵 Japanese — Almost N4 certified, targeting N2

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🫀 Clinical Grade ECG AI Monitor

Streams ECG from MIT-BIH, detects R-peaks, runs a 4-class CNN (Normal, PVC, AFib, Other) trained on real beat annotations, and monitors multiple patients at the same time using threads. AFib is caught separately through HRV analysis, SDNN and RMSSD thresholds independent of the model output. The PyQtGraph dashboard turns red the moment a clinical alarm fires.

Model trains once, saves to disk, and reloads on every subsequent run.

`TensorFlow` `WFDB` `SciPy` `PyQtGraph` `PyQt5` `threading`

[![Repo](https://img.shields.io/badge/View_Repo-ECG_Monitor-7c3aed?style=for-the-badge&logo=github)](https://github.com/vaibhav-krishna-v/ecg-ai-monitor)

</td>
<td width="50%" valign="top">

### 🚦 Wide Scale Multi-Intersection Deep RL Traffic

A 3x3 grid of intersections: 9 nodes, 4 lanes each controlled by a live training DQN agent. Three modes in one codebase: Fixed, Density, and DQN. The agent trains with experience replay and a target network, logs everything to TensorBoard, and gets exported as a TorchScript traced model at the end of each run. A separate analytics script reads the TensorBoard CSVs and generates comparison bar charts and a radar plot.

DQN brought average queue from 26.7 vehicles down to 0.8.

`PyTorch` `TensorBoard` `Tkinter` `NumPy` `Matplotlib` `Pandas`

[![Repo](https://img.shields.io/badge/View_Repo-Traffic_RL-7c3aed?style=for-the-badge&logo=github)](https://github.com/vaibhav-krishna-v/smart-traffic-dqn)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌡️ Priority Aware Industrial Thermal AI

Three thermal zones: CPU, Power, Ambient; each with its own PyTorch policy network training live during simulation. A nonlinear urgency curve maps temperature bands to cooling aggressiveness. On top of that, a spike detector catches sudden load events and a safety override takes over if any zone crosses 70°C. Anti-windup relaxation prevents the system from overcooling once temperatures stabilize.

Live Flask dashboard with Plotly shows all three zone temperatures and cooling percentage updating every second.

`PyTorch` `Flask` `Plotly` `NumPy` `threading`

[![Repo](https://img.shields.io/badge/View_Repo-Thermal_AI-7c3aed?style=for-the-badge&logo=github)](https://github.com/vaibhav-krishna-v/smart-thermal-control)

</td>
<td width="50%" valign="top">

### 💧 Smart Water Tank Digital Twin SCADA

Three tanks: Source, Process, Reserve; running as a live digital twin. The pump activates automatically when Process drops below 40% and Source has enough to transfer. If Process falls further to 35%, Reserve steps in as a secondary failsafe. Each tank is rendered as a 3D mesh in the browser, with fill height and color updating every second. The transfer pipe turns cyan when flow is active.

Glass style Flask dashboard, no desktop dependency.

`Flask` `Plotly` `threading`

[![Repo](https://img.shields.io/badge/View_Repo-Water_SCADA-7c3aed?style=for-the-badge&logo=github)](https://github.com/vaibhav-krishna-v/smart-water-monitor)

</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=for-the-badge&logo=assemblyscript&logoColor=white)

### AI / ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

### Web & Visualization
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![TensorBoard](https://img.shields.io/badge/TensorBoard-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### Hardware & EDA
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Xilinx](https://img.shields.io/badge/Xilinx_Vivado-E01F27?style=for-the-badge&logo=xilinx&logoColor=white)
![Keil](https://img.shields.io/badge/Keil_uVision-003B5C?style=for-the-badge&logo=arm&logoColor=white)
![Cadence](https://img.shields.io/badge/Cadence-005A8B?style=for-the-badge&logo=cadence&logoColor=white)
![HFSS](https://img.shields.io/badge/ANSYS_HFSS-FFB71B?style=for-the-badge&logo=ansys&logoColor=black)
![SolidWorks](https://img.shields.io/badge/SolidWorks-FF0000?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![Fusion360](https://img.shields.io/badge/Fusion_360-FF6600?style=for-the-badge&logo=autodesk&logoColor=white)

</div>

---

## Certifications & Achievements

<details>
<summary><b>🏅 Certifications</b></summary>

| Certification | Issuer |
|---|---|
| Discovering Entrepreneurship | Cisco Networking Academy |
| Introduction to IoT & Digital Transformation | Cisco Networking Academy |
| Strategy Formulation & Data Visualization | IIT Madras |
| Introduction to Cybersecurity | Simplilearn |
| Introduction to Cybercrime | Simplilearn |
| AI/ML for Geodata Analysis | IIRS (ISRO) |
| Deep Learning for Developers | Infosys Springboard |
| Additive Manufacturing Design | Workshop Training |
| VLSI and FPGA | Workshop Training |

</details>

<details>
<summary><b>🏆 Competitions</b></summary>

| Competition | Organizer | Result |
|---|---|---|
| Circuit Master | BMSCE Phase Shift 2023 | Participant |
| Simu Racing | NMIT Arion 2024 | 4th Place |
| HackWithInfy 2025 | Infosys | Participant |
| Capgemini Brand Quest 2025 | Capgemini | Advanced to Level 2 |
| TATA Crucible Campus Quiz 2025 | TATA Group | Participant |

</details>

<details>
<summary><b>🤝 Involvement</b></summary>

- **Manonandhana NGO** — volunteered providing free medical support to neuro-divergent children
- **Oasis NMIT** — Club Member
- **R&D NMIT** — Club Member
- **Shikaram NMIT** — Club Member
- **Microfluidics Workshop** — The Next Frontier in Electronics and Biomedical Innovation, organized with INFAB Semiconductor Pvt Ltd

</details>

---

## GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=vaibhav-krishna-v&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0f0c29&title_color=a78bfa&icon_color=a78bfa&text_color=ffffff"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vaibhav-krishna-v&layout=compact&langs_count=7&theme=tokyonight&hide_border=true&bg_color=0f0c29&title_color=a78bfa&text_color=ffffff"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=vaibhav-krishna-v&theme=tokyonight&hide_border=true&background=0f0c29&ring=a78bfa&fire=a78bfa&currStreakLabel=a78bfa" alt="GitHub Streak"/>

</div>

---

## Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=vaibhav-krishna-v&bg_color=0f0c29&color=a78bfa&line=7c3aed&point=ffffff&area=true&hide_border=true" alt="Contribution Graph"/>
</div>

---

## 🇯🇵 Japanese

```
N5 ████████████████████ Mastered
N4 ████████████████░░░░ Almost Certified ✅
N3 ████████░░░░░░░░░░░░ In Progress 🎯
N2 ░░░░░░░░░░░░░░░░░░░░ Next milestone
```

Studying Japanese to work closer to Japan's semiconductor and embedded systems industry.

---

## Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-vaibhavkv078%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vaibhavkv078@gmail.com)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer&fontColor=ffffff"/>

**Vaibhav Krishna V**
</div>
