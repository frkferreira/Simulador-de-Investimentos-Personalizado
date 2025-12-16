# 📊 Planilha de Simulação de Planejamento e Estratégia de Investimentos baseada em tipos de Fundos de Investimento

Este repositório contém um simulador, focado em **projeção de cenários de longo prazo** e **estratégia de alocação de ativos** baseada em perfil de risco.

## 🎯 Objetivo da Planilha
Diferente de uma simples tabela de fluxo, esta versão funciona como um painel de inteligência financeira onde você define sua capacidade de aporte e o simulador projeta sua liberdade financeira e sugere onde investir.

## 🛠️ Funcionalidades do Simulador (V2)

A aba **SIMULADOR DE INVESTIMENTO** é dividida em três núcleos principais:

### 1. Configurações de Entrada (Inputs)
Campos para definir a base do planejamento:
- **Salário:** Base de renda do investidor.
- **Rendimento da Carteira:** Taxa de retorno mensal esperada.
- **Sugestão de Investimento:** Valor total disponível para novos aportes.

### 2. Projeção de Cenários (Liberdade Financeira)
Baseado nas configurações estipuladas pelo investidor, o simulador calcula automaticamente o **Patrimônio Acumulado** e os **Dividendos Mensais** estimados para diferentes horizontes de tempo:
- **Curto Prazo:** 02 anos.
- **Médio Prazo:** 05 e 10 anos.
- **Longo Prazo:** 20 e 30 anos.

### 3. Estratégia de Alocação (Portfólio Sugerido)
Com base no seu **Perfil de Investidor** (ex: Moderado) e no valor disponível para aporte, a planilha sugere uma distribuição de capital por tipo de ativo:
- **PAPEL:** Dívidas imobiliárias (CRIs).
- **TIJOLO:** Imóveis físicos (Shoppings, Galpões).
- **HÍBRIDOS / FOF's:** Diversificação em outros fundos.
- **DESENVOLVIMENTO / HOTELARIA:** Ativos de maior risco/retorno.

---

## 🧮 Inteligência por Trás do Dashboard

- **Cálculo de Projeção:** Utiliza a fórmula de valor futuro para determinar o crescimento do capital com juros compostos ao longo das décadas.
- **Matriz de Alocação:** Cruza o perfil de investidor cadastrado na aba `SUPORTE` com o valor do aporte mensal para gerar os valores exatos (em R$) de quanto comprar de cada tipo de ativo.
- **Estimativa de Dividendos:** Projeta a renda passiva mensal que o patrimônio acumulado geraria, baseando-se na taxa de rendimento configurada.

---

## 🚀 Como Utilizar

1. **Defina seu Perfil:** Ao escolher qual perfil de investidor você se encaixa, o simulador lhe mostrará as porcentagens de alocação relacionada a esse perfil.
2. **Preencha os Dados na Aba Principal:** Insira seu salário e o valor que deseja investir mensalmente.
3. **Analise os Cenários:** Veja em quanto tempo você atingirá sua meta de dividendos mensais.
4. **Sugestão de Compra:** Utilize a tabela de **TIPO DE FII** para ter uma noção de como dividir seu aporte do mês entre as categorias de fundos imobiliários.

---
*Este simulador é uma ferramenta de apoio tático para investidores que buscam uma carteira equilibrada e focada em renda passiva.*
