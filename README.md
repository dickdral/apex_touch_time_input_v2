# Oracle APEX Dynamic Action Plugin -  Resize Dialog
Oracle Apex for resizing modal dialogs. 

In the attributes a margin and whether the dialog should be centered can be specified. 

## Change history
- V1.0    Initial version
- V2.0    Version for APEX 18.1 and higher

## Requirements
The plugin can be used in applications using Universal Theme from APEX 18.1 upward. 

## Install
- Import plugin file "dynamic_action_plugin_nl_detora_apex_touch_time_input.sql" from source directory into your application
- At installation you will be prompted for the default time format. This can be changed after the installation at any time. 
- The plug-in should be called in an Page Load Dynamic Action
- All items with the class 'has-time-picker' will be provided with a time picker icon

## Plugin Settings
The plugin settings are customizable and you can change:
- **Time format** - Time format for return value
- **Window base** - base value of the time window ( default 7, so time window is 7:00 to 18:55 )
## Demo Application
http://www.speech2form.com/ords/f?p=OPFG:TIME_INPUT_DEMO

## Preview
![](https://raw.githubusercontent.com/dickdral/apex-touch_time_input_v2/master/apex-touch_time_input_v2_example.gif?raw=true)
---
