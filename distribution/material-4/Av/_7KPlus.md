# _7KPlus


```text
material-4/Av/_7KPlus
```

```text
include('material-4/Av/_7KPlus')
```



| Illustration | _7KPlus |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Av/_7KPlus.png) | ![illustration for _7KPlus](../../material-4/Av/_7KPlus.Local.png) |




## _7KPlus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element _7KPlus
include('material-4/Av/_7KPlus')

' renders the element
_7KPlus('7kPlus', '7k Plus', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element _7KPlus
include('material-4/Av/_7KPlus')

' renders the element
_7KPlus('7kPlus', '7k Plus', 'an optional tech label', 'an optional description')
@enduml
```

