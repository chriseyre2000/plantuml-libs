# Invoiceninja


```text
simpleicons-7/I/Invoiceninja
```

```text
include('simpleicons-7/I/Invoiceninja')
```



| Illustration | Invoiceninja |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/I/Invoiceninja.png) | ![illustration for Invoiceninja](../../simpleicons-7/I/Invoiceninja.Local.png) |




## Invoiceninja

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Invoiceninja
include('simpleicons-7/I/Invoiceninja')

' renders the element
Invoiceninja('Invoiceninja', 'Invoiceninja', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Invoiceninja
include('simpleicons-7/I/Invoiceninja')

' renders the element
Invoiceninja('Invoiceninja', 'Invoiceninja', 'an optional tech label', 'an optional description')
@enduml
```

