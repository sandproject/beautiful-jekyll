---
layout: page
title: SAND Project
#subtitle:  Self-managing Anycast Networks for DNS
---

<hr>
<h4 style="text-align:center; margin:5%">
We perform applied research in Anycast networks. <br> Our goal: traffic
engineering and DDoS mitigation.
</h4>


<hr>
<div class="container-fluid">
<div class="col-sm-12 col-sm-offset-0"> 
	<div class="row text-center"><br>
   		<div class="col-md-4 col-sm-4">
            <img src="/img/location.svg" width="90%" height="90%" alt="img banner" class="img-circle img-thumbnail">
            <h3 style="color:#245075">Anycast Catchment</h3>
			<!--	<p> Catchment refers to the nearby anycast site from the perspective of each user. -->
			<p>Active monitoring the visibility of the anycast sites enable to use the historical graph to predict future traffic load.</p>
        </div>
        <div class="col-md-4 col-sm-4">
            <img src="/img/bgp.svg" alt="" width="90%" height="90%" class="img-circle img-thumbnail">
            <h3 class="h3-color">BGP Route Annouces</h3>
	        <p> Modify BGP route announces enables to change each site visibility and redirect traffic from one site to another. </p>
        </div>
        <div class="col-md-4 col-sm-4">
            <img src="/img/load.svg" alt="" width="90%" height="90%" class="img-circle img-thumbnail">
            <h3 class="h3-color">Load <br>Distribution</h3>
            <p>Assist operators to accurately distribute the traffic load across sites is fundamental to develop a defense strategy.</p>
        </div>
	</div>
</div>
</div>

<hr>
<h4>Problem: </h4> 
Anycast relies on the Internet Routing that we do not have the fine
grain control.  We should monitor how the Internet sees our service
and find the best approach to influence the clients' reachability.

<h4>Our solution: </h4> 

We have developed a <a
href="https://github.com/Woutifier/verfploeter">tool</a> using a
simple and novel <a
href="https://dl.acm.org/citation.cfm?id=3131371">approach</a>. Thus,
we do regular measurements and observe how our policy can modify
traffic distribution across the anycast nodes.
<hr>


<h6>Cases:</h6>
<hr>

We are pround to say that folks from B-root and CloudFare are using
the proposed methodology to monitor their anycast networks.


<div class="col-sm-8 col-sm-offset-0"> 
    <div class="row text-center">
        <img style="border: 0px solid #000;margin-left:80px" src="/img/usc.png">
        <img style="border: 0px solid #000;margin-left:80px" src="/img/cloud.png">
    </div>
</div>
<br>

<hr>

<h6>Catchment investigation dashboard:</h6>
<div class="col-sm-12 col-sm-offset-0"> 
	<div class="row text-center"><br>

   			<img style="border: 1px solid #000;" src="/img/sand-dashboard.gif">
	</div>

</div>



<hr>
<div class="container-fluid" style="margin: 0% 25% 0% 25% color:blue">
<div class="col-sm-12 col-sm-offset-0"> 
	<div class="row text-center"><br>
           <div class="box">
                <div class="icon">
                    <div class="image"><i class="fa fa-file-text-o"></i></div>
                    <div class="info">
                        <h4> <span class="label label-primary">News</span> </h4>

						<!--begin news item -->
                        <p align="left">
			                <span class="badge" style="width: 100px;
			                margin-right:10px"> 1 May 2019</span>
			                Verfploeter catchment TTL investigation <a
			                href="https://github.com/joaoceron/verfploeter-ttl-investigation">see
			                research</a>.<br>
                        </p>
						<!--end news item -->


						<!--begin news item -->
                        <p align="left">
        				    <span class="badge" style="width:
        				    100px; margin-right:10px" > 11
        				    March 2019</span> New dashboard
        				    interface. See animation above.<br>
                        </p>
						<!--end news item -->

						<!--begin news item -->
                        <p align="left">
			                <span class="badge" style="width: 100px;
			                margin-right:10px" > 1 August 2018</span>
			                Paper accepted to IMC 2018, see <a
			                href="http://www.sand-project.nl/papers/">papers</a>.<br>
                        </p>
						<!--end news item -->


						<!--begin news item -->
                        <p align="left">
			                <span class="badge" style="width: 100px;
			                margin-right:10px" > 1 June 2018</span>
			                New technical paper, see <a
			                href="http://www.sand-project.nl/papers/">papers</a>.<br>
            			</p>
						<!--end news item -->


						<!--begin news item -->
                        <p align="left">
			                <span class="badge" style="width: 100px;
			                margin-right:10px" >23 May 2018</span> The
			                new website was published.<br>
                        </p>
						<!--end news item -->
                    </div>
                </div>
                <div class="space"></div>
            </div>
 	</div>
</div>
</div>
<hr>



<p style="text-align:justify">
The problem that SAND address is that DNS operators have very few
intelligent real-time tools that enable them to monitor their anycast
services, for instance during a DDoS attack.  Our goal is to develop,
prototype and evaluate tools and recommendations for anycast system
operators. <br> <br>An essential part of the project is to active
investigate anycast site visibility by the understanding of the dynamic
relationship between Internet routing (BGP) and anycast services.
<br>
<br> To accurately map the anycast sites visibility from the client
perspective enables operators to carefully manage their systems and
assisting in attacks response.
</p>
<hr>


<h6>SAND is a joint project:</h6>
<div class="container-fluid" style="margin: 0% 25% 0% 25%">
<div class="col-sm-12 col-sm-offset-0"> 
	<div class="row text-center"><br>
   		<div class="col-md-4 col-sm-4">
		    <a href="http://www.utwente.nl/"><img src="/img/twente.png"></a>
        </div>
        <div class="col-md-4 col-sm-4">
   			<a href="http://www.sidn.nl/"><img src="/img/sidn-logo.png"></a>
        </div>
        <div class="col-md-4 col-sm-4">
   			<a href="https://nlnetlabs.nl/"><img src="/img/nlnetlab.png"></a>
        </div>
	</div>
</div>
</div>


