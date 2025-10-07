pwd: Mostra aonde estou

cd: Mudar Diretorio, mover pelo sistema de arquivos

. (diretório atual): Este é o diretório em que você está atualmente.

.. (diretório anterior): Leva você para o diretório acima do seu atual.

~ (diretório home): Este diretório padrão é o seu “diretório home”, como /home/pete.

-  (diretório anterior): Isso o levará para o diretório anterior onde você estava.

cd .

cd ..

cd ~

cd -

ls (Listar Diretórios)
 
ls é uma ferramenta bastante útil; também mostra informações detalhadas sobre os arquivos e diretórios que você está visualizando.

# Além disso, observe que nem todos os arquivos em um diretório serão visíveis. Nomes de arquivos que começam com . estão ocultos. Você pode visualizá-los, no entanto, com o comando ls e passar a flag -a para ele (a para all).

ls -a

# Existe também mais uma flag útil do ls, -l para long. Isso mostrará informações detalhadas, começando da esquerda: permissões de arquivo, número de links, nome do proprietário, grupo do proprietário, tamanho do arquivo, carimbo de data/hora da última modificação e nome do arquivo/diretório.
ls -l


# Vamos aprender a criar alguns arquivos. Uma maneira muito simples é usar o comando touch. touch permite criar novos arquivos vazios.

touch mysuperduperfile

E pronto, novo arquivo!

touch também é usado para alterar os carimbos de data/hora em arquivos e diretórios existentes. Experimente: faça um ls -l em um arquivo e anote o carimbo de data/hora, depois touch esse arquivo, e ele atualizará o carimbo de data/hora.

