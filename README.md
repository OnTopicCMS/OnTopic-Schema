# OnTopic Reference Schemas
This project provides a number of reference schemas that can be used to bootstrap an [OnTopic application](https://github.com/OnTopicCMS/OnTopic-Library). These can be imported using the [OnTopic Editor](https://github.com/OnTopicCMS/OnTopic-Editor-AspNetCore)'s import capabilities.

## Schemas
- [`Root:Configuration`](Root.Configuration.json): Establishes a minimum configuration for the OnTopic Library and Editor, including `ContentTypes`, `Attributes`, and `Metadata`.

### Metadata
The `Root:Configuration:Metadata` configuration provides a number of `Lookup` lists which can be bound to `TopicList` attributes in the OnTopic Editor to create dropdown lists. A number of these come out-of-the-box with the [core configuration schema](Root.Configuration.json). In addition, the following are available:
- [`Country`](Metadata/Root.Configuration.Metadata.Country.json): A current list of all countries.