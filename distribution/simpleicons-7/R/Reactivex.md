# Reactivex


```text
simpleicons-7/R/Reactivex
```

```text
include('simpleicons-7/R/Reactivex')
```



| Illustration | Reactivex |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/R/Reactivex.png) | ![illustration for Reactivex](../../simpleicons-7/R/Reactivex.Local.png) |




## Reactivex

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Reactivex
include('simpleicons-7/R/Reactivex')

' renders the element
Reactivex('Reactivex', 'Reactivex', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Reactivex
include('simpleicons-7/R/Reactivex')

' renders the element
Reactivex('Reactivex', 'Reactivex', 'an optional tech label', 'an optional description')
@enduml
```

