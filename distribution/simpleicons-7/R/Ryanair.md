# Ryanair


```text
simpleicons-7/R/Ryanair
```

```text
include('simpleicons-7/R/Ryanair')
```



| Illustration | Ryanair |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/R/Ryanair.png) | ![illustration for Ryanair](../../simpleicons-7/R/Ryanair.Local.png) |




## Ryanair

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Ryanair
include('simpleicons-7/R/Ryanair')

' renders the element
Ryanair('Ryanair', 'Ryanair', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ryanair
include('simpleicons-7/R/Ryanair')

' renders the element
Ryanair('Ryanair', 'Ryanair', 'an optional tech label', 'an optional description')
@enduml
```

