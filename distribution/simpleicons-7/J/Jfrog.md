# Jfrog


```text
simpleicons-7/J/Jfrog
```

```text
include('simpleicons-7/J/Jfrog')
```



| Illustration | Jfrog |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/J/Jfrog.png) | ![illustration for Jfrog](../../simpleicons-7/J/Jfrog.Local.png) |




## Jfrog

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Jfrog
include('simpleicons-7/J/Jfrog')

' renders the element
Jfrog('Jfrog', 'Jfrog', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jfrog
include('simpleicons-7/J/Jfrog')

' renders the element
Jfrog('Jfrog', 'Jfrog', 'an optional tech label', 'an optional description')
@enduml
```

