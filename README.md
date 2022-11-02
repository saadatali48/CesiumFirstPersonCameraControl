# Cesium FirstPerson Camera Control ES6

Example Code

Initialize Cesium Viewer
```import CesiumFirstPersonCameraController from "./firstPersonCameraEs6"
 const viewer = new Viewer("cesiumContainer", {
  imageryProvider: new ArcGisMapServerImageryProvider({
    url:
      "https://services.arcgisonline.com/arcgis/rest/services/Canvas/World_Dark_Gray_Base/MapServer",
  }),
  vrButton:true)};
  
  const firstPersonCameraController = new CesiumFirstPersonCameraController({
  cesiumViewer : viewer
});


```
Enable first person camera control
```
  firstPersonCameraController.start()
```
Disable first person camera control
```
  firstPersonCameraController.stop()
```




