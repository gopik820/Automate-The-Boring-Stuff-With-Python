### Practice Questions:-

1. What is an RGBA value?

**Answers**
```
The amount of Red,Blue and Green that is used in an image.
```
2. How can you get the RGBA value of 'CornflowerBlue' from the Pillow module?

**Answers**

```ImageColor.getcolor('CornflowerBlue', 'RGBA')```

3. What is a box tuple?

**Answers**
```
The left-edge x-coordinate, the top-edge y-coordinate, the width, and the height together is the box tuple
```
4. What function returns an Image object for, say, an image file named zophie.png?

**Answers**

```Image.open('zophie.png')```

5. How can you find out the width and height of an Image object’s image?

**Answers**

```imageObj.size ```

6. What method would you call to get Image object for a 100×100 image, excluding the lower-left quarter of it?

**Answers**

```imageObj.crop((0, 50, 50, 50))```

7. After making changes to an Image object, how could you save it as an image file?

**Answers**

```imageObj.save()```

8. What module contains Pillow’s shape-drawing code?

**Answers**
```
ImageDraw
```
9. Image objects do not have drawing methods. What kind of object does? How do you get this kind of object?

**Answers**
```
ImageDraw objects have shape-drawing methods such as point(), line(), or rectangle().
They are returned by passing the Image object to the ImageDraw.Draw() function.
```