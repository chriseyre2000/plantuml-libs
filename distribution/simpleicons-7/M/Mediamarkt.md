# Mediamarkt


```text
simpleicons-7/M/Mediamarkt
```

```text
include('simpleicons-7/M/Mediamarkt')
```



| Illustration | Mediamarkt |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Mediamarkt.png) | ![illustration for Mediamarkt](../../simpleicons-7/M/Mediamarkt.Local.png) |




## Mediamarkt

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Mediamarkt
include('simpleicons-7/M/Mediamarkt')

' renders the element
Mediamarkt('Mediamarkt', 'Mediamarkt', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mediamarkt
include('simpleicons-7/M/Mediamarkt')

' renders the element
Mediamarkt('Mediamarkt', 'Mediamarkt', 'an optional tech label', 'an optional description')
@enduml
```

