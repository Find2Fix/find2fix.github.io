---
layout: '#layouts/Prose.astro'
title: About Find2Fix
---

Find2Fix researches how transparent artificial intelligence (AI) can help reduce software errors. The goal is an open-source pipeline that supports the process from error discovery to mitigation, explaining both the root cause of an error and why a suggested fix works.

## The Find2Fix pipeline

<figure class="not-prose my-6">
    <a href="/images/find2fix-pipeline.png" target="_blank" rel="noopener noreferrer" aria-label="Open the full Find2Fix pipeline diagram in a new tab">
        <img src="/images/find2fix-pipeline.png" alt="The Find2Fix pipeline: source code passes through fault identification with detection and root cause analysis, then patch generation with program synthesis and verification, and finally fault and patch explanation informed by developer knowledge. Feedback loops return patch candidates to fault identification." width="1506" height="266" class="h-auto w-full rounded border border-blue-100 bg-white" />
    </a>
    <figcaption class="mt-3 text-sm text-base-content/70"><a href="/images/find2fix-pipeline.png" target="_blank" rel="noopener noreferrer" class="link link-primary">View the full-size pipeline diagram</a>.</figcaption>
</figure>

## Discovering software errors
Finding an error is only the beginning. Find2Fix investigates in our [fault identification research](/fault-identification) how learned models of software behavior, testing, and code analysis can work together to detect bugs and vulnerabilities and trace them to their root cause.

## Automatically patching
Then turning detected faults into candidate fixes is the next step. Find2Fix combines in our [program synthesis research](/patch-generation) with patterns from existing code to generate patches, using information about the fault to guide the search and testing candidates before proposing a fix.

## Explanations developers can use

Automated detection and repair tools can be difficult to interpret. Find2Fix aims to give developers useful explanations without requiring extensive security knowledge. Our [software vulnerability explanation research](/vulnerability-explanation) investigates developers' explanatory needs and how to evaluate explanation quality.

## Partners

The project is a collaboration between **TU Delft** (Sicco Verwer, Sebastijan Dumancic, and Annibale Panichella), **Radboud University** (Mairieli Wessel, Erik Poll, and Frits Vaandrager), and industrial partners **dCodis** and **ASML**.

[Meet the team](/people) and explore our [publications](/publications).

## Funding

Find2Fix received funding from **NWO**, through the Knowledge and Innovation Covenant (KIC) programme on Cybersecurity for Digital Resilience.
