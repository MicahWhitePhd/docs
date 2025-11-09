# Outcry AI API Documentation

Official API documentation for Outcry AI - The AI-powered activist mentor platform.

🔗 **Live Docs**: [docs.outcryai.com](https://docs.outcryai.com)
🔑 **Get API Key**: [www.outcryai.com/register](https://www.outcryai.com/register)
🌐 **Main Site**: [www.outcryai.com](https://www.outcryai.com)

## Overview

This repository contains the complete API documentation for Outcry AI, built with [Mintlify](https://mintlify.com).

Our API provides:
- **Chat API** - AI-powered activist guidance with theory of change customization
- **Video API** - AI video generation with Sora 2 models
- **Text API** - Single-shot text completions
- **Webhooks** - Real-time event notifications

## 100% OpenAI Compatible

The Outcry AI API is designed to be 100% compatible with OpenAI's API format. Simply change the base URL:

```typescript
import OpenAI from 'openai';

const client = new OpenAI({
  apiKey: 'oc_live_...',
  baseURL: 'https://api.outcryai.com/v1'  // Only difference!
});
```

## Documentation Structure

- **`/api`** - Complete API reference for all endpoints
  - `/api/chat` - Chat completions
  - `/api/text` - Text completions
  - `/api/videos` - Video generation
  - `/api/webhooks` - Webhook management
- **`/guides`** - Implementation guides
  - Authentication
  - Webhooks
  - Theory of Change
  - Error handling
  - Rate limiting
  - Best practices
- **`/examples`** - Code examples
  - Video generation
  - Chat completions
  - Webhook setup
  - Framework integrations

## Development

This documentation is built with Mintlify and automatically deploys when changes are pushed to the main branch.

### Local Preview

```bash
# Install Mintlify CLI
npm i -g mintlify

# Preview docs locally
mintlify dev
```

### Contributing

Documentation improvements are welcome! Please:
1. Fork this repository
2. Make your changes
3. Submit a pull request

## Support

- **Documentation Issues**: [GitHub Issues](https://github.com/micahwhitephd/docs/issues)
- **API Support**: support@outcryai.com
- **Community**: [Discord](https://discord.gg/outcryai)

## License

Documentation is licensed under MIT. See [LICENSE](LICENSE) for details.

---

Built with ❤️ by the Outcry AI team
