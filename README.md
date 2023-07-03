# Python-Logging

## O que são Logs

Um arquivo de log é um registro contínuo, que contém a data e a hora do evento, além de uma mensagem criada automaticamente oelos Softwares e sistmas de TI.

Os logs são registros das ações realizdas nos sistemas. Eles podem registrar falhas, exeções, ajudar a depurar erros, identificar violações de segurança e fornecer informações úteis para os desenvolvedores analisarem.

Em resumo, os logs são capazes de mostrar o que e quando aconteceu um evento, além de indicar que, deu inicio a ele.

## Logging em Python 

Essa é uma biblioteca do Python destinada a criação dos logs nas aplicações. Ela é uma maneira de rastrear eventos que acontecem quando o software executa. Podemos através dela adiciona chamadas de loging no código para indicar que determinado evento ocorreu.

É uma boa prática seguir as orientações da propria documentação. Podemos ver que os logs são definidas em níveis para armazenamento.

```
Resumo
logging.debug
DEBUG - Informações detalhadas, tipicamente de interesse apenas quando diagnosticamos problemas..

logging.info
INFO - Confirmação de que as funcionalidades estão funcionando dentro do esperado.

logging.warning
WARNING - Uma indicação que algo inesperado aconteceu, ou um indicativo que algum futuro ela pode parar de funcionar.

logging.error
ERROR - Por conta de um problema mais grave, o software não conseguiu executar alguma função.

loggingcritical
CRITICAL - Um erro grave, indicando que o programa pode não conseguir continuar rodando.
```
