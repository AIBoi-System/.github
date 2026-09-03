<div align="center">

# 🐮 AiBoi — Gestão para Pecuária 4.0

### *Digitalização do manejo bovino com dados, reprodução, sanidade e gestão de propriedades.*

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-3.11+-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

**Status do Projeto:** Desenvolvimento Ativo (2026)

</div>

## 📄 Sobre o Projeto

O **AiBoi** é uma solução em formato de *monorepo* desenvolvida para modernizar e digitalizar a gestão pecuária. Combinando uma API robusta de alta performance e um aplicativo mobile intuitivo, o sistema atende desde o produtor rural até a equipe de campo diretamente no manejo diário.

Este repositório está dividido em dois módulos principais:

| Módulo | Descrição | Documentação Técnica |
| :--- | :--- | :--- |
| **Backend** | API REST, banco de dados, Docker e testes automatizados. | [📂 backend/README.md](./backend/README.md) |
| **Frontend** | Aplicativo mobile, fluxos de interface e experiência do usuário. | [📂 frontend/README.md](./frontend/README.md) |

---

## 🏗️ Arquitetura e Tecnologias

* **Backend:** Construído em **FastAPI** seguindo os princípios de **Clean Architecture** e **DDD (Domain-Driven Design)** para garantir escalabilidade e fácil manutenção.
* **Frontend:** Desenvolvido em **Flutter**, permitindo uma única base de código para múltiplos alvos (foco principal em Android e iOS).
* **Banco de Dados:** **MySQL** para persistência de dados ágil e segura.

---

## 📂 Estrutura do Repositório

```text
aiBoi-system/
├── backend/          # API FastAPI + SQLAlchemy + MySQL
├── frontend/         # App Flutter (Android, iOS, Web, Desktop)
├── docker-compose.yml
├── global-bundle.pem # Certificado SSL AWS RDS (Atenção: não versionar credenciais!)
└── README.md         # Documentação principal da organização
