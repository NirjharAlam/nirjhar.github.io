## Inversion of GPR B-scans Using Deep Neural Networks
A generative model is used to learn a joint distribution of GPR B-scans and corresponding structural geometry for inversion. The dataset describes buried objects with reflective properties at different positions in a soil-like medium.

<div align="center">
    <img src="../DNN-inversion/img/VAE_architecture.PNG" alt= Results of AE inversion of GPR B-scans from buried cylinders. The material
interfaces are blurry for the cylinders. However, the location and size of the object are detected with
accuracy except for sample (d)." width="600">
    <p><strong>Figure 1:</strong> Results of AE inversion of GPR B-scans from buried cylinders. The material interfaces are blurry for the cylinders. However, the location and size of the object are detected with accuracy except for sample (d).</p>
</div>


<div align="center">
    <img src="../DNN-inversion/img/DNN_inversion_dataset.PNG" alt= (Top) Cylinders of various diameters buried
in concrete at different locations, (Bottom) Corresponding
GPR scans obtained by numerical simulation." width="600">
    <p><strong>Figure 1:</strong> (Top) Cylinders of various diameters buried in concrete at different locations, (Bottom) Corresponding GPR scans obtained by numerical simulation.</p>
</div>



<div align="center">
    <img src="../DNN-inversion/img/DNN_inversion_AE.PNG" alt= Top)An Autoencoder model is trained, using simulated B-scans as input and the permittivity map of the predicted structure as output. Mean squared error is used to compute the difference between the predicted structure and the actual structure as the loss function. " width="600">
    <p><strong>Figure 1:</strong> Top)An Autoencoder model is trained, using simulated B-scans as input and the permittivity map of the predicted structure as output. Mean squared error is used to compute the difference between the predicted structure and the actual structure as the loss function. </p>
</div>


<div align="center">
    <img src="../DNN-inversion/img/DNN_inversion_result.PNG" alt= Results of AE inversion of GPR B-scans from buried cylinders. The material
interfaces are blurry for the cylinders. However, the location and size of the object are detected with
accuracy except for sample (d)." width="600">
    <p><strong>Figure 1:</strong> Results of AE inversion of GPR B-scans from buried cylinders. The material interfaces are blurry for the cylinders. However, the location and size of the object are detected with accuracy except for sample (d).</p>
</div>








<div align="center">
    <img src="./assets/img/workflow_diagram.png" alt=Both material type and subwavelength sample thickness values were correctly predicted by the proposed model." width="800">
    <p><strong>Figure 2:</strong> Both material type and subwavelength sample thickness values were correctly predicted by the proposed model.</p>
</div>


<div align="center">
    <img src="./assets/img/workflow_diagram.png" alt=Both material type and subwavelength sample thickness values were correctly predicted by the proposed model." width="800">
    <p><strong>Figure 2:</strong> Both material type and subwavelength sample thickness values were correctly predicted by the proposed model.</p>
</div>


<div align="center">
    <img src="./assets/img/workflow_diagram.png" alt=Both material type and subwavelength sample thickness values were correctly predicted by the proposed model." width="800">
    <p><strong>Figure 2:</strong> Both material type and subwavelength sample thickness values were correctly predicted by the proposed model.</p>
</div>
