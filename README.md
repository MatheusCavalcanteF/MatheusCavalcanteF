## Olá, eu sou o Matheus

Estudante de **Sistemas de Informação** (Universidade Santa Cecília) e graduado em Gestão de Recursos Humanos. Trabalho em ambiente hospitalar com dados, indicadores (KPIs) e faturamento.

Busco estágio em **Dados** (análise, engenharia, BI) ou **Desenvolvimento de Software**. Moro em Santos, SP.

### Projetos em destaque

| Projeto | O que faz | Stack |
|---|---|---|
| [**Painel de Internações SUS – Baixada Santista**](https://github.com/MatheusCavalcanteF/datasus-etl-baixada-santista) | Pipeline de ponta a ponta com microdados públicos do DATASUS: 4,7 milhões de AIHs de SP viram um Star Schema com 144,8 mil internações dos 9 municípios da Baixada Santista, enriquecido com a API do CNES e a tabela CID-10, consumido pelo Power BI | Python, pandas, NumPy, Parquet, SQLite, Power BI (DAX) |
| [**HealthStaff Sync**](https://github.com/MatheusCavalcanteF/healthstaff-sync) | Conciliador de escalas de enfermagem e banco de horas: importa escalas (PDF/Excel) e aponta inconformidades trabalhistas por colaborador | Java, Spring Boot, PostgreSQL, Python (FastAPI), Next.js, Docker |
| [**Cloud Data Pipeline**](https://github.com/MatheusCavalcanteF/cloud-data-pipeline) | Ingestão em data lake no AWS S3 particionado por data, ETL com pandas e carga idempotente no PostgreSQL | Python, Boto3, AWS S3, PostgreSQL, Docker |
| [**Finanças Pessoais**](https://github.com/MatheusCavalcanteF/api-financas-pessoais) | Aplicação full stack: importação de extratos CSV/OFX com deduplicação e categorização automática | Java, Spring Boot, Spring Security (JWT), PostgreSQL, Next.js, TypeScript |
| [**Folha de Pagamento Hospitalar**](https://github.com/MatheusCavalcanteF/api-folha-pagamento) | API REST que calcula a renda mensal por situação funcional, horas extras e plantões | Java, Spring Boot, Spring Security, Spring Data JPA, JUnit |
| [**Automação de Indicadores da UTI**](https://github.com/MatheusCavalcanteF/automacao-indicadores-uti) | Gera o relatório mensal de indicadores de uma UTI Pediátrica a partir de planilhas, PDF e ODT, entregando o documento Word pronto para revisão | Python, pandas, openpyxl, python-docx, Pytest |
| [**CSV Toolkit**](https://github.com/MatheusCavalcanteF/csv-toolkit) | CLI que filtra e agrega arquivos CSV lendo um registro por vez, sem carregar o arquivo inteiro em memória | C11, CMake, Make |

### Tecnologias

- **Linguagens:** Python, Java, SQL, TypeScript, C
- **Dados e BI:** pandas, NumPy, Jupyter, ETL, Parquet, modelagem dimensional (Star Schema), Power BI (DAX), Excel avançado
- **Back-end e front-end:** Spring Boot, FastAPI, Next.js, React
- **Bancos de dados:** PostgreSQL, SQL Server, SQLite, MongoDB
- **Qualidade e infraestrutura:** Pytest, JUnit, Testcontainers, Playwright, GitHub Actions, Docker, AWS S3

### Como eu trabalho

- Testes automatizados e CI em todos os projetos em destaque.
- Segurança desde o começo: segredos fora do git e, nos projetos em Python, Java e TypeScript, dependências monitoradas (Dependabot) e análise de código (CodeQL).
- Cuidado com dados pessoais (LGPD): os repositórios só usam dados públicos e anonimizados ou dados fictícios.

### Contato

- E-mail: [matheuscf23@gmail.com](mailto:matheuscf23@gmail.com)
