# DECLARAFÁCIL - Organizador de Dados para Imposto de Renda (IRPF)

Ferramenta desenvolvida em Excel para centralizar e organizar documentos e informações anuais necessários para a declaração do Imposto de Renda Pessoa Física.

---

## Objetivo do Projeto

Facilitar o preenchimento da declaração anual reunindo em um único arquivo os dados cadastrais, saldos bancários e comprovantes de rendimentos, evitando esquecimentos e agilizando a conferência.

---

## Estrutura da Planilha

O arquivo está organizado nas seguintes abas:

* *Titular:* Espaço para registro das informações básicas e cadastrais do contribuinte (e dependentes, se houver).
* *Informes Bancários:* Controle centralizado de instituições financeiras, contas e saldos para conferência com os informes de rendimentos anuais.
* *Notas:* Área dedicada ao registro e anexo (via hiperlinks ou objetos incorporados) de holerites, recibos e notas fiscais emitidas ao longo do ano.

---

## Recursos Utilizados

* Organização estruturada em abas temáticas interligadas
As três abas estão integradas por meio de botões interativos que facilitam a organização, em dois locais: no menu de navegação construído na margem esquerda contendo o nome das abas do documento, e também por meio de botões "Anterior" e "Próximo" presentes. 

* Validação de dados
Os dados são formatados automaticamente ao inserir informações como CPF, telefone, celular e CEP. 
A planilha conta com proteção, e as únicas células passíveis de serem selecionadas são aquelas cujo objetivo é que seja preenchida pelo usuário, evitando assim que o app desconfigure.
Foram utilizados campos os quais as respostas devem ser exclusivamente selecionadas de um menu na lista suspensa ao lado da célula (ex: Campo "RESIDENTE DO EXTERIOR" na aba "Titular", campo "BANCO" na aba "Informes", entre outros).

* Hiperlinks / Inserção de objetos para centralização de documentos 
Na aba "Informes" campo "Anexos", é possível anexar os demonstrativos bancários em formato .pdf por da função "Inserir Objeto". O documento pode ser diretamente anexado dentro do arquivo do Excel, ou criado um caminho que ao ser clicado, levará o usuário para o arquivo na máquina local. Também é possível utilizar a inserção de "Hiperlinks", caso os documentos estejam salvos na nuvem, por exemplo. 
Na aba "Notas", o campo "Anexos" pode ser preenchido utilizando os mesmos métodos descritos acima (hiperlinks ou objetos).

---

## Como Utilizar

1. Faça o download do arquivo .xlsx disponível neste repositório.
2. Abra a planilha no Microsoft Excel.
3. Preencha os dados cadastrais na aba *Titular*.
4. Registre as contas bancárias e valores na aba *Informes*, e anexe os demonstrativos bancários no campo "Anexos" por meio de hiperlinks ou objetos.
5. Insira todas as entradas na aba "Notas", e anexe os comprovantes no campo "Anexos" por meio de hiperlinks ou objetos.
Dica: se o objetivo é preencher o arquivo e encaminhar para terceiros, opte por anexar os comprovantes diretamente dentro do arquivo Excel (vá em Inserir > Texto > Objeto > Criar do arquivo > Procurar; escolha o arquivo e selecione a caixa para mostrar o ícone). Ao ser clicado, o arquivo irá abrir localmente.

---

Feito com 💜 por Bruna Stefhany Pena