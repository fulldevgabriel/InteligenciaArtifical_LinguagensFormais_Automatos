# Exercícios Práticos para Fixação — Aula 3 (17/08)

Respostas de Exercicio_GramaticasFormais_Aula3.png.

## Bloco 1 — Derivação

G₁: S → aS | b

1. Gere a palavra aaab.

   S ⇒ aS ⇒ aaS ⇒ aaaS ⇒ aaab

2. Explique como você sabe que a derivação terminou.

   Porque não sobrou nenhum não terminal na cadeia. Em aaab só restam
   terminais (a e b), então não há mais nenhuma regra a aplicar. Foi a
   produção S → b que encerrou, por ser a única que consome o S sem colocar
   outro no lugar.

## Bloco 2 — GLC

G₂: S → aSb | ε

1. Gere a palavra aaabbb.

   S ⇒ aSb ⇒ aaSbb ⇒ aaaSbbb ⇒ aaabbb

2. É possível gerar aabbb? Justifique.

   Não. A produção S → aSb coloca um a e um b sempre em par, e não existe
   regra que produza um b sozinho. Logo toda palavra gerada tem a mesma
   quantidade de a e de b. Como aabbb tem 2 a e 3 b, aabbb ∉ L(G₂).

   L(G₂) = { aⁿbⁿ | n ≥ 0 }

## Bloco 3 — Classificação

S → aA

A → b

Resposta: Regular (Tipo 3).

Nas duas produções o lado esquerdo tem um único não terminal, e o lado direito
é terminal seguido de não terminal (aA) ou apenas um terminal (b) — formato de
gramática regular à direita.

Toda gramática regular também é livre de contexto (Tipo 3 ⊂ Tipo 2), mas a
classificação correta é a mais restrita: Regular.
