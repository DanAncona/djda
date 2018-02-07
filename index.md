---
layout: default
---

<section id="about" name="about"></section>

<div id="intro">
  <div class="container">

        <div class="row">               
            <div class="col-lg-8">

                <ul>
                  {% for post in site.posts %}
                      <a href="{{ post.url }}"><h1>{{ post.title }}</h1></a>
                      <p style="margin-bottom: 10px;">{{post.date | date_to_string}}<br/>
                        <img src="{{post.img}}" style="height: 140px; float: left; margin-right: 20px; margin-top: 18px;">
                        {{post.excerpt}}
                      </p>
                      <p style="line-height: 2px; margin-bottom: 50px;"><a href="{{ post.url }}">Continue reading &raquo;</a></p>
                  {% endfor %}
                </ul>

            </div>

            <div class="col-lg-4">
              <ul>
                <img src="/assets/img/me-signing.jpg" width="240px"/>
                <p>
                Dan Ancona creates stories and builds and evangelizes online tools that connect people and strengthen democracy. He has helped create and build interest in numerous products in twenty years of experience in startups, technology companies and academia, with a research focus on visualization and geographic information. Since 2006, he has been accelerating the shift from top-down, broadcast-based political systems to a more networked, person-to-person, diversity-positive and inclusive democratic system. From 2007 to 2010 he built California VoterConnect, a nonprofit social venture that provided advanced online voter file tools and training to community based organizations and large and small campaigns, focusing on ethnically and racially diverse communities. VoterConnect achieved breakeven revenue in three years, and helped its clients record nearly 1M person to person field contacts in California in the 2010 election cycle. He later founded Democracy Dashboard, the first online social voting and endorsement platform. His clients have included PlaceWorks, TargetSmart Communications, Citizen Engagement Lab, and the Agenda Project. His writing has been published by the Drum Major Institute, TechPresident, Democratic Strategist and various blogs. When he's not writing or building stuff, he's usually cooking, DJing, skiing or sailing. You can get more information about and buy his novel (science fiction, where the advanced technologies are relationships and democracy) at <a href="http://readvenusshrugged.com/">readvenusshrugged.com</a>. He lives in a mini-cohousing community in Oakland with his wife and fellow organizer Jenifer Fernandez Ancona, and their son.
                </p>

                <a href="http://readvenusshrugged.com/"><img src="http://readvenusshrugged.com/images/VenusShrugged-Finalv2-400.png" width="240px"/><br/>Read my book!</a><br/>

                <br/>

                <a href="http://medium.com/@DanAncona"><i class="icon-file"></i><sm> Recent writing</sm></a><br/>
                <a href="http://danancona.blogspot.com/"><i class="icon-file"></i><sm> Super old writing</sm></a><br/>
                <a href="http://tinyletter.com/DanAncona"><i class="icon-file"></i><sm> Newsletter</sm></a><br/>
                <a href="http://m.me/DansBrainBot"><i class="icon-file"></i><sm> DansBrainBot</sm></a><br/>
                <a href="/djda"><i class="icon-file"></i><sm> dj da</sm></a>
              </ul>
            </div>
            
        </div><!--/.row -->
  </div>
</div><!--/ #intro -->


<!--PORTFOLIO DESCRIPTION -->

<!--
<section id="work" name="work"></section>
<div class="container desc">
    <div class="row">
            <div class="col-lg-2 col-lg-offset-1">
                <h5>PORTFOLIO</h5>
            </div>

            <div class="col-lg-6">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p style="margin-bottom: 5px">PLACEWORKS</p>
                <imp><sm>CURRENT</sm></imp>
                <p style="margin-top: 5px"><more>I'm current building civic engagement tools and visualizations for Placeworks, an urban design firm with offices throughout California.<br/><br/>
                </p>
                    <sm><i class="icon-tag"></i> project management, product design, development, visualization</sm></more> 
            </div>
            
            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                <p>DEMOCRACY DASHBOARD</p>
            <p><more>DemDash was, at one point, the future of democracy.<br/><br/>
                <sm><i class="icon-tag"></i> design</sm></more> 
            </p>
            </div>

            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p>CALIFORNIA VOTERCONNECT</p>
                <p><more>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br/><br/>
                    <sm><i class="icon-tag"></i> front-end</sm></more> 
                </p>
            </div>
            
            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p>WHY</p>
                <p><more>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br/><br/>
                    <sm><i class="icon-tag"></i> web design</sm></more> 
                </p>
            </div>

            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p>2063</p>
                <p><more>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br/><br/>
                    <sm><i class="icon-tag"></i> web design</sm></more> 
                </p>
            </div>

            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p>CITIZEN ENGAGEMENT LAB, DEMOCRACY FOR AMERICA, AGENDA PROJECT, POPLICUS</p>
                <p><more>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br/><br/>
                    <sm><i class="icon-tag"></i> web design</sm></more> 
                </p>
            </div>

            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p>ALEXANDRIA DIGITAL LIBRARY</p>
                <p><more>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br/><br/>
                    <sm><i class="icon-tag"></i> web design</sm></more> 
                </p>
            </div>

            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p>INTERVISTA, CRITICAL PATH, VIZBANG</p>
                <p><more>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br/><br/>
                    <sm><i class="icon-tag"></i> web design</sm></more> 
                </p>
            </div>

            <div class="col-lg-6 col-lg-offset-3">
                <p><img class="img-responsive" src="assets/img/port01.jpg" alt=""></p>
            </div>
            <div class="col-lg-3">
                    <p>INSTITUTE FOR ADVANCED TECHNOLOGY IN THE HUMANITIES</p>
                <p><more>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br/><br/>
                    <sm><i class="icon-tag"></i> web design</sm></more> 
                </p>
            </div>

    
    </div>
</div>


-->
