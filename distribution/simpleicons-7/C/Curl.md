# Curl


```text
simpleicons-7/C/Curl
```

```text
include('simpleicons-7/C/Curl')
```



| Illustration | Curl |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Curl.png) | ![illustration for Curl](../../simpleicons-7/C/Curl.Local.png) |




## Curl

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Curl
include('simpleicons-7/C/Curl')

' renders the element
Curl('Curl', 'Curl', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Curl
include('simpleicons-7/C/Curl')

' renders the element
Curl('Curl', 'Curl', 'an optional tech label', 'an optional description')
@enduml
```

