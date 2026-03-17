# Missão da Semana: Engenharia de Prompt (Hands-On Lab)
**Disciplina:** Laboratório / Prática
**Professora:** Kadidja Valéria

## 1. O Problema Escolhido
Desenvolver a lógica principal em JavaScript para uma ferramenta pessoal de precificação de eletrônicos usados, calculando automaticamente o valor ideal de anúncio para garantir a margem de lucro após descontar as taxas da plataforma de revenda.

## 2. Primeira Iteração (Instrução Vaga)
**Prompt Vago:** "Faz um código em javascript para calcular o lucro de um produto que vou revender."

**Resultado Ruim:** A IA gerou um código genérico (Lucro = Venda - Custo), ignorando o desconto das taxas da plataforma e não entregando a formatação monetária (R$) exigida.

## 3. Aplicação da Equação do Prompt de Alto Desempenho

### [Persona + Contexto]
> **Aja como:** Um Desenvolvedor Front-end Sênior especialista em JavaScript puro e lógica de negócios.
> **Contexto:** Estou criando uma ferramenta pessoal em HTML/JS para me ajudar a gerenciar a revenda de eletrônicos usados. Preciso automatizar o cálculo de precificação.

### [Tarefa Específica]
> **A Tarefa:** Crie a função matemática principal, chamada `calcularPrecoAnuncio(custo, taxaPlataforma, lucroDesejado)`, que calcule por qual valor devo anunciar um produto na plataforma para garantir minha margem de lucro exata, descontando as taxas do site.

### [Restrições + Formato]
> **Restrições:**
> 1. Escreva estritamente em Vanilla JavaScript.
> 2. Parâmetros de taxa e lucro devem ser em porcentagem.
> 3. Inclua validação de dados para evitar valores negativos.
> 4. O retorno deve ser o valor final formatado como moeda brasileira (ex: "R$ 1.500,00").
> 5. Adicione comentários curtos explicando a fórmula matemática.
> 
> **Formato:** Quero APENAS o bloco de código JavaScript com a função e duas linhas de `console.log` demonstrando o uso.

## 4. Output Executável
O resultado final gerado por este Prompt Mestre está salvo no arquivo `calculadora.js` deste repositório.
