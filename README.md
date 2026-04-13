<!-- HEADER BANNER -->
<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:040810,50:003320,100:040810&height=220&section=header&text=HARSH%20JHA&fontSize=72&fontColor=00ff88&animation=fadeIn&fontAlignY=40&desc=AI%20Systems%20Builder%20%E2%80%94%20Architecture%20Focused&descAlignY=65&descSize=17&descColor=4a9e6e&stroke=00ff88&strokeWidth=1)

<!-- TYPING ANIMATION -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2800&pause=900&color=00FF88&background=00000000&center=true&vCenter=true&multiline=false&repeat=true&width=680&height=40&lines=Building+AI+systems+that+work+in+real+conditions;Not+demos.+Not+prototypes.+Production+pipelines.;Input+%E2%86%92+Processing+%E2%86%92+Model+%E2%86%92+Validation+%E2%86%92+Output;If+a+system+fails+outside+controlled+conditions%2C+it+is+incomplete.)](https://git.io/typing-svg)

<br/>

![Status](https://img.shields.io/badge/%E2%97%8F%20STATUS-OPEN%20TO%20INTERNSHIPS-00ff88?style=for-the-badge&labelColor=040810&color=003320)
&nbsp;
![Focus](https://img.shields.io/badge/FOCUS-AI%20%2F%20BACKEND%20%2F%20PRODUCT-ffc857?style=for-the-badge&labelColor=040810&color=2a1f00)
&nbsp;
![Location](https://img.shields.io/badge/LOCATION-INDIA-00aaff?style=for-the-badge&labelColor=040810&color=001e33)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-hrshjha-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hrshjha)
&nbsp;
[![X](https://img.shields.io/badge/X%20%2F%20Twitter-@m__eharsh-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/m_eharsh)

</div>

---

## `$ whoami`

```python
harsh_jha = {
    "role"        : "AI Systems Builder — Intern-level, Architecture-focused",
    "positioning" : "End-to-end AI pipelines · Validated outputs · Real-world constraints",
    "identity"    : "I transform unstructured input into decision-ready outputs.",

    "strict_rules": [
        "No demo-only systems",
        "No blind trust in model outputs",
        "No pipelines that break under noise",
        "Every system must handle imperfect input and uncertain outputs",
    ],

    "rule" : "If a system fails outside controlled conditions — it is incomplete."
}
```

---

## `$ cat core_thesis.md`

> Most projects stop at **"model works"**.
>
> I build systems that answer:
>
> — How does it handle **noisy input**?  
> — How is output **validated**, not assumed correct?  
> — What breaks under **latency or compute constraints**?  
> — Does it work **outside controlled environments**?

---

## `$ visualize pipeline`

```mermaid
flowchart LR
    A(["🎙️  RAW INPUT\nnoise · voice · text"]):::input
    B(["⚙️  PROCESSING\nparsing · features"]):::stage
    C(["🧠  MODEL\ninference · predict"]):::stage
    D(["✅  VALIDATION\nNLI · scoring · verify"]):::validate
    E(["📤  OUTPUT\nstructured · reliable"]):::output

    A --> B --> C --> D --> E

    classDef input    fill:#003320,stroke:#00ff88,color:#00ff88
    classDef stage    fill:#0b1628,stroke:#1a3550,color:#c9d8e8
    classDef validate fill:#1f1500,stroke:#ffc857,color:#ffc857
    classDef output   fill:#001e33,stroke:#00aaff,color:#00aaff
```

| Stage | What I Actually Build |
|:---|:---|
| `RAW INPUT` | Voice audio, noisy text, unstructured real-world data |
| `PROCESSING` | Parsing, preprocessing, feature extraction layers |
| `MODEL` | ML inference, LLM generation, prediction pipelines |
| `VALIDATION` | NLI verification, scoring, claim-level checks — no blind trust |
| `OUTPUT` | Structured, decision-ready, verified results |

---

## `$ ls projects/`

<details>
<summary><b>📡 &nbsp;AgriMind — Voice-Based Crop Recommendation System</b></summary>
<br/>

**Problem**
> Crop advisory systems fail in real-world conditions — manual input, no accessibility, zero tolerance for noisy environments.

**System Architecture**

```mermaid
flowchart LR
    A(["🎙️ Speech\nInput"]):::g --> B(["🔧 Parsing\n& Preprocessing"]):::n --> C(["🔢 Feature\nExtraction"]):::n --> D(["🌱 RandomForest\nML Model"]):::g --> E(["🔊 Voice\nOutput"]):::g
    classDef g fill:#003320,stroke:#00ff88,color:#00ff88
    classDef n fill:#0b1628,stroke:#1a3550,color:#c9d8e8
```

**Engineering Highlights**

```diff
+ Built speech-first pipeline — voice is the interface, not a fallback
+ Converts unstructured audio → structured feature vectors for ML
+ Handles noisy, imperfect voice input via custom preprocessing layers
+ Backend-controlled TTS → eliminates cross-browser inconsistency
+ Solved audio encoding + latency constraints under CPU limits
+ Works under real conditions — not just clean benchmark datasets
```

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
&nbsp;`RandomForest` &nbsp;`Whisper` &nbsp;`pyttsx3`

<br/>
</details>

---

<details>
<summary><b>🔍 &nbsp;Hallucination Hunter — Claim-Level LLM Verification System</b></summary>
<br/>

**Problem**
> LLMs generate fluent but partially wrong outputs. Most systems only catch total failure — not **partial hallucinations**.

**System Architecture**

```mermaid
flowchart LR
    A(["📝 LLM\nOutput"]):::a --> B(["✂️ Claim\nDecomposition"]):::n --> C(["🧠 NLI\nVerification"]):::a --> D(["📊 Multi-signal\nScoring"]):::w --> E(["📤 Verified\nOutput"]):::g
    classDef a fill:#003320,stroke:#00ff88,color:#00ff88
    classDef n fill:#0b1628,stroke:#1a3550,color:#c9d8e8
    classDef w fill:#1f1500,stroke:#ffc857,color:#ffc857
    classDef g fill:#001e33,stroke:#00aaff,color:#00aaff
```

**Engineering Highlights**

```diff
+ Atomic claim decomposition via linguistic parsing — not bulk response matching
+ NLI (entailment / contradiction) — not surface-level similarity checks
+ Multi-signal validation: semantic similarity + classification combined
+ Detects partial hallucinations — not just binary pass / fail
+ Modular pipeline — every stage independently replaceable
+ Interpretability layer: each claim mapped to supporting evidence
```

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
&nbsp;`DeBERTa-v3` &nbsp;`spaCy` &nbsp;`XGBoost`

<br/>
</details>

---

## `$ cat skills.sh`

<div align="center">

[![Skills](https://skillicons.dev/icons?i=python,fastapi,pytorch,tensorflow,sklearn,js,html,css&theme=dark&perline=8)](https://skillicons.dev)

</div>

<br/>

```bash
CORE        →  python  fastapi  machine-learning  nlp

AI SYSTEMS  →  llm-integration  prompt-engineering
               validation-pipelines  output-structuring

MODELS      →  scikit-learn  transformers  spacy  xgboost
               feature-engineering  inference-pipelines

FRONTEND    →  html  css  javascript

CURRENT     →  latency-optimization  llm-verification
               production-deployment  eval-benchmarking
```

---

## `$ cat approach.diff`

```diff
- scripts            +  SYSTEMS
- accuracy metrics   +  RELIABILITY  
- curated datasets   +  REAL-WORLD INPUT
- shortcuts          +  ARCHITECTURE
```

---

## `$ github --stats`

<p align="center">

  <img height="165" src="https://github-readme-stats.vercel.app/api?username=hrshjha&show_icons=true&hide_border=true&theme=github_dark&cache_seconds=86400" />
  
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hrshjha&layout=compact&hide_border=true&theme=github_dark&cache_seconds=86400" />

</p>

<p align="center">

  <img src="https://streak-stats.demolab.com?user=hrshjha&theme=github-dark&hide_border=true&cache_seconds=86400" />

</p>

<p align="center">

  <img src="https://github-profile-trophy.vercel.app/?username=hrshjha&theme=darkhub&no-frame=true&margin-w=6&column=6" />

</p>

---

## `$ cat looking_for.txt`

```
TARGET  →  AI / Backend / Product Engineering Internship

BRINGS  →  System-level thinking
        →  Pipeline design — not just models
        →  Ships working, integrated, production-ready systems

LINKS   →  github.com/hrshjha
        →  x.com/m_eharsh
```

---

<!-- FOOTER -->
<div align="center">

<br/>

*This is not a collection of projects.*<br/>
*It is a direction —*<br/>
**Building AI systems that work under real conditions, not ideal ones.**

<br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:040810,50:003320,100:040810&height=120&section=footer)

</div>
