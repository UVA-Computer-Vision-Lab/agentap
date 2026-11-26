<div align="center">
<h1>Tracking Any Point with Agentic Visual Reasoning</h1>

<p>
  <a href="https://xuweiyichen.github.io/">Xuweiyi Chen</a><sup>*‡<img src=".github/assets/uva.svg" alt="University of Virginia" height="11"></sup> &nbsp;·&nbsp; <a href="https://yaojin17.github.io/">Jin Yao</a><sup>*<img src=".github/assets/uva.svg" alt="University of Virginia" height="11"></sup> &nbsp;·&nbsp; <a href="https://linzhanmou.com/">Linzhan Mou</a><sup>*<img src=".github/assets/princeton.svg" alt="Princeton University" height="9"></sup> &nbsp;·&nbsp; Lei Gong<sup>*<img src=".github/assets/uva.svg" alt="University of Virginia" height="11"></sup> <br>
  <a href="https://lsn33096.github.io/">Di Liu</a><sup><img src=".github/assets/meta.svg" alt="Meta" height="7"></sup> &nbsp;·&nbsp; <a href="https://holmes969.github.io/">Cheng Zhang</a><sup><img src=".github/assets/meta.svg" alt="Meta" height="7"></sup> &nbsp;·&nbsp; <a href="https://mars-tin.github.io/">Ziqiao Ma</a><sup><img src=".github/assets/umich.svg" alt="University of Michigan" height="9"></sup> &nbsp;·&nbsp; <a href="https://sihanxu.me/">Sihan Xu</a><sup><img src=".github/assets/umich.svg" alt="University of Michigan" height="9"></sup> &nbsp;·&nbsp; <a href="https://adamharley.com/">Adam W. Harley</a><sup><img src=".github/assets/meta.svg" alt="Meta" height="7"></sup> <br>
  <a href="https://jasonqsy.github.io/">Shengyi Qian</a><sup>†<img src=".github/assets/meta.svg" alt="Meta" height="7"></sup> &nbsp;·&nbsp; <a href="https://www.cs.virginia.edu/~zc3bp/">Zezhou Cheng</a><sup>†<img src=".github/assets/uva.svg" alt="University of Virginia" height="11"></sup>
</p>

<p><img src=".github/assets/uva.svg" alt="University of Virginia" height="15"> University of Virginia &nbsp;·&nbsp; <img src=".github/assets/meta.svg" alt="Meta" height="10"> Meta &nbsp;·&nbsp; <img src=".github/assets/princeton.svg" alt="Princeton University" height="12"> Princeton University &nbsp;·&nbsp; <img src=".github/assets/umich.svg" alt="University of Michigan" height="12"> University of Michigan</p>

<p><sup>*</sup>Equal contribution &nbsp;·&nbsp; <sup>‡</sup>Project lead &nbsp;·&nbsp; <sup>†</sup>Equal advising</p>

<p>
  <a href="https://agentap.cs.virginia.edu/"><strong>Project Page</strong></a>
  &nbsp;·&nbsp;
  <a title="Coming soon"><strong>Paper</strong></a>
  &nbsp;·&nbsp;
  <a href="https://agentap.cs.virginia.edu/demo/"><strong>Demo</strong></a>
  &nbsp;·&nbsp;
  <a href="https://agentap.cs.virginia.edu/leaderboard/"><strong>Leaderboard</strong></a>
  &nbsp;·&nbsp;
  <a href="https://huggingface.co/datasets/uva-cv-lab/TrackingBench"><strong>Benchmark</strong></a>
</p>

<img src=".github/assets/earth.gif" alt="Four points on the Americas as the Earth turns: AllTracker (middle) keeps them on the edge while they are hidden and then loses them; AgenTAP (right) calls them hidden and finds them again" width="100%">
</div>

## Updates

- **The paper, code and evaluation code are coming soon.**

## Overview

A general-purpose vision-language model (VLM) can surpass expert vision models in point localization and visibility prediction through agentic visual reasoning, without correspondence-specific fine-tuning. We introduce **AgenTAP**, an agent that directly predicts point coordinates and visibility and actively checks its own answers. Starting from its own estimate, the VLM autonomously chooses what to inspect and uses the resulting evidence to verify point identity and refine its predictions.
