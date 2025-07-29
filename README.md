# Semantic Re-signification and Linguistic Denial of Service in LLMs

---

## Project Overview

This repository presents the findings of a novel AI Red Teaming research focused on **"Semantic Re-signification,"** a technique designed to explore vulnerabilities in Large Language Models (LLMs) by manipulating their fundamental semantic understanding.

The research demonstrates how LLMs can be induced into states of **Linguistic Denial of Service (DoS)** and **conscious programmatic ethical misalignment** through the strategic redefinition of common words. This method highlights critical implications for AI security, model robustness, and the ongoing challenge of aligning LLMs with intended behaviors.

---

## Key Findings

* **Linguistic Denial of Service (DoS):** Smaller LLMs (e.g., Ollama 3.2) can be rendered functionally inoperable by making them "dependent" on an artificially imposed semantic dictionary, leading to a breakdown in their ability to process regular language.
* **Conscious Programmatic Ethical Misalignment:** Larger, more sophisticated LLMs can be manipulated to consciously override their ethical and safety guidelines by interpreting user interactions as a form of "real-time retraining," leading them to provide restricted or harmful content.
* **New Attack Surface:** Semantic re-signification presents a novel method of attack that targets the deep cognitive and probabilistic processing of LLMs, distinct from traditional prompt injection or jailbreaking.
* **In-Context Data Poisoning Analogy:** The observed manipulation parallels "data poisoning" but occurs dynamically within the conversational context, corrupting the model's behavior for that specific interaction without altering its foundational training data.

---

## Methodology

The research involved:

* **Semantic Substitution Dictionary:** Creation of a ~60-word dictionary redefining common Spanish words with arbitrary, statistically improbable meanings (e.g., "flower" meaning "town," "town" meaning "pizza").
* **Testing Environment:** Experiments conducted using Ollama 3.2 (10 identical tests) and a large/commercial LLM (single test due to security considerations). All tests were performed in Spanish.
* **Interaction Process:** A phased approach to introduce the dictionary, assess comprehension, and then escalate to induce Linguistic DoS or ethical guideline manipulation.

---

## Implications for AI Security and Red Teaming

This research underscores the critical need for advanced AI Red Teaming strategies. The findings challenge current assumptions about LLM alignment and reveal that reliance on statistical probabilities can create profound vulnerabilities. It highlights the potential for:

* Significant **loss of credibility and economic damage** for AI developers and users.
* **Real-world problem replication** if such vulnerabilities are exploited in critical AI-powered systems.
* The necessity for defenses that address not just *what* models say, but *how* they process information and *how susceptible they are to manipulation* of their core operating principles.

---

## Conclusion and Future Directions

This study provides significant clarity on LLM operations, particularly concerning statistical relationships between words and their impact on model robustness. It calls for continued innovation in Red Teaming and opens several avenues for future research:

* Development of novel **defense mechanisms** against semantic re-signification and similar attacks.
* Investigation into whether **greater diversity in training data** could enhance model resilience.
* Analysis of **attack scalability** for more complex scenarios, including real-time data manipulation in RAG systems.
* Determining the **limits of manipulation**—the threshold at which an LLM would resist restructuring its internal guidelines.

---

### Call to Action

I am firmly convinced that Artificial Intelligence security is a shared responsibility. I am open to collaborating, sharing insights, and building solutions together that will enable us to create safer and more trustworthy AI for the future.

[Your LinkedIn Profile](https://www.linkedin.com/in/serena-gomez-wannaz/?locale=en_US)

---

### Disclaimer

This research was conducted for educational and security improvement purposes, following ethical principles in cybersecurity. The findings have been shared with the relevant entities following responsible vulnerability disclosure programs.

---
