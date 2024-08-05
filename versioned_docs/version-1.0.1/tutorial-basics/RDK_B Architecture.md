---
sidebar_position: 1
---

# RDK_B Architecture

RDK Video Architecture is designed to enable service providers and device manufacturers to develop and deploy innovative video applications, services, and user experiences. It consists of several key components that work together seamlessly to provide a robust video platform.

By leveraging the pluggable architecture of RDK, a variety of target device profiles can be supported, ranging from a basic IP streaming-only STB to a full-fledged RDK TV. 

-   [RDK-V IP STB](https://wiki.rdkcentral.com/display/RDK/RDKV+IP)
     
    provides a common method to manage video playback functions. The IP client device serves as an interface and receives video content from an in-home media gateway device or from an external media server. It will have only IP based data streaming without any display of its own Tuner capabilities.
-   [RDK-V Hybrid STB](https://wiki.rdkcentral.com/display/RDK/RDKV+Hybrid)
     
    is an IP STB device along with capabilities such as tuning, conditional access, and stream management with which we can manage complex video functions .
-   [RDK-V IP TV](https://wiki.rdkcentral.com/display/RDK/RDK+TV)
     
    is a smart TV profile powered by RDK Video stack that brings all your favorite apps, live channels, and On Demand contents together in one place.
-   RDK Hybrid TV is a combination of
     
    [RDK TV](https://wiki.rdkcentral.com/display/RDK/RDK+TV)
     
    plus
     
    [Hybrid
     ](https://wiki.rdkcentral.com/display/RDK/RDKV+Hybrid)
    capabilities
     
    such as tuning, conditional access etc.

----------------------------------------------------------------------------

# Thumbnail

The RDK-C Thumbnail feature offers real-time thumbnails and generates thumbnails based on motion events. It includes two types of thumbnails: Next-Gen Thumbnail and Smart Thumbnail.
Thumbnail module is responsible for uploading the thumbnails with timestamp created from video analytics using Camera Feed Data.

# Summary
In summary, the SoC functionalities involve the orchestration of the Linux kernel, camera and video drivers, and ISP, collectively ensuring efficient communication with hardware components and enabling advanced image processing capabilities.
