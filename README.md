# 💬 DialoGPT Conversational Agent

Este repositório contém uma implementação do modelo **DialoGPT** (da Microsoft / Hugging Face) para conversação em linguagem natural. Ele permite interagir com o modelo via terminal ou através de um Jupyter Notebook interativo.


📸 Demonstração / Preview

<img width="1898" height="936" alt="1" src="https://github.com/user-attachments/assets/ccfc61b2-6fe0-4f97-91f5-357345f9b438" />


📁 Estrutura do Repositório
DialoGPT/
├── DialoGPT.ipynb   # Notebook com testes e execução interativa
├── main.py          # Script principal para rodar o chat via terminal
├── .gitignore       # Arquivos e diretórios ignorados pelo Git
└── README.md        # Documentação do projeto



📋 Pré-requisitos
Antes de começar, certifique-se de ter instalado em sua máquina:

Python 3.8+

Gerenciador de pacotes pip

(Opcional, mas recomendado) Placa de vídeo com suporte a CUDA caso queira inferência mais rápida.



🚀 Instalação e Configuração
1. Clonar o Repositório
git clone [https://github.com/SEU-USUARIO/DialoGPT.git](https://github.com/SEU-USUARIO/DialoGPT.git)
cd DialoGPT


2. Criar e Ativar um Ambiente Virtual
Recomenda-se o uso de um ambiente virtual para isolar as dependências:

Linux / macOS:

Bash
python3 -m venv venv
source venv/bin/activate
Windows:

Bash
python -m venv venv
venv\Scripts\activate


3. Instalar as Dependências
Instale as principais bibliotecas necessárias:

Bash
pip install torch transformers jupyter
Dica para GPU: Se você possui placa de vídeo NVIDIA e deseja acelerar o processamento, instale o PyTorch compatível com sua versão de CUDA seguindo as instruções em pytorch.org.

💻 Como Rodar
Opção 1: Execução via Terminal (main.py)
Para iniciar o chatbot interativo diretamente pelo console:

Bash
python main.py
Digite sua mensagem no prompt e pressione Enter para receber a resposta do modelo.

Para sair, basta pressionar Ctrl + C ou digitar palavras de encerramento (como sair ou exit).

Opção 2: Execução via Jupyter Notebook (DialoGPT.ipynb)
Caso prefira visualizar os testes e execuções passo a passo:

Inicie o servidor do Jupyter:

Bash
jupyter notebook
No navegador que abrir automaticamente, selecione o arquivo DialoGPT.ipynb.

Execute as células sequencialmente (Shift + Enter).

🛠️ Tecnologias Utilizadas
Python

Hugging Face Transformers

PyTorch

Microsoft DialoGPT

Jupyter Notebook

📄 Licença
Este projeto é disponibilizado sob a licença MIT (ou a licença de sua preferência).

