# MenuOpen


```text
material-4/Navigation/MenuOpen
```

```text
include('material-4/Navigation/MenuOpen')
```



| Illustration | MenuOpen |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Navigation/MenuOpen.png) | ![illustration for MenuOpen](../../material-4/Navigation/MenuOpen.Local.png) |




## MenuOpen

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element MenuOpen
include('material-4/Navigation/MenuOpen')

' renders the element
MenuOpen('MenuOpen', 'Menu Open', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element MenuOpen
include('material-4/Navigation/MenuOpen')

' renders the element
MenuOpen('MenuOpen', 'Menu Open', 'an optional tech label', 'an optional description')
@enduml
```

