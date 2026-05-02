<div align="center">

![Infomundi Logo](https://raw.githubusercontent.com/Infomundi-Project/.github/refs/heads/main/logo-wordmark-on-white.svg)

</div>

## Overview

[Infomundi](https://infomundi.net/) is a news aggregation and social platform built to simplify access to global information. We collect stories from well over 10,000 publishers worldwide, process them with AI for summaries, sentiment analysis and keyword extraction, then cluster related stories so you can see how the same event is reported across different countries and sources.

Beyond news, Infomundi is a community. Discuss stories with other readers, create and join groups with text and voice channels, share your own posts, and build a profile that reflects your interests. Our leveling system rewards active participation, turning informed reading into an engaging experience.

## Key Features

- **📰 Global News Aggregation**: Automatically fetches and processes news across multiple countries and categories
- **🤖 AI-Powered Summaries**: LLM integration for intelligent story summarization
- **🦁 Maximus AI Assistant**: Conversational news analyst on individual stories, clusters, and country pages
- **🌍 Geographic Organization**: Browse news by region, country, topics and more
- **📊 Story Clustering & Sentiment Analysis**: Groups related stories and analyzes sentiment across publishers
- **🔴 Breaking News Ticker**: Detects fast-developing clusters, surfaces them in a live ticker below the masthead and pushes in-app + email notifications to opted-in users
- **🔊 Text-to-Speech**: Audio playback for story content
- **🔎 Full-Text Search**: Near-instant story search across millions of stories
- **✍️ Article Submission**: Plus/Premium users can submit articles from registered publisher domains
- **👥 Social Features**: User profiles, friendships, comments, reactions, notifications and more
- **💬 Real-Time Chat**: Chat system for live discussions
- **👥 Groups & Channels**: Create communities with text channels, voice chat, roles, and moderation
- **📝 Community Posts**: User-generated posts with images, reactions, and comments
- **🎙️ Voice Chat**: Voice channels within groups
- **🏆 Leveling & XP System**: Gamified user progression based on platform activity
- **💳 Subscription Tiers**: Free / Plus / Premium tiers with daily quotas on AI features
- **🔐 Security-First**: AES-GCM email encryption, Argon2id password hashing, CSRF protection, rate limiting
- **🌐 Backend i18n**: Translated flash messages, and emails to the recipient's preferred language (EN / PT today)
- **🔑 2FA Support**: Both TOTP (authenticator apps) and email-based two-factor authentication
- **🖥️ Known-Device Tracking**: Device fingerprint cookies, new-device email verification, session-trust window
- **🎨 Customizable Profiles**: Avatars, banners, wallpapers, privacy settings, and profile descriptions
- **🔍 Keyword Extraction**: Algorithm for automatic story tagging
- **🚀 Performance**: Redis caching, optimized database queries, AVIF image format

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
