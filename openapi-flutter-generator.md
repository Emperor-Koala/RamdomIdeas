# OpenAPI Spec to Flutter Code Generator
This idea is to take an [OpenAPI Spec](https://spec.openapis.org/oas/v3.1.0) file (JSON or YAML), parse it, and generate all of the models, services and state management to get a Flutter project off the ground quickly.

Ideally, the plugin would include the ability to select different options for the state management as well as for the models. For example, the models could either be generated using [Freezed](https://pub.dev/packages/freezed) or using [Equatable](https://pub.dev/packages/equatable), and the state management could either generate [Bloc/Cubit](https://pub.dev/packages/flutter_bloc) classes, or it could generate [MobX](https://pub.dev/packages/flutter_mobx) state management.

I suppose this idea could also be extended to include other frameworks like ReactJS, SolidJS, etc. 