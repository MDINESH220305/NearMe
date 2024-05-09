# Ex04 Places Around Me
## Date:09/05/2024

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
```C
ex4.html
<HTML>
    <HEAD>
        <TITLE>My City</TITLE>
    </HEAD>
    <BODY>
        <h1 align="center">
            <font color="ligthred"><b>Redhills</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Dinesh.M(212222043002)</b></font>
        </h3>
        <CENTER>
            <img src="C:\Users\Rajkiran\Pictures\Screenshots\background.png" usemap="#mymap" height="500" width="1000">
            <map name="mymap">
                <area title="Kapaleeswarar Temple" href="temple.html" coords="652,320,880,398" shape="rect">
                <area title="Pulhal Lake" href="lake.html" coords="452,600,208" shape="circle">
                <area title="Galaxy Mall" href="mall.html" coords="819,400,981,881" shape="rect">
                <area title="Revathistores" href="Revathistores.html" coords="705,315,935,337,710,414,637,317" shape="poly">
            </map>

        </CENTER>
    </BODY>
</HTML>
lake.html
<HTML>
    <HEAD>
        <TITLE>Pulhal Lake</TITLE>
    </HEAD>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="red">Redhills</font>
        </h1>
        
        <h3 align="center">
            <font color="cyan">Pulhal Lake</font>
        </h3>
        <hr color="red" align="center">
        <br>
        <p><h4>
            Pulhal Lake, or Pulhal aeri, sometimes spelled Puzhal lake and also known as the Red Hills Lake, is located in Red Hills, Chennai, India. It lies in Thiruvallur district of Tamil Nadu state. It is one of the two rain-fed reservoirs that supply water to Chennai City, the other one being the Chembarambakkam Lake and Porur Lake.
            The Pulhal reservoir was built in 1876 during the British rule in Pulhal, Chennai (named Madras at the time). The reservoir was originally a small tank with a capacity of 500 million cubic feet (mcft) and two masonry weirs, built using locally available laterite stones, then functioned as surplus weirs to release excess water from the water body. Today, these masonry weirs are water-retaining structures as they have been replaced by two shutters. In 1997, the storage capacity of the water reservoir was increased to 3,300 mcft and the depth to 21.20 ft to cater to the drinking water needs of Chennai and also to store Penna river water received from Andhra Pradesh through Poondi Reservoir and the Sholavaram Tank.
        </h4></p>
    </body>
</HTML>
mall.html
<HTML>
    <HEAD>
        <TITLE>Galaxy Mall</TITLE>
    </HEAD>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="red">Redhills</font>
        </h1>
        
        <h3 align="center">
            <font color="cyan">Galaxy Mall</font>
        </h3>
        <hr color="red" align="center">
        <br>
        <p><h4>
            Chennai the movie capital of South India with its large consumption of movie content & it very own film industry is a market in want of more screens for its consumers. The Galaxy Mall itself is located in the densely populated Red Hills town zone. The multiplex on the topmost level of the mall culminates the vertical circulation into its pre-function space. The design begins by creating an arrival experience with media walls playing movie trailers & the main entrance with a canopy announcing the cinemas.

The interior concept has been inspired with the classical dance form of bharat natyam. The ceiling designs with its pleat fold formation like the saree & cove lights in mudra position create a context relevant to the regional outpost. A series of design motifs were evolved to flow into the counter fascia, doors & take cues in the chandelier. The design challenge was always to create an interest in purity of spaces with robust finishes which are simple in detail while it continues to have its own signature style.
        </h4></p>
    </body>
</HTML>
Revathistores.html
<HTML>
    <HEAD>
        <TITLE>Revathistores</TITLE>
    </HEAD>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="red">Redhills</font>
        </h1>
        
        <h3 align="center">
            <font color="cyan">Revathistores</font>
        </h3>
        <hr color="red" align="center">
        <br>
        <p><h4>
            Revathi Stores was founded by Mr. S.N. Thyagarajan. Since 1962, Revathi Stores has been trusted with all your home needs. The success of Revathi Stores is based mainly on their Principle of low pricing and outstanding quality.

            Revathi Stores has a total 3 Branches located in Chennai’s prime locations:
            
            Revathi Stores - Red Hills (NEW STORE)
            Revathi Stores is a brand new store with and enormous space of 1 lakh+ sq. ft. Revathi stores gratifies all your needs under one roof. From electronics to textiles to groceries to home appliances, Revathi Stores has it all!
        </h4></p>
    </body>
</HTML>
temple.html
```


## OUTPUT
![Screenshot (58)](https://github.com/MDINESH220305/NearMe/assets/162429215/2ca8089d-369e-400a-a0ff-afe0bad69edd)
![Screenshot (59)](https://github.com/MDINESH220305/NearMe/assets/162429215/04413ff8-cfa3-4ee3-9847-670da358c78b)
![Screenshot (60)](https://github.com/MDINESH220305/NearMe/assets/162429215/01d8a3a1-4ed5-4046-9cf8-2d05f8107de1)
![Screenshot (61)](https://github.com/MDINESH220305/NearMe/assets/162429215/4299ad37-6281-40fd-8826-8676a3aee31a)
![Screenshot (62)](https://github.com/MDINESH220305/NearMe/assets/162429215/9d29e7a1-eeda-437e-a510-ea7ad4df70a3)













## RESULT
The program for implementing image maps using HTML is executed successfully.
