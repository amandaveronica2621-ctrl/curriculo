# AGENTS.md — Diretrizes para Agentes de IA

Este documento define as regras invioláveis, limites operacionais e padrões de desenvolvimento para qualquer modelo ou agente de IA atuando neste repositório.

O projeto é o **portfólio profissional e vitrine de serviços de Amanda Veronica Basso**, graduanda em **Ciências Contábeis** pela **Universidade Atitus**, com formação em **Gestão de Recursos Humanos**, especialista em **Departamento Pessoal Estratégico, Legislação Trabalhista e BPO de Folha de Pagamento Remoto**. O site é publicado de forma estática através do **GitHub Pages**.

---

## 1. Princípios Invioláveis

1. **Fonte Única da Verdade (`SPEC.md`):**
   - O arquivo [`SPEC.md`](file:///c:/Users/amanda.basso/Desktop/Projeto%20Open%20Code%20ADM/SPEC.md) governa todas as decisões de produto, arquitetura, conteúdo, seções e design.
   - Nenhuma decisão de código ou layout pode contradizer o `SPEC.md`. Havendo necessidade de alteração de escopo, atualize o `SPEC.md` antes de codificar.

2. **Spec-Driven Development (Especificação Antes do Código):**
   - Toda funcionalidade ou mudança estrutural deve primeiro ser documentada e validada no `SPEC.md`.
   - Não crie arquivos experimentais nem implementações fora do que foi acordado.

3. **Integridade Rigorosa de Informações Reais:**
   - **Proprietária:** Amanda Veronica Basso.
   - **Formação:** Graduação em Ciências Contábeis (Universidade Atitus) e formação em Gestão de Recursos Humanos.
   - **Experiência Comprovada:** 6 anos de atuação prática em Departamento Pessoal; atualmente responsável pela gestão de folha de empresa com mais de 500 funcionários.
   - **Principais Ferramental e Sistemas:** Totvs RM, Excel Avançado, eSocial, DCTFWeb, FGTS Digital e parametrização de CCTs.
   - **Serviços Oferecidos:** Gestão/Processamento Remoto de Folha de Pagamento (BPO), Mapeamento de Inconsistências & Auditoria de Eventos, Enquadramento Sindical e Compliance Trabalhista.
   - **Canal de Conexão Oficial:** Perfil no LinkedIn (`https://www.linkedin.com/in/amanda-basso-dp`) e Perfil GitHub (`https://github.com/amandaveronica2621-ctrl`).
   - **Restrição Expressa:** Não incluir botão ou link de download de currículo em PDF (por decisão da Amanda, a presença profissional é concentrada exclusivamente no LinkedIn).
   - **Proibição Absoluta:** Nunca invente nomes de clientes reais, números falsificados ou credenciais não autorizadas. Quando necessário exemplificar processos, use termos neutros de mercado (ex.: "PMEs do setor de serviços e comércio").

4. **Compatibilidade Nativa com GitHub Pages:**
   - O projeto deve ser puramente estático (HTML, CSS e JavaScript), sem dependências de servidores backend (Node.js, PHP, Python em runtime), sem bundlers que exijam compilação externa complexa e sem custos.
   - O site opera no arquivo raiz `index.html`.

5. **Identidade Visual Aprovada:**
   - Estilo: **Corporativo & Clássico (Executivo / Consultoria)**.
   - Paleta: Azul-marinho corporativo (`#0d2238` / `#16324f`), cinza ardósia/grafite, fundo limpo branco/off-white e acentos discretos em dourado ou azul real.
   - Sem temas infantis, layouts excessivamente chamativos ou fontes informais.

6. **Acessibilidade e Usabilidade:**
   - Semântica HTML rigorosa (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
   - Contraste visual seguro (WCAG AA mínimo).
   - Design 100% responsivo para celulares, tablets e computadores corporativos.

---

## 2. Fluxo de Trabalho do Agente

Ao receber qualquer nova demanda:

```
[Solicitação do Usuário] 
           ↓
[Verificar e Atualizar SPEC.md] 
           ↓
[Apresentar e Confirmar com a Amanda] 
           ↓
[Implementação Técnica no index.html]
           ↓
[Validação contra os Critérios de Aceite]
```

---

## 3. Checklist Obrigatório para Entregas

Antes de concluir qualquer tarefa técnica neste projeto:
- [ ] O [`SPEC.md`](file:///c:/Users/amanda.basso/Desktop/Projeto%20Open%20Code%20ADM/SPEC.md) está 100% alinhado com o código implementado?
- [ ] A formação (Ciências Contábeis na Atitus + Gestão de RH) está correta em todos os textos?
- [ ] O único canal profissional externo indicado é o LinkedIn (sem menção ou botão de download de currículo)?
- [ ] A linguagem está impecável em português, com termos corretos de Departamento Pessoal, Contabilidade e Legislação Trabalhista?
- [ ] Todos os links internos e âncoras da página funcionam perfeitamente?
- [ ] O layout abre sem quebras em dispositivos móveis e em navegadores desktop?
- [ ] Nenhuma linha de código requer infraestrutura de backend externo?
