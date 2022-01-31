
Este é um script simples para pesquisar algumas informações do sistema.

#!/bin/bash

clear
df -h >> inf-sistema.txt
free -h >> inf-sistema.txt
lscpu >> inf-sistema.txt
lspci >> inf-sistema.txt

