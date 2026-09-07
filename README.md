# Portfólio - Josué Kito

Um site portfólio moderno e responsivo criado com HTML, CSS e JavaScript puro.

## 🎨 Características

- ✅ Design moderno e profissional
- ✅ Totalmente responsivo (mobile, tablet, desktop)
- ✅ Animações suaves e interativas
- ✅ Seções: Home, Sobre, Projetos, Contato
- ✅ Links para redes sociais (Facebook, GitHub)
- ✅ Formulário de contato
- ✅ Sem dependências externas (apenas Font Awesome para ícones)

## 📁 Estrutura do Projeto

```
josuekito.github.io/
├── index.html      # Arquivo HTML principal
├── styles.css      # Estilos e layout
├── script.js       # Interações e animações
└── README.md       # Este arquivo
```

## 🚀 Como Usar

### 1. Personalize suas Informações

**Em `index.html`**, procure pelas seções a seguir e atualize:

- **Seção "Sobre"**: Altere o texto sobre você
- **Projetos**: Edite os 3 cards de projetos com seus próprios projetos
- **Contato**: Atualize seus links de Facebook, GitHub e Email

### 2. Adicionar Seus Projetos

Encontre a seção `<!-- Projetos Section -->` e adicione novos cards:

```html
<div class="projeto-card">
    <div class="projeto-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <h3>Nome do Projeto</h3>
    <p>Descrição do projeto</p>
    <div class="projeto-tags">
        <span class="tag">Tecnologia 1</span>
        <span class="tag">Tecnologia 2</span>
    </div>
    <a href="link-do-projeto" class="btn btn-small">Ver Projeto</a>
</div>
```

### 3. Adicionar Foto de Perfil

Substitua o placeholder do avatar com uma imagem real. Em `index.html`, procure:

```html
<div class="avatar-placeholder">
    <i class="fas fa-user"></i>
</div>
```

E substitua por:

```html
<img src="sua-foto.jpg" alt="Sua Foto" class="avatar">
```

Então adicione este CSS ao final de `styles.css`:

```css
.avatar {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 10px 40px rgba(99, 102, 241, 0.3);
}
```

### 4. Atualizar Links Sociais

Em `index.html`, procure a seção "Redes Sociais" e atualize:

```html
<a href="https://www.facebook.com/seu-usuario" target="_blank">
<a href="https://github.com/seu-usuario" target="_blank">
<a href="mailto:seu-email@gmail.com">
```

## 🎨 Cores

As cores principais podem ser customizadas em `styles.css`:

```css
:root {
    --primary-color: #6366f1;       /* Cor principal (Indigo) */
    --secondary-color: #8b5cf6;     /* Cor secundária (Roxo) */
    --dark-bg: #0f172a;             /* Fundo escuro */
    --light-bg: #f8fafc;            /* Fundo claro */
    --text-dark: #1e293b;           /* Texto escuro */
    --text-light: #64748b;          /* Texto claro */
}
```

## 📱 Responsividade

O site é totalmente responsivo e funciona bem em:
- 📱 Celulares (320px+)
- 📱 Tablets (768px+)
- 💻 Desktops (1024px+)

## 🚀 Deploy no GitHub Pages

Seu site será automaticamente publicado em: `https://josuekito.github.io`

Basta fazer push das alterações para o repositório!

## ✏️ Edições Rápidas

### Mudar Título da Página
Em `index.html`, linha 7:
```html
<title>Seu Nome - Portfólio</title>
```

### Mudar Descrição
Na seção hero (linha 33):
```html
<p class="description">Sua descrição aqui</p>
```

### Adicionar Mais Habilidades
Na seção "Minhas Habilidades" (dentro de `.skills-grid`):
```html
<div class="skill-item">
    <i class="fab fa-nome-icon"></i>
    <span>Nome da Habilidade</span>
</div>
```

## 🔗 Ícones Disponíveis

O projeto usa Font Awesome 6.4.0. Acesse [FontAwesome Icons](https://fontawesome.com/icons) para encontrar mais ícones.

## 💡 Dicas

- Use imagens quadradas para os projetos (melhor proporção)
- Mantenha as descrições dos projetos concisas
- Adicione links válidos para seus projetos
- Teste em diferentes dispositivos antes de publicar

## 📄 Licença

Livre para usar e modificar! 🎉

---

**Desenvolvido com ❤️ para seu portfólio**
