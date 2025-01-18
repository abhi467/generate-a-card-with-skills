# generate-a-card-with-skills
<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>card</title>
    <link rel="stylesheet" href="./card.css">
</head>

<body>
    <main class="main-container">
        <!-- profile image -->
        <section class="profile-container">
            <img src="D:\abhishek passport photo.jpg" alt="abhishekpassport">
        </section>
        <!-- profile info -->
        <section class="text-container">
            <h3>ABHISHEK RANJAN</h3>
            <!-- location section -->
            <section class="location">
                <h4>🤖 INDIA</h4>
                <p class="head-line">UI/UX designer and frontend developer</p>
                <button>Message</button>
                <button>Follow</button>
            </section>
            <!-- Skill section -->
            <section>
                <h3 class="skill-heading">Skills</h3>
                <ul>
                    <li>UI/UX</li>
                    <li>FRONT END DEVELOPER </li>
                    <li> HTML</li>
                </ul>
                <ul>
                    <li>CSS</li>
                    <li>JAVASCRIPT</li>
                    <li>REACT</li>
                    <li>BOOTSTRAP</li>
                </ul>
            </section>
        </section>
    </main>


</body></html>



# css code:-

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body,
html {
    font-family: sans-serif;
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    background-color: blueviolet;
    text-align: center;
}

.main-container {
    background-color: rgb(36, 36, 114);
    border-radius: 10px;
}

.profile-container {
    background-color: white;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    height: 200px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

}

img {
    padding: 6px;
    height: 150px;
    width: 150px;
    border: 5px solid rgb(36, 36, 114);
    border-radius: 50%;
}

.text-container {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    gap: 20px;
    padding: 30px;
    font-size: 16px;
}

.head-line {
    font-size: 14px;
    margin: 10px 0;
}

.location {
    border-bottom: 2px solid rgb(43, 29, 65);
    padding-bottom: 10px;
}
button {
    background-color: rgb(54, 54, 94);
    color: #fff;
    padding: 10px 10px;
    border-radius: 5px;
    margin-right: 5px;
}



.skill-heading {
    text-align: left;
    margin-bottom: 10px;
}

ul {
    display: flex;
    gap: 20px;
    list-style: none;
    font-size: 12px;
    margin-bottom: 15px;
}
