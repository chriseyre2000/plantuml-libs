# Ello


```text
simpleicons-7/E/Ello
```

```text
include('simpleicons-7/E/Ello')
```



| Illustration | Ello |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/E/Ello.png) | ![illustration for Ello](../../simpleicons-7/E/Ello.Local.png) |




## Ello

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Ello
include('simpleicons-7/E/Ello')

' renders the element
Ello('Ello', 'Ello', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ello
include('simpleicons-7/E/Ello')

' renders the element
Ello('Ello', 'Ello', 'an optional tech label', 'an optional description')
@enduml
```

