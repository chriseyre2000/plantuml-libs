# Eclipsevertdotx


```text
simpleicons-7/E/Eclipsevertdotx
```

```text
include('simpleicons-7/E/Eclipsevertdotx')
```



| Illustration | Eclipsevertdotx |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/E/Eclipsevertdotx.png) | ![illustration for Eclipsevertdotx](../../simpleicons-7/E/Eclipsevertdotx.Local.png) |




## Eclipsevertdotx

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Eclipsevertdotx
include('simpleicons-7/E/Eclipsevertdotx')

' renders the element
Eclipsevertdotx('Eclipsevertdotx', 'Eclipsevertdotx', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Eclipsevertdotx
include('simpleicons-7/E/Eclipsevertdotx')

' renders the element
Eclipsevertdotx('Eclipsevertdotx', 'Eclipsevertdotx', 'an optional tech label', 'an optional description')
@enduml
```

