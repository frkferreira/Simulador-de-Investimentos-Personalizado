# 📈 Simulador de Investimentos Personalizado

Este repositório contém uma planilha inteligente desenvolvida para simular a evolução de patrimônio através de juros compostos. O objetivo é fornecer uma visão clara de como aportes mensais e taxas de juros (anuais e mensais) impactam o saldo final ao longo do tempo.

## 🚀 Funcionalidades

- **Conversão Automática de Taxas:** Transforma a taxa anual (Efetiva) em taxa mensal usando a fórmula de juros compostos.
- **Simulação de Aportes:** Permite configurar aportes mensais recorrentes.
- **Cálculo Antecipado:** Os juros são calculados sobre o saldo inicial somado ao aporte do mês, refletindo um cenário de investimento no início do período.
- **Fluxo Mensal Detalhado:** Visão clara mês a mês de:
  - Principal (Saldo Inicial)
  - Aporte realizado
  - Juros gerados no período
  - Saldo final acumulado

## 🧮 Metodologia de Cálculo

Para garantir a precisão financeira, a planilha utiliza as seguintes fórmulas:

### 1. Equivalência de Taxa (Anual para Mensal)
A planilha não divide a taxa por 12 (juros simples), mas utiliza a fórmula de juros compostos:
$$i_{m} = (1 + i_{a})^{\frac{1}{12}} - 1$$

### 2. Evolução do Patrimônio
O cálculo do saldo final de cada mês segue a lógica:
$$\text{Saldo Final} = (\text{Saldo Inicial} + \text{Aporte}) \times (1 + \text{Taxa Mensal})$$

## 📋 Como usar a planilha

1. **Configuração Inicial:** Preencha a data de início e o valor que você já possui investido.
2. **Definição de Taxas:** Insira a taxa anual esperada (ex: 12%). A planilha calculará automaticamente a taxa mensal.
3. **Planejamento de Aportes:** Defina o valor que pretende investir todos os meses.
4. **Análise de Resultados:** Acompanhe a tabela de fluxo para visualizar em quanto tempo você atingirá seus objetivos financeiros.

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel / Google Sheets**
- **Fórmulas Financeiras Avançadas**
- **Markdown** (para documentação)

---
💡 *Dica: Use esta planilha para comparar diferentes cenários, como o impacto de aumentar seu aporte mensal em apenas R$ 100,00 no longo prazo!*
