# TAREFAS EM PLANILHAS

## PROMPTS DA AULA


Aqui você encontra os prompts iniciais da aula:

Tenho uma planilha no Google Sheets com notas de alunos. Na coluna A está o nome do aluno e na coluna B a nota. Crie uma fórmula para filtrar os alunos com nota acima de 7.
Tenho uma planilha no Google Sheets com uma lista de alunos e as notas de cada aluno em 4 diferentes provas. Quero uma função em App Script para calcular a nota final do aluno. Ela recebe as 4 notas das provas e devolve uma nota com o seguinte critério: Se o aluno tirou algum zero a nota final é 0; Senão a nota final é a média das 3 maiores notas.
Escreva um email para um aluno de física para apresentar a nota dele no semestre. Nome: Marcelo Barbosa; Nota: 8,8.

## LINKS

- Ferramenta [Script](https://www.google.com/script/start/)
- [OpenAI](https://openai.com)
- Ferramenta [Eightify](https://eightify.app)
- Feramenta [Gamma](https://gamma.app)
- Ferramenta [Japer](https://www.jasper.ai/free-trial?_from=ads&fp_sid=1-g-Cj0KCQjwnMWkBhDLARIsAHBOftp3-2_GQsww0SIqFbn0x56rZWHUlJDDIFeF8UskgLWHk9we0Us-dKAaAsk1EALw_wcB)
- [Planilha de Notas](https://docs.google.com/spreadsheets/d/1jMZToQ1y5aThfBIG8U8H00V4CEdujRgn4hmuiXjjy5A/edit#gid=0)
- [GPT Tokenizer](https://gpt-tokenizer.dev)
- [Código para gerar um email com a API do GPT](https://gist.github.com/oluizleme/337415402adac665a0e3c81de481fa54)
- Ferramenta [ElevenLabs](https://beta.elevenlabs.io)
- Ferramenta [Whisper](https://huggingface.co/spaces/openai/whisper)
- Conteúdo apresentado na Live [7 ferramentas de IA além do chatGPT](https://docs.google.com/presentation/d/1YWqJEKJxJToQNFKL-vpQ26ojem2oV60sxnD4TtB4dq0/edit#slide=id.g1dc93135802_4_10)

## DESAFIOS

1. Tokenização: Explorando o GPT-Tokenizer e o ChatGPT

Peça para o ChatGPT padrão gerar um texto curto sobre um assunto de seu interesse. Em seguida, acesse a página do GPT-Tokenizer, cole esse texto e observe como o modelo do GPT separa as palavras para gerar 'x' tokens.

2. Playground OpenAI: Brincando com Modelos e Temperaturas no Modo Chat

Crie uma conta na OpenAI, acesse o Playground, selecione o modo 'Chat' e experimente com os diferentes modelos e temperaturas. Gere o mesmo texto em diferentes temperaturas e analise as diferenças entre elas.

3. Gerando Mensagens com base em Notas dos Alunos: Usando a API_KEY

Usando o código do Sérgio e a sua API_KEY, faça a alteração no campo "content:" de 'role: "system"' no código, com o objetivo de gerar uma mensagem personalizada e carinhosa para cada aluno(a), com base na nota que ele(a) recebeu.