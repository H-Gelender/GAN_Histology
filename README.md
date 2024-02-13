# WGAN_GP-Histology

## **Projet GAN pour l'Histologie**
Ce projet vise à perfectionner les compétences dans la création de Réseaux Antagonistes Génératifs (GANs) pour l'histologie médicale. L'objectif est de développer un générateur de données capable de produire des images histologiques à partir d'un ensemble de données limité. Cette approche est particulièrement pertinente pour la génération d'images histologiques de maladies rares où les ensembles de données sont souvent limités.

## Fonctionnalités
Création de Dataset à partir de Lames Histologiques: Le code propose des outils pour créer un dataset à partir de lames histologiques. Cela permet de rassembler les données nécessaires à l'entraînement du générateur.

**Entraînement d'un Générateur de Données:** Le projet comprend des fonctionnalités pour entraîner un générateur de données utilisant l'architecture GAN. Le générateur est capable de produire des images histologiques à partir du dataset créé.

## Utilisation
Pour utiliser ce projet, suivez les étapes suivantes :

**Création du Dataset:** Utilisez les outils fournis pour créer un dataset à partir de lames histologiques.

**Configuration du Générateur:** Configurez les paramètres du générateur selon vos besoins, tels que la taille de l'image en entrée, le nombre de couches, etc.

**Entraînement du Générateur:** Entraînez le générateur en utilisant le dataset préparé. Surveillez les métriques d'entraînement telles que la perte du générateur et du discriminateur.
Résultats :
Les résultats d'un très petit WGAN-GP sur des images redimensionnées de 128x128 à 64x64 pixels peuvent être trouvés dans ce [dossier](https://github.com/H-Gelender/GAN_Histology/tree/main/gen_images)..

Voici des exemples d'images générées après 98 epochs :

![Alt epoch_98](https://github.com/H-Gelender/GAN_Histology/blob/main/gen_images/epoch_98.jpg)

Voici des échantillons de tissus réels :

![Alt](https://github.com/H-Gelender/GAN_Histology/blob/main/real_breast_tissue_images.png)

Ces résultats sont encore irréalistes, mais vous pouvez ajouter des couches plus complexes, et augementer le nombre d'epochs.

## **GAN Project for Histology**
This project aims to improve skills in creating Generative Adversarial Networks (GANs) for medical histology. The objective is to develop a data generator to produce realistic histological images from a limited dataset. This approach is particularly relevant for generating histological images of rare diseases where the datasets are often limited.

## Features
Creation of Dataset from Histological Slides: The code provides tools to create a dataset from histological slides. This allows for the collection of data necessary for training the generator.
Training a Data Generator: The project includes features for training a data generator using the GAN architecture. The generator is capable of producing realistic histological images from the created dataset.

## Usage
**Creating the Dataset:** Use the provided tools to create a dataset from histological slides.

**Configuring the Generator:** Configure the generator parameters according to your needs, such as the size of the input image, number of layers, etc.

**Training the Generator:** Train the generator using the prepared dataset. Monitor training metrics such as the generator and discriminator loss.

## Results: 

The results of a very small WGAN-GP on resized images from 128x128 to 64x64 pixels can be found in this [folder](https://github.com/H-Gelender/GAN_Histology/tree/main/gen_images).

These are examples of generated images after 98 epochs: 

![Alt epoch_98](https://github.com/H-Gelender/GAN_Histology/blob/main/gen_images/epoch_98.jpg)

These are real tissue samples:

![Alt](https://github.com/H-Gelender/GAN_Histology/blob/main/real_breast_tissue_images.png)

These results are still unrealistic, but you can add more complex layers and increase the number of epochs.
