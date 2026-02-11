## Assistente de Voz Inteligente: Whisper + GPT
Este projeto é um Assistente de Voz Virtual desenvolvido para o bootcamp da DIO. Ele demonstra a integração de tecnologias de ponta em Inteligência Artificial para criar um ciclo completo de interação humana: Ouvir (STT), Pensar (LLM) e Falar (TTS).

## Funcionalidades
Transcrição em Tempo Real: Utiliza o modelo OpenAI Whisper para converter fala em texto com alta precisão, processando localmente.
Inteligência Contextual: Integração com a API da OpenAI (GPT-4o-mini) para processamento de linguagem natural.
Resposta Vocal: Síntese de voz através do Google Text-to-Speech (gTTS).
Interface Local: Captura direta via microfone e reprodução imediata de áudio.

## Tecnologias Utilizadas
Python 3.10+: Linguagem base.
OpenAI Whisper: Modelo de rede neural para reconhecimento de fala robusto.
OpenAI API (v1.0.0+): Processamento das respostas com GPT.
FFmpeg: Framework essencial para decodificação e processamento de arquivos de áudio.
SoundDevice & Scipy: Para captura de áudio bruto do hardware.
gTTS & Playsound: Para geração e execução da resposta sonora.

## Pré-requisitos
1. Instalação do FFmpeg
O Whisper exige o FFmpeg instalado no sistema para processar áudios:
Windows: Baixe em gyan.dev, extraia e adicione a pasta bin ao seu PATH.
Linux/Mac: sudo apt install ffmpeg ou brew install ffmpeg.

2. Chave de API da OpenAI
Você precisará de uma API Key válida.
