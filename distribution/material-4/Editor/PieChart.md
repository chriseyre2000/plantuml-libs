# PieChart


```text
material-4/Editor/PieChart
```

```text
include('material-4/Editor/PieChart')
```



| Illustration | PieChart |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/PieChart.png) | ![illustration for PieChart](../../material-4/Editor/PieChart.Local.png) |




## PieChart

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PieChart
include('material-4/Editor/PieChart')

' renders the element
PieChart('PieChart', 'Pie Chart', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PieChart
include('material-4/Editor/PieChart')

' renders the element
PieChart('PieChart', 'Pie Chart', 'an optional tech label', 'an optional description')
@enduml
```

