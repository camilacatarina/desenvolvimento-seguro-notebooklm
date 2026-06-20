# Desenvolvimento Seguro de Aplicações

Projeto desenvolvido para o desafio do BootCamp da DIO com a Bradesco utilizando o NotebookLM como ferramenta de aprendizagem ativa. O tema escolhido foi Desenvolvimento Seguro de Aplicações, com foco em cibersegurança aplicada ao ciclo de desenvolvimento de software.

## Contexto

Fiz um projeto sobre o Desenvolvimento Seguro de Aplicações pois a segurança tornou-se um requisito essencial no desenvolvimento de software. Essas vulnerabilidades em aplicações podem resultar em vazamento de dados, indisponibilidade de serviços e prejuízos financeiros.

Diante disso, este caderno temático foi desenvolvido utilizando o NotebookLM como ferramenta de estudo e aprendizagem ativa, com foco em Desenvolvimento Seguro de Aplicações e na integração da cibersegurança ao ciclo de desenvolvimento de software!

## Objetivos

* Compreender os fundamentos da cibersegurança aplicados ao desenvolvimento de software.
* Estudar os princípios do Desenvolvimento Seguro.
* Conhecer vulnerabilidades comuns presentes em aplicações.
* Entender a importância do Secure by Design.
* Aprender boas práticas para redução de riscos de segurança.
* Construir um material de consulta para futuras revisões.

## Curadoria de Fontes

* ANBIMA – Desenvolvimento Seguro de Aplicações
https://www.anbima.com.br/data/files/A3/36/31/78/7563A910C35D53A9BA2BA2A8/Orientacoes_Desenvolvimento_Seguro_de_Aplicacoes.pdf

* OWASP Top 10 2025
https://owasp.org/Top10/2025/

* UFRJ – Desenvolvimento Seguro
https://seguranca.tic.ufrj.br/tutoriais/desenvolvimentoseguro/

* IBM – Cybersecurity
https://www.ibm.com/br-pt/think/topics/cybersecurity

* Fundação Vanzolini – Cibersegurança e Software Seguro
https://vanzolini.org.br/blog/ciberseguranca-software-seguro/

## Engenharia de Prompts

### Prompt 1

**Pergunta:**
O que é desenvolvimento seguro de aplicações e por que ele é importante para organizações modernas?

**Resultado obtido:**
A resposta definiu desenvolvimento seguro como a integração da segurança em todas as etapas do ciclo de vida do software. Também destacou benefícios como redução de prejuízos financeiros, conformidade com legislações como a LGPD, proteção da reputação da organização e adaptação a ameaças cada vez mais sofisticadas.

**Aprendizados:**
Percebi que o desenvolvimento seguro deixou de ser apenas uma prática técnica e passou a ser um requisito estratégico para as organizações. A segurança deve ser considerada desde o planejamento do software e não apenas após sua implementação.

### Prompt 2

**Pergunta:**
Com base nas fontes fornecidas, explique como a segurança deve ser incorporada ao ciclo de desenvolvimento de software.

**Resultado obtido:**
A resposta apresentou o conceito de SSDLC (Secure Software Development Life Cycle), demonstrando como a segurança deve estar presente em todas as fases do desenvolvimento: planejamento, arquitetura, implementação, testes, implantação e manutenção. Também foram abordados conceitos como modelagem de ameaças, codificação segura, SAST, DAST, hardening e monitoramento contínuo.

**Aprendizados:**
Compreendi que a segurança é um processo contínuo. O conceito de Shift Left mostrou a importância de identificar vulnerabilidades o mais cedo possível, reduzindo custos e aumentando a qualidade do software.

### Prompt 3

**Pergunta:**
Compare a abordagem Secure by Design da CISA com as práticas de desenvolvimento seguro presentes nas demais fontes.

**Resultado obtido:**
A resposta mostrou que o Secure by Design é uma filosofia que defende a segurança como característica nativa do produto. Já as demais fontes detalham como aplicar essa filosofia por meio de práticas concretas, como SSDLC, validação de entradas, princípio do menor privilégio, hardening, gestão de dependências e proteção de dados.

**Aprendizados:**
Entendi que o Secure by Design representa a visão estratégica da segurança, enquanto frameworks, processos e ferramentas são responsáveis por transformar essa visão em ações práticas dentro do desenvolvimento de software.

## Dificuldades Encontradas (Cicatrizes)

Uma das principais dificuldades foi elaborar prompts suficientemente específicos para obter respostas aprofundadas e alinhadas ao objetivo do estudo.

Outro desafio foi conectar conceitos apresentados por diferentes fontes, como Secure by Design, SSDLC, Shift Left e OWASP Top 10. A princípio, esses temas pareciam independentes, mas a partir do refinamento dos prompts foi possível compreender como eles se complementam dentro de uma estratégia de desenvolvimento seguro.

Também foi necessário adaptar as perguntas para obter comparações entre abordagens e não apenas definições. Os melhores resultados foram alcançados quando os prompts solicitaram análises comparativas, aplicações práticas e relações entre os conceitos estudados.

E como aprendizado, ficou evidente que a qualidade das respostas geradas pela IA depende diretamente da qualidade das perguntas formuladas.

## 6. Miniguia de Estudo

### ## 6.1 Resumo Estruturado

### O que é Desenvolvimento Seguro de Aplicações?

O desenvolvimento seguro de aplicações (Application Security - AppSec) consiste na integração de práticas de segurança em todas as etapas do ciclo de vida do software. Seu objetivo é reduzir vulnerabilidades, proteger dados e garantir que os sistemas sejam resilientes a ameaças cibernéticas.

### SSDLC (Secure Software Development Life Cycle)

O SSDLC amplia o ciclo tradicional de desenvolvimento ao incorporar atividades de segurança desde o planejamento até a manutenção do software.

As principais etapas incluem:

* Planejamento e definição de requisitos de segurança;
* Modelagem de ameaças;
* Arquitetura segura;
* Codificação segura;
* Testes de segurança;
* Implantação segura;
* Monitoramento e correção contínua.

### Secure by Design

O conceito Secure by Design estabelece que a segurança deve ser considerada desde a concepção do software. Em vez de corrigir vulnerabilidades após o desenvolvimento, busca-se evitar que elas sejam introduzidas no sistema.

### Shift Left

A abordagem Shift Left consiste em antecipar atividades de segurança para as fases iniciais do desenvolvimento, reduzindo custos de correção e aumentando a qualidade do software.

### Principais Práticas de Segurança

* Validação de entradas;
* Princípio do menor privilégio;
* Defesa em profundidade;
* Criptografia de dados;
* Hardening de ambientes;
* Monitoramento contínuo;
* Gestão de vulnerabilidades.

### Importância para as Organizações

O desenvolvimento seguro contribui para a conformidade regulatória, redução de riscos, proteção da reputação institucional, continuidade dos negócios e proteção dos dados dos usuários.

### ## 6.2 Glossário

**AppSec:** Segurança aplicada ao desenvolvimento de software.

**SSDLC:** Ciclo de Vida de Desenvolvimento Seguro de Software.

**Secure by Design:** Segurança incorporada desde a concepção do sistema.

**Shift Left:** Antecipação das práticas de segurança para as fases iniciais do desenvolvimento.

**OWASP:** Organização que produz referências sobre segurança de aplicações.

**SAST:** Análise estática do código-fonte para identificação de vulnerabilidades.

**DAST:** Análise dinâmica realizada com a aplicação em execução.

**SCA:** Análise de componentes e dependências de terceiros.

**SBOM:** Inventário dos componentes utilizados em um software.

**Hardening:** Processo de fortalecimento da configuração de sistemas.

**Modelagem de Ameaças:** Técnica para identificar riscos e vetores de ataque.

**Privilégio Mínimo:** Concessão apenas das permissões necessárias para cada usuário ou componente.

**Defesa em Profundidade:** Utilização de múltiplas camadas de proteção.

**Privacy by Design:** Privacidade incorporada desde a concepção do sistema.

**Pentest:** Teste de invasão realizado de forma controlada para identificar vulnerabilidades.

### ## 6.3 Prompts Reutilizáveis

* Explique o conceito de Secure by Design para um estudante de Análise e Desenvolvimento de Sistemas.

* Compare Secure by Design e Shift Left, destacando semelhanças, diferenças e aplicações práticas.

* Crie um resumo estruturado sobre o Secure Software Development Life Cycle (SSDLC).

* Quais são os riscos associados ao uso de bibliotecas e dependências de terceiros em aplicações web?

* Crie um checklist de boas práticas de segurança para o deploy de uma aplicação web em produção.

* Explique como aplicar o princípio do menor privilégio em um projeto real de software.

* Quais vulnerabilidades da OWASP Top 10:2025 devo considerar ao desenvolver uma aplicação web?

* Atue como especialista em segurança e avalie os riscos presentes em uma aplicação que armazena dados pessoais de usuários e utiliza autenticação por login e senha.

## 7. Conclusão

A utilização do NotebookLM me demonstrou como a inteligência artificial pode auxiliar na organização do conhecimento, neste refinamento de perguntas e na construção de uma aprendizagem mais ativa e estruturada. Esse estudo reforçou a necessidade de incorporar princípios de segurança desde a concepção das aplicações, para contribuindo para a criação de sistemas mais confiáveis!
