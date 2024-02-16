# Party to live or live to party?
## Research of the Festival Industry in Spain.</br>
Research question: [is it possible to fest in Spain all year round seamlessly?](https://blog.iaac.net/party-to-live-or-live-to-party/)</br>
tools: Python 3.8, Jupyter Notebook, Pandas, GoogleDeepTranslator, BeautifulSoup, Grasshopper (Rhinoceros 3d 7), QGIS 3.28.2, Capcut.</br>
# What I learned: 
- Data mining, data cleaning, data preparation, data manipulation with Python
- Data vizualisation with QGIS and Grasshopper using dynamic maps
- Calendar-making from csv in Grasshopper, data distribution by dates
- Some festivals in tiny rural areas provide the sufficient part of local budget
- A lot of festivals have similar scenario and even name (Feria de Abril, Corpus Cristi, Sant Joan, Romeria, Carnaval, etc)
- All festivals in Catalonia were deprived of international status that alternatively does not affect their highest international attraction by tourists
- Commercial music festivals have higher KPI than public-funded
## Key takeaways
- by 2022 there is around 1000 festivals in Spain performed yearly
- festivals in Spain have categories that correlate with state and local subventions: Interes Internacional, Interes National, Interes Local
- main concentration of festivals is allocated in Catalan Countries: Catalonia, Valencia, Balearic Islands, and Galicia
## video presentation
[![Spain Festival Industry by data science](https://img.youtube.com/vi/ZXprI2yhKzI/0.jpg)](https://www.youtube.com/watch?v=ZXprI2yhKzI)
## data scources
[datasets from Ministry of Tourism of Spain and autonomous communities](https://github.com/bablowsky/Research_of_Spain_Festivals/tree/main/Storytelling_SRC)
## data manipulation
[Dataset of main Spain festivals](fiestas.csv)</br>
[Calendar definition in Grasshopper](storytelling_cal.gh)</br>
[Dataset of expenditures of tourists](g_touristos%20expenditures.csv)

## data visualization
### calendar of festivals' distribution by dates
![Alt text](visuals/calendar_fin_true.jpg?raw=true "Title")
![Calendar definition in Grasshopper](visuals/calendar_def.png)
### map of festivals by euro spent per citizen
![Alt text](visuals/allfest_euro_per_cit.jpg)
### map of festivals by amount of tourists
![Alt text](visuals/allfest_turists.jpg)
### map of festivals by tourists to locals ratio
![Alt text](visuals/allfest_turists_Vs_locals.jpg)
### histogram animated map of week distribution of festivals
![Alt text](visuals/animated_time.gif)
### map of main festivals by province
![Alt text](visuals/fiestabypro.jpg)
### map of festivals by budget
![Alt text](visuals/fiestainter%2Ball.jpg)
### map combined researched festivals and festivals de interes national
![Alt text](visuals/fiestainter%2Bnat.jpg)
### map of festivals de interes international by amount of tourists
![Alt text](visuals/fiestainter.jpg)
