# Resolução desafio: Criando um Ecossistema Hadoop Totalmente Gerenciado com Google Cloud Dataproc

<br>

Repositório criado para o desafio "Criando um Ecossistema Hadoop Totalmente Gerenciado com Google Cloud Dataproc", da Digital Innovation One.

Este desafio consiste em utilizar o Google Cloud Platform para criar um cluster e processar um job, utilizando um arquivo cedido pelo ministrante do curso. O resultado do processo gera um arquivo que está incluso neste repositório.

<br>

---

<br>

### Etapas do Desafio

1. Criar um bucket no Cloud Storage
1. Fazer o upload dos arquivos ```contador.py``` e ```livro.txt``` para o bucket criado
1. Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando ```gs://{SEU_BUCKET}/contador.py```
1. O Job irá gerar uma pasta no bucket chamada ```resultado```. Dentro dessa pasta o arquivo ```part-00000``` irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.

### Entrega do Resultado

1. Criar um repositório no GitHub.
2. Criar um arquivo chamado ```resultado.txt```. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.
3. Inserir os arquivo ```resultado.txt``` e ```part-00000``` no repositório e informar na plataforma da Digital Innovation One.

<br>

---