# Bill Zi

计算机科学博士，Purdue University / Indiana University  

LLMs/MLLMs | AI Agentic Systems | Agent Orchestration & Harnesses | RAG | NLP 与 CV | GenAI | 工业与医疗 AI | XAI 与鲁棒性 | 毫米波与嵌入式

主要做编译器、LLM 系统、分布式实验平台、嵌入式原型，以及各种从零实现的工程项目。

个人主页：[billzi2016.github.io](https://billzi2016.github.io/) · [GitHub 项目](https://github.com/billzi2016/billzi2016.github.io) · [文档](https://billzi2016.github.io/docs/)  
Google Scholar：[Ziqian Bi](https://scholar.google.com/citations?user=4z9m238AAAAJ&hl=en-US)

## 重点项目

<table>
<tr>
<td valign="top">

- [AI-Solar-Panel-Defect-Detection-Deployment](https://github.com/billzi2016/AI-Solar-Panel-Defect-Detection-Deployment) · [文档](https://billzi2016.github.io/AI-Solar-Panel-Defect-Detection-Deployment/)  
  面向太阳能电池和光伏面板缺陷检测的工作区，覆盖数据准备、YOLO 检测实验、异常检测、部署辅助工具和双语 MkDocs 文档。

- [Gomoku-AI](https://github.com/billzi2016/Gomoku-AI) · [演示](https://billzi2016.github.io/Gomoku-AI/) · [文档](https://billzi2016.github.io/Gomoku-AI/docs/)  
  基于 Rust/Wasm 的浏览器五子棋 AI，包含 bitboard、VCF 搜索、Alpha-Beta 剪枝、迭代加深、Web Worker 并行和本地 CPU 推理。

- [Chinese-Chess-AI](https://github.com/billzi2016/Chinese-Chess-AI) · [演示](https://billzi2016.github.io/Chinese-Chess-AI/)
  基于 ElephantEye C++ 引擎与 WebAssembly 的浏览器中国象棋 AI，支持本地 UCCI 搜索分析，无需后端服务。

- [LLM-Benchmark-Studio](https://github.com/billzi2016/LLM-Benchmark-Studio)  
  本地优先的 LLM 评测平台，使用 Django、Vue、PostgreSQL、RabbitMQ、Celery 和 SSE 组织完整评测流程。

- [Build-DeepSeek-Step-by-Step](https://github.com/billzi2016/Build-DeepSeek-Step-by-Step)  
  从 tokenizer、attention、GQA、MLA、MoE 一路讲到训练与对齐的现代 LLM 拆解项目。

- [blockchain-theory](https://github.com/billzi2016/blockchain-theory)
  从零实现区块链基础组件与共识机制，覆盖 PoW、带惩罚机制的 PoS、Merkle Tree、ECDSA 签名与 UTXO 模型。

- [Apple-Silicon-LLM-Engine-from-Scratch](https://github.com/billzi2016/Apple-Silicon-LLM-Engine-from-Scratch)  
  面向 Apple Silicon 的 GPT-2 推理引擎，从 NumPy 版一路做到 PyTorch MPS 和 C++/Metal。

- [distributed-paxos-raft-lab](https://github.com/billzi2016/distributed-paxos-raft-lab)  
  Paxos / Raft 分布式共识实验平台，包含 FastAPI 节点模拟、Vue 控制面板和 Docker 集群编排。

- [GPU-Test-and-Polite-Scheduler](https://github.com/billzi2016/GPU-Test-and-Polite-Scheduler)  
  面向共享 GPU 服务器的实用工具，覆盖验卡、压测、多卡通信测试和礼貌型后台调度。

- [Leetcode-All-Languages-Best-Solutions](https://github.com/billzi2016/Leetcode-All-Languages-Best-Solutions) · [文档](https://billzi2016.github.io/Leetcode-All-Languages-Best-Solutions/)  
  多语言 LeetCode 最优解整理项目，按难度、题号区间和题目 slug 生成 Markdown，并配套 MkDocs 文档站。  
  一个可控制思考级别、节约 token 数量且保持准确回答的 AI agent，通过 Ollama host 调用大语言模型（LLM）gpt-oss 120b 生成解法。  
  覆盖语言：  
  C、C++、Java、Python、Python3、C#、JavaScript  
  TypeScript、PHP、Swift、Kotlin、Dart、Go、Ruby  
  Scala、Rust、Racket、Erlang、Elixir。

- [homemade-risc-v-64-vector-linux-emulator](https://github.com/billzi2016/homemade-risc-v-64-vector-linux-emulator) · [文档](https://billzi2016.github.io/homemade-risc-v-64-vector-linux-emulator/)  
  从零实现的教学型 64 位 RISC-V 模拟器，支持向量扩展与 Linux 启动。

</td>
<td valign="top">

- [Industrial-Query-Agent](https://github.com/billzi2016/Industrial-Query-Agent)  
  面向工业领域问答、检索式工作流和实用 Agent 系统设计的查询助手项目。

- [Chinese-Chess-AI-Pro](https://github.com/billzi2016/Chinese-Chess-AI-Pro) · [演示](https://billzi2016.github.io/Chinese-Chess-AI-Pro/)
  进阶浏览器中国象棋 AI，采用 C++ WebAssembly、NNUE 评估与基于 SharedArrayBuffer 的多线程 Web Worker。

- [Othello-AI](https://github.com/billzi2016/Othello-AI) · [演示](https://billzi2016.github.io/Othello-AI/) · [文档](https://billzi2016.github.io/Othello-AI/docs/)  
  基于 Rust/Wasm 的浏览器黑白棋 AI，包含 bitboard、Alpha-Beta 搜索、精确残局搜索、稳定子评估和 Web Worker 并行。

- [automl-autodl](https://github.com/billzi2016/automl-autodl) · [文档](https://billzi2016.github.io/automl-autodl/)  
  面向 Home Credit 风险建模的表格 AutoML / AutoDL 工作区，包含共享预处理、传统机器学习、PyTorch 深度模型和文档页面。

- [C-Core-Compiler](https://github.com/billzi2016/C-Core-Compiler) · [文档](https://billzi2016.github.io/C-Core-Compiler/)  
  C-like 编译器项目，覆盖词法分析、语法分析、语义检查、IR、代码生成和文档页面。

- [python-git-reproduction](https://github.com/billzi2016/python-git-reproduction) · [文档](https://billzi2016.github.io/python-git-reproduction/)  
  Python 与 Git 可复现实验工作流文档项目，包含 MkDocs 页面和仓库级维护说明。

- [DeepChrInteract-v2](https://github.com/billzi2016/DeepChrInteract-v2) · [文档](https://billzi2016.github.io/DeepChrInteract-v2/)  
  面向染色质互作建模的深度学习项目，配套 Sphinx 文档站。

- [MIMO-FMCW-Radar-Simulator-Multiprocess](https://github.com/billzi2016/MIMO-FMCW-Radar-Simulator-Multiprocess) · [文档](https://billzi2016.github.io/MIMO-FMCW-Radar-Simulator-Multiprocess/)  
  多进程 MIMO FMCW 雷达仿真项目，配套公开文档页面。

- [mmwave-fmcw-cascade-mimo-sensing-platform](https://github.com/billzi2016/mmwave-fmcw-cascade-mimo-sensing-platform) · [文档](https://billzi2016.github.io/mmwave-fmcw-cascade-mimo-sensing-platform/)  
  毫米波 FMCW 级联 MIMO 感知平台，覆盖雷达信号处理和系统工作流文档。

- [mmlock-fmcw-radar-deep-security](https://github.com/billzi2016/mmlock-fmcw-radar-deep-security) · [文档](https://billzi2016.github.io/mmlock-fmcw-radar-deep-security/)  
  面向毫米波感知、认证与安全研究的 FMCW 雷达深度安全项目，采用文档驱动维护。

- [whisper-meeting-transcription-translation-and-summary](https://github.com/billzi2016/whisper-meeting-transcription-translation-and-summary)  
  面向本地音视频文件的离线字幕生成和双语翻译工具，支持 Apple Silicon 上的 MLX 加速和本地 LLM 工作流。

</td>
</tr>
</table>

## 系统、编译器与运行时

<table>
<tr>
<td valign="top">

- [homemade-risc-v-64-vector-linux-emulator](https://github.com/billzi2016/homemade-risc-v-64-vector-linux-emulator) · [文档](https://billzi2016.github.io/homemade-risc-v-64-vector-linux-emulator/)
- [homemade-cpu-raytracer](https://github.com/billzi2016/homemade-cpu-raytracer)
- [C-Core-Compiler](https://github.com/billzi2016/C-Core-Compiler) · [文档](https://billzi2016.github.io/C-Core-Compiler/)
- [python-git-reproduction](https://github.com/billzi2016/python-git-reproduction) · [文档](https://billzi2016.github.io/python-git-reproduction/)
- [Self-Hosting-C-Core-Compiler](https://github.com/billzi2016/Self-Hosting-C-Core-Compiler)
- [Homemade-CPython](https://github.com/billzi2016/Homemade-CPython)

</td>
<td valign="top">

- [build-from-scratch](https://github.com/billzi2016/build-from-scratch)
- [Homemade-Tiny-OS](https://github.com/billzi2016/Homemade-Tiny-OS)
- [Autograd-Compiler-Engine](https://github.com/billzi2016/Autograd-Compiler-Engine)
- [Automatic-Differentiation-From-Scratch](https://github.com/billzi2016/Automatic-Differentiation-From-Scratch)
- [bignum-from-scratch](https://github.com/billzi2016/bignum-from-scratch)
- [Visual-Basic-Core-Compiler](https://github.com/billzi2016/Visual-Basic-Core-Compiler)

</td>
<td valign="top">

- [cordic-fixedpoint-algorithm](https://github.com/billzi2016/cordic-fixedpoint-algorithm)
- [http-server-from--scratch](https://github.com/billzi2016/http-server-from--scratch)
- [Smart-Huffman-Archiver](https://github.com/billzi2016/Smart-Huffman-Archiver)
- [SQLite-Chaos-Tester](https://github.com/billzi2016/SQLite-Chaos-Tester)
- [Reverse-Polish-Notation-Calculator](https://github.com/billzi2016/Reverse-Polish-Notation-Calculator)

</td>
</tr>
</table>

## LLM、Agent 与评测系统

<table>
<tr>
<td valign="top">

- [Industrial-Query-Agent](https://github.com/billzi2016/Industrial-Query-Agent)
- [Build-MCP-Step-by-Step](https://github.com/billzi2016/Build-MCP-Step-by-Step)
- [AI-Agent](https://github.com/billzi2016/AI-Agent)
- [Deep-Learning-The-Definitive-Guide](https://github.com/billzi2016/Deep-Learning-The-Definitive-Guide) · [文档](https://billzi2016.github.io/Deep-Learning-The-Definitive-Guide/)
- [awesome-LLMs](https://github.com/billzi2016/awesome-LLMs)
- [speckit](https://github.com/billzi2016/speckit)

</td>
<td valign="top">

- [ClinicaLLM-OmniBench](https://github.com/billzi2016/ClinicaLLM-OmniBench)
- [ClinicaLLM-OmniBench-EN](https://github.com/billzi2016/ClinicaLLM-OmniBench-EN)
- [LLM-SFT-PEFT-Preference-RL-Quantization-Inference-Deployment](https://github.com/billzi2016/LLM-SFT-PEFT-Preference-RL-Quantization-Inference-Deployment)
- [ai-agent-practice-playbook](https://github.com/billzi2016/ai-agent-practice-playbook)
- [FlashcardsAPP](https://github.com/billzi2016/FlashcardsAPP)
- [midi-react-ai-agent-search](https://github.com/billzi2016/midi-react-ai-agent-search)

</td>
<td valign="top">

- [professional-agentic-learning](https://github.com/billzi2016/professional-agentic-learning)
- [Custom-Style-AI-Chat](https://github.com/billzi2016/Custom-Style-AI-Chat)
- [LLM-Gap-Tracker](https://github.com/billzi2016/LLM-Gap-Tracker)
- [ReAct-AI-Agent](https://github.com/billzi2016/ReAct-AI-Agent)
- [chinapost-internship](https://github.com/billzi2016/chinapost-internship) · [文档](https://billzi2016.github.io/chinapost-internship/)

</td>
</tr>
</table>

## 研究、数据与领域项目

<table>
<tr>
<td valign="top">

- [DeepChrInteract-v2](https://github.com/billzi2016/DeepChrInteract-v2) · [文档](https://billzi2016.github.io/DeepChrInteract-v2/)
- [blockchain-theory](https://github.com/billzi2016/blockchain-theory)
- [ai-agentic-arxiv-observer](https://github.com/billzi2016/ai-agentic-arxiv-observer)
- [Daily-Paper-Reading](https://github.com/billzi2016/Daily-Paper-Reading)
- [LLM-AI-Papers](https://github.com/billzi2016/LLM-AI-Papers)
- [foundation-model-analysis](https://github.com/billzi2016/foundation-model-analysis)
- [generative-models](https://github.com/billzi2016/generative-models)

</td>
<td valign="top">

- [llm-auto-rag-survey](https://github.com/billzi2016/llm-auto-rag-survey)
- [Batch-MRI-Quality-Control](https://github.com/billzi2016/Batch-MRI-Quality-Control)
- [MRI_Deep_Learning_Projects](https://github.com/billzi2016/MRI_Deep_Learning_Projects)
- [Facial-Recognition](https://github.com/billzi2016/Facial-Recognition) · [文档](https://billzi2016.github.io/Facial-Recognition/)
- [Recommender-Systems](https://github.com/billzi2016/Recommender-Systems)
- [SFCN-age-gender-balanced](https://github.com/billzi2016/SFCN-age-gender-balanced)

</td>
<td valign="top">

- [Alphafold-V2-Reproduction](https://github.com/billzi2016/Alphafold-V2-Reproduction)
- [Alphafold-V1-Reproduction](https://github.com/billzi2016/Alphafold-V1-Reproduction)
- [ViT-H](https://github.com/billzi2016/ViT-H)
- [RomeInADay](https://github.com/billzi2016/RomeInADay)
- [homemade-datarobot](https://github.com/billzi2016/homemade-datarobot)
- [SFCN-4-Quadrant-Assessment](https://github.com/billzi2016/SFCN-4-Quadrant-Assessment)

</td>
</tr>
</table>

## 基础设施、观测与工程工具

<table>
<tr>
<td valign="top">

- [NodeExporter-Prometheus-Grafana](https://github.com/billzi2016/NodeExporter-Prometheus-Grafana)
- [Apple-Silicon-Profiler](https://github.com/billzi2016/Apple-Silicon-Profiler)
- [system-burner](https://github.com/billzi2016/system-burner)

</td>
<td valign="top">

- [GPU-Test-and-Polite-Scheduler-EN](https://github.com/billzi2016/GPU-Test-and-Polite-Scheduler-EN)
- [ESP8266-Codex-Usage-Monitor](https://github.com/billzi2016/ESP8266-Codex-Usage-Monitor)
- [ESP8266-Token-Counter](https://github.com/billzi2016/ESP8266-Token-Counter)

</td>
<td valign="top">

- [ESP32-Prometheus-PC-Monitor](https://github.com/billzi2016/ESP32-Prometheus-PC-Monitor)
- [backup-utils](https://github.com/billzi2016/backup-utils)
- [system-design-interview](https://github.com/billzi2016/system-design-interview)

</td>
</tr>
</table>

## 嵌入式、硬件与边缘系统

<table>
<tr>
<td valign="top">

- [ATmega2560-Graphical-RPN-Scientific-Calculator](https://github.com/billzi2016/ATmega2560-Graphical-RPN-Scientific-Calculator)
- [ATMega328p-RPN-Scientific-Calculator](https://github.com/billzi2016/ATMega328p-RPN-Scientific-Calculator)
- [ATmega2560-LCD12864-Game-Of-Life](https://github.com/billzi2016/ATmega2560-LCD12864-Game-Of-Life)

</td>
<td valign="top">

- [LCD12864-Bad-Apple](https://github.com/billzi2016/LCD12864-Bad-Apple)
- [LCD12864-Dither-TV](https://github.com/billzi2016/LCD12864-Dither-TV)
- [Arduino-Wired-Telegraph](https://github.com/billzi2016/Arduino-Wired-Telegraph)
- [ESP32-Weather-Box](https://github.com/billzi2016/ESP32-Weather-Box)
- [immersive-vr-xr-security-telemetry-platform](https://github.com/billzi2016/immersive-vr-xr-security-telemetry-platform)

</td>
<td valign="top">

- [intelligent-esp32-drone-racing-gate-system](https://github.com/billzi2016/intelligent-esp32-drone-racing-gate-system)
- [MCU-Design-and-Prototypes-Sandbox](https://github.com/billzi2016/MCU-Design-and-Prototypes-Sandbox)
- [RS485-Modbus-Concrete-Sensor-Monitor](https://github.com/billzi2016/RS485-Modbus-Concrete-Sensor-Monitor)

</td>
</tr>
</table>

## 算法、搜索与博弈 AI

<table>
<tr>
<td valign="top">

- [mcts-cpu-validate](https://github.com/billzi2016/mcts-cpu-validate) · [文档](https://billzi2016.github.io/mcts-cpu-validate/)
- [gomoku-terminator](https://github.com/billzi2016/gomoku-terminator)
- [Gomoku-AI](https://github.com/billzi2016/Gomoku-AI) · [演示](https://billzi2016.github.io/Gomoku-AI/) · [文档](https://billzi2016.github.io/Gomoku-AI/docs/)
- [Othello-AI](https://github.com/billzi2016/Othello-AI) · [演示](https://billzi2016.github.io/Othello-AI/) · [文档](https://billzi2016.github.io/Othello-AI/docs/)
- [Chinese-Chess-AI](https://github.com/billzi2016/Chinese-Chess-AI) · [演示](https://billzi2016.github.io/Chinese-Chess-AI/)
- [Chinese-Chess-AI-Pro](https://github.com/billzi2016/Chinese-Chess-AI-Pro) · [演示](https://billzi2016.github.io/Chinese-Chess-AI-Pro/)
- [RL-MCTS-gomoku-zero-11x11](https://github.com/billzi2016/RL-MCTS-gomoku-zero-11x11)

</td>
<td valign="top">

- [reversi-mcts-rl-zero](https://github.com/billzi2016/reversi-mcts-rl-zero)
- [reversi-minimax-alphabeta](https://github.com/billzi2016/reversi-minimax-alphabeta)
- [4096-expectimax-bitboard](https://github.com/billzi2016/4096-expectimax-bitboard)
- [tennis-for-two](https://github.com/billzi2016/tennis-for-two) · [演示](https://billzi2016.github.io/tennis-for-two/)
- [maze-algorithms](https://github.com/billzi2016/maze-algorithms)
- [Alphago-Naive](https://github.com/billzi2016/Alphago-Naive)

</td>
<td valign="top">

- [python-falling-blocks-ai](https://github.com/billzi2016/python-falling-blocks-ai)
- [guesswho-ai-from-scratch](https://github.com/billzi2016/guesswho-ai-from-scratch) · [演示](https://billzi2016.github.io/guesswho-ai-from-scratch/)
- [openai-gym-reinforcement-learning-lab](https://github.com/billzi2016/openai-gym-reinforcement-learning-lab)
- [inverted-pendulum-rl-lab](https://github.com/billzi2016/inverted-pendulum-rl-lab)
- [Metropolitan-Routing-Algorithm](https://github.com/billzi2016/Metropolitan-Routing-Algorithm)
- [gomoku-minimax-engine](https://github.com/billzi2016/gomoku-minimax-engine)

</td>
</tr>
</table>

## 练习与学习型仓库

<table>
<tr>
<td valign="top">

- [whitebox-ml-dl-algo](https://github.com/billzi2016/whitebox-ml-dl-algo)
- [advanced-search-data-structures](https://github.com/billzi2016/advanced-search-data-structures)
- [advanced-sorting-algorithms](https://github.com/billzi2016/advanced-sorting-algorithms)

</td>
<td valign="top">

- [Prime-Sieve-Algorithms](https://github.com/billzi2016/Prime-Sieve-Algorithms)
- [Heuristic-Algorithm](https://github.com/billzi2016/Heuristic-Algorithm)
- [Daily-Leetcode](https://github.com/billzi2016/Daily-Leetcode)

</td>
<td valign="top">

- [django-with-speckit](https://github.com/billzi2016/django-with-speckit)
- [leetcode-terminator](https://github.com/billzi2016/leetcode-terminator)

</td>
</tr>
</table>

## 其他项目

<table>
<tr>
<td valign="top">

- [MIMO-FMCW-Radar-Simulator-Multiprocess](https://github.com/billzi2016/MIMO-FMCW-Radar-Simulator-Multiprocess) · [文档](https://billzi2016.github.io/MIMO-FMCW-Radar-Simulator-Multiprocess/)
- [mmwave-fmcw-cascade-mimo-sensing-platform](https://github.com/billzi2016/mmwave-fmcw-cascade-mimo-sensing-platform) · [文档](https://billzi2016.github.io/mmwave-fmcw-cascade-mimo-sensing-platform/)
- [mmlock-fmcw-radar-deep-security](https://github.com/billzi2016/mmlock-fmcw-radar-deep-security) · [文档](https://billzi2016.github.io/mmlock-fmcw-radar-deep-security/)
- [billzi2016.github.io](https://github.com/billzi2016/billzi2016.github.io) · [网站](https://billzi2016.github.io/) · [文档](https://billzi2016.github.io/docs/)

</td>
<td valign="top">

- [vlm-hybrid-gallery](https://github.com/billzi2016/vlm-hybrid-gallery)
- [Receipt-MLLM-OCR](https://github.com/billzi2016/Receipt-MLLM-OCR)
- [whisper-meeting-transcription-translation-and-summary](https://github.com/billzi2016/whisper-meeting-transcription-translation-and-summary)
- [real-time-yolo-vision-intelligence-lab](https://github.com/billzi2016/real-time-yolo-vision-intelligence-lab)

</td>
<td valign="top">

- [chaos-algorithms](https://github.com/billzi2016/chaos-algorithms)
- [Four-Color-Theorem](https://github.com/billzi2016/Four-Color-Theorem)
- [DTMF-Encod-Decode](https://github.com/billzi2016/DTMF-Encod-Decode)

</td>
</tr>
</table>

## 学术主页

[Google Scholar 主页](https://scholar.google.com/citations?user=4z9m238AAAAJ&hl=en-US)

![Google Scholar profile snapshot](images/Snipaste_2026-07-01_01-29-41.png)

## 最近的 GitHub Pages 维护

这一轮维护工作的重点，是把实验型、研究型和长期积累的仓库整理成结构更清楚、对外呈现更完整的公开项目。具体工作包括重新梳理仓库结构、重写并统一 README、建立一致的项目入口，以及补充安装、运行、架构、数据集、实验流程和预期输出等实用说明；对于适合双语呈现的项目，也同步维护英文和中文文档。

各个仓库的文档层也得到了系统加强，包括更清晰的导航、跨页面链接、移动端布局、稳定的静态资源路径和 GitHub Pages 部署。根据项目本身的特点，目前面向外部的文档主要收敛为三种形态：基于 MkDocs 的文档站、基于 Sphinx 的文档站，以及使用 HTML、CSS、JavaScript 构建的原生静态站。

这批持续维护的项目覆盖编译器与运行时系统、LLM 与 Agent 工程、计算机视觉与医学影像、雷达仿真与毫米波感知、可复现研究工作流，以及五子棋、黑白棋等浏览器博弈 AI。整理目标是让每个仓库都更容易查看、理解、复现和长期维护，即使访问者尚未在本地运行项目，也能先掌握其结构、状态和预期用途。下面列出的案例展示了这一轮整理中采用的几种代表性文档和项目呈现方式。

MkDocs 文档站与仓库 README / 文档系统示例：python-git-reproduction

- 页面链接：[https://billzi2016.github.io/python-git-reproduction/](https://billzi2016.github.io/python-git-reproduction/)
- 仓库链接：[https://github.com/billzi2016/python-git-reproduction](https://github.com/billzi2016/python-git-reproduction)

![MkDocs 文档站：python-git-reproduction](images/mkdocs.png)
![仓库 README 与文档系统示例：python-git-reproduction](images/git.png)

Sphinx 文档站：DeepChrInteract-v2

- 页面链接：[https://billzi2016.github.io/DeepChrInteract-v2/](https://billzi2016.github.io/DeepChrInteract-v2/)
- 仓库链接：[https://github.com/billzi2016/DeepChrInteract-v2](https://github.com/billzi2016/DeepChrInteract-v2)

![Sphinx 文档站：DeepChrInteract-v2](images/sphinx.png)

原生静态站：billzi2016.github.io

- 页面链接：[https://billzi2016.github.io/](https://billzi2016.github.io/)
- 仓库链接：[https://github.com/billzi2016/billzi2016.github.io](https://github.com/billzi2016/billzi2016.github.io)

![原生静态站：billzi2016.github.io](images/html.png)

整理型项目 README 示例：Awesome Flow Matching

- 仓库链接：[https://github.com/billzi2016/awesome-flow-matching](https://github.com/billzi2016/awesome-flow-matching)

![整理型项目 README 示例：Awesome Flow Matching](images/awesome.png)

## AI 辅助维护活动

最近我一直在重构和打磨自己的 GitHub Pages，并在 Human-in-the-Loop 的工作流中重度使用 Codex / Claude Code，把不少老仓库逐步整理成更正规、更完整、更易读、也更容易导航的项目站点。下面这些截图记录了过去一个月的使用情况和维护状态。

这项工作并不是为了盲目生成页面，而是按照 Spec-First、Review-Driven 的方式推进，并持续引入测试驱动开发（Test-Driven Development, TDD）、规格驱动开发（Spec-Driven Development, SDD）和持续集成 / 持续交付（Continuous Integration / Continuous Delivery, CI/CD）等工程实践，去提升这些历史项目的可读性、多平台支持能力、可维护性、后续维护效率、安全性和稳定性。AI 辅助极大提升了整体整理和重构速度，而在面对数量众多、相互关联的文档时，AI 也天然更擅长做结构梳理、术语统一和跨文档联动修订，从而减少“这一处改了、另一处没跟上”的问题。与此同时，项目取舍、内容验收、结构收敛以及最终编辑控制始终保持 Human-in-the-Loop，以对 AI 幻觉形成严格抑制，避免未经验证的信息进入最终内容。

跨模型 token 消耗
![Codex 使用面板：跨模型累计消耗 18,935,155,313 个 token](images/Snipaste_2026-07-02_18-00-23.png)

按模型统计的对话轮次
![Codex 使用面板：按模型统计累计 61,090 轮对话](images/Snipaste_2026-07-02_18-01-39.png)

累计生成代码行数
![Codex 使用面板：累计生成 3,429,823 行代码的时间分布](images/Snipaste_2026-07-02_18-02-39.png)
