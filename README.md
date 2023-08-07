# Allied Vision CSI-2 Adapter Board for NVIDIA Jetson AGX Orin Xavier TX2 Dev Kit

![Orin_Adapter_Board_1](/Images/Orin_Adapter_Board_1.png)
![Orin_Adapter_Board_2](/Images/Orin_Adapter_Board_2.png)

This repository contains open hardware design files for an adapter board supporting the Allied Vision Alvium CSI-2 camera pinout to NVIDIA's
AGX Orin Developer Kit. The board allows the user to interface with two Alvium MIPI CSI-2 compatible cameras over a Flexible Flat Cable (FFC) connector.

This adapter is similar to the 
[Adapter Board for Nvidia Jetson TX2 Xavier Dev Kit](https://github.com/alliedvision/adapter_Nvidia_Jetson_TX2_Xavier_DevKit), but with a higher connector optimized for the AGX Orin Developer Kit and with minor changes of the default I/O configuration.

AGX Xavier and TX2 Developer Kits are also supported.

You can also purchase the adapter from [Allied Vision](https://www.alliedvision.com/en/products/accessories/interface-connections/#!?cameraInterfacefilter=10) or from our [distributors](https://www.alliedvision.com/en/avt-locations/avt-distributors/).

## Getting Started

These instructions will get you a copy of the design files to make your own adapter boards for development and testing purposes. 
The board can be produced and assembled using the provided design files. Please take a look at the mechanical layers for more information regarding the PCB stackup recommended for fabrication. 

More information is available on our website:

* [User Guide (PDF)](https://cdn.alliedvision.com/fileadmin/content/documents/products/accessories/embedded/user-guide/Jetson-AGX-Orin-Xavier_TX2_Adapter_User-Guide.pdf)
* [Accessories webpage](https://www.alliedvision.com/en/products/accessories/interface-connections/#!?cameraInterfacefilter=10) 
* [Accessories download webpage](https://www.alliedvision.com/en/support/accessory-documentation/)
* [Alvium CSI-2 download webpage](https://www.alliedvision.com/en/support/technical-documentation/alvium-csi-2-documentation/) 

### Prerequisites

* A running installation of Altium.
* A PCB producer & PCBA manufacturer or some soldering skills.
* One of the supported embedded boards:
	* NVIDIA Jetson AGX Orin Developer Kit
  * NVIDIA Jetson AGX Xavier Developer Kit
  * NVIDIA Jetson TX2 Developer Kit 	

* One or two supported MIPI CSI-2 FPC cables, Allied Vision product codes
 18947, 12316, 12317, 12318 
* [One or two Allied Vision Alvium CSI-2 cameras](https://www.alliedvision.com/en/products/embedded-vision-cameras.html)

### Installing

Open the *CSI2-TX2-XAVIER_Rev02.PrjPcb* project file in your Altium environment.

## Built With

[Altium Designer 22](https://www.altium.com/altium-designer/de)
 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

