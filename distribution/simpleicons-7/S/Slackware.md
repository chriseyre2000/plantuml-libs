# Slackware


```text
simpleicons-7/S/Slackware
```

```text
include('simpleicons-7/S/Slackware')
```



| Illustration | Slackware |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Slackware.png) | ![illustration for Slackware](../../simpleicons-7/S/Slackware.Local.png) |




## Slackware

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Slackware
include('simpleicons-7/S/Slackware')

' renders the element
Slackware('Slackware', 'Slackware', 'an optional tech label', 'an optional description')
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
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Slackware
include('simpleicons-7/S/Slackware')

' renders the element
Slackware('Slackware', 'Slackware', 'an optional tech label', 'an optional description')
@enduml
```

