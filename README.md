# AI Avatar Project

A virtual avatar system that combines AI-generated responses, text-to-speech, and 3D modeling to create an interactive virtual presence. The avatar's movements and speech are driven by responses from a Large Language Model (LLM).

## Features

- AI-powered conversation using LLM
- 3D avatar model created with VRoid Studio
- Live animation through VSeeFace
- Text-to-speech capabilities
- Automated expressions and movements based on LLM responses

## Technology Stack

- **3D Modeling**: VRoid Studio
- **Animation**: VSeeFace
- **AI Conversation**: Large Language Model (LLM)
- **Text-to-Speech**: (TBD)

## Setup Instructions

1. **VRoid Studio Setup**
   - Download and install [VRoid Studio](https://vroid.com/en/studio)
   - Create your custom avatar
   - Export the model in VRM format

2. **VSeeFace Setup**
   - Download and install [VSeeFace](https://www.vseeface.icu/)
   - Import your VRM model
   - Configure animation settings

3. **Project Setup**
   ```bash
   # Clone the repository
   git clone [repository-url]
   cd AI_Avatar

   # Install dependencies
   pip install -r requirements.txt
   ```

## Development Status

This project is currently in development as a minimum viable product (MVP). The following features are being implemented:

- [x] Basic 3D avatar creation
- [ ] LLM integration for conversation
- [ ] Text-to-speech integration
- [ ] Automated expressions and movements
- [ ] Real-time lip sync

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Add appropriate license information]

## Acknowledgments

- Inspired by virtual YouTubers like Kizuna AI and Neuro-sama
- Built with VRoid Studio and VSeeFace and Elevenlabs and whatever else I can stuff into this.
