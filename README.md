# Distro ZorinOS
<img src="https://assets.zorincdn.com/images/computer-mockups/old-computer/1.png" width="400">
Aqui eu vou colocar tudo que estou que estou aprendendo sobre o kernel, no momento tô usando a <strong>Distro ZorinOS</strong>,
mas se aplica em qualquer outra distribuição baseada no <em>UBUNTU 20.04 LTS</em>
e também algumas soluções de alguns problemas que ocorreram comigo. :)

# Problema com saída de audio e microfone;
Bom, ao conectar meu heaset no notebook, ele foi reconhecido ( que bom kkkk ) porém o audio não era reproduzido<br>
a soluçao que encontrei foi instalar "pavucontrol" usando o seguinte comando:<br>
<ol>
	<li><pre>sudo apt install pulseaudio</pre></li>
	<li><pre>sudo apt install pavucontrol</pre></li>
</ol>
	
        
Reinicie o sistema e abra o pavucontrol:<br>
        abra o terminal e digite<br>
        <pre>pavucontrol</pre><hr>
        
# Instalando outra versão do Python
a) Instalar as dependências

<pre>sudo apt install build-essential zlib1g-dev libjpeg-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev sqlite3 liblzma-dev curl libbz2-dev</pre>

b) <a href="https://www.python.org/downloads/">Baixar</a> o fonte do Python


c) Descompactar o Python baixado

d) Com o terminal aberto no diretório do fonte executar:

	./configure --enable-optimizations --with-ensurepip=install

e) Compilar com o comando:

	make -j 2

f) Instalar com o comando:

	sudo make altinstall
	
g) Verifique se foi instalado com o comando:

	python3.x --version

	pip3.x --version
	
 # Ver a versão do kernel<br>
 Com o terminal aberto digite o seguinte comando:
 	<pre>uname -r</pre>

# Comandos cp e mv – Como copiar e mover arquivos no Linux
<h3>Comando cp</h3>
Permite copiar arquivos ou diretórios para outro local.
Se o destino fornecido for o nome de um diretório existente, os arquivos serão copiados para esse diretório, com o mesmo nome. Caso indiquemos um nome de arquivo no caminho de destino, o arquivo de origem será copiado e essa cópia renomeada também.
<h4>Sintaxe</h4>
	<pre>$ cp [opçoões] arquivos_de_origem local_de_destino</pre>

<h4>Opções mais comuns</h4>
<strong>-i, –interactive</strong><br>

Pergunta se desejamos sobrescrever um arquivo de destino já existente.<br>

<strong>-l, –link</strong><br>
Cria hard links para os arquivos em vez de copiá-los.<br>

<strong>-n, –no-clobber</strong><br>
Não sobrescrever um arquivo já existente<br>

<strong>-p</strong><br>
Preserva as permissões originais do arquivo, incluindo proprietário, grupo, stuid, setgid, tempos da última modificação e acesso.<br>

<strong>-r, -R, –recursive</strong><br>
Copia diretórios de forma recursiva.<br>

<strong>-s, –symbolic-link</strong><br>
Cria links simbólicos (symlinks) para os arquivos em vez de copiá-los<br>

<strong>-u, –update</strong><br>
Copia apenas quando os arquivos de origem forem mais novos que os de destino, ou quando os arquivos de destino estiverem faltando.<br>

<strong>-v, –verbose</strong><br>
Modo verboso; explica o que está sendo feito no momento.<br>

<strong>–help</strong><br>
Mostra a ajuda básica do comando e sai.<br>

<strong>–version</strong><br>
Mostra informações sobre a versão do comando e sai.<br>
# O DE MOVER EU TÔ COM PREGUIÇA DE COLOCAR AGORA KKKKKKKKKKKK
