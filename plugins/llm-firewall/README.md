# LLM Firewall Plugin

A phrase-based prompt filtering plugin for Tyk AI Studio's Microgateway. This plugin detects disallowed phrases in incoming prompts and blocks requests that contain policy violations before they reach the LLM.

## Features

- **Phrase-based filtering** - Block requests containing specific phrases or patterns
- **Regex support** - Use regular expressions for complex pattern matching
- **Model-specific rules** - Apply different rules to different LLM models using glob patterns
- **Multi-vendor support** - Works with OpenAI, Anthropic, Google AI, Vertex, and Ollama
- **Configurable hook phase** - Run checks before or after authentication
- **Privacy-preserving** - Logs matched patterns only, not request content
- **Fail-open design** - Allows requests through if parsing fails (configurable)

## Installation

Pull the plugin using:

```
/plugins/llm-firewall:1.0
```

## Configuration

See the plugin configuration options in Tyk AI Studio after installation.

## Support

For questions or issues, visit the [Tyk Community Forums](https://community.tyk.io).
