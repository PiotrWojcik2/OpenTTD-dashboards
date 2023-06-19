# OpenTTD dashboards

**Interactive dashboards created in Power BI based on OpenTTD game dataflow.**

OpenTTD is an open source transport simulator ([openTTD repository](https://github.com/OpenTTD/OpenTTD)) based upon the Transport Tycoon Deluxe created in 1994. Because it is an open source project, we could modify source code in order to gather and export relevant data to csv while playing game. That way, we could create dynamic dataflow, giving posibility to stay on track with up-to-date visualisations. 
OpenTTD dashboards are made to present the gameplay data in real time, concerning things like infrastructure maintenance or vehicles running costs. 

## Dashboards
There are 4 dashboards concerning various aspects of game economy: 
### Main dashboard
The most dynamic dashboard based upon completed orders, in which we can track the income and trasported amount of freight in time. With included filters we can focus on particular aspects, like income from transporting coal and steel by trains.

![main_dashboard](https://github.com/PiotrWojcik2/OpenTTD-dashboards/assets/96016522/b337c959-e010-465f-91fe-030169c7d156)

### Maintenance of infrastructure dashboard
Dashboard updated every in-game month, giving insights about costs of maintaining the infrastructure, like roads or airports.

![maintenance_dashboard](https://github.com/PiotrWojcik2/OpenTTD-dashboards/assets/96016522/405b6c77-902f-42da-a23f-5ad22455ec67)

### Vehicles running cost dashboard
Dashboard updated every in-game year, giving insights about running costs of four main means of transport.

![running_cost_dashboard](https://github.com/PiotrWojcik2/OpenTTD-dashboards/assets/96016522/96f38801-078a-4eb0-8848-ee923cd48247)

### KPIs dashboard
Dasboard updated as frequent as the main one, showing two types of indicators:
* **Ongoing income to costs** indicators are showing whether our company earned enough money in the running year to pay for maintaining infrastructure and vehicles, divided by means of transport,
* **Yearly income to costs** indicators are giving the same information, but in the (finalized) previous years.

There is also additional goal to beat, which in this case is the quadruple of mentioned costs.

![KPIs_dashboard](https://github.com/PiotrWojcik2/OpenTTD-dashboards/assets/96016522/f8c77151-e7f0-496a-ba66-749e32285111)

## Configuration
In order to run visualisations with included data, you have to change given file paths to your global paths. That is because Power BI does not support relative paths. You can easily change it in power query editor for each table.