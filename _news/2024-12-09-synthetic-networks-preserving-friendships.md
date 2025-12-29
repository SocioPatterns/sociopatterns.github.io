---
layout: news_item
title: 'New algorithm to generate synthetic school contact data'
date: '2024-12-09 09:00:00'
slug: synthetic-networks-preserving-friendships
---

We have published a <a href="https://doi.org/10.1371/journal.pcbi.1012661">new paper in PLoS Computational Biology</a> presenting an algorithm to construct synthetic temporal contact networks for epidemic modeling. The algorithm addresses a key limitation in using short-term contact data for long-term epidemic simulations: how to extend contact data while preserving realistic patterns of both regular friendships and casual contacts.

High-resolution contact data are typically recorded over short time windows relative to epidemic timescales. Simply looping over short-term data can lead to unrealistic transmission chains because all contacts are deterministically repeated without any renewal of contact partners. Real contacts include a combination of regularly repeated contacts due to friendships and more casual ones.

Our algorithm longitudinally extends contact data recorded in school settings while preserving this dual aspect of contacts. Using agent-based simulations of SARS-CoV-2 spread on synthetic contacts, we show that preserving friendships does not strongly affect transmission routes between classes but leads to different infection pathways between individual students. The results indicate that gathering contact data during just two days in a population is sufficient to generate realistic synthetic contact sequences on longer timescales, contributing to optimal design of future field data collection efforts.
