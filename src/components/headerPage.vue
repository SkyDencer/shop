<script setup>
    
</script>
<template>
    <Header>
        <div class="head">
            <div class="container">
                <div class="title">
                    <span id="title" title="فانتزی شاپ | ارزانترین  سریعترین">  Fantasy Shop </span>
                    <RouterLink to="/"> <img class="icon" src="../assets/logo.svg" alt="" srcset=""></RouterLink>
                </div>
                <div class="search">
                    <div class="daste-bandi">
                        <form action="AboutView.vue" role="search" method="get">
                            <select name="daste-bandi" id="daste-bandi">
                                <option value="0">دسته بندی</option>
                                <option value="games">بازی ها</option>
                                <option value="consoles">کنسول بازی</option>
                                <option value="giftcarts">گیتف کارت</option>
                                <option value="accessories">لوازم جانبی</option>
                                <option value="digital-game">نصب بازی</option>
                            </select>
                            <input type="text" autocomplete="off" placeholder="جستجو در محصولات ..." aria-label="جستجو" class="search-bar" >
                            <button type="submit" aria-label="جستجو" class="btn-search" title="جستجو...">
                                <svg xmlns="http://www.w3.org/2000/svg" height="16" width="16" viewBox="0 0 512 512"><path d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z"></path></svg>
                                <i class="btn-i-search" aria-hidden="true"></i>
                            </button>
                        </form>
                    </div>
                </div>
                <div class="rocket" >
                
                    <button class="Slogan" title="ورود یا ثبت نام "><RouterLink to="/">
                    <svg class="eh-modal-button-icon" xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" viewBox="0 0 16 16"><path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path></svg>
                    <span class="Slogan1"> ورود یا عضویت</span> </RouterLink>
                </button>
           
                </div>
            </div>
        </div>
            <div class="bar1">
                        <div class="menubar">
                <ul class="menu">
                    <li class="menuselect">
                        <RouterLink to="/main">خانه</RouterLink>
                    </li>
                    <li class="menuselect">
                        <RouterLink to="#">کنسول بازی</RouterLink>
                        <ul class="menu-item">
                            <li><RouterLink class="p2" to="#">پلی استیشن</RouterLink></li>
                            <li><RouterLink class="p2" to="#">ایکس باکس</RouterLink></li>
                            <li><RouterLink class="p2" to="#">نینتدو سویج</RouterLink></li>
                            <li><RouterLink class="p2" to="#">pc</RouterLink></li>
                        </ul>
                    </li>
                    <li class="menuselect">
                        <RouterLink to="#"> <svg xmlns="http://www.w3.org/2000/svg" height="16" width="18" viewBox="0 0 576 512"><path d="M192 64C86 64 0 150 0 256S86 448 192 448H448c106 0 192-86 192-192s-86-192-192-192H192zM496 168a40 40 0 1 1 0 80 40 40 0 1 1 0-80zM392 304a40 40 0 1 1 80 0 40 40 0 1 1 -80 0zM168 200c0-13.3 10.7-24 24-24s24 10.7 24 24v32h32c13.3 0 24 10.7 24 24s-10.7 24-24 24H216v32c0 13.3-10.7 24-24 24s-24-10.7-24-24V280H136c-13.3 0-24-10.7-24-24s10.7-24 24-24h32V200z"></path></svg>بازی ها</RouterLink>
                            <ul class="menu-item">
                                <li><RouterLink class="p2" to="#">بازی های PS5</RouterLink></li>
                                <li><RouterLink class="p2" to="#">بازی های PS4</RouterLink></li>
                                <li><RouterLink class="p2" to="#">بازی های استفاده شده PS4</RouterLink></li>
                                <li><RouterLink class="p2" to="#">بازیهای Playstation VR</RouterLink></li>
                                <li><RouterLink class="p2" to="#">بازی های ایکس باکس(وان/سری اس / سری ایکس)</RouterLink></li>
                                <li><RouterLink class="p2" to="#">بازیهای nintendo switch</RouterLink></li>
                                <li><RouterLink class="p2" to="#">اکانت قانونی</RouterLink></li>
                                <li><RouterLink class="p2" to="#">نصب بازی</RouterLink></li>
                            </ul>
                    </li>
                    <li class="menuselect">
                        <RouterLink to="#"> گیفت کارت </RouterLink>
                        <ul class="menu-item">
                            <li><RouterLink class="p2" to="#">گیفت کارت پلی استیشن</RouterLink></li>
                            <li><RouterLink class="p2" to="#">گیفت کارت ایکس باکس</RouterLink></li>
                            <li><RouterLink class="p2" to="#">گیفت کارت Nintendo Switch</RouterLink></li>
                        </ul>
                    </li>
                    <li class="menuselect">
                        <RouterLink to="#">نصب بازی</RouterLink>
                        <ul class="menu-item">
                            <li><RouterLink class="p2" to="#">نصب بازی رو پلی استیشن</RouterLink></li>
                            <li><RouterLink class="p2" to="#">نصب بازی روی ایکس باکس</RouterLink></li>
                        </ul>
                    </li>
                    <li class="menuselect">
                        <RouterLink to="#">آموزش ها</RouterLink>
                        <ul class="menu-item">
                            <li><RouterLink class="p2" to="#">نصب بازی رو پلی استیشن</RouterLink></li>
                            <li><RouterLink class="p2" to="#">نصب بازی روی ایکس باکس</RouterLink></li>
                        </ul>
                    </li>
                </ul>
                <ul class="menu-1">
                    <li class="menuselect" title="حالت تاریک">
                        <RouterLink to="#"><svg xmlns="http://www.w3.org/2000/svg" height="16" width="12" viewBox="0 0 384 512"><path d="M144.7 98.7c-21 34.1-33.1 74.3-33.1 117.3c0 98 62.8 181.4 150.4 211.7c-12.4 2.8-25.3 4.3-38.6 4.3C126.6 432 48 353.3 48 256c0-68.9 39.4-128.4 96.8-157.3zm62.1-66C91.1 41.2 0 137.9 0 256C0 379.7 100 480 223.5 480c47.8 0 92-15 128.4-40.6c1.9-1.3 3.7-2.7 5.5-4c4.8-3.6 9.4-7.4 13.9-11.4c2.7-2.4 5.3-4.8 7.9-7.3c5-4.9 6.3-12.5 3.1-18.7s-10.1-9.7-17-8.5c-3.7 .6-7.4 1.2-11.1 1.6c-5 .5-10.1 .9-15.3 1c-1.2 0-2.5 0-3.7 0c-.1 0-.2 0-.3 0c-96.8-.2-175.2-78.9-175.2-176c0-54.8 24.9-103.7 64.1-136c1-.9 2.1-1.7 3.2-2.6c4-3.2 8.2-6.2 12.5-9c3.1-2 6.3-4 9.6-5.8c6.1-3.5 9.2-10.5 7.7-17.3s-7.3-11.9-14.3-12.5c-3.6-.3-7.1-.5-10.7-.6c-2.7-.1-5.5-.1-8.2-.1c-3.3 0-6.5 .1-9.8 .2c-2.3 .1-4.6 .2-6.9 .4z"></path></svg></RouterLink>
                    </li>
                    <li class="menuselect" title="علاقه مندی ها">
                        <RouterLink to="#"><svg xmlns="http://www.w3.org/2000/svg" height="16" width="16" viewBox="0 0 512 512"><path d="M225.8 468.2l-2.5-2.3L48.1 303.2C17.4 274.7 0 234.7 0 192.8v-3.3c0-70.4 50-130.8 119.2-144C158.6 37.9 198.9 47 231 69.6c9 6.4 17.4 13.8 25 22.3c4.2-4.8 8.7-9.2 13.5-13.3c3.7-3.2 7.5-6.2 11.5-9c0 0 0 0 0 0C313.1 47 353.4 37.9 392.8 45.4C462 58.6 512 119.1 512 189.5v3.3c0 41.9-17.4 81.9-48.1 110.4L288.7 465.9l-2.5 2.3c-8.2 7.6-19 11.9-30.2 11.9s-22-4.2-30.2-11.9zM239.1 145c-.4-.3-.7-.7-1-1.1l-17.8-20c0 0-.1-.1-.1-.1c0 0 0 0 0 0c-23.1-25.9-58-37.7-92-31.2C81.6 101.5 48 142.1 48 189.5v3.3c0 28.5 11.9 55.8 32.8 75.2L256 430.7 431.2 268c20.9-19.4 32.8-46.7 32.8-75.2v-3.3c0-47.3-33.6-88-80.1-96.9c-34-6.5-69 5.4-92 31.2c0 0 0 0-.1 .1s0 0-.1 .1l-17.8 20c-.3 .4-.7 .7-1 1.1c-4.5 4.5-10.6 7-16.9 7s-12.4-2.5-16.9-7z"></path></svg></RouterLink>
                    </li>
                    <li class="menuselect" title="مقایسه" >
                        <RouterLink to="#"><svg xmlns="http://www.w3.org/2000/svg" height="16" width="18" viewBox="0 0 576 512"><path d="M403.8 34.4c12-5 25.7-2.2 34.9 6.9l64 64c6 6 9.4 14.1 9.4 22.6s-3.4 16.6-9.4 22.6l-64 64c-9.2 9.2-22.9 11.9-34.9 6.9s-19.8-16.6-19.8-29.6V160H352c-10.1 0-19.6 4.7-25.6 12.8L284 229.3 244 176l31.2-41.6C293.3 110.2 321.8 96 352 96h32V64c0-12.9 7.8-24.6 19.8-29.6zM164 282.7L204 336l-31.2 41.6C154.7 401.8 126.2 416 96 416H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H96c10.1 0 19.6-4.7 25.6-12.8L164 282.7zm274.6 188c-9.2 9.2-22.9 11.9-34.9 6.9s-19.8-16.6-19.8-29.6V416H352c-30.2 0-58.7-14.2-76.8-38.4L121.6 172.8c-6-8.1-15.5-12.8-25.6-12.8H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H96c30.2 0 58.7 14.2 76.8 38.4L326.4 339.2c6 8.1 15.5 12.8 25.6 12.8h32V320c0-12.9 7.8-24.6 19.8-29.6s25.7-2.2 34.9 6.9l64 64c6 6 9.4 14.1 9.4 22.6s-3.4 16.6-9.4 22.6l-64 64z"></path></svg></RouterLink>
                    </li>
                    <li class="menuselect" title="سبد خرید">
                        <RouterLink to="#"><li><svg xmlns="http://www.w3.org/2000/svg" height="16" width="14" viewBox="0 0 448 512"><path d="M160 112c0-35.3 28.7-64 64-64s64 28.7 64 64v48H160V112zm-48 48H48c-26.5 0-48 21.5-48 48V416c0 53 43 96 96 96H352c53 0 96-43 96-96V208c0-26.5-21.5-48-48-48H336V112C336 50.1 285.9 0 224 0S112 50.1 112 112v48zm24 48a24 24 0 1 1 0 48 24 24 0 1 1 0-48zm152 24a24 24 0 1 1 48 0 24 24 0 1 1 -48 0z"></path></svg></li></RouterLink>
                    </li>
                </ul>
            </div>               
       </div>
    </Header>
</template>
<style scoped>
   
    header{ 
        justify-content: center;
        width: 100%;
        height: 170px;
        line-height: 15px;
        background-color: black;
    }
    .head{
    height: 130px;
    width: 100%;
    background-color: #f5f7f8f7;
    justify-content: center;
    direction: rtl;
    display: flex;
    }
    .icon{
    border-radius: 100px;
    width: 130px;
    height: 130px;
    }
    .icon:hover{
        width: 140px;
        height: 140px;
        transition: 0.6s ease;
        box-shadow:  0  1px 60px rgba(0, 0, 0, 0.213);
    }
    .rocket{
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 250px;
    height: 150px;
    }
    
    .title{
    width: 260px;
    height: 150px;
    font-size: 30px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
    .Slogan{
        background-color: #d9eeff;
        color: #1e6fb6!important;
        font-size: 17px;
        width: 180px;
        height:40px;
        border-radius: 50rem;
        transition: 0.5s ease-in-out;
        border-color: #d9eeff;
        border: none;
        outline: none
    }  
    .Slogan:hover{
        border-color:#01437c;
    }
    .Slogan1{
        box-sizing: border-box;
        border: none;
        outline: none;
    }
    #daste-bandi{
        border-radius: 0rem 5rem 5rem 0rem;
        background-color: #d9eeff;
        border-color: #d9eeff;
        width: 80px;
        height: 40px;
        cursor: pointer;
    }
    .search-bar{
        outline: none;
        background-color: #d9eeff;
        border-color: #d9eeff;
        width: 300px;
        height: 40px;
        border: none;
    }
    .btn-search{
        border-radius: 5rem 0rem 0rem 5rem;
        outline: none;
        background-color: #d9eeff;
        border-color: #d9eeff;
        width: 50px;
        height: 40px;
        border: none;
        cursor: pointer;
    }
    .menubar{
    direction: rtl;
    display: flex;
    align-items: center;
    width: 100%;
    height: 40px;
    line-height: 10px;
    justify-content: space-between;
   
    }
    .menu{
        width: 500px;
        height: 40px;
        color: white;
        display: flex;
        line-height:30px;
        border-bottom: 2px solid #f80e0e;
        justify-content: space-around;
        border-top: 2px solid #f80e0e;
    }
    .menu-1{
        width: 250px;
        height: 40px;
        color: white;
        display: flex;
        line-height:30px;
        border-bottom: 2px solid #f80e0e;
        justify-content: space-around;
        border-top: 2px solid #f80e0e;
    }
    .menuselect{
        display: flex;
        justify-content: space-around;
        color: rgb(8, 0, 255);
        line-height: 38px;
        width: max-content;
        z-index: 100;
    }
    .menu-item{
        display: none;
        z-index: 1000px;
    }
    .menuselect:hover .menu-item{
        display: block;
        margin-bottom: 2px;
        width:max-content;
        font-weight: 800px;
        height: max-content;
        border-radius: 10px;
        border: black;
        background-color:  rgb(255, 230, 0);
        color: black;
        transition: 0.3s ease;
        font-size: 12px;

    }
    form{
        display: flex;
    }
    .bar1{
        direction: rtl;
        display:flex;
        align-items:center;
        justify-content: center;
        width: 100%;
        height: 40px;
        background-color: #2ef414   ;
        line-height: 10px;
    }
    .smile-icon{
        display: flex;
        line-height: 15px;
    }
    .tx1{
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 73px;
    font-size:18px;
    }
    .container{
        width:80%;
        height: auto;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
</style>