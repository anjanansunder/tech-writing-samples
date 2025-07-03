# CLI Tool – Quick Start Guide

## Overview
This guide helps you get started with **MyApp**, a fictional CLI tool used to automate deployments in various environments.

## System Requirements
- Ubuntu 20.04 or later
- Python 3.8+
- Git 2.25+
- Internet connection

## Installation

```bash
git clone https://github.com/example/myapp.git
cd myapp
pip install -r requirements.txt
python setup.py install
```

## Basic Usage

Verify installation:

```bash
myapp --help
```

Deploy to production:

```bash
myapp deploy --env production --config ./config/prod.yaml
```

## Troubleshooting

If you see a 'Permission denied' error:

```bash
sudo myapp deploy --env production
```

## Support

Visit [GitHub Issues](https://github.com/example/myapp/issues) or email support@myapp.io.
