# ArrowForward


```text
material-4/Navigation/ArrowForward
```

```text
include('material-4/Navigation/ArrowForward')
```



| Illustration | ArrowForward |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/ArrowForward.png) | ![illustration for ArrowForward](../../material-4/Navigation/ArrowForward.Local.png) |




## ArrowForward

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element ArrowForward
include('material-4/Navigation/ArrowForward')

' renders the element
ArrowForward('ArrowForward', 'Arrow Forward', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ArrowForward
include('material-4/Navigation/ArrowForward')

' renders the element
ArrowForward('ArrowForward', 'Arrow Forward', 'an optional tech label', 'an optional description')
@enduml
```

