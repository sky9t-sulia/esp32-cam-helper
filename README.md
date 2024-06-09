# ESP32-CAM Helper

This is an ESP32 compatible component for selecting pinouts for popular ESP32-CAM modules.

## Dependencies

This component depends on the `espressif/esp32-camera` component.

## Usage

Add following lines to your `idf_component.yml` file

```yaml
dependencies:
  sky9t_sulia/esp32-cam-helper:
    git: https://github.com/sky9t-sulia/esp32-cam-helper.git
  another_dependency:
    git: https://github.com/user/another_dependency.git
  ...
```

After installation, you can use this component in your ESP32 projects to easily select the correct pinouts for your ESP32-CAM modules