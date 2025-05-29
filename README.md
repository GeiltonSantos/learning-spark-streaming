# Introdução

# Pré requisitos
learning-sparkśtreaming
Uso do **netcat**

# O exemplo base

# Referências


[Documentação Spark Streaming](https://spark.apache.org/docs/latest/streaming-programming-guide.html)
[Strutured Streaming](https://spark.apache.org/streaming/)
[Documentação Strutured Streaming](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)
[Exemplos Spark Streaming Strutured](https://github.com/apache/spark/tree/v3.5.4/examples/src/main/python/sql/streaming)
[Livro: Stream Processing with Apache Spark](https://www.amazon.com.br/Stream-Processing-Apache-Francois-Garillot/dp/1491944242)


# Ideia de projeto

Usar a [API de cotações](https://docs.awesomeapi.com.br/) para junto do spark streaming fazer requisiçoes de moedas que serão postadas no socket.
Exemplo: https://economia.awesomeapi.com.br/json/last/USD-BRL

```json

{
    "USDBRL": {
        "code": "USD",
        "codein": "BRL",
        "name": "Dólar Americano/Real Brasileiro",
        "high": "6.1834",
        "low": "6.1813",
        "varBid": "-0.0015",
        "pctChange": "-0.02",
        "bid": "6.1808",
        "ask": "6.1818",
        "timestamp": "1735252202",
        "create_date": "2024-12-26 19:30:02"''
    }
}

```