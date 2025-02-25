## VALOR INVÁLIDO AO INICIALIZAR TERMINAL:


#### Extrair log do e1, situado em c:/elgin/tef/logs/e1_log.txt e observar se é obtido o retorno abaixo:

##### {07/02/25 09:49:23:212}{E1_Tef}{I} 		 iniciarLoja: (401) Inicialização realizada com sucesso
{07/02/25 09:49:23:213}{E1_Tef}{I} 		 {"errors":[{"description":"VALOR INVÁLIDO","errorCode":-1951,"message":"'AdministrativePassword' is missing."}],"success":false} ###

##### Este retorno é obtido ao realizar ativação do terminal com versão do client da aditum, inferior à 02.25.xx. Para solução, é necessário atualizar o ELGIN TEF HUB.
