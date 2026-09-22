# Marvin Osorio

<div align="right">
📍 Chicago, IL, United States<br>
🌐 <a href="https://osoriomarv.github.io/">osoriomarv.github.io</a><br>
📧 <a href="mailto:osoriomarv@gmail.com">osoriomarv@gmail.com</a><br>
</div>

<div>
<a href="https://linkedin.com/in/marvinosorio">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://github.com/osoriomarv">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
</div>

I'm an AI Security engineer at Bank of America. I spent three years there as a threat hunter and detection engineer, and before that I was an experimental geochemist, which mostly meant writing code to model things and staring at data. Threat hunting turned out to be the same work with different data. AI security is the same work again, with a model in the loop.

Day to day I build the agentic harnesses a threat-hunt team runs, instrument what those agents touch on the box, evaluate the bank's own LLM deployments, and write the detections that fall out of it. I am an experimentalist and a breaker by nature.

---

## SKILLS

<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" alt="Splunk" />
  <img src="https://img.shields.io/badge/CrowdStrike-E01F27?style=for-the-badge" alt="CrowdStrike" />
  <img src="https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge" alt="Microsoft Sentinel" />
  <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
  <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI" />
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge" alt="MATLAB" />
</div>

**AI security and evaluation:** agent harnesses, OpenTelemetry, LLM evaluation, prompt injection, MITRE ATLAS, MCP, RAG, LangChain, AI SAST

**Investigation and detection:** Splunk (SPL), Microsoft Sentinel (KQL), CrowdStrike Falcon and LogScale (CQL), Microsoft Defender, Sigma, MITRE ATT&CK, Atomic Red Team

**Automation:** Python, PowerShell, Bash, Tines, Git, GitLab CI/CD

---

## WORK EXPERIENCE

### AI Security Sr Engineer | Bank of America 📍 Chicago (hybrid) | June 2026 - Present

- Built the agentic hunting harness the threat-hunt team runs. A hypothesis hunt that took two weeks by hand now re-runs in about four hours.
- Engineered an OpenTelemetry-based, OS-level detection and response sensor for agents. It captures agent API calls, CLI activity, and the OS activity each model touches, so the logs show whether an agent stayed inside its role.
- Implemented a detection-as-code pipeline in GitLab for the threat-hunting team, feeding a detection-tuning harness.
- Wrote v1 of the bank's AI SAST, which the penetration-testing team deployed in CI/CD.
- Designed an LLM evaluation process for an internal chatbot. The findings moved the bank to a vendor guardrail framework.
- Cut token use by 95% on the harnesses with a context-engineering ledger that keeps an agent's beliefs and facts in separate sets, so a fact prunes a belief.

### Threat Hunter & Detection Engineer | Bank of America 📍 Chicago (hybrid) | July 2023 - June 2026

- Ran 29+ hypothesis-driven threat hunts across nation-state and criminal TTPs; 13 became production detections.
- Investigated 30+ incidents and led 5+ end to end, from insider cases to vulnerability-management escalations, reconstructing initial-access and post-exploitation timelines.
- Tuned 15+ detections across Windows, Active Directory, and Microsoft 365, and cut alert volume on the team's developmental detections from 10-20 a week to under one a month.
- Traced AI-assistant misuse, including suggested control bypasses such as SOCKS proxies, from first alert to root cause. The findings led to AI-assistant sandboxing in the IDE across the enterprise.
- Enabled CrowdStrike USB device telemetry fleet-wide and wrote 3 detections for IP-KVMs and other unauthorized USB devices.
- Developed Tines automations connecting SIEM, EDR, and case management, so alerts arrive enriched with endpoint and log context and tier-one incidents close without an analyst.

### Research Assistant | Tulane University, HiTaP Laboratory 📍 New Orleans | June 2021 - June 2023

- Constructed a multi-stage MATLAB thermodynamics model of core formation under a nebular atmosphere with a custom solver, and benchmarked simulated annealing against particle swarm optimization across 10,000+ Monte Carlo runs. Published in Geochimica et Cosmochimica Acta (2025), second author.

---

## RESEARCH

- **Patent pending:** *Automated System for Detecting Likelihood of Falsified Outputs from Large Language Models*, [US 2025/0190763 A1](https://patents.google.com/patent/US20250190763A1/en), assigned to Bank of America. Co-inventor; designed the sandbox verification methodology for the three-model adversarial architecture.
- **Publication:** Sita, M., Osorio, M., Jackson, C., & Mukhopadhyay, S. (2025). *Modeling the early Earth: Core formation in the nebular era does not guarantee a high 3He/4He ratio.* Geochimica et Cosmochimica Acta. [doi:10.1016/j.gca.2025.08.022](https://doi.org/10.1016/j.gca.2025.08.022)

---

## EDUCATION

- **M.S., Experimental Geochemistry** | Tulane University 📍 New Orleans, Louisiana | 2023
- **B.A.** | Occidental College 📍 Los Angeles, California | 2021

---

## PROJECTS

Most of what I'm building right now (agent harnesses, prompt-injection evals, an MCP gateway design, a mechanism tracer) sits in private repos until it is finished. The public ones:

- [osoriomarv.github.io](https://github.com/osoriomarv/osoriomarv.github.io): the site. Plain HTML, no framework.
- [Nbgasexchange-model](https://github.com/osoriomarv/Nbgasexchange-model): the MATLAB model behind the 2025 GCA paper. Metal-silicate partitioning, U-Th and Hf-W decay, magma-ocean core equilibration, and a random-parameter Monte Carlo driver.
- [visualai_codework](https://github.com/osoriomarv/visualai_codework): working through the Welch Labs Illustrated Guide to AI. Perceptrons from scratch in notebooks, chapter by chapter.
- [Particle_swarm_optimization_testing](https://github.com/osoriomarv/Particle_swarm_optimization_testing): a particle swarm optimizer on the Prop 99 dataset. It converged worse than the baseline, which is the finding.
