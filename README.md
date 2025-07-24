# Download de Vídeos e Músicas do YouTube

## Requisitos

Para usar este projeto, você precisa ter o **Python 3** e o **pip** instalados em sua máquina.

No Ubuntu, ou Windows com WSL você pode instalar executando:

```bash
sudo apt update
sudo apt install python3 python3-pip -y
```

## Instalação

1. Faça o clone do repositório:
```bash
git clone https://github.com/tulioanesio/pytube.git
```
2. Acesse a pasta do projeto:
```bash
cd pytube
```
3. Instale a dependência necessária:
```bash
pip install pytubefix
```
## Como usar

Execute o script principal no terminal:
```bash
python index.py
```
Ao rodar, cole o link do vídeo do YouTube que deseja baixar e o download será realizado na pasta raiz do projeto.

## Observações

* Certifique-se de que você está conectado à internet.

* O vídeo será salvo no formato padrão e qualidade disponível.

* A dependência pytubefix ajuda a corrigir erros relacionados à API do YouTube.
