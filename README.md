![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04-E95420?logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-7-red)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)

# 🖥️ NOC Home Lab

> Laboratório de monitoramento de infraestrutura desenvolvido para simular um ambiente de NOC (Network Operations Center) utilizando Zabbix, Grafana, Prometheus, cAdvisor e Docker.

## 📌 Sobre o projeto

Este projeto foi desenvolvido com o objetivo de colocar em prática conceitos de monitoramento, observabilidade e infraestrutura, simulando um ambiente semelhante ao encontrado em empresas.

O ambiente permite monitorar um servidor Ubuntu, containers Docker, serviços web e visualizar métricas em tempo real através de dashboards personalizados.

---

## 🏗️ Arquitetura

![Arquitetura do NOC Home Lab](https://github.com/user-attachments/assets/8cc2ffc6-5cd8-4255-a801-98a22de023f5)
---

## 🛠️ Tecnologias utilizadas

- Ubuntu Server 24.04 LTS
- Docker
- Docker Compose
- Zabbix Server 7
- Zabbix Agent 2
- Grafana
- Prometheus
- cAdvisor
- MariaDB
- Nginx
- Telegram (Alertas)

---

## 📊 Funcionalidades

- ✅ Monitoramento do servidor Ubuntu
- ✅ Monitoramento de containers Docker
- ✅ Dashboards personalizados no Grafana
- ✅ Coleta de métricas com Prometheus
- ✅ Monitoramento de containers com cAdvisor
- ✅ Alertas automáticos via Telegram
- ✅ Simulação de incidentes
- ✅ Documentação do ambiente

---

## 📌 Resultados

O ambiente foi implantado com sucesso e validado através de testes de monitoramento, permitindo:

- Visualização de métricas em tempo real.
- Monitoramento de containers Docker.
- Recebimento de alertas via Telegram.
- Dashboards personalizados no Grafana.
- Coleta de métricas utilizando Prometheus e cAdvisor.

## 📂 Estrutura do projeto

```text
noc-home-lab
│
├── cadvisor/
├── grafana/
├── prometheus/
├── web/
├── zabbix/
│
├── dashboards/
├── diagrams/
├── docs/
├── screenshots/
│
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

## 🚀 Serviços implantados

| Serviço | Porta |
|----------|------:|
| Zabbix | 8080 |
| Grafana | 3000 |
| Prometheus | 9090 |
| cAdvisor | 8082 |
| Nginx | 8081 |

---

## 🧪 Testes realizados

- Monitoramento de CPU
- Monitoramento de containers
- Alertas via Telegram
- Visualização em dashboards
- Coleta de métricas via Prometheus
- Monitoramento de serviços

---

## 📈 Próximas melhorias

- Monitoramento SNMP
- Monitoramento de Switches
- Monitoramento de Access Points
- Monitoramento de Roteadores
- Network Maps
- Node Exporter
- Monitoramento de Logs
- Backup automatizado

---

## 📚 Aprendizados

Durante o desenvolvimento deste laboratório foram praticados conceitos como:

- Linux
- Redes
- Docker
- Monitoramento
- Observabilidade
- Troubleshooting
- Dashboards
- Integração entre ferramentas
- Gerenciamento de incidentes

---

## 👨‍💻 Autor

**Miguel Silva**

- LinkedIn: https://www.linkedin.com/in/miguel-de-sa-silva/
- GitHub: https://github.com/miguel2004silva
