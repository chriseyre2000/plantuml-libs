# OndemandVideo


```text
material-4/Notification/OndemandVideo
```

```text
include('material-4/Notification/OndemandVideo')
```



| Illustration | OndemandVideo |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Notification/OndemandVideo.png) | ![illustration for OndemandVideo](../../material-4/Notification/OndemandVideo.Local.png) |




## OndemandVideo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element OndemandVideo
include('material-4/Notification/OndemandVideo')

' renders the element
OndemandVideo('OndemandVideo', 'Ondemand Video', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element OndemandVideo
include('material-4/Notification/OndemandVideo')

' renders the element
OndemandVideo('OndemandVideo', 'Ondemand Video', 'an optional tech label', 'an optional description')
@enduml
```

