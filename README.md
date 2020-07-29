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

### 2 side

<img src="https://user-images.githubusercontent.com/33668152/88799104-cc081400-d1c7-11ea-900b-eeebbe1c83e2.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799110-cdd1d780-d1c7-11ea-9997-961eeeab4474.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799119-cf030480-d1c7-11ea-9ca7-402c14b537b7.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799123-d0ccc800-d1c7-11ea-9233-7dcc6681844e.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88799108-cd394100-d1c7-11ea-86ab-6ddacbb092b5.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799115-cf030480-d1c7-11ea-9edd-9985419b31fa.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799121-d0343180-d1c7-11ea-829c-0318e3a7f757.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88799128-d1fdf500-d1c7-11ea-97ba-b600751c7edf.png" width="200"/>

---

### Volvo

<img src="https://user-images.githubusercontent.com/33668152/88798702-2654a500-d1c7-11ea-91f0-52a84a9d3a63.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798710-281e6880-d1c7-11ea-8c9e-bd9d047a0778.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798716-2a80c280-d1c7-11ea-875b-347a8bead720.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798731-2e144980-d1c7-11ea-91a0-37cb9ab1c2d8.png" width="200"/>

<img src="https://user-images.githubusercontent.com/33668152/88798708-2785d200-d1c7-11ea-9996-f49e684b5635.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798715-29e82c00-d1c7-11ea-8a08-7d22194fd702.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798729-2d7bb300-d1c7-11ea-8cc3-31e616d61368.png" width="200"/> <img src="https://user-images.githubusercontent.com/33668152/88798734-2f457680-d1c7-11ea-9c2d-dad5fec47b71.png" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

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

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

<img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/> <img src="" width="200"/>

---

### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---
### Ford

<img src="https://user-images.githubusercontent.com/66736646/88667821-aa455900-d103-11ea-882f-26d576adce1e.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667867-b5988480-d103-11ea-813b-37a774f6612a.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667879-bb8e6580-d103-11ea-91c8-e4bec0d4ebd7.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88667905-c21cdd00-d103-11ea-8609-4d86364efa40.png" width="200"/>

<img src="https://user-images.githubusercontent.com/66736646/88671365-07dba480-d108-11ea-84a6-c84dff40d8df.jpg" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670762-4886ee00-d107-11ea-8e88-3e26e72530c9.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670781-4d4ba200-d107-11ea-9743-6327eb6da28f.png" width="200"/> <img src="https://user-images.githubusercontent.com/66736646/88670805-5472b000-d107-11ea-803e-2c34aa8e2528.png" width="200"/>

---




