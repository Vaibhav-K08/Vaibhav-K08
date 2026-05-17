<div align="center">

# Vaibhav Krishna V
### Electronics & Communication Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vkv078)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vaibhav-krishna-v)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vaibhavkv078@gmail.com)
[![Location](https://img.shields.io/badge/Bengaluru%2C%20India-Open%20to%20Japan-ff6b35?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

I build control systems and applied AI — the kind where the physics has to be right, not just the accuracy metric. My four major projects span industrial thermal management, smart water SCADA, clinical ECG monitoring, and urban traffic signal control. Each one was built from sensor physics upward: noise models, actuator dynamics, safety logic, and a live dashboard that makes the system's internal state visible in real time.

I am actively seeking engineering roles at Japanese technology and industrial companies.

---

## 🛠 Technical Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=flat-square&logo=plotly&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![TensorBoard](https://img.shields.io/badge/TensorBoard-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Control & Signal Processing** · **Reinforcement Learning** · **PID / MPC** · **FPGA / VLSI** · **MEMS**  
**Cadence Virtuoso** · **COMSOL Multiphysics** · **Xilinx Vivado**

</div>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌡 [THERMIS-X](https://github.com/vaibhavkrishnav/thermis-x)
**Industrial Thermal AI**

Seven-zone thermal management with full Type-K thermocouple acquisition chain (41.276 µV/°C Seebeck, ADC noise, cold-junction compensation, 0.1% fault injection), hybrid neural-adaptive controller (60/40 policy net / rule blend), slew-rate-limited actuator control (P ∝ RPM³), and six hysteresis-based operating modes. Predictive pre-cooling via 30-sample linear extrapolation.

**58 W nominal · 436 W peak · 83.9% AI effectiveness**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

</td>
<td width="50%" valign="top">

### 💧 [AquaNexus SCADA Pro](https://github.com/vaibhavkrishnav/aquanexus-scada-pro)
**Cascaded Tri-Loop Water Management**

Three interlocked control loops: full PID with anti-windup and 6-tick transport lag (Loop-1), smart agricultural irrigation with IEC 61511 pH hysteresis and 4-guard decision matrix (Loop-2), MPC feedforward from a 10-tick digital twin injected pre-cycle into the valve command (Loop-3). ISO 22400 OEE. Financial ROI tracked live.

**SCADA Score 60.98 · OEE 61.1% · CSV telemetry export**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dash](https://img.shields.io/badge/-Dash-008DE4?style=flat-square&logo=plotly&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ❤️ [CardioSentinel AI v2.0](https://github.com/vaibhavkrishnav/cardiosentinel-ai)
**Clinical ECG Monitoring System**

Multi-scale residual attention 1D-CNN (kernel 3/7/11 parallel entry + Squeeze-and-Excite) trained on MIT-BIH. Hybrid decision engine: ISHNE rule-based pre-emption + neural threshold gates. Five-dimension composite risk score. LSTM future risk predictor. DQN alert escalation agent. ONNX Runtime deployment with INT8 quantization.

**98% accuracy · AUC 0.9997 · 100% AFib & PVC recall · 180–280 ms latency**

![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ONNX](https://img.shields.io/badge/-ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![PyQtGraph](https://img.shields.io/badge/-PyQtGraph-41CD52?style=flat-square&logo=qt&logoColor=white)

</td>
<td width="50%" valign="top">

### 🚦 [AdaptiFlow-X](https://github.com/vaibhavkrishnav/adaptiflow-x)
**Deep RL Urban Traffic Control**

Dueling Double DQN + Prioritised Experience Replay on a 3×3 nine-intersection grid. 16-action space (4 lanes × 4 phase durations). Multi-objective reward: queue + throughput − power − overflow. Pressure routing, emergency preemption, four time-of-day schedules, automated FIXED → DENSITY → DQN benchmark suite. TorchScript export.

**84.1% peak efficiency · 77% power reduction vs. fixed-time baseline**

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorBoard](https://img.shields.io/badge/-TensorBoard-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=vaibhavkrishnav&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vaibhavkrishnav&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎓 Background

| | |
|---|---|
| **Internship** | NMIT ECE Dept — MEMS design, semiconductor fabrication, VLSI/FPGA (Cadence Virtuoso, COMSOL, Vivado) |
| **Certifications** | ISRO · Infosys · Cisco |
| **Volunteer** | Manonandana Trust Early Intervention Centre — community outreach for families of children with developmental disabilities |
| **Interests** | Music · Early morning lake walks · Anime · Manga |

---

## 🇯🇵 Languages

| Language | Level |
|---|---|
| **English** | Professional |
| **日本語** | Self-studied through immersion (anime, manga, games) and structured grammar study. Scored near-passing on JLPT N4 (missed by 11 marks) and NAT-N3 (missed by 14 marks) without dedicated exam preparation. Actively continuing. Genuine long-term interest in working and living in Japan. |

---

## 🎯 What I'm Looking For

An engineering role at a Japanese company where the work is technically serious — embedded systems, industrial AI, control engineering, autonomous systems, or medical devices. I want to be in an environment where getting the physics right matters as much as getting the code to run.

I am not looking for a role where "AI" means wrapping an API. I want to work on systems where the decisions the software makes have consequences in the physical world.

<div align="center">

**Open to relocation to Japan · Available from 2026**

</div>
