# Wolframmathematica


```text
simpleicons-7/W/Wolframmathematica
```

```text
include('simpleicons-7/W/Wolframmathematica')
```



| Illustration | Wolframmathematica |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/W/Wolframmathematica.png) | ![illustration for Wolframmathematica](../../simpleicons-7/W/Wolframmathematica.Local.png) |




## Wolframmathematica

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Wolframmathematica
include('simpleicons-7/W/Wolframmathematica')

' renders the element
Wolframmathematica('Wolframmathematica', 'Wolframmathematica', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wolframmathematica
include('simpleicons-7/W/Wolframmathematica')

' renders the element
Wolframmathematica('Wolframmathematica', 'Wolframmathematica', 'an optional tech label', 'an optional description')
@enduml
```

