# Buddy


```text
simpleicons-7/B/Buddy
```

```text
include('simpleicons-7/B/Buddy')
```



| Illustration | Buddy |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/B/Buddy.png) | ![illustration for Buddy](../../simpleicons-7/B/Buddy.Local.png) |




## Buddy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Buddy
include('simpleicons-7/B/Buddy')

' renders the element
Buddy('Buddy', 'Buddy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Buddy
include('simpleicons-7/B/Buddy')

' renders the element
Buddy('Buddy', 'Buddy', 'an optional tech label', 'an optional description')
@enduml
```

