# Kaios


```text
simpleicons-7/K/Kaios
```

```text
include('simpleicons-7/K/Kaios')
```



| Illustration | Kaios |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/K/Kaios.png) | ![illustration for Kaios](../../simpleicons-7/K/Kaios.Local.png) |




## Kaios

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Kaios
include('simpleicons-7/K/Kaios')

' renders the element
Kaios('Kaios', 'Kaios', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Kaios
include('simpleicons-7/K/Kaios')

' renders the element
Kaios('Kaios', 'Kaios', 'an optional tech label', 'an optional description')
@enduml
```

