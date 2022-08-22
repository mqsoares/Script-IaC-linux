<div align='center'>

<h1> Bootcamp Linux Experience - DIO.me </h1>
  
<br>
  
<a href="https://www.linkedin.com/in/mq-soares/">
  <img alt="Miqueias Soares" src="https://img.shields.io/badge/-Miqueias Soares-747d8c?style=flat-square&logo=Linkedin&logoColor=black" />
</a>

<a href="https://twitter.com/mqsoares">
  <img alt="mqSoares" src="https://img.shields.io/badge/-mqsoares-747d8c?style=flat-square&logo=Twitter&logoColor=black" />
</a>

<a href="mailto:mqseraos@gmail.com">
  <img alt="Miqueias Soares" src="https://img.shields.io/badge/-mqseraos@gmail.com-747d8c?style=flat-square&logo=Gmail&logoColor=black" />
</a>

<br>
<br>

<p> Neste projeto criamos um Arquivo de Bash Script onde toda a infraestrutura de usuários, grupos de usuários, diretórios e permissões são criados automaticamente. Assim, podemos fazer reutilizações do script, sempre que precisarmos, basta executar o script.</p>

<br>

<p> Segundo a Red Hat, Infraestrutura como código (IaC) é o gerenciamento e provisionamento da infraestrutura por meio de códigos, em vez de processos manuais. Com a IaC, são criados arquivos de configuração que incluem as especificações da sua infraestrutura, facilitando a edição e a distribuição de configurações.</p>

<br>

</div> 

<h2>iac.sh - Diretórios, Grupos, Usuários e Permissões </h2>
<p>Script para Criar Estrutura de Usuários, Diretórios e Permissões</p>


```
- O dono de todos os diretórios criados será o usuário root;
- Todos os usuários terão permissão total dentro do diretório publico;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios 
  de departamentos que eles não pertencem.
```
