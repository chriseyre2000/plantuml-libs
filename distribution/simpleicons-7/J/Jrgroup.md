# Jrgroup


```text
simpleicons-7/J/Jrgroup
```

```text
include('simpleicons-7/J/Jrgroup')
```



| Illustration | Jrgroup |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/J/Jrgroup.png) | ![illustration for Jrgroup](../../simpleicons-7/J/Jrgroup.Local.png) |




## Jrgroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Jrgroup
include('simpleicons-7/J/Jrgroup')

' renders the element
Jrgroup('Jrgroup', 'Jrgroup', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jrgroup
include('simpleicons-7/J/Jrgroup')

' renders the element
Jrgroup('Jrgroup', 'Jrgroup', 'an optional tech label', 'an optional description')
@enduml
```

