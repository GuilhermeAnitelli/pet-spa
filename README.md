# 🐾 PetSpa - Banho e Tosa com Carinho

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)

> Um site moderno e amigável para um pet shop especializado em banho, tosa e cuidados com pets.

## 📋 Sobre o Projeto

O **PetSpa** é um landing page desenvolvido para um pet shop que oferece serviços de banho, tosa e taxi dog. O site foi criado com foco em design moderno, responsivo e acessível, transmitindo carinho e profissionalismo no cuidado com os animais de estimação.

### ✨ Características

- 🎨 **Design Moderno**: Interface limpa e intuitiva com cores vibrantes
- 📱 **Totalmente Responsivo**: Adaptado para desktop, tablet e mobile
- 🌈 **Paleta de Cores Alegre**: Laranja (#FF9F43), Azul Céu (#54A0FF) e tons claros
- 🎭 **Animações Suaves**: Efeitos hover e transições elegantes
- ♿ **Acessível**: Estrutura semântica e boa prática em HTML5
- 🔗 **Integração com WhatsApp**: Botões de contato direto
- 📍 **Localização**: Mapa e informações de endereço

## 🚀 Funcionalidades

### Seções do Site

1. **Header/Navegação**
   - Logo animado com ícone de patinha
   - Menu de navegação fixo (sticky)
   - Botão de agendamento via WhatsApp

2. **Hero Section**
   - Chamada principal atrativa
   - Imagem ilustrativa
   - Call-to-action para agendamento

3. **Serviços**
   - Grid de cards com os serviços oferecidos:
     - 🚿 Banho Completo
     - ✂️ Tosa na Tesoura
     - ❤️ Taxi Dog
   - Ícones coloridos e descrições detalhadas

4. **Galeria de Fotos**
   - Grid responsivo com imagens
   - Efeitos hover com rotação e zoom
   - Integração com Unsplash

5. **Depoimentos**
   - Cards com avaliações de clientes
   - Sistema de estrelas
   - Experiências reais de tutores

6. **FAQ (Perguntas Frequentes)**
   - Accordion interativo
   - Respostas para dúvidas comuns
   - Design expansível

7. **Localização e Contato**
   - Endereço e horário de funcionamento
   - Botões de ação (WhatsApp e Google Maps)
   - Imagem ilustrativa da localização

8. **Footer**
   - Créditos do desenvolvedor
   - Copyright

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização avançada com:
  - CSS Variables (Custom Properties)
  - CSS Grid e Flexbox
  - Animações e transições
  - Media Queries para responsividade
- **Google Fonts**: 
  - Fredoka (títulos)
  - Nunito (corpo do texto)
- **Phosphor Icons**: Biblioteca de ícones
- **Unsplash**: Imagens de alta qualidade

## 📁 Estrutura de Arquivos

```
pet-spa/
│
├── index.html                  # Página principal
├── README.md                   # Documentação do projeto
│
└── assets/
    ├── css/
    │   └── style.css          # Estilos globais
    │
    ├── img/
    │   ├── favicon.ico        # Favicon 16x16
    │   ├── favicon-32x32.png  # Favicon 32x32
    │   └── apple-touch-icon.png  # Ícone iOS
    │
    └── js/                    # (vazio - pronto para scripts futuros)
```

## 🎨 Paleta de Cores

```css
--primary: #FF9F43;        /* Laranja vibrante */
--primary-hover: #EE5A24;  /* Laranja escuro (hover) */
--secondary: #54A0FF;      /* Azul céu */
--bg-light: #FEF9E7;       /* Creme claro (fundo) */
--text-dark: #2C3A47;      /* Texto escuro */
--white: #ffffff;          /* Branco */
```

## 🖼️ Tipografia

- **Títulos**: Fredoka (400, 600)
- **Corpo**: Nunito (400, 700)

## 📱 Responsividade

O site é totalmente responsivo com breakpoint principal em **768px**:

- **Desktop**: Layout em duas colunas, grid completo
- **Mobile**: Layout em coluna única, elementos empilhados

## 🚀 Como Usar

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para fontes e ícones externos)

### Instalação

1. Clone ou baixe o repositório:
```bash
git clone https://github.com/seu-usuario/pet-spa.git
```

2. Navegue até a pasta do projeto:
```bash
cd pet-spa
```

3. Abra o arquivo `index.html` no navegador:
```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

Ou simplesmente arraste o arquivo para o navegador.

## 🔧 Personalização

### Alterar Cores

Edite as variáveis CSS no início do arquivo [assets/css/style.css](assets/css/style.css):

```css
:root {
    --primary: #FF9F43;      /* Cor principal */
    --secondary: #54A0FF;    /* Cor secundária */
    --bg-light: #FEF9E7;     /* Cor de fundo */
    /* ... */
}
```

### Alterar Conteúdo

Edite o arquivo [index.html](index.html) diretamente, modificando textos, imagens e links conforme necessário.

### Adicionar JavaScript

O projeto está preparado para receber scripts na pasta `assets/js/`. Adicione seus arquivos `.js` e referencie no HTML:

```html
<script src="/assets/js/script.js" defer></script>
```

## 📈 Melhorias Futuras

- [ ] Sistema de agendamento online integrado
- [ ] Galeria de fotos com lightbox
- [ ] Formulário de contato funcional
- [ ] Seção de blog/dicas para pets
- [ ] Sistema de avaliações dinâmico
- [ ] Integração com redes sociais
- [ ] Animações mais elaboradas (AOS, GSAP)
- [ ] Dark mode

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é livre para uso pessoal e educacional.

## 👨‍💻 Autor

**Guilherme Anitelli**

---


<div align="center">
  
### Feito com 🐾 e muito ☕

Se este projeto foi útil para você, considere dar uma ⭐!

</div>
