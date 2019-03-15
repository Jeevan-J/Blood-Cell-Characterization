
# Blood Cell Characterization

## [#f03c15](Problem Statement)'#f03c15'
- Most of the blood test results for diseases are based on the cell structure and cell count. Pathologists analyse blood samples under microscope and gives results which is time taking process and also error prone in some cases
- Since the development of digital microscopes and machine learning techniques, many attempts were made to automate the process
- The existing models in the market are costly. There are few startups working to develop a low cost slide scanner with a trade off between cost and quality of blood smear images
- **Aim is to develop an end-to-end model, with image processing techniques and machine learning algorithms, which can process microscopic images to count blood cells, classify white blood cells and predict probable diseases**

<div align="center">
  <figure>
    <img src="resources/Im022_1.jpg" alt="Blood Smear Image" width="150px" height="150px"><br>
    <figcaption>Fig.1 - A typical blood smear slide image under microscope</figcaption>
  </figure> 
</div>

## Work Done
- Applied an image processing technique with few pre-processing steps to count Red Blood Cells (RBCs) in the blood smear image.
- Identified and segmented out White blood cells (WBCs) from blood smear image.
- Applied a machine learning algorithm to do semantic segmentation of White blood cells from segmented images.
- Developed a machine learning algorithm to classify segmented WBCs into four sub-categories.
- Worked on **"Classification of Normal vs Malignant Cells in B-ALL White Blood Cancer Microscopic Images"** : ISBI 2019 challenge hosted by SBI Lab, IIIT Delhi.
- Developed an ensemble based machine learning model to classify leukemic B-lymphoblast cells from normal B-lymphoid precursors from blood smear microscopic images

<div align="center">
  <figure>
    <img src="resources/Proposed_end_to_end_model.PNG" alt="Proposed_end_to_end_model"><br>
    <figcaption>Fig.2 - Proposed end to end model</figcaption>
  </figure> 
</div>

## Results
- Presently, our image processing technique is able to count RBC up to 97% accuracy excluding overlapped cells.
- Developed ensemble based machine learning algorithm is able to produce an **accuracy of 94% in classification of WBCs into sub-categories.**
- The same model when trained for two class classification of **leukemic B-lymphoblast cells from normal B-lymphoid precursors** produced an **accuracy of 82%.**

<div align="center">
  <figure>
    <img src="resources/results.PNG" alt="Proposed_end_to_end_model"><br>
    <figcaption>Fig.3 - Performances of of different architectures/approaches on Classification of leukemic B-lymphoblast cells from normal B-lymphoid precursors</figcaption>
  </figure> 
</div>
