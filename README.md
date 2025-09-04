# SSH Honeypot Server

A lightweight, configurable SSH honeypot implementation using Python and Paramiko for cybersecurity research and threat intelligence gathering.

## Overview

This SSH honeypot simulates an SSH server to attract and log malicious connection attempts, providing valuable insights into attack patterns, credentials used by attackers, and command execution attempts. Built with a modular architecture for easy customization and deployment.

## Features

- **Realistic SSH Simulation**: Mimics authentic SSH server behavior using Paramiko
- **Comprehensive Logging**: Captures connection attempts, authentication data, and command execution
- **Configurable Authentication**: Support for password and key-based authentication simulation
- **Command Simulation**: Fake command execution with customizable responses
- **Geolocation Tracking**: Optional IP geolocation for attack source analysis
- **Multiple Output Formats**: JSON, CSV, and plain text logging options
- **Rate Limiting**: Built-in protection against connection flooding
- **Docker Support**: Containerized deployment for easy setup