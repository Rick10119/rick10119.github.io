---
permalink: /
title: "What I'm Doing"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
![About My Research](/images/about.png)
# My Research Focus: Addressing the Duck Curve Challenge through Industrial Consumer-Grid Interactions

I'm a PhD student in Electrical Engineering. My research focuses on solving one of the most pressing challenges in modern power systems: the "duck curve."

## The Duck Curve Problem

The duck curve represents the demand curve in power systems with high renewable energy penetration. As solar generation increases during the day and drops in the evening, it creates a distinctive curve resembling a duck's profile. This phenomenon is causing significant challenges:

- In California, it has led to steep ramping requirements for conventional generators
- In Shandong Province, China, it has resulted in nearly 20% negative prices in the spot market
- Globally, it increases the cost of maintaining power balance through redundant generation resources

## My Solution Approach: Industrial Users as Virtual Power Plants

While traditional solutions focus on building more flexible generation resources, my research explores a different path: leveraging the flexibility of industrial users through virtual power plants (VPPs). Industrial users possess large capacity and significant potential for grid interaction.

My research addresses three key challenges in this domain:

### 1. Model Efficiency

**Challenge**: Current industrial load models use integer variables to describe production processes. A single factory could have 10,000 variables, making optimization problems NP-hard to solve.

**My Solution**: I've developed linearized models using convex relaxation techniques that maintain accuracy while solving 20 times faster than conventional approaches.

### 2. Parameter Identification

**Challenge**: Load parameters are typically private data that VPPs cannot access, with only smart meter data widely available.

**My Solution**: I've pioneered inverse optimization techniques that can identify model parameters from historical smart meter data - something previously thought impossible. This enables accurate modeling without compromising industrial users' privacy.

### 3. Economic Optimization

**Challenge**: Traditional methods separate market bidding from VPP control, resulting in suboptimal economic outcomes.

**My Solution**: By co-optimizing bidding and control strategies, I've achieved a 40% cost reduction through better coordination of industrial users and other resources.

## Real-World Impact

My research isn't just theoretical - it's delivering tangible results. One implemented project with a major auto manufacturer generates $4 million in annual savings.

By exploring industrial flexibility from the perspectives of modeling, data, and economics, I'm working to make the duck curve more manageable and renewable integration more affordable for power systems worldwide.

# Why I Share My Research Openly

I've always found that the most impactful research papers are those with open-source code and data. As a researcher, I believe in making science more accessible, reproducible, and collaborative. This website exists for a simple purpose: to share my research openly and help others understand and apply it.

By providing access to code, data, and detailed explanations of my work, I hope to:

- Make my research more transparent and reproducible
- Help others build upon my findings
- Increase the impact and citations of my papers

For me, solving problems brings joy, but helping others understand those solutions is even more rewarding. I'll be gradually open-sourcing all my research projects and adding explanatory materials to make complex concepts more accessible.

Feel free to explore my publications, code repositories, and explanations. I welcome questions, collaborations, and feedback!

