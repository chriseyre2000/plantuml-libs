# Floatplane


```text
simpleicons-7/F/Floatplane
```

```text
include('simpleicons-7/F/Floatplane')
```



| Illustration | Floatplane |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/F/Floatplane.png) | ![illustration for Floatplane](../../simpleicons-7/F/Floatplane.Local.png) |




## Floatplane

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Floatplane
include('simpleicons-7/F/Floatplane')

' renders the element
Floatplane('Floatplane', 'Floatplane', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Floatplane
include('simpleicons-7/F/Floatplane')

' renders the element
Floatplane('Floatplane', 'Floatplane', 'an optional tech label', 'an optional description')
@enduml
```

