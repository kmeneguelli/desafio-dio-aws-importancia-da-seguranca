# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 04/09/2023  
Empresa: Abstergo Industries 
Responsável: Kaique Siqueira Meneguelli

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Kaique Siqueira Meneguelli. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
- Evitar a utilização da conta root para o trabalho na AWS
- A conta root é a conta que possui controle total sobre todas as ferramentas AWS, podendo definir permissões, ativar ou desativar serviços, formar grupos de trabalho. Então é altamente recomendável que essa conta não seja utilizada e que não tenha seu acesso compartilhado com nenhuma outra pessoa.

Medida 2: 
- Utilização do MFA na conta root ou em contas IAM com permissões importantes
- Ao ativar a autenticação MFA (multifator), é possível evitar que ocorra o acesso indevido a certos recursos AWS.

Medida 3: 
- Criação de grupos de trabalho com permissões definidas
- Na AWS é possível criar grupos de trabalho com usuários do IAM. Nesses grupos é possível aplicar políticas de permissões, permitindo que determinados usuários acessem apenas as ferramentas que foram previamente definidas pelo administrador. Evitando, desta forma, que usuários da empresa possam ter acesso indevido a alguns recursos ou que possam cometer algum equívoco ao tentar alterar alguma configuração.


## Conclusão
A implementação dessas medidas de segurança na empresa Abstergo Industries tem como objetivo um maior controle de acesso das ferramentas AWS, evitando que acessos indevidos ocorram e que alterações incorretas em serviços possam interromper o funcionamento pleno das atividades da empresa. Desta forma, é possível crer que haverá um aumento da eficiência e da produtividade da empresa. É plenamente recomendável que essas medidas sejam aplicadas de forma constante na empresa e que haja sempre aplicação de outras medidas de segurança para tornar o ambiente de trabalho da empresa cada vez mais confiável e seguro.

Assinatura do Responsável pelo Projeto:

Kaique Siqueira Meneguelli
