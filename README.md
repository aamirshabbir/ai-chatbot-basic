# 🤖 AI Chatbot - Rule-Based Version

A modern, responsive rule-based chatbot built with vanilla JavaScript, HTML, and CSS. This project demonstrates fundamental chatbot development concepts with a clean, professional interface.

![Chatbot Demo](./screenshots/chatbot-demo.gif)

## ✨ Features

- **Smart Pattern Recognition**: Responds to greetings, questions, jokes, and more
- **Modern UI/UX**: WhatsApp-style chat bubbles with smooth animations  
- **Typing Indicators**: Realistic chat experience with animated typing dots
- **Auto-scroll**: Automatically scrolls to latest messages
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Real-time Clock**: Shows current time when requested
- **Multiple Response Variations**: Randomized responses for natural feel


## 🎯 Try These Commands

Chat with the bot and try saying:
- "Hello" or "Hi" 👋
- "What time is it?" ⏰  
- "Tell me a joke" 😄
- "Help" or "What can you do?" ❓
- "Thank you" 🙏
- "Goodbye" 👋

## 🛠️ Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Modern styling with gradients and animations  
- **JavaScript (ES6+)**: Interactive functionality and chatbot logic
- **No external dependencies**: Pure vanilla implementation

## 🚀 Quick Start

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/aamirshabbir/ai-chatbot-basic.git
   cd ai-chatbot-basic
   ```

2. **Open in browser**
   ```bash
   # Simply open the HTML file
   open index.html
   # OR serve locally
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Start chatting!**
   - Type any message and press Enter or click Send
   - Try different commands listed above

## 🎨 Customization

### Adding New Chat Responses

Edit the `chatRules` object in `index.html`:

```javascript
const chatRules = {
    // Add your custom category
    music: {
        patterns: ['music', 'song', 'playlist'],
        responses: [
            "I love talking about music! 🎵",
            "What's your favorite genre?"
        ]
    }
    // ... existing rules
};
```

### Styling Changes

Customize colors using CSS variables:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --chat-bg: #f8f9fa;
    --border-radius: 18px;
}
```

## 🛣️ Development Roadmap

This is **Phase 1** of a progressive chatbot development series:

- **Phase 1**: ✅ Rule-based chatbot (Current)
- **Phase 2**: ✅ Enhanced UI & animations (Implemented)  
- **Phase 3**: 🔄 AI API integration (Coming Soon!)
- **Phase 4**: 🚀 Advanced features & deployment

**Follow the journey**: Watch this space for the AI-powered version!


## 🌟 Acknowledgments

- Inspired by modern messaging applications
- Built to demonstrate chatbot fundamentals
- Part of a learning series on AI development

## 📞 Connect

**[Your Name]**
- 📧 **Email**: [amirshabbir56@gmail.com](mailto:amirshabbir56@gmail.com)
- 💼 **LinkedIn**: [linkedin.com/in/amir-shabbir](https://linkedin.com/in/amir-shabbir)  
- 🐱 **GitHub**: [github.com/aamirshabbir](https://github.com/aamirshabbir)

---

⭐ **Found this helpful? Give it a star!** ⭐

💡 **Want to see the AI-powered version?** Watch this repo for updates!