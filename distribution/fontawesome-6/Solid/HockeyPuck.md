# HockeyPuck


```text
fontawesome-6/Solid/HockeyPuck
```

```text
include('fontawesome-6/Solid/HockeyPuck')
```



| Illustration | HockeyPuck |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/HockeyPuck.png) | ![illustration for HockeyPuck](../../fontawesome-6/Solid/HockeyPuck.Local.png) |




## HockeyPuck

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element HockeyPuck
include('fontawesome-6/Solid/HockeyPuck')

' renders the element
HockeyPuck('HockeyPuck', 'Hockey Puck', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element HockeyPuck
include('fontawesome-6/Solid/HockeyPuck')

' renders the element
HockeyPuck('HockeyPuck', 'Hockey Puck', 'an optional tech label', 'an optional description')
@enduml
```

