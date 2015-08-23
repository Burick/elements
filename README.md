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

.gradient(@color: #F5F5F5, @start: #EEE, @stop: #FFF)
.bw-gradient(@color: #F5F5F5, @start: 0, @stop: 255)
.bordered(@top-color: #EEE, @right-color: #EEE, @bottom-color: #EEE, @left-color: #EEE) 
.drop-shadow(@x-axis: 0, @y-axis: 1px, @blur: 2px, @alpha: 0.1)
.rounded(@radius: 2px)
.border-radius(@topright: 0, @bottomright: 0, @bottomleft: 0, @topleft: 0)
.opacity(@opacity: 0.5)
.transition-duration(@duration: 0.2s) 
.transform(...) 
.rotation(@deg:5deg)
.scale(@ratio:1.5)
.transition(@duration:0.2s, @ease:ease-out)
.inner-shadow(@horizontal:0, @vertical:1px, @blur:2px, @alpha: 0.4) 
.box-shadow(@arguments) 
.box-sizing(@sizing: border-box)
.user-select(@argument: none)
.columns(@colwidth: 250px, @colcount: 0, @colgap: 50px, @columnRuleColor: #EEE, @columnRuleStyle: solid, @columnRuleWidth: 1px)
.translate(@x:0, @y:0) 
.background-clip(@argument: padding-box)

Добавил 
.background-size(@size: contain)