# Codechef


```text
simpleicons-7/C/Codechef
```

```text
include('simpleicons-7/C/Codechef')
```



| Illustration | Codechef |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Codechef.png) | ![illustration for Codechef](../../simpleicons-7/C/Codechef.Local.png) |




## Codechef

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Codechef
include('simpleicons-7/C/Codechef')

' renders the element
Codechef('Codechef', 'Codechef', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Codechef
include('simpleicons-7/C/Codechef')

' renders the element
Codechef('Codechef', 'Codechef', 'an optional tech label', 'an optional description')
@enduml
```

