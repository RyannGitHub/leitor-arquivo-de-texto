# 📁 File Processor CLI

Uma aplicação de linha de comando (CLI) desenvolvida em Node.js para processar arquivos de texto. Este projeto permite que os usuários processem arquivos de texto através da linha de comando, identificando e separando palavras repetidas. O usuário fornece o caminho de um arquivo de entrada e um destino para salvar o resultado processado. O terminal exibe mensagens coloridas para facilitar o entendimento do que está acontecendo, utilizando a biblioteca [Chalk](https://www.npmjs.com/package/chalk).


---

## 🚀 Funcionalidades

- 📄 Leitura de arquivos de texto via linha de comando  
- 💾 Salvamento de resultados processados em um caminho de destino  
- ✅ Mensagens de sucesso em **verde**  
- ❌ Mensagens de erro em **vermelho**  
- 🧩 Feedback contínuo ao usuário via terminal  

---

## 🧰 Bibliotecas Utilizadas

Neste projeto, as principais bibliotecas utilizadas são:

- **fs (File System)**: Biblioteca nativa do Node.js que permite interagir com o sistema de arquivos. É usada para ler arquivos de texto, salvar os resultados processados, verificar a existência de arquivos, entre outras operações.  
  [Documentação do fs](https://nodejs.org/api/fs.html)

- **Commander**: Facilita a criação de interfaces de linha de comando (CLI). Permite definir opções e comandos que o usuário pode passar ao executar a aplicação, tornando a manipulação de argumentos mais simples e organizada.  
  [Documentação do Commander](https://www.npmjs.com/package/commander)

- **Chalk**: Utilizada para colorir as mensagens exibidas no terminal. Com o Chalk, mensagens de erro aparecem em vermelho e mensagens de sucesso em verde, tornando a saída mais legível e fácil de interpretar.  
  [Documentação do Chalk](https://www.npmjs.com/package/chalk)


Essas bibliotecas são instaladas e gerenciadas através do **npm** (Node Package Manager).

---


## 📦 Instalação

1. Clone este repositório:

```bash
git clone https://github.com/RyannGitHub/leitor-arquivo-de-texto.git
cd leitor-arquivo-de-texto
