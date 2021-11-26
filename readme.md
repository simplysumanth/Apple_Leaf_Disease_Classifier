# Apple Leaf Disease Detection
![image](https://user-images.githubusercontent.com/26655188/143616922-d514e3b9-9123-416e-8ddb-6667326696b5.png)
## &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/simplysumanth/apple_leaf_disease_classifier/main/app.py) 
Dataset: <a href = "https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data"> Plant Pathology dataset </a> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
Built using : &nbsp; ![image](https://user-images.githubusercontent.com/26655188/143618035-3efecc7a-92e5-4548-a566-94de785454c3.png) &nbsp; &nbsp; ![image](https://user-images.githubusercontent.com/26655188/143617981-be944849-80e3-4440-93c7-1df0e5dc2cae.png)

## Project Aim:
Given a photo of an apple leaf, accurately assess its health. The aim is to distinguish between leaves which are healthy, those which are infected with apple rust, those that have apple scab, and those with more than one disease(combinations).

## Data Description
* train.csv
  * image_id: The image path/Name
  * combinations: one of the target labels
  * healthy: one of the target labels
  * rust: one of the target labels
  * scab: one of the target labels
* Images : A folder containing the train and test images, in jpg format.

## Motivation
Misdiagnosis of the many diseases impacting agricultural crops can lead to misuse of chemicals leading to the emergence of resistant pathogen strains, increased input costs, and more outbreaks with significant economic loss and environmental impacts. Current disease diagnosis based on human scouting is time-consuming and expensive, and although computer-vision based models have the promise to increase efficiency, the great variance in symptoms due to age of infected tissues, genetic variations, and light conditions within trees decreases the accuracy of detection.

## Project Structure
<table border="0">
 <tr>
    <th scope="col">
      <img src = "https://user-images.githubusercontent.com/26655188/143619050-5c0ba744-1bb5-4623-b9df-6fb28dc1942e.png"/>
    </th>
    <td>
      <ul>
        <li>Images : Has sample leaf images (the ones which are not used for training)</li>
        <li>Model :Has the xresnet50 model pickle file trained on images. </li>
        <li>Notebook : Has model_training and inference notebook </li>
      <li>app.py : it is the streamlit app </li>
        <li>requirements.txt : has the necessary packages needed to reproduce the app.</li>
      </ul>
   </td>
  </tr>
</table>
