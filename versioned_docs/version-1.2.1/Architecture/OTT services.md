# OTT services

The Application Platform Layer in the RDK ecosystem offers essential tools for developers to create applications.

## Application Platform

The Application Platform Layer in the RDK ecosystem offers essential tools for developers to create applications. It includes components like a
**UI framework**
,
**HTML5**
rendering engine, and a
**JavaScript runtime**
. Acting as middleware, this layer facilitates communication between applications and core RDK services. In the RDK Video framework,
[Firebolt®](https://rdkcentral.github.io/firebolt/apis/latest/)
handles UI rendering and user input, enabling extensive customization.
[Lightning™](https://lightningjs.io/docs/#/what-is-lightning/index)
, an open-source JavaScript platform, manages the application lifecycle and integrates components using WebGL for rendering. Together,
[Firebolt®](https://rdkcentral.github.io/firebolt/apis/latest/)
and
[Lightning™](https://lightningjs.io/docs/#/what-is-lightning/index)
form a robust foundation for seamless and efficient application development in the RDK Video ecosystem.

**Firebolt
®
1.0(Ripple) -**
Firebolt® 1.0 (Ripple) streamlines RDK app integration with standardized rules. Ripple, its open-source Rust-based Application gateway, facilitates dynamic extensions and serves as a Firebolt® Gateway. RDK 6 is Firebolt® 1.0-certified, with a comprehensive test suite for compliance.

**Security -**
The Application Platform Layer ensures robust security with Dobby-managed
**containerization**
, leveraging Linux kernel features for process isolation.
**Downloadable Application Containers (DAC)**
enable secure running of binary applications on STBs without modification, ensuring compatibility across RDK 6 devices. Access Control is enforced through
**AppArmor**
, a proactive Linux security system. RDKM's open-sourced AppArmor profile generator tool for RDK 6 provides fine-grained control over process resources, contributing to a secure environment.

## Middleware

Serving as a vital bridge between the Application Platform Layer and the hardware(HAL), the RDK Middleware Layer incorporates essential components that are pivotal for the seamless operation of the RDK platform.
Core to this layer are
**RDK services**
, providing JSON-RPC services for interactive applications.
In the realm of security,
**iCrypto**
handles critical cryptographic operations, ensuring secure communication and data protection.
**Rialto**
offers a secure solution for AV pipelines in containerized applications, and the
**Window Manager**
orchestrates GUI layout.
**Device management**
enables streamlined operations in RDK deployments, including bulk operations and firmware downloads. XCONF integration revolutionizes code downloads for a smoother deployment experience. Log uploads aid comprehensive debugging, offering insights into system performance. RDK Feature Control (RFC) enables dynamic feature management for enhanced flexibility. Telemetry systematically collects essential data insights, while WebPA ensures secure communication between cloud servers and RDK devices. The Media Player, crucial for local rendering devices, manages various pipeline functions, supporting IP and QAM playback. The
**Open Content Decryption Module(OCDM)**
enforces Digital Rights Management (DRM) policies. Together with other RDK elements, these components ensure the efficient and secure functioning of the RDK platform.


The Application Layer primarily focuses on the end-user experience. This layer contains applications that provide various services, content, and features to the users. While the RDK ecosystem is continuously evolving, supported applications typically include popular
**OTT services**
like Netflix, Amazon Prime Video, and YouTube, alongside native broadcaster applications and other services.

## Application Platform

The Application Platform Layer in the RDK ecosystem offers essential tools for developers to create applications. 
