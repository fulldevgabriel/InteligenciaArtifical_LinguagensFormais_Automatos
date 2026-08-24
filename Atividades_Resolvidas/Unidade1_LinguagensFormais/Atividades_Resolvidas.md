# Atividades Práticas — Aula 1

Respostas da seção "12. Atividades Práticas" de Notas_de_Aula.md.

## Atividade 1 — Prefixos e Sufixos

Palavra: ab

1. Prefixos: {ε, a, ab}
2. Sufixos: {ε, b, ab}

## Atividade 2 — Gramática

G = ({S}, {a}, {S → aS | ε}, S)

Três palavras geradas:

1. ε

   S ⇒ ε

2. a

   S ⇒ aS ⇒ a

3. aa

   S ⇒ aS ⇒ aaS ⇒ aa

Linguagem gerada: L(G) = { aⁿ | n ≥ 0 }
