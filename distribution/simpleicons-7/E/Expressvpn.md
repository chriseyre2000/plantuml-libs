# Expressvpn


```text
simpleicons-7/E/Expressvpn
```

```text
include('simpleicons-7/E/Expressvpn')
```



| Illustration | Expressvpn |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/E/Expressvpn.png) | ![illustration for Expressvpn](../../simpleicons-7/E/Expressvpn.Local.png) |




## Expressvpn

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Expressvpn
include('simpleicons-7/E/Expressvpn')

' renders the element
Expressvpn('Expressvpn', 'Expressvpn', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Expressvpn
include('simpleicons-7/E/Expressvpn')

' renders the element
Expressvpn('Expressvpn', 'Expressvpn', 'an optional tech label', 'an optional description')
@enduml
```

