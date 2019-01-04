## Building a 4m radio telescope for the 21cm hydrogen line (and other things too)
### Reflector
This is the most recognizable part of the Telescope. Its a parabolic surface that reflects all the incoming radiation into the focal point, where the actual antenna (called feed) picks up the signal.  

**Requirements for the reflector**:
- As big as possible so the signal is strong enough that cheap electronic components can be used
- Portable and easy to assemble as we have no place to permanently mount it
- Made from cheap materials such as wood
- Holes not bigger than 1/10th of the Wavelength (2cm)
- Surface deviations not bigger than 1% of the Wavelenght (2mm)  
  
As a solution to these requirements we came up with a dish with a diameter of 3.5m made from 19 hexagonal elements. Each of those elements is made from 40cm long plywood pieces which are held togehter by small 3d printed pieces and hot glue. The inner 7 are mounted onto a scaffold made from broomsticks and 3d printed parts. The whole dish is covered with chicken wire with a Mesh size of 13mm. The whole design was made in Fusion360

![Reflector design in Fusion 360](https://github.com/phil1425/magentata/fusion-perspektive.png)
![Reflector design in Fusion 360](https://github.com/phil1425/magentata/closeup-element.png)
![Reflector design in Fusion 360](https://github.com/phil1425/magentata/closeup-mount.png)
![Reflector design in Fusion 360](https://github.com/phil1425/magentata/frontal.png)
![Reflector design in Fusion 360](https://github.com/phil1425/magentata/oben.png)
![Reflector design in Fusion 360](https://github.com/phil1425/magentata/perspektive.png)
  
**Pros**
- Easy to disassemble into 25 parts not bigger than 1m
- Only uses about 10sqm of plywood and 1kg of PLA
- The parts are small enough to be made in a 3d printer and laser cutter which are both available in the workshop  
  
**Cons**
- About 600 inividual parts made of plywood and 300 3d printed parts
- Not very rigid, wont survive permanently outdoors

 
### Azimuth mount
This will move the Antenna around so it can be pointed anywhere at the sky. Later it will hopefully be motorized and controllable by a computer. For now it can only be moved manually.  

### Feed Horn
The feed is the part that picks up the radiation so it can be amplified and measured. Basically its a metal can that is open on one side with a small exposed wire inside.  
The feed is based on this [design by Saje and Vidmar](http://antena.fe.uni-lj.si/literatura/Razno/Diplome/Radioteleskop/clanek/radioteleskop.pdf).  
The horn itself is made from 1mm Aluminium sheets: Two half-circles and a quadratic baseplate. After many failed attempts at TIG welding the sheets together we used rivets to form a cylinder. The cylinder was then welded to the baseplate.  
Since the Horn was Rigid enough, the choke was made from laser-cut cardboard covered in tin foil an directly attached to the baseplate  

We drilled a small hole into the side of the horn to attach an SMA connector.
### Electronics
### Software
