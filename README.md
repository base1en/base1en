Paul James – Systems Engineering | Technical Analysis | AI-Directed Development

Systems-focused engineer with 29 years' experience in the automotive industry, including complex technical investigation, diagnostics, systems integration and deployment.

My approach is requirements-led rather than code-led. I specialise in identifying technical problems, investigating system behaviour, defining requirements, evaluating proposed solutions and directing AI-assisted implementation. I retain responsibility for technical decisions, testing and validation rather than treating AI-generated output as inherently correct.

## Open-source / architectural contribution

**OpenCode Home Assistant integration** – architectural analysis, design proposals and testing.

- [Issue #63 – Persistent Context & Local Instructions](https://github.com/magnusoverli/opencode/issues/63#issuecomment-5068219835) – Originated the architectural proposal for persistent project context and user-controlled local instructions. Developed an experimental reference implementation. The resulting architecture was adopted upstream and acknowledged by name in the v2.3.8b0 changelog.
- [PR #73 – Context Integrity Hardening:](https://github.com/magnusoverli/opencode/pull/73) – Beta testing of v2.3.8b0 identified potential context-provenance and retrieval issues. Subsequent maintainer investigation uncovered silent note truncation, broken decision-search matching and additional defects, addressed in the v2.3.8b1 hardening release.
- [Issue #113 – Graceful OpenCode Exit ("Clean Quit") Design Proposal](https://github.com/magnusoverli/opencode/issues/113) – Produced a technical investigation and implementation proposal for graceful termination of OpenCode sessions. Implemented upstream in v2.5.5.

## Projects

**[Home Assistant Home Dashboard Header Customiser](https://github.com/base1en/Home-Assistant-Home-Dashboard-Header-Customiser)**

An independent Home Assistant frontend module that renames the built-in Overview dashboard to Home and adds configurable dashboard shortcut buttons.

- Identified an unconfigurable native UI limitation and developed a working solution.
- Directed AI-assisted exploration and reverse-engineering of undocumented frontend structures, including shadow-root DOM traversal.
- Defined implementation requirements, evaluated integration approaches and iteratively validated behaviour against a live Home Assistant installation.
- Developed re-render resilience, route scoping and cleanup behaviour.
- Uses the supported frontend.extra_module_url loading mechanism, without HACS dependencies.
- Working, publicly available beta; currently unversioned.

Development transparency: Projects involve AI-assisted research, implementation, debugging and documentation. Technical direction, requirements, implementation review and final validation remain my responsibility.

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
