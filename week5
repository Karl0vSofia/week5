<html>
  <head>
 <meta name="viewport" content="width=device-width, initial-scale=1" />
    <script src="aframe/aframe.min.js"></script> 
<script src="mindar/mindar-image-aframe.prod.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/c-frame/aframe-extras@7.0.0/dist/aframe-extras.min.js"></script>
  </head>
  <body>
	    <a-scene mindar-image="imageTargetSrc: C:\Users\Uchenik\Desktop\инновационніе Семериков\Без названия.png;" color-space="sRGB" renderer="colorManagement: true, physicallyCorrectLights" vr-mode-ui="enabled: false" device-orientation-permission-ui="enabled: false">
		<a-assets>
			<img id="forest" src="https://th.bing.com/th/id/OIP.DlOUr-H-J5e-ben3oo2swAHaEo?rs=1&pid=ImgDetMain" crossorigin="anonymous">
			<img id="pallete" src="https://raw.githubusercontent.com/aframevr/sample-assets/master/assets/images/uvgrid/UV_Grid_Sm.jpg" crossorigin=anonymous">
			<video id="wall" src="https://cdn.aframe.io/360-video-boilerplate/video/city.mp4" crossorigin="anonymous"></video>
			<a-asset-item id="ninja-obj"
			src="https://github.com/mrdoob/three.js/blob/dev/examples/models/obj/ninja/ninjaHead_Low.obj"></a-asset-item>
			<a-asset-item id="windmill-mtl"
			src="https://github.com/mrdoob/three.js/blob/dev/manual/examples/resources/models/windmill/windmill.mtl"></a-asset-item>
			<a-asset-item id="zebra" src="https://github.com/mrdoob/three.js/blob/dev/manual/examples/resources/models/animals/Zebra.gltf"></a-asset-item>
		</a-assets>
<a-camera position="0 0 0" look-controls="enabled: false"></a-camera>
      <a-entity mindar-image-target="targetIndex: 0">
				<a-entity scale="0.2 0.2 0.2">
		<!--<a-sky color="grey"></a-sky>-->
		<a-torus position="-3 2 -2" color="#00FFFF" radius="1.8" animation="property: components.material.material.color; type: color; from: green; to: red; loop: true; dur: 10000"></a-torus>
		<a-plane src="#forest" width="4.5" height="4.5" rotation="-55 0 0" position="-2 -1 -4" color="FAEBD7"></a-plane>
		<a-cylinder color="000FF" height="4" radius="0.09" position="-3 -2 -7"></a-cylinder>
		<a-cylinder color="000FF" height="3" radius="0.08" position="-3 -4 -7"></a-cylinder>
		<a-torus-knot color="A52A2A" radius="1.4" position="-4 1 -3" animation="property: rotation; to: 0 0 360; loop: true; 	dur: 10000"></a-torus-knot>
		<a-plane src="#pallete" width="7" height="5" position="4 1 -7"></a-plane>
		<a-text value="Вітаємо у браузерній VR!" color="black" width="10" position="-0.5 1 -6" font="segoescb-msdf.json" 	negate="false"></a-text>
		<!--<a-videosphere src="#wall"></a-videosphere>-->
		<a-obj-model src="#ninja-obj" mtl="#windmill-mtl" position="2.5 -0.5 -5"></a-obj-model>
		<a-gltf-model src="#zebra" position="2 0.5 -5" animation-mixer></a-gltf-model>
		<a-light type="point" intensity="1.5" position="4 0 0"></a-light>
 </a-entity>
	</a-scene>
  </body>
</html>
