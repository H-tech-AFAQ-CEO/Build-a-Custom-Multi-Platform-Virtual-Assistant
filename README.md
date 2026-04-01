# Proxima AI — Control Center

**Proxima AI Control Center** is a comprehensive, single-page web application designed to manage and monitor multiple AI personas across different platforms. Built with vanilla HTML, CSS, and JavaScript, it provides a centralized dashboard for configuring AI behavior, tracking conversations, monitoring LLM health, and embedding AI widgets into external websites.

## ✨ Features

### Core Dashboard
- **Real-time Statistics** – Total conversations, unique users, average response time, and satisfaction rate with trend indicators.
- **Conversation Volume Chart** – Line chart showing daily conversation trends.
- **Platform Distribution** – Donut chart displaying usage split across different AI personas.
- **LLM Health Monitor** – Live status indicators for GPT-4o, Gemini 1.5 Pro, and Claude 3.5 Sonnet with latency metrics.

### AI Persona Management
| Persona | Description | Status |
|---------|-------------|--------|
| **ProximaRide** | Ride-sharing assistant for booking, pricing, and driver support | Live |
| **Proxima Study** | Study-abroad advisor for Canadian universities, costs, and visas | Live |
| **Canadian Exports** | Trade and export advisor for customs, tariffs, and shipping | Draft |

- **Persona Editor** – Customize system prompts, fallback messages, LLM selection, max tokens, and temperature.
- **Visual Card Selection** – Click to switch between personas with real-time editing.
- **Live/ Draft Status Badges** – Clear visual indicators for persona readiness.

### Chat Widget
- **Floating Chat Button** – Accessible from any page, with smooth open/close animation.
- **Persona Selector** – Switch between different AI personas within the chat.
- **Smart Responses** – Context-aware replies based on selected persona (ride, study, or export).
- **Typing Indicator** – Animated dots while waiting for responses.
- **Quick Action Chips** – Predefined prompts for common questions.
- **Backend Integration** – Ready to connect to a real API endpoint (fallback to local responses).

### Conversation Management
- **Full Conversation Log** – Table view of all conversations with timestamps and message counts.
- **Export Functionality** – Download conversations as JSON files.
- **Clear All Option** – Delete all stored conversations with confirmation.
- **Recent Conversations** – Sidebar preview of latest interactions.

### Analytics & Insights
- **Weekly Breakdown Chart** – Stacked bar chart showing activity per persona.
- **LLM Usage Split** – Pie chart displaying which AI models are used most frequently.
- **Key Metrics** – Total queries, resolution rate, escalations, and token usage.
- **Live Chart Updates** – Charts update dynamically with theme changes.

### LLM Management
- **API Key Storage** – Securely store OpenAI, Gemini, and Anthropic API keys in localStorage.
- **Connection Testing** – Verify connectivity to all configured LLM providers.
- **Live Status Indicators** – Green for online, with configurable latency values.
- **Clear Keys Option** – Remove all stored API credentials with one click.

### Settings & Customization
- **Appearance** – Dark/light theme toggle with system preference detection.
- **Brand Color** – Customizable accent color with real-time preview.
- **Widget Behavior** – Toggle prompt chips, cross-reference LLMs, scam filter, and conversation saving.
- **Account Management** – Save display name, email, and timezone preferences.
- **Data Management** – Export all data, clear storage, and view storage usage.

### Embed Widget Generator
- **Copy-Ready Snippets** – Pre-generated code blocks for each persona.
- **Customizable Parameters** – Primary color, border radius, font, and suggested prompts.
- **One-Click Copy** – Copy embed code to clipboard with a single button.
- **Status Indicators** – Show whether each widget is Active or Draft.

## 🖼️ Screenshots

> *Add your actual screenshots here to showcase the dashboard.*

| Dashboard Overview | AI Personas |
|-------------------|-------------|
| *[Insert screenshot of dashboard with charts]* | *[Insert screenshot of persona cards]* |

| Chat Widget | Conversation Log |
|------------|-----------------|
| *[Insert screenshot of floating chat]* | *[Insert screenshot of conversation table]* |

| LLM Management | Settings Panel |
|---------------|----------------|
| *[Insert screenshot of LLM status]* | *[Insert screenshot of settings]* |

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: Node.js server for backend API integration

### Installation & Usage
1. Clone or download the repository.
2. Open `index.html` directly in your browser.
   ```bash
   # Optional: use a local server
   npx serve
