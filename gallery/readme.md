<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Advik Electronic - Gallery</title>
    <style>
        body { font-family: Arial, sans-serif; margin:0; padding:0; background:#111; color:white; }
        h1 { text-align:center; padding:20px; }
        .gallery { 
            display: grid; 
            grid-template-columns: repeat(auto-fill, minmax(140px, 1fr)); 
            gap:10px; 
            padding:15px; 
        }
        .gallery img { 
            width:100%; 
            height:150px; 
            object-fit:cover; 
            border-radius:8px;
            border:2px solid #222;
        }
    </style>
</head>
<body>
    <h1>Advik Electronic - Gallery</h1>

    <div class="gallery">
        <img src="gallery/IMG_0406.jpeg">
        <img src="gallery/IMG_1063.jpeg">
        <img src="gallery/IMG_1064.jpeg">
        <img src="gallery/IMG_1066.jpeg">
    </div>

</body>
</html>
