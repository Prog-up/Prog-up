<div align="center">

# Enzo Juhel

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=2563EB&center=true&vCenter=true&width=680&lines=AI+Software+Engineer+%7C+Multi-Agent+Systems;On-Device+LLM+Inference+%26+Optimization;DevSecOps+%26+Hardened+Infrastructure;Candidate+Dual+M.S.+EPITA+%2B+Boston+University)](https://github.com/Prog-up)

<p align="center">
  <b>Dual M.S. Candidate in Computer Science & Cybersecurity</b><br>
  🎓 <b>EPITA: School of Engineering & Computer Science</b> (Sep 2022 – Jun 2027)<br>
  🎓 <b>Boston University</b> — M.S. in Computer Information Systems (Jan 2027 – Aug 2027)
</p>

<p align="center">
  <a href="https://linkedin.com/in/enzo-juhel"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://huggingface.co/Prog-up"><img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
  <a href="https://github.com/Prog-up"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

</div>

---

### 💡 About Me

I am an **AI Software Engineer & Systems Developer** focused on the intersection of **multi-agent AI systems**, **low-latency on-device LLM inference**, and **hardened DevSecOps infrastructure**. 

- 🤖 **Agentic & Multi-Agent Architectures**: Designing autonomous workflows utilizing **Agent-to-Agent (A2A)** interaction and the **Model Context Protocol (MCP)** for seamless tool invocation.
- ⚡ **Low-Latency Edge Inference**: Optimizing open-weights LLMs for resource-constrained hardware (Intel Iris Xe, OpenVINO, SYCL, Vulkan). Published benchmark researcher and model creator on [Hugging Face](https://huggingface.co/Prog-up).
- 🛡️ **DevSecOps & Bare-Metal Infrastructure**: Automating reproducible, zero-exposure production infrastructure using **Ansible**, **rootless Podman Quadlet**, **nftables**, **Tailscale**, and **SOPS**.
- ⚙️ **Systems Programming**: Deep background in low-level engineering (**C**, **C++**, **Rust**), compiler implementation (Tiger compiler), and formal solvers (DPLL SAT solvers).

---

### 🔬 Featured Projects & Research

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://huggingface.co/Prog-up">Local LLM Inference on Intel Xe GPUs</a></h3>
      <p>Empirical tech watch and benchmark of <b>14 LLMs (1B–9B)</b> on integrated Intel Iris Xe graphics across OpenVINO, SYCL, and Vulkan backends.</p>
      <ul>
        <li>Overcame 4 GiB buffer limit via OpenVINO tiled memory allocation (12–14 tok/s on 7B models).</li>
        <li>Published 3 optimized INT4 quantized models on Hugging Face:
          <br>• <a href="https://huggingface.co/Prog-up/gemma-4-E2B-it-int4-ov"><b>gemma-4-E2B-it-int4-ov</b></a>
          <br>• <a href="https://huggingface.co/Prog-up/gemma-4-E4B-it-int4-ov"><b>gemma-4-E4B-it-int4-ov</b></a>
          <br>• <a href="https://huggingface.co/Prog-up/Qwen2.5-3B-Instruct-int4-ov"><b>Qwen2.5-3B-Instruct-int4-ov</b></a>
        </li>
      </ul>
      <p><b>Tech:</b> <code>OpenVINO</code> <code>SYCL</code> <code>Vulkan</code> <code>Python</code> <code>Hugging Face</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/Prog-up/homeserver">Automated Hardened Home Server</a></h3>
      <p>Declarative, bare-metal server infrastructure deployment fully automated through modular Ansible playbooks and GitOps.</p>
      <ul>
        <li>Systemd-integrated rootless container units via <b>Podman Quadlet</b>.</li>
        <li>Hardened defense-in-depth: <code>nftables</code> network isolation, zero exposed public ports, Tailscale mesh VPN, and Fail2Ban.</li>
        <li>Secrets encrypted with <b>SOPS / age</b> and integrated with self-hosted Forgejo CI/CD runners.</li>
      </ul>
      <p><b>Tech:</b> <code>Debian 13</code> <code>Ansible</code> <code>Podman Quadlet</code> <code>nftables</code> <code>SOPS</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/Kylian14/MirAIge">Autonomous Multi-Agent Honeypot (Mir[AI]ge)</a></h3>
      <p><b>🥇 1st Place Winner — OVHcloud Hackathon (2026)</b></p>
      <ul>
        <li>Engineered a dynamic, procedural honeypot powered by <b>Agent-to-Agent (A2A)</b> multi-agent orchestration.</li>
        <li>Cooperative agents dynamically detect threats (T0 Sigma, T1 heuristics, T2 LLM), reroute traffic, and mislead threat actors while extracting forensic telemetry.</li>
      </ul>
      <p><b>Tech:</b> <code>Python</code> <code>A2A Multi-Agent</code> <code>MCP</code> <code>OpenStack / Octavia</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🔌 <a href="https://github.com/Prog-up/ai-agent">Model Context Protocol (MCP) Ecosystem</a></h3>
      <p>Suite of agentic connectors and tools extending LLMs with direct execution and real-world environmental access.</p>
      <ul>
        <li><a href="https://github.com/Prog-up/ai-agent"><b>ai-agent</b></a>: Local autonomous agent leveraging custom tools and local inference.</li>
        <li><a href="https://github.com/Prog-up/mcp-cli"><b>mcp-cli</b></a>: Command-line interface for testing and interacting with MCP servers.</li>
        <li><a href="https://github.com/Prog-up/web-scraper-mcp"><b>web-scraper-mcp</b></a>: Headless web scraping and extraction server for agent workflows.</li>
      </ul>
      <p><b>Tech:</b> <code>MCP SDK</code> <code>Python</code> <code>FastAPI</code> <code>Docker</code></p>
    </td>
  </tr>
</table>

---

### 🏆 Honors & Competitions

- 🥇 **1st Place Winner** — [OVHcloud Hackathon](https://www.ovhcloud.com/) (2026): *[Mir[AI]ge: Autonomous Procedural Honeypot](https://github.com/Kylian14/MirAIge) with A2A Multi-Agent Architecture*
- 🚩 **5th / 40 Teams** — *Hack'Lantique National Cybersecurity CTF* (2026)
- 🚩 **12th / 100 Teams** — *BreizhCTF* (2026)

---

### 🛠️ Technical Skills

<details open>
<summary><b>AI & Agentic Systems</b></summary>
<br>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-0071C5?style=flat-square&logo=intel&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Model Context Protocol](https://img.shields.io/badge/Model_Context_Protocol_(MCP)-0F172A?style=flat-square&logo=anthropic&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-4B5563?style=flat-square&logo=fastapi&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</details>

<details open>
<summary><b>Languages & Systems</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![OCaml](https://img.shields.io/badge/OCaml-EC6813?style=flat-square&logo=ocaml&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_(Debian_|_NixOS_|_Arch)-FCC624?style=flat-square&logo=linux&logoColor=black)

</details>

<details open>
<summary><b>Cloud, Infrastructure & DevSecOps</b></summary>
<br>

![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Podman Quadlet](https://img.shields.io/badge/Podman_Quadlet-892CA0?style=flat-square&logo=podman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-24292E?style=flat-square&logo=tailscale&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

</details>

<details open>
<summary><b>Cybersecurity & Forensics</b></summary>
<br>

![Ghidra](https://img.shields.io/badge/Ghidra-C33939?style=flat-square&logo=nsa&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-00A98F?style=flat-square&logo=aqua&logoColor=white)
![nftables](https://img.shields.io/badge/nftables-2E3440?style=flat-square&logo=linux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![SOPS](https://img.shields.io/badge/SOPS_/_age-0F172A?style=flat-square&logo=gnupg&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)

</details>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Prog-up&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="Enzo's GitHub Stats" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prog-up&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="45%" />
</div>

---

<div align="center">
  <sub>Built with care & precision • Rennes, France & Boston, MA</sub>
</div>
