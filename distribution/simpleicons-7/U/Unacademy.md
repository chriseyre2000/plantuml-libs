# Unacademy


```text
simpleicons-7/U/Unacademy
```

```text
include('simpleicons-7/U/Unacademy')
```



| Illustration | Unacademy |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/U/Unacademy.png) | ![illustration for Unacademy](../../simpleicons-7/U/Unacademy.Local.png) |




## Unacademy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Unacademy
include('simpleicons-7/U/Unacademy')

' renders the element
Unacademy('Unacademy', 'Unacademy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Unacademy
include('simpleicons-7/U/Unacademy')

' renders the element
Unacademy('Unacademy', 'Unacademy', 'an optional tech label', 'an optional description')
@enduml
```

