# Stop


```text
material-4/Av/Stop
```

```text
include('material-4/Av/Stop')
```



| Illustration | Stop |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/Stop.png) | ![illustration for Stop](../../material-4/Av/Stop.Local.png) |




## Stop

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Stop
include('material-4/Av/Stop')

' renders the element
Stop('Stop', 'Stop', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Stop
include('material-4/Av/Stop')

' renders the element
Stop('Stop', 'Stop', 'an optional tech label', 'an optional description')
@enduml
```

