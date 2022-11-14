## UbuntuTermux

Como instalar:

Você precisa de um telefone Android com CPU de 64 bits, kernel Android de 64 bits e Termux de 64 bits (ou universal) instalado. Não use a versão Play Store do Termux, ela está obsoleta! Além disso, o Android 12 provavelmente não funcionará devido ao novo processo que mata "melhorias".

Copie o arquivo baixado para o seu dispositivo, usarei a pasta Downloads neste guia.

Certifique-se de que seus pacotes estejam atualizados com "pkg update" e "pkg upgrade"

Instale o proot-distro no Termux com "pkg install proot-distro"

Instale a versão base do Ubuntu proot.distro com "proot-distro install ubuntu"

Use o comando "termux-setup-storage" para acessar a memória interna do seu telefone (você também precisa dar permissão no Android).

Use o "proot-distro restore ~/storage/downloads/filename.gz" (obviamente substitua o nome do arquivo pelo nome do arquivo baixado) para instalar a versão baixada do Ubuntu proot-distro. (AVISO: isso excluirá sua instalação anterior do Ubuntu Se você tiver um!)
