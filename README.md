![Logo3](https://user-images.githubusercontent.com/51221856/131055087-984f233a-a2b4-4bb8-b1bf-d8ecc2f7de60.png)

# It is a 2D game engine in progress(written on Object Pascal and compilled in Lazarus). 
# Uses software rendering. 
# Of the features, I can note the super high performance of splines and sprites(work is still being done on it). 
# In the future, a powerful editor for sprites, splines and other game objects will be available.
# Executable file(MorphoEngine.exe) is included, so run-n-fun 😉. 

Screenshots:
   1. Editor Mode
![Editor_Preview1](https://user-images.githubusercontent.com/51221856/176047575-8e07de12-8bfe-4a2f-b57c-303e02846766.png)
![EditorPreview1](https://user-images.githubusercontent.com/51221856/172098745-7ae412e7-996a-4486-8380-322a14bc951f.png)
   2. Game Mode
![EditorPreview1](https://user-images.githubusercontent.com/51221856/160922932-8df2367c-f756-4325-b07f-177e94b40ec3.png)

Nearest TODO:
  - Optimization:
    1. get rid of double, triple or quadruple addressing (priority: low; complexity: easy);
    2. ...;
  - UI:
    1. implementation of object tags(priority: high; complexity: middling);
    2. ...;
  - Sprites:
    1. implementation of rotation and scaling of CSR-images(Compressed Sparse Row), possibly with bilinear filtering (priority: medium; complexity: very hard);
    2. ...;
  - Splines:
    1. static contour anti-aliasing for sparse sprites in CSR format (priority: low; complexity: hard);
    2. implementation of drawing for CSR-lines of any width greater than 3 (priority: low; complexity: very hard);
    3. Bezier splines (priority: high; complexity: middling).
