# 💸 App de Finanças Pessoais Finz do Luiz com Vibe Coding

PRD Refinado no Gemini e Chatgpt:

```txt
PRD: Assistente Financeiro Conversacional

1. Visão Geral do Produto

O objetivo é transformar a gestão financeira em uma tarefa tão simples quanto enviar uma mensagem de texto. O app utiliza inteligência artificial para interpretar entradas do usuário (ex: "Gastei 50 reais em pizza"), categorizar automaticamente e fornecer insights em tempo real, eliminando a barreira da entrada manual complexa.

Melhoria:
- Sistema de aprendizado contínuo (feedback do usuário corrige a IA).
- Sugestões proativas baseadas em comportamento financeiro.
- Foco em UX simples, rápido e agradável.

2. Experiência do Usuário (UX) e Telas Principais

Identidade Visual (Novo - Front-end Premium em Tons Verdes)

- Cor primária: Verde esmeralda (#0F9D58)
- Cor secundária: Verde escuro (#0B6E4F)
- Background: Gradiente suave (verde escuro → quase preto)
- Destaques: Verde neon suave para ações importantes
- Tipografia: Moderna (Inter / Poppins)
- Estilo: Clean, minimalista, elegante (estilo fintech premium)

Componentes:
- Cards com sombra suave e bordas arredondadas (rounded-2xl)
- Botões com efeito hover glow verde
- Animações leves (Framer Motion)
- Dark Mode como padrão

Tela 1: Dashboard Principal (Resumo Visual)

- Saldo Total: Exibição em Real (R$) e Dólar ($)
- Gráfico de Rosca: Distribuição de gastos por categoria
- Botão Flutuante (FAB): Acesso rápido ao chat
- Cards de Metas: Progresso visual com barras animadas
- Indicadores inteligentes (↑ gastos, ↓ economia)

Tela 2: Interface de Chat (Core do Produto)

- Input com NLP (linguagem natural)
- Feed estilo WhatsApp/ChatGPT
- Cards de confirmação de transação
- Sugestões rápidas (chips clicáveis)
- Respostas inteligentes do Agente Financeiro

Exemplo:
"Gastei 120 no mercado"
→ Detecta automaticamente categoria + valor

Tela 3: Carteira Multimoeda (BRL/USD)

- Gráfico comparativo mensal
- Conversão automática com taxa atual
- Separação visual clara entre moedas
- Indicador de impacto cambial

Tela 4: Configurações e Perfil

- Toggle Dark/Light Mode
- Exportação de dados
- Segurança (2FA opcional)
- Integração futura com bancos

3. Funcionalidades Detalhadas

- Parsing de Linguagem Natural (Essencial)
- Categorização Automática (Essencial)
- Gestão de Metas (Alta)
- Agente de Economia Inteligente (Alta)
- Suporte Multimoeda (Alta)
- Sistema de Autenticação (Essencial)

Melhorias:
- Correção manual rápida via UI
- Sugestões automáticas de economia
- Alertas inteligentes

4. Requisitos Técnicos (Lovable Stack)

Frontend:
- React.js
- Tailwind CSS
- Framer Motion (animações)
- Lucide-react (ícones)
- Recharts (gráficos)

Backend:
- Supabase (Auth + Database + Storage)

IA:
- OpenAI API (ou similar)
- Prompt estruturado para classificação:
  - Detectar valor
  - Detectar categoria
  - Detectar moeda
  - Detectar tipo (gasto/receita)

5. Plano de Validação do MVP

1. Teste de Input:
- IA deve acertar ≥ 90% das classificações

2. Engajamento:
- Avaliar uso de metas via chat vs botão

3. Clareza Multimoeda:
- Usuário entende separação BRL/USD sem confusão

6. Diferenciais Educativos

O app não apenas registra, ele ensina.

Exemplo de feedback:
"Seus gastos com delivery aumentaram 15% esta semana. Isso pode atrasar sua meta 'Viagem' em 2 meses. Que tal cozinhar hoje?"

Melhorias:
- Tom amigável e não julgador
- Gamificação leve (níveis financeiros)
- Insights semanais automáticos

7. Melhorias Estratégicas no Prompt (IA)

Prompt da IA deve incluir:

- Classificação estruturada (JSON):
{
  "tipo": "gasto | receita",
  "valor": number,
  "moeda": "BRL | USD",
  "categoria": "string",
  "descricao": "string limpa"
}

- Regras:
- Priorizar precisão sobre criatividade
- Nunca inventar valores
- Categorizar com base em contexto
- Pedir confirmação se ambíguo

8. Visão de Escala (Futuro)

- Integração com bancos (Open Finance)
- Notificações inteligentes
- IA preditiva de gastos
- Planejamento financeiro automático
- Versão web + mobile (PWA)


```

Interações com o Lovable:

> Crie um App de Finanças pessoais com base no seguinte PRD (Product Requirements Document) {PRD}

> Notei que quando tento fazer o login não tenho êxito nisso, corrija isso por favor.

> Mesmo colocando o login correto esta dando erro.

> Adicione novamente a função confirmar o endereço de email, e adicione no cadastro repetir senha desejada, e veja se a senha esta sendo corretamente inserida no banco de dados do usuário novo, para não haver erros.

Resultado final no Lovable: https://financcis.lovable.app

<img width="1816" height="846" alt="image" src="https://github.com/user-attachments/assets/7cf4f15a-b83d-4f38-921a-42409f1c969d" />
<img width="1822" height="791" alt="image" src="https://github.com/user-attachments/assets/6907b68d-a6e5-4a24-8dda-de6d10baef26" />
<img width="1824" height="859" alt="image" src="https://github.com/user-attachments/assets/bbf7f030-9a36-49af-a7f3-70a2add9d344" />
<img width="1834" height="848" alt="image" src="https://github.com/user-attachments/assets/c648630c-1afb-4716-a5e2-38fa46f9a1d6" />

# 💰 Resumo do App de Finanças Pessoais

### O aplicativo é um assistente financeiro inteligente baseado em chat, que permite ao usuário controlar suas finanças apenas conversando, como se estivesse mandando mensagens no WhatsApp.

### A IA interpreta frases como “gastei 50 reais em pizza”, identifica automaticamente o valor, categoria e tipo (gasto ou receita), e registra tudo sem esforço manual.

### Além do registro automático, o app oferece:

📊 Dashboard visual com saldo, gráficos de gastos e metas
💬 Chat inteligente como principal forma de interação
💵 Controle multimoeda (Real e Dólar) com conversão automática
🎯 Gestão de metas financeiras com acompanhamento visual
🤖 Sugestões de economia personalizadas com base nos hábitos do usuário

O diferencial está em ir além do controle:
o app educa financeiramente o usuário, oferecendo insights, alertas e recomendações para melhorar seus hábitos de consumo.



## Reflexão

### O que funcionou bem?
O uso do Gemini e do Chatgpb para refinar o PRD foi de grande ajuda para chegar em app funcional, usando poucos prompts sucessores.

### O que não funcionou como o esperado?  
Não funcionou de primeira com esperado, teve uns pequenos erros ao fazer login, ainda preciso refinar melhor o app no Lovable pois acabou os free credits.

### O que aprendeu sobre conversar com IAs?
É algo surreal de quanto elas podem ser úteis no dia dia, e aplicações em varias áreas de estudo/trabalho.
