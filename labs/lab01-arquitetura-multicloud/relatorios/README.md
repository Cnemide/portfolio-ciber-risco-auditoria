# Relatórios Técnicos

---

## report01-matriz-de-risco.md

## MATRIZ DE RISCO

Risco (ISO 31000, ISO 27005) = Probabilidade × Impacto

---

## R1 — Lock-in contratual

## Probabilidade = Alta
- Contratos governamentais tendem a ser plurianuais.
- Serviços gerenciados criam dependência técnica.
- APIs proprietárias dificultam migração.

## Impacto = Alto

Se:
- Migração pode custar milhões.
- Interrupção de serviços críticos.
- Dependência política/contratual.

## Criticidade = (Alto)^2
Alta × Alto = Crítico


Impacto \ Prob	Baixa	Média	Alta
Baixo	          Baixo	Baixo	Médio
Médio	          Baixo	Médio	Alto
Alto	          Médio	Alto	Crítico

## R2 — Falha de comunicação entre clouds

Média probabilidade
- Integrações multi-cloud exigem redes privadas, VPNs, latência controlada.
- Erros de configuração são comuns.
- Porém, não são inevitáveis.

Impacto Alto: falhas de comunicação podem:
- Derrubar sistema inteiro.
- Gerar inconsistência de dados.

## R4 — Aumento imprevisível de custos

Alta probabilidade

## Modelo OPEX (cloud pública): sem controle, os custos escalam silenciosamente
- Cobrança por consumo
- Tráfego
- Armazenamento
- Processamento
