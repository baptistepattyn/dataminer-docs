---
uid: DMAAlarmTemplateParameter
---

# DMAAlarmTemplateParameter

| Item | Format | Description |
|---|---|---|
| ID                | Integer | The ID of the parameter. |
| Filter            | String  | The filter applied to the parameter, if any. |
| Info              | String  | The threshold defined for information messages, if any. |
| Hysteresis        | String  | The defined alarm hysteresis. |
| CL                | String  | The Critical Low alarm threshold. |
| MaL               | String  | The Major Low alarm threshold. |
| MiL               | String  | The Minor Low alarm threshold. |
| Normal            | String  | The Normal alarm threshold. |
| WaH               | String  | The Warning High alarm threshold. |
| MiH               | String  | The Minor High alarm threshold. |
| MaH               | String  | The Major High alarm threshold. |
| CH                | String  | The Critical High alarm threshold. |
| Monitored         | Boolean | Whether the parameter is included or excluded in alarm template groups. |
| WaL               | String  | The Warning Low alarm threshold. |
| VarianceMonitor   | Boolean | Whether alarms for variance changes are enabled. Obsolete from DataMiner 10.3.12/10.4.0 onwards<!--RN 37434-->. |
| TrendMonitor      | Boolean | Whether alarms for trend changes are enabled. Obsolete from DataMiner 10.3.12/10.4.0 onwards<!--RN 37434-->. |
| LevelShiftMonitor | Boolean | Whether alarms for level shift anomalies are enabled. Obsolete from DataMiner 10.3.12/10.4.0 onwards<!--RN 37434-->. |
| FlatlineMonitor   | Boolean | Whether alarms for flatline anomalies are enabled. Obsolete from DataMiner 10.3.12/10.4.0 onwards<!--RN 37434-->. |
| HysteresisPerSeverity | DMAHysteresisInfo | See [DMAHysteresisInfo](xref:DMAHysteresisInfo). |
| SmartBaseLine         | DMABaseline       | See [DMABaseline](xref:DMABaseline). |
| DisabledIf            | String            | A condition that determines when monitoring is disabled. |
| AutoClear             | String            | The type of automatic clearing: *False* (= no autoclear), *True* (= autoclear) or *Undef* (= the system default is applied). |
| Type                  | String            | The type of alarm thresholds: *NORMAL*, *RELATIVE*, *ABSOLUTE*, *RATE* or *DISCRETE*. |
