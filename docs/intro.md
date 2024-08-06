# Introduction to RDK-B

Let's discover **Welcome to RDK-B**.

## Key Features

-   Configuration management : config is fetched from cloud via polling which is triggered in regular interval(can also be forced) , once the config is fetched it is parsed and saved for respective feature
-   Resolution : Supported resolutions - 480p,720p, and 1080p
-   Bit rate : 115200
-   Recording settings : 24/7 live recording with 720p resolution
-   Wi-Fi : supports 2.4GHZ and 5GHZ
-   Live video : 24/7 supported with 2way audio options enabled
-   Thumbnail : SmartThumbnail - Getting YUV frames and convert that into JPEG image for the thumbnail based on the motion detection from video analytic engine
-   24/7 video recording : CVR module which use amazon kinesis video to handle this feature
-   Firmware upgrade, RDK feature control, and Log upload through XCONF Server

------------------------------------------------------------------------
<!-- The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes. -->
