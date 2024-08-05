---
sidebar_position: 2
---

# Evolution of RDK

From RDK6, RDK shifted from quarterly to annual release cycles, prioritizing quality through meticulous planning and comprehensive certification for improved user experience. This annual RDK Video release aims to synchronize RDK-V with standard industry release practices while comprehensively addressing shared challenges within the community. This approach facilitates the smoother and more consistent adoption of newly contributed features, utilizing the latest releases from technology partners. By aligning with SoC partners, the release enables better resource planning to support core RDK platforms. Furthermore, the RDK video release aligns with SoC, OEM, and App releases, fostering a more cohesive and efficient ecosystem. The first annual release is RDK6 and its release notes can be accessed from
[here](https://wiki.rdkcentral.com/display/RDK/RDK6+Release+Notes)

## RDK Middleware

The RDK middleware is a powerful framework that integrates various functionalities, including libcamera for camera support, OpenCV for computer vision capabilities, PipeWire for multimedia handling, WirePlumber for audio management, and RDK services for comprehensive service integration. Libcamera ensures efficient camera functionality within the middleware, while OpenCV enhances computer vision capabilities for applications. PipeWire facilitates seamless multimedia handling, offering a versatile solution for audio and video processing. WirePlumber ensures effective audio management within the middleware. RDK services provide a comprehensive suite of services, creating a robust and extensible middleware framework with broad functionality and support for diverse applications.

## RDK HAL

The RDK Hardware Abstraction Layer (HAL) is a crucial component that interfaces with hardware-specific functionalities in the RDK environment. RDK HAL leverages the libcamera pipeline for efficient camera integration, enabling streamlined communication between the hardware and higher-level software components. Additionally, it utilizes libv4l2, providing a standardized interface for video capture devices. The combination of RDK HAL, the libcamera pipeline, and libv4l2 ensures seamless integration and optimal utilization of hardware resources, enhancing the overall performance and functionality of RDK-based systems