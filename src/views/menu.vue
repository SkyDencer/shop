<template>
    <ul class="menu">
    <li class="menuselect">
        <RouterLink to="/">خانه</RouterLink>
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
</template>
<style scoped>
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
        border-bottom: 2px solid #495E57;
        justify-content: space-around;
        border-top: 2px solid #495E57;
    }
    .menu-1{
        width: 250px;
        height: 40px;
        color: white;
        display: flex;
        line-height:30px;
        border-bottom: 2px solid #495E57;
        justify-content: space-around;
        border-top: 2px solid #495E57;
    }
    .menuselect{
        display: flex;
        justify-content: space-around;
        color: white;
        line-height: 38px;
        width: max-content;
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
</style>