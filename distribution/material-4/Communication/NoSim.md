# NoSim


```text
material-4/Communication/NoSim
```

```text
include('material-4/Communication/NoSim')
```



| Illustration | NoSim |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/NoSim.png) | ![illustration for NoSim](../../material-4/Communication/NoSim.Local.png) |




## NoSim

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element NoSim
include('material-4/Communication/NoSim')

' renders the element
NoSim('NoSim', 'No Sim', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element NoSim
include('material-4/Communication/NoSim')

' renders the element
NoSim('NoSim', 'No Sim', 'an optional tech label', 'an optional description')
@enduml
```

