# Pandora


```text
simpleicons-7/P/Pandora
```

```text
include('simpleicons-7/P/Pandora')
```



| Illustration | Pandora |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Pandora.png) | ![illustration for Pandora](../../simpleicons-7/P/Pandora.Local.png) |




## Pandora

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Pandora
include('simpleicons-7/P/Pandora')

' renders the element
Pandora('Pandora', 'Pandora', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pandora
include('simpleicons-7/P/Pandora')

' renders the element
Pandora('Pandora', 'Pandora', 'an optional tech label', 'an optional description')
@enduml
```

