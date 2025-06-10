---
layout: post
title: "Securing AI/ML Models in IoT Devices: Lessons from Power-Based Adversarial Attacks"
date: 2025-06-09
categories: [AI Security, Research]
tags: [adversarial ml, power side-channel, transformers, explainable ai]
author: Sahar Zargarzadeh
---

As AI/ML models become core components of IoT security systems, their **vulnerability to adversarial manipulation** presents serious risks. While most adversarial research focuses on image or text data, my work explores a **less studied but highly potent vector: power side-channel signals**.

This post introduces how attackers can exploit these physical signals to **evade AI-based anomaly detection**, and outlines strategies for improving robustness.

---

## ⚡ Why Power Traces Matter

Modern IoT devices often embed lightweight AI models for malware detection. Instead of analyzing logs or traffic, some advanced approaches monitor **power consumption patterns** to detect abnormal behavior.

But here's the problem: these power signatures can be **deliberately manipulated**.

---

## 🧠 My Research: Dummy Code as an Adversarial Tool

In my Ph.D. research, I introduced a **runtime dummy code injection technique** that creates **adversarial perturbations in power signals**. These perturbations are:

- Non-intrusive: Do not affect functionality  
- Targeted: Designed using SHAP to fool specific model features  
- Model-agnostic: Effective against LSTM, CNN, and transformer-based architectures  

The result? A 96% misclassification rate across power-based classifiers during Mirai malware’s scanning phase.

---

## 🔄 A Multimodal, Transformer-Based Defense Strategy

To counter such attacks, I'm building a **multimodal anomaly detection pipeline**. It fuses:

- 📊 Static features (PE headers, imports)  
- 🔄 Dynamic logs (API calls, network behavior)  
- ⚡ Power traces (side-channel)  

Using **transformer-based models**, this architecture learns both temporal and feature relationships while remaining more resilient to perturbations.

---

## 🛡️ Security-By-Design: Applying Microsoft Threat Modeling

At HP, I apply **Microsoft's Threat Modeling methodology** to assess how attackers could manipulate data, escalate privileges, or spoof communications across edge devices.

> For example, what happens if power channels are spoofed to look benign during malicious operations?

These questions help refine AI architectures **before deployment**, ensuring trust and resilience.

---

## ✅ Takeaways

- **Power-based detection is powerful but vulnerable**
- **Multimodal, explainable models offer better protection**
- **Security must be proactive**, with threat modeling integrated into AI design

---

## 📚 Learn More

Check out the full project here:  
👉 [PowerAdversarial-ML](https://github.com/SaharZargarzadeh/PowerAdversarial-ML)

---

Thanks for reading! I'm always open to collaborations and discussions.  
📫 [saharzargarzadeh.github.io](https://saharzargarzadeh.github.io)
