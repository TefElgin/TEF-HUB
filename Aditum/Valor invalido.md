## VALOR INVÁLIDO AO INICIALIZAR TERMINAL:


#### Extrair log do e1, situado em c:/elgin/tef/logs/e1_log.txt e observar se é obtido o retorno abaixo:

##### {07/02/25 09:49:23:212}{E1_Tef}{I} 		 iniciarLoja: (401) Inicialização realizada com sucesso
{07/02/25 09:49:23:213}{E1_Tef}{I} 		 {"errors":[{"description":"VALOR INVÁLIDO","errorCode":-1951,"message":"'AdministrativePassword' is missing."}],"success":false} ###

##### Este retorno é obtido ao realizar ativação do terminal com versão do client da aditum, inferior à 2.3.5. Para solução, é necessário desinstalar o ELGIN TEF HUB (incluindo o client da aditum) e após reinstalar, validar se a versão foi atualizada no painel de controle, vide imagem abaixo:

![Logo do GitHub](https://github.com/TefElgin/TEF-HUB/blob/80f9b4d92a49e2426e968e0da688c198377d539a/Aditum/Imagens/Valor%20Invalido/APLICACAO%20ADITUM.png)
