# Vaibhav Krishna V

**Electronics & Communication Engineer**

I build control systems and applied AI — the kind where the physics has to be right, not just the accuracy metric. My four major projects span industrial thermal management, smart water SCADA, clinical ECG monitoring, and urban traffic signal control. Each one was built from sensor physics upward: noise models, actuator dynamics, safety logic, and a live dashboard that makes the system's internal state visible in real time.

I am actively seeking engineering roles at Japanese technology and industrial companies.

---

## Projects

### [THERMIS-X](https://github.com/vaibhavkrishnav/thermis-x) — Industrial Thermal AI
Seven-zone thermal management system with full Type-K thermocouple acquisition (41.276 µV/°C Seebeck, ADC noise chain, cold-junction compensation, 0.1% fault injection), a hybrid neural-adaptive controller (60/40 policy net / rule blend), slew-rate-limited pump and motor control (P ∝ RPM³ affinity law), and six operating modes with hysteresis-based transitions. Predictive pre-cooling via 30-sample linear extrapolation. 58 W nominal / 436 W peak. Real-time Flask + Plotly SCADA dashboard.

`Python` `PyTorch` `Flask` `Plotly` `pywebview`

---

### [AquaNexus SCADA Pro](https://github.com/vaibhavkrishnav/aquanexus-scada-pro) — Cascaded Tri-Loop Water Management
Three interlocked control loops: PID with anti-windup (saturation suspension + sign-reversal halving), 6-tick transport lag, FDIR watchdog with auto-recovery; smart agricultural irrigation with IEC 61511 pH hysteresis alarm and a 4-guard decision matrix; MPC feedforward from a 10-tick digital twin injected pre-cycle into the valve command. ISO 22400 OEE computed from Availability × Performance (6-tier) × Quality. Financial ROI tracked in real time. Dash dashboard, CSV telemetry export.

`Python` `Dash` `Plotly`

---

### [CardioSentinel AI v2.0](https://github.com/vaibhavkrishnav/cardiosentinel-ai) — Clinical ECG Monitoring System
Multi-scale residual attention 1D-CNN (kernel 3/7/11 parallel entry, Squeeze-and-Excite channel attention) trained on MIT-BIH with class-weighted focal loss. 98% test accuracy, AUC 0.9997, 100% recall on PVC and AFib. Hybrid decision engine: rule-based pre-emption (ISHNE AFib criteria, physiological HR overrides) + neural threshold gates. Composite risk score across five independent clinical dimensions. LSTM future risk predictor, DQN alert escalation agent. ONNX Runtime deployment (ORT_ENABLE_ALL), INT8 quantization available. End-to-end latency 180–280 ms on CPU — within ACLS <300 ms standard. Six golden-time windows with AHA/ESC/ACC citations.

`Python` `TensorFlow` `ONNX Runtime` `PyQtGraph` `wfdb`

---

### [AdaptiFlow-X](https://github.com/vaibhavkrishnav/adaptiflow-x) — Deep RL Traffic Signal Control
Dueling Double DQN with Prioritised Experience Replay managing a 3×3 nine-intersection grid. 16-action space: 4 lanes × 4 phase durations (8/16/28/45 s). 8-D state: normalised queues + circular time-of-day encoding + last action. Multi-objective reward: queue reduction + throughput − power − overflow penalty. Pressure routing spills saturated queues to least-congested adjacent node. Emergency vehicle preemption, four time-of-day schedules with manual override, automated three-mode benchmark suite (FIXED → DENSITY → DQN). TorchScript export for inference-only deployment. TensorBoard logging. 84.1% peak traffic efficiency, 77% power reduction vs. fixed-time baseline.

`Python` `PyTorch` `TensorBoard` `Tkinter`

---

## Background

**Internship — NMIT ECE Department (6 weeks)**
MEMS sensor design, semiconductor fabrication process, VLSI design and simulation using Cadence Virtuoso, COMSOL Multiphysics, and Xilinx Vivado. Hands-on with 6T SRAM cell analysis.

**Certifications**
ISRO · Infosys · Cisco

**Volunteer Work**
Manonandana Trust Early Intervention Centre, Bengaluru — community outreach connecting families of children with developmental disabilities to free professional support services.

---

## Technical Stack

**Languages:** Python · C++ · MATLAB  
**ML / DL:** PyTorch · TensorFlow · scikit-learn · ONNX Runtime  
**Control & Signal Processing:** SciPy · NumPy · PID · MPC · RL (DQN / DDQN / PER)  
**Embedded & Hardware:** Cadence Virtuoso · COMSOL · Vivado · FPGA · MEMS  
**Dashboards & APIs:** Flask · Dash · Plotly · PyQtGraph · pywebview  
**Tools:** Git · TensorBoard · Linux · AtCoder

---

## Languages

**English** — Professional  
**日本語** — Self-studied through immersion (anime, manga, games) and structured
grammar study. Scored near-passing on JLPT N4 (missed by 11 marks) and NAT-N3
(missed by 14 marks) without dedicated exam preparation. Actively continuing.
Genuine long-term interest in working and living in Japan.

---

## What I'm Looking For

An engineering role at a Japanese company where the work is technically serious — embedded systems, industrial AI, control engineering, autonomous systems, or medical devices. I want to be in an environment where getting the physics right matters as much as getting the code to run.

I am not looking for a role where "AI" means wrapping an API. I want to work on systems where the decisions the software makes have consequences in the physical world.

---

## Contact

**Email:** vaibhavkrishna@example.com  
**LinkedIn:** [linkedin.com/in/vaibhavkrishnav](https://linkedin.com/in/vaibhavkrishnav)  
**Location:** Bengaluru, India · Open to relocation to Japan
