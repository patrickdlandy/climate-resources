## climate-resources
Repository for reference information on climate change and emissions calculations

# Climate Change Resources: Social Justice Hackathon

Patrick D. Landy

[website](https://www.patrickdlandy.com)

## CO<sub>2</sub> vs CO<sub>2</sub>e

* Global warming is caused by the accumulation of greenhouse gases that are emitted into the atmosphere. Three common greenhouse gases are CO<sub>2</sub>, Methane (CH<sub>4</sub>), and Nitrous Oxide (N<sub>2</sub>O), with CO<sub>2</sub> being by far the most dominant greenhouse gas emitted by human activities.  Methane and Nitrous Oxide cause more warming per unit of mass than CO<sub>2</sub>, but because so much CO<sub>2</sub> is emitted compared to the other two, emissions are often expressed as CO<sub>2</sub> “equivalent” (CO<sub>2</sub>e), which expresses the emissions in terms of an equivalent mass of CO<sub>2</sub> released.
* 1 metric ton of methane = the same global warming as 25 metric tons of CO<sub>2</sub>
* 1 metric ton of nitrous oxide = the same global warming as 298 metric tons of CO<sub>2</sub>
* Mass of CO<sub>2</sub>e emissions = mass of CO<sub>2</sub> emissions + (25 * mass of methane emissions) + (298 * mass of nitrous oxide emissions)
* Sources: Table 8 in [EPA GHG Emissions Factors Document](https://www.epa.gov/sites/production/files/2020-04/documents/ghg-emission-factors-hub.pdf) and [Useful Summary](https://climatechangeconnection.org/emissions/co2-equivalents/)

## Climate Impact of Individuals

### Calculating carbon emissions from home energy consumption (most likely your power bills) or from transportation

* The EPA frequently publishes emissions factors for different fuel sources and for electricity based on region within the United States. See Tables 1 and 6 in the [EPA document](https://www.epa.gov/sites/production/files/2020-04/documents/ghg-emission-factors-hub.pdf).

### Electricity

* Electrical energy is measured in kilowatt-hours (kWh) on your power bill 
* For every kWh used, greenhouse gases are emitted by power plants, but the amount depends on the region (and the time of day, but that is likely beyond the scope of a residential power bill analysis)
* Example emissions calculation for NYC using the EPA factors:

| NYC Emissions From Electricity (Data and Factors)                |       |
|------------------------------------------------------------------|-------|
| Electricity consumed for month of November (My ConEd Bill) (kWh) | 100   |
| CO<sub>2</sub> factor for NYC Region (NYCW) (lb/MWh)                        | 596.4 |
| CH4 factor for NYC Region (NYCW) (lb/MWh)                        | .022  |
| N2O factor for NYC Region (NYCW) (lb/MWh)                        | .002  |
| Conversion factor (kg/lb)                                        | .454  |
| Conversion factor (Metric tons/kg) or (MT/kg)                    | .001  |
| Conversion factor (MWh/kWh)                                      | .001  |



100 kWh * .001 MWh/kWh * (596.4 lb/MWh + 25 * .022 lb/MWh + 298 * .002 lb/ MWh) * .454 kg/lb *  .001 MT/kg = .027 MT CO<sub>2</sub>e.

So 1 (estimated) month of electricity in a New York City apartment emits .027 metric tons of CO<sub>2</sub>e. Assuming the same monthly quantity, that would be .324 metric tons annually from electricity consumption.

### Gas (Heating)

* Gas is often measured on energy bills in therms.
* 1 therm of gas = 97.25 scf (standard cubic foot)
* For every therm of gas burned on your stove, in your furnace, in your building’s boiler, or in your hot water heater, emissions enter the atmosphere from combustion. This does not vary by region.
* Example gas calculation:

|  			NYC Emissions From Electricity (Data and Factors) 		     |  			  		     |
|-|-|
|  			Gas consumed for month of November (My ConEd Bill) (therms) 		     |  			5 		     |
|  			CO<sub>2</sub> factor for natural gas (kg/scf) 		     |  			.05444 		     |
|  			CH4 factor for natural gas (g/scf) 		     |  			.00103 		     |
|  			N2O factor for natural gas (g/scf) 		     |  			.00010 		     |
|  			Conversion factor (kg/g) 		     |  			.001 		     |
|  			Conversion factor (MT/kg) 		     |  			.001 		     |
|  			Conversion factor (scf/therm) 		     |  			97.25  			 		        |

5 therms * 97.25 scf/therm * (.05444 kg/scf + (25 * .00103 g/scf + 298 * .00010 g/scf) * .001 kg/g) * .001 MT/kg = .026 MT CO<sub>2</sub>e. 

### Fuel Oil (for heating) or gasoline (automobiles)

* Use the same process for natural gas, but look up the emissions per gallon from gasoline or distillate fuel oil No. 2 or No. 4 and calculate based on gallons.

### If heating is not included on a power bill

* Estimating heating fuel emissions when heat is paid for by the building (not billed to individual units) can be difficult, but New York City has tabulated energy consumption data per square foot for many building sizes in the Local Law 84 [Reports](https://www1.nyc.gov/html/gbee/html/plan/ll84_scores.shtml) 

### Calculating emissions from food

* The graphic on [this page (Our World in Data)](https://ourworldindata.org/food-choice-vs-eating-local) breaks down the estimated total life cycle CO<sub>2</sub>e emissions from different foods. This includes transportation, land use change, and other impacts. Beef is the worst by far.

### Planting Trees

* Estimated carbon captured by planting an urban tree: 36.4 lbs (see EPA calculator section on [urban tree seedlings](https://www.epa.gov/energy/greenhouse-gases-equivalencies-calculator-calculations-and-references)).

### Other Methods of Offsetting Personal Emissions

* Fund the destruction of refrigerant chemicals that have an exceptionally high global warming impact through [Tradewater](https://tradewater.us/)
* Fund clean cookstoves to reduce cooking emissions through [BURN](https://burnstoves.com/)
* Prevent deforestation through [Cool Earth](https://www.coolearth.org/)
* The best ways to donate to fight climate change according to [The Atlantic](https://www.theatlantic.com/science/archive/2020/12/how-to-donate-to-fight-climate-change-effectively/617248/) (recent article)

## Climate Impact of Larger Systems

* Project Drawdown publishes [estimates of global emissions avoided through various solutions](https://drawdown.org/solutions/table-of-solutions), often on the scale of tens of gigatons of CO<sub>2</sub>e by 2050
* The Carbon Disclosure Project published a [2017 report](https://6fefcbb86e61af1b2fc4-c70d8ead6ced550b4d987d7c03fcdd1d.ssl.cf3.rackcdn.com/cms/reports/documents/000/002/327/original/Carbon-Majors-Report-2017.pdf?1501833772) on the corporations most responsible for greenhouse gas emissions
* [Emissions by country (Our World in Data)](https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions#global-emissions-have-not-yet-peaked)
* Example of an organization working on large-scale policy advocacy: [Clean Air Task Force](https://www.catf.us/)
* Example of an organization working at the grassroots for political and systemic change: [Sunrise Movement](https://www.sunrisemovement.org/?ms=SunriseMovement)

## Background Resources on Climate Change

### Some of the best sources of current, consensus-based information on the science of climate change are the Intergovernmental Panel on Climate Change (IPCC) Reports.

* The [2018 Special Report: Global Warming of 1.5 ºC](https://www.ipcc.ch/sr15/chapter/spm/) illustrates the severity of the climate crisis by outlining the actions needed to contain global warming to a total of 1.5 ºC and avoid the worst risks of heat waves, agricultural disruptions, coastal damage, and ocean acidification, among other disruptions
* An update to the report is expected in 2021, but you can find the most recent IPCC Synthesis Report [here](https://www.ipcc.ch/report/ar5/syr/) (this is very dense, but it draws on the work of thousands of scientists across the globe, and the United Nations uses this report as a basis for climate policy). 

### The Intersection of Climate Change and Social Justice

* Climate change is being caused by the consumption of energy and land use changes necessary for industrialization and economic growth. Some countries, like European nations and the United States, have already benefitted from industrialization and greater material wealth. However, much of the world is already suffering from climate change's impacts, and many affected people had little to do with the emissions that caused the problem in the first place. In this sense, rich nations created a problem that disproportionately impacts others at an economic disadvantage.
* Sea level rise due to climate change is on track to destroy small [island nations](https://www.nationalgeographic.com/environment/2018/11/rising-seas-force-marshall-islands-relocate-elevate-artificial-islands/)
* Agricultural disruptions due to climate change may [escalate the global refugee crisis](https://www.npr.org/sections/goatsandsoda/2018/06/20/621782275/the-refugees-that-the-world-barely-pays-attention-to)
* Climate change and burning fossil fuels are creating a [public health crisis that disproportionately affects disadvantaged communities](https://www.npr.org/sections/health-shots/2020/12/02/940790818/we-dont-have-to-live-this-way-doctors-call-for-climate-action)

### Existing Carbon Calculator Apps for Reference/Inspiration

* [EPA Greenhouse Gas Equivalencies Calculator](https://www.epa.gov/energy/greenhouse-gas-equivalencies-calculator)
* [Joro](https://www.joro.tech/) (mobile app that tracks carbon using financial transactions)
