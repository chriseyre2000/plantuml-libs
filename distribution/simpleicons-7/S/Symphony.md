# Symphony


```text
simpleicons-7/S/Symphony
```

```text
include('simpleicons-7/S/Symphony')
```



| Illustration | Symphony |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Symphony.png) | ![illustration for Symphony](../../simpleicons-7/S/Symphony.Local.png) |




## Symphony

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Symphony
include('simpleicons-7/S/Symphony')

' renders the element
Symphony('Symphony', 'Symphony', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Symphony
include('simpleicons-7/S/Symphony')

' renders the element
Symphony('Symphony', 'Symphony', 'an optional tech label', 'an optional description')
@enduml
```

