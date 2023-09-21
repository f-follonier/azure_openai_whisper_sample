## Azure Whisper Transcription

This is an unofficial repository that contains Jupyter notebooks demonstrating the integration of the OpenAI Whisper model with Azure OpenAI Service and Azure AI Speech for audio transcription.

Be aware that Whisper on Azure is currently in preview.

### Files

- **azure_ai_speech_whisper_transcription.ipynb**: Demonstrates the use of the OpenAI Whisper model with Azure AI Speech for batch transcription.
  
- **azure_openai_whisper_transcribe.ipynb**: Details the functionality of the OpenAI Whisper model within Azure OpenAI Service, outlining transcription features.

### Resources

- [Whisper Announcement for Azure](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/announcing-the-preview-of-openai-whisper-in-azure-openai-service/ba-p/3928388)
  
- [Whisper Overview on Microsoft](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/whisper-overview)

### Features

#### OpenAI Whisper in Azure OpenAI Service:
- Run the Whisper model in Azure.
- Provides transcription via REST APIs.

#### OpenAI Whisper in Azure AI Speech:
- Suitable for transcribing large volumes of audio content stored in Azure.
- Features include async processing, speaker diarization, large file support (up to 1GB), batch processing, and word-level timestamps.

### Getting Started

- **Azure AI Studio**: [Portal](https://speech.microsoft.com/portal)
  
- **Azure OpenAI**: [Portal](https://azure.microsoft.com/en-us/products/ai-services/openai-service)

  - Access the Whisper model via Azure AI Studio.
  - Apply for Azure OpenAI Service access to use Whisper.

- **Azure AI Speech Studio**:

  Offers access to the Whisper model and further Azure Speech models and let's you compare outputs.

### Availability (September 2023)

OpenAI Service availability: North Central US, West Europe.
Azure AI Speech availability: East US, Southeast Asia, West Europe.

---

Contributions and feedback are welcome. Please report any issues you find.