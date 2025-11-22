# 🤖 Projeto: Agentes Conversacionais para Carreira em Tecnologia

Este projeto foi desenvolvido como um desafio prático inspirado no conceito de Vibe Coding, utilizando prompts avançados e integração com IA conversacional. A proposta é criar **dois agentes inteligentes** que trabalham juntos para ajudar pessoas a descobrirem e planejarem sua carreira em tecnologia.

# 📝 PRD Refinado

```txt
# 🤖 PRD – Sistema de Agentes para Carreira Tech

## 1. Contexto
O sistema é composto por **dois agentes conversacionais**:
- **Agente Primeiro – TechPathFinder**: atua como entrevistador para entender o perfil do usuário.
- **Agente Segundo – TechRoadmapPlanner**: cria um plano de estudos personalizado com base nas informações coletadas.

O objetivo é oferecer uma experiência **humanizada e estruturada**, ajudando iniciantes ou profissionais em transição a escolherem a melhor carreira e seguirem um roadmap claro.

## 2. Problema
- Falta de orientação clara para quem deseja entrar na área de tecnologia.
- Dificuldade em conectar interesses pessoais com carreiras específicas.
- Ausência de planos práticos adaptados à disponibilidade e experiência do usuário.

Este projeto resolve isso com **entrevista guiada**, **análise personalizada** e **roadmap prático**.

## 3. Público-Alvo
- Pessoas que querem iniciar na tecnologia.
- Profissionais em transição de carreira.
- Quem busca crescimento na área tech.

Faixa etária principal: **18–45 anos**.

## 4. Funcionalidades-Chave (MVP)
1. **Entrevista estruturada (Agente 1)**
   - 7 perguntas para entender perfil, interesses e objetivos.
2. **Sugestão de carreiras ranqueadas (Agente 1)**
   - Baseada em afinidade, demanda e experiência.
3. **Plano de estudos completo (Agente 2)**
   - Visão do dia a dia, mapa de skills, roadmap de 90 dias, projeto de portfólio, roteiro de entrevistas e trilha DIO.
4. **Personalização dinâmica**
   - Ajuste conforme horas disponíveis, experiência e objetivo.

## 5. Fluxo entre Agentes
- **Agente 1** coleta dados → analisa perfil → sugere 3 carreiras → usuário escolhe.
- **Agente 2** recebe pacote de informações → gera plano detalhado.

## 6. Recursos Necessários
- IA conversacional (Copilot ou similar).
- Estrutura de prompts avançados.
- Integração com trilhas educacionais (ex.: DIO).

## 7. Validação Inicial
- Teste com usuários iniciantes.
- Métricas:
  - % de usuários que completam as 7 perguntas.
  - % que escolhem uma carreira.
  - Feedback sobre clareza e utilidade do roadmap.

## 8. Diferenciais
- **Experiência conversacional humanizada**.
- **Personalização real** baseada em perfil.
- **Entrega de roadmap prático e aplicável**.

## 9. Entregáveis
- Prompt completo do Agente 1 (TechPathFinder).
- Prompt completo do Agente 2 (TechRoadmapPlanner).
- Documentação do fluxo entre agentes.
- README detalhado do projeto.

## 10. Princípios do Design Universal aplicados
1. **Uso simples e intuitivo** – linguagem clara e acessível.
2. **Flexibilidade no uso** – adaptável a diferentes perfis.
3. **Informação perceptível** – respostas estruturadas e visuais.
4. **Baixo esforço** – interação rápida e objetiva.
```

# 💬 Interações entre Agentes

> Agente 1: entrevista e análise → sugere carreiras → envia dados para Agente 2.
> Agente 2: gera roadmap completo adaptado ao perfil.

# 📌 Resumo do Sistema

## 🎯 Objetivo
Facilitar a escolha e planejamento de carreira tech com:
- **Entrevista estruturada**.
- **Sugestão de carreiras ranqueadas**.
- **Plano de estudos personalizado**.

---

## 👥 Público-Alvo
- Iniciantes na tecnologia.
- Profissionais em transição.
- Quem busca crescimento na área tech.

---

## ⚙️ Funcionalidades Principais
- Entrevista guiada (7 perguntas).
- Sugestão de 3 carreiras com análise.
- Roadmap de 90 dias adaptado.
- Projeto de portfólio.
- Roteiro de entrevistas.
- Trilha educacional recomendada.

---

## ✅ Diferenciais
- Experiência **conversacional e personalizada**.
- **Roadmap prático** com metas claras.
- **Integração com trilhas educacionais**.

---

## 📌 Em resumo
O sistema é um **mentor digital para carreiras tech**, que transforma a escolha e planejamento em uma experiência clara, prática e motivadora.

# 🧠 Reflexões

### O que funcionou bem?
A estrutura de prompts detalhados garante clareza e personalização.

### O que não funcionou como esperado?
Necessidade de ajustes para diferentes níveis de experiência.

### O que aprendi sobre conversar com IAs?
Quanto mais detalhado e claro o prompt, melhor a qualidade da resposta.
