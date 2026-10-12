## 🛠️ Open Source Contributions & QA Research 🛠️ ##

**[RTX-Encore](https://github.com/SilyNoMeta/rtx-encore) (DirectX / Reflex API Hooking)**
* Conducted variable isolation testing and verbose tracing analysis (millisecond-level) to diagnose render queue latency.
* Isolated driver-level (NVCP) vs. native injection conflicts, resulting in the official fix for frame pacing delays in Release v1.0.0-beta.4.
* **Troubleshooting Log:** [Issue #21](https://github.com/SilyNoMeta/rtx-encore/issues/21)
* **Fix Release / Credits:** [v1.0.0-beta.4](https://github.com/SilyNoMeta/rtx-encore/releases/tag/v1.0.0-beta.4)

**[RTX-Encore](https://github.com/SilyNoMeta/rtx-encore) (Live UI Recomposition / Version Regression Analysis)**
- Compared Streamline v2.12.0 vs. v2.14.1 alongside DLSS-G builds, identifying that older builds were hard-capping base engine FPS while v2.14.1 correctly restored native base performance.
- Isolated a live UI recomposition (UIR) hook delay bug where toggling settings required pausing the game (`ESC` trigger) to force injection.
- Provided comparative logs and diagnostic runs that led directly to the official patch in v1.0.0-beta.5.
- **Troubleshooting Log:** [Issue #27](https://github.com/SilyNoMeta/rtx-encore/issues/27)
- **Fix Release / Credits:** [v1.0.0-beta.5](https://github.com/SilyNoMeta/rtx-encore/releases/tag/v1.0.0-beta.5)
