# CS 240 Notes

### About Image Editor assignment
- Done in Java, learn Java from the textbook on your own.
- Read a File, add conversion to it, output into another file.
- What would you need to know in Java to do the image editor?
  - file input, specify command-line parameter, convert strings to ints
  - Java fundamental slides
- Read files in from .ppm which is a text file format
- Give program a file and the program will store and manipulate the information. 

- How to invoke a Java program:
```
java ImageEditor inputFileName outputFileName {grayscale|invert|emboss|motionblur motion-blur-length}
```
### Trouble Shooting
- Motion blur and emboss require data from pixels around it
  - use either a copy of the image, and take data from original and edit the copy or...
  - start from the bottom right instead of top left pixel and it works fine
- If the image has a line through the middle or if the image is almost right but not quite, check if you're dealing with columns or rows.
  
### Tips
- Have methods for reading and writing a file. Good practice is creating a class for both but that is advanced and not needed in the class.

---

## ***01-08-2020* - Java Fundamentals**

#### Similar syntax but different semantics from C++
#### Java cleans up C++
#### Differences between Java and C++
- Built-in garbage collection
- References instead of pointers
- Data types are always the same size in Java
- Specific boolean datatype and language constructs made to use it
- Classes dynamically linked at runtime
- Java is a hybrid, compiled / interpreted language
- Several other differences 