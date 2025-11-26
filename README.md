Segunda atividade de arquitetura de software
-Feito por Iran Matos Barbosa / João Vitor Adiers Xavier

Instruções: baixe a pasta .zip, descompacte a pasta
-Dentro da pasta principal, rode o comando "npm install" para instalar as dependências do arquivo "package.json" para o funcionamento do programa. Após isso os seguintes comandos DEVERIAM ESTAR FUNCIONANDO:

1- npx ts-node adapter_REST.ts   //para iniciar o servidor web para REST.
 -1.5- ctrl + c para encerrar o servidor.

2- No CMD, o comando curl -X POST http://localhost:3000/compromisso -H "Content-Type: application/json" -d "{\"data\": \"15/01/2026\", \"start\": \"10:00\", \"end\": \"12:00\", \"descr\": \"Reuniao de Teste CMD\"}"      //deve adicionar um compromisso ao banco (no linux é diferente, talvez o senhor saiba converter o comando para rodar no linux mas o nosso saiu em CMD).

3- no CMD, o comando curl -X GET http://localhost:3000/compromisso      //deve retornar os compromissos agendados.

4- No proprio terminal, o comando npx ts-node adapter_CLI.ts add "data_compromisso" "hora_inicio" "hora_final"    //deve adicionar um compromisso ao banco, seguindo esses 3 parametros.

5- No proprio terminal, o comando npx ts-node adapter_CLI.ts listar compromissos    \\deve listar os compromissos guardados no banco (Em CLI é mais bonito de ver os compromissos).
