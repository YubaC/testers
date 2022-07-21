<style>
    body,
    div {
        margin: 0;
        padding: 0;
    }
    
    #box>a {
        display: none;
    }
    
    #box>a:first-of-type {
        display: block;
    }
    
    #box>a:target {
        display: none;
    }
    
    #box>a:target+a {
        display: block;
    }
</style>

<div id="box">

<a href="#a" id="a">
    
<p>我是P1的内容</p>
        </a>

<a href="#b" id="b">
    
<p>我是P2的内容</p>
        </a>
</div>