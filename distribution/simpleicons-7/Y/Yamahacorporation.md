# Yamahacorporation


```text
simpleicons-7/Y/Yamahacorporation
```

```text
include('simpleicons-7/Y/Yamahacorporation')
```



| Illustration | Yamahacorporation |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/Y/Yamahacorporation.png) | ![illustration for Yamahacorporation](../../simpleicons-7/Y/Yamahacorporation.Local.png) |




## Yamahacorporation

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Yamahacorporation
include('simpleicons-7/Y/Yamahacorporation')

' renders the element
Yamahacorporation('Yamahacorporation', 'Yamahacorporation', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Yamahacorporation
include('simpleicons-7/Y/Yamahacorporation')

' renders the element
Yamahacorporation('Yamahacorporation', 'Yamahacorporation', 'an optional tech label', 'an optional description')
@enduml
```

