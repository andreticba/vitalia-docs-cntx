<!-- GROUNDING_DOMAINS.md | Vitalia Kit v0.0.1 | 26-11-2026 17:03(GMT-04:00) -->
**GROUNDING_DOMAINS.md | Vitalia Kit v0.0.1 | 26-11-2026 17:03(GMT-04:00)**

# 🛡️ Domínios de Grounding (P03)

![Total](https://img.shields.io/badge/Domínios-12-blue?style=flat-square) ![Global](https://img.shields.io/badge/Global-4-green?style=flat-square) ![Overlays](https://img.shields.io/badge/Overlays-8-informational?style=flat-square) ![Local](https://img.shields.io/badge/Local%2FProjeto-0-yellowgreen?style=flat-square) ![Rejeitados](https://img.shields.io/badge/Rejeitados-0-lightgrey?style=flat-square)

[Voltar ao Painel da Sessão](./README.md)

## 🌍 Domínios Globais (`global`)

| ID | Nome | Trigger | Descrição |
| :--- | :--- | :---: | :--- |
| `security_practices` | Segurança de Aplicação & OWASP | `blocking` | Padrões OWASP API Security e OWASP Top 10 for LLM Applications 2025. |
| `software_architecture` | Engenharia de Software & Contratos | `warning` | Padrões OpenAPI 3.0, RFCs HTTP e proveniência W3C PROV-O. |
| `design_patterns` | Padrões de Projeto & Refatoração | `warning` | Catálogo de design patterns GoF e práticas de refatoração de código. |
| `general_web` | Web Geral & Pesquisas Abertas | `info` | Citações e referências web coletadas pelo researcher pendentes de promoção a domínio oficial. |

## 🧩 Overlays de Domínio (`domain_overlay`)

| ID | Nome | Gate | Princípios | Trigger | Descrição |
| :--- | :--- | :---: | :--- | :---: | :--- |
| `clinical_safety` | Segurança Clínica, Safety Gate e Transbordo HITL | `health` | `P00, P09, P14` | `blocking` | Detecção determinística de risco clínico e salvaguarda HITL tripla (P09/P14). |
| `regulations_compliance` | Regulações, Privacidade & EU AI Act | `health` | `P07, P09, P17` | `blocking` | LGPD (Lei 13.709/2018), HIPAA e EU AI Act (Art. 12 e 14). |
| `python_packages` | Ecossistema Python & Pacotes Core | `python` | `—` | `blocking` | Compatibilidade Python 3.11+ e pacotes oficiais via PyPI. |
| `provedores_de_ia` | Documentação Estruturada de Provedores de IA (/llms.txt) | `ai_providers` | `—` | `blocking` | Especificação llms.txt v2 e APIs oficiais de provedores de IA. |
| `web_frameworks` | Web Frameworks (Django & Next.js) | `web` | `—` | `blocking` | Documentação oficial de frameworks web Django e Next.js. |
| `javascript_ecosystem` | Ecossistema JavaScript, TypeScript & React | `javascript` | `—` | `blocking` | Documentação oficial React e TypeScript. |
| `devops_ci` | DevOps, CI/CD & Containers | `devops` | `—` | `blocking` | GitHub Actions e Docker Compose padrões oficiais. |
| `cloud_services` | Serviços em Nuvem & Infraestrutura | `cloud` | `—` | `blocking` | Google Cloud Platform e provedores cloud documentação oficial. |

<details>
<summary><strong>🔗 Fontes Autoritativas por Domínio</strong></summary>

- **`security_practices`** (global):
  - https://genai.owasp.org/llmrisk/llm082025-vector-and-embedding-weaknesses/ (normative_standard)
  - https://owasp.org/API-Security/ (normative_standard)
- **`software_architecture`** (global):
  - https://www.rfc-editor.org/rfc/rfc9110.txt (normative_standard)
  - https://www.w3.org/TR/prov-o/ (normative_standard)
- **`design_patterns`** (global):
  - https://refactoring.guru/design-patterns (community_reference)
- **`clinical_safety`** (domain_overlay):
  - https://www.who.int/publications (normative_standard)
- **`regulations_compliance`** (domain_overlay):
  - https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm (normative_standard)
- **`python_packages`** (domain_overlay):
  - https://pypi.org (official_vendor)
- **`provedores_de_ia`** (domain_overlay):
  - https://llmstxt.org/ (official_vendor)
  - https://aistudio.google.com/ (official_vendor)
  - https://platform.claude.com/ (official_vendor)
  - https://developers.openai.com/ (official_vendor)
- **`web_frameworks`** (domain_overlay):
  - https://docs.djangoproject.com/en/stable/ (official_vendor)
  - https://nextjs.org/docs (official_vendor)
- **`javascript_ecosystem`** (domain_overlay):
  - https://react.dev/ (official_vendor)
  - https://www.typescriptlang.org/docs/ (official_vendor)
- **`devops_ci`** (domain_overlay):
  - https://docs.github.com/en/actions (official_vendor)
  - https://docs.docker.com/compose/ (official_vendor)
- **`cloud_services`** (domain_overlay):
  - https://cloud.google.com/docs (official_vendor)

</details>

*Projeção gerada em 26-11-2026 17:03(GMT-04:00) — Vitalia Kit v0.0.1*
