# Infomundi

<div align="center">

![Infomundi Logo](https://raw.githubusercontent.com/behindsecurity/behindsecurity/refs/heads/main/images/infomundi-nobg.webp)

</div>

## Overview

Infomundi is a news aggregation and social platform that collects stories from publishers worldwide, processes them with AI-powered summarization, and provides a social layer for users to engage with global news. The platform organizes content by geographic regions and categories, making it easy to discover news from any part of the world.

### Key Features

- **📰 Global News Aggregation**: Automatically fetches and processes news from publishers across multiple countries and categories
- **🤖 AI-Powered Summaries**: AI integration for intelligent story summarization
- **🌍 Geographic Organization**: Browse news by region, country, and category
- **📊 Story Clustering & Sentiment Analysis**: Groups related stories and analyzes sentiment across publishers
- **🔊 Text-to-Speech**: Audio playback for story content
- **👥 Social Features**: User profiles, friendships, comments, reactions, and notifications
- **💬 Real-Time Chat**: WebSocket-powered end to end encrypted chat system for live discussions
- **🏆 Leveling & XP System**: Gamified user progression based on platform activity
- **🔑 2FA Support**: Both TOTP (authenticator apps) and email-based two-factor authentication
- **📈 Analytics**: Site statistics, story views, trending content
- **🎨 Customizable Profiles**: Avatars, banners, wallpapers, privacy settings, and profile descriptions

## Security Features

Infomundi implements defense-in-depth security:

- **Email Privacy**: Emails always encrypted at rest with AES-GCM, searchable via HMAC fingerprints
- **Password Security**: Argon2id hashing with high cost parameters
- **CSRF Protection**: Flask-WTF tokens on all forms
- **Rate Limiting**: Flask-Limiter on authentication and API endpoints
- **Input Validation**: Comprehensive sanitization with bleach
- **Session Management**: Secure cookies with version invalidation
- **2FA Options**: TOTP (RFC 6238) and email-based verification
- **CAPTCHA**: Cloudflare Turnstile with custom fallback
- **WAF**: Fine-tuned WAF rules acting as the first barrier to the production website

---

<div align="center">

**Made with ❤️ by the Infomundi team**

</div>
