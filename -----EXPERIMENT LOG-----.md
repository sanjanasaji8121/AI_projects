\-----EXPERIMENT LOG-----

|Index|Experiment|Recall|Precision|F1|
|-|-|-|-|-|
|0|Baseline (original dataset)|0.263|0.699|0.382|
|1|class\_weight='balanced' was added as a parameter|0.773|0.286|0.417|
|2|class\_weight='balanced' + threshold=0.3(selected manually by experimentation i.e. threshold tuning)|0.900|0.196|0.322|
|3|Frequency encoding<br />|0.995|0.111|0.200|
|4|row level statistics+ frequency encoding|0.953|0.159|0.273|
|5|outlier clipping|o.899|0.195|0.321|



