# Okta


```text
simpleicons-7/O/Okta
```

```text
include('simpleicons-7/O/Okta')
```



| Illustration | Okta |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/O/Okta.png) | ![illustration for Okta](../../simpleicons-7/O/Okta.Local.png) |




## Okta

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Okta
include('simpleicons-7/O/Okta')

' renders the element
Okta('Okta', 'Okta', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Okta
include('simpleicons-7/O/Okta')

' renders the element
Okta('Okta', 'Okta', 'an optional tech label', 'an optional description')
@enduml
```

