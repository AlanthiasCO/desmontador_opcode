# Desmontador (disassemble) de bytecode para opcode:
Ferramenta para desmontar bytecodes de contratos inteligentes em seus respectivos opcodes.

A ferramenta faz web scraping no site https://ethervm.io e coleta os bytecodes e seus respectivos opcodes, criando um dicionario que permite desmontar grandes quantidade de bytecodes (desde que estejam em um arquivo .csv).

Basta organizar o seu dataset com o cabeçalho 'bytecode' e 'category' e inserir ele em 'input_csv'. Ao rodar, será gerado um novo dataset chamado 'output.csv' que terá todos os opcodes respectivos ao seu dataset de origem inserido em 'input.csv'.

TO-DO: Aceitar outros tipos, como JSON.
