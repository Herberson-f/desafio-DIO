# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 21/11/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Herberson G.

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Herberson G.**  
O objetivo principal do projeto foi selecionar e implementar **3 serviços AWS** com foco na **redução imediata de custos operacionais**, otimizando infraestrutura, consumo de recursos e eficiência do ambiente na nuvem.

---

## Descrição do Projeto

O projeto foi dividido em **3 etapas**, cada uma responsável por aplicar uma ferramenta AWS voltada à otimização e ao corte de custos.

---

### **Etapa 1: Amazon S3 (com S3 Intelligent-Tiering)**

- **Foco da ferramenta:**  
  Otimização e redução de custos de armazenamento.

- **Descrição de caso de uso:**  
  A empresa utilizava servidores locais e EBS para arquivar arquivos pouco acessados.  
  Foi realizada a migração desses dados para o **Amazon S3**, ativando a política **S3 Intelligent-Tiering**, que move automaticamente objetos entre camadas de menor custo conforme o padrão de acesso.  
  Também foram revisa
