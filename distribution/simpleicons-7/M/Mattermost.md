# Mattermost


```text
simpleicons-7/M/Mattermost
```

```text
include('simpleicons-7/M/Mattermost')
```



| Illustration | Mattermost |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Mattermost.png) | ![illustration for Mattermost](../../simpleicons-7/M/Mattermost.Local.png) |




## Mattermost

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Mattermost
include('simpleicons-7/M/Mattermost')

' renders the element
Mattermost('Mattermost', 'Mattermost', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mattermost
include('simpleicons-7/M/Mattermost')

' renders the element
Mattermost('Mattermost', 'Mattermost', 'an optional tech label', 'an optional description')
@enduml
```

