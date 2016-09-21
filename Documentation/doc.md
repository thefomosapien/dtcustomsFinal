# Table of Content:

```
/*------------------------------------------------------------------
Project:	Rota Name HTML Template
Version:	1.0
Last change:	18 March 2016
-------------------------------------------------------------------*/
/*------------------------------------------------------------------
[Table of contents]

1. Font Awesome
2. Typography
3. Buttons
4. Form
5. Menu
6. Widget
7. Footer
8. Slick
9. Icon BOx
10. Price table
11. Testimonials
12. Warning section
13. Coupons
14. Careers section
15. About Us
16. Light Gallery
17. Date picker
18. Utilities


-------------------------------------------------------------------*/

```



# Scripts:


- jQuery
- slick carousel http://kenwheeler.github.io/slick/
- light gallery http://sachinchoolur.github.io/lightGallery/
- datapicker bootstrap https://bootstrap-datepicker.readthedocs.org/en/latest/
- isotope http://isotope.metafizzy.co/
- browser js
- device js





# 1. Accordion

  ```
   <div id="accordion" class="panel-group">
       <div class="panel panel-default">
           <div class="panel-heading">
               <h4 class="panel-title">
                   <a class="" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo">How do I know which auto service to trust?</a>
               </h4>
           </div>
           <div id="collapseTwo" class="panel-collapse collapse in">
               <div class="panel-body">
                   <p>Praesent auctor velit nec libero volutpat, vel pellentesque arcu tincidunt. Phasellus nec nisi imperdiet, tincidunt mi et, rhoncus nisl. Nullam sed leo ut lacus aliquam venenatis ut vestibulum felis. Nulla bibendum diam eu tortor faucibus molestie. Pellentesque venenatis rhoncus volutpat. Fusce ut sodales est, turpis. Donec eget feugiat est lacus tincidunt gravida quis felis rhoncus.</p>
               </div>
           </div>
       </div>
    </div>
  ```

  ##### Screenshot

  ![alt text](src/accordion.jpg)



# 2. Blog Posts

  1. Blog Image

  ```
  <article class="ct-blog-post ct-blog-post--image ct-u-paddingTop40 ct-u-paddingBottom80">
      <div class="ct-blog-post--media">
        <img src="assets/images/demo-content/blog_img1.jpg" alt="">
      </div>
      <div class="ct-blog-post--body">
          <div class="ct-blog-post--description"><h6>Posted by Richard on February 15, 2015 in Images,
              4
              comments</h6>
          </div>
          <div class="ct-blog-post--title"><h1><a href=""></a><a href="blog-post.html">Car hacks to instantly improve every drive</a></h1></div>
          <div class="ct-blog-post--content"><p>Aliquam dui magna, viverra sit amet lobortis id,
              fermentum dictum nisi. Nam maximus ullamcorper posuere mollis. Aliquam pharetra ante et
              velit commodo, et bibendum ante venenatis. Phasellus commodo velit nisl, non tempus
              lacus faucibus. In neque elit, mattis non purus eu, accumsan at massa id tincidunt.
              Morbi in varius mi, nec ullamcorper erat.</p>
          </div>
      </div>
      <a href="blog-post.html" class=""><h6 class="ct-fw-700 text-uppercase ct-linkHeader">Read more<i class="fa fa-caret-right"></i></h6></a>
  </article>

  ```
  ![](src/blog-image.jpg)

  2. Blog Simple

  ```
    <article class="ct-blog-post ct-u-paddingTop40 ct-u-paddingBottom80">
        <div class="ct-blog-post--media">

        </div>
        <div class="ct-blog-post--body">
            <div class="ct-blog-post--description"><h6>Posted by Richard on February 12, 2015 in News
                and
                updates, Leave a comment</h6>
            </div>
            <div class="ct-blog-post--title"><h1><a href="blog-post.html">Spring is right around the corner: how to get your
                vehicle
                ready for warmer weather</a></h1>
            </div>
            <div class="ct-blog-post--content"><p>Aliquam interdum dolor et sapien semper scelerisque.
                Suspendisse neque turpis, venenatis eget porta cursus, cursus at justo. Nullam id ipsum
                vitae turpis pellentesque faucibus. Nulla consequat arcu vel iaculis ultricies. Cras
                bibendum maximus libero eget malesuada. Mauris pretium tellus in neque pharetra, vitae
                fermentum mi dignissim. Vivamus nulla sem, commodo at consequat nec.</p>
            </div>
        </div>
        <a href="blog-post.html" class=""><h6 class="ct-fw-700 text-uppercase ct-linkHeader">Read more<i class="fa fa-caret-right"></i></h6></a>
    </article>

  ```
  ![](src/blog-simple.jpg)

  3. Blog Gallery

  ```
    <article class="ct-blog-post ct-blog-post--gallery ct-u-paddingTop40 ct-u-paddingBottom80">
        <div class="ct-blog-post--media">
            <div class="row">
                <div class="col-lg-4 text-center ct-u-paddingBottom30"><img src="assets/images/demo-content/blog_img2.jpg" alt=""></div>
                <div class="col-lg-4 text-center ct-u-paddingBottom30"><img src="assets/images/demo-content/blog_img3.jpg" alt=""></div>
                <div class="col-lg-4 text-center ct-u-paddingBottom30"> <img src="assets/images/demo-content/blog_img4.jpg" alt=""></div>
            </div>
            <div class="row">
                <div class="col-lg-4 text-center ct-u-paddingBottom30"><img src="assets/images/demo-content/blog_img5.jpg" alt=""></div>
                <div class="col-lg-4 text-center ct-u-paddingBottom30"><img src="assets/images/demo-content/blog_img6.jpg" alt=""></div>
                <div class="col-lg-4 text-center ct-u-paddingBottom30"><img src="assets/images/demo-content/blog_img7.jpg" alt=""></div>
            </div>
        </div>
        <div class="ct-blog-post--body">
            <div class="ct-blog-post--description"><h6>Posted by Richard on February 7, 2015 in Gallery,
                Images, 2 comments</h6>
            </div>
            <div class="ct-blog-post--title"><h1><a href="blog-post.html">Buying a used vehicle? What to look for</a></h1>
            </div>
            <div class="ct-blog-post--content"><p>Fusce vel tristique nunc. Aenean tempus, diam quis
                laoreet gravida, lectus sem lobortis orci, id ultricies turpis metus in arcu. Proin
                ullamcorper diam fringilla mi volutpat convallis. Sed tortor orci, lacinia ut leo quis,
                congue varius est. In hac habitasse platea dictumst. Etiam pulvinar pellentesque lorem,
                vel tempus purus vestibulum vitae. Maecenas lorem convallis consectetur.</p>
            </div>
        </div>
        <a href="blog-post.html" class=""><h6 class="ct-fw-700 text-uppercase ct-linkHeader">Read more<i class="fa fa-caret-right"></i></h6></a>
    </article>
  ```
  ![](src/blog-gallery.jpg)

  4. Blog Video

  ```
<article class="ct-blog-post ct-blog-post--video ct-u-paddingTop40 ct-u-paddingBottom80">
    <div class="ct-blog-post--media">

        <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item" src="//www.youtube.com/embed/ePbKGoIGAXY"></iframe>
        </div>

    </div>
    <div class="ct-blog-post--body">
        <div class="ct-blog-post--description"><h6>Posted by Richard on February 3, 2015 in Videos,
            1 comment</h6>
        </div>
        <div class="ct-blog-post--title"><h1><a href="blog-post.html">What is a Car Inspection?</a></h1>
        </div>
        <div class="ct-blog-post--content"><p>Aliquam dui magna, viverra sit amet lobortis id,
            fermentum dictum nisi. Nam maximus ullamcorper posuere mollis. Aliquam pharetra ante et
            velit commodo, et bibendum ante venenatis. Phasellus commodo velit nisl, non tempus
            lacus faucibus. In neque elit, mattis non purus eu, accumsan at massa id tincidunt.
            Morbi in varius mi, nec ullamcorper erat.</p>
        </div>
    </div>
    <a href="blog-post.html" class=""><h6 class="ct-fw-700 text-uppercase ct-linkHeader">Read more<i class="fa fa-caret-right"></i></h6></a>
</article>
  ```
  ![](src/blog-video.jpg)



# 3. Short info box

```
<div class="about-desc">
    <h4>Skills</h4>
    <h6>Pellentesque posuere luctus . Aenean dictum mollis dignissim. Pellentesque interdum
        dictum quam, vitae finibus tortor condimentum sed. Donec egestas tincidunt
        hendrerit.</h6>
</div>
```
![](src/short-info-box.jpg)


# 4. Person Box

```
<div class="media person-box">
    <a href="team.html">
        <div class="media-left">
            <img class="media-object" src="assets/images/demo-content/person1.jpg" alt="person">
        </div>
        <div class="media-body ct-fw-700">
            <h3 class="media-heading">Gregory Evans</h3>
            <h6>Owner</h6>
        </div>
    </a>
</div>
```

![](src/person-box.jpg)

# 5. Team Box

```
<div class="team-box">

    <div class="caption-box">
        <div class="caption upper">
            <h4>James Strasser</h4>
            <h6>Automotive &amp; Small engine technician</h6>
        </div>
        <img src="assets/images/demo-content/team.jpg" alt="">
    </div>

    <div class="caption-box">
        <div class="caption upper">
            <h4>Anne Simmons</h4>
            <h6>Office manager</h6>
        </div>
        <img src="assets/images/demo-content/team.jpg" alt="">
    </div>

</div>
```
![](src/team-box.jpg)

# 6. Reviews with infinite scroll and isotope

```
<div class="ct-isotope-container ct-u-paddingBoth50">
    <div class="grid ct-isotope-gallery" style="position: relative; height: 1132px;">
        <figure class="grid-sizer grid-item ct-isotope-item" style="position: absolute; left: 0%; top: 0px;">
            <div class="ct-isotope-item-inner">
                <div class="ct-isotope-item__media">
                    <div class="ct-testimonials ct-testimonials--sideMenu ct-u-paddingBottom70">
                        <div class="ct-testimonials-box">
                            <div class="ct-testimonials-text">
                                <h3>Julie D. <img src="assets/images/demo-content/stars.png" alt="stars" class="pull-right"> </h3>
                                <h6>Feb 21, 2015</h6>
                                <h5>Cras pharetra nunc ac magna pulvinar, id porttitor leo suscipit. Gravida urna
                                    sit amet accumsan imperdiet. Aenean facilisis ut tellus ut viverra. Vestibulum
                                    magna magna, ultricies condimentum non!</h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </figure>
    </div>

    <div class="text-center ct-u-paddingBoth30">
        <button id="load-more" class="btn btn-black" data-load-name="review" data-load-page="1">Load more reviews</button>
    </div>

</div>
```

and other "reviews" will be loaded from other html file. Example full html file named review1.html [important]:

```
<figure class="grid-item ct-isotope-item">
    <div class="ct-isotope-item-inner">
        <div class="ct-isotope-item__media">
            <div class="ct-testimonials ct-testimonials--sideMenu ct-u-paddingBottom70">
                <div class="ct-testimonials-box">
                    <div class="ct-testimonials-text">
                        <h3>Gerald Schwartz
                            <img src="assets/images/demo-content/stars.png" alt="stars" class="pull-right"> </h3>
                        <h6>Jan 31, 2015</h6>
                        <h5>Nulla porta auctor nunc non lacinia. Aliquam tempus mauris at sem mattis, nec varius neque scelerisque. Integer ornare, massa vulputate mattis dapibus, erat metus suscipit augue, placerat fringilla arcu elit at est.</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
</figure>
<figure class="grid-item ct-isotope-item">
    <div class="ct-isotope-item-inner">
        <div class="ct-isotope-item__media">
            <div class="ct-testimonials ct-testimonials--sideMenu ct-u-paddingBottom70" >
                <div class="ct-testimonials-box">
                    <div class="ct-testimonials-text">
                        <h3>Edward C.
                            <img src="assets/images/demo-content/stars.png" alt="stars" class="pull-right"> </h3>
                        <h6>Feb 7, 2015</h6>
                        <h5>Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
</figure>
<figure class="grid-item ct-isotope-item">
    <div class="ct-isotope-item-inner">
        <div class="ct-isotope-item__media">
            <div class="ct-testimonials ct-testimonials--sideMenu ct-u-paddingBottom70">
                <div class="ct-testimonials-box">
                    <div class="ct-testimonials-text">
                        <h3>Barry Balderston
                            <img src="assets/images/demo-content/stars.png" alt="stars" class="pull-right"> </h3>
                        <h6>Jan 9, 2015</h6>
                        <h5>Ut ac nibh quis mauris imperdiet hendrerit. Nunc quis risus rutrum, blandit ex at, vulputate nunc. Nunc maximus feugiat porttitor. </h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
</figure>

```

## Scripts:


```
    $(window).on('load', function() {


        /* Isotope */

        var isotope_gallery = function() {
            var isotope_filter, isotope_load;
            if ($().isotope) {
                isotope_gallery = $('.ct-isotope-gallery');
                isotope_filter = $('.ct-isotope-filtering button');
                isotope_load = $('#load-more');
                isotope_gallery.isotope({
                    itemSelector: '.ct-isotope-item',
                    percentPosition: true,
                    masonry: {
                        columnWidth: '.grid-sizer'
                    }
                });
                isotope_filter.on(clickEvent, function() {
                    var filter_value, that;
                    that = $(this);
                    isotope_filter.removeClass('is-active');
                    that.addClass('is-active');
                    filter_value = that.attr('data-filter');
                    return isotope_gallery.isotope({
                        filter: filter_value
                    });
                });
                return isotope_load.on(clickEvent, function() {
                    var load_name, load_page, response, that;
                    that = $(this);
                    load_name = that.attr('data-load-name');
                    load_page = parseInt(that.attr('data-load-page'));
                    response = '';
                    $.ajax({
                        type: 'GET',
                        url: load_name + load_page + '.html',
                        async: false,
                        success: function(value) {
                            response = value;
                            return isotope_gallery.isotope('insert', $(response));
                        },
                        complete: function() {
                            return $.ajax({
                                type: 'GET',
                                url: load_name + (load_page + 1) + '.html',
                                async: false,
                                error: function() {
                                    return that.parent().remove();
                                }
                            });
                        }
                    });
                    return that.attr('data-load-page', load_page + 1);
                });
            }
        };

        isotope_gallery();
    });


```


![](src/reviews-with-infinity-scroll.jpg)


# 7. Job Box
```

<div class="ct-jobBox">

    <h6>Feb 9, 2015</h6>
    <h4>B-level mechanical technician</h4>
    <a class="btn btn-black btn-sm" href="job_offer.html">apply now</a>

</div>

```
![](src/job-box.jpg)


# 8. Isotope - single



### Item

```
<figure class="grid-sizer grid-item ct-isotope-item" style="position: absolute; left: 0%; top: 0px;">
    <div class="ct-isotope-item-inner">
        <div class="ct-isotope-item__media">
            <a href="preventive_maintenance.html"><img src="assets/images/demo-content/gallery-01.jpg" alt="Gallery Item"></a>
            <div class="ct-isotope-item__inner">
                <a href="preventive_maintenance.html"><h3 class="ct-services-header">
                    Preventive maintenance
                </h3></a>
            </div>
        </div>
    </div>
</figure>

```
![](src/isotope-item.jpg)

##### JavaScripts - to samo co z review
```
$(window).on('load', function() {


    /* Isotope */

    var isotope_gallery = function() {
        var isotope_filter, isotope_load;
        if ($().isotope) {
            isotope_gallery = $('.ct-isotope-gallery');
            isotope_filter = $('.ct-isotope-filtering button');
            isotope_load = $('#load-more');
            isotope_gallery.isotope({
                itemSelector: '.ct-isotope-item',
                percentPosition: true,
                masonry: {
                    columnWidth: '.grid-sizer'
                }
            });
            isotope_filter.on(clickEvent, function() {
                var filter_value, that;
                that = $(this);
                isotope_filter.removeClass('is-active');
                that.addClass('is-active');
                filter_value = that.attr('data-filter');
                return isotope_gallery.isotope({
                    filter: filter_value
                });
            });
            return isotope_load.on(clickEvent, function() {
                var load_name, load_page, response, that;
                that = $(this);
                load_name = that.attr('data-load-name');
                load_page = parseInt(that.attr('data-load-page'));
                response = '';
                $.ajax({
                    type: 'GET',
                    url: load_name + load_page + '.html',
                    async: false,
                    success: function(value) {
                        response = value;
                        return isotope_gallery.isotope('insert', $(response));
                    },
                    complete: function() {
                        return $.ajax({
                            type: 'GET',
                            url: load_name + (load_page + 1) + '.html',
                            async: false,
                            error: function() {
                                return that.parent().remove();
                            }
                        });
                    }
                });
                return that.attr('data-load-page', load_page + 1);
            });
        }
    };

    isotope_gallery();
});


```
[Isotope Documentation can be found here](http://isotope.metafizzy.co/)
Files are bundled inside confetti.min.js & style.css

# 9. Fancy Contact form

```
<form action="assets/form/send.php" method="POST" data-email-subject="My Rota" class="ct-js-validate ct-formAppointment">
    <div class="form-header"><h4 class="text-uppercase">Personal information</h4></div>


    <div class="form-group">
        <label for="full_name" class="col-sm-2 control-label short-label">Your full name
            <span>*</span></label>

        <div class="col-sm-10">
            <input type="text" class="form-control ct-input" id="full_name" placeholder="" data-placeholder="Your full name" name="field[]" required="required">
        </div>
    </div>
    <div class="form-group">
        <label for="email" class="col-sm-2 control-label short-label">Email address
            <span>*</span></label>

        <div class="col-sm-10">
            <input type="email" class="form-control ct-input" id="email" placeholder="" data-placeholder="Email address" name="field[]" required="required">
        </div>
    </div>
    <div class="form-group">
        <label for="phone_number" class="col-sm-2 control-label short-label">Phone
            number<span>*</span></label>

        <div class="col-sm-10">
            <input type="text" class="form-control ct-input ct-input--short" data-placeholder="Phone number" id="phone_number" placeholder="" name="field[]" required="required">
        </div>
    </div>

    <div class="form-header"><h4 class="text-uppercase">Vehicle information</h4></div>


    <div class="form-group">
        <label for="year" class="col-sm-2 control-label short-label">Year<span>*</span></label>

        <div class="col-sm-10">
            <select class="form-control ct-input ct-input--short" id="year" data-placeholder="Year" name="field[]" required="required">
                <option>2011</option>
                <option>2012</option>
                <option>2013</option>
                <option>2014</option>
                <option>2015</option>
            </select>
        </div>

    </div>
    <div class="form-group">
        <label for="make" class="col-sm-2 control-label short-label">Make<span>*</span></label>

        <div class="col-sm-10">
            <select class="form-control ct-input" data-for="model" id="make" data-placeholder="Make" name="field[]" required="required">
                <option>Volkswagen</option>
                <option>Toyota</option>
                <option>Honda</option>
                <option>BMW</option>
                <option>Mercedes</option>
            </select>
        </div>
    </div>
    <div class="form-group">
        <label for="model" class="col-sm-2 control-label short-label">Model<span>*</span></label>

        <div class="col-sm-10">
            <select class="form-control ct-input" data-target="model" data-for="submodel" id="model" disabled="" data-placeholder="Model" name="field[]" required="required">
                <option value="" disabled="" selected="">Select model...</option>
                <option>1</option>
                <option>2</option>
                <option>3</option>
                <option>4</option>
                <option>5</option>
            </select>
        </div>
    </div>
    <div class="form-group">
        <label for="submodel" class="col-sm-2 control-label short-label">Submodel</label>

        <div class="col-sm-10">
            <select class="form-control ct-input" id="submodel" data-target="submodel" data-placeholder="Submodel" disabled="" name="field[]">
                <option value="" disabled="" selected="">Select submodel...</option>
                <option>1</option>
                <option>2</option>
                <option>3</option>
                <option>4</option>
                <option>5</option>
            </select>
        </div>
    </div>
    <div class="form-group">
        <label for="mileage" class="col-sm-2 control-label short-label">Mileage</label>

        <div class="col-sm-10">
            <select class="form-control ct-input" id="mileage" data-placeholder="Mileage" name="field[]">
                <option value="" disabled="" selected="">Select mileage...</option>
                <option>1</option>
                <option>2</option>
                <option>3</option>
                <option>4</option>
                <option>5</option>
            </select>
        </div>
    </div>

    <div class="form-header"><h4 class="text-uppercase">Appointment information</h4></div>


    <div class="form-group ">
        <label for="waiting" class="col-sm-2 control-label">Waiting
            or&nbsp;Drop&nbsp;off&nbsp;<span>*</span></label>

        <div class="col-sm-10">
            <select class="form-control ct-input ct-input--medium" id="waiting" data-placeholder="Waiting or Drop" name="field[]" required="required">
                <option value="" disabled="" selected="">Select an option...</option>
                <option>Waiting</option>
                <option>Drop off</option>
            </select>
        </div>
    </div>

    <div class="form-group">
        <label for="date" class="col-sm-2 control-label short-label">Date <span>*</span></label>

        <div class="col-sm-10">
            <input type="text" class="form-control ct-input ct-input--short datepicker" data-placeholder="Date" id="date" placeholder="" name="field[]" required="required">
        </div>
    </div>

    <div class="form-group ">
        <label for="time" class="col-sm-2 control-label short-label">Time<span>*</span></label>

        <div class="col-sm-10">
            <select class="form-control ct-input ct-input--short" id="time" data-placeholder="Time" name="field[]" required="required">
                <option value="" disabled="" selected="">Select time...</option>
                <option>1</option>
                <option>2</option>
                <option>3</option>
                <option>4</option>
                <option>5</option>
            </select>
        </div>
    </div>

    <div class="form-header"><h4 class="text-uppercase">Services requested</h4></div>


    <div class="form-group">

        <div class="container">
            <div class="row">

                <div class="col-md-1 col-xs-12 label-services">
                    <label class="label-checkbox">Services <span>*</span></label>
                </div>

                <div class="col-md-3">
                    <ul>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Preventive maintenance" name="field[]">
                            Preventive maintenance
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Oil change" name="field[]">
                            Oil change
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Brakes &amp; Brake repair" name="field[]">
                            Brakes &amp; Brake repair
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Tires &amp; Tire repair" name="field[]">
                            Tires &amp; Tire repair
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Mufflers &amp; Exhaust" name="field[]">
                            Mufflers &amp; Exhaust
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Steering &amp; Suspension" name="field[]">
                            Steering &amp; Suspension
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Batteries, Starters &amp; Charging" name="field[]">
                            Batteries, Starters &amp; Charging
                        </label></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <ul>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Engine cooling" name="field[]">
                            Engine cooling
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Climate control" name="field[]">
                            Climate control
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Check engine light" name="field[]">
                            Check engine light
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Belts &amp; Hoses" name="field[]">
                            Belts &amp; Hoses
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Lights, Wipers &amp; Accessories" name="field[]">
                            Lights, Wipers &amp; Accessories
                        </label></li>
                        <li><label class="checkbox-inline">
                            <input type="checkbox" value="" data-placeholder="Other" name="field[]">
                            Other
                        </label></li>
                    </ul>
                </div>
            </div>
        </div>

    </div>


    <div class="form-group">
        <label for="desc" class="col-lg-2 col-md-2 col-sm-12 control-label">Describe service
            request</label>

        <div class="col-lg-10 col-md-10 col-sm-12">
            <textarea class="form-control ct-input ct-input--wide" id="desc" data-placeholder="Describe service
            request" placeholder="" name="field[]">                                </textarea>
        </div>
    </div>

    <div class="btn-group ct-u-paddingBoth20">
        <button type="submit" class="btn btn-accent">schedule it now</button>
    </div>

    <div role="alert" class="successMessage alert alert-success alert-dismissible">
        <button type="button" data-dismiss="alert" aria-label="Close" class="close"><span aria-hidden="true">×</span>
        </button>
        Your Email has been sent successfully.
    </div>
    <div role="alert" class="errorMessage alert alert-danger alert-dismissible">
        <button type="button" data-dismiss="alert" aria-label="Close" class="close"><span aria-hidden="true">×</span>
        </button>
        Ups, something went wrong.
    </div>

</form>
```

##### JavaScripts
```

$(document).ready(function () {

    var dfor = $('[data-for]'),
        dtarget = $('[data-target]');

    dfor.each(function(){
       var that = $(this);

        that.change(function(){
           if(that.val()) {

               var index = -1,
                   dataFor = that.attr("data-for"),
                   counter = -1;


               dtarget.each(function(){
                   var thiz = $(this),
                       target = thiz.attr("data-target"),
                       ind = target.indexOf(dataFor);

                   counter++;

                   if(ind > -1) {
                      index = counter;
                      return false;
                   }
               });

               if(index > -1) {
                   $(dtarget[index]).prop('disabled', false);
               }
           }
        });
    });


    //datapicker


    var datapicker = $('.datepicker');

    if(datapicker.length) {
        datapicker.datepicker({
            format: 'mm/dd/yyyy'
        });
    }
});

```

![](src/fancy-form.jpg)

[Data picker Documentation can be found here](https://bootstrap-datepicker.readthedocs.org/en/latest/)
Files are bundled inside style.css and main.js



# 10. Pricing table

```
<article class="ct-pricingBox ct-u-backgroundWhite" data-height="555" style="min-height: 555px;">
    <div class="ct-pricingBox-header text-center ct-fw-700">
        <h3>Great savings</h3>

        <h1 class="text-uppercase ct-u-marginBoth10">15<span>%</span> off</h1>
        <h4>any service (excludes tax) with student ID</h4>
    </div>
    <div class="ct-pricingBox-desc">
        <h5>Brakes, Exhaust, Fluids, Factory maintenance service, Suspension, Wheel
            alignments,
            Belts, Hoses, Headlamps, Bulbs &amp; more.</h5>
    </div>
    <div class="ct-pricingBox-logo">
        <div class="media">
            <div class="media-left">
                <img class="media-object" src="assets/images/demo-content/logo.png" alt="logo">
            </div>
            <div class="media-body">
                <h6 class="ct-fw-400">Must present coupon. Most cars. Discount off
                    regular
                    price. Consumer pays all tax. One coupon per total invoice. Not
                    valid with other
                    offers.</h6>
            </div>
        </div>
    </div>
    <div class="ct-pricingBox-btn text-center">
        <div class="btn-group ct-u-paddingBoth10">
            <button type="button" class="btn"><img src="assets/images/demo-content/print.png" alt="print">
            </button>
            <button class="btn btn-accent">Print this coupon</button>
        </div>

    </div>
    <div class="ct-pricingBox-footer ct-fw-400">
        <h6 class="pull-left">Expires 11/16/2015</h6>
        <h6 class="pull-right">BD724NA</h6>
    </div>
</article>
```
![](src/pricing-table.jpg)




# 11. Navigation

```
<nav class="navbar ct-u-backgroundLightGray hidden-xs">
    <div class="container ct-navbar-container">

        <div class="row">

            <ul class="navbar-left ct-u-paddingBoth20 col-lg-9">
                <li class="active"><a href="index.html"><span>Home</span></a></li>
                <li class="dropdown"><a href="#" data-toggle="dropdown" class="dropdown-toggle"><span>About us</span><span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        <li><a href="about-us.html">Who we are</a></li>
                        <li><a href="history.html">Our history</a></li>
                        <li><a href="team.html">Meet the team</a></li>
                        <li><a href="reviews.html">Reviews</a></li>
                        <li><a href="careers.html">Careers</a></li>
                    </ul>
                </li>
                <li class="dropdown"><a href="#" data-toggle="dropdown" class="dropdown-toggle"><span>Services</span><span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        <li><a href="services_overview.html">Services overview</a></li>
                        <li><a href="preventive_maintenance.html">Preventive Maintenance</a></li>
                        <li><a href="oil_change.html">Oil Change</a></li>
                        <li><a href="tires.html">Tires &amp; Tire Repair</a></li>
                        <li><a href="steering.html">Brakes &amp; Brake Repair</a></li>
                        <li><a href="mufflers.html">Mufflers &amp; Exhaust</a></li>
                        <li><a href="steering.html">Steering &amp; Suspension</a></li>
                        <li><a href="batteries.html">Batteries, Starters &amp; Charging</a></li>
                        <li><a href="climate.html">Climate Control</a></li>
                        <li><a href="belts.html">Belts &amp; Hoses</a></li>
                        <li><a href="engine.html">Engine Cooling</a></li>
                        <li><a href="check_engine.html">Check Engine Light</a></li>
                        <li><a href="lights.html">Lights, Wipers &amp; Accessories</a></li>
                    </ul>
                </li>
                <li><a href="appointments.html"><span>Appointments</span></a></li>
                <li><a href="coupons.html"><span>Coupons</span></a></li>
                <li><a href="faq.html"><span>Faq</span></a></li>
                <li class="dropdown"><a href="#" data-toggle="dropdown" class="dropdown-toggle"><span>Blog</span><span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        <li><a href="blog.html">Blog</a></li>
                        <li><a href="blog-post.html">Single post</a></li>
                    </ul>
                </li>
                <li><a href="contact.html"><span>Contact us</span></a></li>
            </ul>

            <button class="btn-search ct-tablet-searcher"><i class="fa fa-search"></i></button>

            <div class="col-lg-3 ct-parent ct-desktop-searcher">
                <div class="ct-navSearcher ct-child" style="width: 491px;">
                    <form class="navbar-form navbar-form--default pull-left" role="search">
                        <div class="form-group">
                            <button class="btn-search"><i class="fa fa-search"></i></button>
                            <input type="text" class="form-control empty ct-u-backgroundDarkGray" id="iconified" placeholder="Search">
                        </div>
                    </form>
                </div>
            </div>

        </div>
    </div>
    </nav>
```

##### Screenshots
1. Default

  ![](src/navbar.jpg)



# 12. Pagination

```
<div class="ct-pagination pagination-centered">
    <ul>
        <li class="pull-left"><a href="#"><i class="fa fa-caret-left"></i> prev page</a></li>
        <li class="ct-pagination--numbers"><a href="#">1</a></li>
        <li class="active ct-pagination--numbers"><a href="#">2</a></li>
        <li class="ct-pagination--numbers"><a href="#">3</a></li>
        <li class="disabled ct-pagination--numbers"><a href="#">...</a></li>
        <li class="ct-pagination--numbers"><a href="#">12</a></li>
        <li class="pull-right"><a href="#">next page <i class="fa fa-caret-right"></i></a></li>
    </ul>
</div>
```
![](src/blog-pagination.jpg)




# 13. Sliders

```
<div class="ct-slick ct-js-slick">
  <div class="item">...</div>
  ...
  <div class="item">...</div>
</div>
```
[Slick Documentation can be found here.](http://kenwheeler.github.io/slick/)
Files are bundled inside confetti.min.js & style.css


### Main Slider
```
<div class="ct-slick ct-js-slick">

    <div class="ct-slick ct-js-slick ct-mainSlider ct-slick-arrow--type1 ct-slick-dots--type1" data-autoplay="false"
         data-arrows="true" data-dots="true" data-items="1" data-height="550">
        <div class="item" data-background="assets/images/demo-content/background-1.jpg" data-height="550">
            <div class="item-inner container">
                <div class="row">
                    <div class="col-lg-5 col-md-6 col-sm-8 col-xs-10 slider-header">
                        <h1 class="ct-fw-700">We’ll have you up and running in no time</h1>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-5 col-md-6  ct-u-marginTop10">
                        <a href="about-us.html" class="btn btn-white btn-slider--motive">Learn how</a>
                        <span>or</span>
                        <a href="appointments.html" class="btn btn-white">Make appointment</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="item" data-background="assets/images/demo-content/background-1.jpg ">
            <div class="item-inner container">
                <div class="row">
                    <div class="col-lg-5 col-md-6 col-sm-8 col-xs-10 slider-header">
                        <h1 class="ct-fw-700">We’ll have you up and running in no time</h1>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-5 col-md-6 ct-u-marginTop10">
                        <a href="about-us.html" class="btn btn-white btn-slider--motive">Learn how</a>
                        <span>or</span>
                        <a href="appointments.html" class="btn btn-white">Make appointment</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="item" data-background="assets/images/demo-content/background-1.jpg">
            <div class="item-inner container">
                <div class="row">
                    <div class="col-lg-5 col-md-6 col-sm-8 col-xs-10 slider-header">
                        <h1 class="ct-fw-700">We’ll have you up and running in no time</h1>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-5 col-md-6 ct-u-marginTop10">
                        <a href="about-us.html" class="btn btn-white btn-slider--motive">Learn how</a>
                        <span>or</span>
                        <a href="appointments.html" class="btn btn-white">Make appointment</a>
                    </div>
                </div>
            </div>
        </div>

    </div>
  ...

</div>
```
![](src/slick.jpg)


[Slick Documentation can be found here](http://kenwheeler.github.io/slick/)
Files are bundled inside style.css and main.js


# 14. Light Gallery


```

<div class="ct-js-lightGallery">
    <a href="assets/images/demo-content/pic_1.jpg">
        <div class="item">
            <div class="item-inner">
                <img src="assets/images/demo-content/pic_1.jpg" alt="">
            </div>
        </div>
    </a>
    <a href="assets/images/demo-content/pic_2.jpg">
        <div class="item">
            <div class="item-inner">
                <img src="assets/images/demo-content/pic_2.jpg" alt="">
            </div>
        </div>
    </a>
    <a href="assets/images/demo-content/pic_3.jpg">
        <div class="item">
            <div class="item-inner">
                <img src="assets/images/demo-content/pic_3.jpg" alt="">
            </div>
        </div>
    </a>

    <a href="assets/images/demo-content/pic_4.jpg">
        <div class="item">
            <div class="item-inner">
                <img src="assets/images/demo-content/pic_4.jpg" alt="">
            </div>
        </div>
    </a>
    <a href="assets/images/demo-content/pic_5.jpg">
        <div class="item">
            <div class="item-inner">
                <img src="assets/images/demo-content/pic_5.jpg" alt="">
            </div>
        </div>
    </a>
    <a href="assets/images/demo-content/pic_6.jpg">
        <div class="item">
            <div class="item-inner">
                <img src="assets/images/demo-content/pic_6.jpg" alt="">
            </div>
        </div>
    </a>
</div>

```


![](src/light-gallery.jpg)

[LightGallery Documentation can be found here.](http://sachinchoolur.github.io/lightGallery/docs/)
Files are bundled inside confetti.min.js & style.css


# 15. Map

```
 <div data-address="Tattersalls Ln, Melbourne" class="ct-googleMap ct-js-googleMap ct-u-backgroundLightBlack"></div>

```


### Scripts

```

<script id="googleMap" type="text/javascript" src="https://maps.googleapis.com/maps/api/js?"></script>


    and inside main.js

  // Google map // -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

        var mapSelector = $(".ct-js-googleMap");

        if(mapSelector.length) {
            var marker_address = mapSelector.attr("data-address");
            var map, bounds, marker, mapStyle, marker_icon;
            mapStyle = [{
                "featureType": "administrative",
                "elementType": "labels.text.fill",
                "stylers": [{"color": "#444444"}]
            }, {"featureType": "landscape", "elementType": "all", "stylers": [{"color": "#f2f2f2"}]}, {
                "featureType": "poi",
                "elementType": "all",
                "stylers": [{"visibility": "off"}]
            }, {
                "featureType": "road",
                "elementType": "all",
                "stylers": [{"saturation": -100}, {"lightness": 45}]
            }, {
                "featureType": "road.highway",
                "elementType": "all",
                "stylers": [{"visibility": "simplified"}]
            }, {
                "featureType": "road.arterial",
                "elementType": "labels.icon",
                "stylers": [{"visibility": "off"}]
            }, {"featureType": "transit", "elementType": "all", "stylers": [{"visibility": "off"}]}, {
                "featureType": "water",
                "elementType": "all",
                "stylers": [{"color": "#425a68"}, {"visibility": "on"}]
            }]
            map = new google.maps.Map(mapSelector[0], {
                center: new google.maps.LatLng(0, 0),
                mapTypeId: google.maps.MapTypeId.ROADMAP, //MapTypeId.ROADMAP, MapTypeId.SATELLITE, MapTypeId.HYBRID, MapTypeId.TERRAIN
                styles: mapStyle,
                scrollwheel: false,
                draggable: true,
                zoom: 16
            });
            bounds = new google.maps.LatLngBounds();
            var geocoder = new google.maps.Geocoder();
            geocoder.geocode({'address': marker_address}, function (results, status) {
                if (status === google.maps.GeocoderStatus.OK) {
                    var image = 'assets/images/marker_icon.png';
                    marker = new google.maps.Marker({
                        position: new google.maps.LatLng(results[0].geometry.location.lat(), results[0].geometry.location.lng()),
                        map: map,
                        icon: image
                    });

                    bounds.extend(marker.position);
                    map.setCenter(results[0].geometry.location);
                } else {
                    alert('Geocode was not successful for the following reason: ' + status);
                }
            });
        }

```

![](src/map.jpg)





# 16. Button

```

<a href="#" class="btn btn-motive">Button</a>

```


## variables

### types

- btn-success
- btn-danger
- btn-warning
- btn-info
- btn-primary
- btn-default
- btn-motive


### size

- btn-sm
- btn (only)
- btn-lg


![](src/buttons.jpg)











