ESCOPO DO PROJETO – VIALERTA
1. Visão Geral

O ViaLerta é um sistema web desenvolvido para auxiliar na identificação e registro de problemas encontrados em vias públicas por meio de Inteligência Artificial.

A solução permite que o usuário envie uma imagem de uma via para análise automática. O modelo de Inteligência Artificial identifica possíveis ocorrências e apresenta os resultados para posterior registro no sistema.

2. Objetivo Geral

Desenvolver uma solução capaz de utilizar Visão Computacional e Inteligência Artificial para auxiliar na identificação de problemas em vias públicas, tornando o processo de registro de ocorrências mais organizado e eficiente.

3. Funcionalidades do Sistema
Para o usuário
Acessar a aplicação web;
Enviar imagens para análise;
Realizar a análise da imagem utilizando o modelo YOLO;
Identificar ocorrências detectadas pela Inteligência Artificial;
Visualizar informações da detecção;
Informar localização da ocorrência;
Registrar um chamado;
Consultar ocorrências registradas.
Para o gerenciamento das ocorrências
Armazenar os dados dos chamados;
Registrar informações da ocorrência;
Associar imagens às ocorrências;
Armazenar os resultados da análise da IA;
Permitir a consulta dos registros realizados.
4. Inteligência Artificial

O sistema utiliza um modelo YOLO treinado para identificar três categorias:

Pothole: buraco;
Crack: trinca;
Manhole: tampa de bueiro.

O modelo recebe uma imagem como entrada e retorna as detecções encontradas, incluindo a localização do objeto identificado e seu nível de confiança.

5. Tecnologias
Python;
YOLO / Ultralytics;
PyTorch;
FastAPI;
React;
TypeScript;
Vite;
Supabase;
HTML e CSS;
Git/GitHub.
6. Arquitetura

O funcionamento geral segue o fluxo:

Usuário → Aplicação Web → API → Modelo YOLO → Resultado da análise → Registro da ocorrência → Banco de Dados

7. Escopo da Inteligência Artificial

O modelo será utilizado exclusivamente para auxiliar na identificação das categorias treinadas.

A detecção realizada pela IA não representa uma avaliação técnica ou estrutural da via. O resultado deve ser considerado uma indicação automática para auxiliar no registro da ocorrência.

8. Fora do Escopo

Não fazem parte do escopo inicial:

Correção física dos problemas identificados;
Fiscalização presencial das vias;
Avaliação estrutural realizada por profissionais;
Monitoramento contínuo por câmeras;
Aplicativo mobile nativo;
Automação completa do atendimento dos chamados.
9. Entregáveis

Ao final do projeto serão entregues:

Aplicação web funcional;
Modelo YOLO treinado;
API de integração;
Banco de dados;
Dataset utilizado no treinamento;
Código-fonte;
Documentação;
Cronograma;
Atas de reunião;
Relatório final;
Repositório GitHub/GitLab.
10. Critérios de Conclusão

O projeto será considerado concluído quando:

A aplicação web estiver funcionando;
O modelo YOLO puder analisar imagens;
As detecções forem apresentadas ao usuário;
O sistema permitir o registro das ocorrências;
Os dados puderem ser armazenados no banco de dados;
A integração entre frontend, API e modelo estiver funcionando;
Os testes principais forem realizados;
A documentação do projeto estiver organizada.
