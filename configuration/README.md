# Application configuration

Application configuration files are located inside ```application/settings``` with a symlink in the project root. Settings are shared between server and client.

- **base.json** is used by application server
- **android.json** extends _base.json_ and overrides settings for android
- **ios.json** extends _base.json_ and overrides settings for ios

## Development VS Production

Settings directory contains 2 subdirectories _development_ and _production_ for development and production environments respectively.