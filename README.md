# Rate-stars
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <video controls width="620" height="440">
        <source src="223.mkv" type="video/mp4">
      </video>
    
      <form>
        <div>
          <label for="rating">Rating</label>
          <input type="range" min="1" max="5" id="rating" name="rating" list="ratings">
          <datalist id="ratings">
              <option value="1" label="1"></option>
              <option value="2"></option>
              <option value="3"></option>
              <option value="4"></option>
              <option value="5" label="5"></option>
          </datalist>
        </div>
        <button type="submit">Submit Rating</button>
      </form>
</body>
</html>
