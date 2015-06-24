 ## Compilações - parte 04
 

 #*****Gettext*****
 -------------------------------

 ------------------------------
 - descompactando : tar -xJf arquivo.tar.xz


  [1] Preparando para compilação
      - cd gettext-tools
      - EMACS="no" ./configure --prefix=/tools --disable-shared
  
  [2] Compilando apenas alguns pacotes do Gettext libraries
      -make -C gnulib-lib
      -make -C intl pluralx.c
      -make -C src msgfmt
      -make -C src msgmerge
      -make -C src xgettext
  
  [3]Install the msgfmt, msgmerge and xgettext programs:
      -cp -v src/{msgfmt,msgmerge,xgettext} /tools/bin
    


#*****Grep*****
-------------------------
O pacote grep contém programas para pesquisar através
de arquivos.
-------------------------
-descompactando : tar -xJf arquivo.tar.xz
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 


#*****Gzip*****
-------------------------


-------------------------
-descompactando : tar -xJf arquivo.tar.xz
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 



#*****M4*****
-------------------------

-------------------------
- descompactando : tar -xjf arquivo.tar.bz2
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 


#*****Make*****
-------------------------

-------------------------
- descompactando : tar -xjf arquivo.tar.bz2
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 


#*****Patch*****
-------------------------
O pacote de patch contém um programa para modificar 
ou criar arquivos aplicando um arquivo "patch" tipicamente 
criado pelo programa diff .
-------------------------
- descompactando : tar -xjf arquivo.tar.bz2
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 


#*****Perl*****
-------------------------
O pacote Perl contém a extração e relatórios 
prática de Idioma 
-------------------------
- descompactando : tar -xjf arquivo.tar.bz2
 
  [1] Preparando para compilação
  [2] make

  -não é necessária a instalação de todos os pacotes
  perl nessa etapa


#*****Sed*****
-------------------------

-------------------------
- descompactando : tar -xjf arquivo.tar.bz2
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 


#*****TAR*****
-------------------------

-------------------------
- descompactando : tar -xjf arquivo.tar.bz2
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 

  #*****Texinfo*****
-------------------------

-------------------------
- descompactando : tar -xJf arquivo.tar.xz
 
  [1] Preparando para compilação
  [2] make
  [3] make check
  [4] make install 


 #*****Util-linux*****
-------------------------

-------------------------
- descompactando : tar -xJf arquivo.tar.xz
 
  [1] Preparando para compilação
  [2] make
  [3] make install 

 #*****Xz*****
-------------------------

-------------------------
- descompactando : tar -xJf arquivo.tar.xz
 
  [1] Preparando para compilação
  [2] make
  [3] make install 
