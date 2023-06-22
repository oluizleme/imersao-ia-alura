# GPT NO SEU TRABALHO: FLUXOS E DADOS

## PROMPTS DA AULA

## LINKS

- [Planilha](https://docs.google.com/spreadsheets/d/1qnOo2Gm-AeOjyZMQygmtvKIxxIUFCN9R_sWwZYy4QHc/edit#gid=0) com as críticas ao filme Avatar
- [Arquivo](https://gist.github.com/fabriciocarraro/796e9e2f8fafac3712b33fc09c93c43e)JSON com 20 filmes e sem as notas 
- [Arquivo](https://gist.github.com/fabriciocarraro/a1760940faf23eb5a264c79732dc27ac)JSON com 20 filmes e com as notas
- [SheetGPT](https://sheetgpt.ai) - Extensão para Google Spreadsheets
- [ChatGPT.openai](https://chat.openai.com)
- [Stable Diffision](https://stablediffusionweb.com)

--- 

## DESAFIOS DA AULA

**Crie 10 críticas variadas para filmes**

Peça ao ChatGPT para gerar 10 críticas variadas para outro filme. Em seguida, solicite que ele converta essas respostas para o formato CSV, copie esses valores e salve-os em um arquivo de texto (.txt). Depois disso, abra o Google Sheets, crie uma nova planilha e importe o arquivo .txt (em "Arquivo -> Importar -> Fazer upload"). Ao fazer essa importação, pode ocorrer um erro se o Google Sheets confundir as vírgulas de separação com vírgulas presentes no texto. Caso ocorra algum erro, peça ao ChatGPT para corrigi-l0.

**Sugira descrições de imagens para serem inseridas em outras IA's**

Utilize o ChatGPT para sugerir descrições de imagens que possam ser inseridas em outras inteligências artificiais, como o Stable Diffusion. Peça ao ChatGPT para criar 5 descrições de imagens com estilos diferentes, a fim de explorar essa combinação entre o ChatGPT e o Stable Diffusion.

**Calcule a média salarial de pessoas com o Google Sheets e o ChatGPT**

Usando a função GPT_LIST() do SheetGPT, gere 20 nomes de pessoas brasileiras na coluna A, a área de atuação dessas pessoas (como "Marketing", "TI", "Direito" ou "Saúde") na coluna B e 20 valores aleatórios de salário entre 1.000 e 20.000 na coluna C. Agora, peça ao ChatGPT para criar uma macro para o Google Sheets que calcule a média desses salários e mostre a resposta na célula D2.