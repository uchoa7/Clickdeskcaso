# Clickdeskcaso
🖥️ Click Desk
Sistema de chamados integrado com Inteligência Artificial para análise de prioridade e suporte ao usuário.
Disponível para Web, Desktop e Mobile.

🎯 Descrição Geral
Empresas enfrentam dificuldades em organizar e priorizar chamados de TI, o que gera atrasos no atendimento e perda de eficiência.
O Click Desk foi desenvolvido para automatizar a classificação e priorização de chamados utilizando IA, garantindo maior agilidade e qualidade no suporte.

📋 Backlog do Produto
 Como usuário, quero abrir um chamado com título e descrição, para registrar meu problema.
 Como analista, quero visualizar os chamados em ordem de prioridade, para atender os mais críticos primeiro.
 Como gestor, quero relatórios sobre o tempo de resolução, para acompanhar o desempenho da equipe.
 Como sistema, quero utilizar IA para definir automaticamente a prioridade dos chamados, para otimizar o fluxo de atendimento.
 Como usuário, quero acessar a aplicação tanto em web, desktop e mobile, para maior flexibilidade.
🗓️ Cronograma de Evolução do Projeto
Sprint	Período	Objetivo	Status
Sprint 1	01/09 – 14/09	Configuração do ambiente, setup do banco e backend inicial	✅ Concluído
Sprint 2	15/09 – 28/09	CRUD de chamados e autenticação	🚧 Em andamento
Sprint 3	29/09 – 12/10	Integração inicial da IA para priorização	⏳ Planejado
Sprint 4	13/10 – 26/10	Implementação do frontend (web + mobile + desktop)	⏳ Planejado
📑 Sprints
Sprint	Período	Documentação	Vídeo (YouTube)
Sprint 1	01/09 – 14/09	Docs Sprint 1	Vídeo Sprint 1
Sprint 2	15/09 – 28/09	Docs Sprint 2	Vídeo Sprint 2
🛠️ Tecnologias Utilizadas
Backend: Java 17, Spring Boot
Banco de Dados: MySQL
Frontend Web: Thymeleaf (ou React, dependendo da evolução)
Mobile: Flutter (ou outra tecnologia escolhida)
Desktop: JavaFX ou Electron (dependendo da stack escolhida)
IA: Modelos de classificação de texto (Deep Learning / NLP)
Build: Gradle/Maven
Versionamento: Git + GitHub/GitLab
Outros: Docker
📂 Estrutura do Projeto
/click-desk
 ├── backend
 │   ├── src
 │   └── test
 ├── frontend-web
 ├── mobile
 ├── desktop
 ├── docs
 │   ├── sprint1.md
 │   ├── sprint2.md
 │   ├── manual.md
 │   └── checklist.md
 ├── README.md
 └── build.gradle / pom.xml


# Clonar o repositório
git clone https://github.com/seu-usuario/click-desk.git  

# Acessar pasta do projeto
cd click-desk  

# Rodar backend (Spring Boot com Maven)
./mvnw spring-boot:run

# ou (com Gradle)
./gradlew bootRun

Para rodar frontend (web, mobile e desktop):
	•	Consulte as instruções específicas em cada pasta (frontend-web/, mobile/, desktop/).

Como testar 🧪
# Rodar testes unitários do backend
./mvnw test
