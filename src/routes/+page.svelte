<script>
    import '../app.css';

    let open = false;

    // let btnClose = false

</script>

<header>
    <div class="topNav">
        <div class="logoNav">
            <img src="images/logo.svg" alt="">
        </div>
        <div class="sideRight">
            <a href="">HOW WE WORK</a>
            <a href="">BLOG</a>
            <a href="">ACCOUNT</a>
            <button class="btnHeader">VIEW PLANS</button>
        </div>
    </div>
    <div class="topMobile">
        <div class="logoMobile">
            <img style="max-width: 100%; display: block;" src="images/logo.svg" alt="">
        </div>
        <div class="navMobile">
            <img src="images/icon-hamburger.svg" alt="" on:click={() => open = !open}>
            {#if open}
            <div class="isOpen">
                <a class="sideOpen" href=""><p>how we work</p></a>
                <a class="sideOpen" href=""><p>blog</p></a>
                <a class="sideOpen" href=""><p>account</p></a>
                <div class="btnSide">
                    <a class="sideOpen" href=""><p>view plans</p></a>
                </div>
            
            </div>
            {/if}
            <!-- <img src="images/icon-close.svg" alt="" on:click={()=> open = !open}> -->
        </div>
    </div>
</header>
<section class="desktop">
    <div class="container">
        <div class="content">
            <div class="borderTop"></div>
            <h1 class="textTop">Humanizing your insurance.</h1>
            <p class="subTop">
                Get your life insurance coverage easier and faster. We blend our expertise 
                and technology to help you find the plan that’s right for you. Ensure you 
                and your loved ones are protected.
            </p>
            <button class="btnTop">VIEW PLANS</button>
        </div>
        <img class="imageTop" src="images/bg-pattern-intro-right-desktop.svg" alt="">
        <img class="imgPhoto" src="images/image-intro-desktop.jpg" alt="">
        <img class="imageBottom" src="images/bg-pattern-intro-left-desktop.svg" alt="">
    </div>
    <div class="midContainer">
        <div class="midContent">
            <div class="borderMid"></div>
            <h1 class="midHeader">We’re different</h1>
            <div class="midList">
                <div class="listContent">
                    <img src="images/icon-snappy-process.svg" alt="">
                    <h2>Snappy Process</h2>
                    <p>Our application process can be completed in minutes, not hours. Don’t get 
                        stuck filling in tedious forms.</p>
                </div>
                <div class="listContent">
                    <img src="images/icon-affordable-prices.svg" alt="">
                    <h2>Affordable Prices</h2>
                    <p>We don’t want you worrying about high monthly costs. Our prices may be low, 
                        but we still offer the best coverage possible.</p>
                </div>
                <div class="listContent">
                    <img src="images/icon-people-first.svg" alt="">
                    <h2>People First</h2>
                    <p>Our plans aren’t full of conditions and clauses to prevent payouts. We make 
                        sure you’re covered when you need it.</p>
                </div>
            </div>
            <div class="midBanner">
                <div class="textBanner">
                    <p>Find out more about how we work</p>
                </div>
                <div class="btnBanner">
                    <button>How We Work</button>
                </div>
            </div>
            
        </div>
    </div>
</section>

<section class="mobile">
    <img style="width: 100%; height: 100%;" src="images/image-intro-mobile.jpg" alt="">
    <div class="containerMobile">
        <div class="contentMobile">
            <h1 class="titleMobile">Humanizing your insurance.</h1>
            <p class="subMobile">Get your life insurance coverage easier and faster. We blend our expertise 
                and technology to help you find the plan that’s right for you. Ensure you 
                and your loved ones are protected.</p>
            <div class="btnMobile">
                <a href="">View Plans</a>
            </div>
            <img class="bgRight" src="images/bg-pattern-intro-right-mobile.svg" alt="">
        </div>
        <div class="midContentMobile">
            <div class="borderMobile"></div>
            <h1 class="titleMobile">We’re different.</h1>
            <div class="listMobile">
                <img src="images/icon-snappy-process.svg" alt="">
                <h1>Snappy Process</h1>
                <p>Our application process can be completed in minutes, not hours. Don’t get 
                    stuck filling in tedious forms.</p>
            </div>
            <div class="listMobile">
                <img src="images/icon-affordable-prices.svg" alt="">
                <h1>Affordable Prices</h1>
                <p>We don’t want you worrying about high monthly costs. Our prices may be low, 
                    but we still offer the best coverage possible.</p>
            </div>
            <div class="listMobile">
                <img src="images/icon-people-first.svg" alt="">
                <h1>People First</h1>
                <p>Our plans aren’t full of conditions and clauses to prevent payouts. We make 
                    sure you’re covered when you need it.</p>
            </div>
            <div class="bannerMobile">
                <h1>Find out more about how we work</h1>
                <button>how we work</button>
            </div>
        </div>
    </div>
    
</section>
<footer>
    <div class="footerBottom">
        <div class="footerContainer">
            <div class="footerTop">
                <div>
                    <img src="images/logo.svg" alt="">
                </div>
                <div class="socialMedia">
                    <a href="">
                        <img class="imgSosmed" src="images/icon-facebook.svg" alt="">
                    </a>
                    <a href="">
                        <img class="imgSosmed" src="images/icon-twitter.svg" alt="">
                    </a>
                    <a href="">
                        <img class="imgSosmed" src="images/icon-pinterest.svg" alt="">
                    </a>
                    <a href="">
                        <img class="imgSosmed" src="images/icon-instagram.svg" alt="">
                    </a>
                </div>
            </div>
            <div class="borderFooter"></div>
            <div class="footerList">
                <div>
                    <p class="titleFooter">Our Company</p>
                    <ul>
                        <li>
                            <a href="">how we work</a>
                        </li>
                        <li>
                            <a href="">why insure?</a>
                        </li>
                        <li>
                            <a href="">view plans</a>
                        </li>
                        <li>
                            <a href="">reviews</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <p class="titleFooter">help me</p>
                    <ul>
                        <li>
                            <a href="">faq</a>
                        </li>
                        <li>
                            <a href="">Terms of use</a>
                        </li>
                        <li>
                            <a href="">privacy of policy</a>
                        </li>
                        <li>
                            <a href="">cookies</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <p class="titleFooter">contact</p>
                    <ul>
                        <li>
                            <a href="">sales</a>
                        </li>
                        <li>
                            <a href="">support</a>
                        </li>
                        <li>
                            <a href="">live chat</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <p class="titleFooter">others</p>
                    <ul>
                        <li>
                            <a href="">careers</a>
                        </li>
                        <li>
                            <a href="">press</a>
                        </li>
                        <li>
                            <a href="">licenses</a>
                        </li>
                    </ul>
                </div>

            </div>
        </div>
    </div>
    <div class="footerMobile">
        <div class="footerTopMobile">
            <img src="images/logo.svg" alt="">
            <div class="sosmedMobile">
                <a href="">
                    <img class="imgSosmed" src="images/icon-facebook.svg" alt="">
                </a>
                <a href="">
                    <img class="imgSosmed" src="images/icon-twitter.svg" alt="">
                </a>
                <a href="">
                    <img class="imgSosmed" src="images/icon-pinterest.svg" alt="">
                </a>
                <a href="">
                    <img class="imgSosmed" src="images/icon-instagram.svg" alt="">
                </a>
            </div>
            <div class="borderMobileFooter"></div>
            <div class="aboutMobile">
                <div style="margin-bottom: 50px;">
                    <p class="titleFooter">Our Company</p>
                    <ul>
                        <li>
                            <a href="">how we work</a>
                        </li>
                        <li>
                            <a href="">why insure?</a>
                        </li>
                        <li>
                            <a href="">view plans</a>
                        </li>
                        <li>
                            <a href="">reviews</a>
                        </li>
                    </ul>
                </div>
                <div style="margin-bottom: 50px;">
                    <p class="titleFooter">help me</p>
                    <ul>
                        <li>
                            <a href="">faq</a>
                        </li>
                        <li>
                            <a href="">Terms of use</a>
                        </li>
                        <li>
                            <a href="">privacy of policy</a>
                        </li>
                        <li>
                            <a href="">cookies</a>
                        </li>
                    </ul>
                </div>
                <div style="margin-bottom: 50px;">
                    <p class="titleFooter">contact</p>
                    <ul>
                        <li>
                            <a href="">sales</a>
                        </li>
                        <li>
                            <a href="">support</a>
                        </li>
                        <li>
                            <a href="">live chat</a>
                        </li>
                    </ul>
                </div>
                <div style="margin-bottom: 50px;">
                    <p class="titleFooter">others</p>
                    <ul>
                        <li>
                            <a href="">careers</a>
                        </li>
                        <li>
                            <a href="">press</a>
                        </li>
                        <li>
                            <a href="">licenses</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</footer>

<style>
    .topNav {
        width: 100%;
        height: 60px;
        background-color: white;
        display: flex;
        justify-content: space-between;
        padding: 20px 50px;
    }

    .topMobile, .mobile, .footerMobile {
        display: none;
    }
    
    .logoNav {
        padding: 0px 100px;
    }

    .sideRight {
        padding: 0px 100px;
        display: flex;
        align-items: center;
        gap: 30px;
    }

    .sideRight a{
        text-decoration: none;
        color: var(--darkgrayishviolet);
        font-weight: bold;
    }

    .sideRight a:hover{
        color: black;
    }

    .btnHeader {
        border: 2px solid black;
        background-color: white;
        color: var(--darkgrayishviolet);
        font-weight: bold;
        width: 130px;
        height: 35px;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
    }

    .btnHeader:hover{
        background-color: black;
        color: var(--darkgrayishviolet);

    }

    .container{
        background-color: var(--darkviolet);
        padding: 50px;
        position: relative;
        display: flex;
        height: 550px;
    }

    .content {
        width: 50%;
        margin: 0px 100px;
        color: white;
    }

    .borderTop {
        border-top: 2px solid white;
        width: 150px;
        margin-top: 50px;
    }

    .textTop {
        font-size: 65px;
        padding: 50px 200px 0px 0px;
        line-height: 3.5rem;
    }

    .subTop {
        width: 100%;
        margin-top: 30px;
        line-height: 1.5rem;
        padding: 0px 150px 30px 0px;
    }

    .btnTop {
        border: 1px solid white;
        width: 150px;
        padding: 10px;
        background-color: var(--darkviolet);
        color: white;
    }

    .btnTop:hover {
        cursor: pointer;
        background-color: white;
        color: var(--darkviolet);
        font-weight: bold;
    }

    .imageTop {
        position: absolute;
        top: 0;
        right: 0px;
        width: 25%;
        z-index: 1;
    }

    .imageBottom {
        position: absolute;
        bottom: -300px;
        left: 0;
        z-index: 1;
        width: 12%;
    }

    .imgPhoto {
        position: absolute;
        top: 100px;
        right: 200px;
    }
    .midContainer {
        background-color: white;
        padding: 50px;
    }

    .midContent {
        width: 100%;
        padding: 0px 100px;
    }

    .borderMid {
        border-top: 2px solid var(--darkviolet);
        width: 150px;
        margin-top: 220px;
    }

    .midHeader{
        font-size: 70px;
        font-family: 'DM Serif Display', serif;
        font-weight: 400;
        margin-top: 20px;
    }

    .midList {
        width: 100%;
        display: flex;
        justify-content: space-between;
        padding: 50px 0px;
    }

    .listContent {
        padding: 50px 0px;
    }

    .listContent h2{
        margin-top: 20px;
    }

    .listContent p {
        margin-top: 20px;
        padding-right: 50px;
        line-height: 1.5rem;
        color: var(--grayishblue);
    }

    .midBanner {
        width: 100%;
        height: 250px;
        background-color: var(--darkviolet);
        padding: 50px;
        color: white;
        display: flex;
        background-image: url(images/bg-pattern-how-we-work-desktop.svg);
        background-repeat: no-repeat;
        background-position: right;
    }

    .textBanner {
        width: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .textBanner p {
        width: 100%;
        font-size: 50px;
        padding: 0px 50px;
        font-weight: 700;
    }

    .btnBanner {
        width: 50%;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        padding-right: 30px;
    }

    .btnBanner button {
        color: white;
        border: 1px solid white;
        background-color: transparent;
        padding: 10px;
        width: 150px;
        font-weight: 700;
        letter-spacing: 1px;
    }

    .btnBanner button:hover {
        background-color: white;
        color: var(--darkgrayishviolet);
        cursor: pointer;
    }

    .footerBottom{
        background-color: var(--lightgray);
        width: 100%;
        padding: 50px;
        background-image: url(images/bg-pattern-footer-desktop.svg);
        background-repeat: no-repeat;
    }

    .footerContainer{
        width: 100%;
        padding: 20px 100px;
    }

    .footerTop {
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .socialMedia {
        width: 50%;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        gap: 20px;
    }

    .imgSosmed:hover{
       filter: grayscale(100%) brightness(10%) contrast(100%);
    }

    .borderFooter {
        width: 100%;
        border-top: 1px solid hsl(273, 4%, 51%);
        margin: 20px 0px;
    }

    .footerList {
        width: 80%;
        display: flex;
        justify-content: space-between;
        margin-top: 20px;
    }

    .titleFooter {
        font-weight: 700;
        color: var(--darkgrayishviolet);
        font-family: 'Karla', sans-serif;
        text-transform: uppercase;
        margin: 30px 0px;
    }

    ul li {
        list-style: none;
        margin-top: 10px;
    }
    
    li a {
        color: black;
        font-family: 'DM Serif Display', serif;
        font-weight: 400;
        text-transform: uppercase;
    }

    li a:hover{
        text-decoration: underline;
    }

    @media only screen and (max-width: 768px) {
        .desktop, .footerBottom, .topNav {
            display: none;
        }

        .mobile {
            width: 100%;
            display: flex;
            flex-direction: column;
        }

        .topMobile {
            background-color: white;
            width: 100%;
            height: 100px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            position: relative;
        }

        .logoMobile {
            width: 50%;
        }

        .navMobile {
            
            width: 50%;
            display: flex;
            justify-content: flex-end;
            cursor: pointer;
        }

        .containerMobile {
            width: 100%;
            height: 100%;
            padding-bottom: 100px;

        }

        .contentMobile {
            color: white;
            width: 100%;
            height: 100%;
            padding: 100px 20px;
            background-color: var(--darkviolet);
            background-image: url(images/bg-pattern-intro-left-mobile.svg);
            background-repeat: no-repeat;
            background-position: top left;
            position: relative;
        }

        .titleMobile {
            width: 100%;
            font-size: 45px;
            text-align: center;
            font-weight: 700;
            font-family: 'DM Serif Display', serif;
        }

        .subMobile {
            width: 100%;
            text-align: center;
            margin-top: 20px;
            line-height: 1.5rem;
        }

        .btnMobile {
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px;
        }

        .btnMobile a {
            width: 150px;
            border: 1px solid white;
            color: white;
            text-transform: uppercase;
            padding: 10px;
            display: flex;
            justify-content: center;
        }

        .bgRight {
            position: absolute;
            right: 0;
            bottom: -180px;
        }

        .midContentMobile {
            width: 100%;
            background-color: white;
            padding: 20px;
            text-align: center;
        }

        .borderMobile {
            display: inline-block;
            width: 50%;
            border-top: 1px solid var(--darkviolet);
            margin-top: 100px;
            margin-bottom: 40px;
        }

        .listMobile {
            padding: 50px 0px;
            width: 100%;
        }

        .listMobile h1 {
            margin: 20px 0px;
            font-size: 30px;
        }

        .listMobile p {
            line-height: 1.5rem;
            color: var(--darkgrayishviolet);
        }

        .bannerMobile {
            width: 100%;
            height: 300px;
            background-color: var(--darkviolet);
            background-image: url(images/bg-pattern-how-we-work-mobile.svg);
            background-repeat: no-repeat;
            background-position: right top;
            background-size: contain;
            padding: 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .bannerMobile h1 {
            font-size: 35px;
            color: white;
            font-family: 'DM Serif Display', serif;
            font-weight: 400;
        }

        .bannerMobile button {
            background-color: transparent;
            border: 1px solid white;
            padding: 10px;
            width: 150px;
            color: white;
            text-transform: uppercase;
            margin-top: 20px;
            font-family: 'Karla', sans-serif;
        }

        .footerMobile {
            display: flex;
            flex-direction: column;
            text-align: center;
            width: 100%;
            background-color: var(--lightgray);
            padding: 50px 20px;
            background-image: url(images/bg-pattern-footer-mobile.svg);
            background-repeat: no-repeat;
            background-position: top;
        }

        .footerTopMobile {
            padding-top: 50px;
            width: 100%;
        }

        .sosmedMobile {
            width: 100%;
            margin: 30px 0px;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
        }

        .borderMobileFooter {
            width: 100%;
            border-top: 1px solid var(--darkgrayishviolet);
        }

        .aboutMobile {
            padding: 40px 0px;
            width: 100%;
        }

        .isOpen {
            position: absolute;
            top: 100px;
            right: 0;
            background-color: var(--grayishblue);
            width: 100vw;
            height: fit-content;
            padding: 30px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            z-index: 2;
        }

        .sideOpen{
            color: white;
            font-size: 24px;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin: 10px 0px;
            text-decoration: none;
        }

        .sideOpen:hover {
            color: black;
        }

        .btnSide {
            color: white;
            width: 100%;
            border: 1px solid white;
            padding: 10px;
        }
        .btnSide:hover {
            border: 1px solid black;
        }
    }
</style>