# TechLabsOS ETH 0.4.3 - OID SNMP 

Esta lista contém OIDs SNMP para TechLabsOS ETH 0.4.3

## 🧩 Informações do Sistema

| OID     | Descrição | Tipo | Parâmetros | Acesso
|-----------|-----------|-----------|-----------|-----------|
| .1.3.6.1.2.1.47.1.1.1.1.0.1 | DEVELOPER  | STRING | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.1.0.2 | NOME DO SOFTWARE  | STRING | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.1.0.3 | VERSÃO DO SOFTWARE  | STRING | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.1.0.4 | VERSÃO DO HARDWARE  | STRING | - | read-only |

---

## ⚡ Monitor de Tensão DC/AC

| OID     | Descrição | Tipo | Parâmetros | Acesso
|-----------|-----------|-----------|-----------|-----------|
| .1.3.6.1.2.1.47.1.1.1.2.0.1 | NOME CH01 DC  | STRING | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.2.0.2 | NOME CH02 DC  | STRING | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.2.0.3 | NOME CH01 AC  | STRING | - | read-only | 
| .1.3.6.1.2.1.47.1.1.1.2.1.1 | VALOR CH01 DC  | INTEGER | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.2.1.2 | VALOR CH02 DC  | INTEGER | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.2.2.3 | VALOR CH01 AC  | INTEGER | 0: DESLIGADO - 1: LIGADO | read-only |

---

## 🌡️ Monitor de Temperatura e Umidade

| OID     | Descrição | Tipo | Parâmetros | Acesso
|-----------|-----------|-----------|-----------|-----------|
| .1.3.6.1.2.1.47.1.1.1.3.0.1 | NOME SENSOR 01  | STRING | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.3.0.2 | NOME SENSOR 02  | STRING | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.3.1.1 | TEMPERATURA SENSOR 01  | INTEGER | - | read-only | 
| .1.3.6.1.2.1.47.1.1.1.3.1.2 | UMIDADE SENSOR 01  | INTEGER | - | read-only |
| .1.3.6.1.2.1.47.1.1.1.3.2.1 | TEMPERATURA SENSOR 02  | INTEGER | - | read-only | 
| .1.3.6.1.2.1.47.1.1.1.3.2.2 | UMIDADE SENSOR 02  | INTEGER | - | read-only |

📬 Dúvidas? Entre em contato: [support@easymonitor.com.br](mailto:support@easymonitor.com.br)