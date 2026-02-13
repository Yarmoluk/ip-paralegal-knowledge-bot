# IP Paralegal Knowledge Bot

[![Status](https://img.shields.io/badge/Status-In_Development-yellow)](https://github.com/Yarmoluk/ip-paralegal-knowledge-bot)
[![Knowledge Base](https://img.shields.io/badge/Knowledge_Base-Black_Hills_IP-blue)](https://yarmoluk.github.io/blackhillsip/)

An AI-powered decision support bot built on top of the [Black Hills IP](https://yarmoluk.github.io/blackhillsip/) knowledge graph — a 200-concept structured representation of intellectual property management and legal technology.

Part of coursework for SEIS 666: Digital Transformation with AI at the University of St. Thomas, exploring how knowledge graphs can serve as the foundation for specialized AI assistants.

## Concept

The [blackhillsip](https://github.com/Yarmoluk/blackhillsip) repository contains the structured knowledge — 200 concepts, 13 chapters, dependency-mapped learning graph covering patent prosecution, trademark registration, international filing, and AI-powered IP tools.

This repository adds the **decision layer**: a specialized bot that reasons over that knowledge graph to answer questions, check compliance, and support IP workflow decisions.

### Planned Capabilities

- **Research queries** — "What are the PCT filing requirements for Japan?"
- **Compliance checking** — "Does this IDS meet Rule 56 requirements?"
- **Deadline monitoring** — "What are the critical dates for this patent family?"
- **Procedure sequencing** — "Walk me through national phase entry from PCT"
- **Concept explanation** — "Explain patent claim construction to a new paralegal"

## Architecture

```
IP Paralegal Knowledge Bot    <- This repo (Decision Bot layer)
         |
   Black Hills IP Textbook    <- blackhillsip repo (Knowledge Graph)
         |
  200-Concept Learning Graph   <- Structured domain expertise
```

## Status

Repository initialized. Knowledge graph complete in [blackhillsip](https://github.com/Yarmoluk/blackhillsip). Bot implementation in progress.

## Related

- [Black Hills IP Textbook](https://yarmoluk.github.io/blackhillsip/) — The knowledge graph this bot reasons over
- [TankScan Course](https://yarmoluk.github.io/tankscan-course/) — Similar pattern applied to industrial IoT
- [SEIS 666 Course Text](https://yarmoluk.github.io/Digital-Transformation-with-AI-Spring-2026/) — The methodology behind these experiments

## License

CC BY-NC-SA 4.0
