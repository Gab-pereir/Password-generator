# Gerador de Senhas

Este projeto é um gerador de senhas aleatórias em Python que permite ao usuário definir o número de caracteres da senha, combinando letras, números e símbolos para gerar uma senha segura.

## Funcionalidades

O script oferece:

1. **Entrada do Usuário**: Permite ao usuário inserir o número de caracteres desejados para a senha.
2. **Verificação da Entrada**: Verifica se o valor de entrada é um número válido. Caso contrário, exibe uma mensagem de erro e encerra o programa.
3. **Geração da Senha**: Cria uma senha aleatória com base no comprimento fornecido pelo usuário, usando letras, números e caracteres especiais.

## Dependências

O código usa apenas bibliotecas padrão do Python, como `random` e `string`, portanto, não há necessidade de instalar bibliotecas externas.

## Como Usar

1. Execute o script.
2. Insira o número de caracteres desejados quando solicitado.
3. O script verificará a validade da entrada. Se a entrada for válida, gerará e imprimirá uma senha aleatória. Caso contrário, exibirá uma mensagem de erro.

### Exemplo

Ao executar o script, a seguinte interação pode ocorrer:

```plaintext
Quantos dígitos terá a senha? 12
Senha gerada com sucesso:
@3v&8Tz#KlQ1
```

## Estrutura do Código

1. **Imports**: O script importa as bibliotecas `random` e `string` para gerar a senha.
2. **Função `password_generator`**: Esta função recebe um argumento `len_pass`, que define o comprimento da senha a ser gerada, e cria uma senha combinando caracteres aleatórios.
3. **Bloco Principal**: Pede ao usuário o comprimento desejado da senha e usa a função `password_generator` para gerar a senha, exibindo-a na tela.

## Possíveis Melhorias

1. **Personalização Avançada**: Adicionar opções para o usuário escolher o tipo de caracteres que deseja (somente letras, letras e números, etc.).
2. **Controle de Erros**: Implementar uma verificação para limites mínimos e máximos de comprimento da senha.
3. **Integração com Interfaces Gráficas**: Expandir o script para uso em uma interface gráfica.
