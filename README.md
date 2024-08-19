# Desafio DevOps Jr Munai

Obrigado por participar de nosso processo seletivo.

## Instruções

- Crie um repositório no seu GitHub
- Faça seus commits descritivos e específicos no seu repositório
- Atenção, avaliaremos o conteúdo do repositório bem como a descrição dos commits.

## Critérios de Avaliação

Os seguintes critérios serão utilizados apra a avaliação do Projeto do desafio:  

- Deve ser feito utilizando Infraestrutura como Código (IaC), tais como Terraform, CloudFormation, Ansible, etc;
- Deve ser feito para ser utilizado com infrastrura em nuvem, tais como AWS, Azure, GCP, etc;
- Deve prever as regras de segurança necessárias para o ambiente;
- Deve prever as regras de roteamento necessárias para o ambiente;
- Deve prever as configurações necessárias para o funcionamento do ambiente;
- Deve ser feito um diagrama de arquitetura do ambiente;
- Os arquivos devem ser claros e organizados;
- Os arquivos não devem ser de formatos binários ou proprietários;
- [Padrão de commits](https://www.conventionalcommits.org/pt-br/v1.0.0/); e
- Código em inglês.

## O desafio

O desafio consiste em criar uma estrutra para uma aplicação web, que deve conter os seguintes recursos:

### Uma máquina de banco de dados contendo um Banco de Dados PostgreSQL
- Deve ser utilizada a versão 17 do PostgreSQL;
- Deve ter uma rotina de backup, enviando o backup para um serviço de armazenamento de Objetos; e
- Deve ser acesseível apenas pela máquina contendo o servidor web.

### Uma máquina para aplicação contendo um servidor web Nginx
- Deve ser utilizada a versão 1.26 do Nginx;
- Deve ser acessível pela internet;
- Deve conter um certificado SSL válido; e
- O serviço SSH deve ser acessível pela internet.

### Uma máquina de banco de dados contendo um Banco de Dados MongoDB
- Deve ser utilizada a versão 7.1 do MongoDB;
- Deve ter uma rotina de backup, enviando o backup para um serviço de armazenamento de Objetos; e
- Deve ser acesseível apenas pela máquina contendo o servidor web.

## Observações

- O dimensionamento das máquinas é de sua escolha;
- O serviço de armazenamento de Objetos é de sua escolha;
- O serviço de Certificado SSL é de sua escolha;



_O desafio acima foi cuidadosamente construído para propósitos de avaliação apenas._
