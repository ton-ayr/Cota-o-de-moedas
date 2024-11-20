# Cotação de Moedas :moneybag:

Este é um projeto simples em Python que utiliza a biblioteca `tkinter` para criar uma interface gráfica e a `requests` para requisitar a API [AwesomeAPI](https://docs.awesomeapi.com.br/) 
que vai buscar cotações de moedas em tempo real.

## Funcionalidades

- Busca as cotações das seguintes moedas:
  - Real (BRL)
  - Dólar (USD)
  - Euro (EUR)
  - Bitcoin (BTC)
- Exibe as cotações em uma interface gráfica amigável.

## Pré-requisitos

- Python 3.x instalado no PC;
- IDE com a linguagem instalada;
- Biblioteca `requests`.

É possível instalar a biblioteca `requests` rodando no terminal o seguinte comando:

```bash
pip install requests
```

## Código

O script está estruturado da seguinte forma:

- `pegar_cotacoes`: Função requisita a a API da AwesomeAPI e processa os dados para exibir as cotações filtradas.

- **Interface Gráfica:**
  
  - Criada com tkinter;
  - Contém um botão para atualizar as cotações e um rótulo para exibi-las.

## Melhorias Futuras

- Melhorar o front da interface gráfica;
- Permitir escolha dinâmica das moedas desejadas;
- Função de converter o valor de moedas;
- Criar executável.

