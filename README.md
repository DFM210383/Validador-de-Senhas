Este projeto é um validador de senhas desenvolvido em Java, inspirado em testes técnicos reais aplicados por empresas de tecnologia durante processos seletivos. 
O objetivo é verificar se uma senha atende a critérios de segurança com base em boas práticas, ao mesmo tempo em que demonstra conhecimento de lógica de programação, 
manipulação de strings e organização de código.
O funcionamento é simples: o usuário digita uma senha no terminal e o programa retorna se ela é válida ou não, explicando os requisitos obrigatórios. 
Para que seja considerada válida, a senha deve possuir no mínimo oito caracteres, conter pelo menos uma letra maiúscula, uma letra minúscula, um número e um caractere especial 
entre @, #, $, %, &, * ou !, além de não permitir espaços em branco. Caso algum desses requisitos não seja atendido, o programa informa quais pontos precisam ser corrigidos.
Para executar o projeto, basta clonar o repositório, compilar o arquivo ValidadorSenha.java com o comando javac e rodar o programa com java. O código é compatível com Java 11 
ou versões mais recentes.
Um exemplo prático seria: ao digitar a senha “Abc@1234”, o sistema retorna que ela é válida. Já se o usuário digitar “senha123”, a aplicação indica que a senha é inválida e 
exibe todos os critérios necessários para corrigi-la.
Esse projeto é uma ótima forma de demonstrar domínio da linguagem Java e pode ser facilmente expandido. Algumas possibilidades de evolução incluem transformar o validador em uma 
API REST com Spring Boot, adicionar testes unitários com JUnit, criar uma versão com interface gráfica utilizando JavaFX ou Swing, ou até mesmo integrá-lo a um sistema de cadastro 
de usuários com banco de dados.
Além de resolver um problema real relacionado à segurança da informação, o código serve como um exemplo prático de aplicação em entrevistas, processos seletivos ou como parte de 
um portfólio público no GitHub.
