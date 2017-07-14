
bower install --save Polymer/polymer
bower install --save firebase/polymerfire
bower install --save PolymerElements/paper-button




chwzr 
[1 day ago] 
with <firebase-auth> ... you can use  a  `<template is="dom-if" if="[[!user]]>`  to show something when not logged in, and vice versa  a `<template is="dom-if" if="[[user]]>` to show the page when logged in..


captaincodeman [24 hours ago] 
if you create a mixin and set the user via some auth-status element, you can easily add role / permission checks to elements for showing and hiding things plus redirecting depending on auth status