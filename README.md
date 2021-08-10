# Linux-ZorinOS
Aqui eu vou colocar tudo que estou que estou aprendendo sobre o kernel, no momento tô usando a Distro ZorinOS e também algumas soluções de alguns problemas que ocorreram comigo. :)

# Problema com saída de audio e microfone;
bom, ao conectar meu heaset no notebook, ele foi reconhecido ( que bom kkkk ) porém o audio não era reproduzido
a soluçao que encontrei foi instalar "pavucontrol" usando o seguinte comando:
        sudo apt install pulseaudio
        sudo apt install pavucontrol
Reinicie o sistema e abra o pavucontrol:
        abra o terminal e digite
        pavucontrol
