# escola-da-nuvem-aws-vpc
Criando recursos de networking nas vpc aws

# AWS Lab: Criação de Recursos de Rede em uma Amazon VPC

Este repositório contém a documentação do laboratório prático de **Redes na AWS (Amazon VPC)**, realizado durante o curso de Computação em Nuvem na **Escola da Nuvem**.

O foco principal foi analisar um cenário de cliente, diagnosticar problemas de conectividade e implementar uma arquitetura de rede roteável e segura na nuvem AWS do zero.

---

## Objetivos do Laboratório
- Entender e analisar o cenário/desafio do cliente.
- Criar uma **Virtual Private Cloud (VPC)** na AWS.
- Configurar componentes de rede essenciais:
  - **Internet Gateway (IGW)** para permitir comunicação com a internet.
  - **Route Table (Tabela de Roteamento)** configurada para direcionar o tráfego externo.
  - **Security Group (SG)** e **Network Access Control List (NACL)** para controle de segurança em nível de instância e sub-rede.
- Implantar uma instância **Amazon EC2**.
- Identificar e solucionar (*troubleshooting*) o problema de conectividade até obter sucesso no teste de conectividade externo usando o comando `ping`.

---

## Tecnologias e Serviços Utilizados
- **Provedor de Nuvem:** Amazon Web Services (AWS)
- **Redes:** Amazon VPC, Subnets, Internet Gateway, Route Tables
- **Segurança:** Security Groups (Stateful) e NACLs (Stateless)
- **Computação:** Amazon EC2 (Linux)
- **Diagnóstico:** Console AWS, protocolo ICMP (`ping`)

---

## 🚀 O que foi Aprendido e Praticado
1. **Troubleshooting de Rede:** Diagnóstico de falhas de conectividade analizando regras de firewall virtual e rotas de IP.
2. **Arquitetura de Nuvem Segura:** Entendimento prático das camadas de segurança (Security Group vs. NACL).
3. **Validação e Conectividade:** Configuração correta de rotas de saída para a internet e teste final validado via comando `ping`.
