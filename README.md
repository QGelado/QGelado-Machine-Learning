# QGelado - Aprendizado de máquina 🤖

## Sobre o projeto ✒️

O projeto busca realizar uma análise de preços dos produtos em estoque no sistema. A ideia principal é fazer uma requisição ao banco de dados para retornar todos os sorvetes em estoque na loja. Após a coleta dos dados via API, o script irá buscar na internet os preços dos produtos pesquisados. Em seguida, será calculada uma média geral dos preços. Por fim, será gerado um arquivo .csv e haverá uma análise mais aprofundada dos dados com as bibliotecas sklearn e matplotlib.

Esses dados serão muito úteis para a loja física, pois proporcionarão automaticamente aos interessados informações sobre os preços dos concorrentes, facilitando a tomada de decisão na definição do preço dos produtos.

## Instalação 🗒️

<p  'align= justify'>
Para rodar o projeto tenha o <a href="https://www.python.org/downloads/" target="_blank">Python</a> instalado na sua máquina. Depois, não esqueça de baixar todas as bibliotecas necessárias para executar o projeto. 
Basta baixar o arquivo 'requirements' do repositório e executar o comando:
</p>

``` 
pip install -r requirements.txt
```

<p  'align= justify'>
Também não esqueça de substituir a rota da API dentro do código: 
  
```
response = requests.get("QGELADO_URL_API/sorvete-padrao")
```

</p>

<h6 align='right'>Feito com ❤️ por <a href="https://github.com/QGelado" target="_blank">QGelado</a></h6> 
