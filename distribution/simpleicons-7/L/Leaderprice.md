# Leaderprice


```text
simpleicons-7/L/Leaderprice
```

```text
include('simpleicons-7/L/Leaderprice')
```



| Illustration | Leaderprice |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/L/Leaderprice.png) | ![illustration for Leaderprice](../../simpleicons-7/L/Leaderprice.Local.png) |




## Leaderprice

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Leaderprice
include('simpleicons-7/L/Leaderprice')

' renders the element
Leaderprice('Leaderprice', 'Leaderprice', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Leaderprice
include('simpleicons-7/L/Leaderprice')

' renders the element
Leaderprice('Leaderprice', 'Leaderprice', 'an optional tech label', 'an optional description')
@enduml
```

