### Systems & Low-Level Software Engineer

Interested in Linux kernel bring-up, hardware enablement on ARM64 platforms, CI/CD build infrastructure, and on-device AI inference[span_10](start_span)[span_10](end_span)[span_11](start_span)[span_11](end_span)[span_12](start_span)[span_12](end_span)[span_13](start_span)[span_13](end_span).

#### Selected Work

* **Mainline Linux Hardware Porting (`uke-fedora`)** — Core contributor and collaborator porting Fedora 44 (KDE Plasma Wayland / Hyprland) to Qualcomm Snapdragon ARM64 tablet hardware (`SM7675`)[span_14](start_span)[span_14](end_span)[span_15](start_span)[span_15](end_span)[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span).
  * **Graphics & Media:** Unified DRM/KMS device nodes to resolve software rendering fallbacks (`llvmpipe`) for full Adreno OpenGL/Vulkan acceleration (`vkmark` ~8K–10K+)[span_18](start_span)[span_18](end_span)[span_19](start_span)[span_19](end_span)[span_20](start_span)[span_20](end_span), and exposed host V4L2 VA-API hardware video codecs to Flatpak sandboxes[span_21](start_span)[span_21](end_span)[span_22](start_span)[span_22](end_span).
  * **Audio & Peripherals:** Integrated smart amplifier firmware, configured ALSA mixer routing and WirePlumber sink priorities for quad-speaker playback[span_23](start_span)[span_23](end_span)[span_24](start_span)[span_24](end_span), and enabled touchscreen and pogo-pin keyboard/backlight drivers[span_25](start_span)[span_25](end_span)[span_26](start_span)[span_26](end_span)[span_27](start_span)[span_27](end_span)[span_28](start_span)[span_28](end_span).
  * **Storage & Build Infrastructure:** Fixed ext4 metadata checksums for online partition expansion (`x-systemd.growfs`)[span_29](start_span)[span_29](end_span)[span_30](start_span)[span_30](end_span)[span_31](start_span)[span_31](end_span), resolved container runtime permission conflicts, and optimized GitHub Actions RPM/rootfs build pipelines (cutting CI build times from ~45 min to ~12.5 min)[span_32](start_span)[span_32](end_span)[span_33](start_span)[span_33](end_span).
* **On-Device Edge AI (`xiaomi-pad7-npu-llm`)** — Running quantized local LLMs on Hexagon NPU hardware with lightweight web interfaces[span_34](start_span)[span_34](end_span).
* **Android Peripheral & HID Tooling (`xiaomi-keyboard-fix`)** — Diagnosed peripheral authentication handshakes, HID rebinding, and input device configurations on custom AOSP builds[span_35](start_span)[span_35](end_span)[span_36](start_span)[span_36](end_span)[span_37](start_span)[span_37](end_span).

#### Technical Stack
`Linux Kernel` • `ARM64` • `Wayland / Mesa / DRM` • `ALSA / WirePlumber` • `RPM Packaging` • `Docker / Podman` • `GitHub Actions CI` • `C++ / Python / Shell`[span_38](start_span)[span_38](end_span)[span_39](start_span)[span_39](end_span)[span_40](start_span)[span_40](end_span)[span_41](start_span)[span_41](end_span)[span_42](start_span)[span_42](end_span)[span_43](start_span)[span_43](end_span)
