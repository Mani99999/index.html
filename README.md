<!-- Html-->
<html>

<head>
    <title> Lets Upgrade </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link href="style.css" rel="stylesheet">
</head>

<body>
    <div id="container">


        <div id="nav">
            <img id="logo" src="https://lucdn.letsupgrade.net/small_logo_new_0cd08c57ce.png" alt="LOGO">
            <div id="nav_elements">
                <div id="link_container">
                    <p class="links">Programs</p>
                    <p class="links">Community</p>
                </div>
                <button class="button black_bg">Sign In</button>
                <button class="button">Sign Up</button>
            </div>


        </div>


        <div id="hero">
            <div id="top_hero">
                <p id="banner"> Live Community Members 🤩 </p>
                
                <div id="top_numbers">
                    <span>7</span>
                    <span>3</span>
                    <span>5</span>
                    <span>8</span>
                    <span>5</span>
                    <span>9</span>
                </div>
            </div>
            <div id="main_hero">
                <h1 id="title">
                    We make Future Developers 🚀
                </h1>
                <h4>
                    Join 7,35,859+ LetsUpgrader's and become a Pro Developer 🔥
                </h4>
            </div>
            <button id="hero_button" class="button black_bg">Start Learning</button>
        </div>
    </div>
</body>

</html>

<!-- Css-->
* {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: 'Roboto';
}


#container {
    height: 100vh;
}


#nav {
    height: 10vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin-inline: auto;
}

#nav_elements {
    display: flex;
}

#logo {
    height: 7vh;
}

.links {
    margin-right: 10px;
    font-size: 16px;
    cursor: pointer;
}

.links:hover {
    color: rgb(255, 102, 0)
}

#link_container {
    display: flex;
    align-items: center;
}

.button {
    margin-left: 10px;
    font-size: 16px;
    border: 1px solid black;
    border-radius: 100px;
    padding: 10px 20px;
    cursor: pointer;
}

.button:hover {
    background-color: black;
    color: white;
}

.black_bg {
    background-color: black;
    color: white;
}

#hero {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;

    padding-bottom: 60px;
    align-items: center;
    height: 100%;
    text-align: center;
}

#title {
    width: 700px;
    font-size: 90px;
    text-align: center;
}

h4 {
    margin-top: 20px;
}

#hero_button {
    font-size: 25px;
    padding: 20px 30px;
}

#banner {
    font-size: 20px;
    font-weight: 400;
    letter-spacing: 1px;
    color: rgb(0, 0, 0, 0.8);
    animation: flash 1s infinite;
}

@keyframes flash {
    0% {
        opacity: 0;
    }

    50% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}

span {
    background-color: black;
    color: white;
    padding: 13px 17px;
    border-radius: 10px;
    font-weight: bold;
    margin-inline: 2px;
}

#top_numbers {
    margin-top: 15px;
    animation: bounce 1s infinite;

}

@keyframes bounce {
    0% {
        transform: translateY(0px);
    }

    50% {
        transform: translateY(10px);
    }

    100% {
        transform: translateY(0px);
    }
}
