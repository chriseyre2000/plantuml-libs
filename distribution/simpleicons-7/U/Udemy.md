# Udemy


```text
simpleicons-7/U/Udemy
```

```text
include('simpleicons-7/U/Udemy')
```



| Illustration | Udemy |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/U/Udemy.png) | ![illustration for Udemy](../../simpleicons-7/U/Udemy.Local.png) |




## Udemy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Udemy
include('simpleicons-7/U/Udemy')

' renders the element
Udemy('Udemy', 'Udemy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Udemy
include('simpleicons-7/U/Udemy')

' renders the element
Udemy('Udemy', 'Udemy', 'an optional tech label', 'an optional description')
@enduml
```

