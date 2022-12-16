# Viewer

In this folder we've incldued sample images that can be used for testing
[Chaise's Image viewer](https://github.com/informatics-isi-edu/chaise/blob/master/docs/viewer/viewer-app.md).

The following are the included images:

## 14-47YP

A multi channel DZI image. Assuming this folder is depolyed directly under `/var/www/html/` folder, the following is an example of using this in atlas depolyment:

```
https://www.atlas-d2k.org/chaise/record/#2/Gene_Expression:Image/RID=14-47YP?url=/atlas-d2k_14-47YP/AF480/ImageProperties.xml&url=/atlas-d2k_14-47YP/AF555/ImageProperties.xml&url=/atlas-d2k_14-47YP/AF647/ImageProperties.xml&url=/atlas-d2k_14-47YP/DAPI/ImageProperties.xml
```
(if the image is deployed under a different subfolder, you need to adjust the passed `url`s to include it)

## 16-2GVR

A multi channel jpg image. The following the channel names corresponding to each image:

- **RBKUSC20170405EXP47-1**: DAPI
- **RBKUSC20170405EXP47-2**: WT1

Given that jpg files don't have the information about the channel, other than including the url to the image, you also need to provide the channel names. Assuming this folder is depolyed directly under `/var/www/html/` folder, the following is an example of using this in atlas depolyment:

```
https://www.atlas-d2k.org/chaise/record/#2/Gene_Expression:Image/RID=16-2GVR?url=/atlas-d2k_16-2GVR/RBKUSC20170405EXP47-1.jpg&channelName=DAPI&url=/atlas-d2k_16-2GVR/RBKUSC20170405EXP47-2.jpg&channelName=WT1
```
(if the image is deployed under a different subfolder, you need to adjust the passed `url` to include it)

## 16-2GN8

A multi channel jpg image. The following the channel names corresponding to each image:

- **RBKUSC20170405EXP27-1**: DAPI
- **RBKUSC20170405EXP27-2**: GATA3

Given that jpg files don't have the information about the channel, other than including the url to the image, you also need to provide the channel names. Assuming this folder is depolyed directly under `/var/www/html/` folder, the following is an example of using this in atlas depolyment:

```
https://www.atlas-d2k.org/chaise/record/#2/Gene_Expression:Image/RID=16-2GN8?url=/atlas-d2k_16-2GN8/RBKUSC20170405EXP27-1.jpg&channelName=DAPI&url=/atlas-d2k_16-2GN8/RBKUSC20170405EXP27-2.jpg&channelName=GATA3
```
(if the image is deployed under a different subfolder, you need to adjust the passed `url` to include it)