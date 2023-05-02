# Feature Provider

A brick to create a feature and tests using best practices and provider support!

## How to use 🚀

```
mason make feature_provider --feature_name login
```

## Variables ✨

| Variable           | Description                     | Default | Type      | Conditional | When             |
| ------------------ | ------------------------------- | ------- | --------- | ----------- | ---------------- |
| `feature_name`     | The name of the feature         | login   | `string`  | false       | N/A              |

## Outputs 📦

```
--feature_name login
├── login
│   ├── models
│   │   └── models.dart
│   ├── provider
│   │   └── provider.dart
│   ├── view
│   │   └── view.dart
│   ├── widgets
│   │   └── widgets.dart
│   └── login.dart
└── ...
```