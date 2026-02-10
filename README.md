# ps-toolkit

A collection of reusable PowerShell helper functions and patterns intended to support automation, scripting, and module development.

## Purpose

This repository serves as a personal PowerShell toolkit, focusing on commonly reused patterns such as:

- Structured logging
- Error handling and retry logic
- REST API interaction
- Configuration and environment handling

## Design Goals

- Functions are small, composable, and well-scoped
- Consistent naming and parameter patterns
- Minimal assumptions about the execution environment
- Suitable for both script-based and module-based usage

## Structure

src/
  Public/
  Private/

ps-toolkit.psm1  
ps-toolkit.psd1

Public: Exported functions intended for reuse  
Private: Internal helper functions

## Usage Notes

- Functions can be imported individually or as a module.
- Breaking changes may occur as patterns evolve.
- Documentation is included inline where appropriate.

## License

MIT License
