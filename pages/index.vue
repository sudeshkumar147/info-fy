<template>
  <div>
   
    <div class="">
      <div class="container">
          <div class="row">
            <div class="col-md-6" v-for="(slid,index) in saids" :key="index">
                <div class="post post-thumb">
                  <a class="post-img" href="blog-post.html"><img src="~assets/img/post-1.jpg" alt=""></a>
                  <div class="post-body">
                      <div class="post-meta">
                        <a class="post-category cat-2" href="#" v-for="(c,index) in slid.category" :key="index">{{ c.name }}</a>
                        <span class="post-date">{{ slid.createdAt | formateDate }}</span>
                      </div>
                      <h3 class="post-title"><a href="blog-post.html">{{ slid.title }}</a></h3>
                  </div>
                </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
                <div class="section-title">
                  <h2>Recent Posts</h2>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                  <a class="post-img" href="blog-post.html"><img src="~assets/img/post-3.jpg" alt=""></a>
                  <div class="post-body">
                      <div class="post-meta">
                        <a class="post-category cat-1" href="category.html">Web Design</a>
                        <span class="post-date">March 27, 2018</span>
                      </div>
                      <h3 class="post-title"><a href="blog-post.html">Pagedraw UI Builder Turns Your Website Design Mockup Into Code Automatically</a></h3>
                  </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                  <a class="post-img" href="blog-post.html"><img src="~assets/img/post-4.jpg" alt=""></a>
                  <div class="post-body">
                      <div class="post-meta">
                        <a class="post-category cat-2" href="category.html">JavaScript</a>
                        <span class="post-date">March 27, 2018</span>
                      </div>
                      <h3 class="post-title"><a href="blog-post.html">Chrome Extension Protects Against JavaScript-Based CPU Side-Channel Attacks</a></h3>
                  </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                  <a class="post-img" href="blog-post.html"><img src="~assets/img/post-5.jpg" alt=""></a>
                  <div class="post-body">
                      <div class="post-meta">
                        <a class="post-category cat-3" href="category.html">Jquery</a>
                        <span class="post-date">March 27, 2018</span>
                      </div>
                      <h3 class="post-title"><a href="blog-post.html">Ask HN: Does Anybody Still Use JQuery?</a></h3>
                  </div>
                </div>
            </div>
            <div class="clearfix visible-md visible-lg"></div>
            <div class="col-md-4">
                <div class="post">
                  <a class="post-img" href="blog-post.html"><img src="~assets/img/post-6.jpg" alt=""></a>
                  <div class="post-body">
                      <div class="post-meta">
                        <a class="post-category cat-2" href="category.html">JavaScript</a>
                        <span class="post-date">March 27, 2018</span>
                      </div>
                      <h3 class="post-title"><a href="blog-post.html">Why Node.js Is The Coolest Kid On The Backend Development Block!</a></h3>
                  </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                  <a class="post-img" href="blog-post.html"><img src="~assets/img/post-1.jpg" alt=""></a>
                  <div class="post-body">
                      <div class="post-meta">
                        <a class="post-category cat-4" href="category.html">Css</a>
                        <span class="post-date">March 27, 2018</span>
                      </div>
                      <h3 class="post-title"><a href="blog-post.html">CSS Float: A Tutorial</a></h3>
                  </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                  <a class="post-img" href="blog-post.html"><img src="~assets/img/post-2.jpg" alt=""></a>
                  <div class="post-body">
                      <div class="post-meta">
                        <a class="post-category cat-1" href="category.html">Web Design</a>
                        <span class="post-date">March 27, 2018</span>
                      </div>
                      <h3 class="post-title"><a href="blog-post.html">Tell-A-Tool: Guide To Web Design And Development Tools</a></h3>
                  </div>
                </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-8">
                <div class="row">
                  <div class="col-md-12">
                      <div class="post post-thumb">
                        <a class="post-img" href="blog-post.html"><img src="~assets/img/post-2.jpg" alt=""></a>
                        <div class="post-body">
                            <div class="post-meta">
                              <a class="post-category cat-3" href="category.html">Jquery</a>
                              <span class="post-date">March 27, 2018</span>
                            </div>
                            <h3 class="post-title"><a href="blog-post.html">Ask HN: Does Anybody Still Use JQuery?</a></h3>
                        </div>
                      </div>
                  </div>
                  <div class="col-md-6">
                      <div class="post">
                        <a class="post-img" href="blog-post.html"><img src="~assets/img/post-1.jpg" alt=""></a>
                        <div class="post-body">
                            <div class="post-meta">
                              <a class="post-category cat-4" href="category.html">Css</a>
                              <span class="post-date">March 27, 2018</span>
                            </div>
                            <h3 class="post-title"><a href="blog-post.html">CSS Float: A Tutorial</a></h3>
                        </div>
                      </div>
                  </div>
                  <div class="col-md-6">
                      <div class="post">
                        <a class="post-img" href="blog-post.html"><img src="~assets/img/post-2.jpg" alt=""></a>
                        <div class="post-body">
                            <div class="post-meta">
                              <a class="post-category cat-1" href="category.html">Web Design</a>
                              <span class="post-date">March 27, 2018</span>
                            </div>
                            <h3 class="post-title"><a href="blog-post.html">Tell-A-Tool: Guide To Web Design And Development Tools</a></h3>
                        </div>
                      </div>
                  </div>
                  <div class="clearfix visible-md visible-lg"></div>
                  <div class="col-md-6">
                      <div class="post">
                        <a class="post-img" href="blog-post.html"><img src="~assets/img/post-4.jpg" alt=""></a>
                        <div class="post-body">
                            <div class="post-meta">
                              <a class="post-category cat-2" href="category.html">JavaScript</a>
                              <span class="post-date">March 27, 2018</span>
                            </div>
                            <h3 class="post-title"><a href="blog-post.html">Chrome Extension Protects Against JavaScript-Based CPU Side-Channel Attacks</a></h3>
                        </div>
                      </div>
                  </div>
                  <div class="col-md-6">
                      <div class="post">
                        <a class="post-img" href="blog-post.html"><img src="~assets/img/post-5.jpg" alt=""></a>
                        <div class="post-body">
                            <div class="post-meta">
                              <a class="post-category cat-3" href="category.html">Jquery</a>
                              <span class="post-date">March 27, 2018</span>
                            </div>
                            <h3 class="post-title"><a href="blog-post.html">Ask HN: Does Anybody Still Use JQuery?</a></h3>
                        </div>
                      </div>
                  </div>
                  <div class="clearfix visible-md visible-lg"></div>
                  <div class="col-md-6">
                      <div class="post">
                        <a class="post-img" href="blog-post.html"><img src="~assets/img/post-3.jpg" alt=""></a>
                        <div class="post-body">
                            <div class="post-meta">
                              <a class="post-category cat-1" href="category.html">Web Design</a>
                              <span class="post-date">March 27, 2018</span>
                            </div>
                            <h3 class="post-title"><a href="blog-post.html">Pagedraw UI Builder Turns Your Website Design Mockup Into Code Automatically</a></h3>
                        </div>
                      </div>
                  </div>
                  <div class="col-md-6">
                      <div class="post">
                        <a class="post-img" href="blog-post.html"><img src="~assets/img/post-4.jpg" alt=""></a>
                        <div class="post-body">
                            <div class="post-meta">
                              <a class="post-category cat-2" href="category.html">JavaScript</a>
                              <span class="post-date">March 27, 2018</span>
                            </div>
                            <h3 class="post-title"><a href="blog-post.html">Chrome Extension Protects Against JavaScript-Based CPU Side-Channel Attacks</a></h3>
                        </div>
                      </div>
                  </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="aside-widget">
                  <div class="section-title">
                      <h2>Most Read</h2>
                  </div>
                  <div class="post post-widget">
                      <a class="post-img" href="blog-post.html"><img src="~assets/img/widget-1.jpg" alt=""></a>
                      <div class="post-body">
                        <h3 class="post-title"><a href="blog-post.html">Tell-A-Tool: Guide To Web Design And Development Tools</a></h3>
                      </div>
                  </div>
                  <div class="post post-widget">
                      <a class="post-img" href="blog-post.html"><img src="~assets/img/widget-2.jpg" alt=""></a>
                      <div class="post-body">
                        <h3 class="post-title"><a href="blog-post.html">Pagedraw UI Builder Turns Your Website Design Mockup Into Code Automatically</a></h3>
                      </div>
                  </div>
                  <div class="post post-widget">
                      <a class="post-img" href="blog-post.html"><img src="~assets/img/widget-3.jpg" alt=""></a>
                      <div class="post-body">
                        <h3 class="post-title"><a href="blog-post.html">Why Node.js Is The Coolest Kid On The Backend Development Block!</a></h3>
                      </div>
                  </div>
                  <div class="post post-widget">
                      <a class="post-img" href="blog-post.html"><img src="~assets/img/widget-4.jpg" alt=""></a>
                      <div class="post-body">
                        <h3 class="post-title"><a href="blog-post.html">Tell-A-Tool: Guide To Web Design And Development Tools</a></h3>
                      </div>
                  </div>
                </div>
                <div class="aside-widget">
                  <div class="section-title">
                      <h2>Featured Posts</h2>
                  </div>
                  <div class="post post-thumb">
                      <a class="post-img" href="blog-post.html"><img src="~assets/img/post-2.jpg" alt=""></a>
                      <div class="post-body">
                        <div class="post-meta">
                            <a class="post-category cat-3" href="category.html">Jquery</a>
                            <span class="post-date">March 27, 2018</span>
                        </div>
                        <h3 class="post-title"><a href="blog-post.html">Ask HN: Does Anybody Still Use JQuery?</a></h3>
                      </div>
                  </div>
                  <div class="post post-thumb">
                      <a class="post-img" href="blog-post.html"><img src="~assets/img/post-1.jpg" alt=""></a>
                      <div class="post-body">
                        <div class="post-meta">
                            <a class="post-category cat-2" href="category.html">JavaScript</a>
                            <span class="post-date">March 27, 2018</span>
                        </div>
                        <h3 class="post-title"><a href="blog-post.html">Chrome Extension Protects Against JavaScript-Based CPU Side-Channel Attacks</a></h3>
                      </div>
                  </div>
                </div>
                <div class="aside-widget text-center">
                  <a href="#" style="display: inline-block;margin: auto;">
                  <img class="img-responsive" src="~assets/img/ad-1.jpg" alt="">
                  </a>
                </div>
            </div>
          </div>
      </div>
    </div>
  </div>  
</template>

<script>
const moment = require('moment');
  export default {
    data() {      
      return {
        saids: [],
      }
    },

    mounted() {
      this.getSlidData();
    },

    methods: {
      getSlidData() {
        this.$axios.post('user/blog/slid').then(result => {
        this.saids = result.data.data
        console.log(result.data.data)
      });
      }
    },
    filters: {
      formateDate: function(value) {
        // return value
        var timestamp = moment.unix(1293683278);
        return timestamp.format("LL");
      }
    }
  }
</script>

<style>

</style>
