# AI Article Summarizer - Chrome Extension

A production-grade Chrome extension that leverages Google Gemini's AI to deliver concise, accurate article summaries with configurable output formats.


https://github.com/user-attachments/assets/b6979509-28bd-4584-8169-7305f0dc185a


## 🏆 Key Features

### 🤖 AI Capabilities
- **📝 Intelligent Summarization** - Google Gemini's NLP extracts key points
- **🔄 Dual Output Formats**:
  - • Bullet-point executive summary
  - ¶ Coherent paragraph version
- **🎯 Context-Aware** - Maintains article meaning and nuance

### ✨ User Experience
- **🔍 Seamless Integration** - Inline summary overlay
- **📋 One-Click Copy** - Instant clipboard access
- **🌐 Universal Compatibility** - Works on most article formats

### ⚙️ Technical
- **🔐 Secure Storage** - Encrypted API key handling
- **⚡ Performance Optimized** - Smart content caching
- **🛡️ Error Resilient** - Graceful API failure handling

## Technical Specifications

| Component           | Technology Used          |
|---------------------|-------------------------|
| Frontend            | HTML5, CSS3, Vanilla JS |
| Chrome APIs         | tabs, storage, runtime  |
| AI Backend          | Google Gemini API       |
| Data Storage        | chrome.storage.sync     |
| Build Process       | Manual (no bundler)     |

## 🛠️ Installation Guide

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

   
##🚀 Usage Documentation
**Basic Flow**
1.Navigate to target article

2.Click extension icon in toolbar

3.Select preferred format

4.Click "Summarize"

5.Use "Copy" button or read directly

**Advanced Features**
-Keyboard shortcut configuration

-Domain-specific summarization rules

-Output length customization (via options)

##🏗️ System Architecture
![deepseek_mermaid_20250708_02811d](https://github.com/user-attachments/assets/6b02c7c3-0967-4104-a564-769fbe333d81)

##🤝Contribution Guidelines
We follow standard GitHub workflow:

1. Fork the repository

2. Create feature branch (git checkout -b feat/new-feature)

3. Commit changes (git commit -am 'Add new feature')

4. Push to branch (git push origin feat/new-feature)

5. Open Pull Request

Please ensure:

-Clear commit messages

-Updated documentation

-Passing basic functionality tests

##Compliance & Security
-All API keys stored using Chrome's encrypted storage

-No data collection or tracking

-Regular dependency audits

##⚖️License
MIT Licensed - See LICENSE for full details.


