# 🌐 Site de Portfólio Pessoal – Projeto Reutilizável

Este repositório contém o desenvolvimento de um site de portfólio pessoal, criado como um modelo prático, elegante e funcional para qualquer pessoa que deseje apresentar seus projetos de forma profissional na internet.

## 📌 Sobre o Projeto

Este site foi pensado para servir como uma **vitrine digital personalizada**, onde qualquer profissional, estudante ou freelancer pode expor seus trabalhos, destacar suas habilidades e facilitar o contato com visitantes ou potenciais clientes.

Com layout responsivo, navegação fluida e estrutura intuitiva, o projeto pode ser facilmente adaptado para diferentes áreas e estilos.

Além das seções de apresentação e projetos, o site oferece **formas de contato direto**, incluindo integração com **WhatsApp via link clicável**, tornando a comunicação rápida e acessível.

## ✨ Funcionalidades e Características

- Design moderno, limpo e responsivo
- Seções para introdução, projetos e contato
- Organização clara de imagens, textos e estrutura visual
- Link de contato direto via WhatsApp
- Código simples e fácil de adaptar para qualquer perfil profissional
- Inclusão de vídeo demonstrativo da navegação

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura semântica
- **CSS3** – Estilização responsiva com Flexbox
- **JavaScript** – Integração dinâmica do formulário com WhatsApp
- **Arquivos de mídia** – Imagens e vídeo demonstrativo

## 🎬 Vídeo de Demonstração

Um vídeo com a navegação do site está incluído no projeto e pode ser visualizado na pasta:

📁 Pages/demo/0701.mp4

## 🗂️ Estrutura do Projeto
- Página inicial com apresentação pessoal
- Seção de projetos com imagens e descrições
- Layout clean e responsivo para dispositivos móveis e desktop

## 📫 Contato
- LinkedIn: [linkedin.com/in/pedro-zangari-faria](https://www.linkedin.com/in/pedro-zangari-faria-69110b2b6/)
- Email: pedrofaria.profissional@gmail.com

## 🚀 Como Utilizar este Projeto

1. Faça o fork ou clone deste repositório
2. Substitua os textos, imagens e links pelos seus próprios dados
3. Personalize cores, estilos e mensagens
4. Publique em uma plataforma como GitHub Pages, Vercel ou Netlify

Com pequenas alterações, você terá um **portfólio funcional e personalizado** para destacar sua presença digital.

## 📫 Integração com WhatsApp

O formulário de contato foi configurado com JavaScript para gerar um link automático com base nos dados inseridos (nome e mensagem), redirecionando para o WhatsApp com a conversa pronta para envio.

js:
const nome = document.getElementById('nome').value;
const mensagem = document.getElementById('mensagem').value;
const link = `https://wa.me/SEUNUMERO?text=Olá, meu nome é ${nome}. ${mensagem}`;
window.open(link, '_blank');

Basta substituir SEUNUMERO pelo número com DDD, sem espaços ou traços.
