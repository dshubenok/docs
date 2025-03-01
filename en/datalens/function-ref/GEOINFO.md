---
editable: false
sourcePath: en/_api-ref/datalens/function-ref/GEOINFO.md
---


# GEOINFO



#### Syntax {#syntax}


```
GEOINFO( address, scale )
```

#### Description {#description}
Converts `address` to geographical name corresponding to the specified `scale`.

Possible values for `scale` parameter:
- `"country"`;
- `"country_code"`;
- `"region"`;
- `"locality"`.

The calculated field using this function must be created at the dataset level.
To enable the function, go to the [Service Settings]({{ link-datalens-settings }}) page.

**Argument types:**
- `address` — `String`
- `scale` — `String`


**Return type**: `String`

{% note info %}

Only constant values are accepted for arguments (`scale`).

{% endnote %}


#### Example {#examples}

```
GEOINFO("посёлок Свободный Серп", "country") = "Россия"
```


#### Data source support {#data-source-support}

`Materialized Dataset`.
