


# poc_energisme

Convertigo NGX builder Project


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Rest Web Service](#rest-web-service)
    - [Mappings](#mappings)
        - [/widget_conso](#widget_conso)
            - [Operations](#operations)
                - [GetOperation](#getoperation)
        - [/widget_conso_gauge](#widget_conso_gauge)
            - [Operations](#operations-1)
                - [GetOperation](#getoperation-1)
        - [/widget_conso_total](#widget_conso_total)
            - [Operations](#operations-2)
                - [GetOperation](#getoperation-2)
        - [/widget_heatmap](#widget_heatmap)
            - [Operations](#operations-3)
                - [GetOperation](#getoperation-3)
        - [/widget_maps](#widget_maps)
            - [Operations](#operations-4)
                - [GetOperation](#getoperation-4)
        - [/widget_multisite_sites_energivore](#widget_multisite_sites_energivore)
            - [Operations](#operations-5)
                - [GetOperation](#getoperation-5)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Adminstration](#adminstration)
        - [Login](#login)
        - [modalAddGroup](#modaladdgroup)
        - [modalUpdateGroup](#modalupdategroup)
        - [Monosite](#monosite)
        - [Multisite](#multisite)
        - [zoomChart](#zoomchart)
    - [Shared Components](#shared-components)
        - [gauge_chart](#gauge_chart)
        - [header](#header)
        - [heatmap](#heatmap)
        - [widget](#widget)
        - [widget_zoom](#widget_zoom)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     poc_energisme=https://github.com/convertigo/poc_energisme.git:branch=main
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     poc_energisme=https://github.com/convertigo/poc_energisme/archive/main.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __poc_energisme__ project


## Rest Web Service

### Mappings

#### /widget_conso

##### Operations

###### GetOperation

**Parameters**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>agg_function</td><td></td>
</tr>
<tr>
<td>date_end</td><td></td>
</tr>
<tr>
<td>date_start</td><td></td>
</tr>
<tr>
<td>sites</td><td></td>
</tr>
<tr>
<td>synthese</td><td></td>
</tr>
</table>

#### /widget_conso_gauge

##### Operations

###### GetOperation

**Parameters**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>agg_function</td><td></td>
</tr>
<tr>
<td>date_end</td><td></td>
</tr>
<tr>
<td>date_start</td><td></td>
</tr>
<tr>
<td>sites</td><td></td>
</tr>
<tr>
<td>synthese</td><td></td>
</tr>
</table>

#### /widget_conso_total

##### Operations

###### GetOperation

**Parameters**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>date_end</td><td></td>
</tr>
<tr>
<td>date_start</td><td></td>
</tr>
<tr>
<td>sites</td><td></td>
</tr>
<tr>
<td>synthese</td><td></td>
</tr>
</table>

#### /widget_heatmap

##### Operations

###### GetOperation

**Parameters**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>date_end</td><td></td>
</tr>
<tr>
<td>date_start</td><td></td>
</tr>
<tr>
<td>sites</td><td></td>
</tr>
<tr>
<td>synthese</td><td></td>
</tr>
</table>

#### /widget_maps

##### Operations

###### GetOperation

**Parameters**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>sites</td><td></td>
</tr>
</table>

#### /widget_multisite_sites_energivore

##### Operations

###### GetOperation

**Parameters**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>date_end</td><td></td>
</tr>
<tr>
<td>date_start</td><td></td>
</tr>
<tr>
<td>limit</td><td></td>
</tr>
<tr>
<td>sites</td><td></td>
</tr>
<tr>
<td>synthese</td><td></td>
</tr>
</table>

## Mobile Application

Describes the mobile application global properties

### Pages

#### Adminstration

#### Login

#### modalAddGroup

#### modalUpdateGroup

#### Monosite

Monosite view

#### Multisite

Multisite view

#### zoomChart

### Shared Components

#### gauge_chart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>bottomLabel</td><td>string (will be shown bellow the gauge)</td>
</tr>
<tr>
<td>canvasWidth</td><td>number</td>
</tr>
<tr>
<td>centralLabel</td><td>string</td>
</tr>
<tr>
<td>name</td><td>string (will be shown above the gauge)</td>
</tr>
<tr>
<td>needleValue</td><td>number</td>
</tr>
<tr>
<td>options</td><td>object</td>
</tr>
</table>

#### header

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>title</td><td></td>
</tr>
<tr>
<td>username</td><td>Username to display</td>
</tr>
</table>

#### heatmap

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>annotations</td><td></td>
</tr>
<tr>
<td>chart</td><td>Object</td>
</tr>
<tr>
<td>colors</td><td>Array of hexadecimal string</td>
</tr>
<tr>
<td>dataLabels</td><td>Object</td>
</tr>
<tr>
<td>fill</td><td>Object</td>
</tr>
<tr>
<td>grid</td><td>Object</td>
</tr>
<tr>
<td>labels</td><td>Array of strings</td>
</tr>
<tr>
<td>legend</td><td>Object</td>
</tr>
<tr>
<td>plotOptions</td><td>Object</td>
</tr>
<tr>
<td>responsive</td><td>Object</td>
</tr>
<tr>
<td>series</td><td>Array of objects</td>
</tr>
<tr>
<td>states</td><td>Object</td>
</tr>
<tr>
<td>stroke</td><td>Object</td>
</tr>
<tr>
<td>subtitle</td><td></td>
</tr>
<tr>
<td>theme</td><td></td>
</tr>
<tr>
<td>title</td><td>Object</td>
</tr>
<tr>
<td>tooltip</td><td>Object</td>
</tr>
<tr>
<td>xaxis</td><td>Object</td>
</tr>
<tr>
<td>yaxis</td><td>Object</td>
</tr>
</table>

#### widget

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>aggregation</td><td></td>
</tr>
<tr>
<td>displayTotalOnly</td><td></td>
</tr>
<tr>
<td>isGauge</td><td>To determine if widget is a gauge widget. true or false (string)</td>
</tr>
<tr>
<td>isGoogleMap</td><td>To determine if widget is a map widget. true or false (string)</td>
</tr>
<tr>
<td>isHeatmap</td><td>To determine if widget is a heatmap widget. true or false (string)</td>
</tr>
<tr>
<td>isInModal</td><td>To determine if widget is zoomed. true or false (string)</td>
</tr>
<tr>
<td>sequenceMarker</td><td></td>
</tr>
<tr>
<td>sequenceParams</td><td>Params of the sequence to call (object) ex: { myFirstParam: 'myValue', mySecondParam: 'myValue' }</td>
</tr>
<tr>
<td>sequenceToCall</td><td>Name of the sequence to call. If the sequence to call is in the same project then : ".mySequenceToCall" (do not forget the ".") if it's in another project then : "myProjectName.mySequenceToCall" </td>
</tr>
<tr>
<td>title</td><td>Widget title (string)</td>
</tr>
</table>

#### widget_zoom

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>aggregation</td><td></td>
</tr>
<tr>
<td>displayTotalOnly</td><td></td>
</tr>
<tr>
<td>isGauge</td><td>To determine if widget is a gauge widget. true or false (string)</td>
</tr>
<tr>
<td>isGoogleMap</td><td>To determine if widget is a map widget. true or false (string)</td>
</tr>
<tr>
<td>isHeatmap</td><td>To determine if widget is a heatmap widget. true or false (string)</td>
</tr>
<tr>
<td>isInModal</td><td>To determine if widget is zoomed. true or false (string)</td>
</tr>
<tr>
<td>sequenceMarker</td><td></td>
</tr>
<tr>
<td>sequenceParams</td><td>Params of the sequence to call (object) ex: { myFirstParam: 'myValue', mySecondParam: 'myValue' }</td>
</tr>
<tr>
<td>sequenceToCall</td><td>Name of the sequence to call. If the sequence to call is in the same project then : ".mySequenceToCall" (do not forget the ".") if it's in another project then : "myProjectName.mySequenceToCall" </td>
</tr>
<tr>
<td>title</td><td>Widget title (string)</td>
</tr>
</table>



