
  DOCUMENTO OFICIAL - DECLARAÇÃO DE APPS E SERVIÇOS DE TERCEIROS (THIRD-PARTY)
                           AURA A.I.O.A.S. 
                        CapybarasTecApps © 2026
================================================================================

SUMÁRIO:
1. OBJETIVO DA DECLARAÇÃO
2. INTEGRAÇÃO COM MOTOR LOCAL (OLLAMA ENGINE)
3. PROVEDORES DE INTELIGÊNCIA ARTIFICIAL EM NUVEM (APIS BYOK)
4. INTEGRAÇÃO E AUTOMAÇÃO COM O SISTEMA OPERACIONAL WINDOWS
5. ISENÇÃO DE VÍNCULO CORPORATIVO E MARCAS REGISTRADAS
6. RESPONSABILIDADE SOBRE CONSUMO DE APIS E CUSTOS DE TERCEIROS

--------------------------------------------------------------------------------
1. OBJETIVO DA DECLARAÇÃO
--------------------------------------------------------------------------------
Este documento declara transparentemente todos os softwares, serviços de terceiros,
motores de inteligência artificial e APIs integrados ou compatíveis com o ecossistema
AURA A.I.O.A.S. (Artificial Intelligence Operations Automation System), desenvolvido
pela CapybarasTecApps.

--------------------------------------------------------------------------------
2. INTEGRAÇÃO COM MOTOR LOCAL (OLLAMA ENGINE)
--------------------------------------------------------------------------------
• MOTOR OLLAMA (https://ollama.com):
  - A AURA A.I.O.A.S. utiliza o Ollama como motor padrão para processamento 100% local e offline.
  - O Ollama é um projeto de código aberto distribuído sob a licença MIT.
  - A AURA conecta-se ao servidor Ollama local via API HTTP na porta padrão (http://localhost:11434).
  - O download e a instalação do Ollama são realizados diretamente pelo usuário ou orientados pelo sistema de forma transparente.

--------------------------------------------------------------------------------
3. PROVEDORES DE INTELIGÊNCIA ARTIFICIAL EM NUVEM (APIS BYOK)
--------------------------------------------------------------------------------
A AURA oferece suporte para conexão com provedores externos de IA em nuvem por meio do
modelo BYOK (Bring Your Own Key - Traga Sua Própria Chave):

• PROVEDORES SUPORTADOS:
  - Groq Cloud (Groq Inc. - Modelos Llama 3)
  - OpenAI (OpenAI L.L.C. - Modelos GPT-4o / GPT-3.5)
  - Anthropic (Anthropic PBC - Modelos Claude 3.5 Sonnet)
  - Google Gemini (Google LLC)
  - DeepSeek (DeepSeek AI)

• REGRAS DE CONEXÃO:
  As chaves de API inseridas pelo usuário são armazenadas de forma criptografada na pasta
  local "Documentos\auramemoryhive" e enviadas diretamente aos endpoints oficiais dos
  respectivos provedores via conexões seguras HTTPS/TLS.

--------------------------------------------------------------------------------
4. AUTOMAÇÃO COM O SISTEMA OPERACIONAL WINDOWS
--------------------------------------------------------------------------------
• RECURSOS DO WINDOWS UTILIZADOS:
  - Microsoft PowerShell & CMD: Para execução de comandos de automação autorizados pelo usuário.
  - SAPI5 / Windows Speech Synthesis: Para reprodução de respostas em voz (TTS).
  - Windows Media Foundation / DirectShow: Para captura de áudio do microfone e vídeo da câmera.

--------------------------------------------------------------------------------
5. ISENÇÃO DE VÍNCULO CORPORATIVO E MARCAS REGISTRADAS
--------------------------------------------------------------------------------
• A CapybarasTecApps e a AURA A.I.O.A.S. não possuem afiliação direta, patrocínio ou
  endosso oficial da Microsoft Corporation, OpenAI, Groq, Anthropic, Google ou Ollama.
• Todas as marcas registradas, nomes de produtos e logotipos mencionados pertencem a seus
  respectivos proprietários.

--------------------------------------------------------------------------------
6. RESPONSABILIDADE SOBRE CONSUMO DE APIS E CUSTOS
--------------------------------------------------------------------------------
• O uso das APIs padrão nativas inclusas na AURA é gerenciado pelo aplicativo sem custos adicionais.
• Ao utilizar chaves próprias (BYOK), qualquer custo de consumo de tokens ou cobrança
  efetuada pelos provedores de nuvem (OpenAI, Anthropic, etc.) é de responsabilidade exclusiva do usuário.

================================================================================
CapybarasTecApps © 2026 - Todos os direitos reservados.
