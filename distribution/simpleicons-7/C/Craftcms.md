# Craftcms


```text
simpleicons-7/C/Craftcms
```

```text
include('simpleicons-7/C/Craftcms')
```



| Illustration | Craftcms |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Craftcms.png) | ![illustration for Craftcms](../../simpleicons-7/C/Craftcms.Local.png) |




## Craftcms

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Craftcms
include('simpleicons-7/C/Craftcms')

' renders the element
Craftcms('Craftcms', 'Craftcms', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Craftcms
include('simpleicons-7/C/Craftcms')

' renders the element
Craftcms('Craftcms', 'Craftcms', 'an optional tech label', 'an optional description')
@enduml
```

