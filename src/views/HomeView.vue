<template>
  <div class="home">
    <div class="header">
      <div class="storeName">
        <span></span>
      </div>
      <div class="shop">
        <span>Shop</span>
      </div>
      <div class="about_us">
        <span>About Us</span>
      </div>
      <div class="about_us">
        <span>Contact</span>
      </div>
      <div class="search_box">
        <input type="text" placeholder="Search">
      </div>
      <div class="searchIcon">
        <img src="https://www.freepnglogos.com/uploads/search-png/search-icon-clip-art-clkerm-vector-clip-art-online-22.png" alt="">
      </div>
      <div class="signLog">
        <span>Sign Up</span> | <span>Log In</span>
      </div>
      <div class="language">
        <div class="world">
          <img src="https://www.freeiconspng.com/thumbs/world-icon-png/web-icon-black-png-planet-web-world-icon-17.png" alt="">
        </div>
        <div class="labels">
          <span> EN</span>
        </div>
      </div>
      <div class="cart">
        <div class="cartImg">
          <img src="https://www.freepnglogos.com/uploads/shopping-cart-png/shopping-cart-svg-png-icon-download-28.png" alt="">
        </div>
        <div class="cartLabel">
          <span>Cart(0)</span>
        </div>
      </div>
    </div>
    <div class="content">
      <div class="sponsor">
        
      </div>
      <!-- <div class="best">
        <span>Best Sell</span>
      </div> -->
      <div class="bookRef">
        <div class="bookInfo">
          <div class="book">
            <img src="https://www.apple.com/newsroom/images/product/iphone/standard/Apple-iPhone-14-Pro-iPhone-14-Pro-Max-deep-purple-220907_inline.jpg.large.jpg" alt="">
          </div>
          <div class="title">
            <span>iPhone 14 Pro max</span>
          </div>
          <div class="price">
            <span>$20.00</span>
          </div>
        </div>
        <div class="bookInfo">
          <div class="book">
            <img src="https://shunliphone.com/wp-content/uploads/2022/10/ipad-pro-12-2022-gray.jpg" alt="">
          </div>
          <div class="title">
            <span>iPad</span>
          </div>
          <div class="price">
            <span>$18.50</span>
          </div>
        </div>
        <div class="bookInfo">
          <div class="book">
            <img src="https://images.macrumors.com/t/MwgTEggiztXrvIN2l8bZny1f93M=/1600x/article-new/2013/09/2023-macbook-pro-transparent.png" alt="">
          </div>
          <div class="title">
            <span>Macbook Pro M2 16inch</span>
          </div>
          <div class="price">
            <span>$25.75</span>
          </div>
        </div>
        <div class="bookInfo">
          <div class="book">
            <img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/airpods-max-hero-select-202011_FMT_WHH?wid=607&hei=556&fmt=jpeg&qlt=90&.v=1633623988000" alt="">
          </div>
          <div class="title">
            <span>Airpod Pro Max</span>
          </div>
          <div class="price">
            <span>$27.00</span>
          </div>
        </div>
      </div>
      <div class="bookRef">
        <div class="bookInfo">
          <div class="book">
            <img src="https://www.sony.jp/products/picture/WH-1000XM5.jpg" alt="">
          </div>
          <div class="title">
            <span>sony wh-1000xm5</span>
          </div>
          <div class="price">
            <span>$20.00</span>
          </div>
        </div>
        <div class="bookInfo">
          <div class="book">
            <img src="https://images.khmer24.co/22-10-02/718201-airpod-pro-2-new-1664684624-62835421-b.jpg" alt="">
          </div>
          <div class="title">
            <span>Airpod Pro 2</span>
          </div>
          <div class="price">
            <span>$18.50</span>
          </div>
        </div>
        <div class="bookInfo">
          <div class="book">
            <img src="https://hips.hearstapps.com/hmg-prod/images/apple-watchos-9-hero-220912-1663689025.jpg" alt="">
          </div>
          <div class="title">
            <span>Apple Watch</span>
          </div>
          <div class="price">
            <span>$25.75</span>
          </div>
        </div>
        <div class="bookInfo">
          <div class="book">
            <img src="data:image/jpeg;base64,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" alt="">
          </div>
          <div class="title">
            <span>Garmin sapphire solar fenix 7x</span>
          </div>
          <div class="price">
            <span>$27.00</span>
          </div>
        </div>
      </div>
      
    </div>
      
    </div>
    
    <div class="footer" style="padding:auto;">
      <div class="newsletter">
        <button style="background-color: #0fb668; padding: 10px; border-radius: 10px; ">Sign Up for new customer</button>
      </div>
      <div class="subscribe">
        <div class="visa">
          <img src="https://financefeeds.com/wp-content/uploads/2021/07/Visa_Inc._logo.svg.png" alt="">
        </div>
        <div class="master">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/MasterCard_Logo.svg/2560px-MasterCard_Logo.svg.png" alt="">
        </div>
        <div class="pay_pal">
          <img src="https://cdn-icons-png.flaticon.com/512/196/196566.png" alt="">
        </div>
        <div class="faq">
          <span>FAQ</span>
        </div>
        <div class="join">
          <span>Join Us</span>
        </div>
        <div class="social_media">
          <div class="social_img">
            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/04/Facebook_f_logo_%282021%29.svg/2048px-Facebook_f_logo_%282021%29.svg.png" alt="">
          </div>
          <div class="social_img">
            <img src="https://seeklogo.com//images/D/discord-logo-134E148657-seeklogo.com.png" alt="">
          </div>
          <div class="social_img">
            <img src="https://static-00.iconduck.com/assets.00/instagram-icon-512x512-ggh8x3cn.png" alt="">
          </div>
          <div class="social_img">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Twitter-logo.svg/1245px-Twitter-logo.svg.png" alt="">
          </div>
        </div>
        <div class="go_subscribe">
          <div class="mail">
            <input type="text" placeholder="Enter your email" style="width:7rem; border-radius:5px" name="" id="mail">
          </div>
          <div class="subscribe_btn">
            <button>Subscribe now</button>
          </div>
        </div>
      </div>
      
    </div>
  
</template>

<style>
@media (min-width: 1024px) {
  .home {
    /* min-height: 100vh; */
    /* display: flex; */
    /* align-items: center; */
  }
  .header{
    display: flex;
    height: 93px;
    background-color: #ebd0d0;
    align-items: center;
    font-size: 18px;
    /* margin: auto; */
  }
  .header span:hover{
    color:rgb(12, 180, 12);
    cursor: pointer;
  }
  .storeName{
    width: 51px;
    height: 22px;
    margin-left: 60px;
  }
  .shop{
    height: 22px;
    margin-left: 557px;
  }
  .about_us{
    height: 22px;
    margin-left: 22px;
  }
  .search_box input{
    width: 30rem;
    height: 43px;
    margin-left: 30px;
    border: none;
    border-radius: 25px;
    padding-left: 15px;
    padding-top: 5px;
  }
  .search_box input::placeholder{
    font-size: 30px;
    color: #D9D9D9;
   
  }
  .searchIcon img{
    width: 21px;
    height: 21px;
    margin-top: 5px;
    margin-left: -50px;
  }
  .signLog{
    margin-left: 30px;
  }
  .language{
    margin-left: 30px;
    display: flex;
    margin-top: 6.5px;
  }
  .language:hover{
    color: rgb(12, 180, 12);
    cursor: pointer;
  }
  .language .world img{
    width: 22px;
    height: 22px;
  }
  .language .labels{
    margin-left: 8px;
  }
  .cart{
    margin-left: 14px;
    display: flex;
    margin-top: 6.5px;
  }
  .cart:hover{
    color: rgb(12, 180, 12);
    cursor: pointer;
  }
  .cart .cartImg img{
    width: 22px;
    height: 22px;
  }
  .cart .cartLabel{
    margin-left: 6px;
  }
  .content{
    height: 685px;
  }
  .sponsor{
    width: 1320px;
    margin: 15px auto;
    display: flex;
  }
  .sponsor .message{
    width: 50%;
    font-size: 100px;
    font-weight: bold;
    padding-left: 135px;
  }
  .sponsor .bookCate{
    margin-left: 10px;
  }
  .sponsor .groupBook .bookCate img{
    width: 130px;
    height: 224px;
  }
  .sponsor .groupBook{
    display: flex;
  }
  .best{
    font-size: 40px;
    text-align: center;
    font-weight: bold;
  }
  .bookRef{
    display: flex;
    font-size: 20px;
    width: 1226px;
    margin: 0px auto;
    justify-content: space-between;
    flex-direction: row;
  }
  .book img{
    width: 224px;
    height: 224px;
  }
  .bookInfo{
    text-align: center;
    width: 224px;
    height: 286px;
  }
  .social{
    width: 1325px;
    margin: 0px auto;
    display: flex;
    justify-content: space-between;
  }
  .logo img{
    width: 291px;
    height: 96px;
    opacity: 45%;
  }
  .footer{
    height: 152px;
    background-color: #ebd0d0;
    font-size: 18px;
  }
  .newsletter{
    text-align: right;
    padding-right: 120px;
    padding-top: 13px;
    margin-bottom: 5px;
  }
  .subscribe{
    display: flex;
    height: 84px;
    align-items: center;
  }
  .visa img{
    width: 51px;
    margin-left: 60px;
  }
  .master img{
    width: 51px;
    margin-left: 20px;
  }
  .pay_pal img{
    width: 84px;
    margin-left: 20px;
  }
  .faq span{
    margin-left: 294px;
  }
  .join span{
    margin-left: 160px;
  }
  .social_media{
    display: flex;
    width: 132px;
    margin-left: 14px;
    justify-content: space-between;
  }
  .social_img img{
    width: 21px;
    height: 21px;
  }
  .go_subscribe{
    display: flex;
    margin-left: 160px;
  }
  .go_subscribe input{
    width: 145px;
    height: 43px;
    text-align: center;
  }
  .go_subscribe button{
    width: 142px;
    height: 48px;
    background-color: black;
    color: white;
  }
  .go_subscribe button:hover{
    cursor: pointer;
  }
  .copyright{
    width: 231px;
    display: flex;
    opacity: 45%;
    margin-left: 60px;
    height: 21px;
    align-items: center;
  }
  .c_icon img{
    width: 21px;
    height: 21px;
  }
  .rightReserve{
    margin-top: -5px;
  }
  .rightReserve span{
    height: 22px;
  }
}
</style>