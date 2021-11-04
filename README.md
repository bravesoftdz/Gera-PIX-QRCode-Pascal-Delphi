# Gera-PIX-QRCode-Delphi
Função em Delphi para Gerar PIX e QR Code em Delphi
Está função foi feita para uso didático e você está livre para usa-lo em seu software

O Projeto foi feito em cima da Documentação do Banco Central de Padronização do Pix

 A Documentação de Iniciação do PIX segue a Padronização de ID + TAMANHO + VALOR
 
 '000201' -> versão do payload QRCPS-MPM, fixo em “01”
 '010211' -> “11” (QR reutilizavel) ou “12” (QR utilizavel apenas uma vez)
 '26'     -> indica arranjo especifico - Merchant Account Information
 
 Neste momento entra o TAMANHO DE CARACTERES ATE O FINAL DA DESCRICAO
 
 '0014br.gov.bcb.pix' ->  “00” (GUI) obrigatório e "14" tamanho do "br.gov.bcb.pix"
 
 PARA OBTER MAIS INSTRUÇÕES BAIXE O PROJETO

# Créditos

ACBr e Foxit Software por disponibilizarem o gerador de QRCode DelphiZXingQRCode
Usuario renatomb do GitHub por disponibilizar codigo em PHP que serviu de grande ajuda
