# Dna


```text
fontawesome-6/Solid/Dna
```

```text
include('fontawesome-6/Solid/Dna')
```



| Illustration | Dna |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Dna.png) | ![illustration for Dna](../../fontawesome-6/Solid/Dna.Local.png) |




## Dna

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Dna
include('fontawesome-6/Solid/Dna')

' renders the element
Dna('Dna', 'Dna', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Dna
include('fontawesome-6/Solid/Dna')

' renders the element
Dna('Dna', 'Dna', 'an optional tech label', 'an optional description')
@enduml
```

