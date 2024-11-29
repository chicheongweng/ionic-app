# Ionic Capacitor Installation Guide

This guide provides step-by-step instructions to install Ionic Capacitor in your project.

## Install Ionic CLI

```sh
npm install -g @ionic/cli
```

## Create a new Ionic project

```sh
ionic start ionic-app tabs
```

## Navigate to the project directory
```sh
cd ionic-app
```

## Install Capacitor core and CLI
```sh
npm install @capacitor/core @capacitor/cli
```

## Initialize Capacitor
```sh
npx cap init
```

## Install Capacitor Android and iOS platforms
```sh
npm install @capacitor/android @capacitor/ios
```

## Add Android and iOS platforms
```sh
npx cap add android
npx cap add ios
```

## Build the Ionic project
```sh
ionic build
```

## Copy web assets to native projects
```sh
npx cap copy
```

## Open the native projects
```sh
npx cap open android
npx cap open ios
```
