# linux

# Grub

https://qastack.com.br/unix/198003/set-default-kernel-in-grub

Adicione duas linhas ao / etc / default / grub

GRUB_SAVEDEFAULT=true
GRUB_DEFAULT=saved

Faça o sudo update-grub, reinicie, entre no menu do grub e selecione o item de menu ou submenu necessário. A escolha será salva e da próxima vez que o computador for inicializado automaticamente.
