# GaugeSimpleHigh


```text
fontawesome-6/Solid/GaugeSimpleHigh
```

```text
include('fontawesome-6/Solid/GaugeSimpleHigh')
```



| Illustration | GaugeSimpleHigh |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/GaugeSimpleHigh.png) | ![illustration for GaugeSimpleHigh](../../fontawesome-6/Solid/GaugeSimpleHigh.Local.png) |




## GaugeSimpleHigh

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element GaugeSimpleHigh
include('fontawesome-6/Solid/GaugeSimpleHigh')

' renders the element
GaugeSimpleHigh('GaugeSimpleHigh', 'Gauge Simple High', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element GaugeSimpleHigh
include('fontawesome-6/Solid/GaugeSimpleHigh')

' renders the element
GaugeSimpleHigh('GaugeSimpleHigh', 'Gauge Simple High', 'an optional tech label', 'an optional description')
@enduml
```

