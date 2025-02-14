---
uid: DashboardTrigger
---

# Trigger

This component (available from DataMiner 10.2.0/10.1.1 onwards) allows you to trigger other components either manually or automatically.

![Trigger](~/user-guide/images/Trigger.png)<br>*Trigger component in DataMiner 10.4.6*

At present, this component can only be used as a filter for a component displaying a [GQI query](xref:Creating_GQI_query) result. It will function as a refresh trigger for that query.

You can for example use this in a low-code app or a dashboard to refresh a [table component](xref:DashboardTable) based on a timer. From DataMiner 10.4.0 [CU12]/10.5.3 onwards<!--RN 41799-->, you can also use this component to refresh a [query filter component](xref:DashboardQueryFilter).

To configure the trigger:

1. Optionally, customize the following component options in the *Component* > *Settings* pane:

   - *Trigger timer*: Determines whether the trigger will automatically go off based on a timer. If this option is enabled, a countdown bar will show when the trigger will go off again.

   - *Time*: If *Trigger Timer* is selected, this setting determines after how many seconds the data is refreshed. By default, this is set to 60 seconds.

1. Optionally, fine-tune the component layout. In the *Component* > *Layout* pane, the following options are available:

   - The default options available for all components. See [Customizing the component layout](xref:Customize_Component_Layout).

   - *Label*: Allows you to specify text that should be displayed on the trigger button.

   - *Icon*: Allows you to select which icon will be displayed on the trigger button.

   - *Show when the last trigger happened*: Select this option to have the component display when the trigger last went off.

   - *Time description format*: If *Show when the last trigger happened* is selected, in this box you can customize the format in which the time when the trigger last went off is displayed. The following placeholders are supported in this format:

     | Placeholder | Description    |
     |-------------|----------------|
     | {duration}  | The approximate time since the trigger last went off. Example: “2 minutes ago” |
     | {time}      | The exact time when the trigger last went off. Example: “Nov 20, 2020, 12:33”  |

   - *Align*: Determines whether the label and icon are displayed on the left side, in the middle or on the right side of the component.

1. Select the trigger component data in the *Data* pane and drag it to the component (e.g. a table component) that should be refreshed based on the trigger.
