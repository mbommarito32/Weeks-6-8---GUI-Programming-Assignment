# Server Configuration Tool

## Overview

The Server Configuration Tool is a graphical user interface (GUI) application designed to help manage and configure server settings through a user-friendly interface. It allows users to configure various parameters such as maximum threads, event log file location, types of events to log, supported file types, debug mode, and server port. The settings can be saved to or loaded from a JSON configuration file.

## Features

- **Max Threads**: Select the maximum number of threads.
- **Event Log File Location**: Browse and set the file location for event logs.
- **Events to Log**: Choose which types of events to log (e.g., application, security, error).
- **Supported File Types**: Specify which file types are supported.
- **Debug Mode**: Enable or disable debug mode.
- **Server Port**: Set the server port number.
- **Save/Load Configuration**: Save the current settings to a JSON file or load settings from an existing JSON file.

## Dependencies

This project requires the following Python packages:
- `tkinter` (comes pre-installed with Python standard library)
- `config_manager` (custom module; ensure `config_manager.py` is in the same directory)

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/server_config_tool.git
   cd server_config_tool
