This month's data consists of two csv files:

First, `mars_weather.csv`.

This file contains data gathered by the Curiosity Rover about the weather conditions on Mars. It covers Sol 1 (August 7, 2012) through Sol 1895 (February 27, 2018). This data was gathered by the Rover Environmental Monitoring Station (REMS) on board the rover.

| Header | Description | Data Type |
|---|---|---|
| `id` | The identification number of a single transmission | number | 
| `terrestrial_date` | The date on Earth (formatted as `month/day/year` or `m/dd/yy`). | date | 
| `sol` | The number of elapsed sols (Martian days) since Curiosity landed on Mars. | number | 
| `ls` | The solar longitude or the Mars-Sun angle, measured from the Northern Hemisphere. In the Northern Hemisphere, the spring equinox is when `ls = 0`. Since Curiosity is in the Southern Hemisphere, the following `ls` values are of importance: <br/>&bull; `ls = 0`: autumnal equinox <br/>&bull; `ls = 90` : winter solstice <br/>&bull; `ls = 180` : spring equinox <br/>&bull; `ls = 270` : summer solstice | number | 
| `month` | The Martian Month. Similarly to Earth, Martian time can be divided into 12 months. Helpful information can be found [here](http://www-mars.lmd.jussieu.fr/mars/time/solar_longitude.html).| text | 
| `min_temp` | The minimum temperature (in °C) observed during a single Martian sol. | number | 
| `max_temp` | The maximum temperature (in °C) observed during a single Martian sol. | number | 
| `pressure` | The atmospheric pressure (Pa) in Curiosity's location on Mars.  | number | 
| `atmo_opacity` | Description of the overall weather conditions on Mars for a given sol based on atmospheric opacity (e.g., `Sunny`). | text | 

For more information, see [Centro de Astrobiología](https://cab.inta-csic.es/rems/category/weather-reports/).

The second file, `BNA_weather.csv` contains weather data gathered at the Nashville International Airport over the same time period. 

|Header | Description |
|-----|-----|
| AWND | Average wind speed |
| FMTM | Time of fastest mile or fastest 1-minute wind |
| PGTM | Peak gust time |
| PRCP | Precipitation |
| PSUN | Daily percent of possible sunshine for the period |
| SNOW | Snowfall |
| SNWD | Snow depth |
| TAVG | Average Temperature |
| TMAX | Maximum temperature |
| TMIN | Minimum temperature |
| TSUN | Total sunshine for the period |
| WDF2 | Direction of fastest 2-minute wind |
| WDF5 | Direction of fastest 5-second wind |
| WSF2 | Fastest 2-minute wind speed |
| WSF5 | Fastest 5-second wind speed |
| WT01 | Fog, ice fog, or freezing fog (may include heavy fog) |
| WT02 | Heavy fog or heaving freezing fog (not always distinguished from fog) |
| WT03 | Thunder |
| WT04 | Ice pellets, sleet, snow pellets, or small hail |
| WT05 | Hail (may include small hail) |
| WT06 | Glaze or rime |
| WT08 | Smoke or haze |
| WT09 | Blowing or drifting snow |
| WT10 | Tornado, waterspout, or funnel cloud |
| WT11 | High or damaging winds |
| WT13 | Mist |
| WT14 | Drizzle |
| WT16 | Rain (may include freezing rain, drizzle, and freezing drizzle) |
| WT17 | Freezing rain |
| WT18 | Snow, snow pellets, snow grains, or ice crystals |
| WT19 | Unknown source of precipitation |
| WT21 | Ground fog |
| WT22 | Ice fog or freezing fog |