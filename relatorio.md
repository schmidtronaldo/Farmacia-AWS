# **RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS**

**Data:** 14/11/2025
**Empresa:** Farmaceutica Industries
**Responsável:** Ronaldo Schmidt

---

## **Introdução**

Este relatório apresenta o processo de implementação de ferramentas na empresa **Farmaceutica Industries**, realizado por **Ronaldo Schmidt**.
O objetivo do projeto foi elencar e descrever **três serviços AWS** cuja adoção permite **redução imediata de custos** relacionados ao armazenamento, transporte, monitoramento e distribuição de medicamentos, garantindo maior eficiência operacional e segurança no fluxo logístico da indústria.

---

## **Descrição do Projeto**

O projeto foi dividido em três etapas, cada uma focada na adoção de um serviço AWS estratégico.

---

### **Etapa 1: AWS IoT Core**

* **Foco da ferramenta:**
  Monitoramento inteligente e em tempo real das condições de transporte e armazenamento de medicamentos.

* **Descrição de caso de uso:**
  O **AWS IoT Core** foi implementado para conectar sensores instalados nas unidades de transporte e nos centros de distribuição. Estes sensores coletam dados como **temperatura, umidade, vibração e localização** durante o deslocamento dos medicamentos.
  O serviço permite que os dados sejam enviados em tempo real para a nuvem, onde são processados e analisados automaticamente.
  Isso garante que qualquer desvio dos parâmetros críticos (como temperatura inadequada para vacinas ou antibióticos) seja detectado imediatamente, reduzindo perdas, evitando desperdícios e aumentando a segurança no transporte.

---

### **Etapa 2: Amazon SageMaker**

* **Foco da ferramenta:**
  Previsão de demanda e otimização de rotas logísticas utilizando Machine Learning.

* **Descrição de caso de uso:**
  O **Amazon SageMaker** foi usado para desenvolver um modelo de previsão baseado em históricos de vendas, sazonalidade e registros logísticos.
  Esse modelo gera **projeções de demanda regional**, permitindo que a empresa distribua seus medicamentos de forma mais eficiente, evitando excesso de estoque em alguns locais e falta em outros.
  Além disso, o SageMaker auxilia na **otimização de rotas de transporte**, sugerindo caminhos mais rápidos e econômicos, o que reduz custos com combustível, horas de trabalho e riscos de atraso.

---

### **Etapa 3: Amazon S3 + Amazon Glacier**

* **Nome da ferramenta:** Amazon S3 (com camadas de arquivamento no Glacier)

* **Foco da ferramenta:**
  Armazenamento seguro e escalável de documentos, laudos, históricos de transporte e dados de sensores.

* **Descrição de caso de uso:**
  O **Amazon S3** foi implementado como repositório central para armazenar todos os registros logísticos, incluindo documentos de compliance, auditorias, certificados de transporte e dados coletados pelos dispositivos IoT.
  Os arquivos mais antigos ou acessados com menor frequência foram movidos automaticamente para o **Amazon Glacier**, reduzindo drasticamente os custos de armazenamento a longo prazo.
  A combinação S3 + Glacier garante conformidade com normas regulatórias do setor farmacêutico, elimina a necessidade de servidores locais e reduz despesas com manutenção de infraestrutura física.

---

## **Conclusão**

A implementação das três ferramentas AWS na empresa **Farmaceutica Industries** tem como esperado:

* Redução significativa de perdas por falhas no transporte (IoT Core).
* Diminuição dos custos de armazenagem e distribuição devido à previsão inteligente de demanda (SageMaker).
* Otimização do fluxo logístico e menor gasto com transporte (SageMaker).
* Armazenamento seguro, auditável e com custos extremamente reduzidos (S3 + Glacier).
* Maior eficiência operacional, rastreabilidade completa e agilidade no processo decisório.

Recomenda-se a continuidade do uso das ferramentas implementadas, bem como a busca por novas tecnologias na AWS capazes de ampliar os ganhos, como AWS Lambda, Amazon QuickSight e AWS Supply Chain.

---

## **Anexos**

* Manual de configuração do AWS IoT Core
* Planilha com previsões geradas pelo SageMaker
* Diagrama de arquitetura das soluções implantadas
* Logs de transporte e sensores integrados
* Documentação S3 e Glacier de retenção e auditoria

---

**Assinatura do Responsável pelo Projeto:**
**Ronaldo Schmidt**


