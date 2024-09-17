<script>
export default{
    data(){
        return{
            
        }
    }
}
</script>

<template>
    <footer>

        <section class="top-footer">
            <div class="container">
                <div class="link-footer">
                    <ul>
                        <li><a href="#"><h3>DC COMICS</h3></a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                        <li><a href="#"><h3>SHOP</h3></a></li>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>    
                    </ul>    
                    <ul>
                        <li><a href="#"><h3>DC</h3></a></li>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy(New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                    <ul>
                        <li><a href="#"><h3>SITES</h3></a></li>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>    
                        
                </div>

                <img src="../assets/img/dc-logo-bg.png" alt="logo-bg">
            </div>
        </section>

        <section class="bottom-footer">
            <div class="container">
                <a href="">SIGN-UP NOW!</a>

                <div class="social">
                    <ul>
                        <li><p>FOLLOW US</p></li>
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </section>

    </footer>
</template>

<style scoped>
.top-footer{
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    max-height: 400px;
    
}
.link-footer{
    display: flex;
    
}
.link-footer h3{
    color: #fff;
}
.link-footer a{
    color: lightgrey;
    font-size: 12px;
}
.link-footer li{
    margin-bottom: 8px;
}
.link-footer li h3{
    margin: 15px 0;
    font-size: 20px;
}
.link-footer ul{
    margin-right: 20px;
}
.top-footer > div{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.top-footer div img{
    height: 400px;
}
.bottom-footer{
    background-color: #303030;
    height: 100px;
}
.bottom-footer > div{
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.social ul{
    display: flex;
    align-items: center;
    gap: 20px;
}
.social ul p{
    color: dodgerblue;
    font-size: 20px;
    font-weight: bold;
}
.bottom-footer div > a{
    color: #fff;
    border: 1px solid dodgerblue;
    padding: 15px 15px;
}
</style>