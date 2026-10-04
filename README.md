# Cassinax EngineLink

**Cassinax EngineLink** is an open-source toolkit for connecting game engines with devices, development tools, input systems, debugging workflows, and external extensions.

The project is designed around a modular architecture, allowing support for different engines, platforms, and development environments without tying the core system to a single engine or device.

## Downloads

| Package | Where |
| --- | --- |
| Unity package (`.unitypackage`) | [Unity/Unitypackages](Unity/Unitypackages) |
| Android app (`.apk`) | [APKs](APKs) |

The main Android app will be distributed through Google Play. The APKs folder holds builds that cannot be published there, such as versions for older Android releases.

Files will appear in these folders as they are released.

## Project Goals

EngineLink aims to provide a common bridge between game engines and external development tools.

The main goals are:

- Connect game engines with physical devices
- Transmit input and sensor data
- Support real-time development workflows
- Provide tools for testing and debugging
- Keep integrations modular and extensible
- Support multiple platforms and game engines
- Maintain a lightweight and developer-friendly architecture

## Initial Development

The first implementation of EngineLink will focus on **Unity**.

The initial goal is to provide a modern device connection workflow that can be used during development and testing.

Android will be one of the first supported device platforms, but it is not intended to define or limit the scope of EngineLink.

Future integrations may include additional engines, platforms, devices, and development tools.

## Architecture

EngineLink is planned around a modular structure:

```text
Cassinax EngineLink
├── Core
├── Engine Integrations
│   └── Unity
├── Platform Extensions
│   └── Android
├── Input Systems
├── Device Communication
├── Debugging Tools
└── Future Extensions
```

The architecture may change as the project evolves.

## Project Status

> Early development

EngineLink is currently in its initial development stage.

Features, APIs, protocols, project structure, and compatibility may change significantly before the first stable release.

## Open Source

Cassinax EngineLink is developed as an open-source project.

Contributions, testing, bug reports, suggestions, and discussions are welcome.

Contribution guidelines will be added as the project matures.

## Documentation

Technical documentation, integration guides, protocol specifications, and extension development information will be added during development.

## Disclaimer

Cassinax EngineLink is an independent project developed by **Cassinax Softwares**.

Third-party game engines, platforms, products, and trademarks mentioned by the project belong to their respective owners.

EngineLink is not affiliated with or endorsed by those companies unless explicitly stated.

---

Developed by **Cassinax Softwares**