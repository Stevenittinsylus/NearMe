# Ex04 Places Around Me
## Date: 18/12/24

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
map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>ORAGADAM</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>STEVE NITTIN SYLUS(24001421)</b></font>
</h3>
<center>


<img src="Screenshot 2024-11-26 080605.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Pachaiamman Temple" title="Pachaiamman Temple" href="temp.html" coords="584,269,655,324" shape="rect">
    <area target="" alt="Murugappa Polytechnic" title="Murugappa Polytechnic" href="clg.html" coords="261,459,66" shape="circle">
    <area target="" alt="Thangal Park" title="Thangal Park" href="park.html" coords="1304,432,1337,471,1342,534,1276,525,1273,460" shape="poly">
    <area target="" alt="Vcare Hair and Skin Clinic" title="Vcare Hair and Skin Clinic" href="vcare.html" coords="1055,659,63" shape="circle">
    <area target="" alt="Msk Diamond Mahal" title="Msk Diamond Mahal" href="mahal.html" coords="771,338,1074,404" shape="rect">
</map>
</center>
</body>
</html>

clg.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Murugappa Polytechnic</title>
    <style>
        body {
            background: linear-gradient(to right, #4facfe, #00f2fe);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #fff;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            margin: 0;
            border-bottom: 2px solid #00f2fe;
            font-size: 3rem;
        }
        p {
            text-align: justify;
            margin: 30px auto;
            font-size: 1.2rem;
            line-height: 1.8;
            max-width: 800px;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            p {
                font-size: 1rem;
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <h1>Murugappa Polytechnic</h1>

    <p>Murugappa Polytechnic is one of the leading technical educational institutions in the region. Established to offer quality education and skill development in engineering and technology, it provides various diploma courses in fields such as mechanical, electrical, and civil engineering. The polytechnic is well-equipped with modern infrastructure and labs, offering students a hands-on learning experience.</p>

</body>
</html>


park.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thangal Park, Ambattur</title>
    <style>
        body {
            background: linear-gradient(to right, #d4fc79, #96e6a1);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #2c3e50;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #fff;
            background: linear-gradient(to right, #43cea2, #185a9d);
            padding: 20px;
            margin: 0;
            font-size: 3rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
            border-bottom: 3px solid #96e6a1;
        }
        p {
            text-align: justify;
            margin: 30px auto;
            font-size: 1.2rem;
            line-height: 1.8;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            p {
                font-size: 1rem;
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <h1>Thangal Park, Ambattur</h1>

    <p>Thangal Park, located in Ambattur, is one of the most popular recreational parks in the area. It serves as a serene space for people of all ages to relax, walk, and enjoy nature. The park is well-maintained, featuring walking paths, benches, and greenery, making it a great spot for family outings and fitness enthusiasts alike. With ample space for children to play, it is an ideal destination for those seeking a peaceful escape from the hustle and bustle of the city.</p>

</body>
</html>

temp.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pachaiamman Temple, Thirumullaivoyal</title>
    <style>
        body {
            background: linear-gradient(to right, #a1ffce, #faffd1);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #2c3e50;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #fff;
            background: linear-gradient(to right, #6dd5ed, #2193b0);
            padding: 20px;
            margin: 0;
            font-size: 3rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
            border-bottom: 3px solid #a1ffce;
        }
        p {
            text-align: justify;
            margin: 30px auto;
            font-size: 1.2rem;
            line-height: 1.8;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            p {
                font-size: 1rem;
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <h1>Pachaiamman Temple, Thirumullaivoyal</h1>

    <p>Pachaiamman Temple, located in Thirumullaivoyal, Chennai, is an ancient and revered temple dedicated to Goddess Pachaiamman. The temple holds great religious significance for the local community and attracts devotees throughout the year. The temple is known for its peaceful ambiance and historic architecture, featuring intricately designed pillars and a serene environment for worship. Devotees visit the temple to seek blessings for prosperity, well-being, and spiritual growth. It is an important cultural landmark in the region and a place for meditation and prayer.</p>

</body>
</html>

vcare.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vcare</title>
    <style>
        body {
            background: linear-gradient(to right, #d9a7c7, #fffcdc);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #2c3e50;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #fff;
            background: linear-gradient(to right, #56ab2f, #a8e063);
            padding: 20px;
            margin: 0;
            font-size: 3rem;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
            border-bottom: 3px solid #a8e063;
        }
        p {
            text-align: justify;
            margin: 30px auto;
            font-size: 1.2rem;
            line-height: 1.8;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            p {
                font-size: 1rem;
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <h1>Vcare</h1>

    <p>Vcare is a leading service provider in the healthcare industry, committed to delivering top-quality healthcare solutions. We offer a wide range of services, including personalized care, medical consultations, and wellness programs. With a team of dedicated professionals and state-of-the-art facilities, Vcare ensures a holistic approach to health and well-being.</p>

</body>
</html>

mahal.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marriage Mahal</title>
    <style>
        body {
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #2c3e50;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #fff;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            padding: 20px;
            margin: 0;
            font-size: 3rem;
            border-bottom: 3px solid #ff9a9e;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
        p {
            text-align: justify;
            margin: 30px auto;
            font-size: 1.2rem;
            line-height: 1.8;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            p {
                font-size: 1rem;
                padding: 15px;
            }
        }
    </style>
</head>
<body>

    <h1>Marriage Mahal</h1>

    <p>Marriage Mahal is a premier venue offering an exquisite setting for weddings and other special occasions. With its spacious halls, luxurious decor, and top-notch amenities, it ensures that every event is memorable. Whether you're planning an intimate ceremony or a grand celebration, Marriage Mahal provides the perfect environment for your most important day.</p>

</body>
</html>

```


## OUTPUT
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)

![alt text](image-5.png)
![alt text](image-6.png)






## RESULT
The program for implementing image maps using HTML is executed successfully.
