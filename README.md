# Random-Coding-Image-Generator
Random Coding Image Generator

<?php
$access_key = 'KAUIqn7nY4obFSaPk0olfrQagyAyt46aZilfbls0NAQ'; // Replace with your own Access Key
$endpoint = 'https://api.unsplash.com/photos/random?query=programming&orientation=landscape&client_id=' . $access_key;
$image_url = json_decode(file_get_contents($endpoint))->urls->regular;
?>
<!DOCTYPE html>
<html>
<head>
    <title>Random Unsplash Image</title>
</head>
<body>
    <img src="<?php echo $image_url; ?>" alt="Random image from Unsplash">
</body>
</html>







