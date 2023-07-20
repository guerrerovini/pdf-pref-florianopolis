# pdf-pref-florianopolis
Automação para o download de PDFs da Prefeitura de Florianópolis

Projeto realizado para automatizar o download de PDFs da Prefeitura de Florianópolis.
Mais informações em: https://jornada-de-dados-do-vini.blogspot.com/

Desenvolvimento realizado em Python 3.9.16 com as bibliotecas Pyautogui, Time, Pyperclip e Pandas. Projeto realizado em ambiente Windows.

Dados:
CMC: a ser preenchido com a inscrição municipal do emissor da NF
Código de verificação: deve ser fornecida uma lista em Excel com o código e o link da prefeitura já montado
Link da prefeitura: deve estar no formato 'https://nfps-e.pmf.sc.gov.br/consulta-frontend/#!/consulta?cod="Código de verificação"&cmc="CMC"', e substituir os itens entre aspas, “Código de Verificação” e “CMC”, por seus respectivos valores
A expectativa do programa é receber uma coluna com o nome 'link' para poder funcionar corretamente

A planilha no código está como 'teste' e esta pode ser substituída para a atual. Uma boa prática seria colocar o documento na mesma pasta em que o código está salvo.
