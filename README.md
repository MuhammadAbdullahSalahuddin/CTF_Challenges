# Memory Forensics Tool

## Overview
A custom, Python-based memory forensics utility designed to analyze volatile memory dumps. This tool specifically focuses on automating the extraction of active network sockets and correlating them with running processes for rapid incident response.

## Features
* **Network Socket Extraction:** Parses memory dumps to identify open TCP/UDP sockets.
* **Process Correlation:** Maps active connections to parent processes.
* **Automated Parsing:** Ingests raw memory artifacts and outputs structured logs.

## Prerequisites
* Python 3.10+
* `pip` package manager

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/memory-forensics-tool.git](https://github.com/your-username/memory-forensics-tool.git)
   cd memory-forensics-tool
