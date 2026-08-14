# 👥 Population Game — Multi-Agent Demographic & Economic Equilibrium Simulator

[![Live Demo](https://img.shields.io/badge/Live_Showcase-GitHub_Pages-38bdf8?style=for-the-badge&logo=github)](https://jirnyak.github.io/Population_game/)
[![AI Index](https://img.shields.io/badge/LLM_Search-llms.txt-38bdf8?style=for-the-badge)](https://raw.githubusercontent.com/Jirnyak/Population_game/main/llms.txt)
[![C++20](https://img.shields.io/badge/C%2B%2B-20-00599C?style=for-the-badge&logo=cplusplus)](https://isocpp.org/)
[![Multi-Agent](https://img.shields.io/badge/Simulation-Multi_Agent_ABM-00f5a0?style=for-the-badge)](https://en.wikipedia.org/wiki/Agent-based_model)

An agent-based demographic simulation modeling multi-generational population dynamics, resource competition, labor market equilibria, and spatial urban migration across cellular automata grids.

---

## 🏛️ Simulation Loop & Multi-Agent Flow

```mermaid
graph TD
    Pop[Agent Population Array] --> Health[Metabolic Energy & Aging Step]
    Health --> Labor[Labor Market Supply / Demand Equilibrium]
    Labor --> Income[Wage & Resource Distribution]
    Income --> Repro{Reproduction / Mortality Threshold}
    Repro -->|Births & Deaths| Update[Next Generation State Vector]
    Update --> Spatial[Spatial Urban Diffusion Grid]
```

---

## 🔬 Core Capabilities

1. **Micro-Economic Price Discovery:** Walrasian auctioneer equilibrium solving for commodity prices based on agent marginal utility.
2. **Cellular Migration Diffusion:** Voronoi-weighted geographic gravity models driving rural-to-urban urbanization waves.
3. **Multi-Generational Genetics:** Trait inheritance, fertility hazard rates, and age-structured cohort survival matrices.

---

### 👨‍💻 Engineering Syndicate & Authors
- **Жирняк (Jirnyak)** — Lead Demographic Physicist & Macro-Economic Systems.  
  GitHub: [@Jirnyak](https://github.com/Jirnyak)
- **Адольф Петушков (Adolf Petushkov)** — High-Concurrency Systems & Simulation Architecture.  
  GitHub: [@marko1olo](https://github.com/marko1olo)
