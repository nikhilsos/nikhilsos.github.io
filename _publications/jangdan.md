---
title: "Jangdan as Downbeats: Downbeat Tracking in Traditional Korean Music Using TCN-RoFormer and Domain-Aware Dynamic Bayesian Network"
collection: publications
category: manuscripts
permalink: jangdan
excerpt: 'Downbeat tracking in Jangdan rhythmic structures using a TCN + RoFormer hybrid and a domain-aware Dynamic Bayesian Network. Incorporates prior knowledge of Jangdan cycle lengths directly into the DBN transition model, enabling accurate downbeat inference with limited annotated data.'
date: 2026-01-01
venue: 'Applied Sciences, MDPI'
---

Jangdan are the rhythmic cycle structures foundational to traditional Korean music (Pansori and related forms). Detecting downbeats — the cycle boundaries — requires reasoning over long temporal spans with strong structural priors, while handling sparse and domain-specific training data.

This work frames Jangdan downbeat tracking as a structured temporal inference problem. A TCN + RoFormer encoder extracts multi-scale sequence representations from audio: the TCN branch captures local rhythmic onset patterns while RoFormer models long-range dependencies with rotary positional encoding. A domain-aware Dynamic Bayesian Network post-processor encodes prior knowledge of valid Jangdan cycle lengths directly into the transition model, constraining inference to musically valid downbeat placements.

The domain-aware DBN is the core contribution — it replaces a generic beat-period prior with one conditioned on the target rhythmic domain, substantially improving downbeat accuracy under limited supervision.

Keywords: downbeat tracking; sequence modelling; temporal convolutional network; Transformer; Dynamic Bayesian Network; signal processing; structured prediction
