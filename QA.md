# Verificação — 24/11/2026

## Verificado

- `node --check` em `app.js` e `content.js`: aprovado.
- 138 verificações de integridade: IDs e cobertura das 18 aulas, referências de fontes, entradas dinâmicas nos dois layouts, assets e fontes presentes, e planos de sessão de 900 segundos.
- Abertura e fechamento da apresentação temática; carregamento das imagens principais.
- Navegação pelas **18 aulas**, com 18 títulos distintos, incluindo a volta ao progresso após a última.
- Marcação e desmarcação de aula atualiza contagem e módulo.
- Mudança Padrão → Clássico atualiza guarda, carga, Revenge Counter, especiais e outros comandos da tabela.
- Caderno e escolha do layout permanecem após recarregar a página.
- Busca sem correspondência mostra estado vazio; limpar a busca restaura os módulos.
- Cronômetro inicia, pausa e reinicia a sessão; avançar pelas quatro etapas encerra em 00:00 e desativa a continuação.
- Exercício de atenção completa o ciclo de espera, sinal e resultado.
- Conferência visual da página de computador, em viewport de aproximadamente 1348 px.
- Conferência em contexto de navegação estreito de **375 px úteis**, incluindo hero, abertura da aula, fechamento e atalho de combos. Documento e diálogo sem transbordamento horizontal.
- Direção visual no Figma com texto editável, componentes reutilizados, tokens e famílias Barlow / Barlow Condensed conferidas.

## Alcance

Os testes de interface foram realizados em Chromium. A largura de celular foi testada em um contexto de navegação de 390 px externos, com 375 px úteis devido à barra de rolagem. Não houve teste em aparelho iPhone/Android físico, Safari ou dentro do PS5.

Os comandos foram pesquisados; o jogo não foi executado neste ambiente. As rotas de combo estão explicitamente condicionadas a personagem, distância, patch e defesa. O minijogo de reação não valida timing do jogo. A apresentação não espera assets externos para permitir entrada.

O progresso utilizado na verificação foi devolvido a zero e o caderno de teste foi limpo. Esses dados são locais ao navegador de teste e nunca entram nos arquivos publicados.

## Versão incorporada

O HTML final também passou por verificação de sintaxe dos scripts e teste no navegador: 6 módulos, família de fonte correta, símbolo carregado por data URL e aula do Galick Gun com comandos Clássicos.

## Revisão de linguagem e controle interativo

Em 24/11/2026, as 18 aulas foram reescritas em linguagem mais simples. IDs e comandos dos dois layouts foram comparados com a versão anterior: preservados. A revisão também passou por verificação de sintaxe e referência de comandos.

Foram testadas 22 explicações de botões (11 em cada layout), a atualização ao trocar de Padrão para Clássico, o salvamento de uma aula após recarregar e a retirada dessa marca ao fim do teste. Em largura útil de 375 px, a página e a lista de botões ficaram sem transbordamento horizontal.
