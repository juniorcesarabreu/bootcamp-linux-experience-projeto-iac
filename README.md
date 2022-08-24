# Arquivo de configuração do Servidor

Infraestrutura como codigo

Esse arquivo automatiza:
- criação de diretórios
	+ publico
	+ adm
	+ ven
	+ sec
- criação de grupos de usuários
	+ GRP_ADM
	+ GRP_VEN
	+ GRP_SEC
- criação de usuários
	+ GRP_ADM
		+ carlos
		+ maria
		+ joao
	+ GRP_VEN
		+ debora
		+ sebastiana
		+ roberto
	+ GRP_SEC
		+ josefina
		+ amanda
		+ rogerio
- configuração de permissões de leitura, escrita e execução
	+ `root` é o dono de todos os diretórios
	+ todos tem permissão total ao diretório `publico`
	+ cada usuário só tem acesso ao diretório do seu grupo
	+ cada usuário tem permissão total no dirretório do seu grupo
