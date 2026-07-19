# PROJECT HEALTH

> Navegacao: [README](README.md) • [PROJECT_INDEX](PROJECT_INDEX.md)

<a id="topo"></a>

Modelo de saúde do projeto com níveis operacionais.

## 1. Níveis de saúde

### Excelente

Condições típicas:

- documentação atualizada e consistente;
- backlog controlado e priorizado;
- respostas à comunidade em tempo adequado;
- releases previsíveis e bem executadas;
- métricas estáveis com tendência positiva.

### Bom

Condições típicas:

- documentação majoritariamente atualizada;
- backlog sob controle com pontos de atenção pontuais;
- respostas regulares da manutenção;
- releases ocorrendo com pequenas pendências;
- métricas estáveis sem degradação relevante.

### Atenção

Condições típicas:

- aumento de links quebrados ou seções desatualizadas;
- crescimento de issues sem triagem adequada;
- atrasos frequentes em respostas e releases;
- checklists de qualidade frequentemente incompletos;
- tendência negativa em métricas por mais de um ciclo.

### Crítico

Condições típicas:

- documentação desatualizada em áreas centrais;
- backlog sem governança e sem priorização;
- ausência prolongada de resposta da manutenção;
- releases interrompidas ou sem critérios mínimos;
- riscos de confiança e continuidade do projeto.

## 2. Quando um indicador muda de nível

Um indicador individual muda de nível quando:

- cruza limiar definido por 2 ciclos consecutivos; ou
- apresenta degradação brusca com impacto imediato na comunidade.

## 3. Regras de classificação geral

- Saúde geral Excelente: maioria dos indicadores em Excelente e nenhum em Crítico.
- Saúde geral Bom: maioria em Bom/Excelente, com poucos em Atenção.
- Saúde geral Atenção: dois ou mais indicadores chave em Atenção.
- Saúde geral Crítico: qualquer indicador estrutural em Crítico por ciclo completo.

## 4. Indicadores chave sugeridos para saúde geral

- cobertura da documentação;
- links quebrados;
- tempo médio para resposta;
- issues abertas sem triagem;
- cumprimento de checklist de release.

## 5. Plano de resposta por nível

- Excelente: manter cadência e melhorar incrementalmente.
- Bom: corrigir pontos de atenção antes de escalar.
- Atenção: acionar plano corretivo com responsáveis e prazos.
- Crítico: congelar expansão e priorizar recuperação estrutural.

---
[↑ Voltar ao topo](#topo)
