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

##Ferramentas:
* Bootstrap
* Javascript / JQuery

##Estrutura Website:
* Barra de Navegação superior sempre visível - botões de __Serviço__, __Sobre__ e __Contato__
* __Inicial__
  - Logo centralizada
  - Nome da Empresa + Engenharia de Computação
  - Imagem de fundo desfocada
  - Botão para _Facebook_ e _Email_ (mailto)
* Seção __Serviço__
  - Resumo serviços e capacidades técnicas
  - Portifólio -  abre em uma tela sobreposta com transparência - projetos em grade de ícones lado a lado
  - Parceiros - igual portifólio
* Seção __Sobre__
  - Sobre nossa empresa / Diretorias
  - Membros - igual portifólio
  - História
* Seção __Contato__
  - Endereço detalhado + link Maps
  - Email / Facebook
  - GitHub
  - Trabalhe Conosco - acompanhe divulgação do processo seletivo no Facebook
