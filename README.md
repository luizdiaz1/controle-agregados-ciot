# Controle de Agregados e CIOT

Sistema que estou desenvolvendo na DIME Distribuidora para organizar os serviços feitos por motoristas agregados (terceiros) e calcular a remuneração deles.

Este repositório tem a **versão de demonstração**. Empresa, pessoas, placas e valores são fictícios, e o banco de dados foi trocado por um banco simulado que roda no navegador. O sistema real não é público.

**Testar a demo:** https://portfolio-luizdias.vercel.app/agregados/ (aceita qualquer e-mail e senha)

## Por que fiz

Parte das entregas é feita por motoristas agregados, que recebem comissão e bonificação por desempenho. Os serviços, os CIOTs, as ocorrências e o cálculo do pagamento de cada um eram organizados e conferidos à mão.

## O que o sistema faz

- Cadastro de motoristas agregados e veículos
- Abertura e finalização de serviços, com notas na saída e no retorno, entregas, reclamações, devoluções e sinistros
- Cálculo da comissão e da bonificação a partir de regras de desempenho
- Calculadora de pagamento por quinzena, controle de CIOTs, relatórios por período e auditoria

## Situação

Em desenvolvimento. Estruturei as informações e as regras de cálculo e estou desenvolvendo o sistema. Na demo, as regras de remuneração já são aplicadas.

## Tecnologias

HTML, CSS e JavaScript (módulos ES) · Supabase

## Rodar localmente

É um site estático, sem etapa de build. Basta servir a pasta:

```bash
npx serve .
```

---

Outros projetos e contato: [portfolio-luizdias.vercel.app](https://portfolio-luizdias.vercel.app)
