Durante este laboratório, aprendi na prática como funciona o conceito de Infraestrutura como Código (IaC) utilizando o serviço AWS CloudFormation.

O principal objetivo foi automatizar a criação de recursos na AWS através de um template YAML, evitando configurações manuais diretamente no console.

Infrastructure as Code é a prática de definir infraestrutura utilizando código ao invés de criar recursos manualmente.

Com isso é possível:

automatizar ambientes;
reduzir erros humanos;
padronizar configurações;
reutilizar infraestrutura facilmente.

Uma Stack no CloudFormation representa um conjunto de recursos AWS criados e gerenciados a partir de um único template.

Ao executar a Stack, a AWS cria automaticamente todos os recursos definidos no arquivo YAML.

Também aprendi que:

ao excluir a Stack, os recursos associados também podem ser removidos;
o CloudFormation gerencia dependências automaticamente;
erros em um recurso podem gerar rollback da Stack.

Security Groups

Portas utilizadas:

22 → SSH
80 → HTTP

Também aprendi a importância de não expor portas desnecessárias publicamente.

Este laboratório ajudou a consolidar conceitos importantes de automação na AWS e mostrou como o CloudFormation pode simplificar o gerenciamento de infraestrutura em ambientes cloud.

Além do conhecimento técnico, também foi importante praticar documentação técnica e organização de projetos utilizando o GitHub.