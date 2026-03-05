# Portfolio Pessoal - Desenvolvedor Web

Um portfólio moderno e responsivo criado para showcasing de projetos de desenvolvimento web, incluindo sites, aplicações e landing pages.

## Características

### Design
- Layout moderno e profissional
- Tema dark com gradientes em roxo/azul
- Totalmente responsivo para todos os dispositivos
- Animações suaves e transições elegantes
- Efeitos visuais interativos (hover, parallax, etc)

### Seções Incluídas
1. **Hero Section** - Apresentação inicial impactante
2. **Sobre** - Informações pessoais e estatísticas
3. **Habilidades** - Cards com suas tecnologias e ferramentas
4. **Projetos** - Galeria filtrada de projetos em destaque
5. **Contato** - Formulário e informações de contato

### Funcionalidades

#### Seção de Projetos
- Sistema de filtragem por categoria (Todos, Sites, Aplicações, Landing Pages)
- Cards com overlay interativo
- Links para demo e código fonte
- Tags de tecnologias utilizadas
- Efeito tilt 3D nos cards ao passar o mouse

#### Navegação
- Menu responsivo com hamburger para mobile
- Scroll suave entre seções
- Indicador de seção ativa
- Efeito de transparência no scroll

#### Animações
- Scroll reveal para elementos
- Typing effect no subtítulo
- Contador animado para estatísticas
- Parallax no hero section
- Transições suaves em todos os elementos

#### Formulário de Contato
- Validação de campos
- Mensagem de confirmação animada
- Design integrado ao tema

## Estrutura de Arquivos

```
MEU PORTFOLIO/
│
├── index.html          # Estrutura HTML principal
├── styles.css          # Estilos e design
├── script.js           # Interatividade e animações
└── README.md           # Documentação
```

## Como Usar

1. **Personalize suas informações:**
   - Abra `index.html`
   - Substitua "Seu Nome", "Seu Logo" e outros textos placeholder
   - Atualize as informações de contato (email, telefone, localização)
   - Adicione seus links de redes sociais

2. **Adicione suas imagens:**
   - Substitua as imagens placeholder nos projetos
   - Adicione sua foto de perfil no hero section
   - Use imagens de qualidade e otimizadas

3. **Personalize os projetos:**
   - Edite os cards de projeto com seus próprios trabalhos
   - Atualize títulos, descrições e tags
   - Adicione links para demos e repositórios
   - Ajuste as categorias conforme necessário

4. **Ajuste as cores (opcional):**
   - Abra `styles.css`
   - Modifique as variáveis CSS em `:root`
   - Teste diferentes combinações de cores

5. **Configure o formulário:**
   - Integre com um serviço de backend
   - Ou use serviços como Formspree, EmailJS, etc.

## Tecnologias Utilizadas

- HTML5 semântico
- CSS3 com variáveis e Grid/Flexbox
- JavaScript vanilla (sem frameworks)
- Font Awesome para ícones
- Google Fonts (Inter)

## Customização Avançada

### Adicionar Mais Projetos

No `index.html`, copie um bloco `.project-card` e ajuste:
```html
<div class="project-card" data-category="sua-categoria">
    <!-- Seu conteúdo aqui -->
</div>
```

### Adicionar Nova Categoria de Filtro

1. Adicione o botão em `.project-filters`:
```html
<button class="filter-btn" data-filter="nova-categoria">Nova Categoria</button>
```

2. Use `data-category="nova-categoria"` nos cards relevantes

### Modificar Cores

Edite as variáveis no início do `styles.css`:
```css
:root {
    --primary-color: #sua-cor;
    --secondary-color: #sua-cor;
    --accent-color: #sua-cor;
}
```

## Otimizações Recomendadas

1. **Imagens:**
   - Use formatos modernos (WebP)
   - Otimize o tamanho das imagens
   - Implemente lazy loading

2. **Performance:**
   - Minifique CSS e JavaScript
   - Use CDN para bibliotecas
   - Implemente cache

3. **SEO:**
   - Adicione meta tags apropriadas
   - Crie um sitemap.xml
   - Use Open Graph tags

4. **Acessibilidade:**
   - Adicione alt text em todas as imagens
   - Teste navegação por teclado
   - Verifique contraste de cores

## Deploy

O site pode ser hospedado gratuitamente em:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

## Suporte para Navegadores

- Chrome (últimas 2 versões)
- Firefox (últimas 2 versões)
- Safari (últimas 2 versões)
- Edge (últimas 2 versões)

## Licença

Livre para uso pessoal e comercial.

---

Desenvolvido com dedicação para apresentar seus projetos da melhor forma possível!
