<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&pause=1400&color=39D353&center=true&vCenter=true&width=820&lines=security+engineering+with+a+blue-team+bias;audit+the+config+%C2%B7+prove+the+path+%C2%B7+ship+the+fix;offline+by+default+%C2%B7+zero+dependencies" alt="security engineering with a blue-team bias" />

# Mehul Patel

**Security engineering · attack-surface auditing · detection tooling**

I build small, offline, zero-dependency tools that answer one question about an environment:
*where can an attacker actually go from here, and what is the shortest fix?*

Every tool reads configuration and logs instead of attacking anything, proves the exposure with
evidence, and prints the exact change that closes it.

</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mehulpatel23b-pixel&color=39d353&style=flat-square&label=profile+views" alt="profile views" />
  <img src="https://img.shields.io/badge/based%20in-India-0d1117?style=flat-square&logo=googlemaps&logoColor=39d353" alt="based in India" />
  <img src="https://img.shields.io/badge/approach-offline%20first-0d1117?style=flat-square" alt="offline first" />
  <img src="https://img.shields.io/badge/runtime%20dependencies-zero-0d1117?style=flat-square" alt="zero runtime dependencies" />
  <img src="https://img.shields.io/badge/tooling-MIT-0d1117?style=flat-square" alt="MIT licensed" />
</p>

---

## ▸ Coverage

| Domain | Exposure it finds | Tools |
| :-- | :-- | :-- |
| **Cloud & identity** | IAM privilege-escalation primitives, CloudTrail identity attacks correlated across principals, CI secrets ranked by real reach | [escalens](https://github.com/mehulpatel23b-pixel/escalens) · [trailtriage](https://github.com/mehulpatel23b-pixel/trailtriage) · [ciradius](https://github.com/mehulpatel23b-pixel/ciradius) |
| **Active Directory** | Live NTLM relay paths from coercion source to target, and the fewest changes that kill the most of them | [relaymap](https://github.com/mehulpatel23b-pixel/relaymap) |
| **Kubernetes & containers** | RBAC hops from any subject to cluster-admin, Dockerfiles that bake in secrets or finish as root | [rbacpath](https://github.com/mehulpatel23b-pixel/rbacpath) · [dockseal](https://github.com/mehulpatel23b-pixel/dockseal) |
| **Network & host** | sshd config as sshd would actually apply it, brute-force and spray chains in auth logs, pcap traffic with scans and C2 beacons | [sshsurface](https://github.com/mehulpatel23b-pixel/sshsurface) · [bruteradar](https://github.com/mehulpatel23b-pixel/bruteradar) · [packetlens](https://github.com/mehulpatel23b-pixel/packetlens) |
| **Email, web & DNS** | Phishing and BEC in raw mail, lookalike URLs, SPF/DMARC spoofability, missing security headers | [mailcase](https://github.com/mehulpatel23b-pixel/mailcase) · [phishverdict](https://github.com/mehulpatel23b-pixel/phishverdict) · [spoofscope](https://github.com/mehulpatel23b-pixel/spoofscope) · [hdrscope](https://github.com/mehulpatel23b-pixel/hdrscope) |
| **AI & agent security** | Risky MCP server config, prompt injection in files and scraped content, ambiguous LLM tool definitions, agent skill leaks | [mcpseal](https://github.com/mehulpatel23b-pixel/mcpseal) · [injectguard](https://github.com/mehulpatel23b-pixel/injectguard) · [toolcheck](https://github.com/mehulpatel23b-pixel/toolcheck) · [skill-doctor](https://github.com/mehulpatel23b-pixel/skill-doctor) |
| **Detection engineering** | How noisy a Sigma rule will be on real logs, duplicate alerts fused into one explainable incident queue | [sigmanoise](https://github.com/mehulpatel23b-pixel/sigmanoise) · [alertfuse](https://github.com/mehulpatel23b-pixel/alertfuse) |
| **Supply chain & CI** | Typosquatted packages, unpinned workflow actions, secrets that were ever committed to git | [pipxray](https://github.com/mehulpatel23b-pixel/pipxray) · [wfshield](https://github.com/mehulpatel23b-pixel/wfshield) · [pastsecrets](https://github.com/mehulpatel23b-pixel/pastsecrets) |

Plus autonomous multi-agent security crews for triage, threat modeling and patch response:
[sentinel-swarm](https://github.com/mehulpatel23b-pixel/sentinel-swarm) · [threatweave](https://github.com/mehulpatel23b-pixel/threatweave) · [patchswarm](https://github.com/mehulpatel23b-pixel/patchswarm)

---

## ▸ Featured work

<p align="center">
  <a href="https://github.com/mehulpatel23b-pixel/escalens">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mehulpatel23b-pixel&repo=escalens&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=C9D1D9" alt="escalens" />
  </a>
  <a href="https://github.com/mehulpatel23b-pixel/trailtriage">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mehulpatel23b-pixel&repo=trailtriage&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=C9D1D9" alt="trailtriage" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/mehulpatel23b-pixel/mcpseal">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mehulpatel23b-pixel&repo=mcpseal&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=C9D1D9" alt="mcpseal" />
  </a>
  <a href="https://github.com/mehulpatel23b-pixel/wfshield">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mehulpatel23b-pixel&repo=wfshield&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=C9D1D9" alt="wfshield" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/mehulpatel23b-pixel/sshsurface">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mehulpatel23b-pixel&repo=sshsurface&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=C9D1D9" alt="sshsurface" />
  </a>
  <a href="https://github.com/mehulpatel23b-pixel/packetlens">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mehulpatel23b-pixel&repo=packetlens&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=C9D1D9" alt="packetlens" />
  </a>
</p>

---

## ▸ How I build

```text
[1] offline         no network calls, no cloud API, no credentials to hand over
[2] zero deps       pure Python standard library, so the auditor has no supply chain of its own
[3] explainable     every finding carries evidence, attack reason and the exact fix
[4] CI-gated        stable exit codes and JSON output, drops straight into a pipeline
[5] read-only       it reads config and logs, it never touches the target
```

A finding you cannot explain is a finding nobody fixes. So each result looks like:
`what is exposed → why it matters → the line to change`.

---

## ▸ Toolbox

**Languages & data**

<p>
  <img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=39D353" alt="Python" />
  <img src="https://img.shields.io/badge/GNU%20Bash-0d1117?style=flat-square&logo=gnubash&logoColor=39D353" alt="Bash" />
  <img src="https://img.shields.io/badge/YAML-0d1117?style=flat-square&logo=yaml&logoColor=CB171E" alt="YAML" />
  <img src="https://img.shields.io/badge/JSON-0d1117?style=flat-square&logo=json&logoColor=white" alt="JSON" />
  <img src="https://img.shields.io/badge/Markdown-0d1117?style=flat-square&logo=markdown&logoColor=white" alt="Markdown" />
</p>

**Platforms & pipelines**

<p>
  <img src="https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-0d1117?style=flat-square&logo=kubernetes&logoColor=326CE5" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-0d1117?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
</p>

**Security domains**

<p>
  <img src="https://img.shields.io/badge/AWS%20IAM-0d1117?style=flat-square" alt="AWS IAM" />
  <img src="https://img.shields.io/badge/CloudTrail-0d1117?style=flat-square" alt="CloudTrail" />
  <img src="https://img.shields.io/badge/NTLM%20relay-0d1117?style=flat-square" alt="NTLM relay" />
  <img src="https://img.shields.io/badge/Kubernetes%20RBAC-0d1117?style=flat-square" alt="Kubernetes RBAC" />
  <img src="https://img.shields.io/badge/OpenSSH-0d1117?style=flat-square&logo=openssh&logoColor=39D353" alt="OpenSSH" />
  <img src="https://img.shields.io/badge/pcap%20triage-0d1117?style=flat-square" alt="pcap triage" />
  <img src="https://img.shields.io/badge/Sigma%20rules-0d1117?style=flat-square" alt="Sigma" />
  <img src="https://img.shields.io/badge/SOC%20alert%20triage-0d1117?style=flat-square" alt="SOC triage" />
  <img src="https://img.shields.io/badge/SPF%20%2F%20DMARC-0d1117?style=flat-square" alt="SPF DMARC" />
  <img src="https://img.shields.io/badge/phishing%20analysis-0d1117?style=flat-square" alt="phishing analysis" />
  <img src="https://img.shields.io/badge/MCP%20security-0d1117?style=flat-square" alt="MCP security" />
  <img src="https://img.shields.io/badge/prompt%20injection-0d1117?style=flat-square" alt="prompt injection" />
  <img src="https://img.shields.io/badge/software%20supply%20chain-0d1117?style=flat-square" alt="supply chain" />
  <img src="https://img.shields.io/badge/CI%2FCD%20hardening-0d1117?style=flat-square" alt="CI hardening" />
</p>

---

## ▸ Signal

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=mehulpatel23b-pixel&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=false&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=C9D1D9" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mehulpatel23b-pixel&layout=compact&theme=github_dark&hide_border=true&langs_count=8&bg_color=0D1117&title_color=39D353&text_color=C9D1D9" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=mehulpatel23b-pixel&hide_border=true&background=0D1117&ring=39D353&fire=39D353&currStreakNum=39D353&sideNums=39D353&currStreakLabel=39D353&sideLabels=C9D1D9&dates=C9D1D9" alt="Contribution streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mehulpatel23b-pixel&bg_color=0D1117&color=C9D1D9&line=39D353&point=39D353&area=true&hide_border=true&title_color=39D353" alt="Contribution graph" />
</p>

---

## ▸ Phishing triage suite

A reported phish moves through five questions. There is a tool for each, and all of them run offline.

| Stage | Tool | The question it answers |
| :-- | :-- | :-- |
| Link in the mail | [redirectchain](https://github.com/mehulpatel23b-pixel/redirectchain) | Where does the chain really end, and where does the trust break on the way |
| Page saved by a user | [formguard](https://github.com/mehulpatel23b-pixel/formguard) | Where does the password post, does the brand match the host, what exfiltrates |
| Attachment forwarded | [attachscan](https://github.com/mehulpatel23b-pixel/attachscan) | What the file really is, past the extension: macro, smuggling, encrypted zip, LNK |
| Thread escalated | [becscan](https://github.com/mehulpatel23b-pixel/becscan) | Who is actually in the conversation: name reuse, lookalike domain, bank change |
| Domain being imitated | [typosquat](https://github.com/mehulpatel23b-pixel/typosquat) | Which lookalike domains exist right now, and which technique built them |
| Impersonation already live | [dmarcrpt](https://github.com/mehulpatel23b-pixel/dmarcrpt) | Which IPs send as your domain and fail both DKIM and SPF |

Older triage pieces that pair with the suite:
[mailcase](https://github.com/mehulpatel23b-pixel/mailcase) (raw mail, 57 checks) ·
[phishverdict](https://github.com/mehulpatel23b-pixel/phishverdict) (URL scoring) ·
[spoofscope](https://github.com/mehulpatel23b-pixel/spoofscope) (SPF/DMARC posture) ·
[hdrscope](https://github.com/mehulpatel23b-pixel/hdrscope) (security headers)

---

## ▸ Ethics

Everything here is defensive and read-only: config auditors, log analysers and posture graders.
There is no exploitation code, no traffic generation and no credential harvesting.
Run them against systems you own or have written authorisation for. Findings stay on your machine.

Assessment work, collaboration, or a tool you want built? Open an issue on any repo or send a DM here on GitHub.

<p align="center">
  <img src="https://github.com/mehulpatel23b-pixel/mehulpatel23b-pixel/raw/output/github-snake-dark.svg" alt="contribution grid" />
</p>

<p align="center"><sub>Offline by default. Explainable by design. MIT licensed.</sub></p>
