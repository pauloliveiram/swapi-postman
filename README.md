# Testes na API de "Star Wars" com Postman

## Sobre o projeto

Essa é uma aplicação de testes automatizados em uma API com informações sobre a saga de filmes "Star Wars". Os testes foram aplicados em todos os endpoints da API, cujos resultados são disponibilizados em relatório gerado pelo Allure. 

Além disso, foi desenvolvida uma pipeline no Github Actions para que os testes sejam executados e o relatórios sejam gerados a cada push ou pull request na branch main do repositório.

## Link da API
https://swapi.dev/

## Tecnologias utilizadas

- Postman
- Allure Report
- Github Actions

## Endpoints com testes automatizados

- [GET] Listar todos os filmes (/films)
- [GET] Obter um filme específico (/films/{id})
- [GET] Listar todos os personagens (/people)
- [GET] Obter um personagem específico (/people/{id})
- [GET] Listar todos os planetas (/planets)
- [GET] Obter um planeta específico (/planets/{id})
- [GET] Listar todas as espécies (/species)
- [GET] Obter uma espécie específica (/species/{id})
- [GET] Listar todas as espaçonaves (/starships)
- [GET] Obter uma espaçonave específica (/starships/{id})
- [GET] Listar todos os veículos (/vehicles)
- [GET] Obter um veículo específico (/vehicles/{id})

## Relatório gerado
![image](https://github.com/pauloliveiram/swapi-postman/assets/39312072/cf69b150-f3e1-4e57-8d61-5f4685032f5c)

## Como executar os testes

1) Clonar o repositório
2) Importar o arquivo "collection_postman.json" no Postman
3) Enviar as requisições dos endpoints
   - Ao enviar a requisição, os testes são executados	

# Autor
Paulo Oliveira



