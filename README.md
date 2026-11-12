# FRONT
aula 11/11/26

PERSISTÊNCIA DE DADOS NO NAVEGAGOR 

Local Storage , Session Storage e Indexddb.

session-> referente a guia , funciona de forma identica ao localstorege, mas os dados duram apenas enquanto a aba estiver aberta.
dados:5-10mb



local -> fica no seu hd , armazena dados que persistem mesmo após o navegador ser fechado. 
capacidade:5-10mb 
dados: apenas strings ( json.stringify e json.parse)
api: síncrona 

indexdDB
o banco de dados do navegador, banco de dados no sql completo e transacional no navegador.
api: assicrona
dados: quase todo 
estrutura: permite criar multiplos dados,
ideal para: aplicação offline(pwas )
