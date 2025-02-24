# Краткая статистика

```vega-lite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v2.json",
  "description": "Description",
  "data": {
    "values": [
      {"a": "800", "b": 8},
      {"a": "900", "b": 8},
      {"a": "1000", "b": 8},
      {"a": "800", "b": 8},
      {"a": "800", "b": 8},
      {"a": "800", "b": 8},
      {"a": "800", "b": 8},
      {"a": "800", "b": 8},
      {"a": "800", "b": 8},
      {"a": "800", "b": 8},
      {"a": "800", "b": 8}
    ]
  },
  "mark": "bar",
  "encoding": {
    "x": {
      "field": "a",
      "type": "ordinal"
    },
    "y": {
      "field": "b",
      "type": "quantitative"
    }
  },
  "width": 500,
  "height": 500
}
```
