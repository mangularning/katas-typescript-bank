# Katas TypeScript (Bank Domain)

**EN (short):** Focused TypeScript drills using a banking domain to master types, modeling, and business rules (framework-free, no `any` by default).

Exercícios curtos e objetivos para consolidar **TypeScript** com exemplos de domínio bancário — sem framework, focado em modelagem e regras.

## Objetivo
Dominar TypeScript para suportar Angular com segurança:
- tipos, unions e narrowing
- interfaces/types (contratos)
- arrays e objetos (transformações)
- classes (encapsulamento de regras)
- generics (nível necessário)
- funções puras (fáceis de testar)

## Organização
- `01-basics/` — tipos, unions, functions
- `02-objects-arrays/` — modelagem e transforms (map/filter/reduce)
- `03-classes/` — regras de negócio e encapsulamento
- `04-async/` — promises/contratos (preparação para HTTP)
- `05-mini-challenges/` — desafios integradores

## Regras do jogo
- Evitar `any` (se usar, justificar)
- Tipar input/output de toda função
- Preferir funções puras quando possível
- Priorizar legibilidade e nomes claros

## Como rodar (setup simples)
```bash
npm init -y
npm i -D typescript ts-node @types/node
npx tsc --init
npx ts-node ./01-basics/seu-exercicio.ts
