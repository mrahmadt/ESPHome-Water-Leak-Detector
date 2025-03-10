## ESPHome Water Leak Detector

A DIY water leak detection system built with [ESPHome](https://esphome.io/) and [Home Assistant](https://www.home-assistant.io/), designed to detect water leaks or identify taps accidentally left running. It utilizes a [YF-B10-S water flow sensor](https://s.click.aliexpress.com/e/_oFxFCpf) installed on the main water supply pipe (from your rooftop tank or directly from the main supply line).

This solution complements traditional floor-based water sensors, such as the [Tuya Smart Water Leak Sensor](https://s.click.aliexpress.com/e/_oCZu8Cd), by detecting hidden leaks like toilet tank leaks, faulty taps, or pipe issues.

The system sends real-time notifications and alerts via Home Assistant, helping you to quickly respond and prevent water damage and excessive water usage.

### Included in this repository:

- ESPHome YAML configuration.
- Home Assistant automation YAML.
- Code to be included in configuration.yaml

### Contributions

The solution is functional but has room for improvement (e.g., better flow measurement accuracy, distinguishing between types of leaks). Contributions and improvements are highly encouraged!

> **Note:** This solution requires some plumbing work. Alternative solutions, such as ultrasonic sensors, were either unreliable or costly in my testing.

