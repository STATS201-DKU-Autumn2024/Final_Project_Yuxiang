# $CO_2$ Emission Dataset


The dataset available at https://github.com/owid/co2-data, curated by Our World in Data, offers comprehensive metrics on carbon dioxide (CO₂) and other greenhouse gas emissions [^1]. It encompasses annual, per capita, cumulative, and consumption-based CO₂ emissions, as well as data on other greenhouse gases and energy mixes. Regularly updated, this dataset serves as a valuable resource for analyzing global and national emission trends and energy profiles.

Here’s the data dictionary of this dataset.

---

## Data Dictionary

| Variable Name                             | Definition                                                                   | Unit                                 |
|:------------------------------------------|:-----------------------------------------------------------------------------|:-------------------------------------|
| country                                   | Country                                                                      | nan                                  |
| year                                      | Year                                                                         | nan                                  |
| iso_code                                  | ISO code                                                                     | nan                                  |
| population                                | Population                                                                   | people                               |
| gdp                                       | Gross domestic product (GDP)                                                 | international-$ in 2011 prices       |
| cement_co2                                | Annual CO₂ emissions from cement                                             | million tonnes                       |
| cement_co2_per_capita                     | Annual CO₂ emissions from cement (per capita)                                | tonnes per person                    |
| co2                                       | Annual CO₂ emissions                                                         | million tonnes                       |
| co2_growth_abs                            | Annual CO₂ emissions growth (abs)                                            | million tonnes                       |
| co2_growth_prct                           | Annual CO₂ emissions growth (%)                                              | %                                    |
| co2_including_luc                         | Annual CO₂ emissions including land-use change                               | million tonnes                       |
| co2_including_luc_growth_abs              | Growth rate of emissions including land-use change                           | million tonnes                       |
| co2_including_luc_growth_prct             | Growth rate of emissions including land-use change (%)                       | %                                    |
| co2_including_luc_per_capita              | Annual CO₂ emissions including land-use change per capita                    | tonnes per person                    |
| co2_including_luc_per_gdp                 | Annual CO₂ emissions including land-use change per GDP                       | kilograms per international-$        |
| co2_including_luc_per_unit_energy         | Annual CO₂ emissions including land-use change per unit energy               | kilograms per kilowatt-hour          |
| co2_per_capita                            | Annual CO₂ emissions (per capita)                                            | tonnes per person                    |
| co2_per_gdp                               | Annual CO₂ emissions per GDP (kg per international-$)                        | kilograms per international-$        |
| co2_per_unit_energy                       | Annual CO₂ emissions per unit energy (kg per kilowatt-hour)                  | kilograms per kilowatt-hour          |
| coal_co2                                  | Annual CO₂ emissions from coal                                               | million tonnes                       |
| coal_co2_per_capita                       | Annual CO₂ emissions from coal (per capita)                                  | tonnes per person                    |
| consumption_co2                           | Annual consumption-based CO₂ emissions                                       | million tonnes                       |
| consumption_co2_per_capita                | Per capita consumption-based CO₂ emissions                                   | tonnes per person                    |
| consumption_co2_per_gdp                   | Annual consumption-based CO₂ emissions per GDP (kg per international-$)      | kilograms per international-$        |
| cumulative_cement_co2                     | Cumulative CO₂ emissions from cement                                         | million tonnes                       |
| cumulative_co2                            | Cumulative CO₂ emissions                                                     | million tonnes                       |
| cumulative_co2_including_luc              | Cumulative CO₂ emissions including land-use change                           | million tonnes                       |
| cumulative_coal_co2                       | Cumulative CO₂ emissions from coal                                           | million tonnes                       |
| cumulative_flaring_co2                    | Cumulative CO₂ emissions from flaring                                        | million tonnes                       |
| cumulative_gas_co2                        | Cumulative CO₂ emissions from gas                                            | million tonnes                       |
| cumulative_luc_co2                        | Cumulative CO₂ emissions from land-use change                                | million tonnes                       |
| cumulative_oil_co2                        | Cumulative CO₂ emissions from oil                                            | million tonnes                       |
| cumulative_other_co2                      | Cumulative CO₂ emissions from other industry                                 | million tonnes                       |
| energy_per_capita                         | Primary energy consumption per capita                                        | kilowatt-hours per person            |
| energy_per_gdp                            | Primary energy consumption per GDP                                           | kilowatt-hours per $                 |
| flaring_co2                               | Annual CO₂ emissions from flaring                                            | million tonnes                       |
| flaring_co2_per_capita                    | Annual CO₂ emissions from flaring (per capita)                               | tonnes per person                    |
| gas_co2                                   | Annual CO₂ emissions from gas                                                | million tonnes                       |
| gas_co2_per_capita                        | Annual CO₂ emissions from gas (per capita)                                   | tonnes per person                    |
| ghg_excluding_lucf_per_capita             | Per capita greenhouse gas emissions from fossil fuels and industry           | tonnes of CO₂ equivalents per person |
| ghg_per_capita                            | Per capita greenhouse gas emissions including land use                       | tonnes of CO₂ equivalents per person |
| land_use_change_co2                       | Annual CO₂ emissions from land-use change                                    | million tonnes                       |
| land_use_change_co2_per_capita            | Annual CO₂ emissions from land-use change per capita                         | tonnes per person                    |
| methane                                   | Annual methane emissions including land use                                  | million tonnes                       |
| methane_per_capita                        | Per capita methane emissions including land use                              | tonnes of CO₂ equivalents per person |
| nitrous_oxide                             | Annual nitrous oxide emissions including land use                            | million tonnes                       |
| nitrous_oxide_per_capita                  | Per capita nitrous oxide emissions including land use                        | tonnes of CO₂ equivalents per person |
| oil_co2                                   | Annual CO₂ emissions from oil                                                | million tonnes                       |
| oil_co2_per_capita                        | Annual CO₂ emissions from oil (per capita)                                   | tonnes per person                    |
| other_co2_per_capita                      | Annual CO₂ emissions from other industry (per capita)                        | tonnes per person                    |
| other_industry_co2                        | Annual CO₂ emissions from other industry                                     | million tonnes                       |
| primary_energy_consumption                | Primary energy consumption                                                   | terawatt-hours                       |
| share_global_cement_co2                   | Share of global annual CO₂ emissions from cement                             | %                                    |
| share_global_co2                          | Share of global annual CO₂ emissions                                         | %                                    |
| share_global_co2_including_luc            | Share of global annual CO₂ emissions including land-use change               | %                                    |
| share_global_coal_co2                     | Share of global annual CO₂ emissions from coal                               | %                                    |
| share_global_cumulative_cement_co2        | Share of global cumulative CO₂ emissions from cement                         | %                                    |
| share_global_cumulative_co2               | Share of global cumulative CO₂ emissions                                     | %                                    |
| share_global_cumulative_co2_including_luc | Share of global cumulative CO₂ emissions including land-use change           | %                                    |
| share_global_cumulative_coal_co2          | Share of global cumulative CO₂ emissions from coal                           | %                                    |
| share_global_cumulative_flaring_co2       | Share of global cumulative CO₂ emissions from flaring                        | %                                    |
| share_global_cumulative_gas_co2           | Share of global cumulative CO₂ emissions from gas                            | %                                    |
| share_global_cumulative_luc_co2           | Share of global cumulative CO₂ emissions from land-use change                | %                                    |
| share_global_cumulative_oil_co2           | Share of global cumulative CO₂ emissions from oil                            | %                                    |
| share_global_cumulative_other_co2         | Share of global cumulative CO₂ emissions from other industry                 | %                                    |
| share_global_flaring_co2                  | Share of global annual CO₂ emissions from flaring                            | %                                    |
| share_global_gas_co2                      | Share of global annual CO₂ emissions from gas                                | %                                    |
| share_global_luc_co2                      | Share of global annual CO₂ emissions from land-use change                    | %                                    |
| share_global_oil_co2                      | Share of global annual CO₂ emissions from oil                                | %                                    |
| share_global_other_co2                    | Share of global annual CO₂ emissions from other industry                     | %                                    |
| share_of_temperature_change_from_ghg      | Share of contribution to global warming                                      | %                                    |
| temperature_change_from_ch4               | Change in global mean surface temperature caused by methane emissions        | °C                                   |
| temperature_change_from_co2               | Change in global mean surface temperature caused by CO₂ emissions            | °C                                   |
| temperature_change_from_ghg               | Change in global mean surface temperature caused by greenhouse gas emissions | °C                                   |
| temperature_change_from_n2o               | Change in global mean surface temperature caused by nitrous oxide emissions  | °C                                   |
| total_ghg                                 | Annual greenhouse gas emissions including land use                           | million tonnes                       |
| total_ghg_excluding_lucf                  | Annual greenhouse gas emissions from fossil fuels and industry               | million tonnes                       |
| trade_co2                                 | Annual CO₂ emissions embedded in trade                                       | million tonnes                       |
| trade_co2_share                           | Share of annual CO₂ emissions embedded in trade                              | %                                    |

[^1]: Ritchie, Hannah, Max Roser, and Pablo Rosado. "CO₂ and greenhouse gas emissions." Our world in data (2023).