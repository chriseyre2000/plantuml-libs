# Gitignoredotio


```text
simpleicons-7/G/Gitignoredotio
```

```text
include('simpleicons-7/G/Gitignoredotio')
```



| Illustration | Gitignoredotio |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/G/Gitignoredotio.png) | ![illustration for Gitignoredotio](../../simpleicons-7/G/Gitignoredotio.Local.png) |




## Gitignoredotio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Gitignoredotio
include('simpleicons-7/G/Gitignoredotio')

' renders the element
Gitignoredotio('Gitignoredotio', 'Gitignoredotio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gitignoredotio
include('simpleicons-7/G/Gitignoredotio')

' renders the element
Gitignoredotio('Gitignoredotio', 'Gitignoredotio', 'an optional tech label', 'an optional description')
@enduml
```

