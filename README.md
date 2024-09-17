# Projeto-Calculadora-EBAC
###### Projeto feito durante o curso de analista de dados na escola EBAC.

Se trata de uma calculadora simples desenvolvida na linguagem Python, que permite o usuário realizar as seguintes operações matemáticas:
- Adição
- Subtração
- Multiplicação
- Divisão
- Resto de divisão (o que sobra quando um número é dividido por outro)
- Potenciação

O programa irá pedir dois números e com eles você poderá escolher uma das operações e continuar até escolher a opção de sair.

# Como utilizar

1. **Abra o terminal do Linux**
   - Acesse o terminal do seu sistema operacional.
  
2. **Navegue até a diretório**
   - Na linha de comandos digite **cd** e o caminho onde está o diretório que será utilizado. Por exemplo:
     
   ```
   cd caminho/para/o/seu/diretorio
   ```
   > Substitua o que vem após o **cd** pelo caminho real.
   
3. **Altere as permissões do script**
   - Para tornar o arquivo de script `executar_calculadora` executável é preciso alterar a permisão dele com o seguinte comando:
  
   ```
    chmod +x executar_calculadora.sh
   ```
   - Com isso o arquivo passa a ser um executável.
 
4. **Alterando o script**
   - Para funcionar é necessário alterar o Script com o caminho real do arquivo no computador. Para alterar utilize o comando:

   ```
   nano executar_calculadora
   ```        
   - Depois que abrir a janela de edição altere o caminho de acordo com as instruções. O código estará assim:
      ```ruby
      #!/bin/bash

      sudo apt update
      sudo apt install python3

      #Adicone o caminho correto ate o arquivo "CalcuradoraEBAC.py" subistituindo o que vem apos "python3"
      python3 .../CalcuradoraEBAC.py
       ```
      > Como por exemplo: `python3 home/user/calculadora/CalcuradoraEBAC.py`
      
5. **Exucute o script**
   - Agora basta utilizar este comando:
    ```
    ./executar_calculadora
    ```
    > Assim o script irá instalar o python3 e executar o programa .py da calculadora.

