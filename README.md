# Esquema conceitual para um contexto de oficina mecânica

**Projeto proposto no Bootcamp [Heineken - Inteligência Artificial Aplicada a Dados com Copilot](https://web.dio.me/track/coding-the-future-heineken-ia-para-analise-de-dados) na plataforma [DIO](https://www.dio.me/).**


<ins>**Descrição do Desafio**</ins>

*"Modelamos juntos um contexto limitado de e-commerce. Agora é a sua vez, você pode escolher uma ferramenta de modelagem para realizar o desafio. Contudo, fique atento! Caso opte por uma variação do modelo de relacionamento de entidade, como nas ferramentas Mysql Workbench ou DBDesigner será preciso especificar como PK e FKs corretamente. Apesar desse conceito não ser utilizado na modelagem conceitual exploramos brevemente suas definições. Sendo assim, seu empregável será o conceito conceitual para o cenário de E-commerce."*

*Instrutora: Juliana Mascarenhas*

<ins>**Objetivo:**</ins>

Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

<ins> **Narrativa:** </ins>

+ Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
+ Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
+ Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
+ A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
+ O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
+ A mesma equipe avalia e executa os serviços
+ Os mecânicos possuem código, nome, endereço e especialidade
+ Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

# Ferramenta utilizada
+ MySQL WorkBench

# Resultado do Projeto
![Oficina Mecânica](https://github.com/user-attachments/assets/d50a7cff-575f-43a7-9d97-942b0060d861)
