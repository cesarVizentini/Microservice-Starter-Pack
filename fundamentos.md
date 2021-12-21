# Fundamentos

## O que são Microsserviços

Microservice é um estilo arquitetural que estrutura uma aplicação em uma coleção de serviços independentes e especializados que se comunicam através de APIs.

### Características

* Altamente sustentável e testável
* Possui baixo acoplamento
* Permite implantação e escalabilidade individuais dos serviços

### Vantagens

* Agilidade e Organização

    Normalmente, equipes diferentes ficam encarregadas de cada microsserviço e isso permite uma grande organização dentro do processo de desenvolvimento e maior agilidade de entrega dado que cada equipe está totalmente focada em seu único microsserviço.

* Escalabilidade Flexível

    O baixo acomplamento entre cada serviço permite que eles sejam escalados de forma independente e cada um a sua demanda, o que, entre outras coisas, diminui muito os custos com infraestrutura.

* Fácil Implantação

    As implantações são facilitadas já que o desligamento de um serviço não implica retirar do ar toda a aplicação, o que é muito bom na hora de fazer atualizações

* Aplicação Poliglota

    O fato da aplicação estar divida em diversos serviços possibilita que cada um deles possa utilizar a linguagem de programação que melhor atenda as suas necessidades. O mesmo vale para a base de dados, já que frequentemente cada microsserviço possui o seu próprio banco de dados.

* Resiliência

    Em um sistema monolítico frequentemente uma falha pode comprometer todas as funcionalidades da aplicação, já nos microsserviços esse impacto é extremamente diminuído, pois se um serviço cai, ele cai sozinho, e mesmo no caso em que esse serviço era essencial para o funcionamento da algum outro isso não impacta a aplicação como um todo.

### Desafios

* Complexidade

    A descentralização de um sistema também possui seus desafios. O mais evidente deles é o aumento de complexidade em praticamente todas as etapas de gestão de projeto, pois a empresa passa agora a gerenciar vários mini sistemas e suas centenas de integrações entre si.

* Monitoramento Robusto

    O monitoramento de uma aplicação arquitetada em microsserviços precisa ser extremamente robusto e bem estruturado, pois, cada serviço e cada integração está sujeito a algum erro e se o seu monitoramento não estiver suficientemente bem organizado torna-se praticamente impossível rastrear falhas.

* Equipe

    A cultura DevOps é imprescindível dentro da sua equipe quando se trata de microsserviços. Com o workflow extremamente veloz de entrega e manutenção constante dos serviços, a falta de uma equipe com cultura e ideiais bem alinhados ao DevOps pode ser o suficiente para acabar com um projeto.

### Equívocos

### Concepção da Arquitetura

* Quando usar
* Quando não usar

### Comunicação entre os Microservices

* Síncrona
* Assíncrona
* Transferência de Estado
* Por base de dados

### Base de Dados por Microservice

* Teorema CAP
* Consistência Eventual
* Transação DistribuÍda

### Testing