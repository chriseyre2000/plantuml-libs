# Scania


```text
simpleicons-7/S/Scania
```

```text
include('simpleicons-7/S/Scania')
```



| Illustration | Scania |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Scania.png) | ![illustration for Scania](../../simpleicons-7/S/Scania.Local.png) |




## Scania

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Scania
include('simpleicons-7/S/Scania')

' renders the element
Scania('Scania', 'Scania', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Scania
include('simpleicons-7/S/Scania')

' renders the element
Scania('Scania', 'Scania', 'an optional tech label', 'an optional description')
@enduml
```

