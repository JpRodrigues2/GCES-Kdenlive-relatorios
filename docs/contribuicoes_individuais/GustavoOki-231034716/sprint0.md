# Relatório de Contribuição – Sprint 0
 
**Disciplina:** Gestão de Configuração e Evolução de Software  
**Equipe:** GCES 2026.1 – Kdenlive  
**Comunidade/Projeto:** [KDE / Kdenlive](https://invent.kde.org/multimedia/kdenlive)  
**Matrícula:** 231034716  
**GitHub:** [@GustOki](https://github.com/GustOki)  
**KDE Invent:** [@gustoki](https://invent.kde.org/gustoki)  
**Período:** 13/04/2026 – 21/04/2026
 
---
 
## 1. Resumo da Sprint

A Sprint 0 teve como foco o conhecimento e imersão do projeto e objetivo. Para a estrutura do projeto e futuros desenvolvimentos do trabalho, foi feito todo o passo-a-passo para cumprir as dependências do KDEnlive utilizando Craft (por conta do SO Windows utilizado) e conclusão da build do software localmente. Além disso, houve o processo de credenciamento no KDE Invent e validação inicial de documentação do grupo utilizando o MkDocs Material.
 
---
 
## 2. Objetivos da Sprint
 
- **Padronização:** Criar um repositório de relatórios com CI/CD funcional e UI/UX otimizada.
- **Acreditação:** Obter as credenciais necessárias no KDE Identity e validar o acesso ao Invent.
- **Configuração de Ambiente:** Construção do ambiente no SO Windows (Craft/Compiler setup).
- **Mapeamento:** Entender a fundo as regras de submissão da comunidade KDE.
---
 
## 3. Entregas Coletivas
 
| Entrega | Status | Link/Referência | Observações |
| :--- | :--- | :--- | :--- |
| **Portal MkDocs** | ✅ Concluído | [Link do Repo/Pages] | Estrutura com modo dark, busca e templates. |
| **Fork & Clone** | ✅ Concluído | [[invent.kde.org/davirnunes/kdenlive](https://invent.kde.org/gustoki/kdenlive)] | Base de código sincronizada localmente. |
| **Guia de Contribuição** | ✅ Concluído | [/materiais/guia_contribuicao.md] | Baseado nas normas oficiais do Kdenlive. |
 
---
 
## 4. Log de Atividades
 
| Data | Atividade | Tipo | Status |
| :--- | :--- | :--- | :--- |
| 15/04 | Estudo de arquitetura do repositório exemplo | Estudo | ✅ |
| 16/04 | Criação de conta KDE Identity | Outro | ✅ |
| 17/04 | Setup inicial do MkDocs Material e CI/CD para deploy | Doc/Infra | ✅ |
| 21/04 | Instalação do **Craft** e configuração de dependências no Windows | Ambiente | ✅ |


---
 
## 5. Maiores Avanços
 
- **Ecossistema da comunidade KDE:** Por ser um ambiente bastante incomum de ser visto e trabalhado com frequência, ter a oportunidade de poder conhecer com mais profundidade a estrutura e regras da comunidade KDE é de extrema importância.
- **Organização em equipe automatizada:** Documentação MkDocs configurado com CI/CD garante que cada log de membro seja publicado automaticamente, reduzindo o trabalho manual.
- **Build no Windows:** Configuração do Craft e as variáveis de ambiente multimídia no Windows sem conflitos críticos.
---
 
## 6. Maiores Dificuldades

- **Complexidade da Build no SO Windows usando Craft:** houveram grandes conflitos na instalação de dependências do software no Windows, exigindo um tempo maior de pesquisa de soluções e várias tentativas de configuração.
 
---
 
## 7. Lições Aprendidas
 
- **Gestão de Configuração:** o Craft não é apenas um instalador, mas uma ferramenta de gestão de configuração essencial para manter a paridade entre ambientes de desenvolvimento distintos.
- **Cultura Open Source:** no Kdenlive, a conversa no Matrix/Fórum é tão importante quanto o código. A proatividade em canais como o [discuss.kde.org](https://discuss.kde.org/tag/kdenlive) é vital.
---
 
## 8. Plano Pessoal para a Próxima Sprint (Sprint 1)
 
- [ ] Aderir a uma issue aberta no Bugzilla KDE.
- [ ] Identificar e abrir ao menos uma issue.
- [ ] Iniciar o estudo da estrutura de classes do projeto (C++/Qt).
