# Playstation


```text
simpleicons-7/P/Playstation
```

```text
include('simpleicons-7/P/Playstation')
```



| Illustration | Playstation |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Playstation.png) | ![illustration for Playstation](../../simpleicons-7/P/Playstation.Local.png) |




## Playstation

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Playstation
include('simpleicons-7/P/Playstation')

' renders the element
Playstation('Playstation', 'Playstation', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Playstation
include('simpleicons-7/P/Playstation')

' renders the element
Playstation('Playstation', 'Playstation', 'an optional tech label', 'an optional description')
@enduml
```

