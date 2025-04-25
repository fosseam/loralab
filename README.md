# LoRaWAN Lab

**Network Measurement & Device Evaluation Toolkit**  
📡 Signal Testing • 📍 Mapping • 🔬 Device Diagnostics

This repository hosts the content, tools and research behind the *LoRaWAN Lab*. 
First working paper: a modular guide for field-testing LoRaWAN networks, devices, and deployments.

## Structure

- `/papers` → Quarto-based working paper, PDF, raw Markdown
- `/tools`  → Payload decoders, mapping utilities, webhook templates

## Quickstart

To build the PDF from source:

```bash
quarto render papers/lorawan-lab.qmd --to pdf
