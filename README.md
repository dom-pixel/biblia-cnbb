# ✝ Bíblia versão CNBB 
Bíblia formatada em `JSON`, utilizando a versão CNBB.

# 💥 Motivação
Este projeto tem o objetivo de democratizar o acesso à Bíblia Sagrada em português brasileiro a programadores, desenvolvedores e pessoas interessadas em proclamar o Evangelho e as boas-novas do Reino de Deus por meio da tecnologia. Gostou do projeto? Você pode nos ajudar a ir ainda mais longe, basta fazer uma contribuição via PayPal.

[![Doar](https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TVZ34XA2QYRTW&source=url)

## ❓ Qual a versão contida no projeto?
Atualmente o projeto conta com uma versão da Bíblia Sagrada em Português Brasileiro (pt-BR):
- Conferência Nacional dos Bispos do Brasil (CNBB)

## 💯 Existem planos para a disponibilização de outros formatos e versões?
Sim, o projeto pretende disponilizar mais dois formatos futuramente, sendo eles:
- XML
- SQL

Também estamos trabalhando em outras versões da biblia e criação de uma API para consumo dos arquivos.

### 📂 JSON
O arquivo JSON está codificado em UTF-8 e possue a seguinte estrutura:
```json
[
	{
	"abbrev" : "Abreviação do livro",
	"chapters": 
		[
			["Texto do versículo 1", "Texto do versículo 2", "Texto do versculo 3", "..."],
			["Texto do versículo 1", "Texto do versículo 2", "Texto do versculo 3", "..."],
			["Texto do versículo 1", "Texto do versículo 2", "Texto do versculo 3", "..."]
		],
    "name" : "Nome do livro"
	}
]
```
Os números dos capítulos e versículos podem ser recuperados pelo índice do array.

## 🤖 Como o arquivo foi montado?
A compilação dos arquivos foi obtida por meio do crawling de páginas web. Portanto, é possível que haja pequenos erros de coleta.
Caso veja algum erro, não hesite em contribuir com o projeto!

## 🤔 Há também versões em outros idiomas?
No momento, apenas em português.

## 📃 Como funcionam as licenças e direitos?
Este projeto é distribuído sob a licença GPLv3. As traduções bíblicas deste projeto são de autoria e propriedade intelectual da Conferência Nacional dos Bispos do Brasil (CNBB).

## 💪 Como eu posso ajudar?
Ajude-nos a entregar um conteúdo de qualidade, revisando os códigos e montando estruturas otimizadas. Toda ajuda é bem vinda.

## 🆘 Eu posso fazer uma doação para o projeto?
Sim, você pode! Basta fazer uma doação voluntária por meio do [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TVZ34XA2QYRTW&source=url).

[![Doar](https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=TVZ34XA2QYRTW&source=url)
