# Coin Conversor Service

Projeto desenvolvido como estudo de integração de APIs REST utilizando Python e a biblioteca `requests`. Este projeto faz parte do curso da **PycodeBR**.

##  Objetivo

Realizar a consulta e conversão de valores entre moedas utilizando a API da [AwesomeAPI](https://docs.awesomeapi.com.br/api-de-moedas).

##  Estrutura do Projeto

- **clients.py**: Contém a classe `CoinConversorService`, responsável pela comunicação com a API.
- **main.py**: Arquivo principal que instancia o serviço e executa uma conversão de exemplo.

##  Tecnologias Utilizadas

- Python 3.x
- Biblioteca `requests`

##  Como Executar

1. Clone o repositório ou copie os arquivos `clients.py` e `main.py`.
2. Instale as dependências:
   ```bash
   pip install requests

## Execute o projeto

```bash
python main.py
```

##  Exemplo de Uso

```bash
from clients import CoinConversorService

client = CoinConversorService()
conversion = client.converter('BTC', 'USD')

print(conversion)
```

##  Resultado Esperado

Valor da conversão entre as moedas especificadas (exemplo: preço do Bitcoin em dólares americanos).