# Manjaro


```text
simpleicons-7/M/Manjaro
```

```text
include('simpleicons-7/M/Manjaro')
```



| Illustration | Manjaro |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Manjaro.png) | ![illustration for Manjaro](../../simpleicons-7/M/Manjaro.Local.png) |




## Manjaro

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Manjaro
include('simpleicons-7/M/Manjaro')

' renders the element
Manjaro('Manjaro', 'Manjaro', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Manjaro
include('simpleicons-7/M/Manjaro')

' renders the element
Manjaro('Manjaro', 'Manjaro', 'an optional tech label', 'an optional description')
@enduml
```

