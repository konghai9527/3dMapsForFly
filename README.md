# 3dMapsForFly
Using Vue frontend tools to build a webpage, with Cesium maps as the 3D display scene, animations for takeoff and landing created by adding airplane models, supporting the rendering of radiation intensity at different heights for a specific radiation source, and supporting display through QWeb in a QWidget using Qt. It also supports loading offline maps.
通过vue前端工具，Node.js (运行环境)、呈现网页形式，cesium地图引擎作为三维显示场景，并通过添加飞机模型制作起飞和落地的动画，支持显示某个辐射源的不同高度辐射强度渲染，支持通过qt使用QWeb进行在QWidget显示出来。支持加载离线地图。
网页运行方式：./my-3d-map路径下npm run dev,既可进行服务器显示
qt加载界面：./my-3d-map路径下npm run build ,将加载的dist路径拷贝至qt目录，qt的url指定到dist下的index.xml
