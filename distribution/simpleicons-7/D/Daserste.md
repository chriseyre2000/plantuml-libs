# Daserste


```text
simpleicons-7/D/Daserste
```

```text
include('simpleicons-7/D/Daserste')
```



| Illustration | Daserste |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/D/Daserste.png) | ![illustration for Daserste](../../simpleicons-7/D/Daserste.Local.png) |




## Daserste

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Daserste
include('simpleicons-7/D/Daserste')

' renders the element
Daserste('Daserste', 'Daserste', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Daserste
include('simpleicons-7/D/Daserste')

' renders the element
Daserste('Daserste', 'Daserste', 'an optional tech label', 'an optional description')
@enduml
```

