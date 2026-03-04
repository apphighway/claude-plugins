# AppHighway — Claude Code Plugin Marketplace

> 159 MCP tools for AI agents

## Installation

In Claude Code, add this marketplace:

```
apphighway/claude-plugins
```

Then install any tool:

```
/plugin install <tool-name>@apphighway-tools
```

## Setup

Set your API key as environment variable:

```bash
export APPHIGHWAY_API_KEY="your-api-key-here"
```

Get your API key at [apphighway.com/dashboard/tokens](https://apphighway.com/dashboard/tokens).

## Available Tools (159)

### ai

- **sentiment-analysis** — Analyze text sentiment with confidence scores (2 pts)
- **text-generation** — Generate text from prompts with style control (5 pts)
- **language-translation** — Translate text between 50+ languages (4 pts)
- **text-summarization** — Summarize long texts into concise summaries (4 pts)
- **grammar-checker** — Check and correct grammar, spelling, and style (4 pts)
- **chatbot-completion** — Generate conversational AI responses (3 pts)
- **entity-extraction** — Extract named entities from text using AI (4 pts)
- **text-to-speech** — Convert text to natural-sounding audio (5 pts)
- **ocr** — Extract text from images using AI vision (5 pts)
- **language-detection** — Detect the language of any text (3 pts)
- **paraphrase** — Rewrite text while preserving meaning (4 pts)
- **speech-to-text** — Transcribe audio to text with timestamps (6 pts)
- **text-embedding** — Generate vector embeddings for text (3 pts)
- **keyword-extractor** — Extract keywords and key phrases from text (3 pts)
- **content-classifier** — Classify text into custom categories using AI (4 pts)
- **question-answering** — Answer questions based on provided context (5 pts)
- **profanity-filter** — Detect and filter profanity in text (2 pts)
- **plagiarism-detector** — Detect plagiarism and content similarity (4 pts)
- **semantic-search** — Search documents by meaning, not just keywords (4 pts)
- **intent-detection** — Detect user intent from natural language (3 pts)
- **readability-analyzer** — Analyze text readability with multiple metrics (1 pts)
- **meeting-summarizer** — AI-powered meeting transcript analysis with action items and decisions (4 pts)
- **review-summarizer** — Summarize product reviews into insights (5 pts)
- **product-summary** — Generate product descriptions from features (5 pts)
- **topic-modeling** — Discover topics in text collections (4 pts)
- **resume-analyzer** — AI-powered resume analysis with ATS scoring and skills extraction (5 pts)
- **contract-analyzer** — AI-powered legal document analysis with risk assessment and plain-language summary (6 pts)
- **qa-extractor** — Extract Q&A pairs from content (5 pts)
- **feedback-cluster** — Cluster user feedback into themes (4 pts)
- **pitch-deck-analyzer** — AI-powered pitch deck analysis with investor readiness scoring (6 pts)
- **prompt-optimizer** — AI-powered prompt optimization for LLMs (5 pts)
- **churn-predictor** — Predict customer churn from usage data using AI (6 pts)
- **social-media-post-generator** — AI-generated platform-optimized social media posts (3 pts)
- **technical-spec-generator** — AI-generated technical specification documents (5 pts)
- **user-story-generator** — AI-generated user stories with acceptance criteria (3 pts)
- **api-doc-generator** — Generate OpenAPI specs from code using AI (5 pts)
- **sql-explainer** — Explain complex SQL queries in plain language with optimization tips (3 pts)
- **commit-message-generator** — Generate conventional commit messages from git diffs (3 pts)
- **code-converter** — Convert code between programming languages (4 pts)
- **regex-generator** — Generate regex patterns from natural language descriptions (3 pts)
- **pr-description-generator** — Generate structured pull request descriptions from diffs (4 pts)
- **seo-analyzer** — AI-powered SEO analysis with scoring and recommendations (5 pts)
- **readme-generator** — AI-generated project README from description and tech stack (4 pts)
- **financial-report-analyzer** — AI-powered financial report analysis with KPIs and recommendations (7 pts)
- **release-notes-generator** — AI-generated release notes from changes and commits (3 pts)
- **funnel-analyzer** — Analyze conversion funnels with AI insights (5 pts)
- **changelog-parser** — Parse changelogs into customer-friendly release announcements (3 pts)
- **incident-postmortem-generator** — AI-generated blameless incident postmortems (5 pts)
- **alt-text-generator** — Generate accessible alt text descriptions following WCAG guidelines (3 pts)

### automation

- **webhook-builder** — Build and validate webhook payloads with HMAC signing (3 pts)
- **workflow-generator** — AI-generated automation workflows (n8n/Zapier format) (6 pts)

### communication

- **email-template-generator** — AI-generated responsive HTML email templates (3 pts)
- **ical-generator** — Create calendar events in .ics format (1 pts)

### data

- **structify** — Convert unstructured text to structured JSON using AI (3 pts)
- **currency-converter** — Convert between 150+ world currencies (1 pts)
- **csv-to-json** — Convert CSV data to structured JSON with type inference (2 pts)
- **weather-forecast** — Get weather forecasts for any location (2 pts)
- **url-metadata** — Extract metadata from any URL (1 pts)
- **json-validator** — Validate JSON against schemas with detailed error reports (1 pts)
- **unit-converter** — Convert between measurement units (1 pts)
- **json-to-csv** — Convert JSON arrays to CSV format (2 pts)
- **ip-geolocation** — Geolocate IP addresses worldwide (2 pts)
- **html-to-markdown** — Convert HTML pages to clean Markdown (2 pts)
- **xml-to-json** — Parse XML documents into clean JSON (2 pts)
- **timezone-converter** — Convert times between timezones worldwide (1 pts)
- **url-shortener** — Generate short URLs with tracking (1 pts)
- **markdown-to-html** — Render Markdown to sanitized HTML (2 pts)
- **yaml-to-json** — Convert YAML to JSON with schema validation (2 pts)
- **geo-locate** — Geocode addresses and coordinates (2 pts)
- **excel-to-json** — Parse Excel spreadsheets into JSON data (3 pts)
- **whois-lookup** — Query domain registration information (2 pts)
- **color-converter** — Convert between color formats (HEX, RGB, HSL) (1 pts)
- **html-sanitizer** — Sanitize HTML to prevent XSS attacks (2 pts)
- **data-anonymizer** — Anonymize PII in text data using AI (3 pts)
- **number-summarizer** — Calculate statistics from number sets (1 pts)
- **pricing-page-parser** — Extract pricing data from web pages (3 pts)
- **spreadsheet-analyzer** — Analyze CSV/JSON data for quality issues and statistics (2 pts)
- **toml-to-json** — Convert between TOML and JSON formats (1 pts)
- **mongodb-query-builder** — AI-powered natural language to MongoDB query conversion (3 pts)
- **tax-calculator** — Estimate income tax for DE/US/UK with progressive brackets (2 pts)
- **sql-formatter** — Format and indent SQL queries for readability (1 pts)
- **migration-generator** — Generate SQL migrations from schema diff descriptions (4 pts)
- **data-profiler** — Profile CSV/JSON datasets with statistics and quality analysis (3 pts)
- **schema-analyzer** — AI-powered database schema analysis with optimization suggestions (5 pts)
- **crypto-price** — Get real-time cryptocurrency prices via CoinGecko API (2 pts)
- **loan-calculator** — Calculate loan payments, interest, and amortization schedules (1 pts)
- **invoice-generator** — Generate structured invoice data with line items, taxes, and totals (2 pts)
- **query-builder** — Convert natural language to SQL queries with schema context (4 pts)
- **prometheus-query-builder** — AI-powered natural language to PromQL conversion (3 pts)
- **mortgage-calculator** — Calculate mortgage payments with amortization schedule (1 pts)
- **graphql-schema-generator** — AI-generated GraphQL SDL schemas from descriptions (4 pts)
- **json-diff** — Compare two JSON objects and output structured differences (1 pts)

### dev-tools

- **uuid-generator** — Generate UUIDs (v4, v5, v7) in bulk (1 pts)
- **hash-generator** — Generate MD5, SHA-256, and other hashes (1 pts)
- **password-generator** — Generate secure random passwords (1 pts)
- **email-validator** — Validate email addresses with DNS and format checks (1 pts)
- **base64-encode-decode** — Encode and decode Base64 strings (1 pts)
- **code-generator** — Generate code from natural language descriptions (5 pts)
- **qr-generator** — Generate QR codes with custom styling (2 pts)
- **regex-explainer** — Explain, generate, and test regular expressions with AI and server-side execution (2 pts)
- **dns-lookup** — Perform DNS queries for any domain (1 pts)
- **code-docstring** — Generate documentation for code functions (6 pts)
- **sql-optimizer** — AI-powered SQL query optimization with performance scoring and index suggestions (4 pts)
- **title-generator** — Generate catchy titles and headlines (4 pts)
- **tone-rewriter** — Rewrite text in a different tone or style (4 pts)
- **business-name** — Generate creative business name suggestions (4 pts)
- **barcode-generator** — Generate barcodes in various formats (2 pts)
- **code-reviewer** — AI-powered deep code review with security analysis and fix suggestions (5 pts)
- **error-log-summarizer** — Summarize and categorize error logs using AI (3 pts)
- **text-outline** — Generate structured outlines for any topic (5 pts)
- **website-analyzer** — Comprehensive website analysis — SEO, performance, security, accessibility, and tech detection (5 pts)
- **changelog-generator** — Generate changelogs from commit messages (2 pts)
- **feature-idea-generator** — Generate product feature ideas using AI (6 pts)
- **cron-explainer** — Translate cron expressions to human-readable descriptions (1 pts)
- **vulnerability-scanner** — AI scans code for OWASP Top 10 vulnerabilities (5 pts)
- **test-generator** — AI-generated unit tests from code (Jest, Vitest, pytest) (5 pts)
- **csp-generator** — Generate Content Security Policy headers from rules (1 pts)
- **ab-test-calculator** — Calculate A/B test statistical significance (3 pts)
- **api-request-builder** — Build HTTP requests as cURL/fetch/axios/Python code (2 pts)
- **security-headers-analyzer** — Analyze HTTP security headers with scoring (3 pts)
- **jwt-decoder** — Decode JWT tokens showing header, payload, and expiry (1 pts)
- **password-strength** — Analyze password strength with entropy and pattern detection (1 pts)
- **github-actions-generator** — AI-generated CI/CD workflows for GitHub Actions (3 pts)
- **nginx-config-generator** — Generate Nginx configuration files (2 pts)
- **k8s-manifest-generator** — AI-generated Kubernetes manifests (Deployment, Service, Ingress) (5 pts)
- **dockerfile-generator** — AI-generated optimized Dockerfiles from tech stack (3 pts)
- **bundle-size-analyzer** — Analyze npm package sizes and suggest lighter alternatives (3 pts)
- **openapi-spec-generator** — AI-generated OpenAPI 3.1 specifications from descriptions (5 pts)
- **regex-tester** — Test regex patterns with captures and explanations (1 pts)
- **shell-script-generator** — AI-generated shell scripts from descriptions (3 pts)
- **docker-compose-generator** — AI-generated docker-compose.yml from service descriptions (3 pts)
- **e2e-test-generator** — AI-generated end-to-end tests (Playwright/Cypress) (5 pts)
- **token-counter** — Count LLM tokens with model-specific ratios (1 pts)
- **semver-calculator** — Parse, compare, and validate semantic versions and ranges (1 pts)
- **chmod-calculator** — Convert Unix file permissions between octal and symbolic formats (1 pts)
- **base-converter** — Convert numbers between binary, octal, decimal, hex, and custom bases (1 pts)
- **load-test-generator** — Generate load test scripts for k6, Locust, and Artillery (5 pts)
- **compliance-checker** — Check code for GDPR, HIPAA, PCI-DSS, SOC2 compliance (5 pts)
- **terraform-module-generator** — AI-generated Terraform modules for cloud infrastructure (5 pts)
- **http-status-reference** — Look up HTTP status codes with descriptions and troubleshooting (1 pts)
- **htaccess-generator** — Generate Apache .htaccess rules for redirects, security, and caching (1 pts)
- **secret-detector** — Scan code for leaked secrets (API keys, tokens, passwords) (2 pts)
- **cors-config-generator** — Generate CORS configurations for multiple frameworks (2 pts)
- **accessibility-checker** — AI-powered WCAG 2.1 compliance checker (3 pts)
- **fake-data-generator** — Generate realistic test data (names, emails, addresses) (2 pts)
- **ip-subnet-calculator** — Calculate IPv4 subnet details from CIDR notation (1 pts)
- **env-validator** — Validate .env files against schema definitions (1 pts)

### productivity

- **image-resize** — Resize and optimize images in bulk (3 pts)
- **pdf-to-text** — Extract text content from PDF documents (4 pts)
- **pdf-merger** — Merge multiple PDF documents into one (3 pts)
- **screenshot-capture** — Capture screenshots of any webpage (5 pts)
- **random-image** — Generate placeholder images for development (2 pts)
- **meta-tag-generator** — Generate OG, Twitter Card, and Schema.org meta tags (1 pts)
- **utm-builder** — Build UTM-tagged URLs for campaign tracking (1 pts)
- **svg-optimizer** — Optimize SVGs by removing unnecessary elements (2 pts)
- **color-palette-generator** — Generate harmonious color palettes from a base color (2 pts)
- **css-minifier** — Minify CSS by removing comments and whitespace (1 pts)
- **robots-txt-generator** — Generate robots.txt from rules (1 pts)
- **sitemap-generator** — Generate XML sitemaps from URL lists (1 pts)

## Links

- [Marketplace](https://apphighway.com/marketplace)
- [Documentation](https://apphighway.com/docs)
- [Get API Key](https://apphighway.com/dashboard/tokens)

---

*Auto-generated from [apphighway.com/api/mcp/registry](https://apphighway.com/api/mcp/registry)*
