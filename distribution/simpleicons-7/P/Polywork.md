# Polywork


```text
simpleicons-7/P/Polywork
```

```text
include('simpleicons-7/P/Polywork')
```



| Illustration | Polywork |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Polywork.png) | ![illustration for Polywork](../../simpleicons-7/P/Polywork.Local.png) |




## Polywork

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Polywork
include('simpleicons-7/P/Polywork')

' renders the element
Polywork('Polywork', 'Polywork', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Polywork
include('simpleicons-7/P/Polywork')

' renders the element
Polywork('Polywork', 'Polywork', 'an optional tech label', 'an optional description')
@enduml
```

