Curso Testanto APIs do Zero com Postman - Pessonizando
https://www.youtube.com/playlist?list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs


1 - O que é uma API? Entenda de uma vez por todas!
(https://www.youtube.com/watch?v=TSLoQzJ-6mw&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=1)

- API (Application Programming Interface) significa interface de programação de aplicações, um conjunto de definições e protocolos para criar e integrar softwares de aplicações.
- Facilitar a comunicação entre partes do sistema/software
- Agiliza o desenvolvimento, não precisa criar
- Aumenta a qualidade
- Boa segurança
- API DIFERENTE DE BIBLIOTECA!
- Bibliotecas são pedaços de código para reutilizar
- A APIs tem descrições do que as pessoas podem utilizar
- Como será feito a entrega de informações é de responsabilidade da API
- Composta por: Descrição, Protocolo (Protocolo HTTP), Restrições Rest
- Formato json ou xml -> requisição neste formato
- Mando para o servidor e recebe uma resposta
- https://swagger.io/ > Documentar API
- Endepoints -> recursos que api terá > URL/Recurso que manda e retorna a resposta


2 - Curso testando APIs do zero: o que é requisição HTTP - Aula 0
(https://www.youtube.com/watch?v=wb4av-65urY&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=2)

- GET (buscar dados) | POST (mandar dados) | PUT (alterar dados) | DELETE -> Cliente manda para API
- API devolve um JSON | XML para o Cliente
- Requisição tem: URL (endepont) | Método (GET | POST | PUT | DELETE) | Header | Body
- HTTP -> Protocolo de comunicação da internet


3 - Curso testando APIs do zero: entenda nossa api rest de estudo - Aula 0.1
(https://www.youtube.com/watch?v=7us8T2_js8k&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=3)

- Apresentação da API utilizada no curso feita criada com Kotlin, SpringBoot, Gradle e como executá-la no terminal ou intellij
- Instalação do INTEJI e do JDK
- https://github.com/vinnypessoni/api-clientes-exemplo-microservico


4 - Curso testando APIs do zero: visão geral do POSTMAN - Aula 1
(https://www.youtube.com/watch?v=8KsDpCpUPqI&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=4)

- Apresentação da ferramenta postman
- Faz requisições manuais ou automatizadas
- Coleções são grupos de requisições
- Coleções podem rodar individualmente ou juntas
- Criação de environment: criações de variáveis de ambientes para rodar em N ambientes.
Exemplo: ambiente de qa, produção...


5 - Curso testando APIs do zero: Criando um GET no POSTMAN - Aula 2
(https://www.youtube.com/watch?v=T_GNDDshSD8&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=5)

- Códigos de HTTP:
Respostas de informação (100-199)
Respostas de sucesso (200-299)
Redirecionamentos (300-399)
Erros do cliente (400-499)
Erros do servidor (500-599)
- Get e Delete não precisa de body


6 - Curso testando APIs do zero: criando um GET com parametro no POSTMAN - Aula 2.1
(https://www.youtube.com/watch?v=-djV2392b-s&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=6)

- Get não tem corpo
- Get pode ser todos ou filtro por id


7 - Curso testando APIs do zero: como fazer um POST no POSTMAN - Aula 3
(https://www.youtube.com/watch?v=uImHd39Rmyg&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=7)

- POST serve para adicionar um registro
- Verificar a rota na variável
- POST > Raw > Format: Jason


8 - Curso testando APIs do zero: criando um PUT no POSTMAN - Aula 4
(https://www.youtube.com/watch?v=uOTrSr361ic&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=8)

- PUT serve para atualizar dados
- PUT > Raw > Format: Jason


9 - Curso testando APIs do zero: criando um DELETE no POSTMAN - Aula 5
(https://www.youtube.com/watch?v=kfyAAVw-pTI&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=9)

- DELETE ser para deletar dados
- Colocar o ID para informar qual deseja deletar
- Delete não tem corpo


10 - Curso testando APIs do zero: autenticação Basic Auth no POSTMAN - Aula 6
(https://www.youtube.com/watch?v=qYxeMAE5DEY&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=10)

- Autenticação: login ou token
- Endpoint com autorização
- Login: aluno | Senha: senha
- No Headers vê como foi a informação para o servidor quando uso modo de autotentição


11 - Curso testando APIs do zero: como executar todos os testes de uma vez no POSTMAN - Aula 7
(https://www.youtube.com/watch?v=J96kOBhP2-s&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=11)

- Automação de teste
- Executar através do runner
- Configurar > Salvar > Rodar


12 - Por onde começar a testar APIs? Descubra
(https://www.youtube.com/watch?v=qd6GDTE5fLs&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=12)

- É um sistema por si só
- Seguir a pirâmede de teste
- Cobertura a nível de endpoints
- Fazer cobertura por endepoints
- Fazer manualmente com o CURL
- Ferramentas de teste manual: Postman (é a que mais usa)
- Ruby> httparty, rspec
- Java/Kotlin > restAssured


13 - REST x SOAP: entenda a diferença de uma vez por todas!
(https://www.youtube.com/watch?v=YWPT2UOxbUg&list=PLEqTHftpM91OzKYUkpaEuByhSpJYc90Hs&index=13)

- SOUP > Simple Object Access Protocol > Ele é um protocolo (conjunto de regras de como se fazer algo) > Conjunto rígido de regras > Ele sempre vai usar o XML para mandar e enviar mensagens > Padronização > Independente da linguiagens que forem usadas e de protocolos > Utiliza apenas método POST
- REST > Representational State Transfer > Regras menos rígidas > É um estilo arquitetural > restFul - respeita as regras do rest > Arquiterura cliente e servidor > Não tem estado > Pode fazer cache > Sistema em camada > Código em demanda > Tem interface > Usa métodos do HTTP
- 70% das APIs públicas são REST
- Mais frequente json e em segunda lugar o xml




















