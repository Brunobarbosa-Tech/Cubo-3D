# 🧊 Cubo 3D Neon

Um projeto em **HTML** e **CSS puro** que cria um cubo 3D animado com efeito **neon** e rotação contínua.\
O projeto utiliza `transform`, `perspective` e `backdrop-filter` para criar um visual moderno e interativo.

---

## 📸 Prévia

\
*(Substitua por um print real do seu projeto)*

---

## 🚀 Funcionalidades

- Cubo 3D com **animação contínua**
- Efeito **neon pulsante** no texto
- Fundo com **imagem e gradiente translúcido**
- Bordas com **brilho animado**
- 100% feito em HTML e CSS (sem JavaScript)
- Responsivo para telas grandes e pequenas

---

## 📂 Estrutura do Projeto

```
seu-projeto/
│── index.html
│── README.md
│── src/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css
│   │   └── img/
│   │       └── planeta.jpg
```

---

## 💻 Como Usar

1. **Clone ou baixe o repositório**

```bash
git clone https://github.com/seu-usuario/cubo-3d-neon.git
```

2. **Abra o projeto**

- Basta abrir o arquivo `index.html` no navegador.

---

## 🎨 Personalização

### Mudar a cor neon

No arquivo `style.css`, altere a cor das sombras do texto e do cubo:

```css
.neon-text {
    text-shadow: 0 0 5px #00f0ff, 0 0 10px #00f0ff, 0 0 20px #00f0ff;
}

.cubo-face {
    box-shadow: 0 0 20px #00f0ff;
}
```

### Trocar a imagem de fundo

Substitua `planeta.jpg` na pasta `img` e atualize o caminho no CSS:

```css
body {
    background-image: linear-gradient(rgba(3,3,3,0.5), rgba(0,0,0,0.5)), url(../img/sua-imagem.jpg);
}
```

### Ajustar tamanho do cubo

Modifique `width` e `height` na classe `.cubo` no CSS:

```css
.cubo {
    width: 200px;
    height: 200px;
}
```

### Responsividade

Para telas menores, ajuste o tamanho do cubo e do texto usando media queries:

```css
@media (max-width: 600px) {
    .cubo {
        width: 120px;
        height: 120px;
    }

    .neon-text {
        font-size: 1.5rem;
    }
}
```

---

## 📜 Licença

Este projeto é de **uso livre** para estudo, prática e personalização.

---

## 💡 Observações

- Todos os efeitos são feitos **apenas com CSS**, sem JavaScript.
- O título `.neon-text` sempre ficará acima do cubo, independentemente da rotação.
- As faces do cubo utilizam `backdrop-filter: blur()` para o efeito de vidro translúcido.
- Ajuste o `perspective` do container `.animation-container` para alterar a profundidade do cubo.

Desenvolvido por Bruno Barbosa &copy; 2025