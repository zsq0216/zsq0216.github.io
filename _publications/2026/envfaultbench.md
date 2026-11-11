---
title: 'EnvFaultBench: Benchmarking LLM Agents on Software Environment-Fault Troubleshooting'
date: 2026-11-08 00:01:00 +0800
selected: true
pub: NeurIPS (E&D Track)
pub_date: '2026'
abstract: >-
  EnvFaultBench evaluates LLM agents on software environment-fault diagnosis and repair using 348 Docker-based
  instances from real GitHub issues in 75 open-source projects. It spans Python, TS/JS, and JVM ecosystems,
  covering 22 fault categories across three root-cause levels. Hidden functional tests verify restoration
  of target behavior rather than matching a prescribed command sequence. Ten LLMs are evaluated under a
  unified agent framework.
authors:
- Siqi Zhong
- Haiyang Shen
- Mugeng Liu
- Chongyang Pan
- Yun Ma
links:
  Dataset: https://huggingface.co/datasets/envfaultbench/EnvFaultBench
  Code: https://github.com/pkuaiweb/envfault-bench
cover: /assets/images/covers/envfaultbench.webp
cover_alt: EnvFaultBench pipeline for fault-instance construction, validation, and agent evaluation
---
