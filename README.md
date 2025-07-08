# AI Article Summarizer - Chrome Extension

A production-grade Chrome extension that leverages Google Gemini's AI to deliver concise, accurate article summaries with configurable output formats.




https://github.com/user-attachments/assets/0aaddd88-e34d-4132-882a-ba06b598cc46





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

   
## Usage Documentation

### Basic Flow
1. **Navigate** to target article
2. **Click** extension icon in toolbar  
   *(Icon appears when on article pages)*
3. **Select** preferred format:
   - Bullet points (•)
   - Paragraph (¶)
4. **Click** "Summarize" button
5. **Use** the output:
   - Click "Copy" button for clipboard
   - Read directly in the overlay

### Advanced Features
- **Keyboard Shortcuts**  
  Configure custom hotkeys in extension options
- **Domain-Specific Rules**  
  Set different summarization behaviors for frequent sites
- **Output Customization**  
  Adjust summary length via options:
  - Concise (3-5 bullet points)
  - Detailed (full paragraph)
  - Custom character limit

## System Architecture
![deepseek_mermaid_20250708_02811d](https://github.com/user-attachments/assets/6b02c7c3-0967-4104-a564-769fbe333d81)

## 🤝 Contribution Guidelines

We follow the standard GitHub collaboration workflow:

### Development Process
1. **Fork** the repository  
   *(Click "Fork" button at top-right of repository page)*
2. **Create** feature branch:  
   ```bash
   git checkout -b feat/your-feature-name

3. Commit changes with descriptive messages:
   ```bash
   git commit -am "feat: Add dark mode support"
4.Push to your branch: 
  ```
git push origin feat/your-feature-name
```
5. Open a Pull Request from your fork to the main repository

## Quality Standards

### Commit Messages
Follow [Conventional Commits](https://www.conventionalcommits.org/) format:  
`type(scope): description`  

**Example**:  
`fix(summarizer): handle empty API responses`

### Documentation
- Update README.md for new features  
- Add code comments for complex logic  
- Document edge cases in `EDGE_CASES.md`

### Testing
Verify functionality with:  
- News articles (e.g., BBC, NY Times)  
- Blog posts (Medium, WordPress)  
- Technical documentation (MDN, GitHub Docs)

## Compliance & Security

### Data Protection
- **API Keys**:  
  Stored using Chrome's encrypted `chrome.storage.sync`  
  (AES-256 encryption)
  
- **Privacy**:  
  - No user data collection  
  - No tracking mechanisms  
  - All processing occurs locally

### Security Practices
- All network requests use HTTPS + HSTS  
- Content scripts run in isolated worlds  
- Regular dependency audits (`npm audit`)

##⚖️License

MIT Licensed - See LICENSE for full details.


