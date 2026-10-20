# Ziyu Zhao (Victor)

**Undergraduate student exploring engineering software, systems, and scientific computing.**

I build tools and research prototypes around terminals, simulation, CAD, embedded systems, and AI-assisted development. Most of them start with a specific question or annoyance, usually somewhere between “why is this hidden from me?” and “can I make this less awkward to test?”

I am particularly interested in systems where **“it ran” is not the same thing as “it worked.”**

## Selected work

### [code-with-pi](https://github.com/12sqawdwq/code-with-pi) · active experiment

An experiment in giving a coding agent and its user the same persistent terminal. The current implementation uses a C11 broker, PTY on Linux, ConPTY on Windows, authenticated local IPC, and tmux for the Linux split view.

I started it because command execution inside coding agents often hides shell state, process ownership, and full terminal output.

### [ANSYS_skill](https://github.com/12sqawdwq/ANSYS_skill) · experimental

A small CAE validation framework built around a fairly boring but important question: how do we know an automated Mechanical workflow actually produced a solved and evaluated result?

It separates geometry-ready, setup-ready, solver-input-generated, and solved/evaluated states, then checks delivery files, result evidence, and a cantilever benchmark.

### [ForgeSpec-Studio](https://github.com/12sqawdwq/ForgeSpec-Studio) · prototype

An experiment in turning loose engineering requirements into inspectable CAD source instead of opaque generated geometry. The intermediate `AssemblySpec` stays visible before deterministic CadQuery code produces STEP and STL files.

The repository also experiments with a small standards database, source checks, manifests, and assurance reports.

### [ANSYS_simulation_IOP](https://github.com/12sqawdwq/ANSYS_simulation_IOP) · research code

A finite-element investigation of transpalpebral tonometry. It includes APDL models, parameter sweeps, run manifests, post-processing scripts, mesh-sensitivity checks, and data-provenance notes.

Negative results remain visible: the current model is not mesh independent, some parameters are not identifiable from the available sweeps, and a frozen high-pressure fit failed to extrapolate well.

### [Harmony_TaskFlow](https://github.com/12sqawdwq/Harmony_TaskFlow) · active prototype

A somewhat over-engineered HarmonyOS experiment involving tasks, Calendar OAuth, Cloudflare Workers/D1, deep links, ArkTS, and a multi-ABI native Mihomo core.

It started as an application project and became a way to explore less documented parts of the HarmonyOS toolchain and its native integration boundaries.

### [CoughKD](https://github.com/12sqawdwq/CoughKD) · research prototype

A medical-audio pipeline for subject-disjoint dataset preparation, PyTorch/CUDA experiments, and teacher–student distillation. Measured runs, planned targets, and clinical claims are kept separate.

## Experience

- **LanZhi Medical · Shenzhen InnoX Academy** — Embedded & Algorithm Development Intern (Jul 2025 – present). Probe control and eyelid–eyeball FEM for a home-use, eyelid-closed tonometer; within ±2.5 mmHg of the gold standard, three patent applications.
- **XJTLU Academy of AI · University of Liverpool** — Research Assistant (2024 – present). Prostate MRI AI (ReFER, PAD-Former, EDRF); maintain the group's 16× A800 GPU cluster.
- **Finkey · Shuangfu Technology (Suzhou)** — Co-founder & Embedded Software Lead (Aug 2025 – present). FIDO2 security key in Rust on Tock OS (nRF52840); 100+ units shipped.
- **ByteDance · Volcano Engine** — Technical Operations Intern (Dec 2025 – May 2026). LLM benchmarking and agent / AI-coding workflow analysis.
- **Z.ai (Zhipu AI)** — Campus Ambassador (Aug 2025 – Apr 2026). Talks on vLLM, SGLang and LangChain; Dify campus partnership and agent hackathon.
- **DeepBlue Technology** — Embedded Software Engineer Intern (Apr 2024 – Jun 2025). Wheeled-biped robot control, SLAM and CAN-linked controllers.
- **Fudan University** — Research Intern, Intelligent Perception & Autonomous Systems Lab (Jun – Aug 2024). ROS 2 navigation on Jetson NX.
- **East China Normal University** — Research Intern, Intelligent Ultrasound Research Center (Nov 2023 – May 2024). Multi-channel electrical-stimulation system on STM32/ESP32.

Full details: [CV (PDF)](https://12sqawdwq.github.io/CV_Ziyu_Zhao_final.pdf)

## Things I am exploring

- persistent PTYs and process ownership in coding-agent workflows
- solver state and result evidence in CAE automation
- source-first, reconstructable CAD generation
- mesh sensitivity, parameter identifiability, and reproducible simulation
- HPC experiments and model-scaling workflows
- embedded and hardware–software boundaries

## A little context

I am a final-year BEng student in Microelectronic Science and Engineering at Xi'an Jiaotong-Liverpool University and the University of Liverpool (dual degree; First Class averages in Years 1–2). My earlier projects include embedded control, robotics, medical imaging, and constrained-device software.

I use coding agents heavily in day-to-day development. The parts I try to keep explicit are the problem definition, architecture choices, debugging record, experiments, and validation. I am still figuring out which layer I want to spend most of my time in; so far, the answer seems to be somewhere between engineering software, systems tooling, and scientific computing.

Research work includes the [PAD-Former PI-RADS classification paper](https://doi.org/10.1109/BIBM66473.2025.11356522) (IEEE BIBM 2025, first author), ReFER (IEEE BIBM 2026, first author, accepted) and EDRF (IEEE BIBM 2026, second author, accepted), along with ongoing public experiments in ocular biomechanics and medical-audio model compression.

## Contact

- [GitHub](https://github.com/12sqawdwq)
- [Personal technical homepage](https://12sqawdwq.github.io/)
- [Email](mailto:102450592zzy@gmail.com)
