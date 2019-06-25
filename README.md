
# Vendas-facil + Docker!

Imagem docker com alpine e instalado manualmente o java e o tomcat. Embutido na imagem docker o .war da api [Vendas-Fácil](https://github.com/brunocarvalho7/Vendas-Facil-AWS) 

## 1) Construir a imagem

> docker build -t brunocarvalho287/vendas-facil .

## 2) Executar a imagem

> docker run -it -p 8080:8080 brunocarvalho287/vendas-facil

A api ficará disponivel em [http://localhost:8080/vendas-facil](http://localhost:8080/vendas-facil)

# Baixar do [Docker hub](https://hub.docker.com/r/brunocarvalho287/vendas-facil-github)

Realizar o download da imagem
> docker pull brunocarvalho287/vendas-facil-github

Executar a imagem, mapeando a porta 8080
> docker run -it -p 8080:8080 brunocarvalho287/vendas-facil-github

A api ficará disponivel em [http://localhost:8080/vendas-facil](http://localhost:8080/vendas-facil)

