# Ovh


```text
simpleicons-7/O/Ovh
```

```text
include('simpleicons-7/O/Ovh')
```



| Illustration | Ovh |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/O/Ovh.png) | ![illustration for Ovh](../../simpleicons-7/O/Ovh.Local.png) |




## Ovh

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Ovh
include('simpleicons-7/O/Ovh')

' renders the element
Ovh('Ovh', 'Ovh', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ovh
include('simpleicons-7/O/Ovh')

' renders the element
Ovh('Ovh', 'Ovh', 'an optional tech label', 'an optional description')
@enduml
```

