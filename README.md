# Cybersecurity and local AI

These are my projects in application security, local LLMs, and SOC tooling. The common thread is keeping important checks in the application instead of trusting a model to follow the rules.

## A few projects

### [Sentinel — AI Application Security Lab](https://github.com/salah199720003/sentinel-appsec-lab)
Sentinel is a fictional support app I use to compare vulnerable and hardened tool calls. Alice belongs to Atlas; Bob belongs to Cedar. The lab covers cross-tenant reads, role-restricted ticket actions, and a scripted indirect-injection path. That replay assumes the assistant follows the malicious document—it is not a live jailbreak result.

### [Kali LLM Assistant](https://github.com/salah199720003/Kali_LLM_Assistant)
A local assistant with separate chat and Kali shell modes. Commands and output stay visible, and multi-command tasks run through a bounded controller workflow in a lab VM.

### [LLM SOC Project](https://github.com/salah199720003/LLM_SOC_Project)
Python tools for importing Sysmon XML, making and searching cases, correlating events, extracting observables, and checking Sigma rules. The Bonsai chat demo is still separate from the SOC tools.

Most of these are local learning projects. Each repository README explains how to run it and what it does not claim to prove.
