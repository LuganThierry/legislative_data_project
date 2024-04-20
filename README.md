### Extração de dados legislativos

O objetivo desse projeto é extrair informações de senadores e de como votaram no Projeto de Emenda Constitucional 45/2023. 

Utilizamos as bibliotecas: **requests**, **beautifulsoup** e **pandas**.

Primeiramente, extraímos dados de cada senador (link da página pessoal, nome, partido, estado e legislatura). 

Em seguida, extraímos os dados de como cada senador votou no PEC (nome, voto e observação).

Então, adicionamos cada extração em um DataFram, combinamos-os e salvamos em formato CSV.

Adicionamos o arquivo CSV na ferramenta de visualização da dados [Flourish](https://app.flourish.studio/).

Selecionamos a visualização hierárquica com prioridade para as volunas: **voto**, **partido** e **nome do senador**. E filtramos por **estado**.  

#### Visualização radial

![image](https://github.com/LuganThierry/legislative_data_project/assets/106288264/81a1d194-ebcf-48e8-8dc1-75c1365e79d5)

#### Visualização em barras

![image](https://github.com/LuganThierry/legislative_data_project/assets/106288264/e46b8149-a57d-4db6-8075-119acfb67b72)

#### Visualização em barras por estado (voto sim)

![image](https://github.com/LuganThierry/legislative_data_project/assets/106288264/e91821c6-20a2-4e65-8fd5-f87eba4be233)

#### Visualização sunburst

![image](https://github.com/LuganThierry/legislative_data_project/assets/106288264/df63bc5b-fd85-412c-baa1-2004d4249b39)

#### Visualização em círculos

![image](https://github.com/LuganThierry/legislative_data_project/assets/106288264/249c6b2a-75fe-41ca-b0af-ee344bbfba91)

#### Visualização treemap

![image](https://github.com/LuganThierry/legislative_data_project/assets/106288264/cc2f3a9e-20b1-4077-99bb-bb7f3692434f)

