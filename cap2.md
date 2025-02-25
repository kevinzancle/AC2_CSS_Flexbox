# 2\. Conceitos Fundamentais

## 2.1 O Modelo de Caixa Flexível

Tem a função de organizar elementos em uma página quando o seu tamanho final é desconhecido ou quando possui um conteúdo dinâmico. 

![Descrição da imagem](https://css-tricks.com/wp-content/uploads/2018/10/01-container.svg)

## 2.2 Elemento Pai (Flex Container) vs. Elementos Filhos (Flex Items)

O flexbox possui o conceito de hierarquia entre pai e filho. Atributos aplicados ao container pai afetam apenas seus filhos.

## 2.3 Propriedade \`display: flex\` e seus efeitos

A propriedade display flex torna os filhos do container flexíveis e suscetíveis a atributos do flexbox.  

### EXEMPLO:

#### HTML
```
<div class = "pai">
  <div class = "filho1"></div>
  <div class = "filho2"></div>
  <div class = "filho3"></div>
</div>

```

#### CSS
```
.pai{
  display: flex;
  flex-direction: collumn;
}

```

# Exercícios Do Capítulo

## 1. Questão Dissertativa  
Explique como funciona o conceito de pai e filho no CSS Flexbox.

## 2. Questão de Múltipla Escolha  
O que acontece quando aplicamos `display: flex` a um elemento?  

a) Ele se torna um Flex Item automaticamente  
b) Seus elementos filhos passam a ser organizados segundo as regras do Flexbox  
c) Ele perde a capacidade de conter outros elementos  
d) Ele impede que os elementos filhos tenham tamanhos flexíveis  

## 3. Questão de Verdadeiro ou Falso  
Quando aplicamos `display: flex` a um elemento, todas as suas regras CSS anteriores são removidas. **(V ou F?)**

## 4. Atividade Prática  
Copie o exemplo do capítulo e teste o flex direction row e collumn.
