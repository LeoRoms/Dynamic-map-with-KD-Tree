**Arthur Guimarães Ferreira**   
**Leonardo Romano Andrade**   


Este programa cria uma aplicação web interativa em *Dash* que mostra, sobre um mapa de Belo Horizonte, os pontos de restaurantes e bares (incluindo participantes do Comida Di Buteco 2025). Ao iniciar, o script:

1. Carrega o polígono de Belo Horizonte e uma tabela de estabelecimentos com latitude/longitude.
2. Constrói uma KD-Tree para permitir buscas rápidas por áreas retangulares.
3. Exibe o mapa com camada base, limite da cidade e máscara externa.
4. Permite desenhar retângulos sobre o mapa para filtrar pontos dentro daquela área, atualizando marcadores agrupados e preenchendo uma tabela com nome, data de início, informação de alvará, endereço e se o local participa do CDB 2025.

Execute `python main.py` e o navegador abrirá automaticamente a interface, onde você pode navegar, dar zoom, desenhar regiões e consultar os detalhes dos estabelecimentos.


O repositório também conta com o relatório deste trabalho prático, que apresenta detalhes da implementação e exemplos de execução.
