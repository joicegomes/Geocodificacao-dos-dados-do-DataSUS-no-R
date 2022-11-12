# Geocodifica-o-dos-dados-do-DataSUS-no-R

## Codigos básicos no R para acessar os dados do DataSUS e mapeá-los com o uso do CEP, um arquivo de logradouros e os limites de bairros de um município: exercício com exemplo em Salvador/BA

Este repositório traz 4 tutoriais que podem ser executados em sequência, e faz parte do material didático desenvolvido para curso "Mapeamento e comunicação comunitária no combate a pandemias" oferecido no segundo semestre de 2020 para alunos de diversos vcursos de graduação e pós-graduação da Universidade Federal da Bahia e para agentes comunitários de saúde da cidade de Salvador/BA, Brasil.

- **O Módulo 0 (zero) apresenta uma rápida introdução ao R** e ao RStudio, com os comandos básicos necessários durante todo o curso;
- **O Módulo 1 apresenta o uso do pacote "microdatasus"**, que permite a o aceso aos dados das AIH (autorização de intenação hospitalar);
- **O módulo 2 apresenta o pacote "hereR" para a geodificação em lote** dos dados do DataSUS por meio da API do Here Maps;
- **O Módulo 3 apresenta o uso dos dados geocoficados no QGIS**, para análise espacial dos dados de internação (PDF com instruções incluso).

Todos os dados auxiliares estão nas respecvtivas pastas, e como exemplo são utilizados os Bairros da cidade de Salvador, BA. Com poucos modificações é possível 
customizar o código para diversos recortes geográficos e CID (Código internacional de doenças.

Para maiores detalhes sobre o pacote microdatasus consulte a página do autor: https://github.com/rfsaldanha/microdatasus

Para a realização da geocodificação você precisrá de uma chave de API na Here Maps: https://developer.here.com/

Os detalhes para a configuração do ambiente no RStudio e ára geração da chave de API estão detalhadamente descritas como comentários nos códigos.

