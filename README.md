# differential-growth
Implementation of the differential growth algorithm in openFrameworks.

There are two shading modes:
- `bin/data/shaders/simple` where the differential growth drawing acts as a mask for a color gradient
- `bin/data/shaders/raymarching` which is an implementation of the raymarching algorithm with the differential growth drawing influencing the depth of the rendered shape and mouse position influencing the source of the diffuse lighting

<img width="1480" alt="Screenshot 2022-05-22 at 20 48 58" src="https://user-images.githubusercontent.com/49707233/169709939-26fc219d-e022-464b-b710-64a480da6907.png">
<img width="1480" alt="Screenshot 2022-05-22 at 20 55 36" src="https://user-images.githubusercontent.com/49707233/169709942-7d50a335-9bfe-41c2-b8c0-5fac6dcdd729.png">
<img width="1680" alt="Screenshot 2022-05-27 at 17 06 13" src="https://user-images.githubusercontent.com/49707233/170715843-6151313f-5748-4947-943a-a99e24b17325.png">
