# Stripe


```text
simpleicons-7/S/Stripe
```

```text
include('simpleicons-7/S/Stripe')
```



| Illustration | Stripe |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Stripe.png) | ![illustration for Stripe](../../simpleicons-7/S/Stripe.Local.png) |




## Stripe

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Stripe
include('simpleicons-7/S/Stripe')

' renders the element
Stripe('Stripe', 'Stripe', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Stripe
include('simpleicons-7/S/Stripe')

' renders the element
Stripe('Stripe', 'Stripe', 'an optional tech label', 'an optional description')
@enduml
```

