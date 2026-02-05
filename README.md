# Site Letícia Moura - Psicanálise

Site estático profissional para psicanalista clínica especializada em atendimento feminino.

## 📁 Estrutura dos Arquivos

```
/
├── index.html          # Página principal do site
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interatividade
├── cerebro.jpg         # Logo (você precisa adicionar)
└── images/
    ├── leticia-moura.jpg      # Foto da profissional (você precisa adicionar)
    └── hero-background.jpg    # Imagem de fundo hero (você precisa adicionar)
```

## 🖼️ Imagens Necessárias

Você precisa adicionar as seguintes imagens na pasta do site:

1. **cerebro.jpg** - Logo da psicanalista (colocar na raiz)
   - Dimensões recomendadas: 200x200px
   - Formato: JPG ou PNG

2. **images/leticia-moura.jpg** - Foto da profissional
   - Dimensões recomendadas: 600x800px
   - Formato: JPG

3. **images/hero-background.jpg** - Imagem de fundo da seção hero
   - Dimensões recomendadas: 1920x1080px
   - Formato: JPG

## 🔧 Configurações Necessárias

### 1. Número de WhatsApp
Substitua `5521999999999` pelo número real nos seguintes locais do `index.html`:
- Links do header
- Links dos botões de CTA
- Links do footer

**Formato:** 55 (código do Brasil) + DDD + número
Exemplo: `5521987654321`

### 2. E-mail de Contato
Substitua `contato@leticiapsi.com` pelo e-mail real no footer.

### 3. Links das Redes Sociais
No footer, adicione os links reais para:
- Instagram
- Facebook
- LinkedIn

### 4. Link de Avaliações do Google
No botão "Ir para Google Avaliações", adicione o link real do perfil do Google Meu Negócio.

## 🚀 Como Usar

### Opção 1: Hospedagem Simples
1. Faça upload de todos os arquivos para seu servidor web
2. Certifique-se de que a estrutura de pastas está correta
3. Adicione as imagens necessárias
4. Acesse pelo seu domínio

### Opção 2: Hospedagem Gratuita (GitHub Pages)
1. Crie um repositório no GitHub
2. Faça upload de todos os arquivos
3. Adicione as imagens
4. Ative o GitHub Pages nas configurações
5. Seu site estará disponível em: `https://seuusuario.github.io/nome-do-repo`

### Opção 3: Netlify (Recomendado)
1. Crie uma conta no Netlify (gratuito)
2. Arraste a pasta com os arquivos para o Netlify
3. Configure um domínio personalizado (opcional)

## 📱 Funcionalidades

- ✅ Design responsivo (mobile, tablet, desktop)
- ✅ Menu de navegação fixo
- ✅ FAQ interativo com accordion
- ✅ Animações suaves ao rolar a página
- ✅ Links para WhatsApp
- ✅ Seções completas: sobre, áreas, depoimentos, eBooks, formação
- ✅ Otimizado para SEO

## 🎨 Personalização de Cores

As cores principais estão definidas no arquivo `styles.css` nas variáveis CSS:

```css
:root {
    --primary-color: #8B4789;      /* Roxo principal */
    --secondary-color: #D4A5D4;    /* Roxo claro */
    --accent-color: #E8B4E8;       /* Rosa claro */
    --dark-color: #2C1C2E;         /* Escuro */
    --light-color: #F9F5F9;        /* Fundo claro */
}
```

Para mudar as cores, basta editar esses valores.

## 📝 Adicionando Conteúdo

### Adicionar Nova Área de Atuação
No `index.html`, dentro da seção `<div class="areas-grid">`, adicione:

```html
<div class="area-card">
    <h3>Título da Área</h3>
    <p>Descrição da área de atuação.</p>
</div>
```

### Adicionar Novo Depoimento
Na seção `<div class="depoimentos-grid">`, adicione:

```html
<div class="depoimento-card">
    <div class="avatar">👩</div>
    <h4>Nome do Cliente</h4>
    <p>"Depoimento aqui..."</p>
</div>
```

### Adicionar Novo eBook
Na seção `<div class="ebooks-grid">`, adicione:

```html
<div class="ebook-card">
    <h3>Título do eBook</h3>
    <p>Descrição do conteúdo.</p>
    <span class="price">Gratuito</span>
</div>
```

## 🔍 SEO

Para melhorar o SEO:
1. Adicione meta tags no `<head>` do HTML
2. Configure o Google Analytics (opcional)
3. Crie um arquivo `sitemap.xml`
4. Configure o Google Search Console

## 📞 Suporte

Para personalização adicional ou dúvidas, entre em contato.

## 📄 Licença

Este site foi desenvolvido para uso exclusivo de Letícia Moura Psicanálise.

---

**Última atualização:** Fevereiro 2026
