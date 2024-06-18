# Archethic Dart workspace

This is a workspace bootstraps to work on Archethic Dart applications and libs.

It uses [Melos](https://melos.invertase.dev) to manage link between apps and local libs.


## Setup

1. Install [Melos](https://melos.invertase.dev/getting-started)
```sh
dart pub global activate melos 
```
2. Create `apps` directory
2. Clone apps you want to work on into `apps` directory.
1. Create `packages` directory
1. Clone libs you want to work on into `packages` directory.
1. [Bootstrap Melos](https://melos.invertase.dev/getting-started) to link apps to local libs
```sh
melos bootstrap
```
