<template>
  <HelloWorld />

    <!-- banner-section start -->


	<!-- Header -->
    <header>
        <div class="header-content">
            <div class="header-content-inner">
                <h1>Dramatically Engage</h1>
                <p>Objectively innovate empowered manufactured products whereas parallel platforms.</p>
                <a href="#" class="btn btn-primary btn-lg">Engage Now</a>
            </div>
        </div>
    </header>

	<!-- Intro Section -->
    <section class="intro">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 col-lg-offset-2">
                	<span class="glyphicon glyphicon-apple" style="font-size: 60px"></span>
                    <h2 class="section-heading">Completely synergize resource taxing relationships</h2>
                    <p class="text-light">Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>
                </div>
            </div>
        </div>
    </section>

	<!-- Content 1 -->
    <section class="content">
        <div class="container">
            <div class="row">
                <div class="col-sm-6">
                    <img class="img-responsive img-circle center-block" src="images/microphone.jpg" alt="">
                </div>
                <div class="col-sm-6">
                	<h2 class="section-header">Best in Class</h2>
                	<p class="lead text-muted">Holisticly predominate extensible testing procedures for reliable supply chains. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>
                	<a href="#" class="btn btn-primary btn-lg">Classify It</a>
                </div>                
                
            </div>
        </div>
    </section>

	<!-- Content 2 -->
     <section class="content content-2">
        <div class="container">
            <div class="row">
                <div class="col-sm-6">
                	<h2 class="section-header">Superior Quality</h2>
                	<p class="lead text-light">Holisticly predominate extensible testing procedures for reliable supply chains. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>
                	<a href="#" class="btn btn-default btn-lg">Test It</a>
                </div>    
                <div class="col-sm-6">
                    <img class="img-responsive img-circle center-block" src="images/iphone.jpg" alt="">
                </div>            
                
            </div>
        </div>
    </section>    

    <!-- Promos -->
	<div class="container-fluid">
        <div class="row promo">
        	<a href="#">
				<div class="col-md-4 promo-item item-1">
					<h3>
						Unleash
					</h3>
				</div>
            </a>
            <a href="#">
				<div class="col-md-4 promo-item item-2">
					<h3>
						Synergize
					</h3>
				</div>
            </a>
			
			<a href="#">
				<div class="col-md-4 promo-item item-3">
					<h3>
						Procrastinate
					</h3>
				</div>
            </a>
        </div>
    </div><!-- /.container-fluid -->

	<!-- Content 3 -->
     <section class="content content-3">
        <div class="container">
			<h2 class="section-header"><span class="glyphicon glyphicon-pushpin text-primary"></span><br> Sanity Check</h2>
			<p class="lead text-muted">Holisticly predominate extensible testing procedures for reliable supply chains. Dynamically innovate resource-leveling customer service for state of the art customer service.</p> 
                    <a href="#" class="btn btn-primary btn-lg">Check Now</a>               
        
        </div>
    </section>
    
	<!-- Footer -->
    <footer class="page-footer">
    
    	<!-- Contact Us -->
        <div class="contact">
        	<div class="container">
				<h2 class="section-heading">Contact Us</h2>
				<p><span class="glyphicon glyphicon-earphone"></span><br> +1(23) 456 7890</p>
				<p><span class="glyphicon glyphicon-envelope"></span><br> info@example.com</p>
        	</div>
        </div>
        	
        <!-- Copyright etc -->
        <div class="small-print">
        	<div class="container">
        		<p>Copyright &copy; Example.com 2015</p>
        	</div>
        </div>
        
    </footer>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
  },
});
</script>
