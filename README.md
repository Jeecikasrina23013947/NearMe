# Ex04 Places Around Me
## Date: 14.04.2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImageMap</title>
</head>
<style>
    *{margin: 0;}
</style>
<script>
    function coordinate(event)
    {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("text1").value=x;
        document.getElementById("text2").value=y;
    }
</script>
<body>
    <IMG src="Map.png" width="100%" height="500" usemap="#MapNew" onmousemove="coordinate(event)">
        <MAP name="MapNew">
           <AREA shape="RECT" coords="643,196,631,147" href="https://www.saveetha.ac.in/" title="saveetha Engineering College"></AREA>
           <AREA shape="RECT" coords="556,253,552,209" href="https://kingsedu.ac.in/" title="Kings Engineering College"></AREA>
           <AREA shape="RECT" coords="903,118,918,150" href="https://srmeaswari.ac.in/" title="SRM Eswari Engineering College"></AREA>
           <AREA shape="RECT" coords="960,380,947,330" href="https://sairam.edu.in/" title="Sri Sairam Engineering College"></AREA>
           <AREA shape="RECT" coords="1032,162,1030,112" href="https://msec.edu.in/" title="Meenakshi Engineering College"></AREA>
           <AREA shape="RECT" coords="595,304,600,267" href="https://www.citchennai.edu.in/" title="Chennai Institute of technology"></AREA>
        </MAP>
        <br>
        X-coordinate
            <input type="text" id="text1">
        Y-coordinate 
            <input type="text" id="text2">
</body>
</html>

```


## OUTPUT
 ![Screenshot 2024-04-14 213551](https://github.com/JAYASREE24032006/NearMe/assets/144360800/a1640895-413b-4b3c-981e-4402c61c2f43)

 ![Screenshot 2024-04-14 213618](https://github.com/JAYASREE24032006/NearMe/assets/144360800/124fc251-6a6c-4399-982c-b7be1aad9cf0)

 ![Screenshot 2024-04-14 220717](https://github.com/JAYASREE24032006/NearMe/assets/144360800/f2775713-f51c-4de1-94f3-d9171eb9dd0b)

 ![image](https://github.com/JAYASREE24032006/NearMe/assets/144360800/8deb3d6a-4e24-43df-b6e8-9bf3072d87c6)

 ![image](https://github.com/JAYASREE24032006/NearMe/assets/144360800/2941cef4-9b7e-4dea-a153-c69c358ddcb4)

 ![Screenshot 2024-04-14 220911](https://github.com/JAYASREE24032006/NearMe/assets/144360800/bddda35b-b067-410d-b3b3-bfd8929ed518)











## RESULT
The program for implementing image maps using HTML is executed successfully.
