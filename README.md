# Conversor de JSON para CSV

O tipo JSON (JavaScript Object Notation) é um padrão de troca de dados de forma leve e simples. É um tipo de dado muito utilizado para comunicação nas API REST.
  
O Objetivo desta atividade é desenvolver um conversor de um JSON para CSV, para que dessa forma ajude o time de Produtos a visualizar melhor os dados de nossa aplicação.


#### Restrições
- Não pode usar biblioteca que facilite a conversão de JSON para CSV
- Estruturas JSON aninhadas não são suportadas
- <strong>(DICA)</strong> No caso do JavaScript, talvez seja melhor utilizar `Object.keys()` e `Object.values()` para buscar os headers e as rows, pois com loops demandaria mais esforço

#### Features
- O usuário pode colocar o JSON em um textbox
- O usuário pode clicar em um botão "Converter" para validar o texto JSON e converte-lo
- O usuário pode ver o CSV convertido em um outro textbox
- O usuário pode ver uma mensagem de , caso o textbox do JSON esteja vazio ou não seja um JSON válido
- O usuário pode clicar em um botão de "Limpar", para limpar o textbox do JSON e do CSV



#### Bônus
- O usuário pode fazer um upload de um arquivo do tipo JSON para o textbox
- O usuário pode clicar em "Buscar" para carregar o arquivo JSON no textbox
- O usuário pode ver uma mensagem de aviso, caso o JSON não seja suportado ou não encontrado
- O usuário pode clicar no botão de "Salvar" para salvar localmente o CSV em sua máquina
- O usuário verá uma mensagem de erro, caso o CSV textbox for vazio ou a operação de salvar falhar

#### Links de ajuda
- [MDN Javascript Object](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Object)
- [JSON // Dicionário do Programador](https://www.youtube.com/watch?v=P81dE-tkaaA)
- [Aprenda JSON em 20 minutos](https://www.youtube.com/watch?v=BWPUSXzSWA8)
  