#Struct Website

**[struct.unb.br](http://struct.unb.br) - Version 2.0 - 2016**

**Struct Computer Engineering, University of Brasilia**

## Guia Básico Git

###Configuração prévia:
* Instale o Git no seu computador
* Clone o repositório:
```
git clone https://github.com/StructCE/website.git
````
* Dê _Fork_ no repositório

###_Branches_ (Ramos):
* _Branches_ são caminhos que você pode criar no código
* Git permite mesclar ramos
* Basicamente: se você quer criar uma nova funcionalidade, crie em um novo ramo - pois esta nova funcionalidade ainda não foi aprovada pelo resto da equipe. Assim você pode trabalhar na nova ideia de forma que as funcionalidades antigas permançam intactas em um _branch_ separado. Se sua implementação for aprovada, será feito um _merge_ do seu ramo com o original (_master_) para que ele receba a nova funcionalidade.

Para verificar a lista de ramos e o ramo atual que você está trabalhando, execute:
```
git branch
```

Para criar um Branch e já começar a usá-lo:
```
git branch [nome_do_branch]
git checkout [nome_do_branch]
```
ou resumidamente:
```
git checkout -b [nome_do_branch]
```

###_Merge_
Um dos membros da equipe ficará responsável pelo _merge_
* Funcionalidade são separadas em Branches de cada um e serão _merged_ com o _master branch_


## Telas do Website (definidas na reunião Web 09/09/16):
