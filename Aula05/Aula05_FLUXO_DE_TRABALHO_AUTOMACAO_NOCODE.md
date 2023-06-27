# FLUXO DE TRABALHO: AUTOMAÇÃO NOCODE

## LINKS


- [TechGuide](https://techguide.sh)
- Ferramenta [Zapier](https://zapier.com)
- Plataforma da [OpenAI](https://platform.openai.com/auth/callback?code=DbhG6N9xHm8MPF6Zbv39CMU-BuzbWggslFXlgqWUDt87n&state=bGtTTlZlQm93UVJzUGJkaDdpXzZqZGUzbUhVYk5ueDZ4WXpVdGVwV3VGVQ%3D%3D)
- Ferramenta [IFTTT](https://ifttt.com)
- Ferramenta [Whisper](https://huggingface.co/spaces/openai/whisper)
- Ferramenta [ElevenLabs](https://beta.elevenlabs.io)
- Ferramenta [PDF.co](https://pdf.co)
- Código para chamada de API usando o [Google Colab](https://colab.research.google.com/drive/17B0fxL1lXCOPtOvUKBIHxbfsH1n5H9fS?usp=sharing)

## DESAFIOS

1. Automação de categorização de tweets em uma planilha do Google Sheets

Neste desafio, você deve criar um sistema automatizado para categorizar tweets em uma planilha do Google Sheets. A ideia é analisar campanhas de marketing nas redes sociais, especificamente aqueles que utilizam uma hashtag específica.

Sempre que alguém postar um tweet com essa hashtag no Twitter, o sistema deve adicionar automaticamente o tweet a uma planilha do Google Sheets e categorizá-lo como "Positivo", "Negativo" ou "Neutro". Isso permitirá a análise da recepção da campanha e a possibilidade de aprimorar a estratégia de marketing.

Você irá criar uma planilha no Google Sheets similar a esta, com as colunas "Usuário", "Tweet" e "Categoria". Depois, irá criar um novo Zap no Zapier, usando o Twitter como trigger (gatilho), e escolhendo a opção de busca por termo, utilizando a hashtag específica da campanha, como por exemplo #7DaysOfCode ou #ImersaoIA.

Feito isso, você poderá adicionar mais uma ação, que será usar o ChatGPT para categorizar o tweet como "Positivo", "Negativo" ou "Neutro". Por fim, você terá outra ação, que será para adicionar as informações do tweet na planilha do Google Sheets que você já criou (pode escolher a opção de criar múltiplas linhas na planilha), e você irá mapear cada coluna para seu item correspondente, que virão ou do Twitter ou do ChatGPT.

2. Análise automática de currículos

Você possui uma pasta no Dropbox onde os candidatos enviam seus currículos em formato PDF. Seu desafio é criar um fluxo automatizado que extraia os dados relevantes desses currículos e faça uma análise para determinar o nível de experiência de cada candidato.

Para isso, primeiramente você irá criar uma conta gratuita no PDF.co para acessar os dados de um PDF e converter arquivos PDF em texto, e obterá sua API KEY.

Em seguida, crie uma planilha no Google Drive similar a esta, com as colunas: "Nome completo", "Email", "Telefone", "Nível" e "Análise".

Com isso pronto, você irá começar um novo Zap no Zapier, e o trigger será a adição de um arquivo PDF a uma pasta sua no Dropbox. No app da PDF.co, configure o evento "PDF to Anything Converter" e insira sua API KEY. Defina o formato de saída como "Plain text without layout...". Preencha o campo "Source PDF URL" com o "1. Share link" do arquivo PDF no Dropbox. Selecione o idioma como "Portuguese".

Agora sim, você vai brincar com o ChatGPT. Você pode adicionar várias ações dele uma depois da outra. Cada ação irá extrair dados diferentes do texto do currículo:

Na primeira ação, extraia apenas o nome completo do candidato.
Na segunda ação, extraia apenas o email do candidato.
Na terceira ação, extraia apenas o telefone do candidato.
Na quarta ação, faça a análise do currículo. Avalie anos de experiência, projetos relevantes e tecnologias com as quais o candidato trabalhou. Classifique o nível do candidato como Júnior, Pleno ou Sênior.
Na quinta e última ação, analise a resposta anterior do ChatGPT e responda com uma palavra se o candidato é Júnior, Pleno ou Sênior.
Por fim, insira os dados extraídos na planilha criada usando uma ação do Google Sheets no Zapier (pode escolher a opção de criar múltiplas linhas na planilha).