## Prereuisites
* Flutter SDK installed on your system. Download from Flutter website.
* Dart programming language (bundled with Flutter).
* IDE like Visual Studio Code or Android Studio configured for Flutter development.

*    dependencies:
        http:
        googleapis:
        google_sign_in:
    
## Add these dependencies to your pubspec.yaml file and run:

* flutter pub get

## Setting up your project and running code samples

1. Create a Flutter project:
    * flutter create project_name
    * cd project_name

2. Configure Google APIs:
    * Create a project in the Google API Console.
    * Set up OAuth 2.0 credentials and download the client_secrets.json file.
    * Place the client_secrets.json file in your project's assets directory and update the pubspec.yaml to include it:
        * assets:
              - assets/client_secrets.json


