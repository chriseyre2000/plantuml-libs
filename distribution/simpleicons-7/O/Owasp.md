# Owasp


```text
simpleicons-7/O/Owasp
```

```text
include('simpleicons-7/O/Owasp')
```



| Illustration | Owasp |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/O/Owasp.png) | ![illustration for Owasp](../../simpleicons-7/O/Owasp.Local.png) |




## Owasp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Owasp
include('simpleicons-7/O/Owasp')

' renders the element
Owasp('Owasp', 'Owasp', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Owasp
include('simpleicons-7/O/Owasp')

' renders the element
Owasp('Owasp', 'Owasp', 'an optional tech label', 'an optional description')
@enduml
```

