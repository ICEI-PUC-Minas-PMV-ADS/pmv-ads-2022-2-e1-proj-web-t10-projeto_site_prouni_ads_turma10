# Arquitetura da Solução

São apresentados nesta seção os detalhes técnicos da solução e os componentes que integram a mesma, e também o ambiente de hospedagem utilizado.

## Diagrama de componentes

A figura abaixo representa os componentes que fazem parte da solução.

![Logo](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t10-projeto_site_prouni_ads_turma10/blob/main/arquitetura.png)

Figura 1 – Arquitetura da solução

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - É o conjunto dos arquivos HTMS, CSS, Java Script e imagens que formam e possibilitam as funcionalidades da solução.
   - **Local Storage** - Dados armazenados no navegador, por meio do bando de dados baseado em JSON. São eles:    
     - **Comentários** - Registro de comentários, sugestões e opiniões dos usuários.
     - **Preferidas** - Conteúdo selecionado para posterior visualização.
 - **Hospedagem** - Local onde as páginas serão mantidas para acesso do navegador. 


## Hospedagem

O site utiliza a plataforma do Heroku como ambiente de hospedagem do site do projeto. O site é mantido no ambiente da URL: 

https://link_exemplo.herokuapp.com

A publicação do site no Heroku é feita por meio de uma submissão do projeto (push) via git para o repositório remoto que se encontra no endereço: 


https://git.heroku.com/link_exemplo.git
