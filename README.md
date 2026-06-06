# Site IFSP - Câmpus Pirituba

**Disciplina:** Desenvolvimento Web Client | **Semana 09:** Manipulação de Páginas com JavaScript (DOM)

## 📌 Sobre o Projeto

Site institucional do IFSP Câmpus Pirituba com páginas de cursos, eventos, contato e login.  
**Novidade da Semana 09:** Slideshow interativo com JavaScript e manipulação do DOM.

## 🚀 Tecnologias
- HTML5
- CSS3
- JavaScript (DOM)

## 📁 Estrutura
```
projeto-ifsp/
├── index.html          # Página principal (com slideshow)
├── cursos.html
├── sobre.html
├── eventos.html        # Formulário de inscrição
├── contato.html
├── login.html
├── css/style.css
├── img/slideshow/      # Imagens do slideshow
└── favicon.ico
```

## 🎬 Slideshow

| Slide | Conteúdo |
|-------|----------|
| 1 | Entrada do Campus |
| 2 | Caixinha de Sugestões |
| 3 | Processo Seletivo 2026 |
| 4 | Comunidade WhatsApp |

### Funcionalidades
- ✅ Transição automática a cada 5 segundos
- ✅ Botões ◀ ▶ para navegação manual
- ✅ Indicadores (dots) para ir direto ao slide
- ✅ Botão Play/Pause
- ✅ Pausa ao passar o mouse
- ✅ Navegação por teclado (setas ← →)

## 🔧 Manipulação do DOM

```javascript
// Seleção de elementos
const slides = document.querySelectorAll('.slide');

// Manipulação de classes
slide.classList.add('active');
slide.classList.remove('active');

// Eventos
botao.addEventListener('click', () => {});
document.addEventListener('keydown', () => {});

// Temporizador
setInterval(nextSlide, 6000);
```

## 🎨 Cores
- Verde: `#2F9E41`
- Verde claro: `#D7E087`
- Vermelho: `#CD181D`

## 🚦 Como executar
1. Abra o arquivo `index.html` no navegador
2. Pressione `F12` para ver os logs do slideshow no console

## 📱 Responsivo
Funciona em desktop, tablet e mobile.

## 👨‍💻 Autor
**Nome:** Letícia Brondi Carvalheiro
**Curso:** ADS
