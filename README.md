# Challenge Robot Framework

*Desafio do estágio em AWS & AI for Software Quality Engineering da Compass UOL realizado para colocar em prática aprendizados sobre testes automatizados com Robot Framework*

<img width="260" height="160" alt="image" src="https://github.com/user-attachments/assets/b8921687-1a04-41f7-85be-b838c2c3ccde" />

## O que é Restful-Booker API
*É uma API com a finalidade de aprender mais sobre testes de API, ferramentas de teste de API com CRUD e autenticação.*


## O que é Robot Framework?
*É um framework de automação de testes de código aberto, sua sintaxe é amigável e usa palavras-chaves e oferece suporte à extensão por meio de biblioteca em Python, Java e outras linguagens.*

<img width="151" height="151" alt="image" src="https://github.com/user-attachments/assets/a34ff69e-4c89-4571-a74e-8eea4d1095d9" />


## O que é RequestLibrary?
*É uma biblioteca que visa fornecer funcionalidades de teste de API HTTP para GET, POST, PUT etc.*

## O que é Collection Library?
*É uma biblioteca para organizar e reutilizar palavras-chave e variáveis no Robot Framework, funcionando como um conjunto de recursos extras.*

## Variáveis:
- ${base_url}: variável que guarda a base url da API
- ${response}: variável que guarda a resposta (status, json)
- ${bookingid}: variável que guarda o id da reserva criada.
- ${token}: variável que guarda o token de autenticação.

## Como acessar?
- Primeiro clone o repositório:
```
git clone git@github.com:Isabela-Silva/Challenge-Robot-Framework-CompassUOL.git
```
- Depois acesse a pasta:
```
cd Challenge-Robot-Framework-CompassUOL
```
- Crie e ative o ambiente Conda:
```
conda env create -f environment.yml
```
- Ative o ambiente:
```
conda activate base
```
- Execute o teste:
```
robot MeuTeste.robot
```


## Ultimo resultado:

*- Todos os testes passaram*

<img width="491" height="292" alt="image" src="https://github.com/user-attachments/assets/0a036d06-65bc-451b-8e8a-42dafdc2ddc7" />


## Refências Bibliográficas:

ROBOT FRAMEWORK, disponível em: https://robotframework.org/.

REQUESTLIBRARY, disponível em: https://docs.robotframework.org/docs/different_libraries/requests

RESTFUL-BOOKER, disponível em: https://restful-booker.herokuapp.com/
