# WayPower

**WayPower** is a lightweight, cross-window manager, **Wayland-native** power management GUI built with **Rust** and the **Iced** library. It allows users to monitor and control battery status, configure power-saving settings, and receive notifications when battery power is running low.

## Features

- **Battery status monitoring**: Displays current battery percentage, charging status, and time remaining.
- **Suspend/hibernate support**: Trigger system suspend or hibernate directly from the application.
- **Low battery notifications**: Sends notifications when battery power reaches a predefined threshold.
- **Cross-desktop compatibility**: Works in any Wayland environment, regardless of the window manager (Hyprland, Sway, etc.).
- **Simple and fast**: Built with Rust for high performance and memory safety.

## Installation

### Dependencies

- **Rust**: Install [Rust](https://www.rust-lang.org/).
- **Wayland**: Your system must be running Wayland, compatible with the Wayland compositor.
- **Upower**: WayPower uses the `upower` API to gather battery information.

### Build and Run

Clone the repository and build the application:

```bash
git clone https://github.com/abubakari3bugaru/waypower.git
cd waypower
cargo build --release
```

Run the application:

```bash
cargo run
```

## License

WayPower is licensed under the MIT License. See the LICENSE file for more details.

## Contributing

We welcome contributions! Please fork the repository, create a new branch, and submit a pull request. For bug reports or feature requests, please open an issue.

## Contact

For any inquiries or suggestions, feel free to contact Abubakari Bugaru at abubakari3bugaru@gmail.com.
