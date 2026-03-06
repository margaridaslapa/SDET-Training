# ⚓ SDET & Software Engineering Intensive Training

Este repositório documenta a minha jornada intensiva de 5 semanas para o domínio de competências em **Software Developer in Test (SDET)** e **Engenharia de Software**. 

Através do desenvolvimento do ecossistema **MariTech** (soluções tecnológicas para o setor marítimo), apliquei conceitos avançados de programação, automação e infraestrutura.

## 🎯 Objetivos do Treino
* **Linguagens:** Domínio de C# (.NET 8) e automação utilitária com Python.
* **Qualidade:** Implementação de pirâmide de testes (Unit, Integration, E2E) e Mocking.
* **Sistemas:** Gestão de memória (Stack/Heap), concorrência (Async) e resiliência.
* **Infraestrutura:** Automação via PowerShell, Bash (Linux) e pipelines CI/CD.

---

## 📅 Estrutura do Programa

### [Week 1: C# OOP & Memory Management](./week-01-csharp-oop-memory-management)
* **Projetos:** `MariTech.FleetCore`, `MariTech.MarinaManager`.
* **Destaques:** Herança, Interfaces, LINQ, Exceptions personalizadas e análise de alocação de memória (Stack vs Heap). Execução em ambiente **Linux (WSL)**.

### [Week 2: Automation & NUnit Framework](./week-02-automation-nunit-selenium-pom)
* **Projetos:** `MariTech.Maintenance.UI.Tests`, `Satellite.StressTester`.
* **Destaques:** Selenium WebDriver com **Page Object Model (POM)**, testes paralelos, e simulação de latência de rede em ambiente marítimo.

### [Week 3: API Testing & Scripting](./week-03-api-testing-rest-python-scripting)
* **Projetos:** `MariTech.SensorAPI.Validator`, `MultiSource.Telemetry.Converter`.
* **Destaques:** Automação de APIs com C# (HttpClient) e Python (Requests). Validação de JSON Schemas e criação de *Data Fuzzers*.

### [Week 4: DevOps & CI/CD Infrastructure](./week-04-devops-cicd-powershell-linux)
* **Projetos:** `Automated.Backup.Integrity`, `Linux.Log.Watchdog`.
* **Destaques:** Automação de backups com **PowerShell**, scripts de monitorização em **Bash** e configuração de pipelines no **Azure DevOps**.

### [Week 5: Web API, Security & Cloud](./week-05-webapi-integration-testing-cloud)
* **Projetos:** `Incident.Reporting.API`, `Crew.Access.Security`.
* **Destaques:** Princípios **SOLID**, injeção de dependência, **Mocking (Moq)** e desenho de arquitetura em **Azure**.

---

## 🛠 Tech Stack principal
- **Linguagens:** C#, Python, PowerShell, Bash.
- **Frameworks:** .NET 8, NUnit, Selenium, PyTest.
- **Ferramentas:** Visual Studio 2022, Docker, WSL (Ubuntu), Azure DevOps.

---

## ⚙️ Como Executar
Cada semana contém o seu próprio guia de execução. No geral, é necessário:
1. Ter o **.NET 8 SDK** instalado.
2. Configurar o **WSL** para os projetos focados em Linux.
3. Executar `dotnet test` na raiz de cada projeto para validar os requisitos de qualidade.

---
*Este repositório foi construído com foco na excelência técnica e na resolução de problemas reais de integridade de dados e automação.*

