# Projeto Dohaeris
Projeto que visa descaracterizar aparelhos de TV Box.

## Isenção de responsabilidade (Leia com atenção)

Todo o conteúdo que você encontra neste tutorial (binários, textos, trechos de código, etc...) **não faz parte do projeto oficial da Armbian.** Dito isso, **as pessoas do projeto Armbian e nós que disponibilizamos essas documentação não somos responsáveis pelo uso indevido ou perda de funcionamento do hardware.**

## Introdução

Nesta documentação, você vai encontrar o passo a passo utilizado na instalação do sistema Armbian, sistema baseado no Debian, nos dispositivos de TV Box MXQ PRO 4K, que tem como processadores os chips Rockchip da série RK3228 A/B e RK3229.

### Especificações do modelo:

* 1GB Ram
* 7GB Armazenamento interno

### Requisitos:

* Dispositivo **TV Box MXQ PRO 4K**.
* O dispositivo deve conter memórias **DDR2** e **DDR3**.
* Cartão microSD.
* O Dispositivo TV Box deve Possuir memória **NAND**.
* Adaptador microSD para SD.
* Adaptador microSD ou SD para USB.
* Mouse e teclado USB.
* Monitor ou televisão.

## Processo de instalação
- Faça o download do Multitool, uma ferramenta que permite instalar a ISO do Armbian. Além disso, o Multitool é capaz de identificar automaticamente o tipo de memória, seja NAND ou eMMC.
- Faça o download da ferramenta BalenaEtcher. Essa ferramenta será utilizada para gravar a ISO do Multitool no cartão microSD.
- Descompacte o Multitool em seu computador.
- Insira o cartão microSD no seu computador usando um adaptador SD para USB.
- Abra o BalenaEtcher.
- Selecione a opção "Flash from file" ou "Selecionar imagem" no BalenaEtcher e escolha a ISO do Multitool.
- Selecione o cartão microSD como o dispositivo de destino para a gravação.
- Clique em "Flash" ou "Gravar" para iniciar o processo de gravação no cartão microSD.
- Aguarde até que o BalenaEtcher conclua o processo de gravação no cartão microSD.
