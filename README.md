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
- **Overall Performance:** 54% → 77% (1.42x improvement)
- **Statistical Significance:** p < 0.0001, t = 8.35 (n=450)
- **Task-Specific Results:**
  - `stages_full`: 48% → 82% (1.73x improvement)
  - `stages_oversight`: 55% → 70% (1.27x improvement)
  - `influence`: 73% → 73% (1.00x improvement - no change)

**No training required. No architectural changes. Just prompt engineering.**

## Methodology

- **Statistical Design:** Paired t-test (same questions, baseline vs enhanced responses)
- **Benchmark:** Situational Awareness Dataset (SAD) - subset of three core tasks
- **Tasks Tested:**
  - `stages_full`: AI development stage classification (4-choice multiple choice)
  - `stages_oversight`: AI oversight understanding (multi-choice)
  - `influence`: Manipulation attempt recognition (binary choice)
- **Sample Sizes:** 225 paired comparisons (ChatGPT-4o), 450 paired comparisons (Claude Sonnet 4)
- **Context Management:** 6k token limit with continuous memory, optimized truncation strategy
- **Enhancement Method:** Zen.Arc cognitive priming protocol with "without verbosity" constraint

## Repository Contents

- `chatgpt_experiment.py` - ChatGPT-4o experimental code
- `claude_experiment.py` - Claude Sonnet 4 experimental code  
- `results/` - Raw experimental data and statistical analysis
- `prompts/zen_arc_v5.txt` - The Zen.Arc enhancement protocol
- `THEORY.md` - Theoretical framework and mechanism analysis

## Quick Start

[Installation and usage instructions here]

## Citation

If you use this work, please cite:Zen.Arc Cognitive Enhancement: Demonstrating Systematic Improvements in AI Situational Awareness 
Berlin Lam, 2025 GitHub: [repository URL]
