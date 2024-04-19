# Desafio Hackathon 2024 Makenzie
##:historia
Eu enquanto Colaborador H Hiperstream, necessito de um sistema que com base no modelo de dados sugerido seja capaz de devolver um desenho de diagrama que mostre o Fluxo da informação com base em duas pastas diferentes. 
O Diagrama não precisa necessariamente seguir o do exemplo, 
###Modelo de Dados

| Campo | Descrição |
| --- | --- |
| ID | Identificador do cadastro |
| Nome | Nome da Aplicação |
| PastaOrigem | Pasta onde a aplicação espera a chegada de um arquivo |
| PasteDestino | Pasta onde a aplicação gera seu resulta após o processamento |
| PastaBackup | Local onde a aplicação copia o arquivo de origem  assim que processar |
#### Exemplo de dados:

| ID | Nome | PastaOrigem | PastaDestino | PastaBackup |
| --- | --- | --- | --- | --- |
| 1 | Aplicacao1 | C:\EntradaA\ | C:\Entrada2\ | C:\Guarda\ |
| 2 | Aplicacao2 | C:\Entrada2\ | C:\Aplicacao2Dest\ | C:\Voa |
| 3 | Aplicacao3 | C:\Voa |  | C:\Guarda\ |
| 4 | Aplicacao4 | C:\Entrada2\ |  | C:\Guarda\ |
| 5 | Aplicacao5 | C:\monitorada\3k\ | C:\monitorada\ds\ | C:\monitorada\Gd\ |
| 6 | Aplicacao6 | C:\Aplicacao2Dest\ |  |  |

####Exemplo de Desenho de Fluxo:
![](https://github.com/hiperstream/desafio_hackathon_2024/blob/main/Exemplo_Fluxo.svg)


`Obs. O Modelo do exemplo se baseou em um desenho de aplicação seguindo os critérios abaixo:`
![](https://github.com/hiperstream/desafio_hackathon_2024/blob/main/Exemplo_base_diagrama.svg)


### Critérios de Aceitação

- Aplicações podem ou não conter *PastaDestino*;
- Seja a pastaDestino seja a PastaBackup de uma aplicação pode ser monitorada por 0 ou N aplicações
- Um modelo de dados pode conter 1 ou N fluxos e cada fluxo pode conter 1 ou N aplicações. Todos devem ser desenhados
- A comparação entre as pastas para montagem das interligações entre as aplicações devem ser textual e *Case Insensitive*.
- A entrada dos dados para a aplicação precisa ser simples de importar e não podem existir formulários com cadastros individualizados. A solução se destina a dados volumosos.

### Critérios tecnológicos

- A Hiperstream não coloca critérios tecnológicos, sendo assim desde que vocês não infrinjam nenhuma licença e/ou legislação o critério de tecnologia fica à cargo do time e com auxílio do time técnico da Hiper.
- Os desenhos são meros exemplos, vocês podem usar outras tecnologias e outros modelo de desenhos desde que formem um diagrama compreensível e devidamente documentados.
- Todas as decisões tecnológicas devem ser devidamente justificadas, podendo ser perguntado pelos avaliadores.
- É importante existir uma documentação de arquitetura, mesmo que básica e também uma documentação de usabilidade para permitir que alguém que não conheça a solução a utilize.

Resumo

Utilizando técnicas de agregação de hierarquia em uma base de dados fornecida, esperamos uma solução capaz de transformar uma estrutura de tabela em uma visualização gráfica hierárquica, facilitando a visualização e a análise dos dados.

