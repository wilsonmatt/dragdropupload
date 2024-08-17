# Drag Drop Upload App

## Overview
This app is an Angular 18 application designed to provide a seamless and interactive experience for uploading and previewing images. 
The app leverages Angular's powerful features and the Angular CDK Drag and Drop module to create a user-friendly interface.

## Components

### UploadComponent
- **Functionality**: Allows users to select or drag and drop images for upload.
- **Features**:
  - Drag-and-drop zone.
  - File input field.
  - Emits an event when new images are uploaded.

### PreviewComponent
- **Functionality**: Displays a preview of uploaded images.
- **Features**:
  - Utilizes Angular’s CDK Drag and Drop module for rearranging images.
  - Renders images in a responsive grid layout.

### AppComponent
- **Functionality**: Manages image state and passes it to the PreviewComponent.
- **Features**:
  - Handles image uploads using Angular signals.
  - Includes placeholder, loading, and defer directives for a better user experience.

## Development

### Development Server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Code Scaffolding
Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running Unit Tests
Run `ng test` to execute the unit tests via Karma.

### Running End-to-End Tests
Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.
