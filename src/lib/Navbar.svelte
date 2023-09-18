<script>

</script>

    <header>
        <input type="checkbox" name="" id="chk1">
        <div class="logo"><h1>Web Master</h1></div>
        <div class="search-box">
            <form action="">
                <input type="text" name="search" id="srch" placeholder="Search">
                <button type="submit"><i class="fa fa-search"></i></button>
            </form>
        </div>
        <ul>
            <li><a href="/pagina">Home</a></li>
            <li><a href="/pagina">Product</a></li>
            <li><a href="/pagina">Blog</a></li>
            <li><a href="/pagina">Contact</a></li>
            <li>
                <a href="/pagina"><i class="fab fa-facebook"></i></a>
                <a href="/pagina"><i class="fab fa-twitter"></i></a>
                <a href="/pagina"><i class="fab fa-instagram"></i></a>
            </li>
        </ul>
        <div class="menu">
            <label for="chk1">
                <i class="fa fa-bars"></i>
            </label>
        </div>
    </header>



<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />


<style>
    
    header {
        width: 100%;
        height: 100px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        position: fixed;
        z-index: 99;
        box-shadow: 0 0 10px #000;
        background: rgba(0,0,0,0.5);
    }

    #chk1{
        display: none;
    }

    i{
        color: #fff;
        cursor: pointer;
    }

    .logo{
        flex: 1;
        color: #fff;
        margin-left: 50px;
        text-transform: uppercase;
    }

    .search-box{
        flex: 1;
        position: relative;
    }

    .search-box input{
        width: 100%;
        height: 40px;
        border: none;
        outline: none;
        background: #f2f2f2;
        border-radius: 30px;
        color: gray;
        font-size: 16px;
        text-align: center;
        
    }

    .search-box button{
        cursor: pointer;
        width: 40px;
        height: 40px;
        border-radius: 30px;
        border: none;
        position: absolute;
        top: 0;
        right: 0;
        transform: scale(0.9);
        background: green;
    }

    header ul{
        flex: 2;
        display: flex;
        justify-content: space-evenly;

    }

    header ul li{
        list-style: none;
    }

    header ul li a{
        text-decoration: none;
        color: #fff;
        font-weight: 600;
        text-transform: uppercase;
        padding: 10px 15px;
    }

    header ul li a:hover{
        border-bottom: 2px solid cadetblue;
    }

    header .menu{
        font-size: 2.5rem;
        display: none;
    }
    

</style>