# Vehicle Logos Dataset

![Vehicle_Logo](https://user-images.githubusercontent.com/66736646/88664543-06f24500-d0ff-11ea-89f3-6e7cb8966ae9.png)

## Overview

A computer vision dataset of vehicle logo segmentation masks. There are 34 logos each with 16 images and masks.

Go [here](#download-the-dataset) if you don't have time.

---

## Table of Contents

- [About the Dataset](#about-the-dataset)
    - [Sample Dataset](#sample-dataset)
    - [Original Dataset](#original-dataset)
- [Download the Dataset](#download-the-dataset)
- [Evaluation](#evaluation)
- [Links and References](#links-and-references)
- [Who are we](#who-are-we)
- [Contact us](#contact-us)
- [License](#license)

---

## About the Dataset

Annotated, machine learning dataset of Vehicle Logos. There are 34 Vehicle Logos classes and 544 images each containing a single cropped vehicle logo and corresponding instance mask. There are 34 logos each with 16 images and masks.

Cropped Logo images have been extracted from larger images containing cars. The car images are created using our mobile application and photographers. The images, crops and masks have been manually created.

Maximum occlusion or truncation for any class annotation is ~10%.

  - All images were collected through our mobile application that is available both on Android and iOS and as such are property of General Blockchain, Inc.
  
  - All annotations were created by our own fully employed in-house team.
  
  - Each cropped image was checked at least twice during the quality assurance process by different people.
  
  - Dataset is available in CSV format.

> Watch the [short video](https://drive.google.com/file/d/13o10ADNnK9MZf94GlUciy8C1ZWtnZw9_/view?usp=sharing) overview to become familiar with the dataset.

---

### Sample Dataset

The sample dataset comes with 34 vehicle classes. Each of the classes have 16 images and masks. So, a total of 544 images and masks are present in the sample dataset.

| No        | Category           | Images  |
| ------------- |:-------------:| -----:|
| 1          |    Toyota        | 16 |
| 2       |    Mitsubishi        | 16 |
| 3   |    Seat        | 16 |
| 4   |    Suzuki        | 16 |
|5 |    Opel        | 16 |
|6     |    Honda 1        | 16 |
|7    |    Renault        | 16 |
|8       |    Mercedes 1        |  16 |
|9        |    Volkswagen         |  16 |
|10        |    Subaru         |  16 |
|11        |    Dacia 1         |  16 |
|12        |    Citroen         |  16 |
|13        |    Land Rover         |  16 |
|14        |    Tesla         |  16 |
|15        |    Mazda         |  16 |
|16        |    Nissan         |  16 |
|17        |    Hyundai         |  16 |
|18        |    Lancia 1         |  16 |
|19        |    Skoda 1         |  16 |
|20        |    Chevrolet 2         |  16 |
|21        |    Porsche         |  16 |
|22        |    Peugeot         |  16 |
|23        |    Jeep         |  16 |
|24        |    Mini         |  16 |
|25        |    Kia 1         |  16 |
|26        |    Lexus         |  16 |
|27        |    Smart 2         |  16 |
|28        |    Volvo 1         |  16 |
|29        |    GMC         |  16 |
|30        |    Ford         |  16 |
|31        |    Daewoo 1         |  16 |
|32        |    Acura         |  16 |
|33        |    Alfa Romeo         |  16 |
|34        |    BMW         |  16 |
|Total          |    34      |544 | 

<!--
| Category        | Toyota           | Mitsubishi           |
| ------------- |:-------------:| -----:|
| Images          |    16        | 16 |
'Toyota' 'Mitsubishi' 'Seat' 'Suzuki' 'Opel' 'Honda 1' 'Renault' 'Mercedes 1' 'Volkswagen' 'Subaru' 'Dacia 1' 'Citroen' 'Land Rover' 'Tesla' 'Mazda' 'Nissan' 'Hyundai' 'Lancia 1' 'Skoda 1' 'Chevrolet 2' 'Porsche' 'Peugeot' 'Jeep' 'Mini' 'Kia 1' 'Lexus' 'Smart 2' 'Volvo 1' 'GMC' 'Ford' 'Daewoo 1' 'Acura' 'Alfa Romeo' 'BMW'
-->

### Original Dataset

Our original dataset comes with 34 vehicle classes and a total of 4934 images. [Here](https://drive.google.com/file/d/13o10ADNnK9MZf94GlUciy8C1ZWtnZw9_/view?usp=sharing) is a demonstration of the dataset.

![originalimg](https://user-images.githubusercontent.com/66736646/88541226-38530e00-d036-11ea-9c26-9d49ed0f7b11.png)

<!--
• A computer vision dataset of vehicle logo segmentation masks. There are 32
logos each with 16 images and masks.
• This dataset release package has been created by the dataset production
team to support the marketing and sales efforts of this dataset. The package
consists of sample data and supporting promotional materials.
• The sample dataset contains 34 classes, and each class has 16 images and
16 masks.
• The images of logos in this dataset were cropped from larger images of cars
which were collected my our mobile app users. The images of cars are not
provided, apart from a small sample, and they can be sold to datasets users
who wish to do object detection of logos.
• Platform screenshots are provided showing datasets exploration and analyzing
a model which was created using the datasets to show what expected
performance of this dataset might be.
• A gif and video animation of a logo mask is provided which is beautiful.
• Marketing keywords are provided for SEO and Google Ads
• Listing documents are provided which contain the fields required to list the
dataset for sale on other platforms.
• Folder Contents
• Readme.txt
• Video Overview - Vehicle Logo Dataset.mp4
• Sample Dataset
• Images - Images containing vehicle logos (cropped from source images
of cars)
• Masks - Instance segmentation masks of vehicle logos
• Source Image Samples - A sample of images showing the original
source images of cars.
• structure.csv - Filenames and links between logo images and masks
• Platform Screenshots
• Dataset Exploration - 4 screenshots showing dataset exploration using
our platform.
• Model Performance - 6 screenshots showing an analysis of a model
trained with the dataset
• Marketing Material
• Promo Images - 5 images collected from the internet showing nice
vehicle logos on cars
• Annotation Animation - 1 gif and 1 video showing showing a mask
• Keywords.csv - List of marketing keywords related to the dataset
• Listings
-->

---

## Download the Dataset

### Download the dataset as zip format

![Download_zip](https://user-images.githubusercontent.com/66736646/88542138-c5e32d80-d037-11ea-9df5-8d987bbc5cad.png)

### Download using git clone

Open terminal and run the following command:

```
git clone https://github.com/GeneralBlockchain/vehicle-logos-dataset.git
```

## Evaluation

### Model Evaluation Result

![evaluation](https://user-images.githubusercontent.com/66736646/88541530-b3b4bf80-d036-11ea-8061-eb911387a1fa.png)

### Confusion Matrix

![Confusion_Matrix](https://user-images.githubusercontent.com/66736646/88541547-ba433700-d036-11ea-920f-a1374a2e825f.png)

## Links and References

- Dataset homepage: https://github.com/GeneralBlockchain/vehicle-logos-dataset

- Repository: https://github.com/GeneralBlockchain/vehicle-logos-dataset.git

- Issue tracker: https://github.com/GeneralBlockchain/vehicle-logos-dataset/issues

- In case of any help you may need from us, please [contact us](#contact-us) directly without any hesitation! We will be glad to help you.

---

## Who are we

We are **[General Blockchain Inc](https://www.generalblockchain.com/)**, a company developing technology to support the AI industry using blockchain technology.

Our vision is to build a programmable, human based, artificial intelligence.

The first application of this human computer is to provide image annotation services to the machine learning and artificial intelligence community.

Please access our Image Annotation AI services [here](https://www.imageannotation.ai/), today.

---

## Contact Us

* Email: contact@generalblockchain.com

---

## License

The repository is licensed under [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### rand

<img src="https://user-images.githubusercontent.com/33668152/88815903-a980f580-d1dd-11ea-8376-56ed8baa61a6.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88815917-adad1300-d1dd-11ea-9c69-cbfe50ef7e2c.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88815920-aede4000-d1dd-11ea-94f9-6a2f881a0718.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88815932-b00f6d00-d1dd-11ea-9eee-d0306c4b5830.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88815915-ad147c80-d1dd-11ea-9ebd-33d08a7f0370.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88815918-ae45a980-d1dd-11ea-8190-c05ed8bfbb46.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88815927-b00f6d00-d1dd-11ea-91b1-939db3879dd2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88815936-b1409a00-d1dd-11ea-9366-d7d7bbd13f6f.png" width="200"/>

---

### three

<img src="https://user-images.githubusercontent.com/33668152/88814663-3dea5880-d1dc-11ea-80b7-f2831e805062.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88814672-417ddf80-d1dc-11ea-8371-773f30a986a2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88814685-4478d000-d1dc-11ea-93f4-7204c82987d1.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88814704-480c5700-d1dc-11ea-8785-44ff2d6eda86.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88814669-40e54900-d1dc-11ea-94b4-0adaf39837cd.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88814684-43e03980-d1dc-11ea-82ad-5f56ee7798b7.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88814699-4773c080-d1dc-11ea-997b-43230d1042a1.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88814713-4b074780-d1dc-11ea-872c-9d59a40819c5.png" width="200"/>

---

### Fig

<img src="https://user-images.githubusercontent.com/33668152/88811288-3032d400-d1d8-11ea-8c56-19efc5986424.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88811297-32952e00-d1d8-11ea-8c4d-96ef40ec6e7f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88811311-35901e80-d1d8-11ea-81c8-c115516aafe4.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88811317-3759e200-d1d8-11ea-9f73-682281f9e572.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88811293-31640100-d1d8-11ea-8f60-a2cb267a05a0.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88811305-33c65b00-d1d8-11ea-8939-17af40a3c2ec.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88811316-36c14b80-d1d8-11ea-8a02-7ec28ec2341f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88811323-37f27880-d1d8-11ea-8120-e1f40b764c0d.png" width="200"/>

---

### Volks

<img src="https://user-images.githubusercontent.com/33668152/88809972-8ef74e00-d1d6-11ea-951d-f1f345bdfb9f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88809983-91f23e80-d1d6-11ea-9362-997b58dc1848.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88809987-93bc0200-d1d6-11ea-9ead-3121e2fba4b1.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88809995-9585c580-d1d6-11ea-95e0-3fb686a0ae49.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88809982-9159a800-d1d6-11ea-9f16-9cd73eac947c.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88809985-93236b80-d1d6-11ea-81f1-2955873a32ae.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88809991-94549880-d1d6-11ea-9e3d-1b1b0abf70b7.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88809999-961e5c00-d1d6-11ea-92cd-ee063616a642.png" width="200"/>

---

### baka

<img src="https://user-images.githubusercontent.com/33668152/88806088-c31c4000-d1d1-11ea-8189-f964ed07e621.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88806096-c57e9a00-d1d1-11ea-83d4-0622f30c1ef4.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88806105-c6afc700-d1d1-11ea-897e-c123beaf4b8a.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88806109-c8798a80-d1d1-11ea-9ba5-27055afb2092.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88806092-c4e60380-d1d1-11ea-8d46-5b20d9ba9f9e.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88806102-c6173080-d1d1-11ea-9304-5daea0cd3949.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88806108-c7e0f400-d1d1-11ea-837e-453124b5f92f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88806111-c9122100-d1d1-11ea-869b-c35c89126602.png" width="200"/>

---

### Porsche

<img src="https://user-images.githubusercontent.com/33668152/88805638-38d3dc00-d1d1-11ea-8069-c30ebfc055ae.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88805650-3b363600-d1d1-11ea-9b0b-8cc0c68f3615.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88805656-3cfff980-d1d1-11ea-9edd-8e5636ac2ebe.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88805663-3d989000-d1d1-11ea-8b35-dc01b1f41b67.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88805646-3a9d9f80-d1d1-11ea-9dd3-2c8f7a9fac7b.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88805654-3c676300-d1d1-11ea-9085-308ffead4723.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88805660-3d989000-d1d1-11ea-9baf-d473f0af6ee2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88805665-3e312680-d1d1-11ea-9455-0f1a0efaddb1.png" width="200"/>

---

### BMW

<img src="https://user-images.githubusercontent.com/33668152/88802465-ee506080-d1cc-11ea-9b15-7af66b1eac0b.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802471-f01a2400-d1cc-11ea-80d6-c00d07a8ba57.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802476-f1e3e780-d1cc-11ea-8ab5-2825f9c3a309.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802485-f3151480-d1cc-11ea-9ce6-6f27b61b4985.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88802469-f01a2400-d1cc-11ea-99ad-7249f7ee45d2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802473-f14b5100-d1cc-11ea-8e36-71dc30395b37.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802482-f27c7e00-d1cc-11ea-9b8f-4f92e256cd7f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802489-f3adab00-d1cc-11ea-9174-432c28acf87e.png" width="200"/>

---

### double

<img src="https://user-images.githubusercontent.com/33668152/88802062-5fdbdf00-d1cc-11ea-8795-89af672a1217.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802068-61a5a280-d1cc-11ea-814c-823b8d088554.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802076-62d6cf80-d1cc-11ea-9920-d0483fa94dab.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802081-6407fc80-d1cc-11ea-9461-969a2e319ab5.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88802066-610d0c00-d1cc-11ea-8566-02c28c8dd147.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802074-623e3900-d1cc-11ea-97b3-9f1d2b5f81a8.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802080-6407fc80-d1cc-11ea-8f1d-256ea60223a1.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88802083-65392980-d1cc-11ea-925e-23da55d1e9be.png" width="200"/>

---

### less

<img src="https://user-images.githubusercontent.com/33668152/88801546-b268cb80-d1cb-11ea-8d0c-500363dbe9fd.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88801558-b4cb2580-d1cb-11ea-81dd-8ad7dfb22e4d.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88801565-b694e900-d1cb-11ea-81c6-bae33026d8f5.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88801581-b8f74300-d1cb-11ea-8c12-3e5b121f6584.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88801553-b4328f00-d1cb-11ea-866d-80800c914045.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88801562-b694e900-d1cb-11ea-8de9-0a2beaac242c.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88801573-b85eac80-d1cb-11ea-95ab-0da7e710c26a.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88801584-b98fd980-d1cb-11ea-9d38-4e546c22f6de.png" width="200"/>

---

### Lancia

<img src="https://user-images.githubusercontent.com/33668152/88800616-46399800-d1ca-11ea-8835-83b1ce212d74.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800624-48035b80-d1ca-11ea-82c0-9b077e5d69c5.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800629-49348880-d1ca-11ea-9de2-79ef6686a21f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800635-4a65b580-d1ca-11ea-9e2d-c85ea2b734f0.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88800622-476ac500-d1ca-11ea-8fa1-6c64b2aa5b18.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800627-489bf200-d1ca-11ea-9673-5751675ee1cc.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800632-49cd1f00-d1ca-11ea-8c21-baac70b43e5f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800639-4afe4c00-d1ca-11ea-8da0-04ea813f88b5.png" width="200"/>

---

### 2nd Brace

<img src="https://user-images.githubusercontent.com/33668152/88800314-c7dcf600-d1c9-11ea-9c16-0fe6b19ed149.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800323-c9a6b980-d1c9-11ea-8460-fcf74100207c.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800326-cb707d00-d1c9-11ea-9b69-e38ad975bb89.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800334-cd3a4080-d1c9-11ea-9d0f-6fe2d38b70ae.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88800319-c9a6b980-d1c9-11ea-8128-9298c5f783b2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800325-cad7e680-d1c9-11ea-8ccc-ea5aeca935b2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800332-cd3a4080-d1c9-11ea-809e-930c732f7405.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88800337-cf040400-d1c9-11ea-9b84-f67dcf365c84.png" width="200"/>

---

### 2 side

<img src="https://user-images.githubusercontent.com/33668152/88799104-cc081400-d1c7-11ea-900b-eeebbe1c83e2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799110-cdd1d780-d1c7-11ea-9997-961eeeab4474.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799119-cf030480-d1c7-11ea-9ca7-402c14b537b7.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799123-d0ccc800-d1c7-11ea-9233-7dcc6681844e.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88799108-cd394100-d1c7-11ea-86ab-6ddacbb092b5.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799115-cf030480-d1c7-11ea-9edd-9985419b31fa.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799121-d0343180-d1c7-11ea-829c-0318e3a7f757.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799128-d1fdf500-d1c7-11ea-97ba-b600751c7edf.png" width="200"/>

---

### Volvo

<img src="https://user-images.githubusercontent.com/33668152/88798702-2654a500-d1c7-11ea-91f0-52a84a9d3a63.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798710-281e6880-d1c7-11ea-8c9e-bd9d047a0778.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798716-2a80c280-d1c7-11ea-875b-347a8bead720.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798731-2e144980-d1c7-11ea-91a0-37cb9ab1c2d8.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88798708-2785d200-d1c7-11ea-9996-f49e684b5635.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798715-29e82c00-d1c7-11ea-8a08-7d22194fd702.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798729-2d7bb300-d1c7-11ea-8cc3-31e616d61368.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798734-2f457680-d1c7-11ea-9c2d-dad5fec47b71.png" width="200"/>

---

### Chevrolet

<img src="https://user-images.githubusercontent.com/33668152/88792104-927ddb80-d1bc-11ea-9cbb-74401b9b6060.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792111-94479f00-d1bc-11ea-92f3-e3c3227cf1b2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792115-96116280-d1bc-11ea-80c9-5ec338752d0d.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792124-97db2600-d1bc-11ea-851f-03988ba7edb1.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88792106-93af0880-d1bc-11ea-857e-570902ff1288.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792113-9578cc00-d1bc-11ea-9143-753b7400141b.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792122-97428f80-d1bc-11ea-9f81-05bad1dfa118.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792129-9873bc80-d1bc-11ea-89bf-1d3ac0ae30ad.png" width="200"/>

---
### Donno

<img src="https://user-images.githubusercontent.com/33668152/88792797-a6760d00-d1bd-11ea-9bd1-ea505fec197c.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792804-a83fd080-d1bd-11ea-8450-20ad8d45e3b4.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792808-aa099400-d1bd-11ea-8ddb-4e0e5eee346d.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792811-abd35780-d1bd-11ea-9913-de32c7f71ab8.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88792802-a7a73a00-d1bd-11ea-8125-8c1cb4ace147.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792806-a8d86700-d1bd-11ea-8c4d-c1e18df97cd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792809-ab3ac100-d1bd-11ea-83ed-1f6badd508c6.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88792813-ac6bee00-d1bd-11ea-8bb4-622a1613283f.png" width="200"/>

---
### Dacia

<img src="https://user-images.githubusercontent.com/33668152/88793281-5ea3b580-d1be-11ea-8bb2-696c4e0b4e6a.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793288-61060f80-d1be-11ea-959e-ed2e31431351.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793294-62373c80-d1be-11ea-9093-a404a0757618.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793301-63686980-d1be-11ea-90a1-a7a57e046ffb.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88793286-606d7900-d1be-11ea-9d2f-dd8986246f3e.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793293-619ea600-d1be-11ea-9294-98ec78828903.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793298-63686980-d1be-11ea-9fe8-00895dcd2051.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793303-64999680-d1be-11ea-9401-4f9fca00d586.png" width="200"/>

---
### Mini

<img src="https://user-images.githubusercontent.com/33668152/88793643-f43f4500-d1be-11ea-9f1d-5ac960117273.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793650-f6090880-d1be-11ea-8a0b-d2e0de91216e.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793659-f73a3580-d1be-11ea-8b5e-53d318c8d889.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793663-f86b6280-d1be-11ea-9a5f-41d627bc1d7b.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88793649-f5707200-d1be-11ea-8498-ee390e5af7a9.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793655-f6a19f00-d1be-11ea-9310-ada3627509b4.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88795894-944a9d80-d1c2-11ea-83b2-b71f963212f4.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88793666-f99c8f80-d1be-11ea-9347-5a1a0b18bccf.png" width="200"/>

---
### Donno Star

<img src="https://user-images.githubusercontent.com/33668152/88794604-8b58cc80-d1c0-11ea-81bf-18759b70d1b7.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88794609-8dbb2680-d1c0-11ea-830b-d3ba77cefca4.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88794613-8eec5380-d1c0-11ea-8609-3960446fbbf6.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88794617-901d8080-d1c0-11ea-9618-559be5896f7a.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88794607-8d229000-d1c0-11ea-98d3-cf517612d62a.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88794611-8e53bd00-d1c0-11ea-80c6-d667b6af2115.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88794615-901d8080-d1c0-11ea-8656-9af5d3ddadf0.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88794620-914ead80-d1c0-11ea-90ff-e6f3a57b2008.png" width="200"/>

---
### Donno Rombos

<img src="https://user-images.githubusercontent.com/33668152/88796238-26eb3c80-d1c3-11ea-9b1d-7c188154e2b8.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88796246-29e62d00-d1c3-11ea-95b9-52e534447785.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88796254-2c488700-d1c3-11ea-9b05-3f791e063bdf.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88796260-2d79b400-d1c3-11ea-829d-0285cb6ef026.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88796243-294d9680-d1c3-11ea-851c-5d71318c9907.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88796253-2baff080-d1c3-11ea-8745-336e215cdf46.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88796257-2ce11d80-d1c3-11ea-84b3-008152eeeae3.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88796263-2e124a80-d1c3-11ea-89ec-7ff5864a189c.png" width="200"/>

---
### Donno Tir

<img src="https://user-images.githubusercontent.com/33668152/88797352-091ed700-d1c5-11ea-982f-d12d35c32718.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797355-0a500400-d1c5-11ea-9a5d-c6b1e7006c71.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797359-0b813100-d1c5-11ea-899a-74bf62951202.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797364-0cb25e00-d1c5-11ea-81fc-52fe4b54b6d4.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88797354-0a500400-d1c5-11ea-8e4b-55014d338b7f.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797358-0b813100-d1c5-11ea-8f22-938319e4dd2d.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797361-0c19c780-d1c5-11ea-9b15-38d96738ff71.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797366-0d4af480-d1c5-11ea-8b23-1008002d4472.png" width="200"/>

---
### Jeep

<img src="https://user-images.githubusercontent.com/33668152/88797832-c7426080-d1c5-11ea-96cc-f0d4dc77b1d7.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797838-c90c2400-d1c5-11ea-875f-fd9f1b3d5290.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797843-ca3d5100-d1c5-11ea-8ab7-31831d719466.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797852-cc071480-d1c5-11ea-8386-477130558afe.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88797836-c8738d80-d1c5-11ea-9e28-378efe762795.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797840-c9a4ba80-d1c5-11ea-8a8f-32efd316ee5d.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797850-cb6e7e00-d1c5-11ea-9ed6-dffb40950e0e.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88797855-cc9fab00-d1c5-11ea-8dbe-1401508b7743.png" width="200"/>

---
### GMC

<img src="https://user-images.githubusercontent.com/33668152/88791460-8e04f300-d1bb-11ea-87d2-082d945d8a18.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88791473-96f5c480-d1bb-11ea-872d-c73433fcdddb.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88791493-a117c300-d1bb-11ea-9706-fcbcae0284d2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88791536-b4c32980-d1bb-11ea-961c-3416e2c7daa8.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88791464-90674d00-d1bb-11ea-84c3-60e829adf558.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88791485-9d843c00-d1bb-11ea-87ea-f7e72e801a44.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88791496-a37a1d00-d1bb-11ea-970d-a5df0492759a.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88791546-b7be1a00-d1bb-11ea-9614-c376b343c034.png" width="200"/>

---

### 3 kona

<img src="https://user-images.githubusercontent.com/33668152/88798336-8e56bb80-d1c6-11ea-8006-c3facd3a4f1a.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798342-90207f00-d1c6-11ea-972b-ee4e60ea43e9.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798346-9151ac00-d1c6-11ea-86d2-a0765b81c4b5.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798349-931b6f80-d1c6-11ea-8a63-538cb953cc64.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88798340-8f87e880-d1c6-11ea-88c0-a234bd77b810.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798343-90b91580-d1c6-11ea-902e-ae6069ed7cc0.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798347-9282d900-d1c6-11ea-8724-b0fd3d9af176.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798353-944c9c80-d1c6-11ea-91cd-0791d3708b06.png" width="200"/>

---


### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---










