# Nucleo


```text
simpleicons-7/N/Nucleo
```

```text
include('simpleicons-7/N/Nucleo')
```



| Illustration | Nucleo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/N/Nucleo.png) | ![illustration for Nucleo](../../simpleicons-7/N/Nucleo.Local.png) |




## Nucleo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Nucleo
include('simpleicons-7/N/Nucleo')

' renders the element
Nucleo('Nucleo', 'Nucleo', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Nucleo
include('simpleicons-7/N/Nucleo')

' renders the element
Nucleo('Nucleo', 'Nucleo', 'an optional tech label', 'an optional description')
@enduml
```

