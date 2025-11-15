
# Projeto de Implementação de Serviços AWS na Farmaceutica Industries**
### Bootcamp Santander 2025 - Ciência de Dados com Python
### Digital Innovation One

### **📌 Visão Geral**

Este projeto apresenta a implementação fictícia de três serviços da AWS (Amazon Web Services) na empresa **Farmaceutica Industries**, com o objetivo principal de **melhorar o fluxo de distribuição de medicamentos e reduzir custos operacionais**, especialmente nos processos de transporte e armazenamento.

A iniciativa foi conduzida por **Ronaldo Schmidt**, responsável pela análise, seleção e aplicação dos serviços mais adequados às necessidades logísticas e regulatórias da indústria farmacêutica.

---

### **🎯 Objetivos do Projeto**

* Reduzir perdas de medicamentos durante o transporte.
* Melhorar a eficiência logística por meio de previsões e análises avançadas.
* Diminuir custos de armazenamento em longo prazo.
* Garantir rastreabilidade e segurança dos dados.
* Automatizar processos críticos da cadeia de suprimentos.

---

### **🧩 Serviços AWS Implementados**

#### **1. AWS IoT Core – Monitoramento de Transporte e Armazenamento**

O AWS IoT Core foi utilizado para conectar sensores instalados em caminhões, contêineres e depósitos.
Esse serviço possibilitou:

* Monitoramento **em tempo real** de temperatura, umidade e localização.
* Alertas automáticos em caso de quebra de cadeia de frio.
* Redução de perdas e melhor controle de qualidade no transporte.

---

#### **2. Amazon SageMaker – Previsão de Demanda e Otimização de Rotas**

O Amazon SageMaker foi adotado para criar modelos de Machine Learning capazes de:

* Prever demanda regional de medicamentos.
* Sugerir rotas de transporte mais eficientes e econômicas.
* Reduzir custos com combustível e horas de deslocamento.
* Evitar estoques excessivos ou insuficientes.

---

#### **3. Amazon S3 + Amazon Glacier – Armazenamento Seguro e de Baixo Custo**

O Amazon S3 serviu como repositório central de documentos e dados logísticos, enquanto o Amazon Glacier foi utilizado para arquivamento de longo prazo.

Benefícios obtidos:

* Armazenamento altamente durável e escalável.
* Redução de custos com infraestruturas locais.
* Conformidade com exigências regulatórias (RDCs, FDA, Boas Práticas).
* Organização dos dados logísticos para auditorias e consultas.

---

### **🏗️ Arquitetura Simplificada do Projeto**

```
Sensores -> AWS IoT Core -> Processamento/Alertas
                                    |
                                    v
                           Amazon SageMaker
                                    |
                                    v
             Previsões, Rotas, Dashboards Logísticos
                                    |
                                    v
           Amazon S3 <-> Arquivamento no Amazon Glacier
```

---

### **📊 Benefícios Esperados**

* Diminuição de custos operacionais imediatos.
* Redução de perdas por falhas na cadeia de frio.
* Logística mais inteligente, baseada em dados.
* Custo de armazenamento reduzido em até 90% (com Glacier).
* Rastreabilidade completa da cadeia de distribuição.
* Aumento geral da eficiência e produtividade.

---

### **📝 Estrutura do Repositório (Sugerida)**

```
/
├── relatorio/
│   └── Relatorio_Implementacao_AWS.pdf
├── modelos/
│   ├── previsao_demanda.ipynb
│   └── otimizacao_rotas.ipynb
├── documentos/
│   ├── manuais/
│   └── fluxos_logisticos.md
└── README.md
```

*(Estrutura opcional — pode ser ajustada conforme a necessidade do seu projeto.)*

---

### **👤 Autor**

**Ronaldo Schmidt**
Responsável pela análise e implementação dos serviços AWS no projeto.

---

## **📎 Licença**

Este projeto é fictício e tem fins exclusivamente acadêmicos e demonstrativos.

---


