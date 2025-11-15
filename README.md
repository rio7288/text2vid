# text2vid
# 🎬 AI Video Generator

**Transform text into videos using AI - 100% Free & Open Source**

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://yourusername.github.io/video-generator)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Hugging Face](https://img.shields.io/badge/Powered%20by-Hugging%20Face-yellow?style=for-the-badge)](https://huggingface.co)

## ✨ Features

- 🎥 **AI-Powered Video Generation** - Convert text descriptions into videos
- 🆓 **100% Free** - No hidden costs, no subscriptions
- 🔒 **Privacy First** - Your API key never leaves your browser
- 🚀 **No Installation** - Works directly in your browser
- 📱 **Mobile Friendly** - Use on any device
- ⚡ **Fast Generation** - Videos ready in 20-60 seconds
- 💾 **Easy Download** - Save videos directly to your device

## 🚀 Quick Start

### For Users

1. **Visit the live website**: [yourusername.github.io/video-generator](https://yourusername.github.io/video-generator)
2. **Get a free API key** from [Hugging Face](https://huggingface.co/settings/tokens)
3. **Enter your API key** in the website
4. **Describe your video** (e.g., "a cat playing with yarn")
5. **Click Generate** and wait 20-60 seconds
6. **Download your video!**

### For Developers

```bash
# Clone the repository
git clone https://github.com/yourusername/video-generator.git

# Open index.html in your browser
# That's it! No build process needed.
```

## 📖 How It Works

This tool uses the **Damo-Vilab Text-to-Video** model hosted on Hugging Face:

1. You provide a text description
2. The AI model processes your prompt
3. Generates a short video (2-3 seconds)
4. You download the result

**Technology Stack:**
- Frontend: HTML5, TailwindCSS, Vanilla JavaScript
- AI Model: [damo-vilab/text-to-video-ms-1.7b](https://huggingface.co/damo-vilab/text-to-video-ms-1.7b)
- API: Hugging Face Inference API

## 🎯 Example Prompts

Here are some prompts that work well:

- "A golden retriever playing in a park on a sunny day"
- "Ocean waves crashing on a beach at sunset"
- "A hummingbird hovering near red flowers"
- "Raindrops falling on a window with city lights in background"
- "A butterfly flying through a garden of colorful flowers"

## 💡 Tips for Best Results

✅ **DO:**
- Be specific and descriptive
- Include colors, lighting, and action
- Keep prompts under 20 words
- Describe simple, clear scenes

❌ **DON'T:**
- Use overly complex descriptions
- Expect photorealistic quality (it's AI-generated)
- Generate videos of real people
- Include multiple complex actions

## 🔧 Deployment Guide

### Deploy on GitHub Pages (Recommended)

1. **Fork this repository**
2. Go to `Settings` → `Pages`
3. Under "Source", select `main` branch
4. Click `Save`
5. Your site will be live at `https://yourusername.github.io/video-generator`

### Deploy on Netlify

1. Create a [Netlify](https://netlify.com) account
2. Drag and drop the `index.html` file
3. Done! Instant deployment

### Deploy on Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts
4. Your site is live!

## 🔐 API Key Security

**Important:** Your API key is stored locally in your browser and is never sent to any server except Hugging Face for video generation. 

- ✅ Keys are processed client-side only
- ✅ No backend server stores your key
- ✅ No data collection or tracking
- ✅ Open source - verify the code yourself

## 📱 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## ⚠️ Limitations

- Video length: 2-3 seconds (model limitation)
- Generation time: 20-60 seconds
- Quality: AI-generated (not photorealistic)
- First generation may be slower (model loading)
- Free tier has rate limits (managed by Hugging Face)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Ideas for Contributions

- [ ] Add more video models
- [ ] Implement video style options
- [ ] Add video length controls
- [ ] Create video history/gallery
- [ ] Add social sharing features
- [ ] Improve UI/UX
- [ ] Add dark/light theme toggle
- [ ] Implement prompt templates

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Hugging Face](https://huggingface.co) - For providing free AI model hosting
- [Damo Academy](https://damo.alibaba.com) - For the text-to-video model
- [TailwindCSS](https://tailwindcss.com) - For the styling framework
- The open source community

## 📞 Support

Having issues? Here's how to get help:

1. **Check the [FAQ](#-faq)** below
2. **Open an [Issue](https://github.com/yourusername/video-generator/issues)**
3. **Star ⭐ the repo** if you find it useful!

## ❓ FAQ

**Q: Is this really free?**  
A: Yes! Both the website and Hugging Face API are free to use.

**Q: Do I need to create an account?**  
A: You need a free Hugging Face account for the API key, but no account is needed to use the website.

**Q: Why is generation slow?**  
A: AI video generation is computationally intensive. The first generation may take longer as the model loads.

**Q: Can I use this commercially?**  
A: Check the [model license](https://huggingface.co/damo-vilab/text-to-video-ms-1.7b) for commercial use terms.

**Q: Where is my data stored?**  
A: Nowhere! Everything runs in your browser. Your API key and videos are not stored on any server.

**Q: The video quality isn't great?**  
A: This is a free AI model with limitations. For professional videos, consider paid services.

**Q: Model is loading error?**  
A: Wait 20-30 seconds and try again. The model needs time to initialize on Hugging Face servers.

## 🌟 Star History

If you like this project, please consider giving it a star! ⭐

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/video-generator?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/video-generator?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/yourusername/video-generator?style=social)

---

<div align="center">

**Made with ❤️ by [Your Name]**

[⭐ Star this repo](https://github.com/yourusername/video-generator) • [🐛 Report Bug](https://github.com/yourusername/video-generator/issues) • [✨ Request Feature](https://github.com/yourusername/video-generator/issues)

</div>
