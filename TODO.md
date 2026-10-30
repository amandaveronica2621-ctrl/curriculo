# TODO.md — Roteiro de Execução Técnica (Passo a Passo)

Este guia foi elaborado para ser executado de forma **linear, sequencial e sem ambiguidades** por qualquer modelo de IA ou desenvolvedor.

> **Status do Projeto:** Concluído com Sucesso e Validado contra `SPEC.md` e `AGENTS.md`.  
> - **Arquivo Principal:** `index.html` (100% estático, autônomo e pronto para publicação via GitHub Pages).  
> - **Restrição Respeitada:** Nenhum botão ou link de currículo em PDF foi adicionado. Canal externo único e oficial: [LinkedIn](https://www.linkedin.com/in/amanda-basso-dp).

---

## Fase 1: Fundação do Arquivo `index.html` e Metadados

- [x] **Tarefa 1.1:** Inicializar o arquivo `index.html` com estrutura HTML5 semântica e `lang="pt-BR"`.
- [x] **Tarefa 1.2:** Configurar as meta tags no `<head>`:
  - `<meta charset="UTF-8">`
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
  - `<title>`: `Amanda Veronica Basso | Departamento Pessoal Estratégico & BPO de Folha`
  - Meta description com foco em: BPO de folha de pagamento remoto, auditoria de eventos e compliance trabalhista.
- [x] **Tarefa 1.3:** Importar tipografia executiva via Google Fonts (`Plus Jakarta Sans`).
- [x] **Tarefa 1.4:** Declarar o bloco `<style>` com as variáveis CSS pré-definidas no `SPEC.md`:
  - `--color-primary: #0d2238;` (Azul-marinho corporativo profundo)
  - `--color-primary-light: #16324f;`
  - `--color-accent: #c5a059;` (Dourado sutil de consultoria)
  - `--color-accent-hover: #b38f46;`
  - `--color-bg-light: #f8fafc;` (Off-white / cinza suave)
  - `--color-surface: #ffffff;` (Branco puro dos cards)
  - `--color-text: #1f2937;` (Cinza grafite para leitura)
  - `--color-text-muted: #4b5563;`
  - `--color-border: #e2e8f0;`
  - `--font-sans: 'Plus Jakarta Sans', system-ui, sans-serif;`

---

## Fase 2: Construção da Estrutura Semântica (HTML)

- [x] **Tarefa 2.1:** **Cabeçalho Fixo (`<header>`):**
  - Logotipo textual / Assinatura: `Amanda Veronica Basso` com subtítulo discreto `Departamento Pessoal Estratégico`.
  - Navegação desktop (`<nav>`): links de âncora para `#servicos`, `#metodologia`, `#sobre`, `#competencias`, `#contato`.
  - Botão de ação (CTA) no cabeçalho: botão destacado para o LinkedIn (`https://www.linkedin.com/in/amanda-basso-dp`) com target `_blank` e `rel="noopener noreferrer"`.
  - Botão hambúrguer acessível para dispositivos móveis (`<button class="mobile-menu-toggle" aria-label="Abrir menu de navegação">`).

- [x] **Tarefa 2.2:** **Seção Hero / Capa (`<section id="hero">`):**
  - Badge superior: `✦ BPO de Folha Remoto & Compliance`
  - Título Principal (H1): `Departamento Pessoal Estratégico com Rigor Contábil e Segurança Jurídica`
  - Parágrafo de Posicionamento com foco na gestão 100% remota para empresas de todo o país, unindo Ciências Contábeis na Universidade Atitus e Gestão de RH.
  - Grupo de Botões (CTAs):
    - Botão primário: `Solicitar Diagnóstico de Folha` (âncora `#contato`)
    - Botão secundário: `Conhecer Serviços` (âncora `#servicos`)
  - Faixa de confiança: Fechamento 100% Pontual, Conformidade com DCTFWeb & eSocial, Operação Remota.
  - Cartão Executivo de Autoridade com badge de Ciências Contábeis (Atitus), Gestão de RH e Totvs RM/Excel.

- [x] **Tarefa 2.3:** **Seção de Serviços Especializados (`<section id="servicos">`):**
  - Título da Seção: `Como Posso Blindar e Otimizar o Departamento Pessoal da Sua Empresa`
  - Grid de 4 Cards detalhados:
    1. **Processamento Remoto de Folha (BPO de DP):** Fechamento mensal completo, cálculo de pró-labore, adicionais, férias, rescisões e transmissão de encargos (eSocial, DCTFWeb, FGTS Digital).
    2. **Mapeamento de Inconsistências & Auditoria:** Varredura detalhada em rubricas e parâmetros tributários (INSS, FGTS, IRRF), corrigindo distorções antes de fiscalizações.
    3. **Enquadramento Sindical & Aplicação de CCTs:** Interpretação precisa de convenções e acordos coletivos, pisos salariais e benefícios mandatórios.
    4. **Criação de Processos & Compliance Trabalhista:** Estruturação de manuais de rotinas de admissão, controle de jornada e prevenção de passivos reclamatórios.

- [x] **Tarefa 2.4:** **Seção Metodologia de Trabalho Remoto (`<section id="metodologia">`):**
  - Título: `Como Funciona a Gestão Remota da Sua Folha`
  - 3 Etapas ilustradas:
    - **Etapa 1 — Diagnóstico & Parametrização:** Análise inicial dos processos atuais, checagem de CCTs e parametrização segura do sistema.
    - **Etapa 2 — Rotina Mensal & Transmissão Segura:** Apuração tempestiva de variáveis, envio de relatórios prévios para aprovação da diretoria e transmissão das guias oficiais.
    - **Etapa 3 — Acompanhamento Consultivo Contínuo:** Suporte ágil e esclarecimento de dúvidas da gestão sobre legislação trabalhista e rotinas operacionais.

- [x] **Tarefa 2.5:** **Seção Sobre a Especialista (`<section id="sobre">`):**
  - Banner lateral com a dupla formação: Graduanda em **Ciências Contábeis** pela **Universidade Atitus** e formação em **Gestão de Recursos Humanos**.
  - Narrativa executiva destacando os 6 anos de experiência sólida e a responsabilidade por empresa de mais de 500 colaboradores.
  - Frase de posicionamento estratégico em destaque.

- [x] **Tarefa 2.6:** **Seção Competências & Tecnologias (`<section id="competencias">`):**
  - Grid de 3 categorias:
    - *Sistemas & Plataformas:* Totvs RM (Sênior), eSocial, DCTFWeb, FGTS Digital, Conectividade Social ICP, DIRF / EFD-Reinf.
    - *Análise de Dados & Cálculos:* Excel Avançado, fórmulas matriciais, tabelas dinâmicas, conciliação de encargos e modelagens.
    - *Legislação & Compliance:* CLT, Convenções Coletivas (CCT), Legislação Previdenciária, Retenção de IRRF e NRs.

- [x] **Tarefa 2.7:** **Seção de Contato e Conversão (`<section id="contato">`):**
  - Card central com convite para diagnóstico inicial sem compromisso.
  - Botão oficial de destaque direcionando para `https://www.linkedin.com/in/amanda-basso-dp`.
  - Botão de envio de e-mail funcional com assunto pré-definido.
  - *Restrição Respeitada:* Zero menções ou links de download de currículo.

- [x] **Tarefa 2.8:** **Rodapé (`<footer>`):**
  - Copyright: `© Amanda Veronica Basso. Todos os direitos reservados.`
  - Texto institucional com créditos à formação e especialidade.
  - Botão funcional de retorno suave ao topo (`Voltar ao topo`).

---

## Fase 3: Estilização Visual e Layout (CSS)

- [x] **Tarefa 3.1:** Implementar reset moderno (`box-sizing: border-box`, `margin: 0`, `padding: 0`).
- [x] **Tarefa 3.2:** Estilizar o cabeçalho fixo com `position: sticky; top: 0;`, `backdrop-filter: blur(12px);` e sombra dinâmica no scroll.
- [x] **Tarefa 3.3:** Estilizar botões com estados interativos nítidos (`:hover`, `:focus-visible`, elevação suave).
- [x] **Tarefa 3.4:** Aplicar layout responsivo através de CSS Grid e Flexbox com breakpoints bem definidos (desktop `>= 1024px`, tablet `768px - 1023px`, mobile `< 768px`).
- [x] **Tarefa 3.5:** Aplicar a paleta Corporativa & Clássica (azul-marinho profundo `#0d2238`, off-white `#f8fafc`, toques dourados `#c5a059` e cinza grafite `#1f2937`).

---

## Fase 4: Comportamento Interativo e Acessibilidade (JavaScript)

- [x] **Tarefa 4.1:** Implementar rolagem suave nativa com compensação da altura do cabeçalho fixo (`scroll-margin-top`).
- [x] **Tarefa 4.2:** Implementar script nativo para abertura/fechamento do menu mobile com atualização de `aria-expanded`.
- [x] **Tarefa 4.3:** Fechamento automático da gaveta mobile ao clicar em links de âncora ou ao pressionar a tecla `ESC`.
- [x] **Tarefa 4.4:** Scrollspy automático destacando no cabeçalho a seção em visualização.
- [x] **Tarefa 4.5:** Botão "Voltar ao topo" com rolagem fluida até `#hero`.

---

## Fase 5: Validação Final e Critérios de Conclusão

- [x] **Check 5.1:** O arquivo `index.html` funciona de forma 100% autônoma ao ser aberto no navegador e está pronto para o GitHub Pages.
- [x] **Check 5.2:** O nome está grafado corretamente como **Amanda Veronica Basso**.
- [x] **Check 5.3:** A formação consta com rigor como **Graduanda em Ciências Contábeis (Universidade Atitus)** e **Formação em Gestão de Recursos Humanos**.
- [x] **Check 5.4:** Os 6 anos de experiência e os 500+ funcionários estão em evidência nas métricas e na narrativa.
- [x] **Check 5.5:** Não existe nenhum botão ou link para download de currículo em PDF.
- [x] **Check 5.6:** O link do LinkedIn aponta com exatidão para `https://www.linkedin.com/in/amanda-basso-dp` e abre em nova aba (`target="_blank"`).
- [x] **Check 5.7:** A paleta reflete o estilo Corporativo & Clássico aprovado.
- [x] **Check 5.8:** A página é 100% responsiva para celulares, tablets e computadores.
