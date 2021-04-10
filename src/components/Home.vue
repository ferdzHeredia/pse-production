<template>
  <mdb-container >
    <hr class="my-3" />

    <!-- First row-->
    <mdb-row>
<mdb-card>
		<mdb-view hover>
			<a href="#!">
				<mdb-card-image
					src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20%282%29.jpg"
					alt="Card image cap"/>
				<mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
			</a>
		</mdb-view>
		<mdb-card-body>
			<mdb-card-title>Card with waves effect</mdb-card-title>
			<mdb-card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</mdb-card-text>
			<mdb-btn color="primary">Button</mdb-btn>
		</mdb-card-body>
	</mdb-card>

      <mdb-col lg="7">
    <div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/6tuZHqcf2QA" allowfullscreen autoplay loop controls muted v-animateOnScroll="'rollIn'"></iframe>
  </div>
    </mdb-col>    
      </mdb-row>
<!-- second row-->
             
  <hr class="my-5" />
  </mdb-container> 
</template>
<script>
  import {mdbContainer, mdbRow, mdbCol, animateOnScroll, mdbCard, mdbCardImage,	mdbCardBody,mdbCardTitle,	mdbCardText, mdbView, mdbMask, mdbBtn} from 'mdbvue';
  export default {
    name: 'Home',
    components: {  
      mdbContainer,
      mdbRow,
      mdbCol, 
      mdbCard,
      mdbCardImage,
			mdbCardBody,
			mdbCardTitle,
			mdbCardText,
      mdbView,
			mdbMask,
      mdbBtn
    },
    directives: {
      animateOnScroll
    }
  }
</script>