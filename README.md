<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/capa-escura.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/capa-clara.svg">
  <img alt="Bruno César Angst — Desenvolvedor por ofício. Investigador por natureza." src="./assets/capa-clara.svg" width="100%">
</picture>

<p align="center">
  <a href="https://brunoangst.com.br/"><img alt="Site" src="https://img.shields.io/badge/brunoangst.com.br-C8653D?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://github.com/BrunoCesarAngst/digitalGarden"><img alt="Jardim digital" src="https://img.shields.io/badge/jardim_digital-191B1F?style=for-the-badge&logo=readme&logoColor=white"></a>
</p>

> Transformo regras de negócio, estados de interação e integrações difíceis em sistemas claros, verificáveis e preparados para evoluir.

## Projetos em destaque — evidências de engenharia

Cada projeto abaixo apresenta **problema, escopo, solução, stack e evidências verificáveis**. Eles são exemplos de trabalho técnico publicado, não alegações de uso comercial ou impacto sem métricas.

| Projeto | Problema abordado | Evidência para avaliar |
| --- | --- | --- |
| [Torq — camada de workspace e IA](https://github.com/BrunoCesarAngst/ia-torq) | Coordenar contratos, decisões e fronteiras entre sistemas | [Arquitetura publicada](https://github.com/BrunoCesarAngst/ia-torq/blob/main/ARCHITECTURE.md) e políticas operacionais; **código dos produtos internos não está neste repositório** |
| [Agenda Arroio do Sal](https://github.com/BrunoCesarAngst/agenda-arroio) | Diferenciar fluxos de agendamento, administração e backup | [Código, scripts de teste e backup](https://github.com/BrunoCesarAngst/agenda-arroio) |
| [App do Sal](https://github.com/BrunoCesarAngst/appadosal) | Integrar interface, API tipo-segura e persistência | [Monorepo, configuração e documentação](https://github.com/BrunoCesarAngst/appadosal) |
| [Demando](https://github.com/BrunoCesarAngst/demando) | Gerir demandas via web e API | [Aplicação Django e configuração da API](https://github.com/BrunoCesarAngst/demando) |
| [Torq Design System](https://github.com/BrunoCesarAngst/DS-Torq) | Reutilização de componentes e padrões de interface | [Biblioteca e documentação](https://github.com/BrunoCesarAngst/DS-Torq) |

**Critério de leitura:** configuração de testes não significa testes aprovados; documentação de arquitetura não comprova implantação; resultados mensuráveis serão incluídos somente quando houver evidência.

## Evidências de implementação

Os projetos abaixo têm uma seção de **evidências no código**, com links diretos para implementações e limites de validação:

- **[Torq — workspace e IA](https://github.com/BrunoCesarAngst/ia-torq#evidências-técnicas-publicadas-inspeção-de-outubro-de-2026):** fronteiras arquiteturais documentadas e testes de hook de manutenção de grafo.
- **[Agenda Arroio](https://github.com/BrunoCesarAngst/agenda-arroio#evidências-no-código-inspeção-de-outubro-de-2026):** autenticação Google e rotinas de exportação/backup no Firebase.
- **[App do Sal](https://github.com/BrunoCesarAngst/appadosal#evidências-no-código-inspeção-de-outubro-de-2026):** integração de autenticação e API tRPC pública/protegida.
- **[Demando](https://github.com/BrunoCesarAngst/demando#evidências-no-código-inspeção-de-outubro-de-2026):** domínio de demandas, paginação HTMX e fluxos de autenticação.
- **[Torq Design System](https://github.com/BrunoCesarAngst/DS-Torq#evidências-no-código-inspeção-de-outubro-de-2026):** árvore recursiva e renderização virtualizada.

**Transparência:** os READMEs também registram lacunas encontradas. Nenhuma métrica de impacto, cobertura de testes, autoria integral ou adoção em produção foi presumida. Documentação, implementação e validação operacional são níveis diferentes de evidência.

## Meu trabalho

Atuo na interseção entre **produto, domínio e engenharia de software**. Minha contribuição começa antes da implementação: investigo o problema, separo fatos de hipóteses, torno decisões explícitas e construo contratos que conectam interface, API, dados e operação.

Tenho maior impacto quando o software começa a resistir: regras extensas, estados difíceis de prever, compatibilidade legada, múltiplos repositórios, decisões arquiteturais dispersas ou automações que precisam operar com segurança.

Não procuro apenas fazer uma funcionalidade funcionar. Procuro compreender **por que funciona, onde pode falhar e como continuará evoluindo**.

## Áreas de investigação técnica

- projetando modelos de interação para editores visuais e estruturas recursivas;
- desenvolvendo automações seguras para revisão e manutenção de código;
- aprofundando governança técnica com contratos, ADRs e evidências verificáveis;
- experimentando a integração entre software, dispositivos compactos e processamento local;
- publicando notas sobre arquitetura, ferramentas e pensamento crítico aplicado à engenharia.

## Engenharia publicada

| Material | O que demonstra |
| --- | --- |
| [Editor visual de regras](https://github.com/BrunoCesarAngst/digitalGarden/blob/main/case-studies/editor-visual-de-regras.md) | Modelagem de domínio, AST, interação, contratos e evolução incremental |
| [Automação segura de revisão](https://github.com/BrunoCesarAngst/digitalGarden/blob/main/case-studies/automacao-segura-de-revisao.md) | Governança, Git, isolamento por worktree e segurança operacional |
| [Seleção não é foco](https://github.com/BrunoCesarAngst/digitalGarden/blob/main/notes/selecao-nao-e-foco.md) | Arquitetura front-end, máquinas de estado e acessibilidade |
| [Decisões que sobrevivem ao código](https://github.com/BrunoCesarAngst/digitalGarden/blob/main/notes/decisoes-arquiteturais.md) | ADRs, rastreabilidade e alinhamento entre contrato, implementação e teste |
| [Polyrepos e worktrees](https://github.com/BrunoCesarAngst/digitalGarden/blob/main/notes/polyrepos-e-worktrees.md) | Organização de ambientes complexos sem contaminar os produtos |

## Outros projetos e materiais públicos

| Projeto | Papel na minha trajetória |
| --- | --- |
| [brunoangst.com.br](https://github.com/BrunoCesarAngst/brunoangst.com.br) | Presença profissional, escrita e identidade digital |
| [digitalGarden](https://github.com/BrunoCesarAngst/digitalGarden) | Conhecimento técnico público e estudos de engenharia |
| [app-mysys](https://github.com/BrunoCesarAngst/app-mysys) | Modelagem de um sistema pessoal inspirado em GTD, ZTD e PARA |

## Ferramentas que uso

`Vue 3` · `TypeScript` · `Vite` · `Pinia` · `Vitest` · `Java 21` · `Quarkus` · `REST` · `PostgreSQL` · `Flyway` · `Redis` · `Docker` · `Linux` · `Git`

## Princípios

- **Compreender antes de construir.** Complexidade mal compreendida reaparece como retrabalho.
- **Tornar decisões verificáveis.** Documentação, contratos, código e testes precisam contar a mesma história.
- **Evoluir sem apagar o contexto.** Compatibilidade e rastreabilidade preservam a capacidade de decidir.
- **Automatizar sem perder controle.** Uma boa automação conhece seus limites e mantém decisões críticas sob responsabilidade humana.

## Contato

Meu site reúne apresentação, princípios, textos e formas de contato:

### [brunoangst.com.br](https://brunoangst.com.br/)

<p align="center">
  <strong>Código é parte da solução. O restante está nas decisões que o tornaram possível.</strong>
</p>
