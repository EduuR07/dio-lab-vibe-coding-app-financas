Crie um app de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): 

PRD — Aplicativo de Organização de Finanças Pessoais por Conversa

1. Visão Geral

Criar uma aplicação web de organização de finanças pessoais na qual o usuário possa registrar e acompanhar sua vida financeira utilizando principalmente linguagem natural.

Em vez de depender de formulários extensos ou planilhas, o usuário poderá escrever mensagens como:

- "Gastei R$ 42,90 no mercado hoje."
- "Paguei R$ 79,90 de internet."
- "Recebi R$ 1.500 de salário."
- "Quero juntar R$ 3.000 para comprar um notebook."

O sistema deverá interpretar essas mensagens, transformar as informações em dados estruturados e utilizá-las para apresentar resumos, metas e orientações financeiras simples.

A solução deverá ser concebida segundo princípios de Design Universal, buscando oferecer uma experiência simples, compreensível e acessível para o maior número possível de pessoas, independentemente de idade, experiência tecnológica, limitações temporárias ou permanentes e diferentes formas de interação com o sistema.

2. Problema

Muitas pessoas têm dificuldade em manter o controle de suas finanças porque as ferramentas existentes podem exigir:

- preenchimento manual frequente;
- criação de categorias;
- manutenção de planilhas;
- conhecimento prévio sobre organização financeira;
- interação com interfaces complexas.

Como consequência, usuários iniciantes podem abandonar rapidamente o controle financeiro.

A proposta do produto é reduzir essa barreira utilizando uma interface conversacional, simples e inclusiva.

3. Objetivo do Produto

Permitir que um usuário iniciante consiga registrar, visualizar e compreender suas finanças pessoais com o mínimo possível de entrada manual e de esforço cognitivo.

A principal ação do produto deve ser:

"Conversar com o aplicativo para registrar e consultar informações financeiras."

O produto deve procurar atender usuários com diferentes níveis de familiaridade digital, diferentes dispositivos e diferentes necessidades de acessibilidade.

4. Público-Alvo

Pessoas que querem começar a organizar suas finanças pessoais, mas não possuem experiência com planilhas, orçamento ou aplicativos financeiros complexos.

Perfil principal

Usuário que:

- possui pouca ou nenhuma experiência com controle financeiro;
- quer entender para onde seu dinheiro está indo;
- prefere uma experiência simples e visual;
- não quer preencher diversos formulários;
- quer estabelecer pequenas metas de economia;
- pode utilizar diferentes dispositivos ou tecnologias assistivas;
- pode apresentar dificuldades visuais, motoras, cognitivas ou de compreensão de interfaces complexas.

5. Proposta de Valor

"Organize suas finanças apenas conversando."

O aplicativo deverá transformar frases naturais em informações financeiras organizadas automaticamente.

A experiência deverá priorizar simplicidade, clareza e acessibilidade, evitando exigir conhecimento técnico ou financeiro prévio do usuário.

6. Princípio de Design Universal

O produto deverá seguir princípios de Design Universal, buscando ser utilizável pelo maior número possível de pessoas sem depender de adaptações específicas posteriores.

O Design Universal deverá ser tratado como requisito transversal do produto e não apenas como uma etapa final de acessibilidade.

A interface deve considerar desde o início:

- diferentes níveis de conhecimento digital;
- usuários jovens e idosos;
- usuários com baixa visão;
- usuários com dificuldades de percepção de cores;
- usuários que utilizam teclado em vez de mouse;
- usuários que utilizam leitores de tela;
- usuários com limitações motoras;
- usuários com dificuldades cognitivas ou de atenção;
- diferentes tamanhos de tela;
- diferentes condições de iluminação;
- limitações temporárias, como uso com uma única mão ou ambiente barulhento.

O objetivo não é criar versões separadas do produto para cada perfil, mas uma experiência principal que funcione bem para o máximo de pessoas possível.

7. Diretrizes de Design Universal e Acessibilidade

7.1 Uso simples e intuitivo

A interface deverá evitar complexidade desnecessária.

Priorizar:

- linguagem simples;
- ações claras;
- poucos elementos por tela;
- organização previsível;
- feedback imediato após ações importantes.

Evitar termos financeiros técnicos sempre que não forem necessários.

Exemplo:

Preferir:

"Quanto você gastou este mês?"

Em vez de:

"Despesas acumuladas do período corrente."

7.2 Informação perceptível

Informações importantes não deverão depender exclusivamente de:

- cor;
- ícones;
- posição visual;
- animações.

Exemplo:

Uma despesa não deverá ser identificada apenas pela cor vermelha.

Utilizar também:

- texto "Despesa";
- símbolo;
- valor;
- descrição textual.

7.3 Contraste e legibilidade

O sistema deverá apresentar:

- contraste adequado entre texto e fundo;
- tamanho de fonte confortável;
- espaçamento adequado;
- textos legíveis em telas pequenas;
- hierarquia visual clara.

Evitar textos muito pequenos ou informações excessivamente compactadas.

7.4 Navegação por teclado

Todas as principais funcionalidades deverão poder ser utilizadas sem mouse.

O usuário deverá conseguir:

- navegar pelos elementos utilizando Tab;
- identificar visualmente qual elemento está em foco;
- ativar botões e links pelo teclado;
- preencher e enviar informações sem depender de ações exclusivamente feitas com mouse.

7.5 Compatibilidade com leitores de tela

Elementos da interface deverão possuir estrutura semântica adequada.

Utilizar:

- títulos hierárquicos;
- labels em campos;
- textos alternativos quando necessário;
- descrições apropriadas para botões;
- atributos ARIA apenas quando necessário.

Evitar elementos interativos sem identificação textual.

7.6 Áreas de interação adequadas

Botões, links e demais controles deverão possuir tamanho suficiente para serem utilizados confortavelmente em telas sensíveis ao toque.

Evitar elementos muito pequenos ou excessivamente próximos.

7.7 Tolerância a erros

O sistema deverá reduzir as consequências de erros do usuário.

Exemplo:

Usuário:

"Gastei R$ 500 no mercado."

O aplicativo deverá apresentar:

"Entendi assim:

Despesa: R$ 500,00
Categoria: Alimentação
Descrição: Mercado
Data: Hoje

Confirmar?"

O usuário poderá corrigir a informação antes que ela seja salva.

Operações destrutivas, como exclusões, deverão solicitar confirmação.

7.8 Baixo esforço cognitivo

A interface deverá evitar exigir que o usuário memorize informações entre telas.

Sempre que possível:

- apresentar contexto;
- exibir informações relevantes;
- oferecer exemplos;
- sugerir ações;
- manter padrões de navegação consistentes.

O chat deverá aceitar linguagem natural, sem exigir comandos específicos.

7.9 Responsividade

A aplicação deverá oferecer boa experiência em:

- smartphones;
- tablets;
- notebooks;
- desktops.

Nenhuma funcionalidade principal deverá depender de uma resolução específica.

8. Escopo do MVP

O MVP deve validar principalmente três hipóteses:

1. O usuário consegue registrar suas movimentações financeiras através de mensagens.
2. O sistema consegue transformar essas mensagens em transações estruturadas.
3. O usuário consegue compreender sua situação financeira através de um dashboard simples.

Além disso, o MVP deverá validar se a experiência principal permanece compreensível e utilizável por pessoas com diferentes níveis de familiaridade tecnológica.

O MVP não precisa ser um sistema financeiro completo.

9. Funcionalidades do MVP

9.1 Autenticação

O usuário deve poder:

- criar uma conta;
- realizar login;
- sair da aplicação.

Cada usuário poderá visualizar apenas seus próprios dados.

9.2 Registro de transações por chat

O usuário poderá escrever mensagens em linguagem natural.

Exemplo:

"Gastei 35 reais no almoço hoje."

O sistema deverá identificar:

- tipo: despesa;
- valor: R$ 35,00;
- descrição: almoço;
- categoria sugerida: Alimentação;
- data: data atual.

Antes de salvar, o sistema deverá apresentar uma confirmação visual e textual.

Exemplo:

"Entendi assim:

Despesa: R$ 35,00
Categoria: Alimentação
Descrição: Almoço
Data: 15/10/2026

Confirmar registro?"

O usuário poderá:

- confirmar;
- cancelar;
- corrigir os dados.

9.3 Receitas e despesas

O sistema deverá aceitar pelo menos dois tipos de movimentações.

Exemplo de receita:

"Recebi 1500 reais do meu salário."

Exemplo de despesa:

"Gastei 80 reais abastecendo o carro."

9.4 Classificação automática

As transações deverão receber uma categoria automaticamente.

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Assinaturas
- Salário
- Outros

Caso o sistema não consiga identificar uma categoria com confiança, deverá utilizar "Outros" ou solicitar confirmação do usuário.

9.5 Histórico de transações

Cada transação deverá exibir:

- descrição;
- valor;
- tipo;
- categoria;
- data.

O usuário poderá:

- editar;
- excluir.

As informações não deverão depender exclusivamente de cores para diferenciação.

9.6 Dashboard financeiro

Criar um dashboard simples contendo:

Resumo do mês

- total de receitas;
- total de despesas;
- saldo do período.

Gastos por categoria

Exibir gráfico simples acompanhado de representação textual ou valores que permitam compreender a informação sem depender exclusivamente da visualização gráfica.

Transações recentes

Exibir as movimentações financeiras mais recentes.

Meta financeira

Exibir o progresso da meta principal do usuário, caso exista.

9.7 Metas financeiras

O usuário poderá criar uma meta financeira.

Exemplo:

"Quero guardar R$ 3.000 para comprar um notebook."

A meta deverá possuir:

- nome;
- valor desejado;
- valor já acumulado;
- data limite opcional.

O progresso deverá possuir representação textual e visual.

Exemplo:

"Notebook
R$ 1.200 de R$ 3.000
40% concluído"

No MVP, o usuário poderá atualizar manualmente o valor acumulado.

9.8 Agente Financeiro

O aplicativo deverá possuir um componente chamado "Agente Financeiro".

Sua função será analisar os dados já cadastrados pelo usuário e apresentar observações simples.

Exemplos:

"Alimentação foi sua maior categoria de gastos neste mês."

"Você gastou R$ 180 em lazer neste mês."

"Sua meta está 40% concluída."

"Se você economizar R$ 100 por mês, poderá avançar mais rapidamente na sua meta."

As orientações devem possuir caráter educativo e informativo.

O sistema não deverá fornecer recomendações de investimento, crédito ou decisões financeiras de alto risco no MVP.

As mensagens devem evitar jargões financeiros desnecessários.

10. Fluxo Principal do Usuário

10.1 Primeiro acesso

Landing Page
-> Criar conta
-> Login
-> Onboarding simples
-> Dashboard

Durante o onboarding, perguntar apenas:

- nome;
- objetivo principal com o aplicativo.

Exemplos de objetivos:

- controlar gastos;
- economizar dinheiro;
- entender minhas despesas.

10.2 Registro de gasto

Dashboard
-> Abrir chat
-> Digitar "Gastei R$ 45 no mercado"
-> Sistema interpreta mensagem
-> Sistema apresenta confirmação
-> Usuário confirma
-> Transação é salva
-> Dashboard é atualizado

10.3 Consulta

O usuário poderá fazer perguntas como:

"Quanto eu gastei esse mês?"

"Quanto gastei com alimentação?"

"Qual foi minha maior categoria de gastos?"

O sistema deverá responder utilizando apenas os dados financeiros cadastrados pelo próprio usuário.

11. Telas do MVP

11.1 Landing Page

Objetivo: apresentar rapidamente o produto.

Elementos:

- nome ou logo;
- headline;
- breve explicação;
- botão "Começar agora";
- botão "Entrar".

Mensagem principal sugerida:

"Organize suas finanças conversando."

Mensagem secundária:

"Registre gastos, acompanhe metas e entenda para onde seu dinheiro está indo sem depender de planilhas."

11.2 Login e Cadastro

Permitir:

- criação de conta;
- login;
- recuperação de senha, caso seja simples de implementar.

11.3 Dashboard

Componentes:

- saldo do mês;
- receitas;
- despesas;
- gráfico por categoria;
- meta financeira;
- transações recentes;
- acesso destacado ao chat.

11.4 Chat Financeiro

Interface semelhante a aplicativos de mensagem.

Componentes:

- histórico da conversa;
- campo de texto;
- botão enviar;
- mensagens do usuário;
- respostas do agente;
- cards de confirmação de transação.

11.5 Transações

Lista contendo:

- descrição;
- categoria;
- valor;
- data;
- tipo.

Permitir:

- editar;
- excluir.

11.6 Metas

Exibir:

- metas cadastradas;
- valor desejado;
- valor acumulado;
- percentual concluído.

Permitir:

- criar meta;
- editar meta;
- excluir meta;
- atualizar progresso.

12. Modelo de Dados Inicial

Usuário

- id
- nome
- email
- created_at

Transação

- id
- user_id
- tipo
- descricao
- valor
- categoria
- data
- created_at

Tipos possíveis:

- receita
- despesa

Meta

- id
- user_id
- nome
- valor_objetivo
- valor_atual
- data_limite
- created_at

13. Regras de Negócio

1. Uma transação deve sempre pertencer a um usuário.

2. Um usuário não pode acessar transações ou metas de outro usuário.

3. Toda transação deve possuir:
   - valor;
   - tipo;
   - data.

4. Transações criadas pelo chat devem ser confirmadas antes de serem salvas.

5. Valores financeiros nunca devem ser negativos no banco de dados. O tipo da transação determina se ela representa entrada ou saída.

6. Caso nenhuma categoria seja identificada, utilizar "Outros".

7. Exclusões de transações deverão solicitar confirmação.

8. O dashboard deverá refletir imediatamente alterações realizadas nas transações.

14. Comportamento da IA

A IA deverá atuar como um assistente de organização financeira.

Ela deverá:

- interpretar mensagens relacionadas às finanças do usuário;
- extrair informações estruturadas;
- consultar dados cadastrados;
- explicar informações de maneira simples;
- sugerir hábitos básicos de economia.

A IA não deverá inventar valores ou movimentações que não existam.

Quando não possuir informação suficiente, deverá solicitar esclarecimento.

Exemplo:

Usuário:

"Gastei 50 ontem."

Resposta:

"Certo. Em que você gastou esses R$ 50?"

15. Experiência e Design

O produto deve transmitir:

- simplicidade;
- confiança;
- organização;
- tranquilidade;
- inclusão.

A interface deverá possuir aparência moderna sem sacrificar legibilidade ou facilidade de uso.

Diretrizes

Utilizar:

- boa hierarquia visual;
- espaçamento consistente;
- cards simples;
- ícones acompanhados de texto quando necessário;
- gráficos fáceis de interpretar;
- estados de foco visíveis;
- feedbacks claros;
- textos objetivos.

Evitar:

- baixo contraste;
- excesso de animações;
- informações transmitidas apenas por cores;
- textos excessivamente pequenos;
- interfaces visualmente sobrecarregadas;
- navegação escondida ou pouco intuitiva.

16. Stack Sugerida

Para fins de aprendizado e prototipação:

Frontend

- React
- TypeScript
- Tailwind CSS
- componentes reutilizáveis

Backend e persistência

- Supabase

Utilizar:

- Supabase Auth para autenticação;
- PostgreSQL ou Supabase Database para dados;
- Row Level Security para isolamento dos dados de cada usuário.

Inteligência Artificial

Utilizar um modelo de linguagem para:

- interpretação das mensagens;
- extração estruturada das transações;
- respostas do Agente Financeiro.

A integração deverá manter a chave da API protegida no backend e nunca exposta diretamente no frontend.

17. Requisitos Não Funcionais

A aplicação deverá:

- funcionar em desktop e dispositivos móveis;
- possuir feedback visual de carregamento;
- tratar erros de maneira amigável;
- impedir acesso não autorizado aos dados;
- armazenar valores monetários de maneira apropriada;
- possuir interface consistente entre as páginas;
- possuir navegação por teclado;
- ser compatível com tecnologias assistivas;
- seguir boas práticas de acessibilidade web;
- possuir contraste visual adequado;
- permitir zoom sem perda significativa de funcionalidade;
- utilizar HTML semântico;
- apresentar textos claros e objetivos.

Sempre que possível, utilizar como referência as diretrizes WCAG atuais para acessibilidade web.

18. Fora do Escopo do MVP

Não implementar inicialmente:

- integração automática com bancos;
- Open Finance;
- importação de extratos bancários;
- investimentos;
- recomendações de ativos;
- cartão de crédito completo;
- parcelamento complexo;
- contas compartilhadas;
- integração com WhatsApp;
- notificações push;
- OCR de notas fiscais;
- leitura de boletos;
- múltiplas moedas;
- sistema de assinatura ou pagamento;
- gamificação avançada.

Essas funcionalidades poderão ser avaliadas após a validação do MVP.

19. Critérios de Aceite do MVP

O MVP será considerado funcional quando um usuário conseguir:

1. criar uma conta e entrar no sistema;
2. escrever "Gastei R$ 30 no almoço" no chat;
3. receber uma interpretação correta da mensagem;
4. confirmar a movimentação;
5. visualizar a transação salva;
6. visualizar o dashboard atualizado;
7. criar uma meta financeira;
8. acompanhar o progresso dessa meta;
9. perguntar sobre seus gastos e receber uma resposta baseada nos dados cadastrados;
10. editar e excluir uma transação;
11. navegar pelas funcionalidades principais utilizando teclado;
12. compreender as informações sem depender exclusivamente de cores ou gráficos;
13. utilizar o sistema com zoom aumentado sem perda significativa de funcionalidade.

20. Estratégia de Validação

Realizar inicialmente testes com aproximadamente 5 a 10 usuários.

Solicitar que cada pessoa execute tarefas como:

Tarefa 1

Registrar um gasto utilizando o chat.

Tarefa 2

Registrar uma receita.

Tarefa 3

Descobrir quanto gastou durante o mês.

Tarefa 4

Criar uma meta financeira.

Tarefa 5

Descobrir qual categoria possui mais gastos.

Observar:

- se o usuário entende naturalmente como registrar uma transação;
- se precisa de explicações;
- se confia na interpretação feita pela IA;
- se entende os gráficos;
- se considera o processo mais fácil do que registrar manualmente;
- se os textos são compreensíveis;
- se os botões e controles são fáceis de utilizar;
- se existe alguma informação dependente somente de cor;
- se o fluxo pode ser concluído pelo teclado;
- se o sistema continua utilizável com zoom aumentado.

Pergunta principal de validação:

"Você usaria esse método de conversa no dia a dia para registrar seus gastos?"

21. Validação de Design Universal

Os testes do MVP deverão incluir não apenas a validação das funcionalidades, mas também a facilidade de uso.

Durante os testes, observar:

- o usuário encontra as funções sem orientação?
- os textos são compreensíveis?
- existe alguma informação transmitida somente por cor?
- o fluxo pode ser concluído apenas pelo teclado?
- o sistema continua utilizável com zoom aumentado?
- os botões possuem tamanho confortável?
- mensagens de erro explicam como corrigir o problema?
- os gráficos também apresentam informações em formato textual?

Sempre que possível, testar com pessoas que apresentem diferentes níveis de familiaridade com tecnologia.

22. Métricas Iniciais de Sucesso

Durante os testes, observar:

- percentual de transações interpretadas corretamente;
- quantidade de correções realizadas pelo usuário;
- tempo necessário para registrar uma transação;
- percentual de usuários que conseguem executar as tarefas sem ajuda;
- percepção de facilidade de uso;
- quantidade de erros de navegação;
- quantidade de barreiras de acessibilidade identificadas.

Meta inicial sugerida:

"Pelo menos 80% das transações simples devem ser interpretadas corretamente sem intervenção manual."

23. Prioridade de Desenvolvimento

O desenvolvimento deverá acontecer incrementalmente.

Fase 1 - Estrutura visual

Criar:

- Landing Page;
- Login e Cadastro;
- Dashboard;
- Chat;
- Transações;
- Metas.

Utilizar inicialmente dados simulados.

Já nesta fase, aplicar os princípios de Design Universal e acessibilidade.

Fase 2 - Backend

Implementar:

- autenticação;
- banco de dados;
- persistência das transações;
- metas;
- isolamento dos dados entre usuários.

Fase 3 - Chat

Implementar:

- interpretação de mensagens;
- confirmação;
- criação automática de transações.

Fase 4 - Inteligência financeira

Implementar:

- consultas aos dados;
- análises por categoria;
- respostas do Agente Financeiro.

Fase 5 - Refinamento

Revisar:

- experiência mobile;
- estados de loading;
- mensagens de erro;
- empty states;
- acessibilidade;
- navegação por teclado;
- leitores de tela;
- contraste;
- legibilidade;
- consistência visual;
- comportamento com zoom aumentado.

24. Critério Central de Experiência

Uma funcionalidade não deverá ser considerada concluída apenas porque funciona tecnicamente.

Ela também deverá ser:

- compreensível;
- perceptível;
- operável;
- consistente;
- tolerante a erros.

O objetivo é criar uma experiência que não exija que o usuário se adapte ao sistema sempre que o próprio sistema puder se adaptar às diferentes formas de uso.

25. Princípio Central do Produto

Sempre que houver dúvida entre adicionar uma nova funcionalidade ou simplificar a experiência existente, priorizar simplicidade e inclusão.

Sempre que houver dúvida entre uma solução visualmente sofisticada e uma solução mais compreensível e acessível, priorizar a compreensão e a acessibilidade.

O objetivo do MVP não é substituir um banco ou aplicativo financeiro completo.

O objetivo é validar se:

"Conversar é uma maneira mais simples e natural de organizar as próprias finanças."

E também:

"Pessoas com diferentes perfis e formas de interação conseguem utilizar o produto com uma boa experiência."