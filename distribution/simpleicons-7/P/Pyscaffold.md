# Pyscaffold


```text
simpleicons-7/P/Pyscaffold
```

```text
include('simpleicons-7/P/Pyscaffold')
```



| Illustration | Pyscaffold |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Pyscaffold.png) | ![illustration for Pyscaffold](../../simpleicons-7/P/Pyscaffold.Local.png) |




## Pyscaffold

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Pyscaffold
include('simpleicons-7/P/Pyscaffold')

' renders the element
Pyscaffold('Pyscaffold', 'Pyscaffold', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pyscaffold
include('simpleicons-7/P/Pyscaffold')

' renders the element
Pyscaffold('Pyscaffold', 'Pyscaffold', 'an optional tech label', 'an optional description')
@enduml
```

