# Taobao


```text
simpleicons-7/T/Taobao
```

```text
include('simpleicons-7/T/Taobao')
```



| Illustration | Taobao |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/T/Taobao.png) | ![illustration for Taobao](../../simpleicons-7/T/Taobao.Local.png) |




## Taobao

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Taobao
include('simpleicons-7/T/Taobao')

' renders the element
Taobao('Taobao', 'Taobao', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Taobao
include('simpleicons-7/T/Taobao')

' renders the element
Taobao('Taobao', 'Taobao', 'an optional tech label', 'an optional description')
@enduml
```

