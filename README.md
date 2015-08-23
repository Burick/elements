LESS Elements
=============

A set of useful mixins for LESS, the CSS pre-processor: <http://lesscss.org>

More information and usage examples over at: <http://lesselements.com>

Examples page of all the mixins here: <http://lesselements.com/tests>

Oreolek has a good fork with the mixins organized under namespaces here: https://github.com/Oreolek/elements 
I recommend going with that if you use other frameworks like Bootstrap to avoid clashes.

TextMate bundle: <https://github.com/juanghurtado/less-elements.tmbundle>

Ruby gem to work with Rails: <https://github.com/krasnoukhov/lesselements-rails> 

License: This work is dedicated to the public domain and is free for all uses, commercial or otherwise. No form of credit required.

1 .gradient(@color: #F5F5F5, @start: #EEE, @stop: #FFF)    
2 .bw-gradient(@color: #F5F5F5, @start: 0, @stop: 255)    
3 .bordered(@top-color: #EEE, @right-color: #EEE, @bottom-color: #EEE, @left-color: #EEE)     
4 .drop-shadow(@x-axis: 0, @y-axis: 1px, @blur: 2px, @alpha: 0.1)    
5 .rounded(@radius: 2px)    
6 .border-radius(@topright: 0, @bottomright: 0, @bottomleft: 0, @topleft: 0)    
7 .opacity(@opacity: 0.5)    
8 .transition-duration(@duration: 0.2s)     
9 .transform(...)     
10 .rotation(@deg:5deg)    
11 .scale(@ratio:1.5)    
12 .transition(@duration:0.2s, @ease:ease-out)    
13 .inner-shadow(@horizontal:0, @vertical:1px, @blur:2px, @alpha: 0.4)     
14 .box-shadow(@arguments)     
15 .box-sizing(@sizing: border-box)    
16 .user-select(@argument: none)    
17 .columns(@colwidth: 250px, @colcount: 0, @colgap: 50px, @columnRuleColor: #EEE, @columnRuleStyle: solid, @columnRuleWidth: 1px)    
18 .translate(@x:0, @y:0)     
19 .background-clip(@argument: padding-box)    

#####Добавил     
.background-size(@size: contain)    