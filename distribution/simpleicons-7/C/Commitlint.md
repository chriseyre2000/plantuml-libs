# Commitlint


```text
simpleicons-7/C/Commitlint
```

```text
include('simpleicons-7/C/Commitlint')
```



| Illustration | Commitlint |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Commitlint.png) | ![illustration for Commitlint](../../simpleicons-7/C/Commitlint.Local.png) |




## Commitlint

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Commitlint
include('simpleicons-7/C/Commitlint')

' renders the element
Commitlint('Commitlint', 'Commitlint', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Commitlint
include('simpleicons-7/C/Commitlint')

' renders the element
Commitlint('Commitlint', 'Commitlint', 'an optional tech label', 'an optional description')
@enduml
```

