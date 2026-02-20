# 01 — Matriz de Risco da Arquitetura Multicloud

## 1. Metodologia

Modelo qualitativo baseado em:
- Probabilidade (Baixa, Média, Alta)
- Impacto (Baixo, Médio, Alto)
- Classificação final por criticidade

---

## 2. Riscos Identificados

| ID | Risco | Probabilidade | Impacto | Criticidade | Mitigação |
|----|-------|---------------|----------|-------------|------------|
| R1 | Lock-in contratual | Alta | Alto | Crítico | Estratégia multicloud + containers |
| R2 | Falha de comunicação entre clouds | Média | Alto | Alto | Orquestração via Kubernetes |
| R3 | Exposição de dados sensíveis | Média | Alto | Alto | Criptografia + IAM federado |
| R4 | Aumento imprevisível de custos | Alta | Médio | Alto | Monitoramento financeiro contínuo |
| R5 | Complexidade operacional | Média | Médio | Moderado | Padronização DevOps |

---

## 3. Conclusão

A arquitetura multicloud reduz risco sistêmico, porém aumenta complexidade operacional, exigindo governança madura.
