# Desafio DevOps Jr Munai

Obrigado por participar do nosso processo seletivo.

## Instruções

- Crie um repositório no seu GitHub.
- Faça commits descritivos e específicos no seu repositório.
- Atenção: avaliaremos tanto o conteúdo do repositório quanto a descrição dos commits.

## Critérios de Avaliação

Os seguintes critérios serão utilizados para a avaliação do projeto do desafio:

- Deve ser realizado utilizando Infraestrutura como Código (IaC), como Terraform, CloudFormation, Ansible, etc.;
- Deve ser desenvolvido para ser utilizado em infraestrutura na nuvem, como AWS, Azure, GCP, etc. **Não é obrigatória a implementação real do sistema**.
- Deve incluir as regras de segurança necessárias para o ambiente;
- Deve incluir as regras de roteamento necessárias para o ambiente;
- Deve incluir as configurações necessárias para o funcionamento do ambiente;
- Deve ser feito um diagrama de arquitetura do ambiente;
- Os arquivos devem ser claros e organizados;
- Os arquivos não devem ser de formatos binários ou proprietários;
- [Padrão de commits](https://www.conventionalcommits.org/pt-br/v1.0.0/);
- Código em inglês.

## O Desafio

O desafio consiste em criar uma estrutura para uma aplicação web, que deve conter os seguintes recursos:

### Máquina de banco de dados contendo um Banco de Dados PostgreSQL

- Deve ser utilizada a versão 17 do PostgreSQL;
- Deve haver uma rotina de backup, enviando o backup para um serviço de armazenamento de objetos; e
- Deve ser acessível apenas pela máquina que contém o servidor web.

### Máquina de aplicação contendo um servidor web

- Deve ser utilizada a versão 1.26 do Nginx;
- Deve ser acessível pela internet;
- Deve conter um certificado SSL válido;
- O serviço SSH deve ser acessível pela internet.

### Máquina de banco de dados contendo um Banco de Dados MongoDB

- Deve ser utilizada a versão 7.1 do MongoDB;
- Deve haver uma rotina de backup, enviando o backup para um serviço de armazenamento de objetos; e
- Deve ser acessível apenas pela máquina que contém o servidor web.

## Observações

- O dimensionamento das máquinas é de sua escolha;
- O serviço de armazenamento de objetos é de sua escolha;
- O serviço de certificado SSL é de sua escolha.

## Nota Importante

O objetivo deste desafio é propor soluções com base no seu conhecimento e demonstrar até onde você consegue ir com suas habilidades atuais. **Não se preocupe se encontrar dificuldades**: estamos interessados em entender seu processo de pensamento e como você aborda problemas. Se houver algum ponto desafiador, sinta-se à vontade para trazê-lo para discussão durante a entrevista.

_O desafio acima foi cuidadosamente construído para propósitos de avaliação apenas._
