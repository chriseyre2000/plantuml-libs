# Shieldsdotio


```text
simpleicons-7/S/Shieldsdotio
```

```text
include('simpleicons-7/S/Shieldsdotio')
```



| Illustration | Shieldsdotio |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Shieldsdotio.png) | ![illustration for Shieldsdotio](../../simpleicons-7/S/Shieldsdotio.Local.png) |




## Shieldsdotio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Shieldsdotio
include('simpleicons-7/S/Shieldsdotio')

' renders the element
Shieldsdotio('Shieldsdotio', 'Shieldsdotio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Shieldsdotio
include('simpleicons-7/S/Shieldsdotio')

' renders the element
Shieldsdotio('Shieldsdotio', 'Shieldsdotio', 'an optional tech label', 'an optional description')
@enduml
```

