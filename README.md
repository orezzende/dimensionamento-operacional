# Calculadora de Dimensionamento Operacional

Ferramenta de logística que calcula a equipe necessária a partir de volumetria, horas disponíveis e produtividade, com medidores de desempenho e leitura automática de relatórios exportados do SAP. Funciona no computador e no celular.

**Demo:** https://orezzende.github.io/dimensionamento-operacional/

## Funcionalidades

- Cálculo da equipe necessária e medidor de performance (abaixo da meta, pode melhorar, ótimo)
- Painéis de Conferência de Notas e Conferência de Engaiolamento, com metas editáveis e cálculo individual por colaborador
- Programador do dia seguinte: calcula conferentes e engaioladores necessários e aplica no cenário do dia
- Leitura de relatórios em Excel, Word e PDF de uma pasta do computador, com visões Simplificada e Detalhada
- Filtro por colaborador, status por desempenho e tabelas expansíveis com rolagem

## Tecnologias

HTML, CSS, JavaScript, PDF.js, SheetJS (xlsx), Mammoth.js, IndexedDB, File System Access API

## Como usar

Preencha o cenário do dia e clique em **Calcular**. A conexão com a pasta de relatórios usa a File System Access API e funciona em Chrome e Edge.

Também dá para baixar o repositório e abrir o `index.html` direto no navegador, sem instalar nada.

## Observações

As bibliotecas (PDF.js, SheetJS e Mammoth.js) são carregadas por CDN, então é preciso estar online.

## Autor

Daniel da Silva Rezende · [GitHub](https://github.com/orezzende) · [LinkedIn](https://www.linkedin.com/in/daniel-da-silva-rezende-711ab1195/)
