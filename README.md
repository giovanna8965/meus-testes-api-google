# meus-testes-api-google
Repositório destinado ao estudo de integração de APIs. Contém arquivos de exportação do Postman com exemplos de uso da Geocoding API do Google e da API ViaCEP. 

# 🚀 Testes de API REST com Postman

Este repositório contém coleções de testes realizadas no Postman para estudar a integração e o funcionamento de APIs públicas. O foco principal foi aprender a manipular métodos HTTP, parâmetros de consulta (Query Params) e chaves de autenticação.

## 🛠️ APIs Testadas

1.  **ViaCEP**: Consulta de endereços brasileiros através do CEP.
    * **Método**: GET
    * **Endpoint**: `https://viacep.com.br/ws/{CEP}/json/`
2.  **Google Maps (Geocoding API)**: Conversão de endereços de texto em coordenadas geográficas (latitude e longitude).
    * **Método**: GET
    * **Endpoint**: `https://maps.googleapis.com/maps/api/geocode/json`

## 📁 Conteúdo do Repositório

* `REST API basics- CRUD, test & variable.postman_collection.json`: Arquivo de exportação que contém todas as requisições configuradas.

## 🚀 Como usar este projeto

1.  Faça o download do arquivo `.json` presente neste repositório.
2.  Abra o seu **Postman**.
3.  Clique no botão **Import** e selecione o arquivo baixado.
4.  **Nota sobre a Google API**: Para que a requisição do Google Maps funcione, você deve inserir sua própria `API Key` no campo `key` dentro da aba **Params**.

## 🧠 Aprendizados
* Configuração de **Query Params** (`address`, `key`).
* Tratamento de erros comuns como `400 Bad Request` (parâmetros ausentes ou mal escritos).
* Exportação e documentação de coleções para compartilhamento via GitHub.
