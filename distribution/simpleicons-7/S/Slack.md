# Slack


```text
simpleicons-7/S/Slack
```

```text
include('simpleicons-7/S/Slack')
```



| Illustration | Slack |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Slack.png) | ![illustration for Slack](../../simpleicons-7/S/Slack.Local.png) |




## Slack

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Slack
include('simpleicons-7/S/Slack')

' renders the element
Slack('Slack', 'Slack', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Slack
include('simpleicons-7/S/Slack')

' renders the element
Slack('Slack', 'Slack', 'an optional tech label', 'an optional description')
@enduml
```

