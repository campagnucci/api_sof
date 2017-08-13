# Explorando as despesas da cidade de São Paulo

Este é um tutorial de primeiros passos para acessar a execução orçamentária do município usando Python e a biblioteca de análise de dados Pandas - muito bem documentada [aqui](https://pandas.pydata.org/pandas-docs/stable/)

## O que é o SOF?

O SOF é o Sistema de Execução Orçamentária da Prefeitura de São Paulo. Todas as despesas realizadas pelos órgãos e entidades municipais são cadastradas nesse sistema, de acordo com códigos padronizados no orçamento.

A Secretaria Municipal da Fazenda de São Paulo mantém uma API para publicação diária das despesas, com informações detalhadas sobre empenhos, contratos e fornecedores, com a série histórica disponível a partir de 2003. É o registro orçamentário mais detalhado possível da cidade, pois as [bases de dados disponíveis](http://orcamento.sf.prefeitura.sp.gov.br/orcamento/execucao.html) no Portal de Dados Abertos têm como máximo de granularidade os chamados "Projeto-Atividade" do Orçamento.

## Documentação de apoio

Um manual detalhado sobre o funcionamento da API pode ser acessado [aqui](https://api.prodam.sp.gov.br/store/site/themes/fancy/templates/api/documentation/download.jag?tenant=null&resourceUrl=/registry/resource/_system/governance/apimgt/applicationdata/provider/admin/SOF/v2.1.0/documentation/files/MANUAL_SOF_API.pdf) 

Também há um [glossário](http://orcamento.sf.prefeitura.sp.gov.br/orcamento/uploads/glossario.pdf) sobre os principais conceitos orçamentários e um manual [introdutório](https://www.paulofreire.org/images/pdfs/livros/Cadernos_Formacao_Planejamento_Orcamento.pdf) para formação sobre o tema do Orçamento.


