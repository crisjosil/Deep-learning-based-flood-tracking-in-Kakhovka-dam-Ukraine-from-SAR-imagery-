# Deep-learning-based flood tracking in Kakhovka dam Ukraine from SAR imagery-
Our team has been monitoring a recent flood event in Ukraine caused by the collapse of the Kakhovka dam. We are using using SAR imagery and cutting-edge deep learning models to do so. We have been able to track the extent of the flooding, identify affected areas, and assess the impact on communities. By leveraging these powerful images, we're able to provide real-time updates and crucial information to aid emergency response teams and help those affected. Read more [here](https://www.doorsblacksea.eu/post/721205312722485249/doors-scientists-respond-to-the-kakhovka-dam).

Tracking flood extent in Near-Real-time downstream of the Kakhovka dam (Ukraine) using Early fusion attention UNET and/or a Siamese network with nested UNET.

The following is a multitemporal RGB of pre and post-event Sentinel-1 images showing in blue the surface area covered by water after the dam collapsed. 

![Alt text](./Flood_tracking_maps/20230609_S1_Multitemporal_RGB.png?raw=true "Kakhovka dam flood extent (Ukraine)")

After implementing and testing different configurations of deep semantic segmenation models, we found that an early fusion attention UNET and/or a Siamese network with nested UNET can be utilised to extract flood extent masks from sentinel-1 imagery. The following corresponds to the flood extent as of 20230609:

![Alt text](./Flood_tracking_maps/20230609_S1_Flood_extent.png?raw=true "Kakhovka dam flood extent (Ukraine)")

Crutially, Sentinel-1 allows us to track the flood extent after new acquisitions are available: 

![Alt text](./Flood_tracking_maps/20230613_Flood_tracking.png?raw=true "Kakhovka dam flood extent (Ukraine)")

The image above shows in dark blue the flood extent as of 20230609, in light blue the flood extent as of 20230613 and in yellow the permanent water bodies. Finally, we can zoom in to obtain some more details of the specific areas impacted by the flood waters. The city of Kerson which was highly impacted by the dam collapsed shows the following:

![Alt text](./Flood_tracking_maps/20230613_Kerson_zoom2.png?raw=true "Kakhovka dam flood extent (Ukraine)")



