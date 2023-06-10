FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/pablowilliam/instaladordeploy.git && sudo chmod -R 777 ./nstaladordeploy && cd instaladordeploy && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf instaladordeploy && git clone https://github.com/pablowilliam/instaladordeploy.git && sudo chmod -R 777 ./instaladordeploy && cd instaladordeploy && sudo ./install_instancia
```

