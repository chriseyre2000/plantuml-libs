# Wechat


```text
simpleicons-7/W/Wechat
```

```text
include('simpleicons-7/W/Wechat')
```



| Illustration | Wechat |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/W/Wechat.png) | ![illustration for Wechat](../../simpleicons-7/W/Wechat.Local.png) |




## Wechat

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Wechat
include('simpleicons-7/W/Wechat')

' renders the element
Wechat('Wechat', 'Wechat', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wechat
include('simpleicons-7/W/Wechat')

' renders the element
Wechat('Wechat', 'Wechat', 'an optional tech label', 'an optional description')
@enduml
```

