# Vendas-facil + Docker!

Imagem docker com alpine e instalado manualmente o java e o tomcat. Embutido na imagem docker o .war da api [Vendas-Fácil](https://github.com/brunocarvalho7/Vendas-Facil-AWS) 

## 1) Construir a imagem

> docker build -t brunocarvalho287/alpine-tomcat

## 2) Executar a imagem

> docker run -it -p 8080:8080 brunocarvalho287/vendas-facil

A api ficará disponivel em [http://localhost:8080/vendas-facil](http://localhost:8080/vendas-facil)

