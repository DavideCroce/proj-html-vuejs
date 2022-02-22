<template>
  <div class="book-store container">
        <div class="row">
          <div class="col-12 col-sm-12 col-md-5 books-info">
            <p class="subtitle">BOOK STORE ONLINE</p>
            <h1>Be Alpha With <span class="green">Wingman's Book</span></h1>
            <ul v-for="improve in improves" :key="improve.thing" class="improves">
              <li><span class="green"><i class="fas fa-check"></i></span>{{improve.thing}}</li>
            </ul>
            <button>Get Free Ebook</button>
          </div>
          <div class="col-12 col-sm-6 col-md-3 book text-center" v-for="book in books" :key="book.title">
            <ul class="to-do">
              <li><i class="fas fa-search"></i></li>
              <li><a :href="book.amazon" target="_blank"><i class="fas fa-shopping-cart"></i></a></li>
              <li><i class="far fa-heart"></i></li>
              <li><i class="fas fa-signal"></i></li>
            </ul>
            <img :src="require(`../assets/img/product-book-${book.image}-400x400.jpg`)" alt="">
            <p class="title">{{book.title}}</p>
            <div class="price">${{book.big}}.<span class="smaller">{{book.small}}</span></div>
          </div>
        </div>
      </div>
</template>

<script>
export default {
name: "BookStore",
data(){
  return{
    books:[
      {
        image: '11',
        title: 'Alpha man by Maxcoach',
        big: '29',
        small: '00',
        amazon: 'https://www.amazon.it/Alpha-Man-Restoring-Your-Original/dp/1796695602/ref=sr_1_1?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1F7TFUTBL92H1&keywords=alpha+man&qid=1645543667&sprefix=alpha+man%2Caps%2C65&sr=8-1'
      },
      {
        image: '10',
        title: 'Real man 4.0 by Maxcoach',
        big: '39',
        small: '00',
        amazon: 'https://www.amazon.it/Real-Strength-Men-freedom-prison/dp/1939828899/ref=sr_1_1?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=39KUTKBSQ4IR&keywords=real+men+4.0&qid=1645543746&sprefix=real+man+4.0%2Caps%2C76&sr=8-1'
      }
    ],
    improves:[
      {
        thing: 'Help you understand yourself better',
      },
      {
        thing: 'Revealing mature tips',
      },
      {
        thing: 'Give the right advice',
      },
      {
        thing: 'Fascinating examples of alpha man',
      },
    ]
  }
}
}
</script>

<style scoped lang="scss">
.book{
  position: relative;
  padding-bottom: 50px;
  a{
    color: black;
  }
}
.book:hover{
  cursor: pointer; 
  .to-do{
    display: block;
  }
}
.to-do{
  list-style-type: none;
  position: absolute;
  top: 30px;
  right: 25px;
  display: none;
  li{
    color: black;
    background-color: #fff;
    margin-bottom: 20px;
    padding: 10px 13px;
    border-radius: 50%;
  }
}
.improves{
    list-style-type: none;
    padding-left: 0;
    li{
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
      width: 100%;
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
  @media screen and (max-width: 575px){
    .books-info{
      display: flex;
      align-items: center;
      flex-direction: column;
      h1{
        padding-right: 0;
      }
    }
  }
    @media screen and (max-width: 767px){
    .books-info{
      display: flex;
      align-items: center;
      flex-direction: column;
      h1{
        padding-right: 0;
      }
    }
  }
</style>