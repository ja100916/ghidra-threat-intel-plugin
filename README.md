# Ghidra Threat Intelligence Plugin

A Ghidra plugin designed to enhance malware analysis and threat hunting workflows by integrating threat intelligence capabilities directly into the reverse engineering environment.

## Features

- **Integrated YARA Scanning**: Scan binaries with custom YARA rules directly in Ghidra
- **One-Click YARA Rule Generation**: Generate detection rules from functions and strings
- **VirusTotal Integration**: Query hashes and strings against VirusTotal's database
- **Threat Intelligence Sidebar**: Unified interface for all threat intel operations

## Installation

1. Build the plugin using Gradle
2. Copy the generated `.zip` file to your Ghidra extensions directory
3. Restart Ghidra

## Usage

[Will be filled in as features are developed]

## Development

This project extends the Ghidra reverse engineering framework. See the [Ghidra API documentation](https://ghidra.re/ghidra_docs/api/ghidra/program/flatapi/FlatProgramAPI.html) for more information.

## License

GPLv3 - Same as Ghidra