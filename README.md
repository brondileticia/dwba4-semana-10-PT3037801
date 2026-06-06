# Semana 10 - Bootstrap

**Disciplina:** Desenvolvimento Web Client | **Curso:** ADS | **IFSP - Câmpus Pirituba**

## 📌 Sobre

Site institucional do IFSP Câmpus Pirituba com página de login estilizada usando **Bootstrap 5**.

## 🚀 Tecnologias

- HTML5 / CSS3
- Bootstrap 5.3
- Bootstrap Icons
- JavaScript

## 🎯 O que foi feito?

### Página de Login (login.html)

| Antes | Depois com Bootstrap |
|-------|---------------------|
| Formulário simples | Card estilizado com sombra |
| Sem ícones | Input Group com ícones |
| Alert padrão | Alertas Bootstrap coloridos |
| Sem toggle | Botão mostrar/esconder senha |
| Layout fixo | Totalmente responsivo |

### Componentes Bootstrap utilizados

```html
✅ Card          - Container do login
✅ Form Control  - Campos estilizados  
✅ Input Group   - Ícones nos campos
✅ Button        - Botão Entrar
✅ Alert         - Mensagens de validação
✅ Icons         - Ícones Bootstrap
```


## 🔧 Funcionalidades JavaScript

```javascript
// 1. Mostrar/esconder senha
toggleSenha.addEventListener('click', () => {
    // alterna type entre password/text
});

// 2. Validação com Bootstrap Alert
form.addEventListener('submit', () => {
    // exibe alerta de erro/sucesso
});
```

## 📱 Responsividade

- ✅ Desktop: Card centralizado
- ✅ Tablet: Card ocupa 75% da tela
- ✅ Mobile: Card ocupa 90% da tela


## 👨‍💻 Autor

**Nome:** Letícia Brondi Carvalheiro
**Prontuário:** PT3037801
