<script>
    import { address } from "../store";


</script>
<style>
     @media screen and (max-width: 768px) {
            #logo p {
                display: none !important;
            }
            
        }
        @media screen and (max-width: 480px) {
       
        }
        img{
            height: 3rem;
        }
        #logo{
            display: flex
;
    gap: 1rem;
    text-decoration: none;
    align-items: center;
        }

        #logo p{
            color:#585858;
            font-weight:bold;
            font-size: 1.3rem;
            display: block;
        }
        #navlinks{
            display: flex
;
    gap: 3vw;

        }
        #navlinks a{
            height: 2.5rem;
    padding-inline: 1.5rem;
    border-radius: 0.5rem;
    transition: 0.2s;
    font-size: 1rem;
    color: white;
    display: flex
;
    align-items: center;
    text-decoration: none;
    font-weight: bold;
        }
        #navlinks a:hover{
            scale:1.05;
            opacity: 0.9;

        }
        nav{
            background-color: #ffffff;
    display: flex
;
    justify-content: space-between;
    padding-inline: 1rem;
    height:4rem;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 3;
    box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 50px;
        }

</style>

<nav>
  
    <a href={`${address}/`} id = 'logo'>
        <img src = 'images/logo.png'>
        <p>Trường THPT Nguyễn Trân</p>
    </a>

<div id="navlinks">
    <a href={`${address}/media`} style="background-color:#5CE1E6">NTS Media</a>
    <a href={`${address}/sbcrew`} style="background-color:#9996E7">S&B Crew</a>
    <a href={`${address}/femb`} style="background-color:#FDB5D7">FEMB</a>
    

</div>
</nav>