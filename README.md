# 💸 Finance Friend (Conversa) — Finanças pessoais com Vibe Coding

> Projeto desenvolvido para o desafio [App de Organização de Finanças Pessoais com Vibe Coding](https://github.com/digitalinnovationone/dio-lab-vibe-coding-app-financas), da **DIO**.

A proposta do **Finance Friend**, apresentado na interface como **Conversa**, é facilitar a organização financeira por meio de mensagens simples. Em vez de depender apenas de planilhas ou formulários, a pessoa pode descrever uma receita, uma despesa ou uma meta usando linguagem natural.

**Links:** [Aplicação no Lovable](https://chatty-cents-companion.lovable.app/) · [PRD utilizado](PRD.md) · [Repositório deste desafio](https://github.com/EduuR07/dio-lab-vibe-coding-app-financas)

## 🎯 Problema e objetivo

Muitas pessoas deixam de acompanhar seus gastos porque registrar cada movimentação pode ser trabalhoso. A ideia foi criar uma experiência mais simples e intuitiva, especialmente para quem está começando a cuidar das próprias finanças.

O objetivo do MVP é explorar três ações principais: **registrar movimentações por conversa**, **organizar os dados financeiros** e **visualizar um resumo claro das receitas, despesas e metas**.

## 🧠 Como utilizei Vibe Coding

Comecei escrevendo um **PRD (Product Requirements Document)** com o contexto do problema, o público-alvo, as funcionalidades, as regras de negócio e os critérios de experiência. Revisei a especificação com auxílio do ChatGPT e a utilizei para orientar a geração da aplicação no **Lovable**.

Também incluí o **Design Universal** como princípio do produto: linguagem compreensível, boa legibilidade, navegação clara e cuidado para não depender apenas de cores. Esses requisitos orientaram o projeto, mas a acessibilidade completa ainda depende de testes específicos.

📄 **[Ler o PRD original enviado ao Lovable](PRD.md)**

## 🖥️ Telas e funcionalidades propostas

A versão gerada apresenta as seguintes áreas:

| Área | Finalidade |
| --- | --- |
| **Painel** | Exibir receitas, despesas, saldo, gastos por categoria e um resumo de metas. |
| **Conversar** | Permitir o registro e a consulta de informações financeiras por mensagens. |
| **Transações** | Organizar movimentações, filtrar registros e oferecer cadastro manual. |
| **Metas** | Criar objetivos de economia e acompanhar seu progresso. |
| **Conta** | A aplicação também apresentou fluxo de cadastro com verificação por e-mail. |

> **Nota:** as imagens documentam as interfaces geradas. O cadastro com verificação por e-mail foi experimentado durante o desenvolvimento; as demais operações precisam ser validadas individualmente antes de serem consideradas totalmente testadas.

### Painel

![Painel financeiro com cartões de receitas, despesas e saldo](assets/painel.png)

### Conversa com o agente financeiro

![Interface do chat com exemplos de comandos financeiros](assets/chat.png)

Exemplos de interações previstas:

- `Gastei R$ 30 no almoço hoje.`
- `Recebi R$ 1.500 de salário.`
- `Quanto eu gastei este mês?`
- `Quero juntar R$ 3.000 para um notebook.`

### Histórico de transações

![Tela de transações com filtros e opção de adicionar manualmente](assets/transacoes.png)

### Metas financeiras

![Tela de metas com opção de criar um objetivo](assets/metas.png)

## 🛠️ Ferramentas utilizadas

- **ChatGPT:** apoio na revisão e organização dos requisitos do PRD.
- **Lovable:** geração e pré-visualização da aplicação a partir das instruções em linguagem natural.
- **GitHub:** documentação e entrega do desafio por meio de um fork do repositório da DIO.

## 🚧 Desafios e aprendizados

### O que funcionou bem?

O que mais me surpreendeu foi conseguir transformar uma especificação escrita em uma aplicação com várias telas e uma identidade visual consistente. A ferramenta gerou o painel, o chat, a área de transações e a área de metas. Também consegui passar pelo processo de criação de conta com verificação por e-mail, algo que eu não esperava ver tão rapidamente.

### O que não funcionou como eu esperava?

Meu primeiro PRD ficou muito extenso e solicitava muitas funcionalidades de uma só vez. Durante a geração, o Lovable consumiu os créditos gratuitos disponíveis e pausou o trabalho antes de concluir tudo. Isso me fez perceber que um documento detalhado ajuda a definir o produto, mas não significa que seja uma boa ideia implementar todos os requisitos em uma única solicitação.

![Lovable com geração pausada por falta de créditos](assets/lovable-creditos.png)

### O que aprendi sobre conversar com IAs?

Aprendi que **clareza, contexto e delimitação de escopo** fazem muita diferença. Não basta pedir “crie um aplicativo”: é importante explicar o problema, definir prioridades e dizer o que realmente precisa estar no MVP. Também entendi que o trabalho não termina quando a IA gera as telas. Ainda é necessário testar os fluxos, conferir os resultados e avaliar se a solução atende ao que foi pedido.

## 🔍 Próximos passos

- Testar o registro de receitas e despesas pelo chat e a atualização do painel.
- Verificar a edição e exclusão de transações e o progresso das metas.
- Avaliar a experiência em dispositivos móveis e com navegação por teclado.
- Refinar as interpretações de mensagens e os feedbacks de confirmação.

## 📌 Conclusão

O desafio mostrou, na prática, como o **Vibe Coding** pode acelerar a transformação de uma ideia em um protótipo navegável. Mais importante do que gerar código rapidamente foi aprender a estruturar requisitos, reconhecer limites da ferramenta e ajustar o escopo sem perder o objetivo do produto.

---

**Desenvolvido por Eduardo Rodrigues Bueno** · [GitHub](https://github.com/EduuR07) · Desafio DIO — Vibe Coding
