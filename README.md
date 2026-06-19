# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> A curated list of awesome **Model Context Protocol (MCP)** servers, clients, tools, frameworks, and resources.

[Model Context Protocol (MCP)](https://modelcontextprotocol.io) is an open standard by Anthropic that enables AI models to securely connect with external data sources, APIs, and tools. This list covers production-ready MCP servers organized by category.

---

> **Test any remote server on this list instantly →** [MCP Playground Online](https://mcpplaygroundonline.com)
> No install. No setup. Paste your server URL and go.

---

## Contents

- [Official Servers](#official-servers)
- [Developer Tools](#developer-tools)
- [Database & Storage](#database--storage)
- [Communication & Messaging](#communication--messaging)
- [Productivity & Project Management](#productivity--project-management)
- [Finance & Payments](#finance--payments)
- [Infrastructure & DevOps](#infrastructure--devops)
- [Search & Web](#search--web)
- [File & Document Management](#file--document-management)
- [E-commerce](#e-commerce)
- [CRM & Marketing](#crm--marketing)
- [Media & Design](#media--design)
- [Security & Auth](#security--auth)
- [AI & ML](#ai--ml)
- [Testing & Debugging](#testing--debugging)
- [Frameworks & SDKs](#frameworks--sdks)
- [Learning Resources](#learning-resources)
- [Communities](#communities)
- [Contributing](#contributing)

---

## Official Servers

> Maintained by Anthropic or official project partners.

- **[Filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)** — Read, write, move, and manage files and directories on local or remote systems.
- **[GitHub MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/github)** — Interact with GitHub repositories, issues, pull requests, commits, and code search.
- **[GitLab MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab)** — Full GitLab integration including projects, MRs, issues, and CI/CD pipelines.
- **[Google Drive MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)** — Browse, read, and search files stored in Google Drive.
- **[Google Maps MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps)** — Location search, directions, geocoding, and place details via Google Maps API.
- **[PostgreSQL MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** — Natural language to SQL queries against any PostgreSQL database.
- **[Slack MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)** — Send messages, read channels, search conversations, manage Slack workspaces.
- **[Memory MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)** — Persistent, knowledge-graph-based memory for AI sessions.
- **[Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)** — Privacy-focused web and local search via Brave Search API.
- **[Fetch MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)** — Fetch and extract content from any URL, with HTML-to-Markdown conversion.
- **[Puppeteer MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer)** — Browser automation, web scraping, and screenshot capture using Puppeteer.
- **[Sentry MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry)** — Query, analyze, and manage Sentry error tracking and performance monitoring.
- **[Sequential Thinking MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking)** — Dynamic multi-step problem solving and structured reasoning chains.
- **[SQLite MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)** — Direct SQLite database access, query execution, and schema introspection.
- **[Time MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/time)** — Time and timezone conversion tools for multi-region applications.

---

## Developer Tools

> MCP servers that integrate with IDEs, version control, CI/CD, and the developer workflow.

- **[Playwright MCP](https://github.com/microsoft/playwright-mcp)** — Browser automation and end-to-end testing using Microsoft's Playwright framework.
- **[Cursor MCP](https://docs.cursor.com/context/model-context-protocol)** — Native MCP client integration inside the Cursor AI-powered IDE.
- **[VS Code MCP](https://code.visualstudio.com/docs/copilot/model-context-protocol)** — Use MCP servers directly from VS Code with GitHub Copilot integration.
- **[Docker MCP](https://github.com/docker/mcp-server)** — Manage Docker containers, images, volumes, and networks through AI.
- **[Kubernetes MCP](https://github.com/strowger/mcp-kubernetes)** — Query and manage Kubernetes clusters, pods, services, and deployments.
- **[NPM MCP](https://github.com/btakita/mcp-server-npm)** — Interact with the NPM registry, search packages, view package details and versions.
- **[Linear MCP](https://github.com/linear/linear-mcp)** — Create and manage Linear issues, projects, cycles, and team workflows.
- **[Jira MCP](https://github.com/george-thomas-v/mcp-jira)** — Query, create, and update Jira issues, sprints, and project boards.
- **[Vercel MCP](https://github.com/vercel/mcp-adapter)** — Deploy projects, manage domains, view logs, and interact with Vercel via AI.
- **[CircleCI MCP](https://github.com/CircleCI-Public/mcp-server-circleci)** — Trigger pipelines, view build status, and manage CircleCI workflows.
- **[Datadog MCP](https://github.com/DataDog/mcp-server-datadog)** — Query metrics, logs, traces, and monitors from your Datadog account.
- **[Grafana MCP](https://github.com/grafana/mcp-grafana)** — Interact with Grafana dashboards, panels, alerts, and data sources.
- **[New Relic MCP](https://github.com/newrelic/newrelic-mcp-server)** — Query application performance, errors, and infrastructure metrics.
- **[Terraform MCP](https://github.com/hashicorp/terraform-mcp-server)** — Plan, apply, and manage Terraform infrastructure through natural language.
- **[Git MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/git)** — Direct Git repository operations including commits, diffs, branches, and history.

---

## Database & Storage

> Connect AI to your data layer — relational, NoSQL, vector, and beyond.

- **[Supabase MCP](https://github.com/supabase-community/supabase-mcp)** — Full Supabase integration: database, auth, storage, and edge functions.
- **[MySQL MCP](https://github.com/benborla29/mcp-server-mysql)** — Connect to MySQL databases and run natural language queries.
- **[MongoDB MCP](https://github.com/kiliczsh/mcp-mongo-server)** — Query and manage MongoDB collections, documents, and aggregations.
- **[Redis MCP](https://github.com/redis/mcp-redis)** — Interact with Redis for caching, queues, and real-time data operations.
- **[Pinecone MCP](https://github.com/pinecone-io/pinecone-mcp)** — Manage vector indexes and run semantic similarity searches via Pinecone.
- **[Qdrant MCP](https://github.com/qdrant/mcp-server-qdrant)** — Vector search and storage operations using Qdrant as the backend.
- **[Snowflake MCP](https://github.com/datadance/mcp-snowflake)** — Query Snowflake data warehouses and manage compute resources.
- **[BigQuery MCP](https://github.com/LucasHild/mcp-server-bigquery)** — Run Google BigQuery queries and explore datasets via natural language.
- **[PlanetScale MCP](https://github.com/neon-mcp/mcp-planetscale)** — Manage PlanetScale branches, run queries, and explore database schemas.
- **[Neon MCP](https://github.com/neondatabase/mcp-server-neon)** — Serverless Postgres management and query execution via Neon.
- **[Airtable MCP](https://github.com/felores/airtable-mcp)** — Read, write, and manage Airtable bases, tables, and records.
- **[Turso MCP](https://github.com/tursodatabase/turso-mcp)** — Manage edge SQLite databases using Turso's distributed platform.

---

## Communication & Messaging

> Integrate AI into how your team and customers communicate.

- **[Gmail MCP](https://github.com/googleworkspace/gmail-mcp)** — Read, send, search, and manage emails directly through Gmail API.
- **[Outlook MCP](https://github.com/microsoft/outlook-mcp)** — Email management, calendar access, and contact search via Microsoft Outlook.
- **[Discord MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/discord)** — Send messages, read channels, manage servers, and search Discord history.
- **[Telegram MCP](https://github.com/aivilmo/telegram-mcp)** — Send messages, manage groups, and read Telegram chats via the Bot API.
- **[Twilio MCP](https://github.com/twilio-labs/mcp)** — Send SMS, voice calls, and manage Twilio resources programmatically.
- **[Intercom MCP](https://github.com/intercom/intercom-mcp-server)** — Manage Intercom conversations, contacts, and customer support tickets.
- **[Zendesk MCP](https://github.com/zendesk/mcp-server)** — Query, update, and resolve Zendesk support tickets and customer records.
- **[HubSpot MCP](https://github.com/hubspot/mcp-hubspot)** — CRM contacts, deals, tickets, and marketing data via HubSpot.
- **[SendGrid MCP](https://github.com/sendgrid/mcp-server-sendgrid)** — Send transactional emails, manage templates, and track email analytics.

---

## Productivity & Project Management

> Connect AI to the tools your team uses every day.

- **[Notion MCP](https://github.com/makenotion/notion-mcp-server)** — Read, write, and manage Notion pages, databases, and workspaces.
- **[Asana MCP](https://github.com/Asana/mcp-server-asana)** — Create tasks, manage projects, and track team progress in Asana.
- **[Trello MCP](https://github.com/Automattic/mcp-server-trello)** — Manage Trello boards, lists, cards, and team workflows.
- **[ClickUp MCP](https://github.com/clickup/clickup-mcp)** — Task management, docs, whiteboards, and goal tracking via ClickUp.
- **[Monday.com MCP](https://github.com/mondaycom/mcp-server)** — Work management, project tracking, and board automation.
- **[Todoist MCP](https://github.com/abhiz123/todoist-mcp-server)** — Manage tasks, projects, labels, and reminders via Todoist.
- **[Google Calendar MCP](https://github.com/nspady/google-calendar-mcp)** — Read, create, and manage Google Calendar events and invites.
- **[Obsidian MCP](https://github.com/MarkusMcNugen/mcp-obsidian)** — Read and write to Obsidian vaults, search notes, and manage knowledge bases.
- **[Confluence MCP](https://github.com/atlassian-labs/mcp-atlassian)** — Read and write Confluence pages, spaces, and company documentation.
- **[Coda MCP](https://github.com/coda/coda-mcp)** — Interact with Coda docs, tables, views, and automated workflows.

---

## Finance & Payments

> Bring financial data and payment intelligence into your AI workflows.

- **[Stripe MCP](https://github.com/stripe/agent-toolkit)** — Query payment data, manage customers, retrieve subscriptions and invoices.
- **[Plaid MCP](https://github.com/plaid/mcp-plaid)** — Access bank account data, transactions, and financial insights via Plaid.
- **[QuickBooks MCP](https://github.com/intuit/mcp-server-quickbooks)** — Manage invoices, expenses, customers, and accounting in QuickBooks.
- **[Xero MCP](https://github.com/xeroapi/mcp-server-xero)** — Access Xero accounting data: invoices, contacts, bank feeds, and reports.
- **[Coinbase MCP](https://github.com/coinbase/agentkit/tree/main/typescript/agentkit)** — Crypto wallet management, transactions, and real-time price data via Coinbase.
- **[CoinGecko MCP](https://github.com/mcp-servers/mcp-coingecko)** — Live cryptocurrency prices, market data, and token information.
- **[Alpaca MCP](https://github.com/alpacahq/mcp-alpaca)** — Stock trading, portfolio management, and market data via Alpaca API.

---

## Infrastructure & DevOps

> Manage cloud infrastructure, deployments, and platform operations.

- **[Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare)** — Manage Workers, KV storage, DNS, R2, and analytics via Cloudflare.
- **[AWS MCP](https://github.com/aws/mcp-server-aws)** — Interact with AWS services: S3, EC2, Lambda, RDS, and CloudWatch.
- **[GCP MCP](https://github.com/GoogleCloudPlatform/mcp-server-gcp)** — Manage Google Cloud resources, BigQuery, GCS, and GKE clusters.
- **[Azure MCP](https://github.com/Azure/azure-mcp)** — Azure resource management, deployments, and monitoring.
- **[Fly.io MCP](https://github.com/superfly/mcp-fly)** — Deploy apps, manage machines, and view logs on Fly.io.
- **[Railway MCP](https://github.com/railwayapp/mcp-railway)** — Manage Railway deployments, services, and environment variables.
- **[Render MCP](https://github.com/rendercom/mcp-render)** — Deploy and manage services, databases, and static sites on Render.
- **[PagerDuty MCP](https://github.com/PagerDuty/mcp-server-pagerduty)** — Manage incidents, on-call schedules, and alert policies.
- **[Prometheus MCP](https://github.com/prom/mcp-prometheus)** — Query Prometheus metrics, alerts, and recording rules via PromQL.

---

## Search & Web

> Give your AI assistant the ability to browse, search, and extract from the web.

- **[Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)** — Privacy-first web and news search powered by Brave.
- **[Tavily MCP](https://github.com/tavily-ai/mcp-tavily)** — AI-optimized web search with real-time results and source citations.
- **[Exa MCP](https://github.com/exa-labs/exa-mcp-server)** — Semantic web search designed for AI agents with high-quality results.
- **[Perplexity MCP](https://github.com/ppl-ai/mcp-perplexity)** — AI-powered research and question answering with live web access.
- **[SerpAPI MCP](https://github.com/serpapi/mcp-serpapi)** — Google, Bing, and YouTube search results via the SerpAPI platform.
- **[Firecrawl MCP](https://github.com/mendableai/firecrawl-mcp-server)** — Scrape, crawl, and extract clean data from any website at scale.
- **[Apify MCP](https://github.com/apify/mcp-server-apify)** — Run web scraping actors and manage datasets on the Apify platform.
- **[Wikipedia MCP](https://github.com/mcp-servers/mcp-wikipedia)** — Search and retrieve Wikipedia articles, summaries, and structured data.

---

## File & Document Management

> Work with documents, PDFs, spreadsheets, and local files through AI.

- **[Google Docs MCP](https://github.com/googleworkspace/google-docs-mcp)** — Create, read, and edit Google Docs with full formatting support.
- **[Google Sheets MCP](https://github.com/googleworkspace/google-sheets-mcp)** — Read, write, and analyze spreadsheet data in Google Sheets.
- **[OneDrive MCP](https://github.com/microsoft/onedrive-mcp)** — Browse, read, and manage files stored in Microsoft OneDrive.
- **[Dropbox MCP](https://github.com/dropbox/mcp-dropbox)** — File access, search, and management for Dropbox storage.
- **[Box MCP](https://github.com/box/box-mcp-server)** — Enterprise content management and file operations via Box.
- **[PDF MCP](https://github.com/mcp-servers/mcp-pdf)** — Parse, extract, and query text and metadata from PDF documents.
- **[Excel MCP](https://github.com/mcp-servers/mcp-excel)** — Read and write Excel files, formulas, and structured spreadsheet data.

---

## E-commerce

> Power AI shopping experiences, inventory management, and order workflows.

- **[Shopify MCP](https://github.com/shopify/dev-mcp)** — Products, orders, customers, and inventory management via Shopify Admin API.
- **[WooCommerce MCP](https://github.com/mcp-servers/mcp-woocommerce)** — Manage WooCommerce store products, orders, and customer data.
- **[Amazon MCP](https://github.com/mcp-servers/mcp-amazon-sp)** — Amazon Seller Partner API for inventory, orders, and product listings.
- **[Magento MCP](https://github.com/mcp-servers/mcp-magento)** — Magento store management including catalog, orders, and CMS pages.
- **[BigCommerce MCP](https://github.com/bigcommerce/mcp-bigcommerce)** — Product catalog, storefront, and order management via BigCommerce.

---

## CRM & Marketing

> Connect AI to customer data, campaigns, and sales pipelines.

- **[Salesforce MCP](https://github.com/salesforce/mcp-server-salesforce)** — Query and update Salesforce CRM records, leads, opportunities, and reports.
- **[HubSpot MCP](https://github.com/hubspot/mcp-hubspot)** — Contacts, deals, campaigns, and marketing analytics from HubSpot CRM.
- **[Mailchimp MCP](https://github.com/mcp-servers/mcp-mailchimp)** — Manage email campaigns, audiences, and automation in Mailchimp.
- **[ActiveCampaign MCP](https://github.com/mcp-servers/mcp-activecampaign)** — Marketing automation, contact management, and campaign analytics.
- **[Pipedrive MCP](https://github.com/pipedrive/mcp-pipedrive)** — Sales pipeline management, deal tracking, and activity logging.
- **[Klaviyo MCP](https://github.com/klaviyo/mcp-klaviyo)** — E-commerce email and SMS marketing automation via Klaviyo.
- **[PostHog MCP](https://github.com/PostHog/mcp-server-posthog)** — Product analytics, feature flags, session recordings, and A/B tests.
- **[Mixpanel MCP](https://github.com/mcp-servers/mcp-mixpanel)** — Event analytics, user segmentation, and funnel analysis from Mixpanel.
- **[NotFair](https://github.com/nowork-studio/NotFair)** — Open-source Claude Code skills for SEO, GEO, Google Ads, and Meta Ads, connecting to live data through Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP.

---

## Media & Design

> AI-powered workflows for creative and visual content.

- **[Figma MCP](https://github.com/GLips/Figma-Context-MCP)** — Read Figma file contents, extract design tokens, and inspect components.
- **[Cloudinary MCP](https://github.com/cloudinary/mcp-server-cloudinary)** — Upload, transform, and manage media assets via Cloudinary.
- **[YouTube MCP](https://github.com/mcp-servers/mcp-youtube)** — Search videos, retrieve transcripts, and access YouTube channel data.
- **[Spotify MCP](https://github.com/varunneal/spotify-mcp)** — Search tracks, manage playlists, and control Spotify playback.
- **[Unsplash MCP](https://github.com/mcp-servers/mcp-unsplash)** — Search and download high-quality stock photography from Unsplash.
- **[Canva MCP](https://github.com/canva-public/mcp-server-canva)** — Access Canva designs, templates, and brand assets via the Canva API.

---

## Security & Auth

> Bring security operations, secrets management, and access control into your AI workflow.

- **[1Password MCP](https://github.com/1password/mcp-server)** — Retrieve secrets, credentials, and secure notes from 1Password vaults.
- **[HashiCorp Vault MCP](https://github.com/hashicorp/vault-mcp)** — Dynamic secrets management and policy enforcement via Vault.
- **[Okta MCP](https://github.com/okta/mcp-server-okta)** — User and group management, SSO configuration, and identity governance.
- **[Auth0 MCP](https://github.com/auth0/auth0-mcp-server)** — Manage Auth0 applications, users, rules, and authentication policies.
- **[Snyk MCP](https://github.com/snyk/mcp-server-snyk)** — Scan code and containers for vulnerabilities and license issues.
- **[VirusTotal MCP](https://github.com/mcp-servers/mcp-virustotal)** — Analyze files, URLs, and IPs for malware and security threats.

---

## AI & ML

> Compose MCP with other AI models, vector stores, and ML pipelines.

- **[OpenAI MCP](https://github.com/mcp-servers/mcp-openai)** — Call GPT models, generate embeddings, and manage OpenAI assistants.
- **[Replicate MCP](https://github.com/replicate/mcp-server)** — Run open-source AI models for image, video, audio, and text generation.
- **[LangChain MCP](https://github.com/langchain-ai/mcp-langchain)** — Use LangChain tools and agents as MCP-compatible servers.
- **[Hugging Face MCP](https://github.com/huggingface/mcp-server-hf)** — Access Hugging Face models, datasets, and inference endpoints.
- **[Weaviate MCP](https://github.com/weaviate/mcp-weaviate)** — Semantic search and vector operations using Weaviate.
- **[Chroma MCP](https://github.com/chroma-core/mcp-server-chroma)** — Open-source vector database operations and similarity search.

---

## Testing & Debugging

> Verify, test, and debug MCP server implementations before going to production.

- **[MCP Playground Online](https://mcpplaygroundonline.com)** ⭐ — **Free browser-based tool to test any MCP server.** Connect via HTTP, SSE, or WebSocket. Browse tools, resources, and prompts. Execute live requests. No install required.
- **[MCP Inspector](https://github.com/modelcontextprotocol/inspector)** — Official CLI inspector from Anthropic for debugging MCP server implementations.
- **[MCP Test](https://github.com/mcp-servers/mcp-test)** — Unit testing framework for MCP server tools and prompt templates.
- **[MCP Validator](https://github.com/mcp-servers/mcp-validator)** — Spec compliance validator — checks your server against the official MCP specification.
- **[MCP Mock Server](https://github.com/mcp-servers/mcp-mock)** — Generate mock MCP servers for client testing and development workflows.

---

## Frameworks & SDKs

> Build your own MCP servers faster with these libraries and frameworks.

### TypeScript / JavaScript
- **[MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)** — Official TypeScript SDK for building MCP servers and clients.
- **[FastMCP](https://github.com/jlowin/fastmcp)** — High-level framework for building MCP servers with minimal boilerplate.
- **[mcp-framework](https://github.com/QuantGeekDev/mcp-framework)** — Opinionated framework for production MCP servers with routing and middleware.

### Python
- **[MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)** — Official Python SDK for building MCP servers and clients.
- **[FastMCP (Python)](https://github.com/jlowin/fastmcp)** — Pythonic high-level MCP server framework with decorators and type inference.
- **[mcp-python-template](https://github.com/mcp-servers/python-template)** — Production-ready Python MCP server template with auth, logging, and tests.

### Other Languages
- **[mcp-go](https://github.com/mark3labs/mcp-go)** — Go SDK for building lightweight, high-performance MCP servers.
- **[mcp-rs](https://github.com/mcp-servers/mcp-rs)** — Rust SDK for building secure, memory-safe MCP server implementations.
- **[mcp-java](https://github.com/modelcontextprotocol/java-sdk)** — Official Java SDK for enterprise MCP server development.
- **[mcp-dotnet](https://github.com/modelcontextprotocol/csharp-sdk)** — C# / .NET SDK for MCP server and client development.

### Utilities
- **[mcp-proxy](https://github.com/sparfenyuk/mcp-proxy)** — Proxy server for running stdio MCP servers via SSE transport.
- **[mcp-gateway](https://github.com/mcp-servers/mcp-gateway)** — API gateway for managing multiple MCP servers with auth and rate limiting.
- **[RapidMCP](https://github.com/mcp-servers/rapidmcp)** — Transform existing REST APIs into MCP servers with zero code changes.
- **[Auto-MCP](https://github.com/mcp-servers/auto-mcp)** — Auto-generate MCP servers for CrewAI, LangGraph, and agent frameworks.

---

## Learning Resources

> Tutorials, guides, courses, and reference material to master MCP.

### Official Documentation
- **[MCP Official Docs](https://modelcontextprotocol.io/docs)** — Complete specification, concepts, and quickstart guides.
- **[MCP Specification](https://modelcontextprotocol.io/specification)** — Full technical specification (Nov 2025 release).
- **[MCP Roadmap](https://modelcontextprotocol.io/development/roadmap)** — Upcoming features and planned protocol improvements.
- **[MCP Blog](https://blog.modelcontextprotocol.io)** — Official announcements, case studies, and protocol updates.

### Tutorials & Guides
- **[Build Your First MCP Server](https://modelcontextprotocol.io/quickstart/server)** — Official step-by-step guide to your first MCP server in TypeScript or Python.
- **[MCP for Beginners](https://mcpplaygroundonline.com/blog)** — Practical beginner articles with zero-setup testing via MCP Playground.
- **[MCP Security Best Practices](https://mcpplaygroundonline.com/blog/mcp-security)** — Auth patterns, token handling, and safe production deployment.
- **[MCP Transports Explained](https://mcpplaygroundonline.com/blog)** — HTTP vs SSE vs WebSocket — when to use each transport method.

### Videos
- **[MCP Explained in 5 Minutes](https://www.youtube.com/watch?v=dQw4w9WgXcQ)** — Concise protocol overview for developers new to MCP.
- **[Build a Production MCP Server](https://www.youtube.com/results?search_query=build+mcp+server)** — End-to-end walkthrough from scaffolding to deployment.

### Newsletters & Blogs
- **[The New Stack — MCP Coverage](https://thenewstack.io/tag/mcp)** — News and analysis on MCP adoption and ecosystem growth.
- **[AI Engineer Weekly](https://aiengineering.substack.com)** — MCP and AI tooling news for working engineers.

---

## Communities

> Where MCP developers ask questions, share projects, and collaborate.

- **[MCP Discord](https://discord.gg/modelcontextprotocol)** — Official Model Context Protocol Discord community.
- **[r/ClaudeAI](https://reddit.com/r/ClaudeAI)** — Reddit community with active MCP discussion threads.
- **[r/LocalLLaMA](https://reddit.com/r/LocalLLaMA)** — Open-source AI community, frequent MCP integration threads.
- **[Hacker News — MCP Tag](https://hn.algolia.com/?q=model+context+protocol)** — HN discussions on MCP launches and technical deep-dives.
- **[GitHub Discussions — MCP Servers](https://github.com/modelcontextprotocol/servers/discussions)** — Official repo discussions for server development questions.

---

## Tools & Directories

> Discover, browse, and manage MCP servers.

- **[MCP Playground Online](https://mcpplaygroundonline.com)** — Test any MCP server in your browser. Supports HTTP, SSE, and WebSocket. Free, no login required.
- **[MCP Servers Directory](https://mcpplaygroundonline.com/mcps)** — Curated, searchable directory of production-ready MCP servers.
- **[MCP Prompt Library](https://mcpplaygroundonline.com/prompts)** — Pre-built prompts for common MCP workflows, ready to use.
- **[MCP Registry](https://registry.modelcontextprotocol.io)** — Official Anthropic MCP server registry with 2000+ entries.
- **[mcp.so](https://mcp.so)** — Community-driven MCP server discovery and rating platform.
- **[Smithery](https://smithery.ai)** — MCP server marketplace with one-click install and configuration.
- **[PulseMCP](https://pulsemcp.com)** — Weekly newsletter tracking new MCP server releases and updates.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

### How to Add a Server

1. **Fork** this repository
2. **Add your entry** to the relevant category in alphabetical order
3. Follow the format: `- **[Name](URL)** — One-sentence description of what it does.`
4. Make sure the server is:
   - Publicly accessible or clearly documented
   - Actively maintained (last commit within 6 months)
   - Genuinely useful — no spam, no link farms
5. **Open a pull request** with a brief description of the server

### Quality Standards

- Servers must implement the MCP spec correctly
- Must have a public README with setup instructions
- No duplicate entries — check existing list before adding
- Descriptions must be objective, not promotional

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0 — freely use, share, and build on it.

---

<p align="center">
  <sub>
    Test any server on this list for free at
    <a href="https://mcpplaygroundonline.com">MCP Playground Online</a> —
    no install, no setup required.
  </sub>
</p>
