<template>
  <mdb-container>
    <h2 class="h1-responsive font-weight-bold text-center my-5">Recent posts</h2>
    <p class="text-center w-responsive mx-auto mb-5">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    <mdb-row>
      <mdb-col lg="5">
        <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
          <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img%20(27).jpg" alt="Sample image" />
          <a>
            <mdb-mask overlay="white-slight" waves/>
          </a>
        </mdb-view>
      </mdb-col>
      <mdb-col lg="7">
        <a class="green-text">
          <h6 class="font-weight-bold mb-3">
            <mdb-icon icon="utensils" class="pr-2" />Food</h6>
        </a>
        <h3 class="font-weight-bold mb-3 p-0">
          <strong>Title of the news</strong>
        </h3>
        <p>Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat mdb-iconcere
          possimus, omnis voluptas assumenda est, omnis dolor repellendus et aut officiis debitis.</p>
        <p>by
          <a>
            <strong>Carine Fox</strong>
          </a>, 19/08/2018</p>
        <mdb-btn color="success" size="md" class="waves-light ">Read more</mdb-btn>
      </mdb-col>
    </mdb-row>
    <hr class="my-5" />
    <mdb-row>
      <mdb-col lg="7">
        <a class="pink-text">
          <h6 class="font-weight-bold mb-3">
            <mdb-icon icon="image" class="pr-2" />Lifestyle
          </h6>
        </a>
        <h3 class="font-weight-bold mb-3 p-0">
          <strong>Title of the news</strong>
        </h3>
        <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti
          quos dolores et quas molestias excepturi sint occaecati cupiditate non provident.</p>
        <p>by
          <a>
            <strong>Carine Fox</strong>
          </a>, 14/08/2018</p>
        <mdb-btn color="pink" size="md" class="mb-lg-0 mb-4 waves-light">Read more</mdb-btn>
      </mdb-col>
      <mdb-col lg="5">
        <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
           <img
            src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(35).jpg"            
            alt="Sample image"
            class="img-fluid"
            v-animateOnScroll="{animation: 'fadeInLeft', delay: 300}"
          >
          <a>
            <mdb-mask overlay="white-slight" waves/>
          </a>
        </mdb-view>
      </mdb-col>
    </mdb-row>
    <hr class="my-5" />
    <mdb-row>
      <mdb-col lg="7">
        <a class="indigo-text">
          <h6 class="font-weight-bold mb-3">
            <mdb-icon icon="suitcase" class="pr-2" />Food</h6>
        </a>
        <h3 class="font-weight-bold mb-3 p-0">
          <strong>Title of the news</strong>
        </h3>
        <p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos
          qui ratione voluptatem sequi nesciunt. Neque porro qui dolorem ipsum quia sit amet.</p>
        <p>by
          <a>
            <strong>Carine Fox</strong>
          </a>, 11/08/2018</p>  
            <mdb-btn color="indigo" size="md" class="waves-light ">Read more</mdb-btn>
             <mdb-btn :to="{ name: 'Team' }" color="indigo" size="md" class="waves-light ">Team</mdb-btn>       
      </mdb-col>
       <mdb-col lg="5">
        <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
          <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img (28).jpg" alt="Sample image" />
          <a>            
            <mdb-mask overlay="white-slight" waves/>
          </a>            
        </mdb-view>
      </mdb-col> 
       
    </mdb-row>
    <!-- Footer -->
  <!-- <mdb-footer color="blue" class="font-small pt-4 mt-4">
    <div class="footer-copyright text-center py-3">
      <mdb-container fluid>
        &copy; 2020 Copyright: <a href="https://www.MDBootstrap.com"> MDBootstrap.com </a>
      </mdb-container>
    </div>
  </mdb-footer> -->
  <!-- Footer -->
    <hr class="my-3" />
  </mdb-container>
</template>
<script>
  
  import { mdbContainer, mdbRow, mdbCol, mdbBtn, mdbView, mdbMask, mdbIcon, animateOnScroll} from 'mdbvue';
  export default {
    name: 'About',
    components: {
       // mdbFooter,
        mdbContainer,
        mdbRow,
        mdbCol,
        mdbBtn,
        mdbView,
        mdbMask,
        mdbIcon,
      //mdbCard,
    //   mdbCardBody,
     
    },
     directives: {
      animateOnScroll
    }
  }
</script>