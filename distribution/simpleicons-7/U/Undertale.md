# Undertale


```text
simpleicons-7/U/Undertale
```

```text
include('simpleicons-7/U/Undertale')
```



| Illustration | Undertale |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/U/Undertale.png) | ![illustration for Undertale](../../simpleicons-7/U/Undertale.Local.png) |




## Undertale

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Undertale
include('simpleicons-7/U/Undertale')

' renders the element
Undertale('Undertale', 'Undertale', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Undertale
include('simpleicons-7/U/Undertale')

' renders the element
Undertale('Undertale', 'Undertale', 'an optional tech label', 'an optional description')
@enduml
```

