---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<div>
    <div class="main-title">
        <lottie-player src="{{ "/assets/animation/home_product.json" | relative_url }}" background="transparent" speed="1"  direction="1" mode="normal" autoplay style="height: 500px"></lottie-player>
        <h1 >PROUDLY MADE FROM SARAWAK</h1>
        <div class="logo-list">
            <img src="{{"/assets/images/halal-logo.png" | relative_url}}" style="height : 100px"/>
            <img src="{{"/assets/images/produk-muslim.png" | relative_url}}" style="height : 100px">
        </div>
    </div>
    <div class="store-list-div">
        <div class="content-wrapper">
            <h1>Discover the natural sweetness of Gula Apong</h1>
            <div class="store-description">
            A unique and nutrient-rich sugar derived from the sap of the Nipah Palm. Sustainably harvested, it’s perfect for traditional Southeast Asian recipes, offering a healthy, natural alternative to refined sugars. Find us at these stores and online platforms.
            </div >
            <div>
                <p> East Malaysia  </p>
            </div>
            <div class="store-list">
             {% for i in (1..5) %}
                <img src="{{"/assets/logo"| append: i | append: '.png'  relative_url}}" class="store-logo" />
             {% endfor %}
            </div>
            <div>
                <p> West Malaysia  </p>
            </div>
            <div class="store-list">
             {% for i in (1..11) %}
                <img src="{{"/assets/logo-west"| append: i | append: '.png'  relative_url}}" class="store-logo" />
             {% endfor %}
            </div>
        </div>
    </div>
    <div class="innovate-div">
        <div class="header">
            <h1> WE INNOVATE AND TRANSFORM THE PRODUCTION! </h1>
        </div>
        <div class="innovate-row">
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/transform1.png" | relative_url}}" >
                    <img src="{{"/assets/innovate3-p.png" | relative_url}}"  >
                </div>   
                <div class="description">
                    <h2>New harvesting technique</h2>
                    <p> We innovate new technique to collect the Nira and improved the hygiene during the process</p>
                </div>
            </div>
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/innovate4.png" | relative_url}}"   >
                    <img src="{{"/assets/innovate8-p.png" | relative_url}}" >
                </div>   
                <div class="description">
                    <h2>Hygienic Cooking Process</h2>
                    <p> New technique of cooking and preparing with in a community centre</p>
                </div>
            </div>
        </div>
        <div class="innovate-row">
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/innovate9.jpg" | relative_url}}"  >
                    <img src="{{"/assets/innovate12-p.png" | relative_url}}">
                </div>   
                <div class="description">
                    <h2>Attracting Packinging</h2>
                    <p>Transforming new packaging for more attraction in global market </p>
                </div>
            </div>
            <div class="innovate-col">
                <div class="compare-list">
                    <img src="{{"/assets/innovate13.jpg" | relative_url}}"    >
                    <img src="{{"/assets/innovate14.png" | relative_url}}"  >
                </div>   
                <div class="description">
                    <h2>Global supply chain</h2>
                    <p>Easily available and distributed thorought the market supply chain</p>
                </div>
            </div>
        </div>
    </div>
    
</div>