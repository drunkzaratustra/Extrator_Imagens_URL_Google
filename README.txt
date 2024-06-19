Este é um código simples de uso pessoal para extração de URL de imagens de produtos para estoque, utilizado para a alimentação da plataforma Bling.

Bibliotecas:
    openpyxl
    selenium
    webdriver

Esse código irá retornar a primeira imagem do Google Imagens através da CLASS_NAME "YQ4gaf" (médotod: find_element(By.CLASS_NAME, "YQ4gaf").
COm isso, é retornada propriedade <scr> da CLASS_NAME.

input_path = r"<URL>"
output_path = r"<URL>"

