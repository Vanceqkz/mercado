# Comercial Junior

Site do supermercado Comercial Junior (Barrolândia, Belmonte – BA).
Página única em HTML, CSS e JavaScript, sem etapa de build.

## Como editar
Tudo está em `index.html`:
- **Produtos e preços:** objeto `D`, dentro do `<script>`, em formato `["Nome", "peso", preço]`, agrupado por categoria.
- **Fotos:** objeto `IMG`. Associe o nome completo do produto ao arquivo, por exemplo `IMG["Arroz 5kg"]="img/arroz-5kg.jpg"`. Sem foto, o card mostra um espaço reservado.
- **WhatsApp:** constante `NUM`.
- **Horário (07h às 19h, horário de Brasília):** função `hrs()`.

## Publicação
- **GitHub Pages:** Settings > Pages > Deploy from a branch > `main` / root.
- **Vercel:** importe o repositório; nenhuma configuração é necessária.

## Pendências
- Fotografias reais dos produtos.
- Painel administrativo com banco de dados (por exemplo, Supabase).

Desenvolvido por Arthur Altoé.
