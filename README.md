# Vehicle Logos Dataset

![Vehicle_Logo]()
(Collage cover will be added)

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


| No        | Category           | Images  |
| ------------- |:-------------:| -----:|
| 1          |    Toyota        | 16 |

| Category           |-------------|toyo|
| Images  |-------------|50|

'Toyota' 'Mitsubishi' 'Seat' 'Suzuki' 'Opel' 'Honda 1' 'Renault'
 'Mercedes 1' 'Volkswagen' 'Subaru' 'Dacia 1' 'Citroen' 'Land Rover'
 'Tesla' 'Mazda' 'Nissan' 'Hyundai' 'Lancia 1' 'Skoda 1' 'Chevrolet 2'
 'Porsche' 'Peugeot' 'Jeep' 'Mini' 'Kia 1' 'Lexus' 'Smart 2' 'Volvo 1'
 'GMC' 'Ford' 'Daewoo 1' 'Acura' 'Alfa Romeo' 'BMW'

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




