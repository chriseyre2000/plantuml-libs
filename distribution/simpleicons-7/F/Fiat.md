# Fiat


```text
simpleicons-7/F/Fiat
```

```text
include('simpleicons-7/F/Fiat')
```



| Illustration | Fiat |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/F/Fiat.png) | ![illustration for Fiat](../../simpleicons-7/F/Fiat.Local.png) |




## Fiat

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Fiat
include('simpleicons-7/F/Fiat')

' renders the element
Fiat('Fiat', 'Fiat', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Fiat
include('simpleicons-7/F/Fiat')

' renders the element
Fiat('Fiat', 'Fiat', 'an optional tech label', 'an optional description')
@enduml
```

