# 💸 App de Finanças Pessoais **Finz**  
Desenvolvido por mim com Vibe Coding
Desafio da DIO

## 📑 PRD Refinado (Gemini + ChatGPT)

```markdown
PRD: Assistente Financeiro Conversacional

1. Visão Geral do Produto
- Gestão financeira simples como enviar uma mensagem.
- IA interpreta entradas do usuário (ex: "Gastei 50 reais em pizza").
- Categorização automática + insights em tempo real.
- Elimina barreiras de entrada manual complexa.

Melhorias:
- Aprendizado contínuo com feedback do usuário.
- Sugestões proativas baseadas em comportamento financeiro.
- UX simples, rápido e agradável.

2. Experiência do Usuário (UX) e Telas Principais
Identidade Visual:
- Verde esmeralda (#0F9D58), verde escuro (#0B6E4F), gradiente suave.
- Tipografia moderna (Inter / Poppins).
- Estilo clean, minimalista e elegante.

Principais Telas:
- Dashboard: saldo, gráfico de rosca, metas animadas.
- Chat: input NLP, feed estilo WhatsApp, confirmações de transação.
- Carteira Multimoeda: BRL/USD, gráficos comparativos, impacto cambial.
- Configurações: dark/light mode, exportação, segurança (2FA).

3. Funcionalidades
- Parsing de linguagem natural.
- Categorização automática.
- Gestão de metas.
- Agente de economia inteligente.
- Suporte multimoeda.
- Autenticação segura.

4. Requisitos Técnicos
Frontend: React.js, Tailwind CSS, Framer Motion, Lucide-react, Recharts  
Backend: Supabase (Auth + Database + Storage)  
IA: OpenAI API (ou similar)

5. Validação do MVP
- IA deve acertar ≥ 90% das classificações.
- Avaliar engajamento via chat vs botão.
- Clareza na separação BRL/USD.

6. Diferenciais Educativos
- Feedback amigável e não julgador.
- Gamificação leve.
- Insights semanais automáticos.

7. Prompt da IA
- Classificação estruturada em JSON.
- Regras: precisão > criatividade, nunca inventar valores, pedir confirmação se ambíguo.

8. Visão de Escala
- Integração com bancos (Open Finance).
- Notificações inteligentes.
- IA preditiva de gastos.
- Planejamento automático.
- Versão web + mobile (PWA).
```

---

## 🎬 Interações com o Lovable

> Crie um App de Finanças pessoais com base no seguinte PRD (Product Requirements Document) {PRD}  
> Notei que quando tento fazer o login não tenho êxito nisso, corrija isso por favor.  
> Mesmo colocando o login correto está dando erro.  
> Adicione novamente a função confirmar o endereço de email, e adicione no cadastro repetir senha desejada, e veja se a senha está sendo corretamente inserida no banco de dados do usuário novo, para não haver erros.  

🔗 Resultado final: [financcis.lovable.app](https://financcis.lovable.app)

### 📸 Prints
<img width="1816" height="846" alt="image" src="https://github.com/user-attachments/assets/7cf4f15a-b83d-4f38-921a-42409f1c969d" />
<img width="1822" height="791" alt="image" src="https://github.com/user-attachments/assets/6907b68d-a6e5-4a24-8dda-de6d10baef26" />
<img width="1824" height="859" alt="image" src="https://github.com/user-attachments/assets/bbf7f030-9a36-49af-a7f3-70a2add9d344" />
<img width="1834" height="848" alt="image" src="https://github.com/user-attachments/assets/c648630c-1afb-4716-a5e2-38fa46f9a1d6" />

---

## 💰 Resumo do App

O **Finz** é um assistente financeiro inteligente baseado em chat, que permite ao usuário controlar suas finanças apenas conversando, como se estivesse mandando mensagens no WhatsApp.

A IA interpreta frases como “gastei 50 reais em pizza”, identifica automaticamente o valor, categoria e tipo (gasto ou receita), e registra tudo sem esforço manual.

### Principais recursos:
- 📊 Dashboard visual com saldo, gráficos e metas  
- 💬 Chat inteligente como principal forma de interação  
- 💵 Controle multimoeda (BRL/USD) com conversão automática  
- 🎯 Gestão de metas financeiras com acompanhamento visual  
- 🤖 Sugestões de economia personalizadas com base nos hábitos  

O diferencial está em ir além do controle: o app educa financeiramente o usuário, oferecendo insights, alertas e recomendações para melhorar seus hábitos de consumo.

---

## 📝 Reflexão

### ✅ O que funcionou bem
- Uso do Gemini e ChatGPT para refinar o PRD.  
- Poucos prompts sucessores já resultaram em um app funcional.  

### ⚠️ O que não funcionou como esperado
- Problemas iniciais no login.  
- Limitação dos créditos gratuitos no Lovable.  

### 📚 O que aprendi sobre conversar com IAs
- É impressionante o quanto elas podem ser úteis no dia a dia.  
- Aplicações práticas em diversas áreas de estudo e trabalho.  
```
