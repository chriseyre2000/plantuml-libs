# EmojiFoodBeverage


```text
material-4/Social/EmojiFoodBeverage
```

```text
include('material-4/Social/EmojiFoodBeverage')
```



| Illustration | EmojiFoodBeverage |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Social/EmojiFoodBeverage.png) | ![illustration for EmojiFoodBeverage](../../material-4/Social/EmojiFoodBeverage.Local.png) |




## EmojiFoodBeverage

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element EmojiFoodBeverage
include('material-4/Social/EmojiFoodBeverage')

' renders the element
EmojiFoodBeverage('EmojiFoodBeverage', 'Emoji Food Beverage', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element EmojiFoodBeverage
include('material-4/Social/EmojiFoodBeverage')

' renders the element
EmojiFoodBeverage('EmojiFoodBeverage', 'Emoji Food Beverage', 'an optional tech label', 'an optional description')
@enduml
```

