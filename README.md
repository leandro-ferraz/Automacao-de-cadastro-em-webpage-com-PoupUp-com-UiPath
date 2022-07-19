# Automacao-de-cadastro-em-webpage-com-PoupUp-com-UiPath
Automação no UiPath para cadastro em webpage com tratamento de PoupUp.

Requisitos:
1. Estar logado no site: https://www.rpahackathon.co.uk/
2. Baixar os pacotes do UiPath (se for o caso):
  - UiPath.UIAutomation.Activities (v22.4.5)
  - UiPath.Excel.Activities (v2.12.3)
  - UiPath.System.Activities (v22.4.1)
  - UiPath.Mail.Activities (v1.15.2)

Descrição:
A automação entra no site RPAHACKATHON (desafio nível 1 e 0 estrelas) e baixa o arquivo necessário com os dados a serem cadastrados. Após isso, realiza um tratamento no arquivo baixado (.CSV) ao corrigir a falta de uma pontuação de ";". Em seguida, cria uma estrutura de decisão para tratar a PoupUp se ela aparecer. Por fim, preenche o cadastro de todas as pessoas que constam no arquivo .CSV.
