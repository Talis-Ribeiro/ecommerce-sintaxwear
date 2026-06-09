# SyntaxWear

Site estático de e-commerce para uma loja de tênis e sneakers, criado com HTML, CSS e uma estrutura simples de pastas para estilos, scripts e imagens.

## Descrição

`SyntaxWear` é um site responsivo que apresenta uma landing page de e-commerce com seções de destaque, categorias de produtos, grade de modelos e um rodapé informativo. O layout foi pensado para ser adaptável a dispositivos desktop, tablet e mobile.

## Tecnologias usadas

- HTML5
- CSS3
- JavaScript (arquivo de script disponível, pronto para futuras interações)

## Estrutura do projeto

- `index.html` - página principal
- `css/` - arquivos de estilo
  - `base.css` - estilos globais e reset de base
  - `product-grid.css` - layout da grade de produtos
  - `variables.css` - variáveis de cores e tipografia
  - `components/` - estilos de componentes específicos
    - `header.css`
    - `hero.css`
    - `product-category.css`
    - `footer.css`
- `js/` - scripts JavaScript
  - `main.js` - ponto de entrada para futura lógica de interação
- `images/` - imagens e ícones usados no site

## Como usar localmente

1. Abra a pasta do projeto no VS Code ou outro editor.
2. Abra `index.html` diretamente no navegador.
3. Para melhor experiência de desenvolvimento, use uma extensão como `Live Server` no VS Code.

## Organização de layout

- Cabeçalho fixo com logo e menu mobile
- Banner hero com chamada principal e botões de ação
- Seção de categorias com cards de produtos
- Grade de produtos com cards destacados e imagens
- Rodapé com formulário de e-mail, links rápidos e descrição de redes sociais


## Observações

- O projeto é estático e não requer servidor backend.
- O arquivo `js/main.js` está pronto para implementar futuras funcionalidades como menu mobile, carrinho ou interações dinâmicas.
- Ajustes de responsividade são feitos principalmente em `css/components/hero.css`, `css/components/product-category.css`, `css/product-grid.css` e `css/components/footer.css`.

## Contato

- Use o repositório no GitHub para versionamento e deploy.
- Atualize o README conforme o site evolui ou novas seções forem adicionadas.
