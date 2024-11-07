---
layout: page
permalink: /research/
title: ''
pubs: null
published: true
---


<!-- Styles your button (this is a black square with white text) -->
<style>
  .back-to-top {
    background-color: #000000;
    color: #FFFFFF;
    opacity: 0;
    transition: opacity .6s ease-in-out;
    z-index: 999;
    position: fixed;
    right: 20px;
    bottom: 20px;
    width: 50px;
    height: 50px;
    box-sizing: border-box;
    border-radius: 0%;
  }

  a.back-to-top {
    font-weight: 1000;
    letter-spacing: 2px;
    font-size: 14px;
    text-transform: uppercase;
    text-align: center;
    line-height: 1.6;
    padding-left: 2px;
    padding-top: 14px;
  }

  .back-to-top:hover, .back-to-top:focus, .back-to-top:visited {
    color: #FFFFFF;
  }

  .back-to-top.show {
    opacity: 1;
  }
</style>

<!-- Adds the back to top link to your website -->
<a href="#" id="back-to-top" class="back-to-top" style="display: inline;">Top</a>

<!-- Fades in the button when you scroll down -->
<script>
  var link = document.getElementById("back-to-top");
  var amountScrolled = 250;

  window.addEventListener('scroll', function(e) {
      if ( window.pageYOffset > amountScrolled ) {
          link.classList.add('show');
      } else {
          link.className = 'back-to-top';
      }
  });  
<!-- Scrolls to Top -->
  link.addEventListener('click', function(e) {
      e.preventDefault();

      var distance = 0 - window.pageYOffset;
      var increments = distance/(500/16);
      function animateScroll() {
          window.scrollBy(0, increments);
          if (window.pageYOffset <= document.body.offsetTop) {
              clearInterval(runAnimation);
          }
      };
      // Loop the animation function
      var runAnimation = setInterval(animateScroll, 16);
  });
</script>


# Research

[Publications](#pubs) <br> [Working Paper](#wp)


### <a id="pubs"></a>Published and Accepted Papers ###

**Do Option Characteristics Predict the Underlying Stock Returns in the Cross-Section?**  with [Xiaoxiao Tang](https://sites.google.com/view/xiaoxiaotang-homepage){:target="_blank"}, [Rasmus Varneskov](https://sites.google.com/site/rasmusvarneskov/home){:target="_blank"} and [Guofu Zhou](http://apps.olin.wustl.edu/faculty/zhou/){:target="_blank"}   
_Management Science_, accepted for publication.
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3795486){:target="_blank"}

**Missing Data in Asset Pricing Panels** with [Joachim Freyberger](https://sites.google.com/view/joachimfreyberger/home){:target="_blank"} and Bjoern Hoeppner and [Michael Weber](https://faculty.chicagobooth.edu/michael-weber/){:target="_blank"}      
_Review of Financial Studies_, accepted for publication.    
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3932438){:target="_blank"}

**Arbitrage Portfolios**  with [Soohun Kim](https://soohunkimi.github.io/myWebpage/) and [Robert Korajczyk](https://www.kellogg.northwestern.edu/faculty/directory/korajczyk_robert.aspx){:target="_blank"}  
_Review of Financial Studies_, (2021), 34, 2813–2856.  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3263001){:target="_blank"}
[[RFS]](https://doi.org/10.1093/rfs/hhaa102){:target="_blank"}
[[Code]](https://github.com/aneuhierl/arbitrage-portfolios){:target="_blank"}

**Frequency Dependent Risk** 
with [Rasmus Varneskov](https://sites.google.com/site/rasmusvarneskov/home){:target="_blank"}  
_Journal of Financial Economics_, (2021), 140, 644-675.   
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3260167){:target="_blank"}
[[JFE]](https://doi.org/10.1016/j.jfineco.2021.01.007){:target="_blank"}

**Estimating the Anomaly Base Rate**  with [Alex Chinco](http://www.alexchinco.com/){:target="_blank"} and [Michael Weber](https://faculty.chicagobooth.edu/michael-weber/){:target="_blank"}  
_Journal of Financial Economics_, (2021), 140, 101-126.  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3344499){:target="_blank"}
[[JFE]](https://doi.org/10.1016/j.jfineco.2020.12.003){:target="_blank"}

**Data Snooping in Equity Premium Prediction**  with [Hubert Dichtl](https://www.dichtl-research-consulting.de/?lang=en#home){:target="_blank"}, Wolfgang Drobetz and Viktoria-Sophie Wendt  
_International Journal of Forecasting_, (2021), 37, 72-94.    
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2972011){:target="_blank"}
[[IJF]](https://doi.org/10.1016/j.ijforecast.2020.03.002){:target="_blank"}

**Dissecting characteristics nonparametrically** with [Joachim Freyberger](https://sites.google.com/view/joachimfreyberger/home){:target="_blank"} and [Michael Weber](https://faculty.chicagobooth.edu/michael-weber/){:target="_blank"}  
_Review of Financial Studies_, (2020), 33, 2326-2377.  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2820700){:target="_blank"} [[RFS]](https://doi.org/10.1093/rfs/hhz123){:target="_blank"}

**Monetary Policy Communication, Policy Slope and the Stock Market**  with [Michael Weber](https://faculty.chicagobooth.edu/michael-weber/){:target="_blank"}  
_Journal of Monetary Economics_, (2019), 108, 140-155.  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2748290){:target="_blank"} [[JME]](https://doi.org/10.1016/j.jmoneco.2019.08.005){:target="_blank"}

**Market Reaction to Corporate Press Releases**   with [Anna Scherbina](http://people.brandeis.edu/~ascherbina/index.html){:target="_blank"} and [Bernd Schlusche](https://sites.google.com/site/schlusche/home){:target="_blank"}  
_Journal of Financial and Quantitative Analysis_, (2013), 48, 1207-1240.  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1556532){:target="_blank"} [[JFQA]](https://doi.org/10.1017/S002210901300046X){:target="_blank"}

**Growth Optimal Investment Strategy: The Impact of Reallocation Frequency and Heavy Tails**  with Günter Bamberg  
__German Economic Review__, (2012), 13, 228–240.  
[[SSRN]]() [[GER]](https://doi.org/10.1111/j.1468-0475.2011.00553.x){:target="_blank"}

**Data Snooping and Market-Timing Rule Performance**  with [Bernd Schlusche](https://sites.google.com/site/schlusche/home){:target="_blank"}  
_Journal of Financial Econometrics_, (2011), 9, 550-587.  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1343896){:target="_blank"} [[JFEC]](https://doi.org/10.1093/jjfinec/nbq032){:target="_blank"}

**On the non-existence of conditional value-at-risk under heavy tails and short sales**  with Günter Bamberg  
_OR Spectrum_, (2010), 32, 49-60.  
[[SSRN]]() [[ORS]](https://doi.org/10.1007/s00291-008-0138-3){:target="_blank"}


### <a id="wp"></a>Working Paper ###
**Does Noise Hurt Economic Forecasts?**  with [Yuan Liao](https://econweb.rutgers.edu/yl1114/){:target="_blank"}, [Xinjie Ma](https://xinjiema.super.site){:target="_blank"} and [Zhentao Shi](http://zhentaoshi.github.io){:target="_blank"}   
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4659309){:target="_blank"}

**Timing the Factor Zoo**  with [Otto Randl](https://sites.google.com/site/ottorandl/){:target="_blank"}, [Christoph Reschenhofer](https://www.christophreschenhofer.com/home){:target="_blank"} and [Josef Zechner](https://www.vgsf.ac.at/faculty/vgsf-faculty/josef-zechner/){:target="_blank"}   
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4376898){:target="_blank"}

**Robust Stock Index Return Predictions Using Deep Learning**  with [Ravi Jagannathan](https://www.kellogg.northwestern.edu/faculty/directory/jagannathan_ravi.aspx){:target="_blank"} and [Yuan Liao](https://econweb.rutgers.edu/yl1114/){:target="_blank"}  
[[SSRN]]([https://www.ssrn.com](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4890466)){:target="_blank"}

**Structural Deep Learning in Conditional Asset Pricing**  with [Jianqing Fan](https://fan.princeton.edu){:target="_blank"}, [Tracy Ke](https://zke.fas.harvard.edu){:target="_blank"} and [Yuan Liao](https://econweb.rutgers.edu/yl1114/){:target="_blank"}  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4117882){:target="_blank"}
  
**Inferences About Properties of Earnings With Disappearing Data**  with [Peter Easton](https://mendoza.nd.edu/mendoza-directory/profile/?slug=peter-easton){:target="_blank"}, [Martin Kapons](https://research.tilburguniversity.edu/en/persons/martin-kapons){:target="_blank"} and [Peter Kelly](https://sites.google.com/a/alumni.nd.edu/peter/research){:target="_blank"}  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3040354){:target="_blank"}

**Time Series Momentum around FOMC Meetings**  with [Michael Weber](https://faculty.chicagobooth.edu/michael-weber/){:target="_blank"}  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3030126){:target="_blank"}

**Liquidity Timing in Commodity Markets and the Impact of Financialization**  with Andrew Thompson  
[[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2682698){:target="_blank"}
