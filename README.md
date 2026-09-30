<div align="center">

# Pedro Blamires Cordeiro

**Desenvolvedor de Software & QA · Salesforce · .NET · SQL Server · Integração de Sistemas**
<br>
*Goiânia/GO · Brasil | Ciência da Computação na PUC Goiás | 🇧🇷 Português · 🇺🇸 English*

[![Email](https://img.shields.io/badge/Email-pedroblamires%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:pedroblamires@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pedroblamires-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedroblamires)
[![GitHub](https://img.shields.io/badge/GitHub-ArrozbR-181717?style=flat&logo=github&logoColor=white)](https://github.com/ArrozbR)

</div>

---

## Sobre mim

Sou **Junior QA Lead / Desenvolvedor de Software na Vacation Innovations** (Orlando, FL), trabalhando remoto do Brasil desde fevereiro de 2025. Atuo em sistemas em produção de ponta a ponta: **Salesforce (Apex, SOQL)**, back-end em **C# / ASP.NET MVC**, banco em **SQL Server** e depuração front-end em **JavaScript**.

Também curso **Ciência da Computação na PUC Goiás**, onde fui monitor de Algoritmos e venho construindo uma base sólida em estruturas de dados, banco de dados, sistemas operacionais, sistemas distribuídos e paradigmas de linguagens. Estou **escrevendo um artigo científico** sobre vulnerabilidades de segurança em código gerado por IA em aplicações web.

## Stack principal

#### Linguagens
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Apex](https://img.shields.io/badge/Apex-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

#### Backend e dados
![.NET](https://img.shields.io/badge/ASP.NET_MVC-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework-68217A?style=for-the-badge&logo=dotnet&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-A91D22?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

#### Integrações e plataformas
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![SOQL](https://img.shields.io/badge/SOQL-032D60?style=for-the-badge&logo=salesforce&logoColor=white)
![Skyvia](https://img.shields.io/badge/Skyvia_ETL-1E88E5?style=for-the-badge&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=openapiinitiative&logoColor=white)

#### Front-end
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

#### Ferramentas
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

## Projetos em destaque

### [KeycapStore (E-Commerce)](https://github.com/ArrozbR/E-Commerce)
Loja de keycaps em **ASP.NET Core (.NET 10)** com pagamento por **cartão e Pix via Stripe Checkout**, construída como projeto de portfólio **pronto para produção**, só que rodando em modo teste e com custo zero de infraestrutura.

**Status:** em desenvolvimento.

**Já implementado:**
- **Clean Architecture** em 4 projetos (Domain, Application, Infrastructure, Web), com **teste de arquitetura** que garante que o domínio não depende de nada externo;
- testes de integração com **WebApplicationFactory + PostgreSQL via Testcontainers**;
- **CI no GitHub Actions** (build, testes, formatação, **gitleaks**), com actions fixadas por hash e `main` protegida por PR obrigatório;
- spike da Stripe documentado: mapeamento real dos eventos de webhook de cartão e Pix, incluindo eventos fora de ordem e falhas de Pix.

**19 ADRs** registram cada decisão de arquitetura, com alternativas rejeitadas e consequências.

![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=flat&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=flat)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![status](https://img.shields.io/badge/status-em_desenvolvimento-yellow?style=flat)

### [agenda-pessoal](https://github.com/ArrozbR/agenda-pessoal)
Agenda/produtividade web em **ASP.NET Core MVC (.NET 10)** que gerencia **tarefas, eventos, anotações e dashboard**, feita pra uso diário no PC e no celular. Roda em produção numa VM da **Oracle Cloud**, atrás de **Nginx** com HTTPS via **Let's Encrypt**.

**Status:** em produção e em uso diário, com deploys frequentes.

**Destaques:**
- arquitetura em camadas com services por interface, ViewModels, **EF Core + SQLite**, migrations e soft delete via query filters globais;
- **tarefas e eventos recorrentes**, subtarefas reordenáveis, histórico de adiamentos e calendário com **drag-and-drop** (FullCalendar);
- lembretes por **Web Push (VAPID)** e **e-mail HTML** (MailKit), com soneca direto da notificação e link assinado;
- exportação **ICS (RFC 5545)** com RRULE e UIDs estáveis;
- editor de anotações rico (checklists, tabelas, imagens) com **sanitização de HTML** na escrita e tags coloridas;
- autenticação por PIN com **hash PBKDF2**, bloqueio por tentativas e Data Protection persistente;
- **10 temas** (7 escuros, 3 claros), layout responsivo com navegação inferior no mobile e assets de PWA;
- backup automático semanal por e-mail e para o OneDrive.

![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core_MVC-512BD4?style=flat&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5.3-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat&logo=oracle&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![status](https://img.shields.io/badge/status-concluído-brightgreen?style=flat)

### [Jogo-da-Forca](https://github.com/ArrozbR/Jogo-da-Forca)
Jogo da forca **multiplayer cliente/servidor** com **servidor tolerante a falhas**, feito em dupla para a disciplina de **Sistemas Distribuídos**. Dois jogadores disputam a mesma palavra, e a partida continua do mesmo ponto mesmo quando **o computador inteiro** que roda o servidor é desligado à força.

**Status:** concluído e testado de ponta a ponta com duas VMs em notebooks diferentes.

**Destaques:**
- comunicação via **sockets TCP** com protocolo próprio de enquadramento de mensagens, servidor usando **só a biblioteca padrão**;
- **replicação primário/backup** com heartbeat, detecção de falha em ~6 s e **failover automático** em ~10 s;
- **fencing** pelo hypervisor da outra máquina e segredo na replicação para impedir que um impostor derrube o primário;
- replica **antes** de confirmar ao cliente, com reenvio idempotente, então nenhum lance se perde ou conta duas vezes no failover;
- **event loop de thread única** como semáforo, eliminando condições de corrida na sala de espera;
- sala de espera com convites, fila de partidas, reconexão com partida suspensa e prazo por jogada controlado pelo servidor;
- cliente gráfico em **PyQt6** que mostra ao vivo qual servidor está atendendo e os bonecos dos dois jogadores;
- infra automatizada com scripts de provisionamento de **VirtualBox** e injeção de falha para testar a janela entre replicar e confirmar.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat&logo=qt&logoColor=white)
![Sockets](https://img.shields.io/badge/TCP_Sockets-222222?style=flat)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat&logo=virtualbox&logoColor=white)
![status](https://img.shields.io/badge/status-concluído-brightgreen?style=flat)

### [cofre-aes](https://github.com/ArrozbR/cofre-aes)
API em **FastAPI** que funciona como um cofre de credenciais, com criptografia **AES-256-GCM** e dados persistidos no **Supabase**.

**Destaques:**
- derivação de chave com **PBKDF2-HMAC-SHA256** (210 mil iterações);
- **AAD** amarrando cada segredo ao seu cofre, impedindo troca de ciphertext entre registros;
- verificador de senha mestra sem guardar a senha em lugar nenhum;
- feito com **PyCryptodome**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![AES-GCM](https://img.shields.io/badge/AES--256--GCM-222222?style=flat)
![status](https://img.shields.io/badge/status-concluído-brightgreen?style=flat)

## Interesses técnicos

- integração de sistemas e pipelines ETL (Salesforce ↔ SQL Server);
- SQL Server: stored procedures, otimização de consultas e migração de dados;
- QA: casos de teste, testes de regressão e análise de causa raiz;
- criptografia aplicada e segurança de aplicações web;
- segurança de código gerado por IA (tema do meu artigo científico em andamento);
- algoritmos, estruturas de dados e sistemas distribuídos.

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ArrozbR&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ArrozbR&layout=compact&theme=tokyonight&hide_border=true" />

</div>

## Contato

<div align="center">

[![Email](https://img.shields.io/badge/pedroblamires%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedroblamires@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedroblamires)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ArrozbR)

<sub>Goiânia/GO</sub>

</div>
