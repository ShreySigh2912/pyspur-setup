# PySpur Setup

This repository contains the configuration files to run PySpur, a graph-based editor for LLM workflows.

## Quick Start

1. Make sure you have Docker and Docker Compose installed
2. Clone this repository
3. Run `docker-compose up`
4. Open http://localhost:3000 in your browser

## Components

- PySpur UI: Available at http://localhost:3000
- Ollama (optional): Local LLM service at port 11434

## File Structure

```
./
├── docker-compose.yml    # Docker Compose configuration
├── README.md            # This file
└── data/                # Persistent data directory
```

## Usage

To start the services:
```bash
docker-compose up -d
```

To stop the services:
```bash
docker-compose down
```

To view logs:
```bash
docker-compose logs -f
```