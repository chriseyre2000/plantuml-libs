# HourglassEmpty


```text
material-4/Action/HourglassEmpty
```

```text
include('material-4/Action/HourglassEmpty')
```



| Illustration | HourglassEmpty |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/HourglassEmpty.png) | ![illustration for HourglassEmpty](../../material-4/Action/HourglassEmpty.Local.png) |




## HourglassEmpty

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element HourglassEmpty
include('material-4/Action/HourglassEmpty')

' renders the element
HourglassEmpty('HourglassEmpty', 'Hourglass Empty', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HourglassEmpty
include('material-4/Action/HourglassEmpty')

' renders the element
HourglassEmpty('HourglassEmpty', 'Hourglass Empty', 'an optional tech label', 'an optional description')
@enduml
```

