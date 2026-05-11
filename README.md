# Compilador Pascal

O projeto implementa um compilador para um subconjunto da linguagem Turbo Pascal feito com Python.

O compilador executa:

Análise lexica
geração de tokens
Análise sintática (parser descendente recursivo)
Tabela de simbolos
Verificação semântica básica

Funcionalidades suportadas

O compilador reconhece:

Declaração de variáveis
Tipos 'integer' e 'real'
Expressões aritméticas
Operadores relacionais
Comandos 'if'
Comandos 'while'
Blocos 'begin/end'
Procedures
Chamadas de procedures

Estrutura do Projeto

'lexer.py' - analisador léxico
'parser.py' - analisador sintático
'token_type.py' - definição dos tipos de tokens
'tokens.py' - estrutura dos tokens
'symbol_table.py' - tabela de símbolos
'main.py' - execução principal do compilador
