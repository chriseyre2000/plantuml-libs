# Man


```text
simpleicons-7/M/Man
```

```text
include('simpleicons-7/M/Man')
```



| Illustration | Man |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Man.png) | ![illustration for Man](../../simpleicons-7/M/Man.Local.png) |




## Man

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Man
include('simpleicons-7/M/Man')

' renders the element
Man('Man', 'Man', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Man
include('simpleicons-7/M/Man')

' renders the element
Man('Man', 'Man', 'an optional tech label', 'an optional description')
@enduml
```

