# Jekyll


```text
simpleicons-7/J/Jekyll
```

```text
include('simpleicons-7/J/Jekyll')
```



| Illustration | Jekyll |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/J/Jekyll.png) | ![illustration for Jekyll](../../simpleicons-7/J/Jekyll.Local.png) |




## Jekyll

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Jekyll
include('simpleicons-7/J/Jekyll')

' renders the element
Jekyll('Jekyll', 'Jekyll', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jekyll
include('simpleicons-7/J/Jekyll')

' renders the element
Jekyll('Jekyll', 'Jekyll', 'an optional tech label', 'an optional description')
@enduml
```

