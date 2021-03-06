---
layout: labitem
title: Lab 2 - Pulse Shaping and Matched Filters

permalink: /ece450/lab2
course: ece450
next: /ece450/lab2/theory
---

In this lab, you will use GNURadio to construct a baseband digital communication system including data source, pulse shaping, AWGN channel, receiver and bit error rate counter. Previously (in [Lab 1]({{site.baseurl}}{% link _ece450/lab1/introduction.md %})) you built a 1-sample-per symbol system with no pulse shaping. In this lab you will build an N-sample-per-symbol system with pulse shaping.

**If you are unfamiliar with GNU Radio, it is strongly recommended that you complete the [introductory GRC tutorials]({{site.baseurl}}{% link _GRC-tutorials/introduction.md%}) hosted on this site before trying these labs.**

You will learn about:

- pulse shaping
- timing recovery in baseband receivers
- BER (bit error rate) measurements
- The $$\frac{E_b}{N_0}$$ metric

## Deliverables

In this lab there are the following deliverables:

- a single page of answers to the deliverable questions laid out in the lab. In this lab there are 6 of them. They are all highlighted and labelled with their respective question numbers. Each question will require some thought and should be answered concisely with 1 to 2 sentences of text and perhaps an accompanying figure.
- a short code you write to generate some BER versus Eb/N0 curves
- your final BER versus Eb/N0 figure
