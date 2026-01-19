# 💸 App de Finanças Pessoais LRA com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

PRD Refinado no Copilot

***
# PRD - App de Organização Financeira com Conversa Natural

## Visão Geral
Criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas em linguagem natural. O objetivo é tornar o controle financeiro mais intuitivo, acessível e livre de burocracias como planilhas ou formulários complexos.

## Problema a Resolver
Muitas pessoas abandonam o controle financeiro por acharem os aplicativos atuais complicados, exigindo entradas manuais e oferecendo pouca personalização. Queremos resolver isso com uma experiência conversacional fluida e recomendações automáticas que se adaptam ao perfil do usuário.

## Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicações — especialmente iniciantes que não têm familiaridade com apps financeiros tradicionais.

## Funcionalidades-Chave
1. Registro de gastos via chat: O usuário descreve seus gastos em linguagem natural, como “gastei R$ 30 no mercado”.
2. Classificação automática de transações: O app identifica e categoriza os gastos com base no texto.
3. Definição e acompanhamento de metas financeiras: O usuário pode criar metas como “economizar R$ 500 até o fim do mês”.
4. Dicas personalizadas do Agente Financeiro: Um assistente virtual que sugere formas de economizar com base nos hábitos do usuário.
5. Relatórios simples e personalizados: Visualizações claras dos gastos, metas e progresso, adaptadas ao estilo do usuário.
6. Registro de gastos por voz: Entrada de dados via comandos de voz para maior acessibilidade.
7. Exportação de relatórios: Possibilidade de exportar relatórios em PDF ou Excel.
8. Gamificação leve: Conquistas e incentivos visuais para estimular hábitos financeiros saudáveis.

## Princípio de Design Universal
A solução será construída com base em Design Universal, garantindo que o aplicativo ofereça uma experiência acessível, intuitiva e inclusiva para o maior número possível de pessoas — independentemente de idade, nível de alfabetização digital, limitações físicas ou cognitivas. Isso inclui:
- Interface clara e legível
- Navegação simples e sem sobrecarga de informações
- Compatibilidade com leitores de tela e comandos por voz
- Feedbacks visuais e auditivos para facilitar o uso

## Requisitos Não Funcionais
- Segurança: Dados criptografados em trânsito e em repouso.
- Performance: Tempo de resposta do chat inferior a 2 segundos.
- Escalabilidade: Suporte a milhares de usuários simultâneos.
- Compatibilidade: Disponível para Android e iOS desde o MVP.

## Métricas de Sucesso
- 70% dos usuários ativos registram pelo menos 5 gastos na primeira semana.
- 50% dos usuários criam e acompanham metas financeiras no primeiro mês.
- NPS acima de 60 após o teste piloto.

## Roadmap
### MVP
- Principais telas: chat, metas, relatórios.
- Recursos técnicos: NLP, categorização automática, motor de recomendações.
- Estratégia de validação inicial com 20–30 usuários reais.
- Linguagem acessível e tom educativo, em português.
- Aplicação dos princípios de Design Universal desde o protótipo.

### Versões Futuras
- Integração com bancos para importação automática de transações.
- Expansão de relatórios avançados.
- Recursos de comunidade e compartilhamento de metas.
- Suporte multilíngue.

## Estratégia de Validação
- Teste piloto com 20–30 usuários iniciantes em apps financeiros.
- Coleta de métricas de uso (engajamento, retenção, metas atingidas).
- Entrevistas qualitativas para feedback sobre usabilidade e clareza.
- Ajustes iterativos com base nos resultados.

***

Interações com o Lovable

> Crie um app de finanças pessoais com base no seguinte prd: # PRD - App de Organização Financeira com Conversa Natural - (PRD)
> Tentei criar uma meta chamada reserva de emergencia, mas ela não apareceu no componenete, o que senti foi que só o assistente financeiro a reconhecer, poderia verificar? Além disso onde vejo os gráficos de extrato?

Resultado Final no Lovable: https://talk-to-finances.lovable.app

<img width="1351" height="596" alt="image" src="https://github.com/user-attachments/assets/e0a8443a-1cfc-444e-a1b9-4fcf049c8fc3" />


## Funcionalidades do App

O aplicativo “Conversa Financeira” oferece uma experiência intuitiva e acessível para o controle das finanças pessoais, com foco em linguagem natural e design inclusivo.

### Principais Funcionalidades

- **Dashboard financeiro simplificado**  
  Exibe saldo atual, receitas, despesas e extrato mensal com visualização gráfica.

- **Registro de gastos por chat ou voz**  
  O usuário informa seus gastos em linguagem natural, como “gastei R$ 30 no mercado”.

- **Classificação automática de transações**  
  O app identifica e categoriza os gastos com base no texto ou comando de voz.

- **Metas financeiras personalizadas**  
  Criação e acompanhamento de objetivos como “economizar R$ 500 até o fim do mês”.

- **Conquistas e gamificação**  
  Sistema leve de incentivos para estimular hábitos financeiros saudáveis.

- **Relatórios visuais e exportáveis**  
  Visualizações claras dos gastos e metas, com opção de exportação em PDF ou Excel.

- **Assistente Financeiro com dicas personalizadas**  
  Recomendações adaptadas ao perfil e hábitos do usuário para melhorar o controle financeiro.

- **Design acessível e inclusivo**  
  Interface compatível com leitores de tela, comandos por voz e feedbacks visuais/auditivos.

## Reflexão

###O que funcionou bem?
 
    O refinamento prévio feito no copilot ajudou muito, pois a interação dentro do Lovable foram breves e em apen as duas interações.
    
### O que não funcionou como o esperado? 

    Pode interagir mais vezes com o Lovable, de forma gratuita.

### O que aprendeu sobre conversar com IAs?

    Aprendi que é basicamente igual como conversar com uma pessoal, com mais detalhes e clareza, melhor será a interação.
    
> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
