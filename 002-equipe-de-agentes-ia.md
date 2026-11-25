# Como começar uma pequena equipe de agentes de IA

**Status:** guia de experimento. Os passos descrevem uma forma de organizar a tarefa, não uma garantia de resultado.
**Versão:** 001 · **Data:** 24/11/2026

## Para quem serve

- **Pessoa autônoma:** separar tarefas repetitivas, como rascunhar propostas ou lembrar prazos.
- **Pequena empresa:** responder perguntas frequentes, organizar pedidos ou acompanhar fornecedores.

## O que você precisa

- Uma ferramenta de IA com conversa (chat). Verifique se é gratuita ou paga e quais são os limites de uso.
- Um lugar para guardar o resultado: uma planilha ou um documento.
- Tempo para conferir o que a IA entrega. Ela pode errar.

**Limitações:** sem automação, cada agente é uma conversa separada que você abre quando precisa. Não há garantia de que a IA acerte sempre.

## Passo a passo

1. **Escolha uma tarefa repetitiva.** Algo que você faz toda semana e que segue um padrão.
2. **Dê uma função só para o agente.** Ele faz uma coisa. Se a tarefa tem três etapas, comece com a primeira.
3. **Escreva o que ele não pode fazer.** Por exemplo: não enviar nada sozinho, não inventar preços, não prometer prazos.
4. **Defina o formato da entrega.** Lista, tabela ou texto curto. Quanto mais claro, mais fácil de conferir.
5. **Defina quem confere.** Sempre alguém decide o que segue adiante.
6. **Guarde o resultado.** Anote a data, o pedido e a resposta, para comparar depois.
7. **Só depois, pense no segundo agente.** Com um agente funcionando, você sabe o que esperar de outro.

## Prompt copiável

```text
Você é um agente de apoio para [sua atividade].

Sua única função: [descreva a tarefa em uma frase].

Você NÃO deve: [liste o que ele não pode fazer, por exemplo: enviar mensagens, inventar valores, prometer prazos].

Quando receber um pedido, responda neste formato:
[lista | tabela | texto curto]

Se faltar alguma informação, pergunte antes de responder.

Pedido: [cole aqui o pedido]
```

## Exemplo fictício

**Entrada (exemplo fictício):** uma autônoma de design, "Ana (exemplo)", pede um rascunho de proposta para um cliente que quer um logotipo. Prazo a combinar, valor a definir.

**Saída (exemplo fictício):**
- Rascunho de proposta com escopo, etapas e campos em aberto para preço e prazo.
- Lista do que precisa ser confirmado antes de enviar.

Ana revisa o texto e decide o valor. O agente não envia nada.

## Como testar se funcionou

- A resposta segue o formato pedido?
- Ela respeitou o que ficou proibido?
- Você consegue conferir cada parte sem refazer tudo?

Se não funcionar, ajuste a função e o que ele não pode fazer. Mude uma coisa por vez.

## Cuidados com dados sensíveis

- Não cole CPF, dados bancários, senhas ou dados de clientes no prompt.
- Use nomes fictícios ou genéricos nos testes.

## Adaptações

- **Loja pequena:** um agente para perguntas frequentes e outro para resumir pedidos da semana.
- **Escritório:** um agente para organizar atas e outro para lembrar retornos pendentes.
- **Uso pessoal:** um agente para planejar compras de mercado com base em uma lista sua.

## Limitações e alternativas

- Se a ferramenta não tiver automação, abra uma conversa nova para cada agente e cole o prompt salvo.
- Se você preferir algo mais simples, comece só com um agente e um formato de entrega.
- Verifique os termos de uso da ferramenta antes de colar informações de clientes.
