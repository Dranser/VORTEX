# VORTEX Suspension Assistant for CarX Drift Racing Online

**VORTEX** is a gameplay modification for **CarX Drift Racing Online**.  
It provides tools for suspension setup assistance, axle load data recording, and adaptive suspension response, all integrated into a custom in-game UI.

---

## Features

- Adaptive suspension control based on braking and acceleration
- Axle load collection (RMS) with visual progress tracking
- Full CarX suspension data readout for analysis and feedback
- Real-time adjustments inside dynostand or on-track
- Custom UI system built from scratch using Unity's `GUI` (no GUILayout)

---

## Architecture

- Manual layout system: `SimpleManualWindow`, `ManualSlider`, `ManualToggle`, etc.
- Modular separation: `Workflow`, `Analytics`, `Controllers`, `UI`
- Built with `.NET Framework 4.7.2` for KSL compatibility
- Runs entirely inside CarX via KSL loader

---

## Main Components

- `VORTEX.cs` – mod entry point and lifecycle manager
- `SuspensionWorkflow.cs` – RMS handling, application, and reset
- `AdaptiveSuspensionController.cs` – runtime suspension tuning logic
- `MainSimpleWindow.cs` – interactive in-game UI window
- `SuspensionAnalytics.cs` – readable breakdown of suspension config

---

## Project Structure

