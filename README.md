# Nexus.js | Multiresolution 3D visualization in Three.js

The 3D models are converted offline into multi-resolution structures of NXS format using the Nexus library's conversion and compression [algorithms](https://github.com/cnr-isti-vclab/nexus). The threejs_nexus.html file implements run-time rendering into a Three.js wrapper and dynamic display of a list of 3D models. 

![Optional Text](../master/src/Nexus_threejsmodels.jpg)

## Usage

Use your own .nxs models and set their paths as values in the Dropdown menu. 

```javascript
 <select id="modelDropdown">
            <option value="../../src/anton_memorial_clean_mesh_L2.nxs">Apollo and Daphne</option>
            <option value="../../src/Mesh_H.nxs">Human</option>
            <option value="../../src/Nair_templeRing.nxs">Temple</option>
        </select>
```
If the models are not visible, try to zoom-in/zoom-out to enable the orbit controls. You may need to modify camera position, lighting settings or scale to adjust the scene based on your 3D models. 

You can directly employ the project in VS (project solution included).

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
