# radares_sp
Obtenção de informações de viagens realizadas no município de São Paulo

Objetivo: Acessar o website (http://dadosradares.prefeitura.sp.gov.br/) e obter um arquivo JSON de cada viagem_id, com discriminação das rotas e seus respectivos arcos.
Requer a criação de um login no link acima.

O banco de dados de radares do município de São Paulo, que é fornecido pelas Secretarias de Mobilidade e Transportes e de Inovação e Tecnologia através de uma API, foi criado mediante registros feitos pelos equipamentos de fiscalização trânsito. Através de solicitações, a API é capaz de fornecer o período (data e horário), as coordenadas dos pares OD e as coordenadas dos pontos de passagem (capturadas por pontos de fiscalização presentes no trajeto do veículo) de uma viagem registrada (Intra - Dados de Radares - API, 2021). É importante destacar que esse banco de dados informa rotas realizadas por um dado veículo, ou seja, a rota real escolhida pelo usuário necessária para a estimação no modelo de escolha discreta. 
