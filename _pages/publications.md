---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<p fontsize = 11> Grouped by research theme. For an updated list, please see my  <a href="https://scholar.google.com/citations?user=fqgk10cAAAAJ&hl=en">google scholar page</a> (* denotes equal contributon).</p>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">Statistical and Algorithmic Foundations of LLMs and Auto-Regressive Models</h2>
{% bibliography --query @*[theme=llm] --group_by none %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">Sequential Decision-Making under Nonstationary Latent Dynamics</h2>
{% bibliography --query @*[theme=latent] --group_by none %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">Statistical Learning Theory and Control of Bilinear Dynamical Systems</h2>
{% bibliography --query @*[theme=bilinear] --group_by none %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">System Identification and Adaptive Control of Switching Dynamical Systems</h2>
{% bibliography --query @*[theme=mjs] --group_by none %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">Non-Asymptotic Learning Theory for Nonlinear Dynamical Systems</h2>
{% bibliography --query @*[theme=nonlinear] --group_by none %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">High-Dimensional Estimation, Low Ranked Structure, and Model Pruning</h2>
{% bibliography --query @*[theme=highdim] --group_by none %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">Sampling and Reconstruction of (Non)-Bandlimited Signals on the Sphere</h2>
{% bibliography --query @*[theme=sphere] --group_by none %}

<h2 class="bibliography" style="text-align: left; color: var(--global-text-color); font-size: 1.4rem">Other Publications</h2>
{% bibliography --query @*[theme=other] --group_by none %}

</div>
