# Canonical


```text
simpleicons-7/C/Canonical
```

```text
include('simpleicons-7/C/Canonical')
```



| Illustration | Canonical |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Canonical.png) | ![illustration for Canonical](../../simpleicons-7/C/Canonical.Local.png) |




## Canonical

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Canonical
include('simpleicons-7/C/Canonical')

' renders the element
Canonical('Canonical', 'Canonical', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Canonical
include('simpleicons-7/C/Canonical')

' renders the element
Canonical('Canonical', 'Canonical', 'an optional tech label', 'an optional description')
@enduml
```

