# Fsecure


```text
simpleicons-7/F/Fsecure
```

```text
include('simpleicons-7/F/Fsecure')
```



| Illustration | Fsecure |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/F/Fsecure.png) | ![illustration for Fsecure](../../simpleicons-7/F/Fsecure.Local.png) |




## Fsecure

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Fsecure
include('simpleicons-7/F/Fsecure')

' renders the element
Fsecure('Fsecure', 'Fsecure', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fsecure
include('simpleicons-7/F/Fsecure')

' renders the element
Fsecure('Fsecure', 'Fsecure', 'an optional tech label', 'an optional description')
@enduml
```

