Status
Stable release.

Changelog — Oxide v0.91.1
Added Windows single-instance protection.
Added debug terminal integration and settings access.
Added recent ROM quick-load action.
Added gamepad input support (gilrs).
Added audio volume slider (0–100).
Fixed language label encoding issues (UTF-8/mojibake).
Updated and normalized multilingual translations (12 languages).
Refactored modules and general cleanup.
Previous versions
Oxide v0.91.0

Added save/load states (3 slots).
Added debug terminal with search and log export.
Added configurable CPU quirks (5 flags, 3 presets).
Refactored codebase into multiple modules (src/ui/, src/debug/).
Added 6 CPU unit tests.
Oxide v0.90.0

Added JSON-based i18n system supporting 12 languages (FR, EN, ES, IT, DE, PT, RU, ZH, JA, KO, AR, HI).
Added automatic Windows system language detection.
Oxide v0.80.0

Added 880Hz buzzer audio via rodio.
Added volume control (0–100).
Oxide v0.70.0

Added full CHIP-8 keyboard input (16-key mapping).
Added gamepad support via gilrs.
Oxide v0.60.0

Added ROM loading (.ch8) via file explorer.
Added recent ROM memory and quick-reload.
Oxide v0.50.0

Added CHIP-8 64×32 pixel display rendering.
Added bottom status bar with version number.
Added automatic screen centering in window.
Oxide v0.40.0

Unified settings window with internal tabs.
Added Game menu dropdown (pause, reset, stop, save/load slots).
Added fullscreen toggle (F11 / Alt+Enter).
Added dynamic window sizing based on video_scale (1x–5x).
Added configurable keyboard shortcuts tab.
Oxide v0.30.0

Implemented full CHIP-8 CPU (35 opcodes).
Added memory.rs and display.rs modules.
Added random number support (opcode CXNN via rand).
Oxide v0.20.0

Added Settings window with tabs (Emulator, Video, Controls).
Added Ok / Apply / Cancel / Default buttons.
Implemented temp/snapshot pattern for proper cancel behavior.
Migrated from eframe 0.27 to 0.33.
Oxide v0.10.0

Initial egui window.
Dark/light theme persistence.
Base Rust project structure.
Known issues
None reported.
