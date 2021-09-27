<template>
    <div id="footer-section">
        <div id="container-elements-margin">
            <div id="container-lists-footer">
                
                
                <ul>

                    <li>
                        <h2>DC COMICS</h2>
                    </li>
                    <li>
                        <a href="">Characters</a>
                    </li>
                    <li>
                        <a href="">Comics</a>
                    </li>
                    <li>
                        <a href="">Movies</a>
                    </li>
                    <li>
                        <a href="">TV</a>
                    </li>
                    <li>
                        <a href="">Games</a>
                    </li>
                    <li>
                        <a href="">Videos</a>
                    </li>
                    <li>
                        <a href="">News</a>
                    </li>

                 
                    <li>
                        <h2>SHOP</h2>
                    </li>
                    <li>
                        <a href="">Shop DC</a>
                    </li>
                    <li>
                        <a href="">Shop DC Collectibles</a>
                    </li>

                </ul>

                <ul>
                    
                    <li>
                        <h2>DC SITES</h2>
                    </li>
                    <li>
                        <a href="">Terms Of Use</a>
                    </li>
                    <li>
                        <a href="">Privacy Policy(New)</a>
                    </li>
                    <li>
                        <a href="">Ad Choices</a>
                    </li>
                    <li>
                        <a href="">Advertising</a>
                    </li>
                    <li>
                        <a href="">Jobs</a>
                    </li>
                    <li>
                        <a href="">Subscriptions</a>
                    </li>
                    <li>
                        <a href="">Talent Workshops</a>
                    </li>
                    <li>
                        <a href="">CPSC Certificates</a>
                    </li>
                    <li>
                        <a href="">Ratings</a>
                    </li>
                    <li>
                        <a href="">Shop Help</a>
                    </li>
                    <li>
                        <a href="">Contact Us</a>
                    </li>

                </ul>

                <ul>

                    <li>
                        <h2>SITES</h2>
                    </li>
                    <li>
                        <a href="">DC</a>
                    </li>
                    <li>
                        <a href="">MAD Magazine</a>
                    </li>
                    <li>
                        <a href="">DC Kids</a>
                    </li>
                    <li>
                        <a href="">DC Universe</a>
                    </li>
                    <li>
                        <a href="">DC Power Visa</a>
                    </li>

                </ul>

                <div id="container-img-footer">
                    <img src="../assets/images/dc-logo-bg.png" alt="">
                </div>

            </div>

        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

//MARGIN E RESET
*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}

#container-elements-margin{
    margin:auto;
    width:90%;
}
//FINE MARGIN E RESET

#footer-section{
    background-image: url(../assets/images/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;

    // padding-top:100px;
    // padding-bottom:150px;
}

h2{
    color:white;
    margin:0;
    padding:10px 0;
}

img{
    height: 100%;
    width:100%;
}
#container-lists-footer{
    display: flex;
 }

 ul{
     padding:50px 50px;
    li{
        list-style-type: none;
        padding:5px 0;
    }
    a{
        color:rgb(179, 172, 172);
        text-decoration: none;
    }
 }

</style>