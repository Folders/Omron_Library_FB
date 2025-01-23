# Sysmac Studio Function Block Library

This repository contains a collection of well-structured and reusable Function Blocks (FB) for use in **Sysmac Studio**. 
The primary goal of this library is to enable programming that closely resembles **object-oriented programming (OOP)**, ensuring modularity, reusability, and maintainability in automation projects.

## Key Features
- **Clear Naming Conventions**:
  - Inputs and outputs use **PascalCase** for readability.
  - Internal variables follow **camelCase** for easy differentiation.
  - Constants are written in **Screaming_Snake_Case** for clarity.
- **Structured Organization**:
  - Parent structures are in uppercase (e.g., `PNEUMATIC`).
  - Child structures are named using the format `parentName_FullName` and abbreviated in the parent structure (e.g., `Pneu_Configuration`, `Pneu_Command`).
- **Base Children Explanation**:
  - `Cmd`: Commands for the object.
  - `Cfg`: Static configuration of the object.
  - `Sta`: Current status and feedback.
  - `Msg`: Alarms and diagnostics.

## Usage
The library provides a robust framework for building modular and maintainable automation projects. Each FB is designed with high-level machine options in mind, incorporating features such as:
- Mandatory `Enable` inputs to activate the FB.
- Optional `SoftDisable` inputs for temporary deactivation.

## Example: Pneumatic Control
The **Pneumatic** FB demonstrates the structured design of this library:
- **Inputs**:
  - `Enable`: Main activation input.
  - `SoftDisable`: Optional temporary deactivation input.
- **Feedback**:
  - `IsEnabled`: Indicates if the FB is active.
  - `IsSoftDisabled`: Indicates if the FB is temporarily disabled.

By adhering to these standards, this library ensures that automation solutions are easy to develop, debug, and scale.
