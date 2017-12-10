# Infraestrutura como Código

![alt tag](https://raw.githubusercontent.com/wiki/helcorin/secdevops/images/iac.jpg)

---

A idéia base por trás de ***IAC*** ou **infraestructure as a code** é desenvolver e configurar a infraestrutura com base em código e ferramentas de automação de ambiente de forma que sua arquitetura possa ser versionada, testada e principlamente ***reproduzida*** sempre que necessário.

O uso dessa abordagem aumenta consideravelmente a velocidade do deploy de sistemas e a eficiência em processos de escalabilidade, esse formato é muito ligado à cultura de sistemas devops e na maioria dos casos possui como base duas características:

***1. Computação em Núvem:***

O uso de cloud computing gera modelos mais escaláveis e maleáveis de arquiteturas, o que possibilita criar e recriar servidores, load balancers volumes e quaisquer outros recursos necessários a partir do uso de Rest Apis e ferramentas de automação, alias a automação é a nossa segunda base.

***2. Automação de Ambientes:***

A segunda característica é a automação usando ferramentas específicas para essa finalidade, a ideia básica por trás da automação é fornecer ferramentas e meios para comunicação e manipulação de recursos, principalmente recursos de cloud computing.

Hoje em dia existem muitas ferramentas de automação e configuração de ambientes criadas para essa finalidade, entre as mais famosos posso citar quatro projetos:

- [Ansible](https://www.ansible.com/)
- [Chef](https://www.chef.io/chef/)
- [Puppet](https://puppet.com/)
- [SaltStack](https://saltstack.com/)
- [CloudFormation](https://aws.amazon.com/pt/cloudformation/)
- [Terraform](https://www.terraform.io/)


### Modelos de serviços em cloud

Quando bem utilizado o conceito de IAC junto a uma plataforma de cloud computing cria um conjunto extremamente eficaz para a construção de arquiteturas ágeis e que atendam às necessidades impostas pelo dinamismo atual dos times de desenvolvimento, existem sertas classificações sobre a maneira como serviços de cloud são entregues aos seus usuários vale a pena um resumo sobre duas dessas classificações, aquelas que estão mais diretamente ligadas a devops:

- ***IAAS ou Infraestruture as a Service:***

Empresas como AWS, Microsoft ou Google e tecnologias como Openstack e Cloudstack se tornaram pioneiras nessa ideia usando um modelo chamado de ***iaas*** ou ***infraestructure as a service*** trata-se da ideia de fornecer plataformas de cloud computing para criação de servidores e serviços de forma dinâmica e escalável, a principal ideia aqui é que o usuário pegue pelos recursos que deseja utilizar. Logo ao inveś de comprar servidores estamos adquirindo processamento, memória e armazenamento sob demanda a idéia é que empresas possam consumir esse recursos abrindo mão dos custos iniciais relacionados a construção de um data center em detrimento de investimentos a serem feitos com base no crescimento da empresa.

- ***SAAS ou software as Service:***

Outro ponto importante é como a nuvem pode entregar valor e ferramentas direto ao desenvolvedor a partir do que chamamos de Saas ou software as a service, o codedeploy é um belo exemplo deste modelo, outro exemplo muito famoso é o Heroku amado por muitos desenvolvedores;


> Todas essas falidades relacionadas a processos de deploy e automação tem em comum o uso de apis, plataformas de Cloud como a AWS e o Google Cloud oferecem um vasto menu de apis entregues como serviços o que perimite o deploy de infra estrutura manipulação de dados auditoria e monitoramento um belo exemplo disso é o lambda capaz de entregar a desenvolvedores poder computacional com a abstenção de toda a parte de hardware e gerenciamento relacionada;


***O uso de cloud compiting resolverá todos os problemas?***

Definitivamente não, entretanto o uso de Cloud sempre deve ser pensado, cada serviço tem seu custo as vezes deveras elevado o que definitivamente deve ser levado em conta antes de qualquer migração ou contratação, além disso existem grandes mudanças na maneira como operar esses recursos e na divisão de responsabilidades, assim como devops o uso de cloud computing demanda estudo e cuidado não se trata de uma bala de prata mas de uma parte importante a ser avaliada capaz de ajudar na evolução do negócio em qualquer tipo de empresa.

---

## Material de Referência:

Existem inumeras referências para consulta sobre esse assunto, no escopo deste material fizemos um overview bem simples mas para aqueles que quiserem se aprofundar um pouco mais na toca do coelho fica as recomendações abaixo:

Este guide sobre terraform explica de forma sucinta porem bem esclarecedora a diferença entre ferramentas de automação e de gerenciamento de configuração, neste caso em específico a escolha é voltada para o terraform, mas vale entender as argumentações e as motivações para essa escolha:

* [A Comprehensive Guide to Terraform](https://blog.gruntwork.io/why-we-use-terraform-and-not-chef-puppet-ansible-saltstack-or-cloudformation-7989dad2865c)

----

**Free Software, Hell Yeah!**