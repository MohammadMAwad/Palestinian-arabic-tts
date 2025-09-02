# 🎙️ Jordanian Arabic Text-to-Speech Web App

A modern, responsive web application that converts Arabic text to natural-sounding Jordanian Arabic speech using the Lahajati.ai API.

## ✨ Features

- **🌍 Multiple Jordanian Dialects**: Support for 4 distinct Jordanian Arabic dialects
  - Ammani Jordanian (Urban)
  - Northern Jordanian (Irbid and Ramtha) 
  - Southern Jordanian (Karak and Ma'an)
  - Bedouin Jordanian (Central and Eastern)

- **🎭 Professional Voice Quality**: High-quality voice synthesis with teacher performance style
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **🎨 Modern UI**: Clean, gradient-based interface with smooth animations
- **⚡ Real-time Processing**: Fast conversion with loading indicators
- **🔊 Audio Playback**: Built-in audio player with full controls
- **📊 API Transparency**: View available voices, dialects, and performance styles
- **⌨️ Keyboard Shortcuts**: Ctrl+Enter to quickly convert text

## 🚀 Live Demo

Simply open `jordanian-arabic-tts-app.html` in any modern web browser to start using the application.

## 📋 Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for API calls)
- Valid Lahajati.ai API key

## 🛠️ Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/MohammadMAwad/jordanian-arabic-tts.git
   cd jordanian-arabic-tts
   ```

2. **Open the application**:
   - Simply open `jordanian-arabic-tts-app.html` in your web browser
   - No additional setup required!

## 🔧 Configuration

The application comes pre-configured with a demo API key. For production use:

1. **Get your API key** from [Lahajati.ai](https://lahajati.ai)
2. **Replace the API key** in the HTML file:
   ```javascript
   const API_KEY = 'your-api-key-here';
   ```

## 📖 Usage

1. **Select Dialect**: Choose your preferred Jordanian Arabic dialect from the dropdown
2. **Enter Text**: Type or paste Arabic text in the textarea
3. **Convert**: Click "Convert to Speech" or use Ctrl+Enter
4. **Listen**: Play the generated audio using the built-in player

### Supported Text

- Modern Standard Arabic
- Jordanian Arabic dialects
- Mixed Arabic text
- Various Arabic scripts and diacritics

## 🎨 Customization

### Styling
The application uses CSS custom properties for easy theming:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --border-color: #e1e5e9;
    --text-color: #333;
}
```

### API Configuration
Modify the API settings in the JavaScript section:

```javascript
const API_BASE_URL = 'https://lahajati.ai/api/v1';
const VOICE_ID = 'l6ErPsa0knOuPHhg7QtW3zyr';
const PERFORMANCE_ID = '1798';
```

## 🔊 Audio Quality

- **Format**: MP3
- **Quality**: High-fidelity speech synthesis
- **Voice**: Professional male voice (Hussein)
- **Performance**: Teacher/Educational style
- **Dialect Accuracy**: Authentic Jordanian pronunciation

## 📱 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| Mobile  | ✅ Responsive |

## 🔐 Privacy & Security

- **API Keys**: Stored client-side (consider server-side for production)
- **Audio Data**: Processed via secure HTTPS API calls
- **No Data Storage**: Text and audio are not stored locally
- **CORS Enabled**: Secure cross-origin requests

## 🚨 Error Handling

The application includes comprehensive error handling for:
- Network connectivity issues
- API rate limits
- Invalid API responses
- Empty audio files
- Malformed text input

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Lahajati.ai** for providing the high-quality Arabic TTS API
- **Jordanian Linguistics Community** for dialect accuracy insights
- **Open Source Community** for inspiration and best practices

## 📧 Support

For support and questions:
- 📧 Email: [your-email@example.com]
- 🐛 Issues: [GitHub Issues](https://github.com/MohammadMAwad/jordanian-arabic-tts/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/MohammadMAwad/jordanian-arabic-tts/discussions)

## 🔗 Related Projects

- [Palestinian Arabic Translator](https://github.com/MohammadMAwad/palestinian-arabic-translator)
- [Arabic Language Tools](https://github.com/MohammadMAwad/arabic-language-tools)

---

**Made with ❤️ for the Arabic-speaking community**

⭐ Star this repository if you find it helpful!