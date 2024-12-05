<p align="center">
    <a href="______________">
    </a>
</p>


[En Français](# NDWI sur Google Earth Engine  - Tutoriel)  
[In English](# NDWI on Google Earth Engine - Tutorial)    

# NDWI sur Google Earth Engine  - Tutoriel

## Contexte
Ce code permet de télécharger une image optique Sentinel-2 et de calculer l'indice d'eau par différence normalisée (NDWI) directement à partir de Google Earth Engine, afin d'identifier la présence d'eau dans une image satellitaire. Le NDWI se calcule généralement à partir des bandes Green (vert, bande 3) et Near Infrared (proche infrarouge (NIR), bande 8) d'une image satellite Sentinel-2 (McFeeters, 1996). Nous avons utilisé les produits Sentinel-2 L2A pour ce tutoriel: 

- S2A_MSIL2A_20240421T133151_N0510_R081_T22JCM_20240421T204952  

- S2B_MSIL2A_20240506T133149_N0510_R081_T22JCM_20240506T154438  

## Avant de commencer :

Assurez-vous d'avoir un compte Google.


# NDWI on Google Earth Engine - Tutorial

## About
This code allows you to download a Sentinel-2 optical image and calculate the Normalized Difference Water Index (NDWI) directly in Google Earth Engine to identify the presence of water in a satellite image. The NDWI is typically calculated using the Green band (band 3) and the Near Infrared (NIR) band (band 8) of a Sentinel-2 satellite image (McFeeters, 1996). We used Sentinel-2 L2A products for this tutorial: 

- S2A_MSIL2A_20240421T133151_N0510_R081_T22JCM_20240421T204952  

- S2B_MSIL2A_20240506T133149_N0510_R081_T22JCM_20240506T154438
  
## Before starting

Make sure you have a Google account.

