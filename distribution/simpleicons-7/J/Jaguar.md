# Jaguar


```text
simpleicons-7/J/Jaguar
```

```text
include('simpleicons-7/J/Jaguar')
```



| Illustration | Jaguar |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/J/Jaguar.png) | ![illustration for Jaguar](../../simpleicons-7/J/Jaguar.Local.png) |




## Jaguar

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Jaguar
include('simpleicons-7/J/Jaguar')

' renders the element
Jaguar('Jaguar', 'Jaguar', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jaguar
include('simpleicons-7/J/Jaguar')

' renders the element
Jaguar('Jaguar', 'Jaguar', 'an optional tech label', 'an optional description')
@enduml
```

