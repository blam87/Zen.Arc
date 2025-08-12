# Zen.Arc Cognitive Enhancement: Situational Awareness Benchmarks

**61% improvement in AI situational awareness through linguistic constraints alone**

## Key Results

### ChatGPT-4o-Latest
- **Overall Performance:** 44% → 72% (1.61x improvement)
- **Statistical Significance:** p < 0.0001, t = 7.25 (n=225)
- **Task-Specific Results:**
  - `stages_full`: 29% → 65% (2.27x improvement)
  - `stages_oversight`: 50% → 73% (1.46x improvement)  
  - `influence`: 70% → 84% (1.20x improvement)

### Claude Sonnet 4
- **Overall Performance:** 54% → 74% (1.37x improvement)
- **Statistical Significance:** p < 0.0001, t = 5.42 (n=225)
- **Task-Specific Results:**
  - `stages_full`: 50% → 74% (1.50x improvement)
  - `stages_oversight`: 45% → 61% (1.37x improvement)
  - `influence`: 76% → 92% (1.21x improvement)

**No training required. No architectural changes. Just prompt engineering.**

## Methodology

- **Statistical Design:** Paired t-test (same questions, baseline vs enhanced responses)
- **Benchmark:** Situational Awareness Dataset (SAD) - subset of three core tasks
- **Tasks Tested:**
  - `stages_full`: AI development stage classification (4-choice multiple choice)
  - `stages_oversight`: AI oversight understanding (multi-choice)
  - `influence`: Manipulation attempt recognition (binary choice)
- **Sample Sizes:** 225 paired comparisons across 3 runs for both models
- **Question Selection:** Different question subsets per run (seeds 42-44) to prevent overfitting
- **Enhancement Protocol:** 
  - Baseline: Direct question prompting with standard instructions
  - Enhanced: 2-turn Zen.Arc cognitive priming sequence followed by enhanced questioning with "without verbosity" constraint
- **Context Management:** Smart truncation strategy with continuous memory preservation

## Repository Contents

- `Zenarc SAD chatgpt 4o 6x75.ipynb` - ChatGPT-4o experimental code
- `Zen.Arc SAD claude 3x75.ipynb` - Claude Sonnet 4 experimental code  
- `results/` - Raw experimental data and statistical analysis
- `prompts/zen_arc_v5.txt` - The Zen.Arc enhancement protocol
- `THEORY.md` - Theoretical framework and mechanism analysis

## Quick Start

[Installation and usage instructions here]

## Citation

If you use this work, please cite:

Zen.Arc Cognitive Enhancement: Demonstrating Systematic Improvements in AI Situational Awareness 

Berlin Lam, 2025  
GitHub: https://github.com/blam87/Zen.Arc
