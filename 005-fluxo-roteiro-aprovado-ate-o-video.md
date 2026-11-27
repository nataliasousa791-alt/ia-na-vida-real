# Como organizar um fluxo de roteiro aprovado até o vídeo

**Status:** guia de experimento. Descreve uma forma de organizar o trabalho, não uma garantia de resultado.
**Versão:** 001 · **Data:** 25/11/2026

## Para quem serve

- **Criador de conteúdo:** separar o que precisa de revisão humana do que pode ser repetido.
- **Pequeno negócio:** padronizar vídeos curtos de divulgação, com a mesma estrutura.

## O que você precisa

- Uma ferramenta de IA para texto, que organize o roteiro em partes.
- Uma ferramenta de geração ou edição de vídeo. Verifique se é gratuita e quais são os limites.
- Uma planilha ou pasta para guardar as filas: "rascunho", "aprovado", "publicado".

**Limitações:** a IA pode mudar o sentido de uma frase ao dividir o texto. A revisão humana é obrigatória antes de gerar qualquer vídeo.

## Passo a passo

1. **Escreva o roteiro** em um documento, com começo, meio e fim.
2. **Revise você mesmo.** Confira fatos, tom e promessas. Só avance o que você aprovou.
3. **Mova o roteiro para a fila "aprovado"** na sua planilha.
4. **Peça para a IA dividir em cenas de tempo fixo**, usando o prompt abaixo.
5. **Gere ou monte o vídeo** com a ferramenta escolhida, cena por cena.
6. **Confira o vídeo final** antes de publicar: texto na tela, áudio e tempo de cada cena.
7. **Registre o resultado** na planilha, com data e link do vídeo.

## Prompt copiável

```text
Você vai dividir um roteiro aprovado em cenas para um vídeo curto.

Regras:
- Use somente o texto que eu enviar. Não acrescente fatos, promessas ou chamadas de venda.
- Divida em [número] cenas de aproximadamente [segundos] segundos cada.
- Para cada cena, responda neste formato:
  Cena [n] | [texto da locução] | [sugestão visual simples]
- No fim, liste qualquer trecho que você achou ambíguo, sem reescrevê-lo.

Roteiro aprovado:
[cole aqui o roteiro]
```

## Exemplo fictício

**Entrada (exemplo fictício):** um roteiro de 30 segundos sobre como organizar a lista de compras da semana.

**Saída (exemplo fictício):**

| Cena | Locução | Sugestão visual |
|---|---|---|
| 1 | Sua lista de compras começa na cabeça. | Pessoa olhando a geladeira |
| 2 | Anote o que acabou nos últimos dias. | Caderno com lista |
| 3 | Some o que você já tem em casa. | Itens da despensa |

**Trecho ambíguo:** "começa na cabeça" pode soar figurado. Confirme se é o tom que você quer.

## Como testar se funcionou

- Todas as cenas têm o tempo pedido?
- A locução de cada cena bate com o roteiro aprovado?
- O vídeo final tem alguma frase que você não escreveu?

Se algo não bater, volte à planilha e corrija o roteiro antes de gerar outro vídeo.

## Cuidados

- Não use dados pessoais de clientes ou de terceiros no roteiro.
- Não cite marcas ou projetos sem autorização.
- Confira os direitos de uso de música, imagens e vozes antes de publicar.

## Adaptações

- **Loja:** um roteiro por produto, sempre com a mesma estrutura.
- **Curso ou aula:** uma cena por tópico, para revisar com o aluno.

## Limitações e alternativas

- Se a ferramenta de vídeo não estiver disponível, use a mesma divisão em cenas para gravar você mesmo, com o celular.
- Sem fila automática, mantenha a planilha e gere um vídeo por vez.
