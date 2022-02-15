# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### Home Page:
~~~html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BPRD HOME PAGE</title>
    <link rel="icon" href="./img/logo.png" type="image/x-icon" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</head>

<body>
    <div class="container-fluid">
        <div class="row">
            <img src="https://bprd.nic.in/images/GY1.jpg
            " style="height: 400px;" alt="police">

            <div class="col-sm-12 bg-info h1 text-center">Bureau of Police Research and Development</div>
            <div class="col-sm-12 bg-info h1 text-center">Ministry of Home affairs</div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/home.html">HOME</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/about.html">ABOUT US</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/gallery.html">GALLERY</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/training.html">TRAINING</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/admin.html">ADMIN</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/contactus.html">CONTACT US</a></div>
            <h3>General :</h3>
            <h4>
                The Bureau of Police Research and Development (BPR&D), was set up on 28 August 1970 in furtherance of the objective of the Government of India for the modernisation of police forces. It has evolved as a multifaceted, consultancy organisation. At present
                it has 4 divisions – Research, Development, Training and Correctional Administration.
            </h4>
            <h3>Functions :</h3>
            <h4>
                Functions of the Bureau of Police Research and Development (BPR&D) are different for each of the four divisions and are as follows:
            </h4>
            <h3>Research Division : </h3>
            <h4>
                1.Analysis and study of crime and problems of general nature affecting the police, e.g.,<br> 2.Trends and causes of crime.<br> 3.Prevention of crime-preventive measures, their effectiveness and relationship with crime. <br>4.Organisation,
                strength, administration, methods, procedures and techniques of the police forces and their modernisation, police act and manuals. <br>5.Improvements in methods of investigation, utility, and results of introducing scientific aids and
                punishment.
                <br>6.Inadequacy of laws. <br>7.Juvenile delinquency. <br>8.Police Uniform, badges, medals, decorations, colours, and flags, police drill, warrant of procedure etc. <br>9. Assistance of Police Research programmes in States and Union Territories,
                processing and coordination of research projects, sponsoring extra mutal research. <br>10.Work relating to Standing Committee on Police Research. <br>11.Police Science Congress & other conferences and seminars relating to study of police
                problems.
                <br>12.Participation in social defence and crime prevention programmes. <br>13.Participation in the work of the United Nations in the field of prevention of crime and treatment of offenders. <br>14.Maintenance of all India statistics of
                crime.
                <br>14.Statistical analysis of trends of crime. <br>15.Documentation relating to Police Science and Criminology. <br>16.Publication of: Police Research & Development Journal Crime in India Indian Police Journal Accidental Deaths and Suicides
                Research Reports and News Letters Reports, Reviews, other journals and books relating to matters connected with police work.
            </h4>


        </div>

    </div>
    <marquee>Thank you for visiting our Website</marquee>
    <footer>The Webpage was developed by Venkatesh E</footer>

</body>
<style>
    marquee {
        font-size: 50px;
        background-color: rgb(0, 195, 255);
        color: rgb(255, 255, 255);
    }
    
    footer {
        font-size: 30px;
        text-align: center;
        background-color: rgb(0, 195, 255);
        color: rgb(255, 255, 255);
    }
</style>

</html>
~~~
### About Page:
~~~html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BPRD ABOUT US</title>
    <link rel="icon" href="./img/logo.png" type="image/x-icon" />

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</head>

<body>
    <div class="container-fluid">
        <div class="row">
            <img src="https://bprd.nic.in/images/GY1.jpg" style="height:400px;" alt="police">

            <div class="col-sm-12 bg-info h1 text-center">Bureau of Police Research and Development</div>
            <div class="col-sm-12 bg-info h1 text-center">Ministry of Home affairs</div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/home.html">HOME</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/about.html">ABOUT US</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/gallery.html">GALLERY</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/training.html">TRAINING</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/admin.html">ADMIN</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/contactus.html">CONTACT US</a></div>
            <h2 class="text-center bg-info">About Us</h2>
            <div class="bg-white" CREATION:</br>
                <h4>

                    1. The Government of India vied Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally established the Bureau of Police Research and Development (BPR&D), under the Ministry of Home Affairs giving a new orientation to then existing Police Research
                    and Advisory Council (1966) for the following reasons and with the primary objective of modernization of police force:</br>

                    1. To take direct and active interest in the issues.</br>

                    2. To promote a speedy and systematic study of the police problems.</br>

                    3. To apply science and technology in the methods and techniques used by police.</br>

                    In addition and as a secondary, the Resolution mandated an advisory role also for the Bureau.</br>

                    2. The Bureau was established with the following two divisions initially with a well laid out charter of duties</br>

                    1. Research, Statistics and Publication.</br>

                    2. Development.</br>

                    3. Training is a vital and growing requirement to improve the competency of police forces in the country. The Gore-Committee (1971) set up by the Government of India studied the training aspects of police and gave several recommendations. The government
                    of India in accepting its recommendations created a Training Division (1973) in addition to the two divisions already existing to function under the Bureau.</br>

                    4. The forensic science services uncompromising & Geese under the Development Division grew over a period and a separate Directorate of Forensic Sciences under the BPR&D came into existence in 1983.</br>

                    5. Further in 1995 Government of India decided to entrust issues relating to Correctional Administration Work to the BPR&D so that problems relating to prisons and implementation of deemed prison reforms can be taken up by the Bureau in a cohesive manner.
                    This set up is operating out of the existing manpower resources.</br>

                    6. During the year 2008, the Government of India further decided to create National Police Mission under the administrative control of BPR&D to transform the police forces in the country into effective instrument for maintenance of internal security and
                    facing the challenges in future, by equipping them with the necessary material, intellectual and organizational resources.</br>

                </h4>
            </div>
            <marquee>Thank you for visiting our Website</marquee>
            <footer>The Webpage was developed by Venkatesh E</footer>
</body>
<style>
    marquee {
        font-size: 50px;
        background-color: rgb(0, 195, 255);
        color: rgb(255, 255, 255);
    }
    
    footer {
        font-size: 30px;
        text-align: center;
        background-color: rgb(0, 195, 255);
        color: rgb(255, 255, 255);
    }
</style>

</html>
~~~
### Contact Page:
~~~html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BPRD CONTACT PAGE</title>
    <link rel="icon" href="./img/logo.png" type="image/x-icon" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</head>

<body>
    <div class="container-fluid">
        <div class="row">
            <img src="https://bprd.nic.in/images/GY1.jpg" style="height:400px;" alt="police">

            <div class="col-sm-12 bg-info h1 text-center">Bureau of Police Research and Development</div>
            <div class="col-sm-12 bg-info h1 text-center">Ministry of Home affairs</div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/home.html">HOME</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/about.html">ABOUT US</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/gallery.html">GALLERY</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/training.html">TRAINING</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/admin.html">ADMIN</a></div>
            <div class="col-sm-2 h2  bg-white bg-gradient"><a href="/static/contactus.html">CONTACT US</a></div>
            <h2 class="text-center bg-info">Contact us</h2>
            <div class="h2 bg-white" style="height:800px;">
                Address:</br>

                Bureau of Police Research and Development</br>
                Ministry of Home Affairs,</br>
                NH-8, Mahipalpur</br>
                New Delhi (India)</br>
                ---------------------------------------------------------------------------------------------------------------------------------</br>

                Telefax:</br>
                DG Office: +91-11-26781312, Email id: dg@bprd.nic.in</br>
                ADG Office: +91-11-26781341, Email id: adg@bprd.nic.in</br>
                Administration Directorate: +91-11-26781326, Email id: igadm@bprd.nic.in</br>
                Training Directorate: +91-11-26782027, Email id: dirtrg@bprd.nic.in</br>
                NPM Directorate: +91-11-26781345, Email id: dirnpm@bprd.nic.in</br>
                MOD Directorate: +91-11-26782023, Email id: igmod@bprd.nic.in</br>
                Research & CA Directorate: +91-11-26781314, Email id: dirrd@bprd.nic.in</br>
                ---------------------------------------------------------------------------------------------------------------------------------</br>
                Phone:

                </br>
                Administration Directorate: +919987233434</br>
                Training Directorate: +8756347690</br>
                ---------------------------------------------------------------------------------------------------------------------------------</br>




            </div>
            <marquee>Thank you for visiting our Website</marquee>
            <footer>The Webpage was developed by Venkatesh E</footer>

</body>
<style>
    marquee {
        font-size: 50px;
        background-color: rgb(0, 195, 255);
        color: rgb(255, 255, 255);
    }
    
    footer {
        font-size: 30px;
        text-align: center;
        background-color: rgb(0, 195, 255);
        color: rgb(255, 255, 255);
    }
</style>

</html>
~~~
## OUTPUT:
### Home Page:
![home](home.jpg)
### About Page:
![aboutus](aboutus.jpg)
### Contact Page:
![contact](contactus.jpg)
## Result:
This above html coding design a website using bootstrap framework successfully.