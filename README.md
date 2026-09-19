Paul James – Systems Engineering / AI-Assisted Engineering

Systems-focused engineer with 29 years' experience in the automotive industry, including technical investigation, diagnostics, systems integration and deployment.

## Open-source / architectural contribution

**OpenCode Home Assistant integration** – architectural analysis, design proposals and testing.

- [Issue #63 – Persistent Context & Local Instructions](https://github.com/magnusoverli/opencode/issues/63#issuecomment-5068219835) – proposed in comments on a memory-plugin feature request; _implemented upstream by the project maintainer_ (shipped as v2.3.8b0), credited by name in the changelog
- [PR #73 – "never let a gap in context read as an absence"](https://github.com/magnusoverli/opencode/pull/73) – beta testing documented in [#63](https://github.com/magnusoverli/opencode/issues/63#issuecomment-5087959098) revealed some potential issues; the maintainer investigated further and found silent note-truncation, a broken decision-search match, and other defects; the findings were fixed upstream in a dedicated hardening release (v2.3.8b1)
- [Issue #113 – Graceful OpenCode Exit ("Clean Quit") Design Proposal](https://github.com/magnusoverli/opencode/issues/113); _implemented upstream by project maintainer_ (v2.5.5)

## Projects

**[HA Overview Page Tweak](https://github.com/base1en/ha-overview-page-tweak)** – Home Assistant frontend module that customises the built-in Home Dashboard header.

* Native header augmentation: replaces "Overview" with "Home" and adds configurable dashboard shortcuts
* AI assisted Reverse-engineering and testing against a live Home Assistant frontend, including shadow-root DOM traversal and re-render handling
* Uses the supported `frontend.extra_module_url` loading mechanism, with no HACS dependencies
* Working beta, currently unversioned

<!--
**base1en/base1en** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
