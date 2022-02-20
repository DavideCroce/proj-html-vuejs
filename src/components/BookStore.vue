<template>
  <div class="book-store container">
        <div class="row">
          <div class="col-5 books-info">
            <p class="subtitle">BOOK STORE ONLINE</p>
            <h1>Be Alpha With <span class="green">Wingman's Book</span></h1>
            <ul>
              <li><span class="green"><i class="fas fa-check"></i></span>Help you understand yourself better</li>
              <li><span class="green"><i class="fas fa-check"></i></span>Revealing mature tips</li>
              <li><span class="green"><i class="fas fa-check"></i></span>Give the right advice</li>
              <li><span class="green"><i class="fas fa-check"></i></span>Fascinating examples of alpha man</li>
            </ul>
            <button>Get Free Ebook</button>
          </div>
          <div class="col-3 book text-center">
            <img src="../assets/img/product-book-11-400x400.jpg" alt="">
            <p class="title">Alpha man by Maxcoach</p>
            <div class="price">$29.<span class="smaller">00</span></div>
          </div>
          <div class="col-3 book text-center">
            <img src="../assets/img/product-book-10-400x400.jpg" alt="">
            <p class="title">Real man 4.0 by Maxcoach</p>
            <div class="price">$39.<span class="smaller">00</span></div>
          </div>
        </div>
      </div>
</template>

<script>
export default {
name: "BookStore",
}
</script>

<style scoped lang="scss">
ul{
    list-style-type: none;
    padding-left: 0;
    padding-bottom: 25px;
    li{
      padding-bottom: 15px;
      color: grey;
      span{
        padding-right: 10px;
      }
    }
  }
  .green{
    color: #20ac97;
  }
  h1{
    font-family: 'Playfair Display', serif;
    padding-bottom: 25px;
    padding-right: 200px;
  }
  button{
    padding: 15px 60px;
     background-color: #20ac97;
    color: white;
    font-weight: 500;
    border: none;
    border-radius: 5px;
    font-size: 13px;
  }
button:hover{
  background-color: #3f3a64;
}
  .book-store{
    margin-bottom: 150px;
  }
  .book{
    // padding: 15px;
    img{
      height: 300px;
    }
    .title{
      font-size: 20px;
      font-weight: 500;
      padding-top: 20px;
    }
    .price{
      font-size: 25px;
      color: #20ac97;
      font-weight: 500;
      .smaller{
        font-size: 18px;
      }
    }
  }
</style>