## 🌟 Você é vascaíno? O Gigante da Colina no seu Código! 🌟

Este repositório contém um pequeno projeto interativo em HTML, CSS e JavaScript para celebrar o **Club de Regatas Vasco da Gama**, fundado em 21 de agosto de 1898.

O projeto consiste em uma página web que pergunta ao usuário se ele torce para o Vasco. A resposta desencadeia diferentes efeitos visuais e sonoros:

* **Resposta "Sim"**: Toca um trecho do hino do Vasco em ritmo funk, inicia um *slideshow* de imagens e logotipos, e exibe confetes digitais.
* **Resposta "Não"**: Toca um efeito sonoro de vaias.

### 💾 Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

| Arquivo | Tipo | Descrição |
| :--- | :--- | :--- |
| `index.html` | HTML | Estrutura principal da página, com a pergunta e botões. Contém o script que gerencia a interação e a reprodução dos sons/efeitos. |
| `style.css` | CSS | Estilos visuais da página, incluindo o fundo, a formatação dos textos e dos botões, e as animações (como o efeito *pulsar* nos escudos). O fundo inicial usa uma colagem de imagens do Vasco. |
| `hino-do-vasco-versão-funk-(estourado)-made-with-Voicemod.mp3` | Áudio | Hino do Vasco (versão funk). Toca ao clicar em "Sim". |
| `vaias.mp3` | Áudio | Efeito sonoro de vaias. Toca ao clicar em "Não". |
| `79322661_10162899418010454_7873062493977837568_n (1).png` | Imagem | Escudo oficial do Club de Regatas Vasco da Gama. |
| `Imagens Do Vasco.jpg` | Imagem | Imagem com o "Almirante" e frases do Vasco, usada no *slideshow*. |
| `20211104-002500-1-.jpg` | Imagem | Imagem com datas históricas e o nome "VASCO", usada no *slideshow*. |
| `20201108-095554-1-.jpg` | Imagem | Imagem com vários adesivos e símbolos do Vasco, usada no *slideshow*. |
| `penalty_vasco_18.jpg` | Imagem | Colagem de momentos e símbolos do Vasco, usada como fundo da página. |
| `VascoLogos-fotor-bg-remover-20251006222037.png` | Imagem | Logo principal do Vasco (referenciada no `index.html`). |
| `unnamed.gif` | Imagem | Possível GIF de bandeira. |

### 3. Faça o Upload dos Arquivos

Depois de criar o repositório, você pode adicionar todos os seus arquivos (HTML, CSS, JS, Áudios e Imagens) de duas maneiras:

#### Opção A: Pelo Próprio GitHub (Mais Simples)

1.  Na página principal do seu repositório, clique em **"Add file"** (Adicionar arquivo) e depois em **"Upload files"** (Fazer upload de arquivos).
2.  Arraste e solte todos os arquivos do seu projeto (incluindo o `index.html`, `style.css`, áudios e imagens) para a caixa.
3.  Descreva brevemente o que está adicionando (ex: "Arquivos iniciais do projeto").
4.  Clique em **"Commit changes"** (Confirmar mudanças).

#### Opção B: Via Linha de Comando (Mais Profissional)

1.  **Inicialize o Git** na pasta do seu projeto local:
    ```bash
    git init
    ```
2.  **Adicione os Arquivos:**
    ```bash
    git add .
    ```
3.  **Faça o Commit:**
    ```bash
    git commit -m "Projeto inicial: Você é vascaíno?"
    ```
4.  **Conecte ao Repositório Remoto (Substitua a URL):**
    ```bash
    git remote add origin [https://docs.github.com/pt/repositories/creating-and-managing-repositories/quickstart-for-repositories](https://docs.github.com/pt/repositories/creating-and-managing-repositories/quickstart-for-repositories)
    ```
5.  **Envie os Arquivos:**
    ```bash
    git push -u origin master 
    # Ou 'main', dependendo do nome do seu branch principal
    ```


