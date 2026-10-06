# Requisitos específicos — AGROPAR

Este documento reúne as necessidades particulares levantadas junto à empresa parceira, além do escopo base do MVP de Saúde e Bem-Estar do Funcionário.

## 🎨 Identidade visual

| Campo | Informação |
|---|---|
| **Logotipo** | <img width="938" height="938" alt="WhatsApp Image 2026-10-02 at 13 59 07" src="https://github.com/user-attachments/assets/d170d029-5b96-4643-b44f-ff227ae96531" /> |
| **Cor primária** | `#019245` (verde) |
| **Cor secundária** | `#FFD535` (amarelo) |
| **Tipografia** | {{FONTE}} |
| **Outras referências** | [Papel timbrado da empresa (Google Docs)](https://docs.google.com/document/d/1mI1wySMA3zaLvqOJ8bZgBs6rM0mXx4gUwaOtHB_m3NM/edit?usp=sharing) |

## 🌐 Site / domínio

| Campo | Informação |
|---|---|
| **Site institucional da empresa** | https://www.agropar.com.br/ |

## 📝 Observações adicionais

- As cores acima foram extraídas do logotipo e devem ser confirmadas com a empresa.
- O documento-base enviado pela empresa descreve um **Módulo de Pessoas, Bem-Estar e Riscos Psicossociais** mais amplo, organizado em quatro blocos: riscos psicossociais do trabalho, bem-estar percebido, engajamento e pessoa-trabalho, e desempenho. O bloco de desempenho poderá ser desenvolvido ou integrado em fase posterior.
- **Princípios de produto da empresa:** sinalizar, não diagnosticar; não culpar automaticamente a pessoa; não usar dados de bem-estar como nota de desempenho; valorizar tendência e contexto em vez de respostas isoladas; garantir confiança por meio da confidencialidade.
- Humor, sono e estresse podem revelar informações sensíveis sobre saúde. O desenho da solução deve considerar a **LGPD** (finalidade, necessidade, confidencialidade, segurança, retenção e níveis de acesso).
- A solução apoia a identificação de fatores de risco psicossociais (NR-1 / GRO / PGR), mas **não substitui** o processo completo de gerenciamento de riscos ocupacionais.
- Pontos que a empresa ainda precisa definir: perguntas de cada dimensão, escalas de resposta, frequência, pesos e fórmulas, faixas de alerta, regras de anonimização, tamanho mínimo de grupo para exibição agregada, perfis de acesso e estrutura do dashboard.

## 🧩 Funcionalidades específicas

### Requisito 1 — Check-in curto e frequente de bem-estar

**Descrição:** Aplicar check-ins rápidos, com escalas simples e linguagem adequada ao público, cobrindo humor, qualidade do sono, estresse percebido, energia e fadiga, e sensação de recuperação. A frequência pode ser diária. As perguntas das avaliações mais amplas (riscos psicossociais, engajamento, pessoa-função e pertencimento) poderão ser diluídas ao longo do mês junto com o check-in.

**Prioridade:** ALTA

**Status:** PENDENTE

### Requisito 2 — Indicadores por dimensão

**Descrição:** Calcular os indicadores separadamente por dimensão (por exemplo, Índice de Bem-Estar Percebido), sem misturar automaticamente saúde, engajamento e desempenho. Uma nota global, se existir, nunca deve esconder as dimensões que a compõem. Siglas, escalas, pesos e faixas de interpretação são propostas iniciais e serão validadas com a empresa.

**Prioridade:** ALTA

**Status:** PENDENTE

### Requisito 3 — Histórico e tendência temporal

**Descrição:** Exibir o histórico e a evolução dos indicadores ao longo do tempo. O dashboard deve privilegiar tendências, já que uma sequência de piora ao longo das semanas é mais relevante do que uma resposta isolada.

**Prioridade:** MÉDIA

**Status:** PENDENTE

### Requisito 4 — Análise agregada e confidencialidade

**Descrição:** Permitir análises agregadas por equipe, setor, função ou período, respeitando critérios de confidencialidade, com tamanho mínimo de grupo para exibição. Evitar a exposição desnecessária de respostas individuais a gestores.

**Prioridade:** ALTA

**Status:** PENDENTE

### Requisito 5 — Alertas de tendência ou risco

**Descrição:** Gerar alertas que indiquem necessidade de investigação a partir de tendências ou padrões, sem produzir diagnóstico clínico automático e sem atribuir causalidade.

**Prioridade:** MÉDIA

**Status:** PENDENTE

### Requisito 6 — Níveis de acesso, auditoria e transparência

**Descrição:** Prever diferentes níveis de acesso aos dados conforme função e sensibilidade da informação, manter trilha de auditoria e explicar ao colaborador, de forma clara, a finalidade, o uso e o acesso aos dados coletados.

**Prioridade:** ALTA

**Status:** PENDENTE

### Requisito 7 — Registro de ações de melhoria

**Descrição:** Permitir o registro de ações de melhoria com responsáveis, prazos e acompanhamento posterior, além de nova mensuração após as intervenções para verificar a evolução.

**Prioridade:** BAIXA

**Status:** PENDENTE
