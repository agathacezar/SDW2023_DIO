# Santender Dev Week 2023 (ETL com Python)

**Contexto:** Eu sou uma ciêntista de dados de uma empresa de viagens, na qual recebi uma tarefa de desenvolver uma solução de envolver os clientes de forma personalizada, quando o mesmo entrar com o seu login no site.

**Condições do Problema:** 
 

1.    Eu recebi uma planilha simples, em formato CSV ('SDW2023.csv'), com uma listade IDs de usuário:

```
IDs dos usuários
1
2
3
4
5
```

2.   Meu trabalho é obter os dados de cada cliente que estão dentro da pasta Usuarios/IDs.

3.   Depois de obter os dados dos clientes, eu vou usar a API do ChatGPT (OpenAI) para gerar uma mensagem de personalizada para os cliente. A mensagem deve ser saudando-o por se conectar no site.

4.  Uma vez que a mensagem para cada cliente esteja pronta, eu vou enviar essas informações de volta para a API, atualizando a lista de "news" de cada usuário.

## **E**xtract

Extraia a lista de IDs de usuário a partir do arquivo CSV. Para cada ID, faça uma requisição para obter os dados do usuário correspondente.

## **T**ransform

Utilize a API do OpenAI GPT-3.5-turbo para gerar uma mensagem de personalizada para cada usuário.

## **L**oad

Atualize a lista de "news" de cada usuário com a nova mensagem gerada.
