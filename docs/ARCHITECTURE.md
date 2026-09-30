# Architecture Notes

HRPN Verification explores an LLM-assisted workflow around health-risk verification and Indian medicine information.

## Components

- Input validation
- Structured medicine data
- Retrieval layer
- LLM reasoning/generation layer
- Application/API layer

The retrieval layer is intended to ground model output in structured project data rather than relying only on model memory.

## Engineering priorities

Correct data handling, traceable retrieval, secure configuration, and explicit uncertainty are more important than maximizing generated text.
