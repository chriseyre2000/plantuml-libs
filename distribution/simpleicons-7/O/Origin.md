# Origin


```text
simpleicons-7/O/Origin
```

```text
include('simpleicons-7/O/Origin')
```



| Illustration | Origin |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/O/Origin.png) | ![illustration for Origin](../../simpleicons-7/O/Origin.Local.png) |




## Origin

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Origin
include('simpleicons-7/O/Origin')

' renders the element
Origin('Origin', 'Origin', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Origin
include('simpleicons-7/O/Origin')

' renders the element
Origin('Origin', 'Origin', 'an optional tech label', 'an optional description')
@enduml
```

