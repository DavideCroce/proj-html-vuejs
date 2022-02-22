<template>
  <div class="sponsors container">
        <div class="row">
          <div class="col-6 col-sm-6 col-md-4 col-lg-2 d-flex align-items-center sponsor" v-for="sponsor in sponsors" :key="sponsor.image">
           <a :href="sponsor.site" target="_blank"><img :src="require(`../assets/img/client-logo-${sponsor.image}-primary.png`)" alt=""></a>
          </div>
        </div>
      </div>
</template>

<script>
export default {
name: "Sponsors",
data(){
  return{
    sponsors:[
      {
        image:'05',
        site: 'https://www.itsalive.in/'
      },
      {
        image:'06',
        site: 'http://sixbasetechnologies.com/'
      },
      {
        image:'07',
        site: 'https://nowherefamous.com/'
      },
      {
        image:'04',
        site: 'https://www.pencilagency.com/'
      },
      {
        image:'03',
        site: 'https://brookdigital.com/'
      },
      {
        image:'02',
        site: 'https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjA27rQzZP2AhUEndUKHexNAqMYABAFGgJ3cw&ae=2&ohost=www.google.com&cid=CAESWeD2lJ7OLQvyYn3e_NDb9oFuY33ui6i68vMfXwHaktSxzHe37NP6pUvco4pVWW3h16TL5569czBSizDmOtZGEaF9Vy7MM0sIuSAW4Z_XN1msi3RXj8rXGb29&sig=AOD64_1UTWgVBjDJaUAqLSZ-6POWgDEtFw&q&adurl&ved=2ahUKEwinhK_QzZP2AhX0R_EDHR9RDVQQ0Qx6BAgEEAE'
      },
    ]
  }
},
}
</script>

<style scoped lang="scss">
.sponsors{
  margin-bottom: 150px;
}
.sponsor{
  filter: grayscale(70%);
  opacity: 0.5;
}
.sponsor:hover{
  cursor: pointer;
}

@media screen and (max-width: 575px){
  .sponsor{
    margin-bottom: 40px;
  }
}
@media screen and (max-width: 767px){
  .sponsor{
    margin-bottom: 40px;
  }
}
@media screen and (max-width: 991px){
  .sponsor{
    margin-bottom: 40px;
  }
}
</style>