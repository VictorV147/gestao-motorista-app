# Sistema de Gestão para Motorista de Aplicativo

## Visão geral

Inicialmente a spluçao procurar desenovlver um sistema de gestão para motorista de aplicativos, denvolvido para uso inicial do meu proprio pai.

## Escopo

- **Usuários:** um unico motorista teste (meu pai)
- **Plataforma:** aplicação web

## Requisitos Funcionais

| ID   | Descrição               | Prioridade |
| ---- | ----------------------- | ---------- |
| RF01 | Registrar abastecimento | Alta       |
| RF02 | Registrar KMs rodados no dia | Alta  |
| RF03 | Registrar quantidade de corridas realizadas no dia | Alta |
| RF04 | Registrar valor ganho no dia por plataforma | Alta |
| RF05 | Registrar dia e horário trabalhado | Alta |
| RF06 | Registrar custos fixos (IPVA, Seguro, Licenciamento) | Média |
| RF07 | Registrar manutenção | Média |
| RF08 | 

## Regras de Negócio

| ID   | Descrição                                                     |
| ---- | ------------------------------------------------------------- |
| RN01 | O KM/L é calculado entre dois abastecimentos com tanque cheio |
| RN02 | O lucro é calculado separado entre o bruto (valor gasto com KM/L - o valor recebido das corridas) e o lucro liquido (o bruto - o valor gasto com custos fixos) |
| RN03 | 

## Requisitos Não Funcionais

| ID    | Descrição                             |
| ----- | ------------------------------------- |
| RNF01 | O sistema deve ser acessível pela web |
| RNF02 | O sistema deve gerar BIs com metricas atualizadas todo dia |

## Métricas principais

1. Média de Lucro por dia
2. Média de valor ganho por dia
3. Gasto médio de combustive por dia 
4. Média de valor ganho por km rodado
5. Média de KM rodado no dia 

## Dúvidas em aberto

- Diluir manutenção por tempo ou por km?
- 
