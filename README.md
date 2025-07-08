A production-grade Chrome extension that leverages Google Gemini's AI to deliver concise, accurate article summaries with configurable output formats.

## Key Features

### Core Functionality
- **Intelligent Summarization** - Utilizes Google Gemini's advanced NLP to extract key information
- **Dual Output Formats**:
  - Bullet-point executive summary
  - Coherent paragraph summary
- **Context-Aware Processing** - Maintains article context and preserves critical details

### User Experience
- **Non-Disruptive Integration** - Summary overlay appears inline with page content
- **One-Click Operations** - Generate and copy summaries without leaving the page
- **Responsive Design** - Adapts to all common article layouts

### Technical Implementation
- **Secure API Handling** - Encrypted local storage for API keys
- **Optimized Performance** - Caching mechanism for frequent domains
- **Error Resilience** - Graceful degradation when API limits are reached

## Technical Specifications

| Component           | Technology Used          |
|---------------------|-------------------------|
| Frontend            | HTML5, CSS3, Vanilla JS |
| Chrome APIs         | tabs, storage, runtime  |
| AI Backend          | Google Gemini API       |
| Data Storage        | chrome.storage.sync     |
| Build Process       | Manual (no bundler)     |

## Installation Guide

### Requirements
- Google Chrome (v89+ recommended)
- Active Google Gemini API key

### Setup Process

```bash
# Clone repository
git clone https://github.com/your-repo/ai-article-summarizer.git
cd ai-article-summarizer
   ```
1. Navigate to chrome://extensions

2. Enable Developer mode

3. Click Load unpacked and select project directory

4. Configure API key in extension options

   
##Usage Documentation
###Basic Flow
Navigate to target article

Click extension icon in toolbar

Select preferred format

Click "Summarize"

Use "Copy" button or read directly

Advanced Features
Keyboard shortcut configuration

Domain-specific summarization rules

Output length customization (via options)
