# Helm


```text
simpleicons-7/H/Helm
```

```text
include('simpleicons-7/H/Helm')
```



| Illustration | Helm |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/H/Helm.png) | ![illustration for Helm](../../simpleicons-7/H/Helm.Local.png) |




## Helm

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Helm
include('simpleicons-7/H/Helm')

' renders the element
Helm('Helm', 'Helm', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Helm
include('simpleicons-7/H/Helm')

' renders the element
Helm('Helm', 'Helm', 'an optional tech label', 'an optional description')
@enduml
```

