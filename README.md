# Transfom data from Excel file to SPSS-SAV Format

SPSS é um software estatístico muito comum em alguns domínios como, por exemplo, Market Research. O sofware possui uma linguagem de script própria onde é possivel ler um arquivo excel e transformá-lo em SAV (formato nativo do SPSS), porém é necessario um considerável esforço de programação.

O objetivo deste código é converter um arquivo Excel com o menor esforço de programação possivel. Para atingir este propósito usaremos um arquivo JSON que servirá de metadata.

Este arquivo metadata ajuda a definir:
* O nome das colunas no arquivo Excel
* O label de cada coluna
* O tipo de dado (Numérico, categórico ou text)
* O tamanho de cada coluna
