# Angellist


```text
simpleicons-7/A/Angellist
```

```text
include('simpleicons-7/A/Angellist')
```



| Illustration | Angellist |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Angellist.png) | ![illustration for Angellist](../../simpleicons-7/A/Angellist.Local.png) |




## Angellist

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Angellist
include('simpleicons-7/A/Angellist')

' renders the element
Angellist('Angellist', 'Angellist', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Angellist
include('simpleicons-7/A/Angellist')

' renders the element
Angellist('Angellist', 'Angellist', 'an optional tech label', 'an optional description')
@enduml
```

