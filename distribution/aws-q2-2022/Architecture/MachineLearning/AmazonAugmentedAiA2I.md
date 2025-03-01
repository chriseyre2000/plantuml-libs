# AmazonAugmentedAiA2I


```text
aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I
```

```text
include('aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I')
```



| Illustration | AmazonAugmentedAiA2I | AmazonAugmentedAiA2ICard | AmazonAugmentedAiA2IGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I.png) | ![illustration for AmazonAugmentedAiA2I](../../../aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I.Local.png) | ![illustration for AmazonAugmentedAiA2ICard](../../../aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2ICard.Local.png) | ![illustration for AmazonAugmentedAiA2IGroup](../../../aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2IGroup.Local.png) |




## AmazonAugmentedAiA2I

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonAugmentedAiA2I
include('aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I')

' renders the element
AmazonAugmentedAiA2I('AmazonAugmentedAiA2i', 'Amazon Augmented Ai A2i', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonAugmentedAiA2I
include('aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I')

' renders the element
AmazonAugmentedAiA2I('AmazonAugmentedAiA2i', 'Amazon Augmented Ai A2i', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonAugmentedAiA2ICard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonAugmentedAiA2ICard
include('aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I')

' renders the element
AmazonAugmentedAiA2ICard('AmazonAugmentedAiA2iCard', 'Amazon Augmented Ai A2i Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonAugmentedAiA2ICard
include('aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I')

' renders the element
AmazonAugmentedAiA2ICard('AmazonAugmentedAiA2iCard', 'Amazon Augmented Ai A2i Card', 'an optional description')
@enduml
```

## AmazonAugmentedAiA2IGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonAugmentedAiA2IGroup
include('aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I')

' renders the element
AmazonAugmentedAiA2IGroup('AmazonAugmentedAiA2iGroup', 'Amazon Augmented Ai A2i Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonAugmentedAiA2IGroup
include('aws-q2-2022/Architecture/MachineLearning/AmazonAugmentedAiA2I')

' renders the element
AmazonAugmentedAiA2IGroup('AmazonAugmentedAiA2iGroup', 'Amazon Augmented Ai A2i Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

