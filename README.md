#jquerymin#

jquery-like minimum wrapper optimized for speed

##Installation##
TBD


##API##

###Initialization###

####$(element)####


###Selectors###

####$.id(myId)####
document.getElementById(myId)

####$.class(myClass)####
document.getElementsByClassName(myClass)

####$.tag(tagName)####
document.getElementsByTagname(tagName)

####Chainable?####
$.id(myId).class(myClass)

###HTML Manipulation###
$(elem).append(elem2)
$(elem).prepend(elem2)
$(elem).html()

Form serialization


###Events###
.on()


###AJAX###
.ajax


###Class Modifiers###
$(elem).addClass(myClassName)
$(elem).removeClass(myClassName)
$(elem).toggle(myClassName, forced /* optional */)

###CSS modifiers###
$(elem).attr() // set and get
