# Linux-ZorinOS
Aqui eu vou colocar tudo que estou que estou aprendendo sobre o kernel, no momento tô usando a Distro ZorinOS e também algumas soluções de alguns problemas que ocorreram comigo. :)

# Problema com saída de audio e microfone;
Bom, ao conectar meu heaset no notebook, ele foi reconhecido ( que bom kkkk ) porém o audio não era reproduzido<br>
a soluçao que encontrei foi instalar "pavucontrol" usando o seguinte comando:<br>
        sudo apt install pulseaudio<br>
        sudo apt install pavucontrol<br>
Reinicie o sistema e abra o pavucontrol:<br>
        abra o terminal e digite<br>
        pavucontrol<hr>
        
# Instalando outra versão do Python
a) Instalar as dependências

sudo apt install build-essential zlib1g-dev libjpeg-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev sqlite3 liblzma-dev curl libbz2-dev

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
