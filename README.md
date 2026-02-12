***** Medical Plant Image Classification Using Teachable Machine  <br>

This project focuses on developing an image-based medical plant identification system using Google Teachable Machine.
The system is trained to recognize different medicinal plants commonly found in the Philippines by analyzing images of their leaves, flowers, and overall structure.
The goal of the project is to help users easily identify medicinal plants using a camera or uploaded images, which can support education, herbal research, and awareness of traditional medicine.

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/90e4b95c-82f5-4699-bd98-cf32b45c7a89" width="900"/>
</p>

<br><br>

## Collect “Under the Hood” Results

<p align="center">
  <img src="https://github.com/user-attachments/assets/6f5cdc6c-28dc-466c-9c38-2106ccc87e03" width="300"/>
</p>

<br><br>

## Test the Model (Preview Section)

<table align="center">
  <tr>
    <th>Plant Name</th>
    <th>Prediction Screenshot</th>
  </tr>

  <tr>
    <td>Coral Berry</td>
    <td><img src="https://github.com/user-attachments/assets/daa171b2-3bb2-4207-a29b-16296017b7e9" width="250"/></td>
  </tr>

  <tr>
    <td> Blumea balsamifera</td>
    <td><img src="https://github.com/user-attachments/assets/1e0211df-7c62-49a7-b3b4-49e08521520e" width="250"/></td>
  </tr>

  <tr>
    <td>Muskmelon</td>
    <td><img src="https://github.com/user-attachments/assets/25411e61-33d2-4ddb-b682-c4d9843666a9" width="250"/></td>
  </tr>

  <tr>
    <td>Sea Poison Tree</td>
    <td><img src="https://github.com/user-attachments/assets/8df0b6e7-1c6d-4bfb-b512-6357791d192c" width="250"/></td>
  </tr>

  <tr>
    <td>Wild leek</td>
    <td><img src="https://github.com/user-attachments/assets/3dd9c6af-3bba-434e-80bc-bfb10312c4e8" width="250"/></td>
  </tr>

  <tr>
    <td>Chile Plant</td>
    <td><img src="https://github.com/user-attachments/assets/c97c5b37-3a95-4726-8f5f-1c2c73104fa6" width="250"/></td>
  </tr>

  <tr>
    <td>Akapulko</td>
    <td><img src="https://github.com/user-attachments/assets/c6c7d2a4-aa0d-4905-8957-87285000fee2" width="250"/></td>
  </tr>

  <tr>
    <td>Jute Mallow</td>
    <td><img src="https://github.com/user-attachments/assets/7b873cfd-fe0d-4abf-8078-ffada1dba5ea" width="250"/></td>
  </tr>

  <tr>
    <td>Giant Taro</td>
    <td><img src="https://github.com/user-attachments/assets/908b952b-1c34-42b4-b1dc-9df02a833e0d" width="250"/></td>
  </tr>

  <tr>
    <td>Giant Crape Myrtle</td>
    <td><img src="https://github.com/user-attachments/assets/c3413b2d-bb8d-441d-9acd-7a8379a3ba0c" width="250"/></td>
  </tr>

</table>

Export the Model
<img width="1920" height="1080" alt="Screenshot 2026-02-12 200815" src="https://github.com/user-attachments/assets/74d50295-5258-41e2-b855-bb84cc16bdd2" />

## A. Project Overview

This project develops an image classification model using Teachable Machine to identify medicinal plant species commonly found in the Philippines.
The model analyzes plant images and predicts the correct species based on visual features such as leaf shape, texture, and structure.
The purpose of this model is to assist students, researchers, and the general public in identifying medicinal plants quickly using image recognition technology.

## B. Plant Species

<table>

<tr>
<td><img src="https://github.com/user-attachments/assets/113e77bc-f1f4-4a87-9e8d-d52a7e42bd38" width="200"/></td>
<td>
<b>Common Name:</b> Coral Berry <br>
<b>Scientific Name:</b> Ardisia crenata <br>
<b>Description:</b> A small evergreen shrub known for its bright red berries and ornamental value.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/c9000a7e-04c6-4d82-a7cc-8b9fa01be577" width="200"/></td>
<td>
<b>Common Name:</b> Mugwort <br>
<b>Scientific Name:</b> Artemisia vulgaris <br>
<b>Description:</b> A medicinal herb traditionally used for digestive and menstrual disorders.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/27d4a21b-94e6-4cd5-bb3a-7efe88cf307b" width="200"/></td>
<td>
<b>Common Name:</b> Blumea Balsamifera <br>
<b>Scientific Name:</b> Blumea balsamifera <br>
<b>Description:</b> A medicinal plant used in herbal treatments for fever and kidney disorders.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/6df1999b-08db-438d-a268-e90f5d7c7470" width="200"/></td>
<td>
<b>Common Name:</b> Akapulko <br>
<b>Scientific Name:</b> Senna alata <br>
<b>Description:</b> A medicinal plant commonly used to treat fungal skin infections.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/e359de72-c012-4a19-a4de-edc6c1fa52f6" width="200"/></td>
<td>
<b>Common Name:</b> Wild Leek <br>
<b>Scientific Name:</b> Allium ampeloprasum <br>
<b>Description:</b> A plant related to onions and garlic, used for culinary and medicinal purposes.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/b34252fa-94a1-40c9-9eb4-526a92559673" width="200"/></td>
<td>
<b>Common Name:</b> Sea Poison Tree <br>
<b>Scientific Name:</b> Barringtonia asiatica <br>
<b>Description:</b> A coastal tree traditionally used in fish poisoning and herbal medicine.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/d7270312-0fda-40d9-852a-6debb0520167" width="200"/></td>
<td>
<b>Common Name:</b> Muskmelon <br>
<b>Scientific Name:</b> Cucumis melo <br>
<b>Description:</b> A fruit-bearing vine plant known for its sweet edible melon.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/fff3e13c-31c7-404e-8b8b-3932f840a748" width="200"/></td>
<td>
<b>Common Name:</b> Chili Plant <br>
<b>Scientific Name:</b> Capsicum annuum <br>
<b>Description:</b> A plant producing spicy fruits widely used in cooking and medicine.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/888ce78e-6a1d-4df9-b6b1-57c9c3acc482" width="200"/></td>
<td>
<b>Common Name:</b> Jute Mallow <br>
<b>Scientific Name:</b> Corchorus olitorius <br>
<b>Description:</b> A leafy vegetable used in traditional dishes and herbal medicine.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/34eaeabc-4d0a-4f46-bc94-7d7e0558cb4e" width="200"/></td>
<td>
<b>Common Name:</b> Giant Crape Myrtle <br>
<b>Scientific Name:</b> Lagerstroemia speciosa <br>
<b>Description:</b> A flowering tree known for its vibrant purple flowers and medicinal uses.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/bc16ec6a-f012-45b5-be18-f91bb3285130" width="200"/></td>
<td>
<b>Common Name:</b> Giant Taro <br>
<b>Scientific Name:</b> Alocasia macrorrhizos <br>
<b>Description:</b> A large tropical plant known for its broad leaves and edible roots.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/c87d025a-9f4c-43b3-ae1b-0977583caa55" width="200"/></td>
<td>
<b>Common Name:</b> Globe Amaranth <br>
<b>Scientific Name:</b> Gomphrena globosa <br>
<b>Description:</b> A flowering plant used in herbal teas and ornamental gardening.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/2002d9b8-b302-40e6-8113-e540f76aa332" width="200"/></td>
<td>
<b>Common Name:</b> Hyptis <br>
<b>Scientific Name:</b> Hyptis capitata <br>
<b>Description:</b> A medicinal herb used traditionally for treating wounds and infections.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/dccc6379-f489-4102-bb96-286b68a3e175" width="200"/></td>
<td>
<b>Common Name:</b> Lantana Camara <br>
<b>Scientific Name:</b> Lantana camara <br>
<b>Description:</b> A flowering shrub known for colorful blooms and medicinal properties.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/b84b75af-4a85-4c54-a595-0d803285f603" width="200"/></td>
<td>
<b>Common Name:</b> Mentha Spicata <br>
<b>Scientific Name:</b> Mentha spicata <br>
<b>Description:</b> Also known as spearmint, used for digestive and respiratory treatments.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/31568225-7c2e-46dd-96b8-ccf84e7bef34" width="200"/></td>
<td>
<b>Common Name:</b> Peperomia Pellucida <br>
<b>Scientific Name:</b> Peperomia pellucida <br>
<b>Description:</b> A small herb used traditionally for arthritis and gout treatment.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/f6bd50d1-9037-43b4-8d0b-55b625b7a1c9" width="200"/></td>
<td>
<b>Common Name:</b> Phyllanthus Niruri <br>
<b>Scientific Name:</b> Phyllanthus niruri Linn. <br>
<b>Description:</b> Commonly known as "stonebreaker," used for kidney and liver health.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/708b57fb-93ca-4de4-ac2d-460780eb3631" width="200"/></td>
<td>
<b>Common Name:</b> Plumeria Obtusa <br>
<b>Scientific Name:</b> Plumeria obtusa <br>
<b>Description:</b> A tropical flowering tree known for its fragrant white flowers.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/3db3d15e-d54b-4bfa-909a-2830943f1393" width="200"/></td>
<td>
<b>Common Name:</b> Sesbania Grandiflora <br>
<b>Scientific Name:</b> Sesbania grandiflora <br>
<b>Description:</b> A fast-growing tree with edible flowers and medicinal properties.
</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/5f65a389-975d-4ac7-9e8c-3507b3813dc6" width="200"/></td>
<td>
<b>Common Name:</b> Wrightia Antidysenterica <br>
<b>Scientific Name:</b> Wrightia antidysenterica <br>
<b>Description:</b> A medicinal plant used traditionally for treating diarrhea and skin diseases.
</td>
</tr>

</table>




Reflection Questions:
Answer the following questions based on your experience:
1. How did the number of images per class affect your model’s accuracy?<br>
More images made the model more accurate. Less images caused more mistakes.

2. Which plant species were most commonly misclassified and why?<br>
Mentha spicata and Peperimia pellucida were often confused because their leaves look similar.

3. How did changing the epochs, batch size, or learning rate affect the training results?<br>
More epochs helped at first but too many caused overfitting.
Small batch size trained slowly but carefully; large batch trained faster.
High learning rate was unstable; low learning rate was slower but steady.

5. What challenges did you encounter during dataset collection and labeling?<br>
It was hard to get enough images, lighting was not always good, and some plants looked very similar.

6. If you were to improve your model, what specific changes would you make and why?<br>
Collect more images, use tricks like flipping/rotating images, take clearer pictures, and adjust training settings for better results.
