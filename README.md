# AgenTwin: An AI Agent Framework for Cooperative Digital Twin Interoperability

[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/henrikcorrea/agentwin-msc)


This repository contains the master's dissertation **"AgenTwin: An AI Agent Framework for Cooperative Digital Twin Interoperability"** conducted at the Institute of Informatics, Federal University of Rio Grande do Sul (UFRGS).

> **Note:** This repository is a continuation of the former [research proposal](https://github.com/HenriKCorrea/pep) and has evolved into the full dissertation.

## Overview

This dissertation investigates how AI Agent Protocols can enable semantic interoperability between heterogeneous Digital Twin (DT) systems while preserving their domain-specific optimizations and stakeholder autonomy. AgenTwin proposes a Digital Ecosystem architecture leveraging the Model Context Protocol (MCP) and the Agent-to-Agent (A2A) protocol to facilitate cross-domain collaboration without requiring unified ontologies or disruptive system changes. A proof-of-concept implementation integrating KTWIN (Smart City) and Eclipse Ditto (Energy Grid) platforms validates the approach through a realistic EV charging coordination scenario.

## Research Question

**How can AgenTwin leverage AI Agent Protocols to improve Digital Twin systems interoperability while preserving existing system autonomy?**

## Overleaf Integration

This project is synchronized with Overleaf for review. [Click here](https://www.overleaf.com/project/67eed6c5ea3465a8417292f3) to see it.  To compare local changes with the Overleaf version:

### Setup Overleaf Remote

```bash
# Add Overleaf as a remote repository
git remote add overleaf https://git@git.overleaf.com/67eed6c5ea3465a8417292f3

# Fetch the Overleaf repository
git fetch overleaf --depth 1
```

### Compare with Overleaf

```bash
# Diff local article directory against Overleaf master branch
# Excludes Overleaf-specific configuration files
git diff main:article overleaf/master -- ':(exclude)texmf/' ':(exclude).gitignore' ':(exclude).latexmkrc'

# Save diff to file for review
git diff main:article overleaf/master -- ':(exclude)texmf/' ':(exclude).gitignore' ':(exclude).latexmkrc' > diff.txt
```

## Author

**Henrique Krausburg Correa**  
Master's Student, Institute of Informatics - UFRGS  
Advisor: Prof. Dr. Juliano Araújo Wickboldt

## License

This research is part of academic work at UFRGS. All code and documentation will be made available under appropriate open-source licenses upon completion.

## References

See `article.bib` for complete bibliography.

