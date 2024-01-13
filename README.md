# Desafio Criando um Ransomware com Python

  Neste desafio cria-se dois arquivos em Python, um codificador (encrypter.py) e um decodificador (decrypter.py).
  Para testar, usa-se um arquivo na extesão TXT (teste.txt)

## 🛠 Ferramentas:
- Python

## Entendendo o codificador (encrypter.py)

  Este encriptador faz as seguintes etapas:
  
  * abre o arquivo alvo
  * lê o conteúdo do arquivo alvo
  * codifica o conteúdo com base em uma chave de 16 caracteres usando o padrão AES
  * salva o conteúdo encriptado em outro arquivo
  * exclui o arquivo original

  ## Entendendo o decodificador (decrypter.py)

  Este desencriptador faz as seguintes etapas:
  
  * abre o arquivo encriptado
  * lê o conteúdo do arquivo encriptado
  * decodifica o conteúdo com base na chave de 16 caracteres do arquivo encriptador
  * salva o conteúdo desencriptado em um arquivo, voltando ao original
  * exclui o arquivo encriptado
