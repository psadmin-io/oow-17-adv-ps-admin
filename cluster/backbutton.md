!SLIDE center subsection blue

# Back Button

!SLIDE bullets

# Back Button

* TODO: image of back button

~~~SECTION:notes~~~

~~~ENDSECTION~~~

!SLIDE bullets

# Tips and Tricks

* Multi Tools version
    * 8.54.21? and up?
* Component settings
* Nav Collections TODO

~~~SECTION:notes~~~

~~~ENDSECTION~~~

!SLIDE bullets

# How it works

* JavaScript
    * PT_COMMON > PT_HISTORY
* TODO - call out details
    * backNavigation.classicBackButton.create();
    * var pt_history = getHistoryObject();

~~~SECTION:notes~~~

~~~ENDSECTION~~~

!SLIDE center subsection grey

# Demo

!SLIDE supplemental guide

# Back Button Demo

## JavaScript Location

1. PT_COMMON > PT_HISTORY

## Create the back button HTML

1. backNavigation.classicBackButton.create();

## Add to History

1. AddToHistory(label, keyData, userData, pageName, stateNum, elemNum, classicURL, dashboard, appBcData, nPost, userQueryString, bReturnToLastPage) 
1. AddToHistory("Testing", "", "", "", 0, 0, "http://google.com", 0, "","","",true);

## Examples

1. var pt_history = getHistoryObject();
1. pt_history.nodes();
1. pt_history.pop();
1. pt_history.save();
1. var pt_history = getHistoryObject();
1. pt_history.nodes();
1. Try back button 
TODO - not working?