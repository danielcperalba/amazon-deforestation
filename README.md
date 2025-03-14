# Visualização do Desmatamento na Amazônia

## Descrição
Este projeto tem como objetivo visualizar a evolução do desmatamento na Amazônia Legal por meio de mapas interativos e dashboards informativos. Ele utilizará **Geopandas** e **Fiona** para manipulação de dados geoespaciais e **Folium** para a geração de mapas interativos. Além disso, será desenvolvido um **Dashboard no Power BI** para exibir a taxa de desmatamento na região.

## Funcionalidades
- Exibição da Amazônia Legal com estados, limites, municípios, unidades de conservação e terras indígenas.
- Mapa interativo utilizando **Folium**.
- Implementação de um **controle deslizante** para visualizar a evolução do desmatamento ao longo do tempo.
- Análise da taxa de desmatamento através de um **dashboard no Power BI**.

## 🛠 Tecnologias Utilizadas
- **Python**: Geopandas, Fiona, Folium
- **Power BI**: Para visualização e análise dos dados

## Fonte de Dados
Os dados utilizados no projeto são obtidos do [TerraBrasilis](http://terrabrasilis.dpi.inpe.br/), que fornece informações detalhadas sobre o desmatamento na região amazônica.

## Estrutura do Projeto
```bash
/Projeto-Desmatamento-Amazonia
├── data/               # Arquivos de dados (shapefiles, geojson, etc.)
├── notebooks/          # Notebooks Jupyter para exploração e análise dos dados
├── scripts/            # Scripts Python para processamento de dados e geração de mapas
├── dashboards/         # Arquivos do Power BI
├── README.md           # Documentação do projeto
```

## Como Usar
1. **Baixar a base de dados** do TerraBrasilis.
2. **Processar os dados geoespaciais** com Geopandas e Fiona.
3. **Gerar os mapas interativos** com Folium.
4. **Visualizar a evolução do desmatamento** utilizando o controle deslizante.
5. **Explorar os dashboards** desenvolvidos no Power BI.

## Próximos Passos
- [ ] Baixar e processar os dados do TerraBrasilis.
- [ ] Implementar o carregamento e manipulação dos dados geoespaciais.
- [ ] Criar a interface interativa do mapa com Folium.
- [ ] Construir o dashboard no Power BI.

## Contribuição
Caso queira contribuir com o projeto, fique à vontade para abrir uma **issue** ou enviar um **pull request**.

---
> Este projeto visa aumentar a conscientização sobre o desmatamento na Amazônia e fornecer insights valiosos para pesquisadores e tomadores de decisão.

