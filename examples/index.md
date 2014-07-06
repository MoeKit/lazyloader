# 使用

---

````html
<style>
    img {width:200px;height:500px;border:green;}
</style>

<div id="loading-box"></div>
<p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p>
<p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p>
<p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p>
<p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p><p>lazy</p>

<img data-original="http://placehold.it/200X500&text=hell0o"/>
<br/>

<img data-original="http://placehold.it/200X501&text=hello1"/>

<br/>

<img data-original="http://placehold.it/200X502&text=hello2"/>

<br/>

<img data-original="http://placehold.it/200X503&text=hello3"/>

<br/>

<img data-original="http://placehold.it/200X504&text=hello4"/>

<br/>

<img data-original="http://placehold.it/200X505&text=hello5"/>

<br/>

<img data-original="http://placehold.it/200X506&text=hello6"/>

<br/>


````


````javascript
seajs.use('index',function(Lazyloader){
   var lazy= new Lazyloader({
        target:'img',
        effect:'fadeIn',
        event : "click"
    }).on('all',function(event,a){
        //console.log(event,a);
    })
    //console.log(lazy);
});
````


