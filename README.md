# IESB-Chatbot-RestauranteADG
Repositório do Trabalho Final de Computação Cognitiva II

## Observações
Este chatbot roda localmente, sendo necessário atenção a algumas informações antes do processo de instalação do mesmo para rodar:
- O arquivo .env já encontra-se com as devidas APIKeys e URLs de acesso ao Watson Assistant, Speech To Text e Text To Speech.
- O arquivo requirements.txt contém as bibliotecas necessárias para instalar na máquina a se utilizar o Chatbot.
- O Chatbot está configurado para rodar localmente na porta 5080. Caso seja necessário, a porta pode ser alterada no arquivo 'app.py' linha 123.

## Pré-Requisitos
- MacOS
- Python 3 - https://python.org.br/instalacao-mac/
- Google Chrome

## Instruções para instalação
### MacOS
- Para instalação do chatbot é necessário abrir uma Nova Janela de Terminal na Pasta do projeto conforme imagem abaixo:

![image](https://user-images.githubusercontent.com/32220516/169116445-ce38fa0c-562b-4c72-aeb0-25b9ab52fb42.png)

- Após aberta a janela do Terminal basta instalar as bibliotecas digitando o comando

```pip install -r requirements.txt```

- Após instaladas as bibliotceas corretamente, basta executar o arquivo python digitando o comando

```python app.py```

- Ao executar o arquivo ```app.py```, será exibida uma linha no Terminal indicando que o assistente está funcionando conforme imagem abaixo:

![image](https://user-images.githubusercontent.com/32220516/169118273-0522f366-ba3a-4746-9d83-10cad3b95178.png)

- Basta abrir o Google Chrome e digitar a URL ```http://localhost:5080``` que será aberto o chat de voz do Restaurante ADG.

![image](https://user-images.githubusercontent.com/32220516/169118617-ee43ad8a-866d-4d95-925f-e5315d8b5e53.png)

- Certifique-se de que o Google Chrome tem permissão de uso do microfone para utilização do Chatbot.
- Para falar, basta clicar no botão de microfone e ao finalizar clique novamente para enviar.
