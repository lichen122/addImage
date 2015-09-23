This is an example show you add to directly add image or restaer data onto the map without the need to publishing the image as an imageservices.

Steps:
1.have a img ready no matter from your local or from online resources.
2.Create a MapImage class("esri/layers/MapImage") and pass in the image url and the extent where you want to show the image on. 
3.Create a MapImageLayer("esri/layers/MapImageLayer") and pass in the mapimage. 
4.Lastly, add the mapImageLayer on to the map.