# Slickpic


```text
simpleicons-7/S/Slickpic
```

```text
include('simpleicons-7/S/Slickpic')
```



| Illustration | Slickpic |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Slickpic.png) | ![illustration for Slickpic](../../simpleicons-7/S/Slickpic.Local.png) |




## Slickpic

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Slickpic
include('simpleicons-7/S/Slickpic')

' renders the element
Slickpic('Slickpic', 'Slickpic', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Slickpic
include('simpleicons-7/S/Slickpic')

' renders the element
Slickpic('Slickpic', 'Slickpic', 'an optional tech label', 'an optional description')
@enduml
```

