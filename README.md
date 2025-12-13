# 💸 App Finanças Pessoais do Douglas com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o Lovable e o Copilot Web. A proposta é criar um
Aplicativo de Organização Financeira Pessoal baseado em interações em linguagem natural.

## 📑 PRD Refinado no Copilot Web

```markdown
# PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

## Visão Geral
O objetivo é criar um aplicativo que permita ao usuário organizar suas finanças pessoais por meio de conversas em linguagem natural. A proposta é substituir formulários complexos e planilhas manuais por uma experiência fluida e acessível, baseada em diálogo.

## Problema a Resolver
Muitos usuários abandonam aplicativos de finanças porque:
- Exigem entradas manuais excessivas.
- Oferecem pouca personalização.
- Tornam o processo burocrático e desmotivador.

O desafio é oferecer uma experiência simples, natural e motivadora, com recomendações automáticas que incentivem o usuário a continuar.

## Público-Alvo
- Pessoas que desejam começar a organizar suas finanças sem complicação.
- Usuários iniciantes em controle financeiro.
- Pessoas que preferem interações mais humanas e menos técnicas.
- Todos os perfis de usuários, considerando princípios de Design Universal para garantir acessibilidade e boa experiência para o maior número possível de pessoas.

## Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações em categorias (alimentação, transporte, lazer etc.).
3. Definição e acompanhamento de metas financeiras (ex.: economizar R$500/mês).
4. Agente Financeiro que fornece dicas personalizadas de economia.
5. Relatórios simples e personalizados, com visualizações amigáveis (gráficos e resumos).
6. Design Universal aplicado em todas as telas e interações, garantindo acessibilidade (ex.: contraste adequado, suporte a leitores de tela, navegação intuitiva).

## Entregável da IA
- Plano de MVP contendo:
  - Principais telas (chat, metas, relatórios).
  - Recursos necessários (NLP para interpretação de linguagem natural, motor de categorização, sistema de notificações).
  - Esboço de validação inicial (testes com usuários iniciantes e diversos perfis, incluindo pessoas com necessidades de acessibilidade).
  - Linguagem acessível e educativa para facilitar o aprendizado do usuário.
```

⚠️ **Aviso Importante de Segurança**

⚠️ **Leia antes de usar**

**Ele não deve ser utilizado para gerenciar dados financeiros reais ou informações sensíveis.** Este aplicativo foi desenvolvido como parte de um **desafio educacional do bootcamp da DIO.me** e tem caráter de **portfólio**. 

- Use **e-mails fictícios** e **senhas diferentes da sua principal** ao testar.  
- O foco aqui é demonstrar habilidades técnicas e criatividade, não oferecer um produto final pronto para produção.  
- Em um cenário real, seriam aplicadas medidas adicionais de segurança como **Row Level Security (RLS)**, **proteção contra senhas vazadas** e **monitoramento contínuo**.

---

## 💬 Interações com o Lovable

### Exemplos de Prompts Utilizados
> Crie um APP de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Tentei criar uma meta chamada Reserva de Emergência, mas ela não apareceu no componente. A impressão que tive foi que apenas o Assistente Financeiro a reconheceu, poderia verificar? Além disso, onde vejo os gráficos e o extrato? Além disso, o histórico do Chat aparentemente não fica salvo.

> Dados zerados para usuários novos. Adicione uma tela de Login, Registro e Esqueci a Senha para o usuário. Adicione uma IA ao Chatbot Assistente Financeiro Inteligente que responde perguntas sobre educação financeira. Adicione uma funcionalidade de parcelas com o nome "Adicionar Compras Parceladas". Adicione a funcionalidade de apagar e editar uma Meta. E na aba de relatórios adicione mais variações de categorias de gastos, além de "Alimentação, Lazer, Transporte e Outros".

> Backend: Sim, ativar Cloud. Parcelas: Registrar valor total e número de parcelas.

> Adicionar lembretes, Adicionar Tema Escuro, Adicionar Extrato Completo. Aparentemente os botões de exclusão e editar de Meta não estão aparecendo. E eu preciso que, quando um usuário crie uma conta, os valores venham zerados para ele e ele mesmo os adicione. 

### 🎯 Resultado Final
[conversa-fin-com-amigo.lovable.app](https://conversa-fin-com-amigo.lovable.app)

<img width="1875" height="956" alt="screencapture-conversa-fin-com-amigo-lovable-app-2025-12-13-15_43_36" src="https://github.com/user-attachments/assets/4c4c6d03-cdd8-4f7d-a843-3b3253cfdcb0" />

---

## ⚙️ Funcionalidades do Aplicativo de Finanças Pessoais

### 1. Visão Geral Financeira Mensal
- Exibe o saldo do mês, receitas e despesas de forma clara.
- Permite ao usuário acompanhar rapidamente sua situação financeira.

### 2. Registro de Transações via Chat
- Adição de gastos e receitas por meio de linguagem natural.
- Classificação automática das transações por categoria (ex.: Alimentação, Transporte, Lazer).

### 3. Metas Financeiras
- Área dedicada ao acompanhamento de metas de economia.
- Exibe progresso percentual e valor acumulado em relação ao objetivo.

### 4. Relatórios Personalizados
- Visualizações simples e acessíveis dos dados financeiros.
- Gráficos e resumos que facilitam o entendimento.

### 5. Agente Financeiro
- Oferece dicas personalizadas de economia com base nos hábitos do usuário.
- Atua como assistente virtual para melhorar a saúde financeira.

### 6. Design Universal
- Interface acessível e inclusiva para todos os perfis de usuários.
- Suporte a leitores de tela, contraste adequado, navegação intuitiva e linguagem clara.

---

## 💭 Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.

### O que não funcionou como o esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.

### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes e clareza você dá, melhor é a interação.

---

## 📬 Feedback e Suporte

Se você encontrar **qualquer erro técnico** no aplicativo, fique à vontade para me enviar um e-mail em **douglascblsousa.offsec@gmail.com**. 
Prometo responder e corrigir o problema o mais rápido possível 🚀.

Além disso, sugestões de melhorias são super bem-vindas! 💡
Sinta-se livre para compartilhar ideias que possam deixar o app ainda mais útil e divertido de usar.

