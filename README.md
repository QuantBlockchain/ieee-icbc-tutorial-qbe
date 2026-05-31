<div style="text-align:center; padding:30px 20px; background:linear-gradient(135deg, rgba(31,111,235,0.08) 0%, rgba(16,185,129,0.08) 100%); border-radius:16px; margin-bottom:30px; border:1px solid rgba(31,111,235,0.2);">

# ⚛️ QBE Tutorial — IEEE ICBC 2026
##  Blockchain Infrastructure for Intelligent Cyber-Physical-Social Systems: Post-Quantum Security, Interoperability, and Trustworthy Data Economies in the Era of Embodied AI

<p style="font-size:1.1rem; color:#1f6feb; font-weight:600; letter-spacing:0.5px;">
  
  <strong>Q</strong>uantum Security • <strong>B</strong>lockchain Infrastructure • <strong>E</strong>mbodied AI
</p>

</div>

<p align="center" style="margin:30px 0;">
  <a href="https://nextjs.org" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white" alt="Next.js" />
  </a>
  <a href="https://aws.amazon.com/braket/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/AWS%20Braket-FF9900?logo=amazon-aws&logoColor=white" alt="AWS Braket" />
  </a>
  <a href="https://aws.amazon.com/cdk/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/AWS%20CDK-232F3E?logo=aws&logoColor=white" alt="AWS CDK" />
  </a>
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
  </a>
  <a href="./LICENSE" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/License-MIT-brightgreen" alt="MIT License" />
  </a>
</p>

<div style="text-align:center; margin:40px 0;">
  <img src="https://raw.githubusercontent.com/QuantBlockchain/ieee-icbc-tutorial-qbe/main/Roadmap/QBE.png" alt="QBE Framework Roadmap" style="width:100%; max-width:900px; border-radius:12px; box-shadow:0 20px 60px rgba(0,0,0,0.15); border:2px solid rgba(31,111,235,0.2);">
</div>

<div style="display:flex; flex-wrap:wrap; justify-content:center; gap:12px; margin:40px 0; padding:30px 20px; background:linear-gradient(180deg, rgba(255,255,255,0.5), rgba(31,111,235,0.03)); border-radius:16px;">
  <a href="#-tutorial-information" style="display:inline-flex; align-items:center; gap:8px; padding:12px 18px; background:linear-gradient(135deg,#1f6feb,#0a58ca); color:#ffffff; text-decoration:none; border-radius:999px; font-weight:700; font-size:0.95rem; box-shadow:0 4px 15px rgba(31,111,235,0.35); border:1px solid rgba(255,255,255,0.2); transition:all 0.3s ease;">📋 Overview</a>
  <a href="#-speakers" style="display:inline-flex; align-items:center; gap:8px; padding:12px 18px; background:linear-gradient(135deg,#8b5cf6,#7c3aed); color:#ffffff; text-decoration:none; border-radius:999px; font-weight:700; font-size:0.95rem; box-shadow:0 4px 15px rgba(139,92,246,0.35); border:1px solid rgba(255,255,255,0.2); transition:all 0.3s ease;">👥 Speakers</a>
  <a href="#-agenda" style="display:inline-flex; align-items:center; gap:8px; padding:12px 18px; background:linear-gradient(135deg,#1f6feb,#0a58ca); color:#ffffff; text-decoration:none; border-radius:999px; font-weight:700; font-size:0.95rem; box-shadow:0 4px 15px rgba(31,111,235,0.35); border:1px solid rgba(255,255,255,0.2); transition:all 0.3s ease;">📅 Agenda</a>
  <a href="#-additional-materials" style="display:inline-flex; align-items:center; gap:8px; padding:12px 18px; background:linear-gradient(135deg,#10b981,#059669); color:#ffffff; text-decoration:none; border-radius:999px; font-weight:700; font-size:0.95rem; box-shadow:0 4px 15px rgba(16,185,129,0.35); border:1px solid rgba(255,255,255,0.2); transition:all 0.3s ease;">📚 Materials</a>
  <a href="#-repository-structure" style="display:inline-flex; align-items:center; gap:8px; padding:12px 18px; background:linear-gradient(135deg,#f59e0b,#d97706); color:#ffffff; text-decoration:none; border-radius:999px; font-weight:700; font-size:0.95rem; box-shadow:0 4px 15px rgba(245,158,11,0.35); border:1px solid rgba(255,255,255,0.2); transition:all 0.3s ease;">🗂️ Repo</a>
</div>
  <a href="#-m0-opening-demo" style="display:inline-flex; align-items:center; gap:6px; padding:8px 14px; background:linear-gradient(135deg,#1f6feb,#0a58ca); color:#fff; text-decoration:none; border-radius:999px; font-weight:600; font-size:0.85rem; box-shadow:0 2px 8px rgba(31,111,235,0.3);">🎬 M0</a>
  <a href="#-m1-embodied-ai--world-models" style="display:inline-flex; align-items:center; gap:6px; padding:8px 14px; background:linear-gradient(135deg,#ec4899,#db2777); color:#fff; text-decoration:none; border-radius:999px; font-weight:600; font-size:0.85rem; box-shadow:0 2px 8px rgba(236,72,153,0.3);">🤖 M1</a>
  <a href="#-m2-quantum-hardware-threat" style="display:inline-flex; align-items:center; gap:6px; padding:8px 14px; background:linear-gradient(135deg,#8b5cf6,#7c3aed); color:#fff; text-decoration:none; border-radius:999px; font-weight:600; font-size:0.85rem; box-shadow:0 2px 8px rgba(139,92,246,0.3);">⚛️ M2</a>
  <a href="#-m3-scalable-architecture" style="display:inline-flex; align-items:center; gap:6px; padding:8px 14px; background:linear-gradient(135deg,#10b981,#059669); color:#fff; text-decoration:none; border-radius:999px; font-weight:600; font-size:0.85rem; box-shadow:0 2px 8px rgba(16,185,129,0.3);">⛓️ M3</a>
  <a href="#-m4-trustworthy-data-economies" style="display:inline-flex; align-items:center; gap:6px; padding:8px 14px; background:linear-gradient(135deg,#f59e0b,#d97706); color:#fff; text-decoration:none; border-radius:999px; font-weight:600; font-size:0.85rem; box-shadow:0 2px 8px rgba(245,158,11,0.3);">💎 M4</a>
  <a href="#-m5-industry-ecosystem" style="display:inline-flex; align-items:center; gap:6px; padding:8px 14px; background:linear-gradient(135deg,#06b6d4,#0891b2); color:#fff; text-decoration:none; border-radius:999px; font-weight:600; font-size:0.85rem; box-shadow:0 2px 8px rgba(6,182,212,0.3);">🏢 M5</a>
</div>

---

<div style="padding:30px; background:linear-gradient(135deg, rgba(139,92,246,0.1), rgba(236,72,153,0.1)); border-radius:16px; border-left:6px solid #8b5cf6; margin:40px 0;">
  <p style="font-size:1.1rem; line-height:1.8; color:#333; margin:0;">
    <strong style="color:#8b5cf6;">⚛️ Quantum Security</strong> + <strong style="color:#10b981;">⛓️ Blockchain Infrastructure</strong> + <strong style="color:#ec4899;">🤖 Embodied AI</strong>
  </p>
  <p style="font-size:1rem; line-height:1.8; color:#555; margin:15px 0 0 0;">
    A unified framework for architecting quantum-resistant, interoperable, and data-trustworthy <strong>Cyber-Physical-Social Systems (CPSS)</strong>.
  </p>
</div>

---

## 📋 Tutorial Information

<div style="overflow-x:auto; margin:30px 0;">
<table style="width:100%; border-collapse:collapse; background:linear-gradient(180deg, #f9fafb, #ffffff);">
<thead>
<tr style="background:linear-gradient(135deg, #1f6feb, #0a58ca); color:white;">
<th style="padding:14px; text-align:left; font-weight:700; border:1px solid #ddd;">📍 Conference</th>
<th style="padding:14px; text-align:left; font-weight:700; border:1px solid #ddd;">📅 Dates</th>
<th style="padding:14px; text-align:left; font-weight:700; border:1px solid #ddd;">🌏 Location</th>
<th style="padding:14px; text-align:left; font-weight:700; border:1px solid #ddd;">⏱️ Duration</th>
<th style="padding:14px; text-align:left; font-weight:700; border:1px solid #ddd;">🔗 Website</th>
</tr>
</thead>
<tbody>
<tr style="background:#ffffff; border-bottom:1px solid #e5e7eb;">
<td style="padding:14px; border:1px solid #ddd; color:#1f6feb; font-weight:600;">IEEE ICBC 2026</td>
<td style="padding:14px; border:1px solid #ddd; color:#10b981; font-weight:600;">June 1–5, 2026</td>
<td style="padding:14px; border:1px solid #ddd; color:#f59e0b; font-weight:600;">Brisbane, Australia</td>
<td style="padding:14px; border:1px solid #ddd; color:#8b5cf6; font-weight:600;">2 hours</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="https://icbc2026.ieee-icbc.org/program-schedule" target="_blank" rel="noopener noreferrer" style="color:#1f6feb; text-decoration:none; font-weight:600;">ICBC 2026 Schedule →</a></td>
</tr>
</tbody>
</table>
</div>

---

## 📚 Additional Materials

<div style="padding:24px; background:linear-gradient(135deg, rgba(16,185,129,0.08), rgba(16,185,129,0.02)); border:1px solid rgba(16,185,129,0.3); border-radius:12px; border-left:4px solid #10b981;">
  <ul style="margin:0; padding-left:24px; line-height:2;">
    <li><strong>📁 blockchain-journal-calls/</strong> — Conference journal call collateral and booklet assets
      <ul style="margin-top:8px; padding-left:24px;">
        <li><code style="background:#f0f0f0; padding:2px 6px; border-radius:4px;">MDPI- Blockchains.pdf</code></li>
        <li><code style="background:#f0f0f0; padding:2px 6px; border-radius:4px;">SI-List-Flyer-A5-Blockchains.pdf</code></li>
        <li><code style="background:#f0f0f0; padding:2px 6px; border-radius:4px;">blockchainsJournalBookletPrint.pdf</code></li>
      </ul>
    </li>
  </ul>
</div>

---

## 👥 Speakers

<div style="display:grid; grid-template-columns:1fr; gap:40px; margin:40px 0;">

Prof. Song Guo

<p>
<img src=“https://raw.githubusercontent.com/QuantBlockchain/ieee-icbc-tutorial-qbe/main/headshots/SongGuo.JPEG” align=“left” width=“140” hspace=“15” vspace=“5”>
Song Guo is a Chair Professor at the Department of Computer Science and Engineering, Hong Kong University of Science and Technology (HKUST). He also holds a Changjiang Chair Professorship awarded by the Ministry of Education of China. His research focuses on Large Language Models, Edge AI, and Machine Learning Systems. A Highly Cited Researcher, he has received over a dozen Best Paper Awards and the Edward J. McCluskey Technical Achievement Award (2024), First Prize in Natural Science (China Electronics Society, 2023), and Gold Medals at Geneva Inventions Expo (2023, 2024). He is a Fellow of the Canadian Academy of Engineering, Member of Academia Europaea, Fellow of the IEEE, Distinguished Member of the ACM, and Fellow of the Asia-Pacific Artificial Intelligence Association. He served as IEEE Communications Society Distinguished Lecturer and Board of Governors member. He is Editor-in-Chief of IEEE Transactions on Cloud Computing and founding Editor-in-Chief of IEEE Open Journal of the Computer Society. He has chaired numerous IEEE/ACM conference committees, delivered 100+ keynotes, and serves as Secretary General of CCF Hong Kong.

Module: M1 – Embodied AI & World Models

<br clear=“left”/>

Prof. Huawei Huang

<p>
<img src=“https://raw.githubusercontent.com/QuantBlockchain/ieee-icbc-tutorial-qbe/main/headshots/HuaweiHuang.JPG” align=“left” width=“140” hspace=“15” vspace=“5”>
Huawei Huang received the Ph.D. degree from the University of Aizu, Japan, in 2016. He is a Future Professor at Sun Yat-sen University, with dual appointments at Lingnan College and the Hong Kong Institute of Advanced Studies. He previously served as a JSPS Research Fellow and Assistant Professor at Kyoto University. He is a recipient of the Guangdong Outstanding Young Scholar Fund, an IEEE Senior Member, and a CCF Senior Member. Since 2021, he has been listed in the Stanford University World’s Top 2% Scientists ranking. His research interests include high-performance blockchain systems, DeFi protocols, and Web3 infrastructures. He has published in top-tier venues such as IEEE ToN, JSAC, TPDS, INFOCOM, and WWW, with over 9,000 citations. He has served as chair for more than ten international conferences and led over ten national research projects, including the National Key R&D Program of China and NSFC programs. He has authored three academic books on blockchain, one textbook, and one popular science book. He leads the development of BlockEmulator, an open-source blockchain experimental platform supporting researchers in over 90 countries, and the BrokerChain project, which launched its Academic Testnet in June 2025.

Module: M3 – Scalable Architecture & Interoperability

<br clear=“left”/>

Dongping Liu, Ph.D.

<p>
<img src=“https://raw.githubusercontent.com/QuantBlockchain/ieee-icbc-tutorial-qbe/main/headshots/DongpingLiu.JPEG” align=“left” width=“140” hspace=“15” vspace=“5”>
Dongping Liu is the CEO of Tenorshare and a former Senior Industry Business Development Manager for Higher Education and Research at Amazon Web Services, where he specializes in driving digital transformation in academia through AI, deep learning, and high-performance computing solutions. With 15 years of experience in the higher education and research sector, he has successfully led the implementation of cutting-edge cloud technologies for educational institutions and research organizations. His expertise spans educational technology innovation, business development strategy, and large-scale research computing deployments. He has been awarded the First Prize of Beijing Science and Technology Award, published 30+ research papers, and obtained 10+ authorized patents along with multiple software copyrights. He contributes to this tutorial by bridging academic research needs with practical AWS cloud solutions and sharing insights on AI/HPC applications in higher education. He holds a Ph.D. in Physics from the Institute of Physics, Chinese Academy of Sciences, and completed postdoctoral research at McGill University, Canada.

Module: M5 – Industry Ecosystem Integration

<br clear=“left”/>

Aoyu Zhang, Ph.D.

<p>
<img src=“https://raw.githubusercontent.com/QuantBlockchain/ieee-icbc-tutorial-qbe/main/headshots/AoyuZhang.JPEG” align=“left” width=“140” hspace=“15” vspace=“5”>
Aoyu Zhang is Senior Applied Scientist at AWS China Solution Development Center, where he advances the design and implementation of AI and quantum cloud solutions. He used to develop open-source quantum computing solutions for drug discovery under Amazon Braket. His research also includes hybrid quantum-classical algorithms, quantum benchmarking, and cross-domain applications in blockchain security and Web-scale cryptography. He delivered the keynote at the 2025 forum on Cloud Computing Services for Blockchain Security and contributes to this tutorial by leading the quantum core and live Amazon Braket demonstrations. He holds a Ph.D. in Biomedical Engineering from Peking University.

Module: M2 – Quantum Hardware Threat Assessment

<br clear=“left”/>

Prof. Luyao Zhang

<p>
<img src=“https://raw.githubusercontent.com/QuantBlockchain/ieee-icbc-tutorial-qbe/main/headshots/LuyaoZhang.JPEG” align=“left” width=“140” hspace=“15” vspace=“5”>
Luyao Zhang is a tenure-track Assistant Professor of Economics and Senior Research Scientist at Duke Kunshan University. Her research bridges computational and economic sciences through groundbreaking technologies for intelligent economics, encompassing big data, blockchain, generative AI, and geospatial analysis, with publications in Review of Economics and Statistics, Scientific Data, ACM CCS, IEEE S&P, ACM CSCW, and NeurIPS Datasets and Benchmarks. She holds a Ph.D. from The Ohio State University (Presidential Fellowship, NSF support) and a B.A./B.S. dual degree from Peking University, with professional certificates from Oxford and MIT in blockchain, reinforcement learning, and quantum computing. Her NSFC-funded project “Trust Mechanism Design on Blockchain” integrates game theory, reinforcement learning, and human-AI interaction. She serves as Guest Editor for Electronic Markets, Editorial Board Member of Scientific Data and Blockchain: Research and Applications, Working Group Secretary for IEEE P3469, and Academic Editor of Blockchain – Pioneering the Web3 Infrastructure for an Intelligent Future (2025).

Module: M4 – Trustworthy Data Economies

<br clear=“left”/>



---

## 📅 Agenda

<div style="overflow-x:auto; margin:30px 0;">
<table style="width:100%; border-collapse:collapse; background:linear-gradient(180deg, #f9fafb, #ffffff);">
<thead>
<tr style="background:linear-gradient(135deg, #1f6feb, #0a58ca); color:white;">
<th style="padding:16px; text-align:left; font-weight:700; border:1px solid #ddd;">⏰ Segment</th>
<th style="padding:16px; text-align:left; font-weight:700; border:1px solid #ddd;">📚 Module</th>
<th style="padding:16px; text-align:left; font-weight:700; border:1px solid #ddd;">👤 Presenter</th>
<th style="padding:16px; text-align:left; font-weight:700; border:1px solid #ddd;">📖 Description</th>
</tr>
</thead>
<tbody>
<tr style="border-bottom:1px solid #e5e7eb;">
<td style="padding:14px; border:1px solid #ddd; font-weight:600; color:#1f6feb;">🎬 M0</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="#-m0-opening-demo" style="color:#1f6feb; text-decoration:none; font-weight:500;">Opening Demo</a></td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Dongping Liu, Aoyu Zhang, Luyao Zhang</td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Quantum-Web3-AI convergence via interactive applications</td>
</tr>
<tr style="background:rgba(236,72,153,0.03); border-bottom:1px solid #e5e7eb;">
<td style="padding:14px; border:1px solid #ddd; font-weight:600; color:#ec4899;">🤖 M1</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="#-m1-embodied-ai--world-models" style="color:#ec4899; text-decoration:none; font-weight:500;">Embodied AI & World Models</a></td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Song Guo (HKUST)</td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">IRASim, WMPO, bridge to blockchain</td>
</tr>
<tr style="border-bottom:1px solid #e5e7eb;">
<td style="padding:14px; border:1px solid #ddd; font-weight:600; color:#8b5cf6;">⚛️ M2</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="#-m2-quantum-hardware-threat" style="color:#8b5cf6; text-decoration:none; font-weight:500;">Quantum Hardware Threat</a></td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Aoyu Zhang (AWS)</td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">AWS Braket demo, PQC standards, threat timelines</td>
</tr>
<tr style="background:rgba(16,185,129,0.03); border-bottom:1px solid #e5e7eb;">
<td style="padding:14px; border:1px solid #ddd; font-weight:600; color:#10b981;">⛓️ M3</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="#-m3-scalable-architecture" style="color:#10b981; text-decoration:none; font-weight:500;">Scalable Architecture</a></td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Huawei Huang (SYSU)</td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">BlockEmulator, BrokerChain, cross-shard protocols</td>
</tr>
<tr style="border-bottom:1px solid #e5e7eb;">
<td style="padding:14px; border:1px solid #ddd; font-weight:600; color:#f59e0b;">💎 M4</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="#-m4-trustworthy-data-economies" style="color:#f59e0b; text-decoration:none; font-weight:500;">Trustworthy Data Economies</a></td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Luyao Zhang (DKU)</td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Croissant metadata, provenance, incentives</td>
</tr>
<tr style="background:rgba(6,182,212,0.03); border-bottom:1px solid #e5e7eb;">
<td style="padding:14px; border:1px solid #ddd; font-weight:600; color:#06b6d4;">🏢 M5</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="#-m5-industry-ecosystem" style="color:#06b6d4; text-decoration:none; font-weight:500;">Industry Ecosystem</a></td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Dongping Liu (Tenorshare)</td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Operationalizing trustworthy AI infrastructure</td>
</tr>
<tr style="background:rgba(31,111,235,0.05);">
<td style="padding:14px; border:1px solid #ddd; font-weight:600; color:#1f6feb;">🎯 Panel</td>
<td style="padding:14px; border:1px solid #ddd;"><a href="#-closing-panel" style="color:#1f6feb; text-decoration:none; font-weight:500;">Closing Synthesis</a></td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">All Speakers</td>
<td style="padding:14px; border:1px solid #ddd; font-size:0.9rem;">Integrated QBE roadmap and future directions</td>
</tr>
</tbody>
</table>
</div>

---

## 🎬 M0: Opening Demo

<div style="padding:24px; background:linear-gradient(135deg, rgba(31,111,235,0.08), rgba(31,111,235,0.02)); border:1px solid rgba(31,111,235,0.3); border-radius:12px; border-left:4px solid #1f6feb; margin:20px 0;">

**Quantum-Web3-AI Convergence** (~15 min)  
**Presenters:** Dongping Liu, Aoyu Zhang, Luyao Zhang

The opening demonstration establishes the empirical QBE framework through two interactive applications:

| 🔗 Application | 📝 Description | Links |
|:---|:---|:---|
| **QSignAI** | Post-quantum signature analysis and benchmarking for blockchain security | [🔗 GitHub](https://github.com/QuantBlockchain/QSignAI) / [📄 arXiv](https://arxiv.org/abs/2605.27729) |
| **Quantum Futures Interactive** | Interactive quantum computing exploration with cryptographic threat timelines | [🔗 GitHub](https://github.com/QuantBlockchain/qc-bc-interactive) / [📄 arXiv](https://arxiv.org/abs/2605.15991) |

> **📁 Folder:** `M0` — Upload opening demo slides and videos here.

</div>

---

## 🤖 M1: Embodied AI & World Models

<div style="padding:24px; background:linear-gradient(135deg, rgba(236,72,153,0.08), rgba(236,72,153,0.02)); border:1px solid rgba(236,72,153,0.3); border-radius:12px; border-left:4px solid #ec4899; margin:20px 0;">

**Presenter:** Prof. Song Guo (HKUST)  
**📁 Folder:** `M1`

> Presentation of edge-distributed AI and robotics systems, world-model-based architectures (IRASim), and the WMPO reinforcement learning framework — defining the target infrastructure that M2 must secure against quantum threats.

### 📑 Content Overview

| # | Topic | Key Points |
|:---|:---|:---|
| 01 | From Virtual to Physical AI | Generative vs. Embodied AI paradigm shift |
| 02 | Embodied Intelligence Fundamentals | Three elements (environment, body, intelligence); physical generalization challenge |
| 03 | IRASim World Model | Fine-grained video prediction for robot manipulation (ICCV 2025); 500M params matching 7B models |
| 04 | WMPO Algorithm | World Model-based Policy Optimization; 10-50x sample efficiency over GRPO |
| 05 | Future Outlook | Unified embodied foundation models; 3D spatial intelligence |

### 📚 Key References
- [3] Zhu et al., "IRASim: A Fine-Grained World Model for Robot Manipulation," ICCV 2025
- [4] Mon-Williams et al., "Embodied large language models enable robots," Nature MI 2025

</div>

---

## ⚛️ M2: Quantum Hardware Threat

<div style="padding:24px; background:linear-gradient(135deg, rgba(139,92,246,0.08), rgba(139,92,246,0.02)); border:1px solid rgba(139,92,246,0.3); border-radius:12px; border-left:4px solid #8b5cf6; margin:20px 0;">

**Presenter:** Aoyu Zhang (AWS)  
**📁 Folder:** `M2`

> Empirical analysis of quantum capabilities via AWS Braket and evidence-based post-quantum migration strategies. Determines the security requirements that M3 must address through scalable architectures.

| 🔬 Topic | 💡 Key Points |
|:---|:---|
| Quantum threat timeline | Shor & Grover impact on blockchain; 2029-2030 act-by window |
| Harvest-Now, Decrypt-Later | 30% of BTC (~$500B) has exposed public keys; blockchain is uniquely vulnerable |
| NIST PQC Standards | ML-KEM, ML-DSA, SLH-DSA, FN-DSA finalized Aug 2024 |
| AWS Braket Live Demo | Toy Shor circuits, Grover search, fidelity benchmarks on real QPUs |

</div>

---

## ⛓️ M3: Scalable Architecture

<div style="padding:24px; background:linear-gradient(135deg, rgba(16,185,129,0.08), rgba(16,185,129,0.02)); border:1px solid rgba(16,185,129,0.3); border-radius:12px; border-left:4px solid #10b981; margin:20px 0;">

**Presenter:** Prof. Huawei Huang (SYSU)  
**📁 Folder:** `M3`

> Demonstration of BrokerChain cross-shard protocols and cross-ledger coordination using BlockEmulator and BlockEmulator-X, providing the scalable foundation upon which M4 implements trustworthy data economies.

| 🏗️ Topic | 🎯 Key Points |
|:---|:---|
| BlockEmulator v1.0 | Open-source sharding testbed; 5-layer architecture; BrokerChain protocol |
| BlockEmulator-X (v2.0) | Ground-up rewrite; YAML config; gRPC networking; safer execution model |
| BrokerChain | Cross-shard protocol (INFOCOM 2022); 10,000+ TPS; broker accounts |
| Live Demo | `bash example_run.sh` — 4 shards × 4 nodes + 1 supervisor |

### 🔗 Key Resources
- [BlockEmulator GitHub](https://github.com/HuangLab-SYSU/BlockEmulator)
- [BrokerChain GitHub](https://github.com/HuangLab-SYSU/BrokerChain)

</div>

---

## 💎 M4: Trustworthy Data Economies

<div style="padding:24px; background:linear-gradient(135deg, rgba(245,158,11,0.08), rgba(245,158,11,0.02)); border:1px solid rgba(245,158,11,0.3); border-radius:12px; border-left:4px solid #f59e0b; margin:20px 0;">

**Presenter:** Prof. Luyao Zhang (Duke Kunshan University)  
**📁 Folder:** `M4`

> Implementation of Croissant metadata standards for ML-ready datasets, security analysis of blockchain interoperability mechanisms, and blockchain provenance for Ethereum Beacon Chain and Uniswap data.

### 📑 Content Overview

| # | Topic | 🔑 Key Points |
|:---|:---|:---|
| 01 | The Data Trust Problem | Data pipeline challenges in CPSS |
| 02 | Croissant Metadata | ML-ready dataset standard (NeurIPS 2024); JSON-LD specification; robotics practice |
| 03 | Blockchain Provenance | Ethereum Beacon Chain framework (Sci. Data 2025); Uniswap economic indices; provenance architecture |
| 04 | Interoperability Security | SoK on cross-chain security (IEEE S&P 2024); cross-ledger data exchange protocols |
| 05 | Incentive Mechanisms | Token-based data quality design; PoS incentive redesign (DOCS 2024) |

### 📚 Key References
- [8] Akhtar et al., "Croissant: A metadata format for ML-ready datasets," NeurIPS 2024
- [12] Augusto et al., "SoK: Security and privacy of blockchain interoperability," IEEE S&P 2024
- [13] Yan et al., "A data engineering framework for Ethereum beacon chain rewards," Scientific Data 2025
- [14] Chemaya et al., "A dataset of Uniswap daily transaction indices," Scientific Data 2025
- [15] Tian et al., "Redesign incentives in proof-of-stake Ethereum," DOCS 2024

</div>

---

## 🏢 M5: Industry Ecosystem

<div style="padding:24px; background:linear-gradient(135deg, rgba(6,182,212,0.08), rgba(6,182,212,0.02)); border:1px solid rgba(6,182,212,0.3); border-radius:12px; border-left:4px solid #06b6d4; margin:20px 0;">

**Presenter:** Dongping Liu (Tenorshare)  
**📁 Folder:** `M5`

> Operationalization of cloud infrastructure and multi-modal data deployment for embodied AI, completing the pipeline from theoretical security to production-ready CPSS infrastructure.

| 🏛️ Topic | 🎯 Key Points |
|:---|:---|
| Three-layer architecture | AI Agent Execution (AWS) + Blockchain Trust & Audit + Post-Quantum Security |
| AWS open-source stack | AgentSquad, Strands SDK, NovaAct, Bedrock AgentCore |
| Blockchain audit bridge | MCP-based agent-to-chain integration with PQ signatures |
| Docker deployment | Open-source, reproducible, one-command setup |
| Enterprise validation | 670-person team deployment at Tenorshare |

</div>

---

## 🎯 Closing Panel

<div style="padding:24px; background:linear-gradient(135deg, rgba(31,111,235,0.08), rgba(31,111,235,0.02)); border:1px solid rgba(31,111,235,0.3); border-radius:12px; border-left:4px solid #1f6feb; margin:20px 0;">

**Integrated QBE Roadmap** — All Speakers

The closing panel synthesizes five modules into a unified CPSS strategy and future research agenda.

| 🎯 Pillar | 🛠️ Technology | 📊 Outcome |
|:---|:---|:---|
| **Quantum Security** | Crypto-agile migration, AWS Braket validation | Long-term threat resilience |
| **Embodied AI** | World models (IRASim, WMPO) | 10-50x data cost reduction |
| **Scalable Architecture** | BrokerChain cross-shard protocol | 10,000+ TPS throughput |
| **Trustworthy Data** | Croissant + provenance + incentives | Discoverable, traceable, secure data |
| **Industry Integration** | Open-source Docker stack | Production-ready deployment |

### 🌟 The QBE Vision

<p style="padding:16px; background:linear-gradient(135deg, rgba(236,72,153,0.1), rgba(139,92,246,0.1)); border-radius:8px; border-left:4px solid #ec4899; font-style:italic; font-size:1.05rem; line-height:1.8; color:#333;">
  A unified infrastructure where quantum-resistant security, scalable coordination, and trustworthy data economies jointly power next-generation <strong>Cyber-Physical-Social Systems</strong>.
</p>

</div>

---

## 🗂️ Repository Structure

<div style="background:linear-gradient(135deg, rgba(31,111,235,0.05), rgba(139,92,246,0.05)); border:1px solid rgba(31,111,235,0.2); border-radius:12px; padding:20px; margin:30px 0; font-family:'Courier New', monospace; font-size:0.9rem; line-height:1.6; overflow-x:auto;">

```
ieee-icbc-tutorial-qbe/
│
├─ 📄 README.md                # This file
├─ 📜 LICENSE                  # MIT License
│
├─ 📸 headshots/               # Speaker headshot photos
│  ├─ SongGuo.JPEG
│  ├─ HuaweiHuang.JPG
│  ├─ DongpingLiu.JPEG
│  ├─ AoyuZhang.JPEG
│  └─ LuyaoZhang.JPEG
│
├─ 🎨 Roadmap/                 # QBE framework roadmap illustration
│  └─ QBE.png
│
├─ 📚 blockchain-journal-calls/  # Journal call collateral and booklet
│  ├─ MDPI- Blockchains.pdf
│  ├─ SI-List-Flyer-A5-Blockchains.pdf
│  └─ blockchainsJournalBookletPrint.pdf
│
├─ 🎬 M0/                      # Opening Demo: Quantum-Web3-AI
│  └─ (slides, videos)
│
├─ 🤖 M1/                      # Embodied AI & World Models
│  └─ (slides, videos)
│
├─ ⚛️  M2/                      # Quantum Hardware Threat Assessment
│  └─ (slides, videos)
│
├─ ⛓️  M3/                      # Scalable Architecture & Interoperability
│  └─ (slides, videos)
│
├─ 💎 M4/                      # Trustworthy Data Economies
│  └─ (slides, videos)
│
└─ 🏢 M5/                      # Industry Ecosystem Integration
   └─ (slides, videos)
```

</div>

> **📝 Note:** Each `M0` through `M5` folder should contain the presenter's slides (PPT/PDF) and any recorded video materials for that module.

---

## 📖 Citation

<div style="background:#f5f5f5; border:1px solid #ddd; border-radius:8px; padding:20px; overflow-x:auto; font-family:'Courier New', monospace; font-size:0.85rem; line-height:1.6;">

```bibtex
@inproceedings{guo2026qbe,
  title={Blockchain Infrastructure for Intelligent Cyber--Physical--Social 
         Systems: Post-Quantum Security, Interoperability, and Trustworthy 
         Data Economies in the Era of Embodied {AI}},
  author={Guo, Song and Huang, Huawei and Liu, Dongping and Zhang, Aoyu 
          and Zhang, Luyao},
  booktitle={IEEE International Conference on Blockchain and Cryptocurrency 
             (ICBC)},
  year={2026},
  note={Tutorial, June 1--5, 2026, Brisbane, Australia}
}
```

</div>

---

## 📜 License

<div style="padding:20px; background:linear-gradient(135deg, rgba(16,185,129,0.08), rgba(16,185,129,0.02)); border:1px solid rgba(16,185,129,0.3); border-radius:12px; border-left:4px solid #10b981;">

This project is licensed under the <strong>MIT License</strong> — see the <a href="./LICENSE" style="color:#10b981; text-decoration:none; font-weight:600;">LICENSE</a> file for details.

</div>

---

<div style="text-align:center; padding:40px 20px; margin:40px 0 0 0; background:linear-gradient(135deg, rgba(31,111,235,0.08) 0%, rgba(16,185,129,0.08) 100%); border-top:2px solid rgba(31,111,235,0.3); border-radius:0 0 16px 16px;">
  <p style="font-size:1.2rem; font-weight:700; color:#1f6feb; margin:0 0 10px 0;">⚛️ • ⛓️ • 🤖</p>
  <p style="font-size:1.1rem; font-weight:600; color:#333; margin:0 0 5px 0;">QBE Tutorial</p>
  <p style="font-size:0.95rem; color:#666; margin:0;">IEEE International Conference on Blockchain and Cryptocurrency 2026</p>
  <p style="font-size:0.9rem; color:#888; margin:10px 0 0 0;">June 1–5, 2026 • Brisbane, Australia</p>
</div>
