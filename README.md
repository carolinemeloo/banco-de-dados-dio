# Projeto - Configuração de Banco de Dados no Azure

Este repositório foi criado como parte do desafio da DIO com o objetivo de documentar, de forma simples e prática, a criação de uma instância de banco de dados no Microsoft Azure. Aqui compartilho minhas anotações pessoais, aprendizados, dicas e analogias que me ajudaram a entender os conceitos da computação em nuvem.

---

## O que você vai encontrar aqui:

- Dicas e analogias para facilitar o entendimento
- Passo a passo para criar a instância de banco de dados
- Palavras-chave explicadas de forma simples
- Técnicas para memorizar os conceitos

---

## O que aprendi até aqui

### Entendendo a Nuvem (Cloud Computing)

Uma das analogias que mais me ajudou foi a do **professor explicando a nuvem como uma máquina de lavar compartilhada**:  
> *Você não precisa comprar uma máquina, instalar, consertar, pagar energia... Você só paga para usar quando precisa.*  
> Assim também é a nuvem: você usa recursos de forma sob demanda, pagando pelo que usar.

### Modelos de Serviço: IaaS, PaaS e SaaS

Para entender esses modelos, criei a técnica da **Pizza da Nuvem**:

- 🍕 **IaaS**: você faz a pizza do zero (estrutura).
- 🍕 **PaaS**: você recebe pronta para assar (plataforma).
- 🍕 **SaaS**: você só come (software pronto).

### Outras Palavras-chave importantes:

- **Elasticidade**: a nuvem se adapta à demanda (aumenta ou reduz recursos conforme necessário).
- **Alta disponibilidade**: sistemas funcionam mesmo em caso de falhas.
- **Backup automático**: segurança para seus dados.
- **Escalabilidade**: permite crescer sem mudar a estrutura.

---

## Passo a passo: Criando o banco de dados

1. Acesse [portal.azure.com](https://portal.azure.com)
2. Vá em **"SQL Database" > "Criar"**
3. Dê um nome ao banco e configure um servidor
4. Escolha o modelo de compra e camada de preço (DTU ou vCore)
5. Ajuste as regras de firewall
6. Clique em **"Revisar + Criar"** e aguarde a implantação

---

## Minhas Dicas

- Comece explorando a interface do Azure com calma
- Use os planos mais básicos para aprender sem gastar
- Documente tudo que você fizer — é útil para revisar depois
- Use analogias no seu aprendizado: elas ajudam MUITO!

---

## Referências

- [Documentação Oficial - Azure SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-create-quickstart)
- [GitHub Docs](https://docs.github.com/)
- [Guia de Markdown](https://guides.github.com/features/mastering-markdown/)

---

Desenvolvido como parte do bootcamp da DIO 
