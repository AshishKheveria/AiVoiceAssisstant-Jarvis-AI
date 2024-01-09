## Overview:
This repository houses an interactive Voice Assistant leveraging **Google Bard API**, integrating *Speech Recognition*, and offering **Text-to-Speech** functionality. It serves as a conversational interface, allowing users to engage with Bard using voice commands for queries, actions, and interactions.

### Key Features:

- **Voice Interaction:** Utilizes Speech Recognition to identify the wake word 'Jarvis,' initiating the Assistant's listening mode for user prompts.
- **Google Bard Integration:** Employs Google Bard API to process and respond to user queries, harnessing AI capabilities for conversational responses.
- **Customizable Wake Word:** Users have the flexibility to customize the wake word for activating the Assistant, enhancing personalization.
- **Whisper Models:** Incorporates Whisper models for transcribing audio inputs, ensuring accurate and efficient speech recognition.
- **Text-to-Speech (TTS):** Provides audible responses using either the system's native TTS or, on macOS, system messages for seamless interaction.

### Technical Overview:

- **Libraries and APIs:** Utilizes *Bard library* for Google Bard integration, *speech_recognition* for audio input handling, and *whisper* for transcription using pre-trained models.
- **Platform Compatibility:** Developed with cross-platform compatibility in mind, utilizing specific modules for macOS and other operating systems.
- **Modularity:** The codebase is structured with modularity in mind, allowing easy integration of additional functionalities or extensions.
- **Error Handling:** Incorporates robust error handling mechanisms to ensure smooth execution, logging, and recovery from audio transcribing and processing errors.

### Usage:

1. Clone the repository and configure necessary API tokens.
2. Run the main script to activate the Assistant.
3. Speak the wake word ('Jarvis') to activate the Assistant, followed by your query or prompt for Bard.
4. Interact with Bard, receiving responses audibly and in the console.

### Future Development:

This project lays the foundation for further enhancements, including the addition of new features, improving accuracy in speech recognition, and expanding Bard's capabilities through API integrations or custom modules.

### Contributions:

Contributions, suggestions, and improvements via pull requests are welcome! Feel free to extend functionalities or enhance existing features.

**Note:** Ensure compliance with API usage policies and guidelines provided by Google Bard and related services.
