# Faceit


```text
simpleicons-7/F/Faceit
```

```text
include('simpleicons-7/F/Faceit')
```



| Illustration | Faceit |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/F/Faceit.png) | ![illustration for Faceit](../../simpleicons-7/F/Faceit.Local.png) |




## Faceit

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Faceit
include('simpleicons-7/F/Faceit')

' renders the element
Faceit('Faceit', 'Faceit', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Faceit
include('simpleicons-7/F/Faceit')

' renders the element
Faceit('Faceit', 'Faceit', 'an optional tech label', 'an optional description')
@enduml
```

