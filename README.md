# Deliberation Component Prototype

## Overview
Interactive system measuring discourse metrics in citizen-AI dialogue, inspired by Speech-Centred Systems Framework (Meaning Load constraint).

## Features
- 🗣️ Conversational interface for policy questions
- 📊 Real-time discourse metrics (length, sentiment, complexity)
- 💾 CSV export of conversation logs
- 🤝 Built with HuggingFace + Gradio

## Tech Stack
- **Interface:** Gradio (ChatInterface)
- **Model:** DistilGPT2 / Phi-3-mini (switchable)
- **Metrics:** TextBlob (sentiment, sentence analysis)
- **Logging:** Pandas + CSV export

## Motivation
Operationalises interpretive burden as measurable constraint in human-AI democratic engagement.

## Future Work
- Swap to larger models (Phi-3, LLaMA) for quality
- Integrate voting interface UI
- Expand metric set (argument coherence, citation tracking)
- Run user study (n=10+)

## Run Locally
bash pip install gradio transformers textblob pandas python app.py
