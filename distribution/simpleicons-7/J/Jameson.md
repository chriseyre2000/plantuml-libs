# Jameson


```text
simpleicons-7/J/Jameson
```

```text
include('simpleicons-7/J/Jameson')
```



| Illustration | Jameson |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/J/Jameson.png) | ![illustration for Jameson](../../simpleicons-7/J/Jameson.Local.png) |




## Jameson

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Jameson
include('simpleicons-7/J/Jameson')

' renders the element
Jameson('Jameson', 'Jameson', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jameson
include('simpleicons-7/J/Jameson')

' renders the element
Jameson('Jameson', 'Jameson', 'an optional tech label', 'an optional description')
@enduml
```

