<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=180&section=header&text=Sandie&fontColor=ffffff&fontSize=64&fontAlignY=38&desc=offline-first%20tooling%20for%20LLM-heavy%20codebases&descAlignY=60&descSize=16" alt="Sandie" />

<a href="https://github.com/Sandie">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=620&lines=Read-only+by+default.;Evidence+before+recommendations.;Reproducible+builds%2C+byte-for-byte.;Fallback-preserving+patches%2C+never+auto-applied." alt="typing" />
</a>

<br/>

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-8.14-02303A?style=flat-square&logo=gradle&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-schema_v4-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SBOM](https://img.shields.io/badge/SBOM-CycloneDX_1.5-4c1?style=flat-square)
![Builds](https://img.shields.io/badge/builds-reproducible-2ea043?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

</div>

---

### `$ whoami`

```text
handle     Sandie
focus      developer tooling · LLM cost & reliability · privacy-preserving analysis
stack      Java 21 · Gradle · SQLite · JUnit · CycloneDX
principle  don't touch the target repo, don't store what you don't need,
           don't claim what the evidence doesn't prove
```

### Now building

<table>
<tr>
<td width="70%">

**[JevCostCutter](https://github.com/Sandie/jevcostcutter)** — *stop paying an LLM to do an if/else.*<br/>A Java 21 CLI that finds bounded LLM decisions in a codebase, replays them in shadow mode against a cheaper decision engine, measures agreement and economics, and only then proposes a **review-only patch that keeps the original LLM call as fallback**.

`1.0.0-rc1` · 12 modules · 92 tests green · reproducible TAR/ZIP/SBOM · privacy audit: 0 findings

</td>
<td width="30%" align="center">

```text
inventory
   ↓
import evidence
   ↓
shadow replay
   ↓
metrics + $
   ↓
gate → patch
```

</td>
</tr>
</table>

### How I ship

| | |
|---|---|
| 🔒 **Read-only boundary** | Target repositories are snapshotted by SHA-256 before and after. Unchanged, or it's a bug. |
| 🧾 **Minimal evidence** | Raw prompts, payloads and credentials are never persisted. Only sanitized, bounded aggregates. |
| ⚖️ **Honest gates** | Synthetic, stale or insufficient evidence cannot authorize a recommendation. |
| 🔁 **Reproducible releases** | Two clean builds, separate caches, byte-for-byte identical artifacts. |
| 📌 **Pinned supply chain** | SHA-pinned CI actions, Gradle dependency verification, SBOM with artifact hashes. |

<!-- TOKEN: раскомментируй, когда будет название и контракт
### $<TICKER>

Experimental community token for the JevCostCutter project. **Not an investment product**, no promised returns, no affiliation with any company or person other than Sandie, including TypeSafe.

`Contract: <ADDRESS>` · [chain explorer](<LINK>)
-->

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sandie&show_icons=true&hide_border=true&theme=github_dark&hide_title=true" height="150" alt="stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sandie&layout=compact&hide_border=true&theme=github_dark" height="150" alt="langs" />

<sub>Read-only by default · Sandie</sub>

</div>
