# Oreilly


```text
simpleicons-7/O/Oreilly
```

```text
include('simpleicons-7/O/Oreilly')
```



| Illustration | Oreilly |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/O/Oreilly.png) | ![illustration for Oreilly](../../simpleicons-7/O/Oreilly.Local.png) |




## Oreilly

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Oreilly
include('simpleicons-7/O/Oreilly')

' renders the element
Oreilly('Oreilly', 'Oreilly', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Oreilly
include('simpleicons-7/O/Oreilly')

' renders the element
Oreilly('Oreilly', 'Oreilly', 'an optional tech label', 'an optional description')
@enduml
```

