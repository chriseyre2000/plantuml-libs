# Hackerrank


```text
simpleicons-7/H/Hackerrank
```

```text
include('simpleicons-7/H/Hackerrank')
```



| Illustration | Hackerrank |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/H/Hackerrank.png) | ![illustration for Hackerrank](../../simpleicons-7/H/Hackerrank.Local.png) |




## Hackerrank

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Hackerrank
include('simpleicons-7/H/Hackerrank')

' renders the element
Hackerrank('Hackerrank', 'Hackerrank', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Hackerrank
include('simpleicons-7/H/Hackerrank')

' renders the element
Hackerrank('Hackerrank', 'Hackerrank', 'an optional tech label', 'an optional description')
@enduml
```

