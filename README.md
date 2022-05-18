# Retsurante ADG - Voice Chatbot
Projeto de Chatbot de voz

ReadMe de informações para instalação do Chatbot de voz localmente.


## Pré-Requisitos
* MacOS
* [Python 3 instalado](https://python.org.br/instalacao-mac/)
* Google Chrome

## Observações
Para instalação deste Chatbot é necessário que seja feita algumas observações:
* O arquivo sample.env possui as credenciais de acesso (APIKey e URL) ao Watson Assistant, Speech To Text e Text To Speech
* O arquivo requirements.txt possui as bibliotecas necessárias para instalação do chatbot
* O chatbot rodará localmente na porta 5080 da máquina. Caso seja necessário aterar a porta, a mesma pode ser alterada no arquivo ```app.py``` na linha 123

## Instalação
MacOS

* Fazer download deste repositório em sua máquina local
* Após o download, renomear o arquivo ```sample.env``` para apenas ```.env```
* Executar uma nova janela de Terminal da Pasta clicando com o botão direito sobre a pasta do repositório e clicando em 'Novo Terminal na Pasta'

![image](https://user-images.githubusercontent.com/32220516/169123007-b528bad0-b84e-4a81-8e8a-6bceacd70c9b.png)

* Instalar as bibliotecas necessárias com o comando

```pip install -r requirements.txt```

* Ao finalizar a instalação das bibliotecas, executar o arquivo python utilizando o comando

```python app.py```

* Será exibida uma linha de comando indicando que o chatbot está ativo e pronto para uso

![image](https://user-images.githubusercontent.com/32220516/169126855-84d1b191-9a7a-4ff6-a6ca-b195ae6864b5.png)

* Basta abrir o Google Chrome e digitar a URL ```http://localhost:5080``` (ou outra porta caso tenha sido alterada), e será aberta a página do Chatbot de Voz conforme imagem abaixo

![image](https://user-images.githubusercontent.com/32220516/169128709-1c5d38c5-43a4-4cdc-a86c-c8a121390cc8.png)

* Certifique-se de que o Google Chrome possui autorização de uso do microfone na página aberta
* Para falar, basta clicar no ícone de microfone e clicar novamente para enviar a mensagem de voz



