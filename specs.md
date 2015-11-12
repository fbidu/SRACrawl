# SRA Crawler

## Crawler inicial
1. Buscar dados de RNA Seq
2. A principio só de humano
3. NÃO de cultura de células - Como isso é específicado?
4. Puxar todos os metadados - descrição, tamanho dos reads, etc
5. Modelar o banco para os metadados

## Downloads
1. Fazer o download automatizado
2. Converter os arquivos .sra para .fastq usando o fastqdump do SRA Toolkit

## Montagem
1. Depois vem a parte de montagem
2. A principio vai ser feita no trinity
3. Da montagem, fazer um BlastX contra um banco de dados de vírus 
4. O banco vai vir do NCBI
7. Fazer um parser dos resultados do BlastX para verificar quais contigues bateram com as proteínas virais
8. No final vou ter vários contigues e vou saber o vírus mais próximo que dá match com ele

## Filogenia
