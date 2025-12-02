🌦️ Sistema de Informações Climáticas em Tempo Real — Java

Aplicação simples em Java que consulta a WeatherAPI e exibe informações meteorológicas em tempo real diretamente no terminal.

Este projeto utiliza:

HttpClient para requisições HTTP

WeatherAPI para dados climáticos

org.json para leitura do JSON

Scanner para entrada de dados

Tratamento de erros e formatação limpa no console

🚀 Funcionalidades

Consulta de clima atual digitando o nome da cidade

Exibição de:

Temperatura

Sensação térmica

Condição do tempo

Umidade

Velocidade do vento

Pressão atmosférica

Data e hora da última atualização

Tratativa para cidade não encontrada (code: 1006)

🛠 Tecnologias usadas

Java 17+

HttpClient

WeatherAPI

org.json

Git / GitHub

📌 Como executar

Instale dependências da biblioteca org.json (caso use IDE).

Crie um arquivo api-key.txt na pasta raiz com sua chave da WeatherAPI.

Compile e execute o programa:

javac ProjetoSistemaDeInformacoesClimaticasEmTempoReal.java
java ProjetoSistemaDeInformacoesClimaticasEmTempoReal
