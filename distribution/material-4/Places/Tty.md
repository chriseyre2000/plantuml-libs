# Tty


```text
material-4/Places/Tty
```

```text
include('material-4/Places/Tty')
```



| Illustration | Tty |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Places/Tty.png) | ![illustration for Tty](../../material-4/Places/Tty.Local.png) |




## Tty

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Tty
include('material-4/Places/Tty')

' renders the element
Tty('Tty', 'Tty', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Tty
include('material-4/Places/Tty')

' renders the element
Tty('Tty', 'Tty', 'an optional tech label', 'an optional description')
@enduml
```

