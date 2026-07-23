# Agenda Plena — instaladores

Sistema local de controle de clientes de terapia e mentoria: cadastro, agenda, prontuário,
formulários, atividades, mentoria e financeiro. **100% offline**: os dados e o prontuário
ficam no computador de quem atende, sem servidor e sem nuvem.

Este repositório guarda **apenas os instaladores** de cada versão. Ele existe para que o
programa já instalado consiga se atualizar sozinho. **O código-fonte é privado.**

## Baixar

A versão mais recente está em [Releases](../../releases/latest). Baixe o arquivo
`AgendaPlena-Instalador-<versão>.exe` e execute.

Instalar ou atualizar **nunca toca no banco de dados**: os dados ficam em
`%APPDATA%\agenda-plena`, fora da pasta do programa.

## Ativação

O sistema é liberado por computador. Ao abrir uma instalação nova, ele mostra o código
daquela máquina; com esse código, quem vende emite o código de liberação correspondente.
Baixar o instalador, sozinho, não dá acesso ao sistema.

## Atualização automática

A partir da versão 0.16.0 o programa procura versão nova uma vez por abertura, baixa em
segundo plano e instala **quando você fecha o programa**, nunca durante um atendimento.
Sem internet, ele não procura e nada quebra.

Versões anteriores à 0.16.0 não têm esse mecanismo: a atualização para a 0.16.0 precisa ser
feita à mão, uma única vez.

## Suporte

Fale com quem instalou o sistema para você.
