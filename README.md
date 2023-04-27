# Contao Camps

Zusammenfassung der Contao-Camps

* [2023 - Regensburg](2023/camp-2023.md)
* [2022 - Potsdam](2022/camp-2022.md)
* 2021 - Camp hat nicht stattgefunden (Corona)
* 2020 - Hamburg - Ausfall wg. Corona
* [2019 - München](2019/camp-2019.md)
* [2018 - Leipzig](2018/camp-2018.md)
* [2017 - Jever](2017/camp-2017.md)
* [2016 - Nürnberg](2016/camp-2016.md)
* 2015 - Camp hat nicht stattgefunden
* [2014 - Karlsruhe](2014/camp-2014.md)
* [2013 - München](2013/camp-2013.md)
* [2012 - Essen](2012/camp-2012.md)
* [2011 - Essen](2011/camp-2011.md)
* [2010 - Stuttgart (noch als Contao Developer Conference)](2010/camp-2010.md)


```vega-lite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Teilnehmer pro Camp",
  "data": {
    "values": [
      {"a": "2010", "b": 16}, {"a": "2011", "b": 60}, {"a": "2012", "b": 50},
      {"a": "2013", "b": 50}, {"a": "2014", "b": 100}, {"a": "2015", "b": 0},
      {"a": "2016", "b": 80}, {"a": "2017", "b": 50}, {"a": "2018", "b": 80},
      {"a": "2019", "b": 80}, {"a": "2020", "b": 0}, {"a": "2021", "b": 0},
      {"a": "2022", "b": 60}, {"a": "2023", "b": 30}
    ]
  },
  "mark": "bar",
  "encoding": {
    "x": {"field": "a", "type": "nominal", "axis": {"labelAngle": -60}, "title": "Jahr"},
    "y": {"field": "b", "type": "quantitative", "title": "Teilnehmer"}
  },
  "width": 500,
  "height": 400,
  "color": {"value": "#F47C00"}
}
```
