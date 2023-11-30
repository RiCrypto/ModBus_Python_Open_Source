# ModBus_Python_Open_Source is a mod_py4u
Modbus Python Library - A Python library for Modbus communication, developed by Prof. Dr. Ricardo Augusto De Almeida from New Westminster, Canada.

# Modbus Python Library

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/modbus-python.svg)](https://github.com/yourusername/modbus-python/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/modbus-python.svg)](https://github.com/yourusername/modbus-python/issues)

A Python library for Modbus communication, developed by Prof. Dr. Ricardo Augusto De Almeida from New Westminster, Canada. This library allows you to easily communicate with Modbus-enabled devices using Python.

## Features

- **Modbus TCP and RTU Support**: Communicate with Modbus devices over TCP or RTU protocols.
- **Read and Write Operations**: Perform read and write operations to Modbus registers.
- **Easy-to-Use API**: Simple and intuitive API for interacting with Modbus devices.
- **Cross-Platform Compatibility**: Works on Windows, Linux, and macOS.

.mod_py4u/
.|-- docs/
.|   |-- source/
.|   |   |-- index.rst
.|   |-- conf.py
.|-- mod_py4u/
.|   |-- __init__.py
.|   |-- client/
.|   |   |-- __init__.py
.|   |   |-- base4u.py
.|   |   |-- tcp4u.py
.|   |   |-- rtu4u.py
.|   |-- server/
.|   |   |-- __init__.py
.|   |   |-- base4u.py
.|   |   |-- tcp4u.py
.|   |   |-- rtu4u.py
.|-- tests/
.|   |-- __init__.py
.|   |-- test_client4u.py
.|   |-- test_server4u.py
.|-- setup.py
.|-- README.md
.|-- LICENSE


## Installation

```bash
pip install mod_py4u

