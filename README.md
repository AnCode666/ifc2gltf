# IFC TO glTF WEB CONVERTER

Web app to convert 3D models of building projects stored in IFC files to GLB format (binary version of glTF format)

Built with the libraries developed by:

**That Open Company and the community** [https://github.com/ThatOpen]

Also uses following libraries:

**three.js** [https://github.com/mrdoob/three.js]

**GLTFExporter** [https://threejs.org/docs/#examples/en/exporters/GLTFExporter]

The code used to build the 3D viever, the UI, and to read the IFC files is a copy of the ifcLoader example from That Open Documents [https://docs.thatopen.com/Tutorials/Components/Core/IfcLoader]. Go to the file src/example.ts and look for the comments in the code that start with "AnCode:" to locate the code needed to convert and download the GLB file.

The converter uses Vite as build tool.

The converter let you use your web browser to load local IFC files and save a GLB file containing a 3D model of the building project stored in the IFC file.


To run it locally:

1º. Clone this repo.

2ª. To install the dependencies, run: npm i

3ª. To start vite building, and a development server, run: npm run dev


To use it:

1º. Navigate to the port of the local server deployed.

2º. Open the control panel on the right.

3º. Hit Load IFC buttom.

4º. After the model is loaded, press the Export GLB file buttom.


GLB file should start downloading...

Enjoy it!!!