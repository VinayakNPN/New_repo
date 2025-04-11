# 📚 Study-Buddy


## Your AI-Powered Study Companion

Study-Buddy is a Flutter application that leverages Google's Gemini AI to create an intelligent study assistant. Whether you need help understanding concepts, analyzing diagrams, solving problems, or just want to chat about academic topics, Study-Buddy is there to assist you 24/7.

---

## ✨ Features

- **Text-Based AI Assistance** - Ask any study-related questions and get intelligent responses
- **Image Analysis** - Upload images of problems, diagrams, or notes for AI interpretation
- **Clean Modern UI** - Intuitive interface with a calming blue gradient design
- **Camera Integration** - Quickly snap photos of textbook pages or handwritten notes
- **Gallery Access** - Select existing images from your device
- **Responsive Design** - Works on various screen sizes and orientations

---

## 🛠️ Technologies Used

- **Flutter** - Cross-platform UI toolkit for building beautiful applications
- **Gemini API** - Google's multimodal AI model for text and image understanding
- **Material Design** - Clean, intuitive visual language for a consistent experience
- **Image Picker** - Seamless camera and gallery integration

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.7.2 or higher)
- Dart SDK
- Android Studio / VS Code
- A Gemini API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Study-Buddy.git
   cd Study-Buddy
   ```

2. **Create a config.json file**
   
   Create the file `assets/config.json` with your Gemini API key:
   ```json
   {
     "geminiAPIkey": "YOUR_GEMINI_API_KEY"
   }
   ```

3. **Install dependencies**
   ```bash
   flutter pub get
   ```

4. **Generate JSON serialization code**
   ```bash
   flutter pub run build_runner build
   ```

5. **Run the app**
   ```bash
   flutter run
   ```

---

## 💡 How to Use

1. **Launch the app** - Open Study-Buddy on your device
2. **Ask a question** - Type your study-related question in the text field
3. **For image analysis:**
   - Tap the camera icon to take a photo
   - Tap the gallery icon to select an existing image
   - Add an optional text prompt for context
4. **Send your query** - Tap the send button and wait for the AI response
5. **Review the answer** - The AI-generated response will appear at the top of the screen

---

## 🧩 Project Structure

```
lib/
├── config_model.dart       # Model for API key configuration
├── config_model.g.dart     # Generated JSON serialization code
├── home_screen.dart        # Main UI screen with chat functionality
└── main.dart               # App entry point and configuration
```

---

## 🛣️ Roadmap

- [ ] Add chat history functionality
- [ ] Implement dark mode support
- [ ] Create subject-specific AI modes
- [ ] Add support for PDF analysis
- [ ] Implement note-taking capabilities
- [ ] Add voice input support

---

## 📋 Requirements

- Android 5.0+ (API level 21+)
- iOS 11.0+
- 2GB RAM or more recommended
- Camera access (optional, for image analysis)
- Internet connection required

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to improve Study-Buddy.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📞 Support

If you encounter any issues or have questions, please file an issue on the GitHub repository.

---

<p align="center">Made with ❤️ for students everywhere</p>