# Selenium


```text
simpleicons-7/S/Selenium
```

```text
include('simpleicons-7/S/Selenium')
```



| Illustration | Selenium |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Selenium.png) | ![illustration for Selenium](../../simpleicons-7/S/Selenium.Local.png) |




## Selenium

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Selenium
include('simpleicons-7/S/Selenium')

' renders the element
Selenium('Selenium', 'Selenium', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Selenium
include('simpleicons-7/S/Selenium')

' renders the element
Selenium('Selenium', 'Selenium', 'an optional tech label', 'an optional description')
@enduml
```

