![preview](https://raw.githubusercontent.com/SaketDronamraju/AutoLabel-Forge/main/cover_1527311.svg)
[![Download](https://raw.githubusercontent.com/SaketDronamraju/AutoLabel-Forge/main/start_368490.svg)](https://SaketDronamraju.github.io/AutoLabel-Forge/)

# 🧠 PromptForge — The Semantic Alchemy Engine for Dataset Generation

**Transform raw ideas into structured, labeled datasets using LLM-driven prompt decomposition and recombination.**

---

## 🌟 Why PromptForge Exists

Most dataset creation tools force you to think like a machine — rigid schemas, manual tagging, and endless CSV wrangling. PromptForge flips the paradigm. Instead of *you* adapting to the tool, the tool adapts to *your* language.

Inspired by the philosophy that **every object, concept, or phenomenon can be decomposed into atomic semantic components and reassembled into rich, labeled data**, PromptForge acts as a **linguistic forge** — melting down natural language prompts into elemental parts, then alloying them into new, diverse, and highly specific training examples.

Think of it as **alchemy for data scientists**: you provide the philosophical "prima materia" (a single prompt or concept), and PromptForge transmutes it into gold-standard labeled datasets.

---

## 🚀 The Core Innovation: Deconstruct → Recombine → Label

### 🔬 Phase 1: Semantic Deconstruction
PromptForge doesn't just read your prompt — it **dissects** it. Using advanced LLM agents, the engine breaks your input down into:
- **Entities** (the "what")
- **Attributes** (the "how")
- **Relationships** (the "why")
- **Contexts** (the "where/when")
- **Intentions** (the "purpose")

### ⚗️ Phase 2: Generative Recombination
This is where the magic happens. The engine applies **combinatorial explosion** to recombine those atomic parts into new, meaningful variations. It's not random noise — it's **guided stochasticity** that respects the original semantic boundaries while exploring the latent space of possibilities.

Output variations include:
- ✅ **Paraphrased versions** (linguistic diversity)
- ✅ **Contextual shifts** (e.g., changing "a dog" to "a golden retriever in a park")
- ✅ **Attribute negation** (e.g., "a car" → "a car without a roof")
- ✅ **Cross-domain adaptation** (e.g., "a knife" → "a surgical scalpel")

### 🏷️ Phase 3: Intelligent Auto-Labeling
Every generated example receives:
- **Multi-format labels** (JSON, YAML, CSV-ready)
- **Confidence scores** for LLM uncertainty
- **Human-review checkpoint suggestions**
- **Schema detection** — PromptForge infers the ideal label structure from the data itself

---

## 🌍 Supports "Everything Under the Sun"

PromptForge is **domain-agnostic** by design:

| Domain | Example Prompt | Generated Dataset Size |
|--------|----------------|----------------------|
| 🌿 Botany | "Describe a leaf's vein patterns" | 1,200+ labeled leaf illustrations |
| 🏦 Finance | "Explain compound interest scenarios" | 850+ risk-labeled case studies |
| 🎮 Gaming | "Identify RPG character classes" | 2,400+ class/attribute combos |
| 🏥 Healthcare | "Classify symptom clusters" | 1,800+ diagnostic triage examples |
| 🌌 Astronomy | "Categorize exoplanet types" | 600+ spectral/type labels |

The engine **self-learns** your domain vocabulary from the first prompt and adapts its decomposition strategy accordingly.

---

## ✨ Feature Highlights

### 🧩 Adaptive Semantic Graph
Every prompt builds a **visual knowledge graph** of entities and relationships. Watch in real-time as your concepts connect, and drag nodes to manually adjust the recombination space.

### 🌐 Multilingual Semantic Core
PromptForge delivers **native-quality dataset generation in 40+ languages** — including low-resource languages like Swahili, Icelandic, and Basque. The decomposition engine detects the *cultural context* of idioms and metaphors, not just literal translations.

### ⚡ Recombination Reservoir
A built-in **diversity meter** ensures your dataset doesn't collapse into near-duplicates. PromptForge maintains a "reservoir" of generated samples and actively rejects those with cosine similarity above your threshold.

### 🛠️ Custom Forge Recipes
Advanced users can write **recipe files** (JSON/YAML) that define:
- Custom entity extraction rules
- Recombination mutation rates
- Label taxonomy structures
- Review workflow checkpoints

### 📊 Enterprise-Grade Export Studio
Export your forge output directly to:
- **Hugging Face Datasets** format
- **LangChain** compatible structure
- **Pandas** (already vectorized)
- **Parquet** / **Arrow** for distributed training

### 👁️ Visual Annotation Review Board
A **two-pane inspector** shows the original prompt vs. the generated variation side-by-side, with highlighted semantic changes — making human-in-the-loop verification a breeze.

---

## 🧰 How It Works (Technical Overview)

### The Semantic Decomposer Engine
```
Input Prompt
    ↓
[LLM Agent A: Entity Extraction]
    ↓
[LLM Agent B: Relationship Mapping]
    ↓
[LLM Agent C: Context Vectorization]
    ↓
[Semantic Atom Graph]
```

### The Recombination Core
```
Semantic Atom Graph
    ↓
[Genetic Algorithm with LLM Mutation]
    ↓
[Constraint Satisfaction Filter]
    ↓
[Novelty Detector (Similarity Check)]
    ↓
[New Example Pool]
```

### The Label Synthesizer
```
New Example Pool
    ↓
[Schema Inference from First 10 Samples]
    ↓
[Label Generation with Confidence]
    ↓
[Human Review Integration]
    ↓
[Export Ready]
```

---

## 🕰️ 24/7 Ambient Support Loop

PromptForge includes an **always-on semantic watchdog** that:
- **Automatically detects data drift** — if your generated dataset starts becoming repetitive, it alerts you
- **Proactively suggests recipe tweaks** based on your success metrics
- **Monitors token usage** so you never hit surprise API limits

Our global support rotation ensures **human-assisted troubleshooting** within minutes — not days.

---

## 📁 Project Anatomy

```
promptforge/
├── forge_core/          # The semantic decomposition & recombination engines
│   ├── decomposer/
│   ├── recombiner/
│   └── label_synth/
├── recipe_library/     # Curated recipes for common domaines
│   ├── medical_imaging/
│   ├── legal_text/
│   └── sensor_reading/
├── ui_dashboard/       # React-based visual interface
├── cli_tool/           # Headless mode for CI/CD pipelines
└── test_suite/         # Unit & integration tests
```

---

## 🧪 Try It: A Live Example

**Input Prompt:**
> "A coffee cup on a wooden table in a rustic cafe"

**Decomposed Atoms:**
- *Entity:* cup, table, cafe
- *Attribute:* wooden, rustic
- *Context:* cafe environment
- *Material:* ceramic, wood, brick

**Recombined Variations (Sample):**
1. "An espresso cup on a walnut counter in a brick-walled café"
2. "A glass mug on a bamboo table on a café terrace"  
3. "A cracked porcelain cup on a pine table in a log cabin café"
4. "A 3D-rendered cup on a floating table in a virtual café"

**Generated Labels:**
```yaml
- entity: cup
  material: ceramic
  table_type: wooden
  environment: rustic_cafe
  lighting: warm_indoor
  novelty_score: 0.87
```

---

## 📌 Use Cases That Shine

### 🎓 Academic Research
Generate synthetic data for **underrepresented minority groups** in your training set — without privacy concerns. PromptForge creates *plausible* variations that your model hasn't seen.

### 🏢 Enterprise Data Teams
When your production data is sparse, PromptForge **bridges the gap** between what you have and what you need. Forge 10,000 labeled examples in an afternoon from a single afternoon's brainstorming session.

### 🕵️ Platform Content Moderation
Create adversarial examples by recombining toxic phrases into **novel offensive patterns** — staying ahead of content policy violations.

### 🎨 Creative AI Projects
Train diffusion models on **ultra-specific prompts** like "a cyberpunk garden gnome riding a hoverboard during a neon rainstorm" — and let PromptForge explore 500 variations of that aesthetic.

---

## ⚠️ Important Disclaimers

### 🧊 Cooling Period Notice
While PromptForge generates *highly plausible* data, **it does not replace ground truth**. Always maintain a **human review checkpoint** for any dataset going into production. The confidence scores provided are heuristic, not absolute.

### 🛡️ Ethical Use Policy
PromptForge respects existing copyright structures. Use it only on:
- Your own original prompts
- Open-licensed source materials
- Public domain concepts

Do **not** attempt to use PromptForge to reverse-engineer proprietary datasets or bypass access controls.

### 📈 Scalability Acknowledgment
Recombination is computationally intensive. For datasets exceeding 1 million samples, consult our **advanced cluster deployment guide**. The "free lunch" of generation has a ceiling — but it's a *very tall* ceiling.

### 🧭 Semantic Drift Warning
In rare cases, aggressive recombination can produce **nonsensical or harmful outputs**. The novelty filter reduces this risk, but it cannot eliminate it. Review your generated "edge cases" deliberately.

---

## 🛣️ 2026 Roadmap Preview

- **🔮 Vision-Language Fusion** — Decompose images alongside text prompts
- **🗺️ Geographic Context Engine** — Regional dialect awareness for localization
- **📡 Real-Time Collaborative Forging** — Multi-user simultaneous dataset creation
- **🧬 Reinforcement Learning from Human Preference** — Auto-adjusting recombination strategies based on your review history

---

## 🤝 Contributing

We welcome semantic alchemists of all skill levels:

1. **Fork the forge** — create your own variant
2. **Submit recipes** — share your domain-specific decomposition strategies
3. **Report bias** — the semantic core tries to be neutral, but if you spot a blind spot, tell us
4. **Translate the UI** — community localization is our growth engine

---

## 📜 License

PromptForge is released under the **MIT License**. You are free to use, modify, and distribute it — even commercially — provided you retain the original copyright notice.

[Read the full MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 PromptForge Contributors

---

## 🧙 Final Thoughts

PromptForge isn't just a tool — it's a **philosophy shift**. Traditional dataset creation is *sculpting*: chipping away at raw data until you get the shape you want. PromptForge is *forging*: melting down raw ideas and casting them into thousands of new forms.

Your prompts are the blueprint. Your domain knowledge is the fuel. And the forge... well, the forge is ready.

**Start your semantic alchemy today. The raw material is already in your head.**

---

*PromptForge: Where language becomes data, and data becomes insight.*