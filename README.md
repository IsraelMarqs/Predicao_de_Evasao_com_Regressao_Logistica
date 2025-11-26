# Predicao_de_Evasao_com_Regressao_Logistica
## Preparação

Certifique-se de ter o Python instalado e rode o comando abaixo para instalar as bibliotecas:
pip install fastapi uvicorn scikit-learn pandas joblib pydantic pyngrok

Execute a primeira célula para treinar o modelo e gerar o arquivo .pkl.

Configure seu token do Ngrok, rode a segunda célula e clique no link público gerado.

No link aberto, vá até o endpoint POST /predict.

Clique em 'Try it out'.

Preencha os dados do aluno e clique em Execute.

O resultado com a probabilidade de evasão será exibido no campo de resposta.
