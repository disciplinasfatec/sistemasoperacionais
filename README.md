# Serialização e Desserialização

```sh
# ls -lh
```

![alt text](https://github.com/disciplinasfatec/sistemasoperacionais/blob/main/Passo04.png "image Passo04")

```sh
# cat > arq1.txt
Este é o conteúdo do arquivo arq1.txt
<ctrl D>
# ls -lh
```

![alt text](https://github.com/disciplinasfatec/sistemasoperacionais/blob/main/Passo05.png "image Passo05")

```sh
# cat > arq2.txt
Este é o conteúdo do arquivo arq2.txt
<ctrl d>
# ls -lh
```
#
#
```sh
# cat > arq3.txt
Este é o conteúdo do arquivo arq3.txt
<ctrl d>
# ls -lh
```
#
#
```sh
# ls -lh
```
#
#
-----
tar -> Serializar e de-serializar arquivos
#
#
```sh
# ls -lh
# tar -cvf arquivo.tar arq1.txt arq2.txt arq3.txt
    c -> Create, v -> Verbose e f -> File
# ls -lh
```
#
#
```sh
# cat arquivo.tar
# cat arq1.txt
# cat arq2.txt
# cat arq3.txt
```
#
#
```sh
# ls -lh
# rm arq1.txt arq2.txt arq3.txt
# ls -lh
# tar -xvf arquivo.tar
    x -> eXtract, v -> Verbose e f -> File
```
#
#
```sh
# ls -lh
# cat arq1.txt
# cat arq2.txt
# cat arq3.txt
```
#
#
```sh
# ls -lh
# tar -tf arquivo.tar
    t -> lisT
```
#
#
```sh
# ls -lh
# cat > arq4.txt
Este é o conteúdo do arquivo arq4.txt
<ctrl d>
# ls -lh
```
#
#
```sh
# ls -lh
# tar -rvf arquivo.tar arq4.txt
    r -> append
# tar -tf arquivo.tar
```
#
#
```sh
# ls -lh
# cat arquivo.tar
```
#
#
```sh
# ls -lh
# rm arq4.txt
# ls -lh
# tar -xvf arquivo.tar arq4.txt
```
#
#
```sh
# ls -lh
# cat arq4.txt
```
#
#
```sh
# ls -lh
# tar -cvzf arquivo.tar.gz arq1.txt arq2.txt arq3.txt arq4.txt
ou 
# tar -cvzf arquivo.tgz arq1.txt arq2.txt arq3.txt arq4.txt
    c -> Create, v -> Verbose, z -> Zip (compactar pelo algoritimo gzip) e f -> File
# ls -lh
```
#
#
```sh
# ls -lh
# rm arq1.txt arq2.txt arq3.txt arq4.txt
# ls -lh
```
#
#
```sh
# ls -lh
# tar -xvzf arquivo.tgz
# ls -lh
```
#
#
```sh
# ls -lh
# rm arquivo.*
# ls -lh
```
#
#
```sh
# ls -lh
# rm arq1.txt arq2.txt arq3.txt arq4.txt
# ls -lh
```

