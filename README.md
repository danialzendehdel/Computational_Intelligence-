# Ship Classification and Localisation 


`Professor`  : Antonello Rizzi   
`Supervisor` : Emanuele Ferrandino  
`authors`    : Danial Zendehdel , Peyman Javaheri.  

The aim of this project was to classify ships in 5 different categories such as Cargo , Cruise , Military,Carrier , Tanker and in addition to that find the centriod of each found ship in the image.  


The Dataset has been downloaded from `Game of Deep Learning` website.The link for downloadinf the Dataset is [here](https://drive.google.com/drive/folders/1LJI0l9YI91xK8WGrdl5S-4U-KgMOY-pM?usp=sharing),then from these images the new CSV file extracted with benefit of using `LabelImg` with annotations in addition to labels which are included in this repository.  

There are 2125 images from Cargo , 916 from Carrier , 776 from Cruise ,1148 from Military and 1217 Tanker. 



Two models have been used in here :   
Multiple ouput : this is MobileNetV2 base model which is used to get predictions for both bounding boxes and labels classification , some layers added for Regression leg.  
Second Model : This one consists two model one Xception exclusive for Classification and MobileNetV2 for regression.


The Wrights for Demo can be downloaded from [here](https://drive.google.com/drive/folders/1r_rpWPb6CWqYgPlyaUK9CqYv1GbBu3nM?usp=sharing).   
Link for Test Data [here](https://drive.google.com/drive/folders/1BSx8Ozi1P-vKpHDZIPSxMPPx6gD48WrQ?usp=sharing)
