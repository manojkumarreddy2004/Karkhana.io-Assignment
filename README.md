# Karkhana.io-Assignment

How I structured the code:
I created a MobiusStrip class to keep everything modular and clean. It takes radius (R), width (w), and resolution (n) as input and computes a 3D mesh using the parametric equations of a Möbius strip. The class includes methods to compute surface area, edge length, and plot the strip using matplotlib.

How I approximated surface area:
To estimate the surface area, I used numerical integration by approximating small surface patches. I calculated partial derivatives with respect to u and v to get tangent vectors, took their cross product to find the area of each patch, and then summed everything up.

Any challenges I faced:
Handling the surface’s twist without a built-in geometry library was tricky. Another challenge was calculating the surface normals accurately from gradients for the area approximation. Getting the visualization to look clean also took some fine-tuning with resolution and rendering options.

OUTPUT SCREENSHOT: 

![output](https://github.com/user-attachments/assets/4cde3aee-05e1-4173-b77a-51699b2e65c5)
