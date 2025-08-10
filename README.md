# Geospatial-data-solution-here-hackathon-2025
Exploring advanced techniques for data visualization, cleaning, and feature extraction from LiDAR point clouds.
# Libraries used

```python
laspy
open3d
matplotlib
pandas
numpy
```

# 1- Returning the XYZ to the original coordinates then plotted to see where it is “Germany”

![3dab23f8-7166-469b-8e99-942e95c90be2.jpg](attachment:c8366715-a99e-4db1-9cc5-e7d711535dd7:3dab23f8-7166-469b-8e99-942e95c90be2.jpg)

# 2- Loading data and visualize it

## hist of coordinate values

![image.png](attachment:68044373-aee2-4562-8a37-197d30fa6774:image.png)

## A visualization of a subset of the data

![image.png](attachment:35c3296d-6a30-4433-b4a0-a985c8168555:image.png)

![image.png](attachment:1f6e9998-d354-4e89-a0eb-8a7a561e22ee:image.png)

# 3- Cleaning data and extracting important features

## A visualization with intensity

![image.png](attachment:a28ad518-7602-4694-a911-7f652c88247c:image.png)

# 4- Cleaning data by removing the statistical outliers

## Before

![image.png](attachment:b4625ae3-40aa-43c7-93dc-ac2498f7bce8:image.png)

## After

![image.png](attachment:202b5bbf-1a73-452b-8afc-9deb0323eb17:image.png)

# 5- Extract road and non-road by segmenting plane

## Actual image

![0f96f2ca-a53c-4ace-a60a-b5ebb818aefb.jpg](attachment:920d4caa-8cae-4579-8a64-244ffb33ffc0:0f96f2ca-a53c-4ace-a60a-b5ebb818aefb.jpg)

## Mapped image

![9cdd7b8c-a036-402d-b0da-8c44ed4ad368.jpg](attachment:71304e4b-c9c9-4d88-8e82-b6a4932d9df2:9cdd7b8c-a036-402d-b0da-8c44ed4ad368.jpg)

## Ground Image

![4d5fe27f-68ff-4ce7-a245-762488d17845.jpg](attachment:f9bd0f8a-7d9e-4e44-9336-6a66215363e5:4d5fe27f-68ff-4ce7-a245-762488d17845.jpg)

## Non-Ground

![17f96778-7d96-4f31-a9e0-4bda2712b456.jpg](attachment:631975ad-abe5-430a-80cc-13f97960b2f9:17f96778-7d96-4f31-a9e0-4bda2712b456.jpg)

# 6- Extracting surface signs by masking with intensity

## Before

![image.png](attachment:c713392d-ca0a-43da-bbea-bc0ebe91df1c:image.png)

## After

![image (1).png](attachment:14a01ff4-efea-4605-922d-023507c43fc3:image_(1).png)
