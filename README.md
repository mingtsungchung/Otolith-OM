# Age-based δ15N and δ13C values of otolith organic matter reveal the inter- and intraspecific trophic partitioning in marine fishes


This study aims to investigate the trophic trajectory of five commercially important Sciaenidae species inhabiting coastal and estuarine environments, where they experience spatial and resource competition. To achieve this, we conducted a comprehensive analysis of their trophic ecology.

The study comprises three datasets: (1)  Baseline stable isotope values, (2) Isotopic niche derived from stable isotope values of muscle tissue and otolith organic matter, and (3) Stable isotope values of otolith organic matter

## Description of the data and file structure

Baseline: The stable carbon and nitrogen isotope values of particulate organic matter (POM) were collected from inshore and offshore seawater. These samples represent the pelagic ecosystem and are compared to published data on benthic ecosystems.

| **Column name** | **Description**                                                                                                                                                                                                           | **Units** | **Data format** | **Missing data code**                                    |
| :-------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------- | :-------------- | :------------------------------------------------------- |
| Location        | The sampling location of particulate organic matter.                                                                                                                                                                      | -         | Category        | -                                                        |
| Latitude        | The latitude of the sampling location.                                                                                                                                                                                    | degree    | Number          | -                                                        |
| Longitude       | The longitude of the sampling location.                                                                                                                                                                                   | degree    | Number          | -                                                        |
| Ecosystem       | Categories as pelagic and benthic ecosystems.                                                                                                                                                                             | -         | Category        | -                                                        |
| Environment     | Categories as inshore and offshore.                                                                                                                                                                                       | -         | Category        | -                                                        |
| Year            | The sampling years.                                                                                                                                                                                                       | -         | Category        | -                                                        |
| Month           | The sampling months.                                                                                                                                                                                                      | -         | Category        | -                                                        |
| Temperature     | The temperature of the sampling location.                                                                                                                                                                                 | °C        | Number          | NA: Temperature was not recorded during sampling.        |
| Salinity        | The salinity of the sampling location.                                                                                                                                                                                    | PSU       | Number          | NA: Salinity was not recorded during sampling.           |
| d15N            | Stable nitrogen isotope value of particulate organic matter. The number in the bracket symbol represents one standard deviation.                                                                                          | ‰         | Number          | NA: The sample amount was under the detected limit.      |
| d15N.sd         | The standard deviation of stable nitrogen isotope value of particulate organic matter.                                                                                                                                    | ‰         | Number          | NA: A single estimation is without a standard deviation. |
| d13C            | Stable carbon isotope value of particulate organic matter.                                                                                                                                                                | ‰         | Number          | NA: The sample amount was saturated.                     |
| d13C.sd         | The standard deviation of stable carbon isotope value of particulate organic matter.                                                                                                                                      | ‰         | Number          | NA: A single estimation is without a standard deviation. |
| Source          | The data was obtained by this study or Nazir et al. (2024). Nazir et al. "Anthropogenic nitrogen pollution inferred by stable isotope records of crustose coralline algae." Marine Pollution Bulletin 198 (2024): 115839. | -         | Category        | -                                                        |

Isotope niche: Basic fish information—such as age, length, weight, and sampling locations—is provided. δ¹³C and δ¹⁵N values were measured in the otolith core, otolith edge, and muscle tissue to facilitate comparative analysis.

| **Column name**   | **Description**                                                               | **Units** | **Data format** | **Missing data code**                              |
| :---------------- | :---------------------------------------------------------------------------- | :-------- | :-------------- | :------------------------------------------------- |
| Species           | Five fish species analysed in this study.                                     | -         | Category        | -                                                  |
| Location          | The sampling location of particulate organic matter.                          | -         | Category        | -                                                  |
| SampleID          | Fish individual ID number.                                                    | -         | Category        | -                                                  |
| Age               | The age of the individual sample.                                             | year      | Number          | NA: The age was not estimated during the analyses. |
| Length            | The total length of the individual sample.                                    | cm        | Number          | -                                                  |
| Weight            | The total weight of the individual sample.                                    | g         | Number          | -                                                  |
| Muscle.d15N       | Stable nitrogen isotope value of muscle tissue.                               | ‰         | Number          | -                                                  |
| Muscle.d13C       | Stable carbon isotope value of muscle tissue.                                 | ‰         | Number          | -                                                  |
| Otolith.core.d15N | Stable nitrogen isotope value of the organic matter in the otolith core area. | ‰         | Number          | -                                                  |
| Otolith.edge.d15N | Stable nitrogen isotope value of the organic matter in the otolith edge area. | ‰         | Number          | -                                                  |
| Otolith.core.d13C | Stable carbon isotope value of the organic matter in the otolith core area.   | ‰         | Number          | NA: The sample amount was saturated.               |
| Otolith.edge.d13C | Stable carbon isotope value of the organic matter in the otolith edge area.   | ‰         | Number          | NA: The sample amount was saturated.               |

Otolith organic matter: Stable carbon (δ¹³C) and nitrogen (δ¹⁵N) isotope data were obtained from each layer of otolith dissolution in individual fish. These values were aligned with age estimates derived from growth ring counting and 3D scanning of otolith morphology during organic matter extraction. The dataset includes maximum, minimum, and median age estimates from both methods.

| **Column name** | **Description**                                                                                                        | **Units** | **Data format** | **Missing data code**                              |
| :-------------- | :--------------------------------------------------------------------------------------------------------------------- | :-------- | :-------------- | :------------------------------------------------- |
| Species         | Five fish species analysed in this study.                                                                              | -         | Category        | -                                                  |
| ID              | Fish individual ID number.                                                                                             | -         | Category        | -                                                  |
| Layer           | The otolith dissolution sequence. Number 1 represents the otolith core.                                                | -         | Category        | -                                                  |
| LayerID         | The otolith dissolution layers were categorised as the core, edge and the layers between the core and edge.            | -         | Category        | NA: The layers between the core and edge           |
| d15N            | Stable nitrogen isotope value of otolith organic matter. deviation.                                                    | ‰         | Number          | -                                                  |
| d13C            | Stable carbon isotope value of otolith organic matter                                                                  | ‰         | Number          | NA: The sample amount was saturated.               |
| Age.min         | The minimum age assigned to the dissolution layer of otolith organic matter.                                           | year      | Category        | NA: The age was not estimated during the analyses. |
| Age.max         | The maximum age assigned to the dissolution layer of otolith organic matter.                                           | year      | Number          | NA: The age was not estimated during the analyses. |
| Age.median      | The medium age assigned to the dissolution layer of otolith organic matter, which is based on the minimum maximum age. | year      | Number          | NA: The age was not estimated during the analyses. |

##
