## 1. Get a model
You can either export a [.stl](https://en.wikipedia.org/wiki/STL_(file_format) file from you prefered modeling program or checkout [thingiverse](http://www.thingiverse.com) for a pre built model.

## 2. Slice it

In order for the printer to understand the file was are truing to print we need to convert the file to [G-Code](https://en.wikipedia.org/wiki/G-code). Think of G-Code as the language spoken by the printer. We do this using an application called a slicer.


You can download a free slicer for the Zortrax M200 [here](http://support.zortrax.com/downloads/). When prompted enter the model number of our Zortrax M200 (Serial number ZBF7FE4B8)
![here](/assets/downloadslicer.png)


Once download you can install the slicer by moving the application to you applications folder.

![Install Z-suit Application](/assets/installzsuite.png)

When you first open Z-Suite you will again be prompted to enter the serial number of the printer (ZBF7FE4B8). Then select the model M200 and

 Next select *open model* from the menu in the upper left had corner and select the .STL file you either made or downloaded earlier from the dropdown.
![Open STL File](/assets/openstlfile.png)

Now we need to choose the fidelity of the model. 3d printers measure  quality in-terms of microns. The CubePro can print from 300um - 70um. Think of microns as the ppi for 3d form resolution. To configure the print resolution and add any support structure select *build* from right had side of the navigation.

### 2.2 Build It
There are three steps to building you model.

| Preset   | Resolution | Strength | Pattern  |
|:---------|:----------:|:--------:|:--------:|
| Standard |   200um    |  Strong  |  Cross   |
| Premium  |   200um    |  Strong  | Diamonds |
| Draft    |   300um    |  Hollow  |  Cross   |




![Build STL](/assets/buildfromstl.png)

![Build STL](/assets/savestl.png)

![Build STL](/assets/printtime.png)





## 3. Print it

## 4. Cleaning up the model


Want to print commenting
[thingiverse](https://www.thingiverse.com/)

## Added Complexity
