# Winmate


```text
simpleicons-7/W/Winmate
```

```text
include('simpleicons-7/W/Winmate')
```



| Illustration | Winmate |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/W/Winmate.png) | ![illustration for Winmate](../../simpleicons-7/W/Winmate.Local.png) |




## Winmate

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Winmate
include('simpleicons-7/W/Winmate')

' renders the element
Winmate('Winmate', 'Winmate', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Winmate
include('simpleicons-7/W/Winmate')

' renders the element
Winmate('Winmate', 'Winmate', 'an optional tech label', 'an optional description')
@enduml
```

