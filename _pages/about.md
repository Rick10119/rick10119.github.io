---
permalink: /
title: "Building a Demand Flexibility Economy"
description: "Power-system research on demand flexibility, low-carbon technologies, and sustainable energy infrastructure planning."
author_profile: true
redirect_from: 
  - /about/
  - /about.html

impact_row:
  - title: "Nature Energy"
    excerpt: "**Cover Article (2026).** Industrial overcapacity and product inventories as a source of seasonal grid flexibility."
    url: "https://www.nature.com/articles/s41560-026-02073-y"
    btn_label: "Read the paper"
    btn_class: "btn--primary"
  - title: "Industrial Implementation"
    excerpt: "**US$4 million/year** in estimated operating-cost savings from coordinating manufacturing load, battery storage, and solar generation."
    url: "/projects/industrial-energy-management/"
    btn_label: "View the project"
    btn_class: "btn--primary"
  - title: "Open-Source Modeling"
    excerpt: "Models of aluminum, ammonia, and methanol production implemented in the MacroEnergy.jl energy-system planning framework."
    url: "https://github.com/macroenergy/MacroEnergy.jl"
    btn_label: "View the code"
    btn_class: "btn--primary"

research_areas:
  - title: "Physically Grounded and Scalable Modeling"
    excerpt: "Optimization methods that represent industrial production constraints while remaining tractable for power-system planning and operations."
  - title: "Large Loads and Energy Infrastructure Planning"
    excerpt: "Co-optimizing production capacity, inventories, facility locations, computing workloads, and operating schedules with generation, storage, and grid investments."
  - title: "Markets and Institutions for Demand Flexibility"
    excerpt: "Procurement mechanisms, contracts, and electricity markets that compensate firms for the capital, inventory, and operating costs of providing flexibility."
---

I am a power-system researcher. I develop optimization models and decision-support tools for low-carbon power systems, with a focus on flexibility from large loads, energy infrastructure planning, and electricity markets.

My research connects the physical constraints and investment decisions of industrial and other large energy users with power-system planning and operations. My goal is to build a **demand flexibility economy** in which firms meet their productive needs while reliably supporting power systems and earning predictable revenue in return.

[Explore Research Projects]({{ base_path }}/projects/){: .btn .btn--primary }
[Download CV]({{ base_path }}/files/CV_Ruike_Lyu.pdf){: .btn .btn--inverse }
[Email Me](mailto:{{ site.author.email }}){: .btn }

## Selected Impact

{% include feature_row id="impact_row" %}

## Current Research

{% include feature_row id="research_areas" %}

## Research Vision

Factories, buildings, data centers, and other large loads can adjust when and where they use electricity, but their flexibility is shaped by physical processes, investment decisions, and economic incentives. Realizing this flexibility therefore requires more than short-term load control: it requires co-designing operational models, infrastructure investments, and market arrangements.

Across this agenda, I combine physically grounded optimization, data-driven inference, and system-scale planning to determine not only how much flexibility large energy users can provide, but also what investments and institutions are needed to make that flexibility dependable and economically sustainable.

## Latest News

<ul>
{% for item in site.data.news limit:6 %}
  <li><strong>[{{ item.date }}]</strong> {{ item.text | markdownify | remove: "<p>" | remove: "</p>" }} <a href="{% if item.url contains '://' %}{{ item.url }}{% else %}{{ item.url | relative_url }}{% endif %}">{{ item.link_label }}</a>.</li>
{% endfor %}
</ul>
