<script>
    
</script>

<center>
    <div id="main_show">
        
        <div id="opts">
            <a href="#contact_div" class="opts_link">
                <p>Get in touch</p>
            </a>
            
            <a href="#about_div" class="opts_link">
                <p>About me</p>
            </a>
            
            <a href="#home_div" class="opts_link">
                <p>Hello</p>
            </a>
        </div>
        
        <div id="center_stuffs">
            <div id="home_div">
                <h3 id="sub_txt">
                    Hey, You've reached Manash...
                </h3>
            
                <h1 id="hello">
                    HELLO WORLD!
                </h1>
            </div>
    
            <div id="about_div">
                <h1 id="about">
                    About Me
                </h1>
            </div>
        
            <div id="contact_div">
                <h1 id="get">
                    Get In Touch
                </h1>
            </div>
        </div>
    </div>


    <div id="connect_ico">
        <p id="reach_me">
            Reach me:   
        </p>

        <a href="mailto: manash.81142615@gmail.com" target="_blank" class="links">
            <img src="/link_icons/email.png" alt="eml" class="link_img">
        </a>

        <a href="https://www.linkedin.com/in/manash-prajapati/" target="_blank" rel="noreferrer" class="links">
            <img src="/link_icons/linkedin.png" alt="lin" class="link_img">
        </a>

        <a href="https://github.com/Manash-sth" target="_blank" rel="noreferrer" class="links">
            <img src="/link_icons/github.png" alt="git" class="link_img">
        </a>
    </div>



</center>

<style>
    h3, h1, p {
        color: aliceblue;
        font-family: 'sono';
        font-weight: 300;
    }

    h1 {
        font-size: 8rem;
    }

    #connect_ico {
        display: flex;
        align-items: center;
        justify-content: space-between;
        bottom: 0;
        position: fixed;
        margin-left: 1rem;
        margin-bottom: 1rem;
    }

    .links {
        margin-left: 1rem;
    }
    
    .link_img {
        width: 2rem;
        height: 2rem;   
    }

    #opts {
        display: flex;
        position: fixed;
        left: 15rem;

    }

    .opts_link {
        margin-right: 2rem;
        text-decoration: none;
        margin: 20px;

    }

    #home_div {
        height: 100vh;
    }

    #about_div {
        height: 100vh;
    }

    #contact_div {
        height: 100vh;
    }

    #center_stuffs {
        display: flex;
        flex-direction: column;
    }

    #main_show {
        display: flex;
        flex-direction: column;
    }
    
    @media only screen and (max-width: 1400px) {
        #opts {
            left: 10rem;
        }

        h1 {
            font-size: 6rem;
        }
    }

    @media only screen and (min-width: 1000px) {
        #opts {
            top: 30rem;
            transform: rotate(270deg);
            transform-origin: left bottom 0;
        }
    }

    @media only screen and (max-width: 1000px){
        #center_stuffs {
            margin-top: 10rem;
        }

        #opts {
            left: 0;
            top: 0;
            width: 100%;
            background-color: black;
            justify-content: center;

        }
    }

    @media only screen and (max-width: 800px) {
        /* #opts {
        } */

        h1 {
            font-size: 3rem;
        }
    }


</style>