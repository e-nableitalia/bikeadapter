## bikeadapter

A bike adapter device for children with limb difference problems, configurable to be adapted to the user, can be entirely build with a 3d printer using a flexible filament

## Description

After several iteraction the e-Nable Italia's team composed by Alessandro and Michele has released the first prototype of a hand device called "Bike Adapter".

This device was designed to help children and adults with limb difference problems (amputations or agenesys of hand/arm) to easly connect with the bicycle handlebar allowing a better control of the bike direction.

Fusion version is deprecated and was left here only for historical reason, we suggest to to build your device using the last stable version published on OnShape by e-Nable Italia (See OnShape project below).

The device is printed with flexible filament (TPU) to obtain the perfect mix between comfort, safety and functionality.
The project is open source, e-Nable Italia's volunteers provide the Bike Adapter device (and others) free of charge for anyone is in need of such assistive devices.

## History

Up to Rev. 18v6 of the project the Bike Adapter was entirely designed with Autodesk Fusion360 and can be customized setting the approriate values in the available parameters allowing the generation of a 3d model adapted to the end user and thus STL or 3MF files for the slicer/3d printer.

Since Rev. 19 the project was moved on OnShape and project version numbering was restarted.

## OnShape project

* [Stable release](https://cad.onshape.com/documents/ca8363f0e231780e668e998b/w/a26bb6ec5623c8082f0c169f/e/3e5b5222f11b40dd3fc85b5d) - Manteined by e-Nable Italia

> [!IMPORTANT]
> This project is parametric and requires specific recipient adaptation, see **dimensioning** section for details.


## Version history

* [OnShape V3](https://cad.onshape.com/documents/ca8363f0e231780e668e998b/w/a26bb6ec5623c8082f0c169f/e/3e5b5222f11b40dd3fc85b5d) - reinforced structure, added internal hole to double perimeters surface and to increase flexibility, new design significatively decreases print time
* [OnShape V2](https://cad.onshape.com/documents/5b587ad656e9d002f8e6bad6/w/de2c6c2802ab923db649ef32/e/ab629266e0f6758e30a87845) - added multiple supports
* [OnShape V1](https://cad.onshape.com/documents/46a4c4172ddd04c75d593001/w/5926f7823c4074041b5158a1/e/589555b9dba7eac6af07f0b4) - first release, single support

* [Development release](https://cad.onshape.com/documents/e225086690158d5a937bf9fe/w/4021bf2bfacdceba3b1f0556/e/9dfe74fe60fd68384dbb2f50) - Mantained by Alessandro Villa

## Thingiverse project

the project was also published on Thingiverse at the following link: [Bike Adapter](https://www.thingiverse.com/thing:5422603)

## Dimensioning

Dimensioning is done by setting appropriate values in parameters exposed in the OnShape project.

An online configurator tool is available at the following address: [Bike Adapter Configurator] (https://dev.e-nableitalia.it/configurator/)

Manual dimensioning can be done by inserting the appropriate values in the OnShape Feature panel.
Insert the values in the parameters in sequence:
* A_lng_unaff, length of unaffected arm
* B_lng_affect, length of affected arm
* C_tip_circ, circumference length, measured approximately 2 cm below the tip of the stump
* D_root_circ, circumference length, measured at the elbow crease
* E_handle_dia, bike handlebar diameter
* F_lng_affect_inner_elbow, length of affected arm, measured from elbow crease to the tip of the stump
* vent_hole_no, number of vent holes, take care to choose an appropriate value to keep holes below the solid body of the device

Instructions for dimensioning the device can be found [here](https://e-nableitalia.it/en/dimensionamento-bike-adapter/)

## Printing directives

* Rafts: No 
* Supports: No 
* Resolution: 0.2 
* Infill: 15% - Gyroid
* Filament brand: Ninjaflex 
* Filament color: Whater Translucent (#3DNF0829005), this material has proven to be the most realiable and with better layer adhesion (compared to other colors and filament brands we evaluated)
* Filament material: TPU, suggested shore 85a, higher shore gives more rigidity, use lower for additional flexibility for the device.

## Authors

Michele Praga - pragamichele@gmail.com

Alessandro Villa - filotto78@gmail.com

e-Nable Italia - info@e-nableitalia.it 

Check for further information, updates and information on this and other e-Nable Italia’s projects on our website: [https://e-nableitalia.it/bikeadapter](https://e-nableitalia.it/it_it/portfolio/bike-adapter/) & https://e-nableitalia.it

## License

This material is released under *Creative Commons - Attribution - Non-Commercial - Share Alike license*

## LIMITATION OF LIABILITY.

UNDER NO CIRCUMSTANCES AND UNDER NO LEGAL THEORY, WHETHER TORT (INCLUDING NEGLIGENCE), CONTRACT, OR OTHERWISE, SHALL YOU, THE INITIAL DEVELOPER, ANY OTHER CONTRIBUTOR, OR ANY DISTRIBUTOR OF COVERED CODE, OR ANY SUPPLIER OF ANY OF SUCH PARTIES, BE LIABLE TO ANY PERSON FOR ANY INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF GOODWILL, WORK STOPPAGE, COMPUTER FAILURE OR MALFUNCTION, OR ANY AND ALL OTHER COMMERCIAL DAMAGES OR LOSSES, EVEN IF SUCH PARTY SHALL HAVE BEEN INFORMED OF THE POSSIBILITY OF SUCH DAMAGES. THIS LIMITATION OF LIABILITY SHALL NOT APPLY TO LIABILITY FOR DEATH OR PERSONAL INJURY RESULTING FROM SUCH PARTY'S NEGLIGENCE TO THE EXTENT APPLICABLE LAW PROHIBITS SUCH LIMITATION. SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OR LIMITATION OF INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO THIS EXCLUSION AND LIMITATION MAY NOT APPLY TO YOU.

