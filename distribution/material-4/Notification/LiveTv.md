# LiveTv


```text
material-4/Notification/LiveTv
```

```text
include('material-4/Notification/LiveTv')
```



| Illustration | LiveTv |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Notification/LiveTv.png) | ![illustration for LiveTv](../../material-4/Notification/LiveTv.Local.png) |




## LiveTv

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element LiveTv
include('material-4/Notification/LiveTv')

' renders the element
LiveTv('LiveTv', 'Live Tv', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element LiveTv
include('material-4/Notification/LiveTv')

' renders the element
LiveTv('LiveTv', 'Live Tv', 'an optional tech label', 'an optional description')
@enduml
```

