# Deep-learning-based flood tracking in Kakhovka dam Ukraine from SAR imagery-
Tracking flood extent in Near-Real-time downstream of the Kakhovka dam (Ukraine) using Early fusion attention UNET and/or a Siamese network with nested UNET.

The following is a multitemporal RGB of pre and post-event Sentinel-1 images showing in blue the surface area covered by water after the dam collapsed. 

![Alt text](./Flood_tracking_maps/20230609_S1_Multitemporal_RGB.png?raw=true "Kakhovka dam flood extent (Ukraine)")

After implementing and testing different configurations of deep semantic segmenation models, we found that an early fusion attention UNET and/or a Siamese network with nested UNET can be utilised to extract flood extent masks from sentinel-1 imagery. The following corresponds to the flood extent as of 20230609:

![Alt text](./Flood_tracking_maps/20230609_S1_Flood_extent.png?raw=true "Kakhovka dam flood extent (Ukraine)")

Crutially, Sentinel-1 allows us to track the flood extent after new acquisitions are available: 

![Alt text](./Flood_tracking_maps/20230613_S1_Flood_tracking.png?raw=true "Kakhovka dam flood extent (Ukraine)")

The image above shows in dark blue the flood extent as of 20230609, in light blue the flood extent as of 20230613 and in yellow the permanent water bodies. Finally, we can zoom in to obtain some more details of the specific areas impacted by the flood waters. The city of Kerson which was highly impacted by the dam collapsed shows the following:

![Alt text](./Flood_tracking_maps/20230613_Kerson_zoom2.png?raw=true "Kakhovka dam flood extent (Ukraine)")



