# Codersrank


```text
simpleicons-7/C/Codersrank
```

```text
include('simpleicons-7/C/Codersrank')
```



| Illustration | Codersrank |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Codersrank.png) | ![illustration for Codersrank](../../simpleicons-7/C/Codersrank.Local.png) |




## Codersrank

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Codersrank
include('simpleicons-7/C/Codersrank')

' renders the element
Codersrank('Codersrank', 'Codersrank', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Codersrank
include('simpleicons-7/C/Codersrank')

' renders the element
Codersrank('Codersrank', 'Codersrank', 'an optional tech label', 'an optional description')
@enduml
```

