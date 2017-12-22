## 1. Get a model
You can either export a [.stl](https://en.wikipedia.org/wiki/STL_(file_format) file from you prefered modeling program or checkout [thingiverse](http://www.thingiverse.com) for a pre built model.

## 2. Slice it

In order for the printer to understand the file was are truing to print we need to convert the file to [G-Code](https://en.wikipedia.org/wiki/G-code). Think of G-Code as the language spoken by the printer. We do this using an application called a slicer.


You can download a free slicer for the Zortrax M200 [here](http://support.zortrax.com/downloads/). When prompted enter the model number of our Zortrax M200 (Serial number ZBF7FE4B8)
![here](/assets/downloadslicer.png)


Once download you can install the slicer by moving the application to you applications folder.

![Install Z-suit Application](/assets/installzsuite.png)

When you first open Z-Suite you will again be prompted to enter the serial number of the printer (ZBF7FE4B8). Then select the model M200.
![Open STL File](/assets/selectm200.png)

 Next select *+* from left side menu bar and select the .STL file you either made or downloaded earlier from the dropdown.

![Open STL File](/assets/openstlfile.png)

Now we need to choose the fidelity of the model. 3d printers measure  quality in-terms of microns. The m200 can print from 300um - 70um. Think of microns as the ppi for 3d form resolution. Our printer also rates the infill from scale Maximum (100% solid) to Low ( 25% solid)

|Name|Percent Solid|
|:--|:--|
|Maximum|100%|
|High   |  75% |
|Medium   |  50% |
|Low   |  25% |

![Build STL](/assets/savestl.png)
To configure the print resolution and add any support structure select *prepare to print* from the botton left of the window.

### 2.2 Build It



![Build STL](/assets/printbuilding.png)
Now slicer will build the file for the printer. This can take any where from under a minutes to an hour depending on how complexity of the print geometry.


![Build STL](/assets/printtimebuilt.png)
Once finished you will see the amount of material needed and estimated print time at the bottom of the window. The printer can be left over night but you need to make sure there is enought material on the spool if you choose to do so.




## 3. Print it

![Build STL](/assets/savetosd.png)


![Build STL](/assets/insertsd.png)


![Build STL](/assets/startprint.png)


## 4. Cleaning up the model

When you print has finished the printer will chime and start to cool. Check out this site to learn more about [removing your print from the platform.](http://support.zortrax.com/removing-the-print-m200/)


## Printer maintance

Zortrax has wonderful documentation on keeping the m200 well takencare of check out [here](http://support.zortrax.com/all-categories/?printers=m200) to learn more.
