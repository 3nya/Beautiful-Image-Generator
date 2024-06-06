Small project 

With the input of one image (any image), you can turn it into a beautiful picture! Uses pixels from your image to depict a (similar in color) beautiful image. 
Uses Pillow and NumPy :)

Things i want to fix (5/18):
- Uses average color but this doesn't totally bring out the ideal results (avg color vs dominant color). I want to change the algorithim to search for dominant colors instead. 
- Algorithim is slow (not that slow, but would like to try something different than brute forcing)
  - Additionally brute force would not work for larger images and smaller pixels
- Need to fix the forloop for some reason it doesn't go over the entire image (in the test it does but that was manually tweaked to work for that one image)

(6/5):
- Can use any sized image now and can choose the overal quality of the image (choosing size of each displayed pixel)
- Added a method that uses dominant color but there isn't much of a difference... probably going to try making another method...
- Tried RGBA over RGB but no big difference
