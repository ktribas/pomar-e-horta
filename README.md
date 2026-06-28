# 🌿 Manejo da Horta e Pomar

Painel interativo de manejo de horta e pomar para **Juquitiba/SP**, com calendário de poda guiado pelas fases da lua, adubação mês a mês e calendário de plantio. Funciona offline, direto no navegador.

🔗 **Acesse:** https://SEU-USUARIO.github.io/horta/
*(troque pelo seu link real do GitHub Pages)*

## O que tem aqui

O painel é dividido em quatro abas:

- **✂️ Poda & Lua** — 41 espécies frutíferas com tipo de poda, melhor época em Juquitiba/SP, grupo de manejo e a semana lunar recomendada para 2026. Tem busca e filtros por mês, grupo e tipo de poda, além de ordenação por qualquer coluna.
- **🌱 Adubação mensal** — o que adubar em cada mês do ano, como aplicar, grupos prioritários e os insumos minerais permitidos.
- **📖 Manejo do pomar** — notas técnicas por grupo (A a G), o critério lunar adotado e os princípios gerais de manejo das frutíferas.
- **🥬 Calendário de plantio** — 51 hortaliças, raízes e ervas, com melhor época de plantio, estação principal e exigência de sol. Filtra por categoria, estação e sol.

O **mês atual** aparece sempre destacado, tanto na tabela de poda quanto nos cards de adubação.

## Critério lunar adotado

- **Lua Minguante** → podas de frutificação, contenção e limpeza
- **Lua Nova** → evitar podas estruturais (estimula brotação)
- **Lua Cheia** → evitar (alta pressão de seiva)
- **Lua Crescente** → apenas podas verdes muito leves

## Como funciona

É uma única página `index.html`, sem servidor e sem dependências externas. Todos os dados estão embutidos no próprio arquivo, então abre instantaneamente e funciona sem internet.

## Como atualizar os dados

Os dados são uma "fotografia" da planilha de origem no momento em que a página foi gerada. Para atualizar:

1. Edite a planilha de manejo (fonte dos dados).
2. Gere uma nova versão do `index.html` a partir da planilha.
3. Suba o arquivo atualizado no repositório (**Add file → Upload files → Commit changes**).
4. O GitHub Pages republica sozinho em 1 a 2 minutos.

## Observações

- As épocas de poda são referências para o clima de Juquitiba/SP e podem variar conforme a altitude e o ano. Use como guia, observando sempre a dormência e a brotação reais de cada planta.
- As semanas lunares são fixas para **2026**.
