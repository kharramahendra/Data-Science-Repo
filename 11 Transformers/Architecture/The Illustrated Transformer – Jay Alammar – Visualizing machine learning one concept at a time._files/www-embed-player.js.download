(function(){'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ea="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function fa(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ia=fa(this);function v(a,b){if(b)a:{var c=ia;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ea(c,a,{configurable:!0,writable:!0,value:b})}}
v("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ea(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
v("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ia[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ea(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ja(aa(this))}})}return a});
function ja(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ka(a){return a.raw=a}
function la(a,b){a.raw=b;return a}
function w(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if("number"==typeof a.length)return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function ma(a){if(!(a instanceof Array)){a=w(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function na(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var oa="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)na(d,e)&&(a[e]=d[e])}return a};
v("Object.assign",function(a){return a||oa});
var pa="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},qa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=pa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ra;
if("function"==typeof Object.setPrototypeOf)ra=Object.setPrototypeOf;else{var sa;a:{var ta={a:!0},ua={};try{ua.__proto__=ta;sa=ua.a;break a}catch(a){}sa=!1}ra=sa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var va=ra;
function x(a,b){a.prototype=pa(b.prototype);a.prototype.constructor=a;if(va)va(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Aa=b.prototype}
function wa(){this.u=!1;this.m=null;this.i=void 0;this.h=1;this.H=this.l=0;this.K=this.j=null}
function xa(a){if(a.u)throw new TypeError("Generator is already running");a.u=!0}
wa.prototype.B=function(a){this.i=a};
function ya(a,b){a.j={exception:b,md:!0};a.h=a.l||a.H}
wa.prototype.return=function(a){this.j={return:a};this.h=this.H};
wa.prototype.yield=function(a,b){this.h=b;return{value:a}};
wa.prototype.A=function(a){this.h=a};
function za(a,b,c){a.l=b;void 0!=c&&(a.H=c)}
function Aa(a){a.l=0;var b=a.j.exception;a.j=null;return b}
function Ba(a){var b=a.K.splice(0)[0];(b=a.j=a.j||b)?b.md?a.h=a.l||a.H:void 0!=b.A&&a.H<b.A?(a.h=b.A,a.j=null):a.h=a.H:a.h=0}
function Ca(a){this.h=new wa;this.i=a}
function Da(a,b){xa(a.h);var c=a.h.m;if(c)return Ea(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Fa(a)}
function Ea(a,b,c,d){try{var e=b.call(a.h.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.u=!1,e;var f=e.value}catch(g){return a.h.m=null,ya(a.h,g),Fa(a)}a.h.m=null;d.call(a.h,f);return Fa(a)}
function Fa(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.u=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ya(a.h,c)}a.h.u=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.md)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ga(a){this.next=function(b){xa(a.h);a.h.m?b=Ea(a,a.h.m.next,b,a.h.B):(a.h.B(b),b=Fa(a));return b};
this.throw=function(b){xa(a.h);a.h.m?b=Ea(a,a.h.m["throw"],b,a.h.B):(ya(a.h,b),b=Fa(a));return b};
this.return=function(b){return Da(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ha(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function A(a){return Ha(new Ga(new Ca(a)))}
function Ia(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
v("Reflect",function(a){return a?a:{}});
v("Reflect.construct",function(){return qa});
v("Reflect.setPrototypeOf",function(a){return a?a:va?function(b,c){try{return va(b,c),!0}catch(d){return!1}}:null});
v("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.u=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=ia.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.Z),reject:g(this.m)}};
b.prototype.Z=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.fa(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.X(g):this.H(g)}};
b.prototype.X=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ha(h,g):this.H(g)};
b.prototype.m=function(g){this.B(2,g)};
b.prototype.H=function(g){this.B(1,g)};
b.prototype.B=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.ea();this.K()};
b.prototype.ea=function(){var g=this;e(function(){if(g.T()){var h=ia.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.T=function(){if(this.u)return!1;var g=ia.CustomEvent,h=ia.Event,k=ia.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ia.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.K=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.fa=function(g){var h=this.l();g.Yb(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(t,r){return"function"==typeof t?function(u){try{l(t(u))}catch(y){n(y)}}:r}
var l,n,p=new b(function(t,r){l=t;n=r});
this.Yb(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Yb=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=w(g),n=l.next();!n.done;n=l.next())d(n.value).Yb(h,k)})};
b.all=function(g){var h=w(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(u){return function(y){t[u]=y;r--;0==r&&l(t)}}
var t=[],r=0;do t.push(void 0),r++,d(k.value).Yb(p(t.length-1),n),k=h.next();while(!k.done)})};
return b});
v("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=w(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!na(k,g)){var l=new c;ea(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!na(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&na(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&na(k,g)&&na(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&na(k,g)&&na(k[g],this.h)?delete k[g][this.h]:!1};
return b});
v("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ja(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h[0][l];if(n&&na(h[0],l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=w(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(w([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ja(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
v("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
v("Object.setPrototypeOf",function(a){return a||va});
v("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
v("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
v("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
function Ka(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
v("Array.prototype.keys",function(a){return a?a:function(){return Ka(this,function(b){return b})}});
v("Set",function(a){function b(c){this.h=new Map;if(c){c=w(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(w([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
v("Array.prototype.values",function(a){return a?a:function(){return Ka(this,function(b,c){return c})}});
v("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)na(b,d)&&c.push(b[d]);return c}});
v("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
v("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
v("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ja(this,b,"includes").indexOf(b,c||0)}});
v("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||Infinity===b||-Infinity===b||0===b)return b;var c=Math.floor(Math.abs(b));return 0>b?-c:c}});
v("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
v("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
v("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
v("Array.prototype.entries",function(a){return a?a:function(){return Ka(this,function(b,c){return[b,c]})}});
v("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
v("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
v("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)na(b,d)&&c.push([d,b[d]]);return c}});
v("globalThis",function(a){return a||ia});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var La=La||{},B=this||self;function C(a,b,c){a=a.split(".");c=c||B;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Ma(a,b){var c=D("CLOSURE_FLAGS");a=c&&c[a];return null!=a?a:b}
function D(a,b){a=a.split(".");b=b||B;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Na(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Oa(a){var b=Na(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Pa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Qa(a){return Object.prototype.hasOwnProperty.call(a,Ra)&&a[Ra]||(a[Ra]=++Sa)}
var Ra="closure_uid_"+(1E9*Math.random()>>>0),Sa=0;function Ta(a,b,c){return a.call.apply(a.bind,arguments)}
function Ua(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Va(a,b,c){Va=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ta:Ua;return Va.apply(null,arguments)}
function Wa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Xa(){return Date.now()}
function Ya(a,b){function c(){}
c.prototype=b.prototype;a.Aa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Za(a){return a}
;function $a(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,$a);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Ya($a,Error);$a.prototype.name="CustomError";function bb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function cb(){}
function db(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var eb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},fb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},gb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},hb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},ib=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
fb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function jb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function kb(a,b){b=eb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function lb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Oa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function mb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function nb(a){var b=ob,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function pb(a){for(var b in a)return!1;return!0}
function qb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function rb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function sb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function tb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function ub(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=ub(a[c]);return b}
var vb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function wb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<vb.length;f++)c=vb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var xb;function yb(){if(void 0===xb){var a=null,b=B.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Za,createScript:Za,createScriptURL:Za})}catch(c){B.console&&B.console.error(c.message)}xb=a}else xb=a}return xb}
;function zb(){}
function Ab(a){return new zb(Bb,a)}
var Bb={};Ab("");var Cb={};function Db(a){this.h=a}
Db.prototype.toString=function(){return this.h.toString()};function Eb(a){this.h=a}
Eb.prototype.toString=function(){return this.h+""};
function Fb(a){if(a instanceof Eb&&a.constructor===Eb)return a.h;Na(a);return"type_error:TrustedResourceUrl"}
var Gb={};function Hb(a){var b=yb();a=b?b.createScriptURL(a):a;return new Eb(a,Gb)}
;var Ib=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};function Jb(a){this.h=a}
Jb.prototype.toString=function(){return this.h.toString()};
var Kb={},Lb=new Jb("about:invalid#zClosurez",Kb);var Mb=Ma(610401301,!1),Nb=Ma(572417392,Ma(1,!0));function Ob(){var a=B.navigator;return a&&(a=a.userAgent)?a:""}
var Pb,Qb=B.navigator;Pb=Qb?Qb.userAgentData||null:null;function Rb(a){return Mb?Pb?Pb.brands.some(function(b){return(b=b.brand)&&-1!=b.indexOf(a)}):!1:!1}
function E(a){return-1!=Ob().indexOf(a)}
;function Sb(){return Mb?!!Pb&&0<Pb.brands.length:!1}
function Tb(){return Sb()?!1:E("Opera")}
function Ub(){return Sb()?!1:E("Trident")||E("MSIE")}
function Vb(){return E("Firefox")||E("FxiOS")}
function Wb(){return Sb()?Rb("Chromium"):(E("Chrome")||E("CriOS"))&&!(Sb()?0:E("Edge"))||E("Silk")}
;function Xb(a){this.h=a}
Xb.prototype.toString=function(){return this.h.toString()};function Yb(){a:{var a=B.document;if(a.querySelector&&(a=a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&Zb.test(a))break a;a=""}return a}
var Zb=/^[\w+/_-]+[=]{0,2}$/;function $b(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var ac=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function bc(a){return a?decodeURI(a):a}
function cc(a,b){return b.match(ac)[a]||null}
function dc(a){return bc(cc(3,a))}
function ec(a){var b=a.match(ac);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function fc(a){var b=a.indexOf("#");return 0>b?a:a.slice(0,b)}
function hc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function ic(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)ic(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function jc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)ic(a[b],a[b+1],c);return c.join("&")}
function kc(a){var b=[],c;for(c in a)ic(c,a[c],b);return b.join("&")}
function lc(a,b){var c=2==arguments.length?jc(arguments[1],0):jc(arguments,1);return hc(a,c)}
function mc(a,b){b=kc(b);return hc(a,b)}
function nc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return hc(a,b+c)}
function oc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var pc=/#|$/,qc=/[?&]($|#)/;function rc(a,b){for(var c=a.search(pc),d=0,e,f=[];0<=(e=oc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(qc,"$1")}
;function sc(a){this.h=a}
;function tc(a,b,c){this.j=a;this.m=b;this.i=c||[];this.h=new Map}
m=tc.prototype;m.Ld=function(a){var b=Ia.apply(1,arguments),c=this.zc(b);c?c.push(new sc(a)):this.yd(a,b)};
m.yd=function(a){var b=this.getKey(Ia.apply(1,arguments));this.h.set(b,[new sc(a)])};
m.zc=function(){var a=this.getKey(Ia.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
m.ce=function(){var a=this.zc(Ia.apply(0,arguments));return a&&a.length?a[0]:void 0};
m.clear=function(){this.h.clear()};
m.getKey=function(){var a=Ia.apply(0,arguments);return a?a.join(","):"key"};function uc(a,b){tc.call(this,a,3,b)}
x(uc,tc);uc.prototype.l=function(a){var b=Ia.apply(1,arguments),c=0,d=this.ce(b);d&&(c=d.h);this.yd(c+a,b)};function vc(a,b){tc.call(this,a,2,b)}
x(vc,tc);vc.prototype.record=function(a){this.Ld(a,Ia.apply(1,arguments))};function wc(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function xc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Oa(d)?xc.apply(null,d):wc(d)}}
;function F(){this.qb=this.qb;this.H=this.H}
m=F.prototype;m.qb=!1;m.aa=function(){return this.qb};
m.dispose=function(){this.qb||(this.qb=!0,this.S())};
function yc(a,b){a.addOnDisposeCallback(Wa(wc,b))}
m.addOnDisposeCallback=function(a,b){this.qb?void 0!==b?a.call(b):a():(this.H||(this.H=[]),this.H.push(void 0!==b?Va(a,b):a))};
m.S=function(){if(this.H)for(;this.H.length;)this.H.shift()()};function zc(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
zc.prototype.stopPropagation=function(){this.j=!0};
zc.prototype.preventDefault=function(){this.defaultPrevented=!0};function Ac(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function Bc(a){var b=D("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||B.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Cc(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Dc[c])c=Dc[c];else{c=String(c);if(!Dc[c]){var f=/function\s+([^\(]+)/m.exec(c);Dc[c]=f?f[1]:"[Anonymous]"}c=Dc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function Cc(a,b){b||(b={});b[Ec(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Ec(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Cc(a,b));return c}
function Ec(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Dc={};var Fc=function(){if(!B.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
B.addEventListener("test",c,b);B.removeEventListener("test",c,b)}catch(d){}return a}();function Gc(){return Mb?!!Pb&&!!Pb.platform:!1}
function Hc(){return E("iPhone")&&!E("iPod")&&!E("iPad")}
;function Ic(a){Ic[" "](a);return a}
Ic[" "]=function(){};var Jc=Tb(),Kc=Ub(),Lc=E("Edge"),Mc=E("Gecko")&&!(-1!=Ob().toLowerCase().indexOf("webkit")&&!E("Edge"))&&!(E("Trident")||E("MSIE"))&&!E("Edge"),Qc=-1!=Ob().toLowerCase().indexOf("webkit")&&!E("Edge");Qc&&E("Mobile");Gc()||E("Macintosh");Gc()||E("Windows");(Gc()?"Linux"===Pb.platform:E("Linux"))||Gc()||E("CrOS");var Rc=Gc()?"Android"===Pb.platform:E("Android");Hc();E("iPad");E("iPod");Hc()||E("iPad")||E("iPod");Ob().toLowerCase().indexOf("kaios");
function Sc(){var a=B.document;return a?a.documentMode:void 0}
var Tc;a:{var Uc="",Vc=function(){var a=Ob();if(Mc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Lc)return/Edge\/([\d\.]+)/.exec(a);if(Kc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Qc)return/WebKit\/(\S+)/.exec(a);if(Jc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Vc&&(Uc=Vc?Vc[1]:"");if(Kc){var Wc=Sc();if(null!=Wc&&Wc>parseFloat(Uc)){Tc=String(Wc);break a}}Tc=Uc}var Xc=Tc,Yc;if(B.document&&Kc){var Zc=Sc();Yc=Zc?Zc:parseInt(Xc,10)||void 0}else Yc=void 0;var $c=Yc;function ad(a,b){zc.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Ya(ad,zc);var bd={2:"touch",3:"pen",4:"mouse"};
ad.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Mc){a:{try{Ic(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:bd[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&ad.Aa.preventDefault.call(this)};
ad.prototype.stopPropagation=function(){ad.Aa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
ad.prototype.preventDefault=function(){ad.Aa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var cd="closure_listenable_"+(1E6*Math.random()|0);var dd=0;function ed(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.dc=e;this.key=++dd;this.Qb=this.Xb=!1}
function fd(a){a.Qb=!0;a.listener=null;a.proxy=null;a.src=null;a.dc=null}
;function gd(a){this.src=a;this.listeners={};this.h=0}
gd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=hd(a,b,d,e);-1<g?(b=a[g],c||(b.Xb=!1)):(b=new ed(b,this.src,f,!!d,e),b.Xb=c,a.push(b));return b};
gd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=hd(e,b,c,d);return-1<b?(fd(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function id(a,b){var c=b.type;c in a.listeners&&kb(a.listeners[c],b)&&(fd(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function hd(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Qb&&f.listener==b&&f.capture==!!c&&f.dc==d)return e}return-1}
;var jd="closure_lm_"+(1E6*Math.random()|0),kd={},ld=0;function md(a,b,c,d,e){if(d&&d.once)nd(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)md(a,b[f],c,d,e);else c=od(c),a&&a[cd]?a.listen(b,c,Pa(d)?!!d.capture:!!d,e):pd(a,b,c,!1,d,e)}
function pd(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Pa(e)?!!e.capture:!!e,h=qd(a);h||(a[jd]=h=new gd(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=rd();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Fc||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(sd(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");ld++}}
function rd(){function a(c){return b.call(a.src,a.listener,c)}
var b=td;return a}
function nd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)nd(a,b[f],c,d,e);else c=od(c),a&&a[cd]?a.h.add(String(b),c,!0,Pa(d)?!!d.capture:!!d,e):pd(a,b,c,!0,d,e)}
function ud(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ud(a,b[f],c,d,e);else(d=Pa(d)?!!d.capture:!!d,c=od(c),a&&a[cd])?a.h.remove(String(b),c,d,e):a&&(a=qd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=hd(b,c,d,e)),(c=-1<a?b[a]:null)&&vd(c))}
function vd(a){if("number"!==typeof a&&a&&!a.Qb){var b=a.src;if(b&&b[cd])id(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(sd(c),d):b.addListener&&b.removeListener&&b.removeListener(d);ld--;(c=qd(b))?(id(c,a),0==c.h&&(c.src=null,b[jd]=null)):fd(a)}}}
function sd(a){return a in kd?kd[a]:kd[a]="on"+a}
function td(a,b){if(a.Qb)a=!0;else{b=new ad(b,this);var c=a.listener,d=a.dc||a.src;a.Xb&&vd(a);a=c.call(d,b)}return a}
function qd(a){a=a[jd];return a instanceof gd?a:null}
var wd="__closure_events_fn_"+(1E9*Math.random()>>>0);function od(a){if("function"===typeof a)return a;a[wd]||(a[wd]=function(b){return a.handleEvent(b)});
return a[wd]}
;function xd(){F.call(this);this.h=new gd(this);this.Ka=this;this.fa=null}
Ya(xd,F);xd.prototype[cd]=!0;m=xd.prototype;m.addEventListener=function(a,b,c,d){md(this,a,b,c,d)};
m.removeEventListener=function(a,b,c,d){ud(this,a,b,c,d)};
function yd(a,b){var c=a.fa;if(c){var d=[];for(var e=1;c;c=c.fa)d.push(c),++e}a=a.Ka;c=b.type||b;"string"===typeof b?b=new zc(b,a):b instanceof zc?b.target=b.target||a:(e=b,b=new zc(c,a),wb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=zd(g,c,!0,b)&&e}b.j||(g=b.h=a,e=zd(g,c,!0,b)&&e,b.j||(e=zd(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=zd(g,c,!1,b)&&e}
m.S=function(){xd.Aa.S.call(this);this.removeAllListeners();this.fa=null};
m.listen=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
m.removeAllListeners=function(a){if(this.h){var b=this.h;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,fd(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function zd(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Qb&&g.capture==c){var h=g.listener,k=g.dc||g.src;g.Xb&&id(a.h,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Ad(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Ad.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Bd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function Cd(a,b){return a+Math.random()*(b-a)}
;function Dd(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=Dd.prototype;m.clone=function(){return new Dd(this.x,this.y)};
m.equals=function(a){return a instanceof Dd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function Ed(a,b){this.width=a;this.height=b}
m=Ed.prototype;m.clone=function(){return new Ed(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.Lb=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function Fd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Gd(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function Hd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Id;function Jd(){var a=B.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!E("Presto")&&(a=function(){var e=Gd("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Va(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Ub()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Zc;c.Zc=null;e()}};
return function(e){d.next={Zc:e};d=d.next;b.port2.postMessage(0)}}return function(e){B.setTimeout(e,0)}}
;function Kd(a){B.setTimeout(function(){throw a;},0)}
;function Ld(){this.i=this.h=null}
Ld.prototype.add=function(a,b){var c=Md.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Ld.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Md=new Ad(function(){return new Nd},function(a){return a.reset()});
function Nd(){this.next=this.scope=this.h=null}
Nd.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Nd.prototype.reset=function(){this.next=this.scope=this.h=null};var Od,Pd=!1,Qd=new Ld;function Rd(a,b){Od||Sd();Pd||(Od(),Pd=!0);Qd.add(a,b)}
function Sd(){if(B.Promise&&B.Promise.resolve){var a=B.Promise.resolve(void 0);Od=function(){a.then(Td)}}else Od=function(){var b=Td;
"function"!==typeof B.setImmediate||B.Window&&B.Window.prototype&&(Sb()||!E("Edge"))&&B.Window.prototype.setImmediate==B.setImmediate?(Id||(Id=Jd()),Id(b)):B.setImmediate(b)}}
function Td(){for(var a;a=Qd.remove();){try{a.h.call(a.scope)}catch(b){Kd(b)}Bd(Md,a)}Pd=!1}
;function Ud(a){this.h=0;this.u=void 0;this.l=this.i=this.j=null;this.m=this.H=!1;if(a!=cb)try{var b=this;a.call(void 0,function(c){Vd(b,2,c)},function(c){Vd(b,3,c)})}catch(c){Vd(this,3,c)}}
function Wd(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
Wd.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Xd=new Ad(function(){return new Wd},function(a){a.reset()});
function Yd(a,b,c){var d=Xd.get();d.i=a;d.h=b;d.context=c;return d}
function Zd(a){return new Ud(function(b,c){c(a)})}
Ud.prototype.then=function(a,b,c){return $d(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Ud.prototype.$goog_Thenable=!0;m=Ud.prototype;m.qc=function(a,b){return $d(this,null,a,b)};
m.catch=Ud.prototype.qc;m.cancel=function(a){if(0==this.h){var b=new ae(a);Rd(function(){be(this,b)},this)}};
function be(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?be(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):ce(c),de(c,e,3,b)))}a.j=null}else Vd(a,3,b)}
function ee(a,b){a.i||2!=a.h&&3!=a.h||fe(a);a.l?a.l.next=b:a.i=b;a.l=b}
function $d(a,b,c,d){var e=Yd(null,null,null);e.child=new Ud(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof ae?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;ee(a,e);return e.child}
m.bf=function(a){this.h=0;Vd(this,2,a)};
m.cf=function(a){this.h=0;Vd(this,3,a)};
function Vd(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.bf,f=a.cf;if(d instanceof Ud){ee(d,Yd(e||cb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Pa(d))try{var k=d.then;if("function"===typeof k){ge(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.u=c,a.h=b,a.j=null,fe(a),3!=b||c instanceof ae||he(a,c))}}
function ge(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function fe(a){a.H||(a.H=!0,Rd(a.Xd,a))}
function ce(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
m.Xd=function(){for(var a;a=ce(this);)de(this,a,this.h,this.u);this.H=!1};
function de(a,b,c,d){if(3==c&&b.h&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.child)b.child.j=null,ie(b,c,d);else try{b.j?b.i.call(b.context):ie(b,c,d)}catch(e){je.call(null,e)}Bd(Xd,b)}
function ie(a,b,c){2==b?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function he(a,b){a.m=!0;Rd(function(){a.m&&je.call(null,b)})}
var je=Kd;function ae(a){$a.call(this,a)}
Ya(ae,$a);ae.prototype.name="cancel";function ke(a,b){xd.call(this);this.j=a||1;this.i=b||B;this.l=Va(this.Ze,this);this.m=Xa()}
Ya(ke,xd);m=ke.prototype;m.enabled=!1;m.Ga=null;m.setInterval=function(a){this.j=a;this.Ga&&this.enabled?(this.stop(),this.start()):this.Ga&&this.stop()};
m.Ze=function(){if(this.enabled){var a=Xa()-this.m;0<a&&a<.8*this.j?this.Ga=this.i.setTimeout(this.l,this.j-a):(this.Ga&&(this.i.clearTimeout(this.Ga),this.Ga=null),yd(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
m.start=function(){this.enabled=!0;this.Ga||(this.Ga=this.i.setTimeout(this.l,this.j),this.m=Xa())};
m.stop=function(){this.enabled=!1;this.Ga&&(this.i.clearTimeout(this.Ga),this.Ga=null)};
m.S=function(){ke.Aa.S.call(this);this.stop();delete this.i};
function le(a,b,c){if("function"===typeof a)c&&(a=Va(a,c));else if(a&&"function"==typeof a.handleEvent)a=Va(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:B.setTimeout(a,b||0)}
;function me(a){F.call(this);this.B=a;this.j=0;this.l=100;this.m=!1;this.i=new Map;this.u=new Set;this.flushInterval=3E4;this.h=new ke(this.flushInterval);this.h.listen("tick",this.mb,!1,this);yc(this,this.h)}
x(me,F);m=me.prototype;m.sendIsolatedPayload=function(a){this.m=a;this.l=1};
function ne(a){a.h.enabled||a.h.start();a.j++;a.j>=a.l&&a.mb()}
m.mb=function(){var a=this.i.values();a=[].concat(ma(a)).filter(function(b){return b.h.size});
a.length&&this.B.flush(a,this.m);oe(a);this.j=0;this.h.enabled&&this.h.stop()};
m.vc=function(a){var b=Ia.apply(1,arguments);this.i.has(a)||this.i.set(a,new uc(a,b))};
m.Vc=function(a){var b=Ia.apply(1,arguments);this.i.has(a)||this.i.set(a,new vc(a,b))};
function pe(a,b){return a.u.has(b)?void 0:a.i.get(b)}
m.Ub=function(a){this.Kd.apply(this,[a,1].concat(ma(Ia.apply(1,arguments))))};
m.Kd=function(a,b){var c=Ia.apply(2,arguments),d=pe(this,a);d&&d instanceof uc&&(d.l(b,c),ne(this))};
m.record=function(a,b){var c=Ia.apply(2,arguments),d=pe(this,a);d&&d instanceof vc&&(d.record(b,c),ne(this))};
function oe(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function qe(a){this.h=a;this.h.vc("/client_streamz/bg/fic",{Da:3,Ca:"ke"})}
function re(a){this.h=a;this.h.vc("/client_streamz/bg/fiec",{Da:3,Ca:"rk"},{Da:3,Ca:"ke"},{Da:2,Ca:"ec"},{Da:3,Ca:"em"})}
function se(a,b,c,d,e){a.h.Ub("/client_streamz/bg/fiec",b,c,d,e)}
function te(a){this.h=a;this.h.Vc("/client_streamz/bg/fil",{Da:3,Ca:"rk"},{Da:3,Ca:"ke"})}
te.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fil",a,b,c)};
function ue(a){this.h=a;this.h.vc("/client_streamz/bg/fsc",{Da:3,Ca:"rk"},{Da:3,Ca:"ke"})}
function ve(a){this.h=a;this.h.Vc("/client_streamz/bg/fsl",{Da:3,Ca:"rk"},{Da:3,Ca:"ke"})}
ve.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fsl",a,b,c)};var we={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function xe(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=ye(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=ze(a,h),d+=ze(a,h+4),e+=ze(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return we.toString(e)}
function ye(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function ze(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;Vb();var Ae=Hc()||E("iPod"),Be=E("iPad");!E("Android")||Wb()||Vb()||Tb()||E("Silk");Wb();var Ce=E("Safari")&&!(Wb()||(Sb()?0:E("Coast"))||Tb()||(Sb()?0:E("Edge"))||(Sb()?Rb("Microsoft Edge"):E("Edg/"))||(Sb()?Rb("Opera"):E("OPR"))||Vb()||E("Silk")||E("Android"))&&!(Hc()||E("iPad")||E("iPod"));var De={},Ee=null;function Fe(a,b){Oa(a);void 0===b&&(b=0);Ge();b=De[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function He(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;Ie(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function Ie(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),n=Ee[l];if(null!=n)return n;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
Ge();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function Ge(){if(!Ee){Ee={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));De[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===Ee[f]&&(Ee[f]=e)}}}}
;var Je="undefined"!==typeof Uint8Array,Ke=!Kc&&"function"===typeof btoa;function Le(a){if(!Ke)return Fe(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var Me=/[-_.]/g,Ne={"-":"+",_:"/",".":"="};function Oe(a){return Ne[a]||""}
function Pe(a){return Je&&null!=a&&a instanceof Uint8Array}
var Qe={};var Re;function Se(a){if(a!==Qe)throw Error("illegal external caller");}
function Te(a,b){Se(b);this.value_=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
Te.prototype.Lb=function(){return null==this.value_};
Te.prototype.sizeBytes=function(){Se(Qe);var a=this.value_;if(null!=a&&!Pe(a))if("string"===typeof a)if(Ke){Me.test(a)&&(a=a.replace(Me,Oe));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=He(a);else Na(a),a=null;return(a=null==a?a:this.value_=a)?a.length:0};function Ue(){return"function"===typeof BigInt}
var Ve=!Nb,We=!Nb;function Xe(a){return Array.prototype.slice.call(a)}
;var Ye;Ye="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;Math.max.apply(Math,ma(Object.values({Ff:1,Df:2,Cf:4,If:8,Hf:16,Gf:32,tf:64,Kf:128,Bf:256,Af:512,Ef:1024,yf:2048,Jf:4096,zf:8192})));var Ze=Ye?function(a,b){a[Ye]|=b}:function(a,b){void 0!==a.Ta?a.Ta|=b:Object.defineProperties(a,{Ta:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function $e(a){var b=af(a);1!==(b&1)&&(Object.isFrozen(a)&&(a=Xe(a)),bf(a,b|1))}
function cf(a,b,c){return c?a|b:a&~b}
var af=Ye?function(a){return a[Ye]|0}:function(a){return a.Ta|0},df=Ye?function(a){return a[Ye]}:function(a){return a.Ta},bf=Ye?function(a,b){a[Ye]=b}:function(a,b){void 0!==a.Ta?a.Ta=b:Object.defineProperties(a,{Ta:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function ef(){var a=[];Ze(a,1);return a}
function ff(a,b){bf(b,(a|0)&-14591)}
function gf(a,b){bf(b,(a|34)&-14557)}
function hf(a){a=a>>14&1023;return 0===a?536870912:a}
;var jf={},kf={};function lf(a){return!(!a||"object"!==typeof a||a.Zf!==kf)}
function mf(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var nf,of=!Nb;function pf(a,b){if(null==a){if(!b)throw Error();}else if("string"===typeof a)a=a?new Te(a,Qe):Re||(Re=new Te(null,Qe));else if(a.constructor!==Te)if(Pe(a))a instanceof Uint8Array||Array.isArray(a),a=a.length?new Te(new Uint8Array(a),Qe):Re||(Re=new Te(null,Qe));else throw Error();return a}
function qf(a,b,c){if(!Array.isArray(a)||a.length)return!1;var d=af(a);if(d&1)return!0;if(!(b&&(Array.isArray(b)?b.includes(c):b.has(c))))return!1;bf(a,d|1);return!0}
var rf,sf=[];bf(sf,55);rf=Object.freeze(sf);function tf(a){if(a&2)throw Error();}
;var uf=0,vf=0;function wf(a){var b=0>a;a=Math.abs(a);var c=a>>>0;a=Math.floor((a-c)/4294967296);b&&(c=w(xf(c,a)),b=c.next().value,a=c.next().value,c=b);uf=c>>>0;vf=a>>>0}
function yf(a,b){b>>>=0;a>>>=0;if(2097151>=b)var c=""+(4294967296*b+a);else Ue()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+6777216*c+6710656*b,c+=8147497*b,b*=2,1E7<=a&&(c+=Math.floor(a/1E7),a%=1E7),1E7<=c&&(b+=Math.floor(c/1E7),c%=1E7),c=b+zf(c)+zf(a));return c}
function zf(a){a=String(a);return"0000000".slice(a.length)+a}
function Af(){var a=uf,b=vf;b&2147483648?Ue()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=w(xf(a,b)),a=b.next().value,b=b.next().value,a="-"+yf(a,b)):a=yf(a,b);return a}
function xf(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function Bf(){var a=Error();Ac(a,"incident");Kd(a)}
function Cf(a){a=Error(a);Ac(a,"warning");return a}
;function Df(a){return a.displayName||a.name||"unknown type name"}
function Ef(a){if(null!=a&&"boolean"!==typeof a)throw Error("Expected boolean but got "+Na(a)+": "+a);return a}
var Ff=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function Gf(a){var b=typeof a;return"number"===b?Number.isFinite(a):"string"!==b?!1:Ff.test(a)}
function Hf(a){if(null!=a){if("number"!==typeof a)throw Cf("int32");Number.isFinite(a)||Bf()}return a}
function If(a){if(null==a)return a;if("string"===typeof a){if(!a)return;a=+a}if("number"===typeof a)return a}
function Jf(a){if(null!=a){var b=!!b;if(!Gf(a))throw Cf("int64");a="string"===typeof a?Kf(a):b?Lf(a):Mf(a)}return a}
function Nf(a){return"-"===a[0]?20>a.length?!0:20===a.length&&-922337<Number(a.substring(0,7)):19>a.length?!0:19===a.length&&922337>Number(a.substring(0,6))}
function Mf(a){Gf(a);a=Math.trunc(a);if(!Number.isSafeInteger(a)){wf(a);var b=uf,c=vf;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,0==b&&(c=c+1>>>0);b=4294967296*c+(b>>>0);a=a?-b:b}return a}
function Lf(a){Gf(a);a=Math.trunc(a);if(Number.isSafeInteger(a))a=String(a);else{var b=String(a);Nf(b)?a=b:(wf(a),a=Af())}return a}
function Kf(a){Gf(a);var b=Math.trunc(Number(a));if(Number.isSafeInteger(b))return String(b);b=a.indexOf(".");-1!==b&&(a=a.substring(0,b));a.indexOf(".");if(!Nf(a)){if(16>a.length)wf(Number(a));else if(Ue())a=BigInt(a),uf=Number(a&BigInt(4294967295))>>>0,vf=Number(a>>BigInt(32)&BigInt(4294967295));else{b=+("-"===a[0]);vf=uf=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),vf*=1E6,uf=1E6*uf+d,4294967296<=uf&&(vf+=Math.trunc(uf/4294967296),vf>>>=0,uf>>>=0);b&&(b=w(xf(uf,vf)),
a=b.next().value,b=b.next().value,uf=a,vf=b)}a=Af()}return a}
function Of(a){if("string"!==typeof a)throw Error();return a}
function Pf(a){if(null!=a&&"string"!==typeof a)throw Error();return a}
function Qf(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Df(b)+" but got "+(a&&Df(a.constructor)));}
function Rf(a,b,c){if(null!=a&&"object"===typeof a&&a.Jc===jf)return a;if(Array.isArray(a)){var d=af(a),e=d;0===e&&(e|=c&32);e|=c&2;e!==d&&bf(a,e);return new b(a)}}
;var Sf;function Tf(a,b){af(b);Sf=b;a=new a(b);Sf=void 0;return a}
function Uf(a,b,c){null==a&&(a=Sf);Sf=void 0;if(null==a){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-16760833|(b&1023)<<14)}else{if(!Array.isArray(a))throw Error();d=af(a);if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error();a:{c=d;if(d=a.length){var e=d-1;if(mf(a[e])){c|=256;b=e-(+!!(c&512)-1);if(1024<=b)throw Error();d=c&-16760833|(b&1023)<<14;break a}}if(b){b=Math.max(b,d-(+!!(c&512)-1));if(1024<b)throw Error();d=c&-16760833|(b&1023)<<14}else d=c}}bf(a,d);return a}
;function Vf(a,b){return Wf(b)}
function Wf(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a){if(Array.isArray(a))return of||!qf(a,void 0,9999)?a:void 0;if(Pe(a))return Le(a);if(a instanceof Te){var b=a.value_;return null==b?"":"string"===typeof b?b:a.value_=Le(b)}}}return a}
;function Xf(a,b,c){a=Xe(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function Yf(a,b,c,d,e,f){if(null!=a){if(Array.isArray(a))a=e&&0==a.length&&af(a)&1?void 0:f&&af(a)&2?a:Zf(a,b,c,void 0!==d,e,f);else if(mf(a)){var g={},h;for(h in a)g[h]=Yf(a[h],b,c,d,e,f);a=g}else a=b(a,d);return a}}
function Zf(a,b,c,d,e,f){var g=d||c?af(a):0;d=d?!!(g&32):void 0;a=Xe(a);for(var h=0;h<a.length;h++)a[h]=Yf(a[h],b,c,d,e,f);c&&c(g,a);return a}
function $f(a){return a.Jc===jf?a.toJSON():Wf(a)}
;function ag(a,b,c){c=void 0===c?gf:c;if(null!=a){if(Je&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=af(a);if(d&2)return a;b&&(b=0===d||!!(d&32)&&!(d&64||!(d&16)));return b?(bf(a,(d|34)&-12293),a):Zf(a,ag,d&4?gf:c,!0,!1,!0)}a.Jc===jf&&(c=a.D,d=df(c),a=d&2?a:Tf(a.constructor,bg(c,d,!0)));return a}}
function bg(a,b,c){var d=c||b&2?gf:ff,e=!!(b&32);a=Xf(a,b,function(f){return ag(f,e,d)});
Ze(a,32|(c?2:0));return a}
function cg(a){var b=a.D,c=df(b);return c&2?Tf(a.constructor,bg(b,c,!1)):a}
;Object.freeze({});Object.freeze({});function dg(a,b){a=a.D;return eg(a,df(a),b)}
function eg(a,b,c,d){if(-1===c)return null;if(c>=hf(b)){if(b&256)return a[a.length-1][c]}else{var e=a.length;if(d&&b&256&&(d=a[e-1][c],null!=d))return d;b=c+(+!!(b&512)-1);if(b<e)return a[b]}}
function G(a,b,c){var d=a.D,e=df(d);tf(e);fg(d,e,b,c);return a}
function fg(a,b,c,d,e){mf(d);var f=hf(b);if(c>=f||e){e=b;if(b&256)f=a[a.length-1];else{if(null==d)return e;f=a[f+(+!!(b&512)-1)]={};e|=256}f[c]=d;e!==b&&bf(a,e);return e}a[c+(+!!(b&512)-1)]=d;b&256&&(a=a[a.length-1],c in a&&delete a[c]);return b}
function gg(a){return void 0!==hg(a,ig,11,!1)}
function jg(a,b,c,d){var e=a.D,f=df(e);tf(f);if(null==c)return fg(e,f,b),a;var g=af(c),h=g,k=!!(2&g)||Object.isFrozen(c),l=!k&&!1;if(!(4&g))for(g=21,k&&(c=Xe(c),h=0,g=kg(g,f,!0)),k=0;k<c.length;k++)c[k]=d(c[k]);l&&(c=Xe(c),h=0,g=kg(g,f,!0));g!==h&&bf(c,g);fg(e,f,b,c);return a}
function lg(a,b,c,d){a=a.D;var e=df(a);tf(e);for(var f=e,g=0,h=0;h<c.length;h++){var k=c[h];null!=eg(a,f,k)&&(0!==g&&(f=fg(a,f,g)),g=k)}(c=g)&&c!==b&&null!=d&&(e=fg(a,e,c));fg(a,e,b,d)}
function hg(a,b,c,d){a=a.D;var e=df(a),f=eg(a,e,c,d);b=Rf(f,b,e);b!==f&&null!=b&&fg(a,e,c,b,d);return b}
function mg(a,b,c,d){d=void 0===d?!1:d;b=hg(a,b,c,d);if(null==b)return b;a=a.D;var e=df(a);if(!(e&2)){var f=cg(b);f!==b&&(b=f,fg(a,e,c,b,d))}return b}
function ng(a,b,c,d){null!=d?Qf(d,b):d=void 0;return G(a,c,d)}
function og(a,b,c,d){var e=a.D,f=df(e);tf(f);if(null==d)return fg(e,f,c),a;for(var g=af(d),h=g,k=!!(2&g)||!!(2048&g),l=k||Object.isFrozen(d),n=!l&&!1,p=!0,t=!0,r=0;r<d.length;r++){var u=d[r];Qf(u,b);k||(u=!!(af(u.D)&2),p&&(p=!u),t&&(t=u))}k||(g=cf(g,5,!0),g=cf(g,8,p),g=cf(g,16,t));if(n||l&&g!==h)d=Xe(d),h=0,g=kg(g,f,!0);g!==h&&bf(d,g);fg(e,f,c,d);return a}
function kg(a,b,c){a=cf(a,2,!!(2&b));a=cf(a,32,!!(32&b)&&c);return a=cf(a,2048,!1)}
function pg(a,b){a=dg(a,b);var c;null==a?c=a:Gf(a)?"number"===typeof a?c=Mf(a):c=Kf(a):c=void 0;return c}
function qg(a){a=dg(a,1);var b=void 0===b?!1:b;b=null==a?a:Gf(a)?"string"===typeof a?Kf(a):b?Lf(a):Mf(a):void 0;return b}
function rg(a){return pf(a,!1)}
function sg(a,b,c){null!=c&&(Number.isFinite(c)||Bf());return G(a,b,c)}
;function tg(a,b,c){this.D=Uf(a,b,c)}
m=tg.prototype;m.toJSON=function(){if(nf)var a=ug(this,this.D,!1);else a=Zf(this.D,$f,void 0,void 0,!1,!1),a=ug(this,a,!0);return a};
m.serialize=function(){nf=!0;try{return JSON.stringify(this.toJSON(),Vf)}finally{nf=!1}};
function vg(a,b){if(null==b||""==b)return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error(void 0);Ze(b,32);return Tf(a,b)}
m.clone=function(){var a=this.D,b=df(a);return Tf(this.constructor,bg(a,b,!1))};
m.Jc=jf;m.toString=function(){return ug(this,this.D,!1).toString()};
function ug(a,b,c){var d=a.constructor.Va,e=df(c?a.D:b),f=hf(e),g=!1;if(d&&of){if(!c){b=Xe(b);var h;if(b.length&&mf(h=b[b.length-1]))for(g=0;g<d.length;g++)if(d[g]>=f){Object.assign(b[b.length-1]={},h);break}g=!0}f=b;c=!c;h=df(a.D);a=hf(h);h=+!!(h&512)-1;for(var k,l,n=0;n<d.length;n++)if(l=d[n],l<a){l+=h;var p=f[l];null==p?f[l]=c?rf:ef():c&&p!==rf&&$e(p)}else k||(p=void 0,f.length&&mf(p=f[f.length-1])?k=p:f.push(k={})),p=k[l],null==k[l]?k[l]=c?rf:ef():c&&p!==rf&&$e(p)}k=b.length;if(!k)return b;var t;
if(mf(f=b[k-1])){a:{var r=f;c={};a=!1;for(var u in r){h=r[u];if(Array.isArray(h)){n=h;if(!We&&qf(h,d,+u)||!Ve&&lf(h)&&0===h.size)h=null;h!=n&&(a=!0)}null!=h?c[u]=h:a=!0}if(a){for(var y in c){r=c;break a}r=null}}r!=f&&(t=!0);k--}for(e=+!!(e&512)-1;0<k;k--){u=k-1;f=b[u];if(!(null==f||!We&&qf(f,d,u-e)||!Ve&&lf(f)&&0===f.size))break;var z=!0}if(!t&&!z)return b;var H;g?H=b:H=Array.prototype.slice.call(b,0,k);b=H;g&&(b.length=k);r&&b.push(r);return b}
;function wg(a){this.D=Uf(a)}
x(wg,tg);var xg=[1,2,3];function yg(a){this.D=Uf(a)}
x(yg,tg);var zg=[1,2,3];function Ag(a){this.D=Uf(a)}
x(Ag,tg);Ag.Va=[1];function Bg(a){this.D=Uf(a)}
x(Bg,tg);Bg.Va=[3,6,4];function Cg(a){this.D=Uf(a)}
x(Cg,tg);Cg.Va=[1];function Dg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.startsWith("blob:")&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==
c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Eg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var t=g,r=0;64>r;r+=4)t[r/4]=p[r]<<24|p[r+1]<<16|p[r+2]<<8|p[r+3];for(r=16;80>r;r++)p=t[r-3]^t[r-8]^t[r-14]^t[r-16],t[r]=(p<<1|p>>>31)&4294967295;p=e[0];var u=e[1],y=e[2],z=e[3],H=e[4];for(r=0;80>r;r++){if(40>r)if(20>r){var L=z^u&(y^z);var I=1518500249}else L=u^y^z,I=1859775393;else 60>r?(L=u&y|z&(u|y),I=2400959708):(L=u^y^z,I=3395469782);L=((p<<5|p>>>27)&4294967295)+L+H+I+t[r]&4294967295;H=z;z=y;y=(u<<30|u>>>2)&4294967295;u=p;p=L}e[0]=e[0]+p&4294967295;e[1]=e[1]+u&4294967295;e[2]=
e[2]+y&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+H&4294967295}
function c(p,t){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var r=[],u=0,y=p.length;u<y;++u)r.push(p.charCodeAt(u));p=r}t||(t=p.length);r=0;if(0==l)for(;r+64<t;)b(p.slice(r,r+64)),r+=64,n+=64;for(;r<t;)if(f[l++]=p[r++],n++,64==l)for(l=0,b(f);r+64<t;)b(p.slice(r,r+64)),r+=64,n+=64}
function d(){var p=[],t=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var r=63;56<=r;r--)f[r]=t&255,t>>>=8;b(f);for(r=t=0;5>r;r++)for(var u=24;0<=u;u-=8)p[t++]=e[r]>>u&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,Td:function(){for(var p=d(),t="",r=0;r<p.length;r++)t+="0123456789ABCDEF".charAt(Math.floor(p[r]/16))+"0123456789ABCDEF".charAt(p[r]%16);return t}}}
;function Fg(a,b,c){var d=String(B.location.href);return d&&a&&b?[b,Gg(Dg(d),a,c||null)].join(" "):null}
function Gg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],fb(d,function(h){e.push(h)}),Hg(e.join(" "));
var f=[],g=[];fb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];fb(d,function(h){e.push(h)});
a=Hg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Hg(a){var b=Eg();b.update(a);return b.Td().toLowerCase()}
;var Ig={};function Jg(a){this.h=a||{cookie:""}}
m=Jg.prototype;m.isEnabled=function(){if(!B.navigator.cookieEnabled)return!1;if(!this.Lb())return!0;this.set("TESTCOOKIESENABLED","1",{hc:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.hg;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.hc}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Ib(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{hc:0,path:b,domain:c});return d};
m.Cc=function(){return Kg(this).keys};
m.Lb=function(){return!this.h.cookie};
m.clear=function(){for(var a=Kg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function Kg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Ib(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var Lg=new Jg("undefined"==typeof document?null:document);function Mg(a){return!!Ig.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Ng(a){a=void 0===a?!1:a;var b=B.__SAPISID||B.__APISID||B.__3PSAPISID||B.__OVERRIDE_SID;Mg(a)&&(b=b||B.__1PSAPISID);if(b)return!0;if("undefined"!==typeof document){var c=new Jg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID")||c.get("OSID");Mg(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function Og(a,b,c,d){(a=B[a])||"undefined"===typeof document||(a=(new Jg(document)).get(b));return a?Fg(a,c,d):null}
function Pg(a,b){b=void 0===b?!1:b;var c=Dg(String(B.location.href)),d=[];if(Ng(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?B.__SAPISID:B.__APISID;e||"undefined"===typeof document||(e=new Jg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?Fg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Mg(b)&&((b=Og("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Og("__3PSAPISID","__Secure-3PAPISID",
"SAPISID3PHASH",a))&&d.push(a))}return 0==d.length?null:d.join(" ")}
;function Qg(a){this.D=Uf(a)}
x(Qg,tg);Qg.Va=[2];function Rg(a){xd.call(this);this.intervalMs=a;this.enabled=!1;this.i=function(){return Xa()};
this.j=this.i()}
x(Rg,xd);Rg.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
Rg.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.j=this.i())};
Rg.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
Rg.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.i()-this.j,0);b<.8*this.intervalMs?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),yd(this,"tick"),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function Sg(a){this.D=Uf(a)}
x(Sg,tg);function Tg(a){this.D=Uf(a)}
x(Tg,tg);function Ug(a){this.h=this.i=this.j=a}
Ug.prototype.reset=function(){this.h=this.i=this.j};
Ug.prototype.getValue=function(){return this.i};function Vg(a){this.D=Uf(a)}
x(Vg,tg);function Wg(a){this.D=Uf(a)}
x(Wg,tg);Wg.Va=[1];function ig(a){this.D=Uf(a)}
x(ig,tg);var Xg=["platform","platformVersion","architecture","model","uaFullVersion"];new Wg;function Yg(a){this.D=Uf(a)}
x(Yg,tg);function Zg(a){this.D=Uf(a)}
x(Zg,tg);function $g(a){this.D=Uf(a,35)}
x($g,tg);$g.Va=[3,20,27];function ah(a){this.D=Uf(a,19)}
x(ah,tg);ah.prototype.Rb=function(a){return sg(this,2,a)};
ah.Va=[3,5];function bh(a){this.D=Uf(a,7)}
x(bh,tg);var ch=function(a){return function(b){return vg(a,b)}}(bh);
bh.Va=[5,6];function dh(a){this.D=Uf(a)}
x(dh,tg);var eh;eh=new function(a,b,c){this.h=a;this.fieldName=b;this.ctor=c;this.isRepeated=0;this.i=mg;this.defaultValue=void 0}(175237375,{Uf:0},dh);function fh(a){F.call(this);var b=this;this.componentId="";this.i=[];this.na="";this.Ba=this.fa=-1;this.ha=!1;this.B=this.experimentIds=null;this.Z=this.ea=this.u=this.l=0;this.Ka=1;this.timeoutMillis=0;this.K=!1;this.logSource=a.logSource;this.rb=a.rb||function(){};
this.j=new gh(a.logSource,a.vb);this.network=a.network;this.Cb=a.Cb||null;this.bufferSize=1E3;this.nb=Wa(Cd,0,1);this.X=a.df||null;this.sessionIndex=a.sessionIndex||null;this.Jb=a.Jb||!1;this.pageId=a.pageId||null;this.logger=null;this.withCredentials=!a.dd;this.vb=a.vb||!1;var c=sg(new Yg,1,1);hh(this.j,c);this.m=new Ug(1E4);this.h=new Rg(this.m.getValue());a=ih(this,a.Wc);md(this.h,"tick",a,!1,this);this.T=new Rg(6E5);md(this.T,"tick",a,!1,this);this.Jb||this.T.start();this.vb||(md(document,"visibilitychange",
function(){"hidden"===document.visibilityState&&b.xc()}),md(document,"pagehide",this.xc,!1,this))}
x(fh,F);function ih(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
m=fh.prototype;m.S=function(){this.xc();this.h.stop();this.T.stop();F.prototype.S.call(this)};
function jh(a){a.X||(a.X=.01>a.nb()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.X}
function kh(a,b){a.m=new Ug(1>b?1:b);a.h.setInterval(a.m.getValue())}
m.log=function(a){a=a.clone();var b=this.Ka++;a=G(a,21,Jf(b));this.componentId&&G(a,26,Pf(this.componentId));qg(a)||(b=Date.now(),b=Number.isFinite(b)?b.toString():"0",G(a,1,Jf(b)));null==pg(a,15)&&G(a,15,Jf(60*(new Date).getTimezoneOffset()));this.experimentIds&&(b=this.experimentIds.clone(),ng(a,Qg,16,b));b=this.i.length-this.bufferSize+1;0<b&&(this.i.splice(0,b),this.l+=b);this.i.push(a);this.Jb||this.h.enabled||this.h.start()};
m.flush=function(a,b){var c=this;if(0===this.i.length)a&&a();else if(this.K)lh(this.j,3),mh(this);else{var d=Date.now();if(this.Ba>d&&this.fa<d)b&&b("throttled");else{lh(this.j,1);var e=nh(this.j,this.i,this.l,this.u,this.Cb,this.ea,this.Z);d={};var f=this.rb();f&&(d.Authorization=f);var g=jh(this);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,g=nc(g,"authuser",this.sessionIndex));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=nc(g,"pageId",this.pageId));if(f&&this.na===f)b&&b("stale-auth-token");
else{this.i=[];this.h.enabled&&this.h.stop();this.l=0;var h=e.serialize(),k;this.B&&this.B.isSupported(h.length)&&(k=this.B.compress(h));var l={url:g,body:h,Pd:1,Nc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},n=function(r){c.m.reset();c.h.setInterval(c.m.getValue());if(r){var u=null;try{var y=JSON.stringify(JSON.parse(r.replace(")]}'\n","")));u=ch(y)}catch(H){}if(u){r=Number;y="-1";y=void 0===y?"0":y;var z=qg(u);r=r(null!=z?z:y);0<r&&(c.fa=Date.now(),
c.Ba=c.fa+r);u=eh.ctor?eh.i(u,eh.ctor,eh.h,!0):eh.i(u,eh.h,null,!0);if(r=null===u?void 0:u)u=-1,u=void 0===u?0:u,r=If(dg(r,1)),u=null!=r?r:u,-1!==u&&(c.ha||kh(c,u))}}a&&a();c.u=0},p=function(r,u){var y=void 0===y?2:y;
var z=e.D;var H=df(z),L=!!(2&H),I=H;H=L?1:y;y=1===H;H=2===H;var da=!!(2&I)&&H,T=I;var N=T&2;I=eg(z,T,3);Array.isArray(I)||(I=rf);var ba=!!(T&32);T=af(I);0===T&&ba&&!N?(T|=33,bf(I,T)):T&1||(T|=1,bf(I,T));N&&(N=!1,T&2||(Ze(I,34),N=!!(4&T)),N&&Object.freeze(I));N=I;I=df(z);var J=af(N),ca=!!(2&J);T=!!(4&J);ba=!!(32&J);var ha=ca&&T||!!(2048&J);if(!T){var V=N,ab=I,Nc=!!(2&J);Nc&&(ab=cf(ab,2,!0));for(var Oc=!Nc,Pc=!0,X=0,Gi=0;X<V.length;X++){var Hi=Rf(V[X],$g,ab);if(Hi instanceof $g){if(!Nc){var hn=!!(af(Hi.D)&
2);Oc&&(Oc=!hn);Pc&&(Pc=hn)}V[Gi++]=Hi}}Gi<X&&(V.length=Gi);J=cf(J,4,!0);J=cf(J,16,Pc);J=cf(J,8,Oc);bf(V,J);ca&&!da&&(Object.freeze(N),ha=!0)}da=J;ca=!!(8&J)||y&&!N.length;if(!L&&!ca){ha&&(N=Xe(N),ha=!1,da=0,J=kg(J,I,!1),I=fg(z,I,3,N));L=N;ca=J;for(V=0;V<L.length;V++)J=L[V],ab=cg(J),J!==ab&&(L[V]=ab);ca=cf(ca,8,!0);J=ca=cf(ca,16,!L.length)}ha||(y?J=cf(J,!N.length||16&J&&(!T||ba)?2:2048,!0):J=cf(J,32,!1),J!==da&&bf(N,J),y&&(Object.freeze(N),ha=!0));H&&ha&&(N=Xe(N),J=kg(J,I,!1),bf(N,J),fg(z,I,3,N));
z=N;y=pg(e,14);H=c.m;H.h=Math.min(3E5,2*H.h);H.i=Math.min(3E5,H.h+Math.round(.2*(Math.random()-.5)*H.h));c.h.setInterval(c.m.getValue());401===r&&f&&(c.na=f);y&&(c.l+=y);void 0===u&&(u=c.isRetryable(r));u&&(c.i=z.concat(c.i),c.Jb||c.h.enabled||c.h.start());b&&b("net-send-failed",r);++c.u},t=function(){c.network&&c.network.send(l,n,p)};
k?k.then(function(r){l.Nc["Content-Encoding"]="gzip";l.Nc["Content-Type"]="application/binary";l.body=r;l.Pd=2;t()},function(){t()}):t()}}}};
m.xc=function(){oh(this.j,!0);this.flush();oh(this.j,!1)};
function mh(a){ph(a,function(b,c){b=nc(b,"format","json");var d=!1;try{d=window.navigator.sendBeacon(b,c.serialize())}catch(e){}a.K&&!d&&(a.K=!1);return d})}
function ph(a,b){if(0!==a.i.length){var c=rc(jh(a),"format");c=lc(c,"auth",a.rb(),"authuser",a.sessionIndex||"0");for(var d=0;10>d&&a.i.length;++d){var e=a.i.slice(0,32),f=nh(a.j,e,a.l,a.u,a.Cb,a.ea,a.Z);if(!b(c,f)){++a.u;break}a.l=0;a.u=0;a.ea=0;a.Z=0;a.i=a.i.slice(e.length)}a.h.enabled&&a.h.stop()}}
m.isRetryable=function(a){return 500<=a&&600>a||401===a||0===a};
function gh(a,b){this.vb=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new ah;Number.isInteger(a)&&this.h.Rb(a);b||(this.locale=document.documentElement.getAttribute("lang"));hh(this,new Yg)}
gh.prototype.Rb=function(a){this.h.Rb(a);return this};
function hh(a,b){ng(a.h,Yg,1,b);dg(b,1)||sg(b,1,1);if(!a.vb){b=qh(a);var c=dg(b,5);(null==c||"string"===typeof c)&&c||G(b,5,Pf(a.locale))}a.uach&&(b=qh(a),mg(b,Wg,9)||ng(b,Wg,9,a.uach))}
function lh(a,b){gg(rh(a))&&(a=sh(a),sg(a,1,b))}
function oh(a,b){gg(rh(a))&&(a=sh(a),G(a,2,Ef(b)))}
function rh(a){return mg(a.h,Yg,1)}
function th(a,b){var c=void 0===c?Xg:c;b(window,c).then(function(d){a.uach=d;d=qh(a);ng(d,Wg,9,a.uach);return!0}).catch(function(){return!1})}
function qh(a){a=rh(a);var b=mg(a,ig,11);b||(b=new ig,ng(a,ig,11,b));return b}
function sh(a){a=qh(a);var b=mg(a,Vg,10);b||(b=new Vg,G(b,2,Ef(!1)),ng(a,Vg,10,b));return b}
function nh(a,b,c,d,e,f,g){c=void 0===c?0:c;f=void 0===f?0:f;g=void 0===g?0:g;d=void 0===d?0:d;if(gg(rh(a))){var h=sh(a);G(h,3,Hf(d))}gg(rh(a))&&(d=sh(a),G(d,4,Hf(f)));gg(rh(a))&&(f=sh(a),G(f,5,Hf(g)));a=a.h.clone();g=Date.now().toString();a=G(a,4,Jf(g));b=og(a,$g,3,b);e&&(a=new Sg,e=G(a,13,Hf(e)),a=new Tg,e=ng(a,Sg,2,e),a=new Zg,e=ng(a,Tg,1,e),e=sg(e,2,9),ng(b,Zg,18,e));c&&G(b,14,Jf(c));return b}
;function uh(){}
uh.prototype.serialize=function(a){var b=[];vh(this,a,b);return b.join("")};
function vh(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),vh(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),wh(d,c),c.push(":"),vh(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":wh(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var xh={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},yh=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function wh(a,b){b.push('"',a.replace(yh,function(c){var d=xh[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),xh[c]=d);return d}),'"')}
;function zh(){}
zh.prototype.h=null;zh.prototype.getOptions=function(){var a;(a=this.h)||(a={},Ah(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var Bh;function Ch(){}
Ya(Ch,zh);function Dh(a){return(a=Ah(a))?new ActiveXObject(a):new XMLHttpRequest}
function Ah(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
Bh=new Ch;function Eh(a){xd.call(this);this.headers=new Map;this.T=a||null;this.i=!1;this.K=this.J=null;this.l=this.ea="";this.j=this.Z=this.u=this.X=!1;this.m=0;this.B=null;this.Ba="";this.ha=this.na=!1}
Ya(Eh,xd);var Fh=/^https?$/i,Gh=["POST","PUT"],Hh=[];function Ih(a,b,c,d,e,f,g){var h=new Eh;Hh.push(h);b&&h.listen("complete",b);h.h.add("ready",h.Rd,!0,void 0,void 0);f&&(h.m=Math.max(0,f));g&&(h.na=g);h.send(a,c,d,e)}
m=Eh.prototype;m.Rd=function(){this.dispose();kb(Hh,this)};
m.send=function(a,b,c,d){if(this.J)throw Error("[goog.net.XhrIo] Object is active with another request="+this.ea+"; newUri="+a);b=b?b.toUpperCase():"GET";this.ea=a;this.l="";this.X=!1;this.i=!0;this.J=this.T?Dh(this.T):Dh(Bh);this.K=this.T?this.T.getOptions():Bh.getOptions();this.J.onreadystatechange=Va(this.pd,this);try{this.getStatus(),this.Z=!0,this.J.open(b,String(a),!0),this.Z=!1}catch(g){this.getStatus();Jh(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=w(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=B.FormData&&a instanceof B.FormData;!(0<=eb(Gh,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=w(c);for(d=b.next();!d.done;d=b.next())c=w(d.value),d=c.next().value,c=c.next().value,this.J.setRequestHeader(d,c);this.Ba&&(this.J.responseType=this.Ba);"withCredentials"in this.J&&this.J.withCredentials!==this.na&&(this.J.withCredentials=this.na);try{Kh(this),0<this.m&&(this.ha=Lh(this.J),this.getStatus(),this.ha?(this.J.timeout=this.m,this.J.ontimeout=Va(this.Dd,
this)):this.B=le(this.Dd,this.m,this)),this.getStatus(),this.u=!0,this.J.send(a),this.u=!1}catch(g){this.getStatus(),Jh(this,g)}};
function Lh(a){return Kc&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
m.Dd=function(){"undefined"!=typeof La&&this.J&&(this.l="Timed out after "+this.m+"ms, aborting",this.getStatus(),yd(this,"timeout"),this.abort(8))};
function Jh(a,b){a.i=!1;a.J&&(a.j=!0,a.J.abort(),a.j=!1);a.l=b;Mh(a);Nh(a)}
function Mh(a){a.X||(a.X=!0,yd(a,"complete"),yd(a,"error"))}
m.abort=function(){this.J&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.J.abort(),this.j=!1,yd(this,"complete"),yd(this,"abort"),Nh(this))};
m.S=function(){this.J&&(this.i&&(this.i=!1,this.j=!0,this.J.abort(),this.j=!1),Nh(this,!0));Eh.Aa.S.call(this)};
m.pd=function(){this.aa()||(this.Z||this.u||this.j?Oh(this):this.ye())};
m.ye=function(){Oh(this)};
function Oh(a){if(a.i&&"undefined"!=typeof La)if(a.K[1]&&4==Ph(a)&&2==a.getStatus())a.getStatus();else if(a.u&&4==Ph(a))le(a.pd,0,a);else if(yd(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(Qh(a))yd(a,"complete"),yd(a,"success");else{try{var b=2<Ph(a)?a.J.statusText:""}catch(c){b=""}a.l=b+" ["+a.getStatus()+"]";Mh(a)}}finally{Nh(a)}}}
function Nh(a,b){if(a.J){Kh(a);var c=a.J,d=a.K[0]?function(){}:null;
a.J=null;a.K=null;b||yd(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Kh(a){a.J&&a.ha&&(a.J.ontimeout=null);a.B&&(B.clearTimeout(a.B),a.B=null)}
m.isActive=function(){return!!this.J};
m.isComplete=function(){return 4==Ph(this)};
function Qh(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=cc(1,String(a.ea)),!a&&B.self&&B.self.location&&(a=B.self.location.protocol.slice(0,-1)),b=!Fh.test(a?a.toLowerCase():"");c=b}return c}
function Ph(a){return a.J?a.J.readyState:0}
m.getStatus=function(){try{return 2<Ph(this)?this.J.status:-1}catch(a){return-1}};
m.getLastError=function(){return"string"===typeof this.l?this.l:String(this.l)};function Rh(){}
Rh.prototype.send=function(a,b,c){b=void 0===b?function(){}:b;
c=void 0===c?function(){}:c;
Ih(a.url,function(d){d=d.target;if(Qh(d)){try{var e=d.J?d.J.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Nc,a.timeoutMillis,a.withCredentials)};function Sh(a,b){F.call(this);this.logSource=a;this.sessionIndex=b;this.i="https://play.google.com/log?format=json&hasfast=true";this.j=!1;this.componentId="";this.network=new Rh}
x(Sh,F);Sh.prototype.dd=function(){this.X=!0;return this};function Th(a,b,c,d,e,f){a=void 0===a?-1:a;b=void 0===b?"":b;c=void 0===c?"":c;d=void 0===d?!1:d;e=void 0===e?"":e;F.call(this);this.logSource=a;this.componentId=b;f?a=f:(a=new Sh(a,"0"),a.componentId=b,yc(this,a),""!==c&&(a.i=c),d&&(a.j=!0),e&&(a.h=e),b=new fh({logSource:a.logSource,rb:a.rb?a.rb:Pg,sessionIndex:a.sessionIndex,df:a.i,vb:a.j,Jb:!1,dd:a.X,pageId:a.pageId,Wc:a.Wc,network:a.network?a.network:void 0}),yc(a,b),a.u&&hh(b.j,a.u),a.h&&(c=a.h,d=qh(b.j),G(d,7,Pf(c))),a.m&&(b.B=a.m),a.componentId&&
(b.componentId=a.componentId),a.Cb&&(b.Cb=a.Cb),a.l&&((c=a.l)?(b.experimentIds||(b.experimentIds=new Qg),c=c.serialize(),G(b.experimentIds,4,Pf(c))):b.experimentIds&&G(b.experimentIds,4)),a.K&&(c=a.K,b.experimentIds||(b.experimentIds=new Qg),jg(b.experimentIds,2,c,rg)),a.B&&(c=a.B,b.ha=!0,kh(b,c)),a.T&&th(b.j,a.T),a.network.Rb&&a.network.Rb(a.logSource),a.network.Se&&a.network.Se(b),a=b);this.h=a}
x(Th,F);
Th.prototype.flush=function(a){var b=a||[];if(b.length){a=new Cg;for(var c=[],d=0;d<b.length;d++){var e=b[d];var f=new Bg;f=G(f,1,Pf(e.j));for(var g=[],h=0;h<e.i.length;h++)g.push(e.i[h].Ca);f=jg(f,3,g,Of);g=[];h=[];for(var k=w(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var n=e.m;for(var p=e.zc(l)||[],t=[],r=0;r<p.length;r++){var u=p[r],y=u&&u.h;u=new yg;switch(n){case 3:y=Number(y);Number.isFinite(y)&&lg(u,1,zg,Jf(y));break;case 2:y=Number(y);
if(null!=y&&"number"!==typeof y)throw Error("Value of float/double field must be a number, found "+typeof y+": "+y);lg(u,2,zg,y)}t.push(u)}n=t;for(p=0;p<n.length;p++){t=n[p];r=new Ag;t=ng(r,yg,2,t);r=l;u=[];y=[];for(var z=0;z<e.i.length;z++)y.push(e.i[z].Da);for(z=0;z<y.length;z++){var H=y[z],L=r[z],I=new wg;switch(H){case 3:lg(I,1,xg,Pf(String(L)));break;case 2:H=Number(L);Number.isFinite(H)&&lg(I,2,xg,Hf(H));break;case 1:lg(I,3,xg,Ef("true"===L))}u.push(I)}og(t,wg,1,u);g.push(t)}}og(f,Ag,4,g);c.push(f);
e.clear()}og(a,Bg,1,c);b=this.h;a instanceof $g?b.log(a):(c=new $g,a=a.serialize(),a=G(c,8,Pf(a)),b.log(a));this.h.flush()}};function Uh(a,b){this.h=b;this.m=void 0;this.B=new Th(1828);this.i=new me(this.B);this.K=new te(this.i);this.H=new ue(this.i);this.u=new ve(this.i);this.l=new re(this.i);this.j=xe(a);(new qe(this.i)).h.Ub("/client_streamz/bg/fic",this.h)}
function Vh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Wh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Xh(a){function b(z,H,L){Promise.resolve().then(function(){var I;null!=(I=c.ra)&&void 0!==I.m&&I.K.record(Vh()-I.m,I.j,I.h);h.resolve({Nd:z,Ve:H,dg:L})})}
var c=this;this.h=!1;var d=a.program;var e=a.ee;if(!1!==a.Ee){var f,g;this.ra=null!=(g=a.ra)?g:new Uh(e,null!=(f=a.cg)?f:"_")}var h=new Wh;this.i=h.promise;if(!B[e]){var k;null!=(k=this.ra)&&se(k.l,k.j,k.h,1,"");var l;null!=(l=this.ra)&&l.i.mb()}else if(!B[e].a){var n;null!=(n=this.ra)&&se(n.l,n.j,n.h,2,"");var p;null!=(p=this.ra)&&p.i.mb()}try{var t=B[e].a,r;null!=(r=this.ra)&&(r.m=Vh());this.j=w(t(d,b,!0,a.mg)).next().value;this.Ue=h.promise.then(function(){})}catch(z){var u;
null!=(u=this.ra)&&se(u.l,u.j,u.h,4,z.message);var y;null!=(y=this.ra)&&y.i.mb();throw z;}}
Xh.prototype.snapshot=function(a){var b=this;if(this.h)throw Error("Already disposed");var c=Vh(),d;null!=(d=this.ra)&&d.H.h.Ub("/client_streamz/bg/fsc",d.j,d.h);return this.i.then(function(e){var f=e.Nd;return new Promise(function(g){f(function(h){var k;null!=(k=b.ra)&&k.u.record(Vh()-c,k.j,k.h);g(h)},[a.cd,
a.We,a.ff])})})};
Xh.prototype.Ad=function(a){if(this.h)throw Error("Already disposed");var b=Vh(),c;null!=(c=this.ra)&&c.H.h.Ub("/client_streamz/bg/fsc",c.j,c.h);a=this.j([a.cd,a.We,a.ff]);var d;null!=(d=this.ra)&&d.u.record(Vh()-b,d.j,d.h);return a};
Xh.prototype.dispose=function(){var a;null!=(a=this.ra)&&a.i.mb();this.h=!0;this.i.then(function(b){(b=b.Ve)&&b()})};
Xh.prototype.aa=function(){return this.h};var Yh=window;Ab("csi.gstatic.com");Ab("googleads.g.doubleclick.net");Ab("partner.googleadservices.com");Ab("pubads.g.doubleclick.net");Ab("securepubads.g.doubleclick.net");Ab("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Zh=ka([""]),$h=la(["\x00"],["\\0"]),ai=la(["\n"],["\\n"]),bi=la(["\x00"],["\\u0000"]);function ci(a){return-1===a.toString().indexOf("`")}
ci(function(a){return a(Zh)})||ci(function(a){return a($h)})||ci(function(a){return a(ai)})||ci(function(a){return a(bi)});function di(a){this.pe=a}
function ei(a){return new di(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var fi=[ei("data"),ei("http"),ei("https"),ei("mailto"),ei("ftp"),new di(function(a){return/^[^:]*([/?#]|$)/.test(a)})],gi="function"===typeof URL;
function hi(a){if(a instanceof Jb)a instanceof Jb&&a.constructor===Jb?a=a.h:(Na(a),a="type_error:SafeUrl");else{b:if(gi){try{var b=new URL(a)}catch(c){b="https:";break b}b=b.protocol}else c:{b=document.createElement("a");try{b.href=a}catch(c){b=void 0;break c}b=b.protocol;b=":"===b||""===b?"https:":b}a="javascript:"!==b?a:void 0}return a}
;function ii(a,b){b=hi(b);void 0!==b&&(a.href=b)}
;var ji={};function ki(){}
function li(a){this.h=a}
x(li,ki);li.prototype.toString=function(){return this.h};function mi(a){var b="true".toString(),c=[new li(ni[0].toLowerCase(),ji)];if(0===c.length)throw Error("");if(c.map(function(d){if(d instanceof li)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function oi(){throw Error("unknown trace type");}
;var pi="alternate author bookmark canonical cite help icon license next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function qi(a,b){if(b instanceof Eb)a.href=Fb(b).toString();else{if(-1===pi.indexOf("stylesheet"))throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=hi(b);if(void 0===b)return;a.href=b}a.rel="stylesheet"}
;function ri(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function si(a,b){a.src=Fb(b);ri(a)}
;function ti(a){var b=ui;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function vi(){var a=[];ti(function(b){a.push(b)});
return a}
var ui={gf:"allow-forms",hf:"allow-modals",jf:"allow-orientation-lock",kf:"allow-pointer-lock",lf:"allow-popups",mf:"allow-popups-to-escape-sandbox",nf:"allow-presentation",pf:"allow-same-origin",qf:"allow-scripts",rf:"allow-top-navigation",sf:"allow-top-navigation-by-user-activation"},wi=db(function(){return vi()});
function xi(){var a=yi(),b={};fb(wi(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function yi(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function zi(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Ai=(new Date).getTime();"undefined"!==typeof TextDecoder&&new TextDecoder;var Bi="undefined"!==typeof TextEncoder?new TextEncoder:null,Ci=Bi?function(a){return Bi.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function Di(a){xd.call(this);var b=this;this.u=this.j=0;this.Fa=null!=a?a:{oa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.l=function(){return A(function(e){return e.yield(Ei(b),0)})};
window.addEventListener("offline",this.l);window.addEventListener("online",this.l);this.u||Fi(this)}
x(Di,xd);function Ii(){var a=Ji;Di.h||(Di.h=new Di(a));return Di.h}
Di.prototype.dispose=function(){window.removeEventListener("offline",this.l);window.removeEventListener("online",this.l);this.Fa.qa(this.u);delete Di.h};
Di.prototype.wa=function(){return this.i};
function Fi(a){a.u=a.Fa.oa(function(){var b;return A(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.A(3):c.yield(Ei(a),3):c.yield(Ei(a),3);Fi(a);c.h=0})},3E4)}
function Ei(a,b){return a.m?a.m:a.m=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,za(h,2,3),d&&(a.j=a.Fa.oa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.K=[h.j];h.l=0;h.H=0;a.m=void 0;a.j&&(a.Fa.qa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?yd(a,"networkstatus-online"):yd(a,"networkstatus-offline"));c(g);Ba(h);break;case 2:Aa(h),g=!1,h.A(3)}})})}
;function Ki(){this.data=[];this.h=-1}
Ki.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Ki.prototype.get=function(a){return!!this.data[a]};
function Li(a){-1===a.h&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function Mi(a,b){this.h=a[B.Symbol.iterator]();this.i=b}
Mi.prototype[Symbol.iterator]=function(){return this};
Mi.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function Ni(a,b){return new Mi(a,b)}
;function Oi(){this.blockSize=-1}
;function Pi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.H=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
Ya(Pi,Oi);Pi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function Qi(a,b,c){c||(c=0);var d=a.H;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
Pi.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)Qi(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Qi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Qi(this,e);f=0;break}}this.i=f;this.l+=b}};
Pi.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;Qi(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Ri(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Si(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Ti(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Ri(a).match(/\S+/g)||[],b=0<=eb(a,b));return b}
function Ui(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Ti(a,"inverted-hdpi")&&Si(a,Array.prototype.filter.call(a.classList?a.classList:Ri(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function Vi(){}
Vi.prototype.next=function(){return Wi};
var Wi={done:!0,value:void 0};function Xi(a){return{value:a,done:!1}}
Vi.prototype.Ha=function(){return this};function Yi(a){if(a instanceof Zi||a instanceof $i||a instanceof aj)return a;if("function"==typeof a.next)return new Zi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Zi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Ha)return new Zi(function(){return a.Ha()});
throw Error("Not an iterator or iterable.");}
function Zi(a){this.i=a}
Zi.prototype.Ha=function(){return new $i(this.i())};
Zi.prototype[Symbol.iterator]=function(){return new aj(this.i())};
Zi.prototype.h=function(){return new aj(this.i())};
function $i(a){this.i=a}
x($i,Vi);$i.prototype.next=function(){return this.i.next()};
$i.prototype[Symbol.iterator]=function(){return new aj(this.i)};
$i.prototype.h=function(){return new aj(this.i)};
function aj(a){Zi.call(this,function(){return a});
this.j=a}
x(aj,Zi);aj.prototype.next=function(){return this.j.next()};function bj(a,b){this.i={};this.h=[];this.Xa=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof bj)for(c=a.Cc(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
m=bj.prototype;m.Cc=function(){cj(this);return this.h.concat()};
m.has=function(a){return dj(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||ej;cj(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function ej(a,b){return a===b}
m.Lb=function(){return 0==this.size};
m.clear=function(){this.i={};this.Xa=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return dj(this.i,a)?(delete this.i[a],--this.size,this.Xa++,this.h.length>2*this.size&&cj(this),!0):!1};
function cj(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];dj(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],dj(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return dj(this.i,a)?this.i[a]:b};
m.set=function(a,b){dj(this.i,a)||(this.size+=1,this.h.push(a),this.Xa++);this.i[a]=b};
m.forEach=function(a,b){for(var c=this.Cc(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new bj(this)};
m.keys=function(){return Yi(this.Ha(!0)).h()};
m.values=function(){return Yi(this.Ha(!1)).h()};
m.entries=function(){var a=this;return Ni(this.keys(),function(b){return[b,a.get(b)]})};
m.Ha=function(a){cj(this);var b=0,c=this.Xa,d=this,e=new Vi;e.next=function(){if(c!=d.Xa)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return Wi;var f=d.h[b++];return Xi(a?f:d.i[f])};
return e};
function dj(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function K(a){F.call(this);this.m=1;this.j=[];this.l=0;this.h=[];this.i={};this.u=!!a}
Ya(K,F);m=K.prototype;m.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.m;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.m=e+3;d.push(e);return e};
m.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.Eb(a)}return!1};
m.Eb=function(a){var b=this.h[a];if(b){var c=this.i[b];0!=this.l?(this.j.push(a),this.h[a+1]=function(){}):(c&&kb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
m.Za=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.u)for(e=0;e<c.length;e++){var g=c[e];fj(this.h[g+1],this.h[g+2],d)}else{this.l++;try{for(e=0,f=c.length;e<f&&!this.aa();e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.l--,0<this.j.length&&0==this.l)for(;c=this.j.pop();)this.Eb(c)}}return 0!=e}return!1};
function fj(a,b,c){Rd(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.Eb,this),delete this.i[a])}else this.h.length=0,this.i={}};
m.S=function(){K.Aa.S.call(this);this.clear();this.j.length=0};function gj(a){this.h=a}
gj.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,(new uh).serialize(b))};
gj.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
gj.prototype.remove=function(a){this.h.remove(a)};function hj(a){this.h=a}
Ya(hj,gj);function ij(a){this.data=a}
function jj(a){return void 0===a||a instanceof ij?a:new ij(a)}
hj.prototype.set=function(a,b){hj.Aa.set.call(this,a,jj(b))};
hj.prototype.i=function(a){a=hj.Aa.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
hj.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function kj(a){this.h=a}
Ya(kj,hj);kj.prototype.set=function(a,b,c){if(b=jj(b)){if(c){if(c<Xa()){kj.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Xa()}kj.Aa.set.call(this,a,b)};
kj.prototype.i=function(a){var b=kj.Aa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Xa()||c&&c>Xa())kj.prototype.remove.call(this,a);else return b}};function lj(){}
;function mj(){}
Ya(mj,lj);mj.prototype[Symbol.iterator]=function(){return Yi(this.Ha(!0)).h()};
mj.prototype.clear=function(){var a=Array.from(this);a=w(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function nj(a){this.h=a}
Ya(nj,mj);m=nj.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.Ha=function(a){var b=0,c=this.h,d=new Vi;d.next=function(){if(b>=c.length)return Wi;var e=c.key(b++);if(a)return Xi(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Xi(e)};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function oj(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
Ya(oj,nj);function pj(a,b){this.i=a;this.h=null;var c;if(c=Kc)c=!(9<=Number($c));if(c){qj||(qj=new bj);this.h=qj.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),qj.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
Ya(pj,mj);var rj={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},qj=null;function sj(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return rj[b]})}
m=pj.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(sj(a),b);tj(this)};
m.get=function(a){a=this.h.getAttribute(sj(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(sj(a));tj(this)};
m.Ha=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new Vi;d.next=function(){if(b>=c.length)return Wi;var e=c[b++];if(a)return Xi(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Xi(e)};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);tj(this)};
function tj(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function uj(a,b){this.i=a;this.h=b+"::"}
Ya(uj,mj);uj.prototype.set=function(a,b){this.i.set(this.h+a,b)};
uj.prototype.get=function(a){return this.i.get(this.h+a)};
uj.prototype.remove=function(a){this.i.remove(this.h+a)};
uj.prototype.Ha=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Vi;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return Xi(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var M={},vj="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;M.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
M.Qc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var wj={ob:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
gd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},xj={ob:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
gd:function(a){return[].concat.apply([],a)}};
M.Te=function(){vj?(M.lb=Uint8Array,M.Ja=Uint16Array,M.Jd=Int32Array,M.assign(M,wj)):(M.lb=Array,M.Ja=Array,M.Jd=Array,M.assign(M,xj))};
M.Te();var yj=!0;try{new Uint8Array(1)}catch(a){yj=!1}
function zj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new M.lb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var Aj={};Aj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var Bj={},Cj,Dj=[],Ej=0;256>Ej;Ej++){Cj=Ej;for(var Fj=0;8>Fj;Fj++)Cj=Cj&1?3988292384^Cj>>>1:Cj>>>1;Dj[Ej]=Cj}Bj=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^Dj[(a^b[d])&255];return a^-1};var Gj={};Gj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function Hj(a){for(var b=a.length;0<=--b;)a[b]=0}
var Ij=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],Jj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],Kj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],Lj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],Mj=Array(576);Hj(Mj);var Nj=Array(60);Hj(Nj);var Oj=Array(512);Hj(Oj);var Pj=Array(256);Hj(Pj);var Qj=Array(29);Hj(Qj);var Rj=Array(30);Hj(Rj);function Sj(a,b,c,d,e){this.Bd=a;this.Zd=b;this.Yd=c;this.Ud=d;this.ue=e;this.kd=a&&a.length}
var Tj,Uj,Vj;function Wj(a,b){this.ed=a;this.zb=0;this.Wa=b}
function Xj(a,b){a.W[a.pending++]=b&255;a.W[a.pending++]=b>>>8&255}
function Yj(a,b,c){a.ga>16-c?(a.ma|=b<<a.ga&65535,Xj(a,a.ma),a.ma=b>>16-a.ga,a.ga+=c-16):(a.ma|=b<<a.ga&65535,a.ga+=c)}
function Zj(a,b,c){Yj(a,c[2*b],c[2*b+1])}
function ak(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function bk(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=ak(d[e]++,e))}
function ck(a){var b;for(b=0;286>b;b++)a.sa[2*b]=0;for(b=0;30>b;b++)a.bb[2*b]=0;for(b=0;19>b;b++)a.ia[2*b]=0;a.sa[512]=1;a.Qa=a.Db=0;a.ya=a.matches=0}
function dk(a){8<a.ga?Xj(a,a.ma):0<a.ga&&(a.W[a.pending++]=a.ma);a.ma=0;a.ga=0}
function ek(a,b,c){dk(a);Xj(a,c);Xj(a,~c);M.ob(a.W,a.window,b,c,a.pending);a.pending+=c}
function fk(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function gk(a,b,c){for(var d=a.Y[c],e=c<<1;e<=a.Oa;){e<a.Oa&&fk(b,a.Y[e+1],a.Y[e],a.depth)&&e++;if(fk(b,d,a.Y[e],a.depth))break;a.Y[c]=a.Y[e];c=e;e<<=1}a.Y[c]=d}
function hk(a,b,c){var d=0;if(0!==a.ya){do{var e=a.W[a.Ib+2*d]<<8|a.W[a.Ib+2*d+1];var f=a.W[a.Gc+d];d++;if(0===e)Zj(a,f,b);else{var g=Pj[f];Zj(a,g+256+1,b);var h=Ij[g];0!==h&&(f-=Qj[g],Yj(a,f,h));e--;g=256>e?Oj[e]:Oj[256+(e>>>7)];Zj(a,g,c);h=Jj[g];0!==h&&(e-=Rj[g],Yj(a,e,h))}}while(d<a.ya)}Zj(a,256,b)}
function ik(a,b){var c=b.ed,d=b.Wa.Bd,e=b.Wa.kd,f=b.Wa.Ud,g,h=-1;a.Oa=0;a.tb=573;for(g=0;g<f;g++)0!==c[2*g]?(a.Y[++a.Oa]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.Oa;){var k=a.Y[++a.Oa]=2>h?++h:0;c[2*k]=1;a.depth[k]=0;a.Qa--;e&&(a.Db-=d[2*k+1])}b.zb=h;for(g=a.Oa>>1;1<=g;g--)gk(a,c,g);k=f;do g=a.Y[1],a.Y[1]=a.Y[a.Oa--],gk(a,c,1),d=a.Y[1],a.Y[--a.tb]=g,a.Y[--a.tb]=d,c[2*k]=c[2*g]+c[2*d],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=k,a.Y[1]=k++,gk(a,c,1);while(2<=a.Oa);a.Y[--a.tb]=
a.Y[1];g=b.ed;k=b.zb;d=b.Wa.Bd;e=b.Wa.kd;f=b.Wa.Zd;var l=b.Wa.Yd,n=b.Wa.ue,p,t=0;for(p=0;15>=p;p++)a.La[p]=0;g[2*a.Y[a.tb]+1]=0;for(b=a.tb+1;573>b;b++){var r=a.Y[b];p=g[2*g[2*r+1]+1]+1;p>n&&(p=n,t++);g[2*r+1]=p;if(!(r>k)){a.La[p]++;var u=0;r>=l&&(u=f[r-l]);var y=g[2*r];a.Qa+=y*(p+u);e&&(a.Db+=y*(d[2*r+1]+u))}}if(0!==t){do{for(p=n-1;0===a.La[p];)p--;a.La[p]--;a.La[p+1]+=2;a.La[n]--;t-=2}while(0<t);for(p=n;0!==p;p--)for(r=a.La[p];0!==r;)d=a.Y[--b],d>k||(g[2*d+1]!==p&&(a.Qa+=(p-g[2*d+1])*g[2*d],g[2*
d+1]=p),r--)}bk(c,h,a.La)}
function jk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];++g<h&&l===f||(g<k?a.ia[2*l]+=g:0!==l?(l!==e&&a.ia[2*l]++,a.ia[32]++):10>=g?a.ia[34]++:a.ia[36]++,g=0,e=l,0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function kk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];if(!(++g<h&&l===f)){if(g<k){do Zj(a,l,a.ia);while(0!==--g)}else 0!==l?(l!==e&&(Zj(a,l,a.ia),g--),Zj(a,16,a.ia),Yj(a,g-3,2)):10>=g?(Zj(a,17,a.ia),Yj(a,g-3,3)):(Zj(a,18,a.ia),Yj(a,g-11,7));g=0;e=l;0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function lk(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.sa[2*c])return 0;if(0!==a.sa[18]||0!==a.sa[20]||0!==a.sa[26])return 1;for(c=32;256>c;c++)if(0!==a.sa[2*c])return 1;return 0}
var mk=!1;function nk(a,b,c){a.W[a.Ib+2*a.ya]=b>>>8&255;a.W[a.Ib+2*a.ya+1]=b&255;a.W[a.Gc+a.ya]=c&255;a.ya++;0===b?a.sa[2*c]++:(a.matches++,b--,a.sa[2*(Pj[c]+256+1)]++,a.bb[2*(256>b?Oj[b]:Oj[256+(b>>>7)])]++);return a.ya===a.Mb-1}
;function ok(a,b){a.msg=Gj[b];return b}
function pk(a){for(var b=a.length;0<=--b;)a[b]=0}
function qk(a){var b=a.state,c=b.pending;c>a.P&&(c=a.P);0!==c&&(M.ob(a.output,b.W,b.Pb,c,a.Ab),a.Ab+=c,b.Pb+=c,a.Rc+=c,a.P-=c,b.pending-=c,0===b.pending&&(b.Pb=0))}
function rk(a,b){var c=0<=a.va?a.va:-1,d=a.o-a.va,e=0;if(0<a.level){2===a.I.wc&&(a.I.wc=lk(a));ik(a,a.fc);ik(a,a.ac);jk(a,a.sa,a.fc.zb);jk(a,a.bb,a.ac.zb);ik(a,a.Xc);for(e=18;3<=e&&0===a.ia[2*Lj[e]+1];e--);a.Qa+=3*(e+1)+14;var f=a.Qa+3+7>>>3;var g=a.Db+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)Yj(a,b?1:0,3),ek(a,c,d);else if(4===a.strategy||g===f)Yj(a,2+(b?1:0),3),hk(a,Mj,Nj);else{Yj(a,4+(b?1:0),3);c=a.fc.zb+1;d=a.ac.zb+1;e+=1;Yj(a,c-257,5);Yj(a,d-1,5);Yj(a,e-4,4);for(f=0;f<e;f++)Yj(a,a.ia[2*
Lj[f]+1],3);kk(a,a.sa,c-1);kk(a,a.bb,d-1);hk(a,a.sa,a.bb)}ck(a);b&&dk(a);a.va=a.o;qk(a.I)}
function O(a,b){a.W[a.pending++]=b}
function sk(a,b){a.W[a.pending++]=b>>>8&255;a.W[a.pending++]=b&255}
function tk(a,b){var c=a.nd,d=a.o,e=a.xa,f=a.od,g=a.o>a.ka-262?a.o-(a.ka-262):0,h=a.window,k=a.Ya,l=a.Ia,n=a.o+258,p=h[d+e-1],t=h[d+e];a.xa>=a.jd&&(c>>=2);f>a.v&&(f=a.v);do{var r=b;if(h[r+e]===t&&h[r+e-1]===p&&h[r]===h[d]&&h[++r]===h[d+1]){d+=2;for(r++;h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&d<n;);r=258-(n-d);d=n-258;if(r>e){a.yb=b;e=r;if(r>=f)break;p=h[d+e-1];t=h[d+e]}}}while((b=l[b&k])>g&&0!==--c);return e<=
a.v?e:a.v}
function uk(a){var b=a.ka,c;do{var d=a.Hd-a.v-a.o;if(a.o>=b+(b-262)){M.ob(a.window,a.window,b,b,0);a.yb-=b;a.o-=b;a.va-=b;var e=c=a.ec;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.I.la)break;e=a.I;c=a.window;f=a.o+a.v;var g=e.la;g>d&&(g=d);0===g?c=0:(e.la-=g,M.ob(c,e.input,e.hb,g,f),1===e.state.wrap?e.G=Aj(e.G,c,g,f):2===e.state.wrap&&(e.G=Bj(e.G,c,g,f)),e.hb+=g,e.kb+=g,c=g);a.v+=c;if(3<=a.v+a.ta)for(d=a.o-a.ta,a.M=a.window[d],
a.M=(a.M<<a.Na^a.window[d+1])&a.Ma;a.ta&&!(a.M=(a.M<<a.Na^a.window[d+3-1])&a.Ma,a.Ia[d&a.Ya]=a.head[a.M],a.head[a.M]=d,d++,a.ta--,3>a.v+a.ta););}while(262>a.v&&0!==a.I.la)}
function vk(a,b){for(var c;;){if(262>a.v){uk(a);if(262>a.v&&0===b)return 1;if(0===a.v)break}c=0;3<=a.v&&(a.M=(a.M<<a.Na^a.window[a.o+3-1])&a.Ma,c=a.Ia[a.o&a.Ya]=a.head[a.M],a.head[a.M]=a.o);0!==c&&a.o-c<=a.ka-262&&(a.R=tk(a,c));if(3<=a.R)if(c=nk(a,a.o-a.yb,a.R-3),a.v-=a.R,a.R<=a.Hc&&3<=a.v){a.R--;do a.o++,a.M=(a.M<<a.Na^a.window[a.o+3-1])&a.Ma,a.Ia[a.o&a.Ya]=a.head[a.M],a.head[a.M]=a.o;while(0!==--a.R);a.o++}else a.o+=a.R,a.R=0,a.M=a.window[a.o],a.M=(a.M<<a.Na^a.window[a.o+1])&a.Ma;else c=nk(a,0,
a.window[a.o]),a.v--,a.o++;if(c&&(rk(a,!1),0===a.I.P))return 1}a.ta=2>a.o?a.o:2;return 4===b?(rk(a,!0),0===a.I.P?3:4):a.ya&&(rk(a,!1),0===a.I.P)?1:2}
function wk(a,b){for(var c,d;;){if(262>a.v){uk(a);if(262>a.v&&0===b)return 1;if(0===a.v)break}c=0;3<=a.v&&(a.M=(a.M<<a.Na^a.window[a.o+3-1])&a.Ma,c=a.Ia[a.o&a.Ya]=a.head[a.M],a.head[a.M]=a.o);a.xa=a.R;a.rd=a.yb;a.R=2;0!==c&&a.xa<a.Hc&&a.o-c<=a.ka-262&&(a.R=tk(a,c),5>=a.R&&(1===a.strategy||3===a.R&&4096<a.o-a.yb)&&(a.R=2));if(3<=a.xa&&a.R<=a.xa){d=a.o+a.v-3;c=nk(a,a.o-1-a.rd,a.xa-3);a.v-=a.xa-1;a.xa-=2;do++a.o<=d&&(a.M=(a.M<<a.Na^a.window[a.o+3-1])&a.Ma,a.Ia[a.o&a.Ya]=a.head[a.M],a.head[a.M]=a.o);
while(0!==--a.xa);a.fb=0;a.R=2;a.o++;if(c&&(rk(a,!1),0===a.I.P))return 1}else if(a.fb){if((c=nk(a,0,a.window[a.o-1]))&&rk(a,!1),a.o++,a.v--,0===a.I.P)return 1}else a.fb=1,a.o++,a.v--}a.fb&&(nk(a,0,a.window[a.o-1]),a.fb=0);a.ta=2>a.o?a.o:2;return 4===b?(rk(a,!0),0===a.I.P?3:4):a.ya&&(rk(a,!1),0===a.I.P)?1:2}
function xk(a,b){for(var c,d,e,f=a.window;;){if(258>=a.v){uk(a);if(258>=a.v&&0===b)return 1;if(0===a.v)break}a.R=0;if(3<=a.v&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.R=258-(e-d);a.R>a.v&&(a.R=a.v)}3<=a.R?(c=nk(a,1,a.R-3),a.v-=a.R,a.o+=a.R,a.R=0):(c=nk(a,0,a.window[a.o]),a.v--,a.o++);if(c&&(rk(a,!1),0===a.I.P))return 1}a.ta=0;return 4===b?(rk(a,!0),0===a.I.P?3:4):
a.ya&&(rk(a,!1),0===a.I.P)?1:2}
function yk(a,b){for(var c;;){if(0===a.v&&(uk(a),0===a.v)){if(0===b)return 1;break}a.R=0;c=nk(a,0,a.window[a.o]);a.v--;a.o++;if(c&&(rk(a,!1),0===a.I.P))return 1}a.ta=0;return 4===b?(rk(a,!0),0===a.I.P?3:4):a.ya&&(rk(a,!1),0===a.I.P)?1:2}
function zk(a,b,c,d,e){this.ge=a;this.te=b;this.xe=c;this.se=d;this.be=e}
var Ak;Ak=[new zk(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(1>=a.v){uk(a);if(0===a.v&&0===b)return 1;if(0===a.v)break}a.o+=a.v;a.v=0;var d=a.va+c;if(0===a.o||a.o>=d)if(a.v=a.o-d,a.o=d,rk(a,!1),0===a.I.P)return 1;if(a.o-a.va>=a.ka-262&&(rk(a,!1),0===a.I.P))return 1}a.ta=0;if(4===b)return rk(a,!0),0===a.I.P?3:4;a.o>a.va&&rk(a,!1);return 1}),
new zk(4,4,8,4,vk),new zk(4,5,16,8,vk),new zk(4,6,32,32,vk),new zk(4,4,16,16,wk),new zk(8,16,32,32,wk),new zk(8,16,128,128,wk),new zk(8,32,128,256,wk),new zk(32,128,258,1024,wk),new zk(32,258,258,4096,wk)];
function Bk(){this.I=null;this.status=0;this.W=null;this.wrap=this.pending=this.Pb=this.za=0;this.F=null;this.Ea=0;this.method=8;this.wb=-1;this.Ya=this.Tc=this.ka=0;this.window=null;this.Hd=0;this.head=this.Ia=null;this.od=this.jd=this.strategy=this.level=this.Hc=this.nd=this.xa=this.v=this.yb=this.o=this.fb=this.rd=this.R=this.va=this.Na=this.Ma=this.Dc=this.ec=this.M=0;this.sa=new M.Ja(1146);this.bb=new M.Ja(122);this.ia=new M.Ja(78);pk(this.sa);pk(this.bb);pk(this.ia);this.Xc=this.ac=this.fc=
null;this.La=new M.Ja(16);this.Y=new M.Ja(573);pk(this.Y);this.tb=this.Oa=0;this.depth=new M.Ja(573);pk(this.depth);this.ga=this.ma=this.ta=this.matches=this.Db=this.Qa=this.Ib=this.ya=this.Mb=this.Gc=0}
function Ck(a,b){if(!a||!a.state||5<b||0>b)return a?ok(a,-2):-2;var c=a.state;if(!a.output||!a.input&&0!==a.la||666===c.status&&4!==b)return ok(a,0===a.P?-5:-2);c.I=a;var d=c.wb;c.wb=b;if(42===c.status)if(2===c.wrap)a.G=0,O(c,31),O(c,139),O(c,8),c.F?(O(c,(c.F.text?1:0)+(c.F.Sa?2:0)+(c.F.extra?4:0)+(c.F.name?8:0)+(c.F.comment?16:0)),O(c,c.F.time&255),O(c,c.F.time>>8&255),O(c,c.F.time>>16&255),O(c,c.F.time>>24&255),O(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),O(c,c.F.os&255),c.F.extra&&c.F.extra.length&&
(O(c,c.F.extra.length&255),O(c,c.F.extra.length>>8&255)),c.F.Sa&&(a.G=Bj(a.G,c.W,c.pending,0)),c.Ea=0,c.status=69):(O(c,0),O(c,0),O(c,0),O(c,0),O(c,0),O(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),O(c,3),c.status=113);else{var e=8+(c.Tc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;sk(c,e+(31-e%31));0!==c.o&&(sk(c,a.G>>>16),sk(c,a.G&65535));a.G=1}if(69===c.status)if(c.F.extra){for(e=c.pending;c.Ea<(c.F.extra.length&65535)&&(c.pending!==c.za||
(c.F.Sa&&c.pending>e&&(a.G=Bj(a.G,c.W,c.pending-e,e)),qk(a),e=c.pending,c.pending!==c.za));)O(c,c.F.extra[c.Ea]&255),c.Ea++;c.F.Sa&&c.pending>e&&(a.G=Bj(a.G,c.W,c.pending-e,e));c.Ea===c.F.extra.length&&(c.Ea=0,c.status=73)}else c.status=73;if(73===c.status)if(c.F.name){e=c.pending;do{if(c.pending===c.za&&(c.F.Sa&&c.pending>e&&(a.G=Bj(a.G,c.W,c.pending-e,e)),qk(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ea<c.F.name.length?c.F.name.charCodeAt(c.Ea++)&255:0;O(c,f)}while(0!==f);c.F.Sa&&c.pending>
e&&(a.G=Bj(a.G,c.W,c.pending-e,e));0===f&&(c.Ea=0,c.status=91)}else c.status=91;if(91===c.status)if(c.F.comment){e=c.pending;do{if(c.pending===c.za&&(c.F.Sa&&c.pending>e&&(a.G=Bj(a.G,c.W,c.pending-e,e)),qk(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ea<c.F.comment.length?c.F.comment.charCodeAt(c.Ea++)&255:0;O(c,f)}while(0!==f);c.F.Sa&&c.pending>e&&(a.G=Bj(a.G,c.W,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.F.Sa?(c.pending+2>c.za&&qk(a),c.pending+2<=c.za&&(O(c,a.G&
255),O(c,a.G>>8&255),a.G=0,c.status=113)):c.status=113);if(0!==c.pending){if(qk(a),0===a.P)return c.wb=-1,0}else if(0===a.la&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return ok(a,-5);if(666===c.status&&0!==a.la)return ok(a,-5);if(0!==a.la||0!==c.v||0!==b&&666!==c.status){d=2===c.strategy?yk(c,b):3===c.strategy?xk(c,b):Ak[c.level].be(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.P&&(c.wb=-1),0;if(2===d&&(1===b?(Yj(c,2,3),Zj(c,256,Mj),16===c.ga?(Xj(c,c.ma),c.ma=0,c.ga=0):8<=c.ga&&
(c.W[c.pending++]=c.ma&255,c.ma>>=8,c.ga-=8)):5!==b&&(Yj(c,0,3),ek(c,0,0),3===b&&(pk(c.head),0===c.v&&(c.o=0,c.va=0,c.ta=0))),qk(a),0===a.P))return c.wb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(O(c,a.G&255),O(c,a.G>>8&255),O(c,a.G>>16&255),O(c,a.G>>24&255),O(c,a.kb&255),O(c,a.kb>>8&255),O(c,a.kb>>16&255),O(c,a.kb>>24&255)):(sk(c,a.G>>>16),sk(c,a.G&65535));qk(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var Dk={};Dk=function(){this.input=null;this.kb=this.la=this.hb=0;this.output=null;this.Rc=this.P=this.Ab=0;this.msg="";this.state=null;this.wc=2;this.G=0};var Ek=Object.prototype.toString;
function Fk(a){if(!(this instanceof Fk))return new Fk(a);a=this.options=M.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&0<a.windowBits?a.windowBits=-a.windowBits:a.gzip&&0<a.windowBits&&16>a.windowBits&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.I=new Dk;this.I.P=0;var b=this.I;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<
f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=ok(b,-2);else{8===e&&(e=9);var k=new Bk;b.state=k;k.I=b;k.wrap=h;k.F=null;k.Tc=e;k.ka=1<<k.Tc;k.Ya=k.ka-1;k.Dc=f+7;k.ec=1<<k.Dc;k.Ma=k.ec-1;k.Na=~~((k.Dc+3-1)/3);k.window=new M.lb(2*k.ka);k.head=new M.Ja(k.ec);k.Ia=new M.Ja(k.ka);k.Mb=1<<f+6;k.za=4*k.Mb;k.W=new M.lb(k.za);k.Ib=1*k.Mb;k.Gc=3*k.Mb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.kb=b.Rc=0;b.wc=2;c=b.state;c.pending=0;c.Pb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.G=2===c.wrap?
0:1;c.wb=0;if(!mk){d=Array(16);for(f=g=0;28>f;f++)for(Qj[f]=g,e=0;e<1<<Ij[f];e++)Pj[g++]=f;Pj[g-1]=f;for(f=g=0;16>f;f++)for(Rj[f]=g,e=0;e<1<<Jj[f];e++)Oj[g++]=f;for(g>>=7;30>f;f++)for(Rj[f]=g<<7,e=0;e<1<<Jj[f]-7;e++)Oj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)Mj[2*e+1]=8,e++,d[8]++;for(;255>=e;)Mj[2*e+1]=9,e++,d[9]++;for(;279>=e;)Mj[2*e+1]=7,e++,d[7]++;for(;287>=e;)Mj[2*e+1]=8,e++,d[8]++;bk(Mj,287,d);for(e=0;30>e;e++)Nj[2*e+1]=5,Nj[2*e]=ak(e,5);Tj=new Sj(Mj,Ij,257,286,15);Uj=new Sj(Nj,
Jj,0,30,15);Vj=new Sj([],Kj,0,19,7);mk=!0}c.fc=new Wj(c.sa,Tj);c.ac=new Wj(c.bb,Uj);c.Xc=new Wj(c.ia,Vj);c.ma=0;c.ga=0;ck(c);c=0}else c=ok(b,-2);0===c&&(b=b.state,b.Hd=2*b.ka,pk(b.head),b.Hc=Ak[b.level].te,b.jd=Ak[b.level].ge,b.od=Ak[b.level].xe,b.nd=Ak[b.level].se,b.o=0,b.va=0,b.v=0,b.ta=0,b.R=b.xa=2,b.fb=0,b.M=0);b=c}}else b=-2;if(0!==b)throw Error(Gj[b]);a.header&&(b=this.I)&&b.state&&2===b.state.wrap&&(b.state.F=a.header);if(a.dictionary){var l;"string"===typeof a.dictionary?l=zj(a.dictionary):
"[object ArrayBuffer]"===Ek.call(a.dictionary)?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.I;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,2===b||1===b&&42!==l.status||l.v)b=-2;else{1===b&&(a.G=Aj(a.G,f,g,0));l.wrap=0;g>=l.ka&&(0===b&&(pk(l.head),l.o=0,l.va=0,l.ta=0),c=new M.lb(l.ka),M.ob(c,f,g-l.ka,l.ka,0),f=c,g=l.ka);c=a.la;d=a.hb;e=a.input;a.la=g;a.hb=0;a.input=f;for(uk(l);3<=l.v;){f=l.o;g=l.v-2;do l.M=(l.M<<l.Na^l.window[f+3-1])&l.Ma,l.Ia[f&l.Ya]=l.head[l.M],l.head[l.M]=f,f++;while(--g);
l.o=f;l.v=2;uk(l)}l.o+=l.v;l.va=l.o;l.ta=l.v;l.v=0;l.R=l.xa=2;l.fb=0;a.hb=d;a.input=e;a.la=c;l.wrap=b;b=0}else b=-2;if(0!==b)throw Error(Gj[b]);this.Lf=!0}}
Fk.prototype.push=function(a,b){var c=this.I,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=zj(a):"[object ArrayBuffer]"===Ek.call(a)?c.input=new Uint8Array(a):c.input=a;c.hb=0;c.la=c.input.length;do{0===c.P&&(c.output=new M.lb(d),c.Ab=0,c.P=d);a=Ck(c,e);if(1!==a&&0!==a)return Gk(this,a),this.ended=!0,!1;if(0===c.P||0===c.la&&(4===e||2===e))if("string"===this.options.to){var f=M.Qc(c.output,c.Ab);b=f;f=f.length;if(65537>f&&(b.subarray&&yj||!b.subarray))b=
String.fromCharCode.apply(null,M.Qc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=M.Qc(c.output,c.Ab),this.chunks.push(b)}while((0<c.la||0===c.P)&&1!==a);if(4===e)return(c=this.I)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=ok(c,-2):(c.state=null,a=113===d?ok(c,-3):0)):a=-2,Gk(this,a),this.ended=!0,0===a;2===e&&(Gk(this,0),c.P=0);return!0};
function Gk(a,b){0===b&&(a.result="string"===a.options.to?a.chunks.join(""):M.gd(a.chunks));a.chunks=[];a.err=b;a.msg=a.I.msg}
function Hk(a,b){b=b||{};b.gzip=!0;b=new Fk(b);b.push(a,!0);if(b.err)throw b.msg||Gj[b.err];return b.result}
;function Ik(a){if(!a)return null;a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue;var b;a?b=Hb(a):b=null;return b}
;function Jk(a){return Hb(null===a?"null":void 0===a?"undefined":a)}
;function Kk(a){this.name=a}
;var Lk=new Kk("rawColdConfigGroup");var Mk=new Kk("rawHotConfigGroup");function Nk(a){this.D=Uf(a)}
x(Nk,tg);var Ok=new Kk("continuationCommand");var Pk=new Kk("webCommandMetadata");var Qk=new Kk("signalServiceEndpoint");var Rk={xf:"EMBEDDED_PLAYER_MODE_UNKNOWN",uf:"EMBEDDED_PLAYER_MODE_DEFAULT",wf:"EMBEDDED_PLAYER_MODE_PFP",vf:"EMBEDDED_PLAYER_MODE_PFL"};var Sk=new Kk("feedbackEndpoint");function Tk(a){this.D=Uf(a)}
x(Tk,tg);Tk.prototype.setTrackingParams=function(a){return G(this,1,pf(a,!0))};var Uk=new Kk("webPlayerShareEntityServiceEndpoint");var Vk=new Kk("playlistEditEndpoint");var Wk=new Kk("modifyChannelNotificationPreferenceEndpoint");var Xk=new Kk("unsubscribeEndpoint");var Yk=new Kk("subscribeEndpoint");function Zk(){var a=$k;D("yt.ads.biscotti.getId_")||C("yt.ads.biscotti.getId_",a)}
function al(a){C("yt.ads.biscotti.lastId_",a)}
;function bl(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var cl=B.window,dl,el,fl=(null==cl?void 0:null==(dl=cl.yt)?void 0:dl.config_)||(null==cl?void 0:null==(el=cl.ytcfg)?void 0:el.data_)||{};C("yt.config_",fl);function gl(){bl(fl,arguments)}
function P(a,b){return a in fl?fl[a]:b}
function hl(a){var b=fl.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var il=[];function jl(a){il.forEach(function(b){return b(a)})}
function kl(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){ll(b)}}:a}
function ll(a){var b=D("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=P("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),gl("ERRORS",b));jl(a)}
function ml(a,b,c,d,e){var f=D("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=P("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),gl("ERRORS",f))}
;var nl=/^[\w.]*$/,ol={q:!0,search_query:!0};function pl(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=ql(f[0]||""),h=ql(f[1]||"");g in c?Array.isArray(c[g])?lb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(pl);k.args=[{key:l,value:f[1],query:a,method:rl==n?"unchanged":n}];ol.hasOwnProperty(l)||ml(k)}}return c}
var rl=String(pl);function sl(a){var b=[];mb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];fb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function tl(a){"?"==a.charAt(0)&&(a=a.substr(1));return pl(a,"&")}
function ul(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),tl(1<a.length?a[1]:a[0])):{}}
function vl(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=tl(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return mc(a,e)+d}
function wl(a){if(!b)var b=window.location.href;var c=cc(1,a),d=dc(a);c&&d?(a=a.match(ac),b=b.match(ac),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?dc(b)==d&&(Number(cc(4,b))||null)==(Number(cc(4,a))||null):!0;return a}
function ql(a){return a&&a.match(nl)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function xl(a){var b=yl;a=void 0===a?D("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Ai;e.flash="0";a:{try{var f=b.h.top.location.href}catch(V){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Yh:g;try{var h=g.history.length}catch(V){h=0}e.u_his=h;var k;e.u_h=null==(k=Yh.screen)?void 0:k.height;var l;e.u_w=null==(l=Yh.screen)?void 0:l.width;var n;e.u_ah=null==(n=Yh.screen)?void 0:n.availHeight;var p;e.u_aw=null==
(p=Yh.screen)?void 0:p.availWidth;var t;e.u_cd=null==(t=Yh.screen)?void 0:t.colorDepth}catch(V){}h=b.h;try{var r=h.screenX;var u=h.screenY}catch(V){}try{var y=h.outerWidth;var z=h.outerHeight}catch(V){}try{var H=h.innerWidth;var L=h.innerHeight}catch(V){}try{var I=h.screenLeft;var da=h.screenTop}catch(V){}try{H=h.innerWidth,L=h.innerHeight}catch(V){}try{var T=h.screen.availWidth;var N=h.screen.availTop}catch(V){}r=[I,da,r,u,T,N,y,z,H,L];try{var ba=(b.h.top||window).document,J="CSS1Compat"==ba.compatMode?
ba.documentElement:ba.body;var ca=(new Ed(J.clientWidth,J.clientHeight)).round()}catch(V){ca=new Ed(-12245933,-12245933)}ba=ca;ca={};var ha=void 0===ha?B:ha;J=new Ki;"SVGElement"in ha&&"createElementNS"in ha.document&&J.set(0);u=xi();u["allow-top-navigation-by-user-activation"]&&J.set(1);u["allow-popups-to-escape-sandbox"]&&J.set(2);ha.crypto&&ha.crypto.subtle&&J.set(3);"TextDecoder"in ha&&"TextEncoder"in ha&&J.set(4);ha=Li(J);ca.bc=ha;ca.bih=ba.height;ca.biw=ba.width;ca.brdim=r.join();b=b.i;b=(ca.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,ca.wgl=!!Yh.WebGLRenderingContext,ca);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var yl=new function(){var a=window.document;this.h=window;this.i=a};
C("yt.ads_.signals_.getAdSignalsString",function(a){return sl(xl(a))});Xa();navigator.userAgent.indexOf(" (CrKey ");function R(a){a=zl(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Al(a,b){a=zl(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function zl(a){return P("EXPERIMENT_FLAGS",{})[a]}
function Bl(){for(var a=[],b=P("EXPERIMENTS_FORCED_FLAGS",{}),c=w(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=P("EXPERIMENT_FLAGS",{});var e=w(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var Cl="XMLHttpRequest"in B?function(){return new XMLHttpRequest}:null;
function Dl(){if(!Cl)return null;var a=Cl();return"open"in a?a:null}
function El(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function Fl(a,b){"function"===typeof a&&(a=kl(a));return window.setTimeout(a,b)}
;var Gl="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(ma(Gl),["client_dev_set_cookie"]);var Hl={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Il="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ma(Gl)),Jl=!1;
function Kl(a,b){b=void 0===b?{}:b;var c=wl(a),d=R("web_ajax_ignore_global_headers_if_set"),e;for(e in Hl){var f=P(Hl[e]),g="X-Goog-AuthUser"===e||"X-Goog-PageId"===e;"X-Goog-Visitor-Id"!==e||f||(f=P("VISITOR_DATA"));!f||!c&&dc(a)||d&&void 0!==b[e]||"TVHTML5_UNPLUGGED"===P("INNERTUBE_CLIENT_NAME")&&g||(b[e]=f)}R("enable_eom_webview_header")&&c&&P("WEBVIEW_EOM",!1)&&(b["X-Yt-Webview-Eom"]="1");"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!dc(a))b["X-YouTube-Utc-Offset"]=
String(-(new Date).getTimezoneOffset());if(c||!dc(a)){try{var h=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(k){}h&&(b["X-YouTube-Time-Zone"]=h)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&dc(a)||(b["X-YouTube-Ad-Signals"]=sl(xl()));return b}
function Ll(a){var b=window.location.search,c=dc(a);R("debug_handle_relative_url_for_query_forward_killswitch")||!c&&wl(a)&&(c=document.location.hostname);var d=bc(cc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=tl(b),f={};fb(Il,function(g){e[g]&&(f[g]=e[g])});
return vl(a,f||{},!1)}
function Ml(a,b){var c=b.format||"JSON";a=Nl(a,b);var d=Ol(a,b),e=!1,f=Pl(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=El(k),n=null,p=400<=k.status&&500>k.status,t=500<=k.status&&600>k.status;if(l||p||t)n=Ql(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||B;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,
k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=Fl(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||B,f))},d)}return f}
function Nl(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=P("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=vl(a,b||{},!0);return a}
function Ol(a,b){var c=P("XSRF_FIELD_NAME"),d=P("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=P("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||dc(a)&&!b.withCredentials&&dc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(R("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=tl(e),wb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):kc(e));f=e||f&&!pb(f);!Jl&&f&&"POST"!=b.method&&(Jl=!0,ll(Error("AJAX request with postData should use POST")));return e}
function Ql(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,ml(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Rl(a):null)e={},fb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Sl(g)})}d&&Tl(e);
return e}
function Tl(a){if(Pa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=yb();d=e?e.createHTML(d):d;a[c]=new Xb(d)}else Tl(a[b])}}
function Rl(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Sl(a){var b="";fb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Ul(a,b){b.method="POST";b.postParams||(b.postParams={});return Ml(a,b)}
function Pl(a,b,c,d,e,f,g,h){function k(){4==(l&&"readyState"in l?l.readyState:0)&&b&&kl(b)(l)}
c=void 0===c?"GET":c;d=void 0===d?"":d;h=void 0===h?!1:h;var l=Dl();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;R("debug_forward_web_query_parameters")&&(a=Ll(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Kl(a,e))for(var n in e)l.setRequestHeader(n,e[n]),"content-type"==n.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
h&&"setAttributionReporting"in XMLHttpRequest.prototype&&l.setAttributionReporting({eventSourceEligible:!0,triggerEligible:!1});l.send(d);return l}
;var Vl=[{Ic:function(a){return"Cannot read property '"+a.key+"'"},
lc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ic:function(a){return"Cannot call '"+a.key+"'"},
lc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ic:function(a){return a.key+" is not defined"},
lc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Xl={Ua:[],Ra:[{callback:Wl,weight:500}]};function Wl(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Yl(){this.Ra=[];this.Ua=[]}
var Zl;function $l(){if(!Zl){var a=Zl=new Yl;a.Ua.length=0;a.Ra.length=0;Xl.Ua&&a.Ua.push.apply(a.Ua,Xl.Ua);Xl.Ra&&a.Ra.push.apply(a.Ra,Xl.Ra)}return Zl}
;var am=new K;function bm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=cm(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=cm(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=cm(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function cm(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function dm(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=em(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f="string"!==typeof g||"clickTrackingParams"!==f&&"trackingParams"!==f?0:(g=bm(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?em(f+".ve",g,h,k):0;d+=f;d+=em(e,a[e],b,c);if(500<d)break}}else c[b]=fm(a),d+=c[b].length;else c[b]=fm(a),d+=c[b].length;return d}
function em(a,b,c,d){c+="."+a;a=fm(b);d[c]=a;return c.length+a.length}
function fm(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function gm(){this.Xe=!0}
function hm(){gm.h||(gm.h=new gm);return gm.h}
function im(a,b){a={};var c=Pg([]);c&&(a.Authorization=c,c=b=null==b?void 0:b.sessionIndex,void 0===c&&(c=Number(P("SESSION_INDEX",0)),c=isNaN(c)?0:c),R("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in fl||(a["X-Origin"]=window.location.origin),void 0===b&&"DELEGATED_SESSION_ID"in fl&&(a["X-Goog-PageId"]=P("DELEGATED_SESSION_ID")));return a}
;var jm={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function km(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function lm(){if(!B.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return B.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":B.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":B.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":B.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function mm(a,b,c,d,e){Lg.set(""+a,b,{hc:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function nm(a){return Lg.get(""+a,void 0)}
function om(a,b,c){Lg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function pm(){if(!Lg.isEnabled())return!1;if(!Lg.Lb())return!0;Lg.set("TESTCOOKIESENABLED","1",{hc:60});if("1"!==Lg.get("TESTCOOKIESENABLED"))return!1;Lg.remove("TESTCOOKIESENABLED");return!0}
;var qm=D("ytglobal.prefsUserPrefsPrefs_")||{};C("ytglobal.prefsUserPrefsPrefs_",qm);function rm(){this.h=P("ALT_PREF_COOKIE_NAME","PREF");this.i=P("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=nm(this.h);a&&this.parse(a)}
var sm;function tm(){sm||(sm=new rm);return sm}
m=rm.prototype;m.get=function(a,b){um(a);wm(a);a=void 0!==qm[a]?qm[a].toString():null;return null!=a?a:b?b:""};
m.set=function(a,b){um(a);wm(a);if(null==b)throw Error("ExpectedNotNull");qm[a]=b.toString()};
function xm(a){return!!((ym("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
m.remove=function(a){um(a);wm(a);delete qm[a]};
m.clear=function(){for(var a in qm)delete qm[a]};
function wm(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function um(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function ym(a){a=void 0!==qm[a]?qm[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
m.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(qm[d]=c.toString())}};var zm={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Am={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function Bm(){var a=B.navigator;return a?a.connection:void 0}
function Cm(){var a=Bm();if(a){var b=zm[a.type||"unknown"]||"CONN_UNKNOWN";a=zm[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Dm(){var a=Bm();if(null!=a&&a.effectiveType)return Am.hasOwnProperty(a.effectiveType)?Am[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function S(a){var b=Ia.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ma(b))}
x(S,Error);function Em(){try{return Fm(),!0}catch(a){return!1}}
function Fm(a){if(void 0!==P("DATASYNC_ID"))return P("DATASYNC_ID");throw new S("Datasync ID not set",void 0===a?"unknown":a);}
;function Gm(){}
function Hm(a,b){return Ji.ab(a,0,b)}
Gm.prototype.oa=function(a,b){return this.ab(a,1,b)};
Gm.prototype.Fb=function(a){var b=D("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var Im=Al("web_emulated_idle_callback_delay",300),Jm=1E3/60-3,Km=[8,5,4,3,2,1,0];
function Lm(a){a=void 0===a?{}:a;F.call(this);this.i=[];this.j={};this.Z=this.h=0;this.X=this.m=!1;this.K=[];this.T=this.ea=!1;for(var b=w(Km),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.l=0;this.uc=a.timeout||1;this.B=Jm;this.u=0;this.ha=this.ze.bind(this);this.sc=this.af.bind(this);this.Ba=this.Md.bind(this);this.Ka=this.he.bind(this);this.nb=this.Ce.bind(this);this.na=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!R("disable_scheduler_requestIdleCallback");(this.fa=!1!==
a.useRaf&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.ha)}
x(Lm,F);m=Lm.prototype;m.Fb=function(a){var b=Xa();Mm(this,a);a=Xa()-b;this.m||(this.B-=a)};
m.ab=function(a,b,c){++this.Z;if(10===b)return this.Fb(a),this.Z;var d=this.Z;this.j[d]=a;this.m&&!c?this.K.push({id:d,priority:b}):(this.i[b].push(d),this.X||this.m||(0!==this.h&&Nm(this)!==this.u&&this.stop(),this.start()));return d};
m.qa=function(a){delete this.j[a]};
function Om(a){a.K.length=0;for(var b=5;0<=b;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
m.isHidden=function(){return!!document.hidden||!1};
function Pm(a){return!a.isHidden()&&a.fa}
function Nm(a){if(a.i[8].length){if(a.T)return 4;if(Pm(a))return 3}for(var b=5;b>=a.l;b--)if(0<a.i[b].length)return 0<b?Pm(a)?3:2:1;return 0}
m.Nb=function(a){var b=D("yt.logging.errors.log");b&&b(a)};
function Mm(a,b){try{b()}catch(c){a.Nb(c)}}
function Qm(a){for(var b=w(Km),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
m.he=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ea=!0;Rm(this,b);this.ea=!1};
m.af=function(){Rm(this)};
m.Md=function(){Sm(this)};
m.Ce=function(a){this.T=!0;var b=Nm(this);4===b&&b!==this.u&&(this.stop(),this.start());Rm(this,void 0,a);this.T=!1};
m.ze=function(){this.isHidden()||Sm(this);this.h&&(this.stop(),this.start())};
function Sm(a){a.stop();a.m=!0;for(var b=Xa(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&Mm(a,e)}Tm(a);a.m=!1;Qm(a)&&a.start();b=Xa()-b;a.B-=b}
function Tm(a){for(var b=0,c=a.K.length;b<c;b++){var d=a.K[b];a.i[d.priority].push(d.id)}a.K.length=0}
function Rm(a,b,c){a.T&&4===a.u&&a.h||a.stop();a.m=!0;b=Xa()+(b||a.B);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Nb(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&Mm(a,f);d=a.ea?0:1;d=a.l>d?a.l:d;if(!(Xa()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&Mm(a,c)}while(c&&Xa()<b)}a.m=!1;Tm(a);a.B=Jm;Qm(a)&&a.start()}
m.start=function(){this.X=!1;if(0===this.h)switch(this.u=Nm(this),this.u){case 1:var a=this.Ka;this.h=this.na?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,Im);break;case 2:this.h=window.setTimeout(this.sc,this.uc);break;case 3:this.h=window.requestAnimationFrame(this.nb);break;case 4:this.h=window.setTimeout(this.Ba,0)}};
m.pause=function(){this.stop();this.X=!0};
m.stop=function(){if(this.h){switch(this.u){case 1:var a=this.h;this.na?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
m.S=function(){Om(this);this.stop();this.fa&&document.removeEventListener("visibilitychange",this.ha);F.prototype.S.call(this)};var Um=D("yt.scheduler.instance.timerIdMap_")||{},Vm=Al("kevlar_tuner_scheduler_soft_state_timer_ms",800),Wm=0,Xm=0;function Ym(){var a=D("ytglobal.schedulerInstanceInstance_");if(!a||a.aa())a=new Lm(P("scheduler")||{}),C("ytglobal.schedulerInstanceInstance_",a);return a}
function Zm(){$m();var a=D("ytglobal.schedulerInstanceInstance_");a&&(wc(a),C("ytglobal.schedulerInstanceInstance_",null))}
function $m(){Om(Ym());for(var a in Um)Um.hasOwnProperty(a)&&delete Um[Number(a)]}
function an(a,b,c){if(!c)return c=void 0===c,-Ym().ab(a,b,c);var d=window.setTimeout(function(){var e=Ym().ab(a,b);Um[d]=e},c);
return d}
function bn(a){Ym().Fb(a)}
function cn(a){var b=Ym();if(0>a)b.qa(-a);else{var c=Um[a];c?(b.qa(c),delete Um[a]):window.clearTimeout(a)}}
function dn(){en()}
function en(){window.clearTimeout(Wm);Ym().start()}
function fn(){Ym().pause();window.clearTimeout(Wm);Wm=window.setTimeout(dn,Vm)}
function gn(){window.clearTimeout(Xm);Xm=window.setTimeout(function(){jn(0)},Vm)}
function jn(a){gn();var b=Ym();b.l=a;b.start()}
function kn(a){gn();var b=Ym();b.l>a&&(b.l=a,b.start())}
function ln(){window.clearTimeout(Xm);var a=Ym();a.l=0;a.start()}
function mn(){D("yt.scheduler.initialized")||(C("yt.scheduler.instance.dispose",Zm),C("yt.scheduler.instance.addJob",an),C("yt.scheduler.instance.addImmediateJob",bn),C("yt.scheduler.instance.cancelJob",cn),C("yt.scheduler.instance.cancelAllJobs",$m),C("yt.scheduler.instance.start",en),C("yt.scheduler.instance.pause",fn),C("yt.scheduler.instance.setPriorityThreshold",jn),C("yt.scheduler.instance.enablePriorityThreshold",kn),C("yt.scheduler.instance.clearPriorityThreshold",ln),C("yt.scheduler.initialized",
!0))}
;function nn(){Gm.apply(this,arguments)}
x(nn,Gm);function on(){nn.h||(nn.h=new nn);return nn.h}
nn.prototype.ab=function(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=D("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Fl(a,c||0)};
nn.prototype.qa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=D("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
nn.prototype.start=function(){var a=D("yt.scheduler.instance.start");a&&a()};
nn.prototype.pause=function(){var a=D("yt.scheduler.instance.pause");a&&a()};
var Ji=on();R("web_scheduler_auto_init")&&mn();function pn(a){var b=new oj;(b=b.isAvailable()?a?new uj(b,a):b:null)||(a=new pj(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new kj(a):null;this.i=document.domain||window.location.hostname}
pn.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape((new uh).serialize(b))}catch(f){return}else e=escape(b);mm(a,e,c,this.i)};
pn.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=nm(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
pn.prototype.remove=function(a){this.h&&this.h.remove(a);om(a,"/",this.i)};var qn=function(){var a;return function(){a||(a=new pn("ytidb"));return a}}();
function rn(){var a;return null==(a=qn())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var sn=[],tn,un=!1;function vn(){var a={};for(tn=new wn(void 0===a.handleError?xn:a.handleError,void 0===a.logEvent?yn:a.logEvent);0<sn.length;)switch(a=sn.shift(),a.type){case "ERROR":tn.Nb(a.payload);break;case "EVENT":tn.logEvent(a.eventType,a.payload)}}
function zn(a){un||(tn?tn.Nb(a):(sn.push({type:"ERROR",payload:a}),10<sn.length&&sn.shift()))}
function An(a,b){un||(tn?tn.logEvent(a,b):(sn.push({type:"EVENT",eventType:a,payload:b}),10<sn.length&&sn.shift()))}
;function Bn(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Cn(a){return a.substr(0,a.indexOf(":"))||a}
;var Dn=Ae||Be;function En(a){var b=Ob();return b?0<=b.toLowerCase().indexOf(a):!1}
;var Fn={},Gn=(Fn.AUTH_INVALID="No user identifier specified.",Fn.EXPLICIT_ABORT="Transaction was explicitly aborted.",Fn.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Fn.MISSING_INDEX="Index not created.",Fn.MISSING_OBJECT_STORES="Object stores not created.",Fn.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Fn.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Fn.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Fn.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Fn.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Fn.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Fn.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Fn),Hn={},In=(Hn.AUTH_INVALID="ERROR",Hn.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Hn.EXPLICIT_ABORT="IGNORED",Hn.IDB_NOT_SUPPORTED="ERROR",Hn.MISSING_INDEX=
"WARNING",Hn.MISSING_OBJECT_STORES="ERROR",Hn.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Hn.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Hn.QUOTA_EXCEEDED="WARNING",Hn.QUOTA_MAYBE_EXCEEDED="WARNING",Hn.UNKNOWN_ABORT="WARNING",Hn.INCOMPATIBLE_DB_VERSION="WARNING",Hn),Jn={},Kn=(Jn.AUTH_INVALID=!1,Jn.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Jn.EXPLICIT_ABORT=!1,Jn.IDB_NOT_SUPPORTED=!1,Jn.MISSING_INDEX=!1,Jn.MISSING_OBJECT_STORES=!1,Jn.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Jn.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Jn.QUOTA_EXCEEDED=!1,Jn.QUOTA_MAYBE_EXCEEDED=!0,Jn.UNKNOWN_ABORT=!0,Jn.INCOMPATIBLE_DB_VERSION=!1,Jn);function Ln(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Gn[a]:c;d=void 0===d?In[a]:d;e=void 0===e?Kn[a]:e;S.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Ln.prototype)}
x(Ln,S);function Mn(a,b){Ln.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Gn.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Mn.prototype)}
x(Mn,Ln);function Nn(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Nn.prototype)}
x(Nn,Error);var On=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Pn(a,b,c,d){b=Cn(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Ln)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Ln("QUOTA_EXCEEDED",a);if(Ce&&"UnknownError"===e.name)return new Ln("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Nn)return new Ln("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&On.some(function(f){return e.message.includes(f)}))return new Ln("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Ln("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",qd:e.name})];e.level="WARNING";return e}
function Qn(a,b,c){var d=rn();return new Ln("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function Rn(a){if(!a)throw Error();throw a;}
function Sn(a){return a}
function Tn(a){this.h=a}
function Un(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=w(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=w(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Un.all=function(a){return new Un(new Tn(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={ub:0};f.ub<a.length;f={ub:f.ub},++f.ub)Un.resolve(a[f.ub]).then(function(g){return function(h){d[g.ub]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
Un.resolve=function(a){return new Un(new Tn(function(b,c){a instanceof Un?a.then(b,c):b(a)}))};
Un.reject=function(a){return new Un(new Tn(function(b,c){c(a)}))};
Un.prototype.then=function(a,b){var c=this,d=null!=a?a:Sn,e=null!=b?b:Rn;return new Un(new Tn(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Vn(c,c,d,f,g)}),c.i.push(function(){Wn(c,c,e,f,g)})):"FULFILLED"===c.state.status?Vn(c,c,d,f,g):"REJECTED"===c.state.status&&Wn(c,c,e,f,g)}))};
Un.prototype.catch=function(a){return this.then(void 0,a)};
function Vn(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Un?Xn(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Wn(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Un?Xn(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Xn(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Un?Xn(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Yn(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Zn(a){return new Promise(function(b,c){Yn(a,b,c)})}
function $n(a){return new Un(new Tn(function(b,c){Yn(a,b,c)}))}
;function ao(a,b){return new Un(new Tn(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var bo=window,U=bo.ytcsi&&bo.ytcsi.now?bo.ytcsi.now:bo.performance&&bo.performance.timing&&bo.performance.now&&bo.performance.timing.navigationStart?function(){return bo.performance.timing.navigationStart+bo.performance.now()}:function(){return(new Date).getTime()};function co(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(U());this.i=!1}
m=co.prototype;m.add=function(a,b,c){return eo(this,[a],{mode:"readwrite",ja:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return eo(this,[a],{mode:"readwrite",ja:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return eo(this,[a],{mode:"readonly",ja:!0},function(c){return c.objectStore(a).count(b)})};
function fo(a,b,c){a=a.h.createObjectStore(b,c);return new go(a)}
m.delete=function(a,b){return eo(this,[a],{mode:"readwrite",ja:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return eo(this,[a],{mode:"readonly",ja:!0},function(c){return c.objectStore(a).get(b)})};
function ho(a,b,c){return eo(a,[b],{mode:"readwrite",ja:!0},function(d){d=d.objectStore(b);return $n(d.h.put(c,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function eo(a,b,c,d){var e,f,g,h,k,l,n,p,t,r,u,y;return A(function(z){switch(z.h){case 1:var H={mode:"readonly",ja:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?H.mode=c:Object.assign(H,c);e=H;a.transactionCount++;f=e.ja?3:1;g=0;case 2:if(h){z.A(4);break}g++;k=Math.round(U());za(z,5);l=a.h.transaction(b,e.mode);H=z.yield;var L=new io(l);L=jo(L,d);return H.call(z,L,7);case 7:return n=z.i,p=Math.round(U()),ko(a,k,p,g,void 0,b.join(),e),z.return(n);case 5:t=Aa(z);r=Math.round(U());u=Pn(t,
a.h.name,b.join(),a.h.version);if((y=u instanceof Ln&&!u.h)||g>=f)ko(a,k,r,g,u,b.join(),e),h=u;z.A(2);break;case 4:return z.return(Promise.reject(h))}})}
function ko(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Ln&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&An("QUOTA_EXCEEDED",{dbName:Cn(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Ln&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),An("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),lo(a,!1,d,f,b,g.tag),zn(e)):lo(a,!0,d,f,b,g.tag)}
function lo(a,b,c,d,e,f){An("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function go(a){this.h=a}
m=go.prototype;m.add=function(a,b){return $n(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return $n(this.h.clear()).then(function(){})};
function mo(a,b,c){a.h.createIndex(b,c,{unique:!1})}
m.count=function(a){return $n(this.h.count(a))};
function no(a,b){return oo(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?no(this,a):$n(this.h.delete(a))};
m.get=function(a){return $n(this.h.get(a))};
m.index=function(a){try{return new po(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Nn(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function oo(a,b,c){a=a.h.openCursor(b.query,b.direction);return qo(a).then(function(d){return ao(d,c)})}
function io(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Ln;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function jo(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return w(d).next().value})}
io.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Ln("EXPLICIT_ABORT");};
io.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new go(a),this.i.set(a,b));return b};
function po(a){this.h=a}
m=po.prototype;m.count=function(a){return $n(this.h.count(a))};
m.delete=function(a){return ro(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return $n(this.h.get(a))};
m.getKey=function(a){return $n(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function ro(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return qo(a).then(function(d){return ao(d,c)})}
function so(a,b){this.request=a;this.cursor=b}
function qo(a){return $n(a).then(function(b){return b?new so(a,b):null})}
m=so.prototype;m.advance=function(a){this.cursor.advance(a);return qo(this.request)};
m.continue=function(a){this.cursor.continue(a);return qo(this.request)};
m.delete=function(){return $n(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return $n(this.cursor.update(a))};function to(a,b,c){return new Promise(function(d,e){function f(){t||(t=new co(g.result,{closed:p}));return t}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Od,k=c.blocking,l=c.Ye,n=c.upgrade,p=c.closed,t;g.addEventListener("upgradeneeded",function(r){try{if(null===r.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");r.dataLoss&&"none"!==r.dataLoss&&An("IDB_DATA_CORRUPTED",{reason:r.dataLossMessage||"unknown reason",dbName:Cn(a)});var u=f(),y=new io(g.transaction);
n&&n(u,function(z){return r.oldVersion<z&&r.newVersion>=z},y);
y.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var r=g.result;k&&r.addEventListener("versionchange",function(){k(f())});
r.addEventListener("close",function(){An("IDB_UNEXPECTEDLY_CLOSED",{dbName:Cn(a),dbVersion:r.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function uo(a,b,c){c=void 0===c?{}:c;return to(a,b,c)}
function vo(a,b){b=void 0===b?{}:b;var c,d,e,f;return A(function(g){if(1==g.h)return za(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Od)&&c.addEventListener("blocked",function(){e()}),g.yield(Zn(c),4);
if(2!=g.h)g.h=0,g.l=0;else throw f=Aa(g),Pn(f,a,"",-1);})}
;function wo(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
wo.prototype.i=function(a,b,c){c=void 0===c?{}:c;return uo(a,b,c)};
wo.prototype.delete=function(a){a=void 0===a?{}:a;return vo(this.name,a)};
function xo(a,b){return new Ln("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function yo(a,b){if(!b)throw Qn("openWithToken",Cn(a.name));return a.open()}
wo.prototype.open=function(){function a(){var f,g,h,k,l,n,p,t,r,u;return A(function(y){switch(y.h){case 1:return g=null!=(f=Error().stack)?f:"",za(y,2),y.yield(c.i(c.name,c.options.version,e),4);case 4:h=y.i;for(var z=c.options,H=[],L=w(Object.keys(z.Bb)),I=L.next();!I.done;I=L.next()){I=I.value;var da=z.Bb[I],T=void 0===da.Fe?Number.MAX_VALUE:da.Fe;!(h.h.version>=da.Gb)||h.h.version>=T||h.h.objectStoreNames.contains(I)||H.push(I)}k=H;if(0===k.length){y.A(5);break}l=Object.keys(c.options.Bb);n=h.objectStoreNames();
if(c.m<Al("ytidb_reopen_db_retries",0))return c.m++,h.close(),zn(new Ln("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());if(!(c.l<Al("ytidb_remake_db_retries",1))){y.A(6);break}c.l++;return y.yield(c.delete(),7);case 7:return zn(new Ln("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());case 6:throw new Mn(n,l);case 5:return y.return(h);case 2:p=Aa(y);if(p instanceof DOMException?
"VersionError"!==p.name:"DOMError"in self&&p instanceof DOMError?"VersionError"!==p.name:!(p instanceof Object&&"message"in p)||"An attempt was made to open a database using a lower version than the existing version."!==p.message){y.A(8);break}return y.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:t=y.i;r=t.h.version;if(void 0!==c.options.version&&r>c.options.version+1)throw t.close(),c.j=!1,xo(c,r);return y.return(t);case 8:throw b(),p instanceof Error&&!R("ytidb_async_stack_killswitch")&&
(p.stack=p.stack+"\n"+g.substring(g.indexOf("\n")+1)),Pn(p,c.name,"",null!=(u=c.options.version)?u:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw xo(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Ye:b,upgrade:this.options.upgrade};return this.h=d=a()};var zo=new wo("YtIdbMeta",{Bb:{databases:{Gb:1}},upgrade:function(a,b){b(1)&&fo(a,"databases",{keyPath:"actualName"})}});
function Ao(a,b){var c;return A(function(d){if(1==d.h)return d.yield(yo(zo,b),2);c=d.i;return d.return(eo(c,["databases"],{ja:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return $n(f.h.put(a,void 0)).then(function(){})})}))})}
function Bo(a,b){var c;return A(function(d){if(1==d.h)return a?d.yield(yo(zo,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function Co(a,b){var c,d;return A(function(e){return 1==e.h?(c=[],e.yield(yo(zo,b),2)):3!=e.h?(d=e.i,e.yield(eo(d,["databases"],{ja:!0,mode:"readonly"},function(f){c.length=0;return oo(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function Do(a){return Co(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function Eo(a,b,c){return Co(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function Fo(a){var b,c;return A(function(d){if(1==d.h)return b=Fm("YtIdbMeta hasAnyMeta other"),d.yield(Co(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var Go,Ho=new function(){}(new function(){});
function Io(){var a,b,c,d;return A(function(e){switch(e.h){case 1:a=rn();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=Dn)f=/WebKit\/([0-9]+)/.exec(Ob()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Ob()),f=!(f&&602<=parseInt(f[1],10)));if(f||Lc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
za(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(Ao(d,Ho),4);case 4:return e.yield(Bo("yt-idb-test-do-not-use",Ho),5);case 5:return e.return(!0);case 2:return Aa(e),e.return(!1)}})}
function Jo(){if(void 0!==Go)return Go;un=!0;return Go=Io().then(function(a){un=!1;var b;if(null!=(b=qn())&&b.h){var c;b={hasSucceededOnce:(null==(c=rn())?void 0:c.hasSucceededOnce)||a};var d;null==(d=qn())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Ko(){return D("ytglobal.idbToken_")||void 0}
function Lo(){var a=Ko();return a?Promise.resolve(a):Jo().then(function(b){(b=b?Ho:void 0)&&C("ytglobal.idbToken_",b);return b})}
;var Mo=0;function No(a,b){Mo||(Mo=Ji.oa(function(){var c,d,e,f,g;return A(function(h){switch(h.h){case 1:return h.yield(Lo(),2);case 2:c=h.i;if(!c)return h.return();d=!0;za(h,3);return h.yield(Eo(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return h.yield(vo(f.actualName),7);case 7:return h.yield(Bo(f.actualName,c),6);case 6:h.h=4;h.l=0;break;case 3:g=Aa(h),zn(g),d=!1;case 4:Ji.qa(Mo),Mo=0,d&&No(a,b),h.h=0}})}))}
function Oo(){var a;return A(function(b){return 1==b.h?b.yield(Lo(),2):(a=b.i)?b.return(Fo(a)):b.return(!1)})}
new Wh;function Po(a){if(!Em())throw a=new Ln("AUTH_INVALID",{dbName:a}),zn(a),a;var b=Fm();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Qo(a,b,c,d){var e,f,g,h,k,l;return A(function(n){switch(n.h){case 1:return f=null!=(e=Error().stack)?e:"",n.yield(Lo(),2);case 2:g=n.i;if(!g)throw h=Qn("openDbImpl",a,b),R("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),zn(h),h;Bn(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Po(a);za(n,3);return n.yield(Ao(k,g),5);case 5:return n.yield(uo(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=Aa(n),za(n,7),n.yield(Bo(k.actualName,
g),9);case 9:n.h=8;n.l=0;break;case 7:Aa(n);case 8:throw l;}})}
function Ro(a,b,c){c=void 0===c?{}:c;return Qo(a,b,!1,c)}
function So(a,b,c){c=void 0===c?{}:c;return Qo(a,b,!0,c)}
function To(a,b){b=void 0===b?{}:b;var c,d;return A(function(e){if(1==e.h)return e.yield(Lo(),2);if(3!=e.h){c=e.i;if(!c)return e.return();Bn(a);d=Po(a);return e.yield(vo(d.actualName,b),3)}return e.yield(Bo(d.actualName,c),0)})}
function Uo(a,b,c){a=a.map(function(d){return A(function(e){return 1==e.h?e.yield(vo(d.actualName,b),2):e.yield(Bo(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Vo(){var a=void 0===a?{}:a;var b,c;return A(function(d){if(1==d.h)return d.yield(Lo(),2);if(3!=d.h){b=d.i;if(!b)return d.return();Bn("LogsDatabaseV2");return d.yield(Do(b),3)}c=d.i;return d.yield(Uo(c,a,b),0)})}
function Wo(a,b){b=void 0===b?{}:b;var c;return A(function(d){if(1==d.h)return d.yield(Lo(),2);if(3!=d.h){c=d.i;if(!c)return d.return();Bn(a);return d.yield(vo(a,b),3)}return d.yield(Bo(a,c),0)})}
;function Xo(a,b){wo.call(this,a,b);this.options=b;Bn(a)}
x(Xo,wo);function Yo(a,b){var c;return function(){c||(c=new Xo(a,b));return c}}
Xo.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.pc?So:Ro)(a,b,Object.assign({},c))};
Xo.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.pc?Wo:To)(this.name,a)};
function Zo(a,b){return Yo(a,b)}
;var $o={},ap=Zo("ytGcfConfig",{Bb:($o.coldConfigStore={Gb:1},$o.hotConfigStore={Gb:1},$o),pc:!1,upgrade:function(a,b){b(1)&&(mo(fo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),mo(fo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function bp(a){return yo(ap(),a)}
function cp(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:U()},g.yield(bp(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(ho(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function dp(a,b,c,d){var e,f,g;return A(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:U()},h.yield(bp(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(ho(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function ep(a){var b,c;return A(function(d){return 1==d.h?d.yield(bp(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(eo(b,["coldConfigStore"],{mode:"readwrite",ja:!0},function(e){return ro(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function fp(a){var b,c;return A(function(d){return 1==d.h?d.yield(bp(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(eo(b,["hotConfigStore"],{mode:"readwrite",ja:!0},function(e){return ro(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function gp(){F.call(this);this.i=[];this.h=[];var a=D("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(ma(a)),this.h=a):(this.h=[],C("yt.gcf.config.hotUpdateCallbacks",this.h))}
x(gp,F);gp.prototype.S=function(){for(var a=w(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);0<=b&&c.splice(b,1)}this.i.length=0;F.prototype.S.call(this)};function hp(){this.h=0;this.i=new gp}
function ip(){var a;return null!=(a=D("yt.gcf.config.hotConfigGroup"))?a:P("RAW_HOT_CONFIG_GROUP")}
function jp(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:if(!R("start_client_gcf")){g.A(0);break}c&&(a.j=c,C("yt.gcf.config.hotConfigGroup",a.j||null));a.l(b);d=Ko();if(!d){g.A(3);break}if(c){g.A(4);break}return g.yield(fp(d),5);case 5:e=g.i,c=null==(f=e)?void 0:f.config;case 4:return g.yield(cp(c,b,d),3);case 3:if(c)for(var h=c,k=w(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function kp(a,b,c){var d,e,f,g;return A(function(h){if(1==h.h){if(!R("start_client_gcf"))return h.A(0);a.coldHashData=b;C("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Ko())?c?h.A(4):h.yield(ep(d),5):h.A(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.A(0);g=c.configData;return h.yield(dp(c,b,g,d),0)})}
function lp(){if(!hp.h){var a=new hp;hp.h=a}a=hp.h;var b=U()-a.h;if(!(0!==a.h&&b<Al("send_config_hash_timer"))){b=D("yt.gcf.config.coldConfigData");var c=D("yt.gcf.config.hotHashData"),d=D("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=U());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
hp.prototype.l=function(a){this.hotHashData=a;C("yt.gcf.config.hotHashData",this.hotHashData||null)};function mp(){return"INNERTUBE_API_KEY"in fl&&"INNERTUBE_API_VERSION"in fl}
function np(){return{innertubeApiKey:P("INNERTUBE_API_KEY"),innertubeApiVersion:P("INNERTUBE_API_VERSION"),je:P("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),ld:P("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Tf:P("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:P("INNERTUBE_CONTEXT_CLIENT_VERSION"),le:P("INNERTUBE_CONTEXT_HL"),ke:P("INNERTUBE_CONTEXT_GL"),me:P("INNERTUBE_HOST_OVERRIDE")||"",oe:!!P("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),ne:!!P("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:P("SERIALIZED_CLIENT_CONFIG_DATA")}}
function op(a){var b={client:{hl:a.le,gl:a.ke,clientName:a.ld,clientVersion:a.innertubeContextClientVersion,configInfo:a.je}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=B.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=P("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=Bl();0<c.length&&(b.request={internalExperimentFlags:c});c=a.ld;if(("WEB"===c||"MWEB"===c||1===c||2===c)&&b){var d;b.client.mainAppWebInfo=null!=(d=b.client.mainAppWebInfo)?
d:{};b.client.mainAppWebInfo.webDisplayMode=lm()}(d=D("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(R("web_log_memory_total_kbytes")&&(null==(e=B.navigator)?0:e.deviceMemory)){var f;e=null==(f=B.navigator)?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+1E6*e)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=Cm())&&b&&(b.client.connectionType=a);R("web_log_effective_connection_type")&&(a=Dm())&&
b&&(b.client.effectiveConnectionType=a);R("start_client_gcf")&&(e=lp())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,a&&f&&e&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.coldConfigData=a,b.client.configInfo.coldHashData=f,b.client.configInfo.hotHashData=e));P("DELEGATED_SESSION_ID")&&!R("pageid_as_header_web")&&(b.user={onBehalfOfUser:P("DELEGATED_SESSION_ID")});!R("fill_delegate_context_in_gel_killswitch")&&(a=P("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;f=a.assign;e=b.client;d={};c=w(Object.entries(tl(P("DEVICE",""))));for(var g=c.next();!g.done;g=c.next()){var h=w(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?d.deviceMake=h:"cmodel"===g?d.deviceModel=h:"cbr"===g?d.browserName=h:"cbrver"===g?d.browserVersion=h:"cos"===g?d.osName=h:"cosver"===g?d.osVersion=h:"cplatform"===g&&(d.platform=h)}b.client=f.call(a,e,d);return b}
function pp(a,b,c){c=void 0===c?{}:c;var d={};P("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":P("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||P("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||P("AUTHORIZATION");b||(a?b="Bearer "+D("gapi.auth.getToken")().Mf:(a=im(hm()),R("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;function qp(a,b){this.version=a;this.args=b}
qp.prototype.serialize=function(){return{version:this.version,args:this.args}};function rp(a,b){this.topic=a;this.h=b}
rp.prototype.toString=function(){return this.topic};var sp=D("ytPubsub2Pubsub2Instance")||new K;K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Eb;K.prototype.publish=K.prototype.Za;K.prototype.clear=K.prototype.clear;C("ytPubsub2Pubsub2Instance",sp);var tp=D("ytPubsub2Pubsub2SubscribedKeys")||{};C("ytPubsub2Pubsub2SubscribedKeys",tp);var up=D("ytPubsub2Pubsub2TopicToKeys")||{};C("ytPubsub2Pubsub2TopicToKeys",up);var vp=D("ytPubsub2Pubsub2IsAsync")||{};C("ytPubsub2Pubsub2IsAsync",vp);
C("ytPubsub2Pubsub2SkipSubKey",null);function wp(a,b){var c=xp();c&&c.publish.call(c,a.toString(),a,b)}
function yp(a){var b=zp,c=xp();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=D("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(tp[d])try{if(f&&b instanceof rp&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Xa){var l=new h;h.Xa=l.version}var n=h.Xa}catch(z){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var p=n.construct;
var t=k.args,r=t.length;if(0<r){var u=Array(r);for(k=0;k<r;k++)u[k]=t[k];var y=u}else y=[];f=p.call(n,h,y)}catch(z){throw z.message="yt.pubsub2.Data.deserialize(): "+z.message,z;}}catch(z){throw z.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+z.message,z;}a.call(window,f)}catch(z){ll(z)}},vp[b.toString()]?D("yt.scheduler.instance")?Ji.oa(g):Fl(g,0):g())});
tp[d]=!0;up[b.toString()]||(up[b.toString()]=[]);up[b.toString()].push(d);return d}
function Ap(){var a=Bp,b=yp(function(c){a.apply(void 0,arguments);Cp(b)});
return b}
function Cp(a){var b=xp();b&&("number"===typeof a&&(a=[a]),fb(a,function(c){b.unsubscribeByKey(c);delete tp[c]}))}
function xp(){return D("ytPubsub2Pubsub2Instance")}
;function Dp(a,b,c){c=void 0===c?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&wp("meta_logging_csi_event",{timerName:a,lg:b})}
;var Ep=void 0,Fp=void 0;function Gp(){Fp||(Fp=Ik(P("WORKER_SERIALIZATION_URL")));return Fp||void 0}
function Hp(){var a=Gp();Ep||void 0===a||(Ep=new Worker(Fb(a),void 0));return Ep}
;var Ip=Al("max_body_size_to_compress",5E5),Jp=Al("min_body_size_to_compress",500),Kp=!0,Lp=0,Mp=0,Np=Al("compression_performance_threshold_lr",250),Op=Al("slow_compressions_before_abandon_count",4),Pp=!1,Qp=new Map,Rp=1,Sp=!0;function Tp(){if("function"===typeof Worker&&Gp()&&!Pp){var a=function(c){c=c.data;if("gzippedGelBatch"===c.op){var d=Qp.get(c.key);d&&(Up(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Qp.delete(c.key))}},b=Hp();
b&&(b.addEventListener("message",a),b.onerror=function(){Qp.clear()},Pp=!0)}}
function Vp(a,b,c,d,e){e=void 0===e?!1:e;var f={startTime:U(),ticks:{},infos:{}};if(Kp)try{var g=Wp(b);if(null!=g&&(g>Ip||g<Jp))d(a,c);else{if(R("gzip_gel_with_worker")&&(R("initial_gzip_use_main_thread")&&!Sp||!R("initial_gzip_use_main_thread"))){Pp||Tp();var h=Hp();if(h&&!e){Qp.set(Rp,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:Rp});Rp++;return}}var k=Hk(Ci(b));Up(k,f,a,c,d)}}catch(l){ml(l),d(a,c)}else d(a,c)}
function Up(a,b,c,d,e){Sp=!1;var f=U();b.ticks.gelc=f;Mp++;R("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Np&&(Lp++,R("abandon_compression_after_N_slow_zips")?Mp===Al("compression_disable_point")&&Lp>Op&&(Kp=!1):Kp=!1);Xp(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Yp(a){var b=void 0===b?!1:b;var c=void 0===c?!1:c;var d=U(),e={startTime:d,ticks:{},infos:{}},f=b?D("yt.logging.gzipForFetch",!1):!0;if(Kp&&f){if(!a.body)return a;try{var g=c?a.body:"string"===typeof a.body?a.body:JSON.stringify(a.body);f=g;if(!c&&"string"===typeof g){var h=Wp(g);if(null!=h&&(h>Ip||h<Jp))return a;f=Hk(Ci(g),b?{level:1}:void 0);var k=U();e.ticks.gelc=k;if(b){Mp++;if((R("disable_compression_due_to_performance_degredation")||R("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Np)if(Lp++,R("abandon_compression_after_N_slow_zips")||R("abandon_compression_after_N_slow_zips_lr")){b=Lp/Mp;var l=Op/Al("compression_disable_point");0<Mp&&0===Mp%Al("compression_disable_point")&&b>=l&&(Kp=!1)}else Kp=!1;Xp(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(n){return ml(n),a}}else return a}
function Wp(a){try{return(new Blob(a.split(""))).size}catch(b){return ml(b),null}}
function Xp(a){R("gel_compression_csi_killswitch")||!R("log_gel_compression_latency")&&!R("log_gel_compression_latency_lr")||Dp("gel_compression",a,{sampleRate:.1})}
;function Zp(a){a=Object.assign({},a);delete a.Authorization;var b=Pg();if(b){var c=new Pi;c.update(P("INNERTUBE_API_KEY"));c.update(b);a.hash=Fe(c.digest(),3)}return a}
;var $p;function aq(){$p||($p=new pn("yt.innertube"));return $p}
function bq(a,b,c,d){if(d)return null;d=aq().get("nextId",!0)||1;var e=aq().get("requests",!0)||{};e[d]={method:a,request:b,authState:Zp(c),requestTime:Math.round(U())};aq().set("nextId",d+1,86400,!0);aq().set("requests",e,86400,!0);return d}
function cq(a){var b=aq().get("requests",!0)||{};delete b[a];aq().set("requests",b,86400,!0)}
function dq(a){var b=aq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(U())-d.requestTime)){var e=d.authState,f=Zp(pp(!1));sb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(U())),eq(a,d.method,e,{}));delete b[c]}}aq().set("requests",b,86400,!0)}}
;function fq(a){this.Wb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.sb=function(){};
this.now=Date.now;this.Kb=!1;var b;this.Cd=null!=(b=a.Cd)?b:100;var c;this.wd=null!=(c=a.wd)?c:1;var d;this.ud=null!=(d=a.ud)?d:2592E6;var e;this.sd=null!=(e=a.sd)?e:12E4;var f;this.vd=null!=(f=a.vd)?f:5E3;var g;this.U=null!=(g=a.U)?g:void 0;this.cc=!!a.cc;var h;this.Zb=null!=(h=a.Zb)?h:.1;var k;this.mc=null!=(k=a.mc)?k:10;a.handleError&&(this.handleError=a.handleError);a.sb&&(this.sb=a.sb);a.Kb&&(this.Kb=a.Kb);a.Wb&&(this.Wb=a.Wb);this.V=a.V;this.Fa=a.Fa;this.da=a.da;this.ba=a.ba;this.sendFn=a.sendFn;
this.Lc=a.Lc;this.Kc=a.Kc;gq(this)&&(!this.V||this.V("networkless_logging"))&&hq(this)}
function hq(a){gq(a)&&!a.Kb&&(a.h=!0,a.cc&&Math.random()<=a.Zb&&a.da.Qd(a.U),iq(a),a.ba.wa()&&a.Tb(),a.ba.listen(a.Lc,a.Tb.bind(a)),a.ba.listen(a.Kc,a.Yc.bind(a)))}
m=fq.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(gq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.da.set(d,this.U).then(function(e){d.id=e;c.ba.wa()&&jq(c,d)}).catch(function(e){jq(c,d);
kq(c,e)})}else this.sendFn(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(gq(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.V&&this.V("nwl_skip_retry")&&(e.skipRetry=c);if(this.ba.wa()||this.V&&this.V("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(1==k.h)return k.yield(d.da.set(e,d.U).catch(function(l){kq(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.da.set(e,this.U).catch(function(g){d.sendFn(a,b,e.skipRetry);
kq(d,g)})}else this.sendFn(a,b,this.V&&this.V("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(gq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.da.pb(d.id,c.U):e=!0;c.ba.gb&&c.V&&c.V("vss_network_hint")&&c.ba.gb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.da.set(d,this.U).then(function(g){d.id=g;e&&c.da.pb(d.id,c.U)}).catch(function(g){kq(c,g)})}else this.sendFn(a,b,void 0,!0)};
m.Tb=function(){var a=this;if(!gq(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Fa.oa(function(){var b;return A(function(c){if(1==c.h)return c.yield(a.da.hd("NEW",a.U),2);if(3!=c.h)return b=c.i,b?c.yield(jq(a,b),3):(a.Yc(),c.return());a.i&&(a.i=0,a.Tb());c.h=0})},this.Cd))};
m.Yc=function(){this.Fa.qa(this.i);this.i=0};
function jq(a,b){var c;return A(function(d){switch(d.h){case 1:if(!gq(a))throw Error("IndexedDB is not supported: immediateSend");if(void 0===b.id){d.A(2);break}return d.yield(a.da.re(b.id,a.U),3);case 3:(c=d.i)||a.sb(Error("The request cannot be found in the database."));case 2:if(lq(a,b,a.ud)){d.A(4);break}a.sb(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){d.A(5);break}return d.yield(a.da.pb(b.id,a.U),5);case 5:return d.return();case 4:b.skipRetry||(b=mq(a,
b));if(!b){d.A(0);break}if(!b.skipRetry||void 0===b.id){d.A(8);break}return d.yield(a.da.pb(b.id,a.U),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function mq(a,b){if(!gq(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(n){switch(n.h){case 1:g=nq(f);(h=oq(f))&&a.V&&a.V("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.V&&a.V("nwl_consider_error_code")&&g||a.V&&!a.V("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.mc)){n.A(2);break}if(!a.ba.oc){n.A(3);break}return n.yield(a.ba.oc(),3);case 3:if(a.ba.wa()){n.A(2);break}c(e,f);if(!a.V||!a.V("nwl_consider_error_code")||void 0===(null==(k=b)?void 0:k.id)){n.A(6);
break}return n.yield(a.da.Oc(b.id,a.U,!1),6);case 6:return n.return();case 2:if(a.V&&a.V("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.mc)return n.return();a.potentialEsfErrorCounter++;if(void 0===(null==(l=b)?void 0:l.id)){n.A(8);break}return b.sendCount<a.wd?n.yield(a.da.Oc(b.id,a.U,!0,h?!1:void 0),12):n.yield(a.da.pb(b.id,a.U),8);case 12:a.Fa.oa(function(){a.ba.wa()&&a.Tb()},a.vd);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.A(2):h.yield(a.da.pb(b.id,a.U),2);a.ba.gb&&a.V&&a.V("vss_network_hint")&&a.ba.gb(!0);d(e,f);h.h=0})};
return b}
function lq(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function iq(a){if(!gq(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.da.hd("QUEUED",a.U).then(function(b){b&&!lq(a,b,a.sd)?a.Fa.oa(function(){return A(function(c){if(1==c.h)return void 0===b.id?c.A(2):c.yield(a.da.Oc(b.id,a.U),2);iq(a);c.h=0})}):a.ba.wa()&&a.Tb()})}
function kq(a,b){a.Id&&!a.ba.wa()?a.Id(b):a.handleError(b)}
function gq(a){return!!a.U||a.Wb}
function nq(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function oq(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var pq;
function qq(){if(pq)return pq();var a={};pq=Zo("LogsDatabaseV2",{Bb:(a.LogsRequestsStore={Gb:2},a),pc:!1,upgrade:function(b,c,d){c(2)&&fo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),mo(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return pq()}
;function rq(a){return yo(qq(),a)}
function sq(a,b){var c,d,e,f;return A(function(g){if(1==g.h)return c={startTime:U(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(rq(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:P("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(ho(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=U();tq(c);return g.return(f)})}
function uq(a,b){var c,d,e,f,g,h,k;return A(function(l){if(1==l.h)return c={startTime:U(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},l.yield(rq(b),2);if(3!=l.h)return d=l.i,e=P("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,U()],h=IDBKeyRange.bound(f,g),k=void 0,l.yield(eo(d,["LogsRequestsStore"],{mode:"readwrite",ja:!0},function(n){return ro(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(p){p.getValue()&&(k=p.getValue(),"NEW"===
a&&(k.status="QUEUED",p.update(k)))})}),3);
c.ticks.tc=U();tq(c);return l.return(k)})}
function vq(a,b){var c;return A(function(d){if(1==d.h)return d.yield(rq(b),2);c=d.i;return d.return(eo(c,["LogsRequestsStore"],{mode:"readwrite",ja:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",$n(f.h.put(g,void 0)).then(function(){return g})})}))})}
function wq(a,b,c,d){c=void 0===c?!0:c;var e;return A(function(f){if(1==f.h)return f.yield(rq(b),2);e=f.i;return f.return(eo(e,["LogsRequestsStore"],{mode:"readwrite",ja:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),void 0!==d&&(k.options.compress=d),$n(h.h.put(k,void 0)).then(function(){return k})):Un.resolve(void 0)})}))})}
function xq(a,b){var c;return A(function(d){if(1==d.h)return d.yield(rq(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function yq(a){var b,c;return A(function(d){if(1==d.h)return d.yield(rq(a),2);b=d.i;c=U()-2592E6;return d.yield(eo(b,["LogsRequestsStore"],{mode:"readwrite",ja:!0},function(e){return oo(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function zq(){A(function(a){return a.yield(Vo(),0)})}
function tq(a){R("nwl_csi_killswitch")||Dp("networkless_performance",a,{sampleRate:1})}
;var Aq={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,mbsConnectionInitiated:138,
mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,kidsParentalGateTracking:168,
kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
transactionFlowPaymentSubmitted:460,transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,
ypcPauseFlowSucceeded:190,ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,
ypcFamilyCreateFlowCancelled:259,ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,
accountRegistryChange:226,userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,
musicSideloadedPlaylistServiceCalled:246,embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,
yongleUsbSetup:271,touStrikeInterstitialEvent:272,liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,
notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,
tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,
iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,
mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,
mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,
clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,
mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,genericClientExperimentEvent:423,homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,
dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,
tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,
tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486,crossDeviceNotificationTransfer:487,androidIntentEvent:488,unpluggedAmbientInterludesCounterfactualEvent:489,keyPlaysPlayback:490,vssData:491};var Bq={},Cq=Zo("ServiceWorkerLogsDatabase",{Bb:(Bq.SWHealthLog={Gb:1},Bq),pc:!0,upgrade:function(a,b){b(1)&&mo(fo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function Dq(a){return yo(Cq(),a)}
function Eq(a){var b,c;A(function(d){if(1==d.h)return d.yield(Dq(a),2);b=d.i;c=U()-2592E6;return d.yield(eo(b,["SWHealthLog"],{mode:"readwrite",ja:!0},function(e){return oo(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Fq(a){var b;return A(function(c){if(1==c.h)return c.yield(Dq(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Gq={},Hq=0;function Iq(a){var b=new Image,c=""+Hq++;Gq[c]=b;b.onload=b.onerror=function(){delete Gq[c]};
b.src=a}
;function Jq(){this.h=new Map;this.i=!1}
function Kq(){if(!Jq.h){var a=D("yt.networkRequestMonitor.instance")||new Jq;C("yt.networkRequestMonitor.instance",a);Jq.h=a}return Jq.h}
Jq.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Jq.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
Jq.prototype.removeParams=function(a){return a.split("?")[0]};
Jq.prototype.removeParams=Jq.prototype.removeParams;Jq.prototype.isEndpointCFR=Jq.prototype.isEndpointCFR;Jq.prototype.requestComplete=Jq.prototype.requestComplete;Jq.getInstance=Kq;var Lq;function Mq(){Lq||(Lq=new pn("yt.offline"));return Lq}
function Nq(a){if(R("offline_error_handling")){var b=Mq().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Mq().set("errors",b,2592E3,!0)}}
;function Oq(){xd.call(this);var a=this;this.j=!1;this.i=Ii();this.i.listen("networkstatus-online",function(){if(a.j&&R("offline_error_handling")){var b=Mq().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new S(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;ll(d)}Mq().set("errors",{},2592E3,!0)}}})}
x(Oq,xd);function Pq(){if(!Oq.h){var a=D("yt.networkStatusManager.instance")||new Oq;C("yt.networkStatusManager.instance",a);Oq.h=a}return Oq.h}
m=Oq.prototype;m.wa=function(){return this.i.wa()};
m.gb=function(a){this.i.i=a};
m.de=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.Vd=function(){this.j=!0};
m.listen=function(a,b){return this.i.listen(a,b)};
m.oc=function(a){a=Ei(this.i,a);a.then(function(b){R("use_cfr_monitor")&&Kq().requestComplete("generate_204",b)});
return a};
Oq.prototype.sendNetworkCheckRequest=Oq.prototype.oc;Oq.prototype.listen=Oq.prototype.listen;Oq.prototype.enableErrorFlushing=Oq.prototype.Vd;Oq.prototype.getWindowStatus=Oq.prototype.de;Oq.prototype.networkStatusHint=Oq.prototype.gb;Oq.prototype.isNetworkAvailable=Oq.prototype.wa;Oq.getInstance=Pq;function Qq(a){a=void 0===a?{}:a;xd.call(this);var b=this;this.i=this.m=0;this.j=Pq();var c=D("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Rq(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Rq(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){yd(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){yd(b,"publicytnetworkstatus-offline")})))}
x(Qq,xd);Qq.prototype.wa=function(){var a=D("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Qq.prototype.gb=function(a){var b=D("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Qq.prototype.oc=function(a){var b=this,c;return A(function(d){c=D("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return R("skip_network_check_if_cfr")&&Kq().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.gb((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.wa())})):c?d.return(c(a)):d.return(!0)})};
function Rq(a,b){a.rateLimit?a.i?(Ji.qa(a.m),a.m=Ji.oa(function(){a.l!==b&&(yd(a,b),a.l=b,a.i=U())},a.rateLimit-(U()-a.i))):(yd(a,b),a.l=b,a.i=U()):yd(a,b)}
;var Sq;function Tq(){var a=fq.call;Sq||(Sq=new Qq({Yf:!0,Qf:!0}));a.call(fq,this,{da:{Qd:yq,pb:xq,hd:uq,re:vq,Oc:wq,set:sq},ba:Sq,handleError:function(b,c,d){var e,f=null==d?void 0:null==(e=d.error)?void 0:e.code;if(400===f||415===f){var g;ml(new S(b.message,c,null==d?void 0:null==(g=d.error)?void 0:g.code),void 0,void 0,void 0,!0)}else ll(b)},
sb:ml,sendFn:Uq,now:U,Id:Nq,Fa:on(),Lc:"publicytnetworkstatus-online",Kc:"publicytnetworkstatus-offline",cc:!0,Zb:.1,mc:Al("potential_esf_error_limit",10),V:R,Kb:!(Em()&&Vq())});this.j=new Wh;R("networkless_immediately_drop_all_requests")&&zq();Wo("LogsDatabaseV2")}
x(Tq,fq);function Wq(){var a=D("yt.networklessRequestController.instance");a||(a=new Tq,C("yt.networklessRequestController.instance",a),R("networkless_logging")&&Lo().then(function(b){a.U=b;hq(a);a.j.resolve();a.cc&&Math.random()<=a.Zb&&a.U&&Eq(a.U);R("networkless_immediately_drop_sw_health_store")&&Xq(a)}));
return a}
Tq.prototype.writeThenSend=function(a,b){b||(b={});Em()||(this.h=!1);fq.prototype.writeThenSend.call(this,a,b)};
Tq.prototype.sendThenWrite=function(a,b,c){b||(b={});Em()||(this.h=!1);fq.prototype.sendThenWrite.call(this,a,b,c)};
Tq.prototype.sendAndWrite=function(a,b){b||(b={});Em()||(this.h=!1);fq.prototype.sendAndWrite.call(this,a,b)};
Tq.prototype.awaitInitialization=function(){return this.j.promise};
function Xq(a){var b;A(function(c){if(!a.U)throw b=Qn("clearSWHealthLogsDb"),b;return c.return(Fq(a.U).catch(function(d){a.handleError(d)}))})}
function Uq(a,b,c,d){d=void 0===d?!1:d;b=R("web_fp_via_jspb")?Object.assign({},b):b;R("use_cfr_monitor")&&Yq(a,b);if(R("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(U())));else{var e;if(null==(e=b.postParams)?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(U())}if(c&&0===Object.keys(b).length){var f=void 0===f?"":f;var g=void 0===g?!1:g;var h=void 0===h?!1:h;if(a)if(f)Pl(a,void 0,"POST",f);else if(P("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||
h)Pl(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new bb({url:a});if(k.j&&k.i||k.l){var l=bc(cc(5,a)),n;if(!(n=!l||!l.endsWith("/aclk"))){var p=a.search(pc),t=oc(a,0,"ri",p);if(0>t)var r=null;else{var u=a.indexOf("&",t);if(0>u||u>p)u=p;r=decodeURIComponent(a.slice(t+3,-1!==u?u:0).replace(/\+/g," "))}n="1"!==r}var y=!n;break b}}catch(H){}y=!1}if(y){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(H){}z=!1}c=z?!0:!1}else c=
!1;c||Iq(a)}}else b.compress?b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),Vp(a,b.postBody,b,Ml,d)):Vp(a,JSON.stringify(b.postParams),b,Ul,d):Ml(a,b)}
function Yq(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Kq().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Kq().requestComplete(a,!0);d(e,f)}}
function Vq(){return"www.youtube-nocookie.com"!==dc(document.location.toString())}
;var Zq=!1,$q=B.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Zq};C("ytNetworklessLoggingInitializationOptions",$q);function ar(){var a;A(function(b){if(1==b.h)return b.yield(Lo(),2);a=b.i;if(!a||!Em()&&!R("nwl_init_require_datasync_id_killswitch")||!Vq())return b.A(0);Zq=!0;$q.isNwlInitialized=Zq;return b.yield(Wq().awaitInitialization(),0)})}
;function br(a){var b=this;this.config_=null;a?this.config_=a:mp()&&(this.config_=np());Hm(function(){dq(b)},5E3)}
br.prototype.isReady=function(){!this.config_&&mp()&&(this.config_=np());return!!this.config_};
function eq(a,b,c,d){function e(u){u=void 0===u?!1:u;var y;if(d.retry&&"www.youtube-nocookie.com"!=h&&(u||R("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(y=bq(b,c,l,k)),y)){var z=g.onSuccess,H=g.onFetchSuccess;g.onSuccess=function(da,T){cq(y);z(da,T)};
c.onFetchSuccess=function(da,T){cq(y);H(da,T)}}try{if(u&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Wq().writeThenSend(r,g):Wq().sendAndWrite(r,g);
else if(d.compress){var L=!d.networklessOptions.writeThenSend;if(g.postBody){var I=g.postBody;"string"!==typeof I&&(I=JSON.stringify(g.postBody));Vp(r,I,g,Ml,L)}else Vp(r,JSON.stringify(g.postParams),g,Ul,L)}else R("web_all_payloads_via_jspb")?Ml(r,g):Ul(r,g)}catch(da){if("InvalidAccessError"==da.name)y&&(cq(y),y=0),ml(Error("An extension is blocking network request."));else throw da;}y&&Hm(function(){dq(a)},5E3)}
!P("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&ml(new S("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new S("innertube xhrclient not ready",b,c,d);ll(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(u,y){if(d.onSuccess)d.onSuccess(y)},
onFetchSuccess:function(u){if(d.onSuccess)d.onSuccess(u)},
onError:function(u,y){if(d.onError)d.onError(y)},
onFetchError:function(u){if(d.onError)d.onError(u)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.me)&&(h=f);var k=a.config_.oe||!1,l=pp(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},t=a.config_.ne&&f;t=t&&f.startsWith("Bearer");t||(p.key=a.config_.innertubeApiKey);var r=vl(""+h+n,p||{},!0);(D("ytNetworklessLoggingInitializationOptions")?
$q.isNwlInitialized:Zq)?Jo().then(function(u){e(u)}):e(!1)}
;var cr=0,dr=Qc?"webkit":Mc?"moz":Kc?"ms":Jc?"o":"";C("ytDomDomGetNextId",D("ytDomDomGetNextId")||function(){return++cr});var er={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function fr(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in er||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function gr(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
fr.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
fr.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
fr.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var ob=B.ytEventsEventsListeners||{};C("ytEventsEventsListeners",ob);var hr=B.ytEventsEventsCounter||{count:0};C("ytEventsEventsCounter",hr);
function ir(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return nb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Pa(e[4])&&Pa(d)&&sb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var jr=db(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function kr(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=ir(a,b,c,d);if(e)return e;e=++hr.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new fr(h);if(!Hd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new fr(h);
h.currentTarget=a;return c.call(a,h)};
g=kl(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),jr()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);ob[e]=[a,b,c,g,d];return e}
function lr(a){a&&("string"==typeof a&&(a=[a]),fb(a,function(b){if(b in ob){var c=ob[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?jr()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete ob[b]}}))}
;function mr(a){this.B=a;this.h=null;this.l=0;this.u=null;this.m=0;this.i=[];for(a=0;4>a;a++)this.i.push(0);this.j=0;this.T=kr(window,"mousemove",Va(this.X,this));a=Va(this.K,this);"function"===typeof a&&(a=kl(a));this.Z=window.setInterval(a,25)}
Ya(mr,F);mr.prototype.X=function(a){void 0===a.h&&gr(a);var b=a.h;void 0===a.i&&gr(a);this.h=new Dd(b,a.i)};
mr.prototype.K=function(){if(this.h){var a=U();if(0!=this.l){var b=this.u,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.l);this.i[this.j]=.5<Math.abs((d-this.m)/this.m)?1:0;for(c=b=0;4>c;c++)b+=this.i[c]||0;3<=b&&this.B();this.m=d}this.l=a;this.u=this.h;this.j=(this.j+1)%4}};
mr.prototype.S=function(){window.clearInterval(this.Z);lr(this.T)};var nr={};
function or(a){var b=void 0===a?{}:a;a=void 0===b.Be?!1:b.Be;b=void 0===b.Wd?!0:b.Wd;if(null==D("_lact",window)){var c=parseInt(P("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;C("_lact",c,window);C("_fact",c,window);-1==c&&pr();kr(document,"keydown",pr);kr(document,"keyup",pr);kr(document,"mousedown",pr);kr(document,"mouseup",pr);a?kr(window,"touchmove",function(){qr("touchmove",200)},{passive:!0}):(kr(window,"resize",function(){qr("resize",200)}),b&&kr(window,"scroll",function(){qr("scroll",200)}));
new mr(function(){qr("mouse",100)});
kr(document,"touchstart",pr,{passive:!0});kr(document,"touchend",pr,{passive:!0})}}
function qr(a,b){nr[a]||(nr[a]=!0,Ji.oa(function(){pr();nr[a]=!1},b))}
function pr(){null==D("_lact",window)&&or();var a=Date.now();C("_lact",a,window);-1==D("_fact",window)&&C("_fact",a,window);(a=D("ytglobal.ytUtilActivityCallback_"))&&a()}
function rr(){var a=D("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var sr=B.ytPubsubPubsubInstance||new K,tr=B.ytPubsubPubsubSubscribedKeys||{},ur=B.ytPubsubPubsubTopicToKeys||{},vr=B.ytPubsubPubsubIsSynchronous||{};function wr(a,b){var c=xr();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){tr[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{vr[a]?f():Fl(f,0)}catch(g){ll(g)}},void 0);
tr[d]=!0;ur[a]||(ur[a]=[]);ur[a].push(d);return d}return 0}
function yr(a){var b=xr();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),fb(a,function(c){b.unsubscribeByKey(c);delete tr[c]}))}
function zr(a,b){var c=xr();c&&c.publish.apply(c,arguments)}
function Ar(a){var b=xr();if(b)if(b.clear(a),a)Br(a);else for(var c in ur)Br(c)}
function xr(){return B.ytPubsubPubsubInstance}
function Br(a){ur[a]&&(a=ur[a],fb(a,function(b){tr[b]&&delete tr[b]}),a.length=0)}
K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Eb;K.prototype.publish=K.prototype.Za;K.prototype.clear=K.prototype.clear;C("ytPubsubPubsubInstance",sr);C("ytPubsubPubsubTopicToKeys",ur);C("ytPubsubPubsubIsSynchronous",vr);C("ytPubsubPubsubSubscribedKeys",tr);var Cr=Symbol("injectionDeps");function Dr(a){this.name=a}
Dr.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Er(a){this.key=a}
function Fr(){this.h=new Map;this.i=new Map}
Fr.prototype.resolve=function(a){return a instanceof Er?Gr(this,a.key,[],!0):Gr(this,a,[])};
function Gr(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(void 0!==d.Fd)var e=d.Fd;else if(d.ef)e=d[Cr]?Hr(a,d[Cr],c):[],e=d.ef.apply(d,ma(e));else if(d.Ed){e=d.Ed;var f=e[Cr]?Hr(a,e[Cr],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ma(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.kg||a.i.set(b,e);return e}
function Hr(a,b,c){return b?b.map(function(d){return d instanceof Er?Gr(a,d.key,c,!0):Gr(a,d,c)}):[]}
;var Ir;function Jr(){Ir||(Ir=new Fr);return Ir}
;var Kr=window;function Lr(){var a,b;return"h5vcc"in Kr&&(null==(a=Kr.h5vcc.traceEvent)?0:a.traceBegin)&&(null==(b=Kr.h5vcc.traceEvent)?0:b.traceEnd)?1:"performance"in Kr&&Kr.performance.mark&&Kr.performance.measure?2:0}
function Mr(a){switch(Lr()){case 1:Kr.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Kr.performance.mark(a+"-start");break;case 0:break;default:oi()}}
function Nr(a){switch(Lr()){case 1:Kr.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:var b=a+"-start",c=a+"-end";Kr.performance.mark(c);Kr.performance.measure(a,b,c);break;case 0:break;default:oi()}}
;var Or=R("web_enable_lifecycle_monitoring")&&0!==Lr(),Pr=R("web_enable_lifecycle_monitoring");function Qr(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?on():d;this.j=c;this.scheduler=d;this.i=new Wh;this.h=a;for(a={cb:0};a.cb<this.h.length;a={Ob:a.Ob,cb:a.cb},a.cb++)a.Ob=this.h[a.cb],c=function(e){return function(){e.Ob.Fc();b.h[e.cb].nc=!0;b.h.every(function(f){return!0===f.nc})&&b.i.resolve()}}(a),d=this.getPriority(a.Ob),d=this.scheduler.ab(c,d),this.h[a.cb]=Object.assign({},a.Ob,{Fc:c,
jobId:d})}
function Rr(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=w(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.nc||(a.scheduler.qa(c.jobId),a.scheduler.ab(c.Fc,10))}
Qr.prototype.cancel=function(){for(var a=w(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.nc||this.scheduler.qa(b.jobId),b.nc=!0;this.i.resolve()};
Qr.prototype.getPriority=function(a){var b;return null!=(b=a.priority)?b:this.j};function Sr(a){this.state=a;this.plugins=[];this.l=void 0;this.u={};Or&&Mr(this.state)}
m=Sr.prototype;m.install=function(a){this.plugins.push(a);return this};
m.uninstall=function(){var a=this;Ia.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
m.transition=function(a,b){var c=this;Or&&Nr(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Rr(this.j),this.j=void 0);Tr(this,a,b);this.state=a;Or&&Mr(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Ur(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Ur(a,b){var c=b.filter(function(e){return 10===Vr(a,e)}),d=b.filter(function(e){return 10!==Vr(a,e)});
return a.u.jg?function(){var e=Ia.apply(0,arguments);return A(function(f){if(1==f.h)return f.yield(a.Ie.apply(a,[c].concat(ma(e))),2);a.zd.apply(a,[d].concat(ma(e)));f.h=0})}:function(){var e=Ia.apply(0,arguments);
a.Je.apply(a,[c].concat(ma(e)));a.zd.apply(a,[d].concat(ma(e)))}}
m.Je=function(a){for(var b=Ia.apply(1,arguments),c=on(),d=w(a),e=d.next(),f={};!e.done;f={xb:f.xb},e=d.next())f.xb=e.value,c.Fb(function(g){return function(){Wr(g.xb.name);g.xb.callback.apply(g.xb,ma(b));Xr(g.xb.name)}}(f))};
m.Ie=function(a){var b=Ia.apply(1,arguments),c,d,e,f,g;return A(function(h){1==h.h&&(c=on(),d=w(a),e=d.next(),f={});if(3!=h.h){if(e.done)return h.A(0);f.eb=e.value;f.Hb=void 0;g=function(k){return function(){Wr(k.eb.name);var l=k.eb.callback.apply(k.eb,ma(b));"function"===typeof(null==l?void 0:l.then)?k.Hb=l.then(function(){Xr(k.eb.name)}):Xr(k.eb.name)}}(f);
c.Fb(g);return f.Hb?h.yield(f.Hb,3):h.A(3)}f={eb:f.eb,Hb:f.Hb};e=d.next();return h.A(2)})};
m.zd=function(a){var b=Ia.apply(1,arguments),c=this,d=a.map(function(e){return{Fc:function(){Wr(e.name);e.callback.apply(e,ma(b));Xr(e.name)},
priority:Vr(c,e)}});
d.length&&(this.j=new Qr(d))};
function Vr(a,b){var c,d;return null!=(d=null!=(c=a.l)?c:b.priority)?d:0}
function Wr(a){Or&&a&&Mr(a)}
function Xr(a){Or&&a&&Nr(a)}
function Tr(a,b,c){Pr&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
ia.Object.defineProperties(Sr.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Yr(a){Sr.call(this,void 0===a?"none":a);this.h=null;this.l=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.m},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var Zr;x(Yr,Sr);Yr.prototype.i=function(a,b){var c=this;this.h=Hm(function(){"application_navigating"===c.currentState&&c.transition("none")},5E3);
a(null==b?void 0:b.event)};
Yr.prototype.m=function(a,b){this.h&&(Ji.qa(this.h),this.h=null);a(null==b?void 0:b.event)};
function $r(){Zr||(Zr=new Yr);return Zr}
;var as=[];C("yt.logging.transport.getScrapedGelPayloads",function(){return as});function bs(){this.store={};this.h={}}
bs.prototype.storePayload=function(a,b){a=cs(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
bs.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=ds(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,ma(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,ma(this.store[b[d]].splice(0,a.sizeLimit))));(null==a?0:a.sizeLimit)&&c.length<(null==a?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,ma(this.smartExtractMatchingEntries(a))));return c};
bs.prototype.extractMatchingEntries=function(a){a=ds(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ma(this.store[a[c]])),delete this.store[a[c]]);return b};
bs.prototype.getSequenceCount=function(a){a=ds(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=(null==(d=this.store[a[c]])?void 0:d.length)||0}return b};
function ds(a,b){var c=cs(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&cs(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(es(b.auth,g[0])){var h=b.isJspb;es(void 0===h?"undefined":h?"true":"false",g[1])&&es(b.cttAuthInfo,g[2])&&(h=b.tier,h=void 0===h?"undefined":JSON.stringify(h),es(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function es(a,b){return void 0===a||"undefined"===a?!0:a===b}
bs.prototype.getSequenceCount=bs.prototype.getSequenceCount;bs.prototype.extractMatchingEntries=bs.prototype.extractMatchingEntries;bs.prototype.smartExtractMatchingEntries=bs.prototype.smartExtractMatchingEntries;bs.prototype.storePayload=bs.prototype.storePayload;function cs(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo,void 0===a.tier?"undefined":a.tier].join("/")}
;function gs(a,b){if(a)return a[b.name]}
;var hs=Al("initial_gel_batch_timeout",2E3),is=Al("gel_queue_timeout_max_ms",6E4),js=Math.pow(2,16)-1,ks=Al("gel_min_batch_size",5),ls=void 0;function ms(){this.l=this.h=this.i=0;this.j=!1}
var ns=new ms,ps=new ms,qs=new ms,rs=new ms,ss,ts=!0,us=B.ytLoggingTransportTokensToCttTargetIds_||{};C("ytLoggingTransportTokensToCttTargetIds_",us);var vs={};function ws(){var a=D("yt.logging.ims");a||(a=new bs,C("yt.logging.ims",a));return a}
function xs(a,b){if("log_event"===a.endpoint){ys();var c=zs(a),d=As(a.payload)||"";a:{if(R("enable_web_tiered_gel")){var e=Aq[d||""];var f,g,h,k=null==Jr().resolve(new Er(hp))?void 0:null==(f=ip())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.eventLoggingConfig)?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(!1===e.enabled&&!R("web_payload_policy_disabled_killswitch"))return;k=Bs(e.tier);if(400===k){Cs(a,b);return}}vs[c]=
!0;e={cttAuthInfo:c,isJspb:!1,tier:k};ws().storePayload(e,a.payload);Ds(b,c,e,"gelDebuggingEvent"===d)}}
function Ds(a,b,c,d){function e(){Es({writeThenSend:!0},R("flush_only_full_queue")?b:void 0,f,c.tier)}
var f=!1;f=void 0===f?!1:f;d=void 0===d?!1:d;a&&(ls=new a);a=Al("tvhtml5_logging_max_batch_ads_fork")||Al("web_logging_max_batch")||100;var g=U(),h=Fs(f,c.tier),k=h.l;d&&(h.j=!0);d=0;c&&(d=ws().getSequenceCount(c));1E3<=d?e():d>=a?ss||(ss=Gs(function(){e();ss=void 0},0)):10<=g-k&&(Hs(f,c.tier),h.l=g)}
function Cs(a,b){if("log_event"===a.endpoint){ys();var c=zs(a),d=new Map;d.set(c,[a.payload]);var e=As(a.payload)||"";b&&(ls=new b);return new Ud(function(f,g){ls&&ls.isReady()?Is(d,ls,f,g,{bypassNetworkless:!0},!0,"gelDebuggingEvent"===e):f()})}}
function zs(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);us[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Es(a,b,c,d){a=void 0===a?{}:a;c=void 0===c?!1:c;new Ud(function(e,f){var g=Fs(c,d),h=g.j;g.j=!1;Js(g.i);Js(g.h);g.h=0;ls&&ls.isReady()?void 0===d&&R("enable_web_tiered_gel")?Ks(e,f,a,b,c,300,h):Ks(e,f,a,b,c,d,h):(Hs(c,d),e())})}
function Ks(a,b,c,d,e,f,g){var h=ls;c=void 0===c?{}:c;e=void 0===e?!1:e;f=void 0===f?200:f;g=void 0===g?!1:g;var k=new Map;var l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(void 0!==d)f=R("enable_web_tiered_gel")?ws().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):ws().extractMatchingEntries(e),k.set(d,f);else for(d=w(Object.keys(vs)),l=d.next();!l.done;l=d.next())l=l.value,e=R("enable_web_tiered_gel")?ws().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):ws().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),0<e.length&&k.set(l,e),(R("web_fp_via_jspb_and_json")&&c.writeThenSend||!R("web_fp_via_jspb_and_json"))&&delete vs[l];Is(k,h,a,b,c,!1,g)}
function Hs(a,b){function c(){Es({writeThenSend:!0},void 0,a,b)}
a=void 0===a?!1:a;b=void 0===b?200:b;var d=Fs(a,b),e=d===rs||d===qs?5E3:is;R("web_gel_timeout_cap")&&!d.h&&(e=Gs(function(){c()},e),d.h=e);
Js(d.i);e=P("LOGGING_BATCH_TIMEOUT",Al("web_gel_debounce_ms",1E4));R("shorten_initial_gel_batch_timeout")&&ts&&(e=hs);e=Gs(function(){0<Al("gel_min_batch_size")?ws().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=ks&&c():c()},e);
d.i=e}
function Is(a,b,c,d,e,f,g){e=void 0===e?{}:e;var h=Math.round(U()),k=a.size,l=(void 0===g?0:g)&&R("vss_through_gel_video_stats")?"video_stats":"log_event";a=w(a);var n=a.next();for(g={};!n.done;g={ic:g.ic,batchRequest:g.batchRequest,dangerousLogToVisitorSession:g.dangerousLogToVisitorSession,kc:g.kc,jc:g.jc},n=a.next()){var p=w(n.value);n=p.next().value;p=p.next().value;g.batchRequest=ub({context:op(b.config_||np())});if(!Oa(p)&&!R("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=
p;(p=us[n])&&Ls(g.batchRequest,n,p);delete us[n];g.dangerousLogToVisitorSession="visitorOnlyApprovedKey"===n;Ms(g.batchRequest,h,g.dangerousLogToVisitorSession);R("always_send_and_write")&&(e.writeThenSend=!1);g.kc=function(t){R("start_client_gcf")&&Ji.oa(function(){return A(function(r){return r.yield(Ns(t),0)})});
k--;k||c()};
g.ic=0;g.jc=function(t){return function(){t.ic++;if(e.bypassNetworkless&&1===t.ic)try{eq(b,l,t.batchRequest,Os({writeThenSend:!0},t.dangerousLogToVisitorSession,t.kc,t.jc,f)),ts=!1}catch(r){ll(r),d()}k--;k||c()}}(g);
try{eq(b,l,g.batchRequest,Os(e,g.dangerousLogToVisitorSession,g.kc,g.jc,f)),ts=!1}catch(t){ll(t),d()}}}
function Os(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,Nf:!!e,headers:{},postBodyFormat:"",postBody:"",compress:R("compress_gel")||R("compress_gel_lr")};Ps()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(U())));return a}
function Ms(a,b,c){Ps()||(a.requestTimeMs=String(b));R("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=P("EVENT_ID"))&&((c=P("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*js/2)),c++,c>js&&(c=1),gl("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Ls(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function ys(){var a;(a=D("yt.logging.transport.enableScrapingForTest"))||(a=zl("il_payload_scraping"),a="enable_il_payload_scraping"!==(void 0!==a?String(a):""));a||(as=[],C("yt.logging.transport.enableScrapingForTest",!0),C("yt.logging.transport.scrapedPayloadsForTesting",as),C("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),C("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
C("yt.logging.transport.scrapeClientEvent",!0))}
function Ps(){return R("use_request_time_ms_header")||R("lr_use_request_time_ms_header")}
function Gs(a,b){return R("transport_use_scheduler")?R("logging_avoid_blocking_during_navigation")||R("lr_logging_avoid_blocking_during_navigation")?Hm(function(){if("none"===$r().currentState)a();else{var c={};$r().install((c.none={callback:a},c))}},b):Hm(a,b):Fl(a,b)}
function Js(a){R("transport_use_scheduler")?Ji.qa(a):window.clearTimeout(a)}
function Ns(a){var b,c,d,e,f,g,h,k,l,n;return A(function(p){return 1==p.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=gs(d,Mk),g=null==(f=d)?void 0:f.hotHashData,h=gs(d,Lk),l=null==(k=d)?void 0:k.coldHashData,(n=Jr().resolve(new Er(hp)))?g?e?p.yield(jp(n,g,e),2):p.yield(jp(n,g),2):p.A(2):p.return()):l?h?p.yield(kp(n,l,h),0):p.yield(kp(n,l),0):p.A(0)})}
function Fs(a,b){b=void 0===b?200:b;return a?300===b?rs:ps:300===b?qs:ns}
function As(a){a=Object.keys(a);a=w(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,Aq[b])return b}
function Bs(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var Qs=B.ytLoggingGelSequenceIdObj_||{};C("ytLoggingGelSequenceIdObj_",Qs);
function Rs(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||U());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=rr();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!R("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,Qs[b]=b in Qs?Qs[b]+1:0,a.sequence={index:Qs[b],groupKey:b},d.endOfSequence&&delete Qs[d.sequenceGroup]);(d.sendIsolatedPayload?Cs:xs)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function yn(a,b,c){c=void 0===c?{}:c;var d=br;P("ytLoggingEventsDefaultDisabled",!1)&&br===br&&(d=null);R("web_all_payloads_via_jspb")&&!c.timestamp&&(c.lact=rr(),c.timestamp=U());Rs(a,b,d,c)}
;C("ytLoggingGelSequenceIdObj_",B.ytLoggingGelSequenceIdObj_||{});var Ss=new Set,Ts=0,Us=0,Vs=0,Ws=[],Xs=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function xn(a){Ys(a)}
function Zs(a){Ys(a,"WARNING")}
function $s(a){a instanceof Error?Ys(a):(a=Pa(a)?JSON.stringify(a):String(a),a=new S(a),a.name="RejectedPromiseError",Zs(a))}
function Ys(a,b,c,d,e,f,g,h){f=void 0===f?{}:f;f.name=c||P("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||P("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),R("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(5<=Ts))){d=Ws;var k=Bc(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var n=l.split("\n");n.shift();l=n.join("\n")}n=k.lineNumber||"Not available";k=k.fileName||"Not available";var p=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var t=0;t<a.args.length&&!(p=dm(a.args[t],"params."+t,c,p),
500<=p);t++);else if(a.hasOwnProperty("params")&&a.params){var r=a.params;if("object"===typeof a.params)for(t in r){if(r[t]){var u="params."+t,y=fm(r[t]);c[u]=y;p+=u.length+y.length;if(500<p)break}}else c.params=fm(r)}if(d.length)for(t=0;t<d.length&&!(p=dm(d[t],"params.context."+t,c,p),500<=p);t++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);t={message:e,name:f,lineNumber:n,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(t.lineNumber=
t.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=$l();c=w(a.Ua);for(d=c.next();!d.done;d=c.next())if(d=d.value,t.message&&t.message.match(d.ag)){a=d.weight;break a}a=w(a.Ra);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(t)){a=c.weight;break a}a=1}t.sampleWeight=a;a=w(Vl);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.lc[t.name])for(e=w(c.lc[t.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=t.message.match(f.regexp)){t.params["params.error.original"]=d[0];e=f.groups;f={};
for(n=0;n<e.length;n++)f[e[n]]=d[n+1],t.params["params.error."+e[n]]=d[n+1];t.message=c.Ic(f);break}t.params||(t.params={});a=$l();t.params["params.errorServiceSignature"]="msg="+a.Ua.length+"&cb="+a.Ra.length;t.params["params.serviceWorker"]="false";B.document&&B.document.querySelectorAll&&(t.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Ab("sample").constructor!==zb&&(t.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(t);
if(0!==t.sampleWeight&&!Ss.has(t.message)){if(g&&R("web_enable_error_204"))at(void 0===b?"ERROR":b,t);else{b=void 0===b?"ERROR":b;"ERROR"===b?(am.Za("handleError",t),R("record_app_crashed_web")&&0===Vs&&1===t.sampleWeight&&(Vs++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},R("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:t.message}}}}),yn("appCrashed",g)),Us++):"WARNING"===b&&am.Za("handleWarning",t);if(R("kevlar_gel_error_routing")){g=b;h=void 0===
h?{}:h;b:{a=w(Xs);for(c=a.next();!c.done;c=a.next())if(En(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:t.stack};t.fileName&&(c.filename=t.fileName);a=t.lineNumber&&t.lineNumber.split?t.lineNumber.split(":"):[];0!==a.length&&(1!==a.length||isNaN(Number(a[0]))?2!==a.length||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:t.message,errorClassName:t.name,sampleWeight:t.sampleWeight};
"ERROR"===g?a.level="ERROR_LEVEL_ERROR":"WARNING"===g&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];P("FEXP_EXPERIMENTS")&&(h.experimentIds=P("FEXP_EXPERIMENTS"));e=P("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!hl("web_disable_gel_stp_ecatcher_killswitch")&&e)for(f=w(Object.keys(e)),d=f.next();!d.done;d=f.next())d=d.value,h.kvPairs.push({key:d,value:String(e[d])});if(e=t.params)for(f=w(Object.keys(e)),d=f.next();!d.done;d=f.next())d=
d.value,h.kvPairs.push({key:"client."+d,value:String(e[d])});d=P("SERVER_NAME");e=P("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(yn("clientError",h),("ERROR"===g||R("errors_flush_gel_always_killswitch"))&&Es(void 0,void 0,!1))}R("suppress_error_204_logging")||at(b,t)}try{Ss.add(t.message)}catch(z){}Ts++}}}
function at(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:P("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=w(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=P("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=w(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=P("SERVER_NAME");b=P("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Ml(P("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function bt(){this.register=new Map}
function ct(a){a=w(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.fg("ABORTED")}
bt.prototype.clear=function(){ct(this);this.register.clear()};
var dt=new bt;var et=Date.now().toString();
function ft(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(et)for(a=1,b=0;b<et.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^et.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var gt,ht=B.ytLoggingDocDocumentNonce_;ht||(ht=ft(),C("ytLoggingDocDocumentNonce_",ht));gt=ht;function jt(a){this.h=a}
m=jt.prototype;m.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
m.getAsJspb=function(){var a=new Tk;void 0!==this.h.trackingParams?a.setTrackingParams(this.h.trackingParams):(void 0!==this.h.veType&&G(a,2,Hf(this.h.veType)),void 0!==this.h.veCounter&&G(a,6,Hf(this.h.veCounter)),void 0!==this.h.elementIndex&&G(a,3,Hf(this.h.elementIndex)),this.h.isCounterfactual&&G(a,5,Ef(!0)));if(void 0!==this.h.dataElement){var b=this.h.dataElement.getAsJspb();ng(a,Tk,7,b)}void 0!==this.h.youtubeData&&ng(a,Nk,8,this.h.jspbYoutubeData);return a};
m.toString=function(){return JSON.stringify(this.getAsJson())};
m.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
m.getLoggingDirectives=function(){return this.h.loggingDirectives};function kt(a){return P("client-screen-nonce-store",{})[void 0===a?0:a]}
function lt(a,b){b=void 0===b?0:b;var c=P("client-screen-nonce-store");c||(c={},gl("client-screen-nonce-store",c));c[b]=a}
function mt(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function nt(a){return P(mt(void 0===a?0:a))}
C("yt_logging_screen.getRootVeType",nt);function ot(){var a=P("csn-to-ctt-auth-info");a||(a={},gl("csn-to-ctt-auth-info",a));return a}
function pt(){return Object.values(P("client-screen-nonce-store",{})).filter(function(a){return void 0!==a})}
function qt(a){a=kt(void 0===a?0:a);if(!a&&!P("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
C("yt_logging_screen.getCurrentCsn",qt);function rt(a,b,c){var d=ot();(c=qt(c))&&delete d[c];b&&(d[a]=b)}
function st(a){return ot()[a]}
C("yt_logging_screen.getCttAuthInfo",st);C("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=void 0===c?0:c;if(a!==kt(c)||b!==P(mt(c)))if(rt(a,d,c),lt(a,c),gl(mt(c),b),b=function(){setTimeout(function(){a&&yn("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:gt,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});var tt=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};C("yt.msgs_",tt);function ut(a){bl(tt,arguments)}
;function vt(){var a=tb(wt),b;return(new Ud(function(c,d){a.onSuccess=function(e){El(e)?c(new xt(e)):d(new zt("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new zt("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new zt("Request timed out","net.timeout",e))};
b=Ml("//googleads.g.doubleclick.net/pagead/id",a)})).qc(function(c){c instanceof ae&&b.abort();
return Zd(c)})}
function zt(a,b,c){$a.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
x(zt,$a);function xt(a){this.xhr=a}
;function At(){this.h=0;this.value_=null}
At.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.value_))&&"function"===typeof a.then?a:Bt(a):2===this.h&&b?(a=b.call(c,this.value_))&&"function"===typeof a.then?a:Ct(a):this};
At.prototype.getValue=function(){return this.value_};
At.prototype.isRejected=function(){return 2==this.h};
At.prototype.$goog_Thenable=!0;function Ct(a){var b=new At;a=void 0===a?null:a;b.h=2;b.value_=void 0===a?null:a;return b}
function Bt(a){var b=new At;a=void 0===a?null:a;b.h=1;b.value_=void 0===a?null:a;return b}
;function Dt(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:wl(a)?"same-origin":"cors",credentials:wl(a)?"same-origin":"include"};b={};for(var d=w(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function Et(){return Ng()||(Ae||Be)&&En("applewebkit")&&!En("version")&&(!En("safari")||En("gsa/"))||Rc&&En("version/")?!0:P("EOM_VISITOR_DATA")?!1:!0}
;function Ft(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Rk)if(Rk[d]==c.embeddedPlayerMode){b=Rk[d];break b}}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function Gt(a){$a.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Ht;this.isTimeout=a instanceof zt&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof ae}
x(Gt,$a);Gt.prototype.name="BiscottiError";function Ht(){$a.call(this,"Biscotti ID is missing from server")}
x(Ht,$a);Ht.prototype.name="BiscottiMissingError";var wt={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},It=null;function Jt(){if(R("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Et())return Error("User has not consented - not fetching biscotti id.");var a=P("PLAYER_VARS",{});if("1"==rb(a))return Error("Biscotti ID is not available in private embed mode");if(Ft(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function $k(){var a=Jt();if(void 0!==a)return Zd(a);It||(It=vt().then(Kt).qc(function(b){return Lt(2,b)}));
return It}
function Kt(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new Ht;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new Ht;a=a.id;al(a);It=Bt(a);Mt(18E5,2);return a}
function Lt(a,b){b=new Gt(b);al("");It=Ct(b);0<a&&Mt(12E4,a-1);throw b;}
function Mt(a,b){Fl(function(){vt().then(Kt,function(c){return Lt(b,c)}).qc(cb)},a)}
function Nt(){try{var a=D("yt.ads.biscotti.getId_");return a?a():$k()}catch(b){return Zd(b)}}
;function Ot(a){if("1"!=rb(P("PLAYER_VARS",{}))){a&&Zk();try{Nt().then(function(){},function(){}),Fl(Ot,18E5)}catch(b){ll(b)}}}
;var Pt=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Qt(){var a=void 0===a?window.location.href:a;if(R("kevlar_disable_theme_param"))return null;bc(cc(5,a));try{var b=ul(a).theme;return Pt.get(b)||null}catch(c){}return null}
;function Rt(){this.h={};if(this.i=pm()){var a=nm("CONSISTENCY");a&&St(this,{encryptedTokenJarContents:a})}}
Rt.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.Pa.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=w(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];St(this,a)}};
function St(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&mm("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Tt=window.location.hostname.split(".").slice(-2).join(".");function Ut(){var a=P("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===P("INNERTUBE_CLIENT_NAME")&&(this.h=Vt(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Wt;function Xt(){Wt=D("yt.clientLocationService.instance");Wt||(Wt=new Ut,C("yt.clientLocationService.instance",Wt));return Wt}
m=Ut.prototype;m.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
m.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===P("INNERTUBE_CLIENT_NAME")?(this.h=Vt(this))&&this.h.set("yt-location-playability-token",a,15552E3):mm("YT_CL",JSON.stringify({loctok:a}),15552E3,Tt,!0))};
function Vt(a){return void 0===a.h?new pn("yt-client-location"):a.h}
m.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=Vt(this))&&this.h.remove("yt-location-playability-token"):om("YT_CL")};
m.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===P("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
m.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
m.createLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);return b};function Yt(a,b){var c,d=null==(c=gs(a,Qk))?void 0:c.signal;if(d&&b.Sb&&(c=b.Sb[d]))return c();var e;if((c=null==(e=gs(a,Ok))?void 0:e.request)&&b.Sd&&(e=b.Sd[c]))return e();for(var f in a)if(b.bd[f]&&(a=b.bd[f]))return a()}
;function Zt(a){return function(){return new a}}
;var $t={},au=($t.WEB_UNPLUGGED="^unplugged/",$t.WEB_UNPLUGGED_ONBOARDING="^unplugged/",$t.WEB_UNPLUGGED_OPS="^unplugged/",$t.WEB_UNPLUGGED_PUBLIC="^unplugged/",$t.WEB_CREATOR="^creator/",$t.WEB_KIDS="^kids/",$t.WEB_EXPERIMENTS="^experiments/",$t.WEB_MUSIC="^music/",$t.WEB_REMIX="^music/",$t.WEB_MUSIC_EMBEDDED_PLAYER="^music/",$t.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",$t);
function bu(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=au[b];if(c){var d=new RegExp(c),e=w(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(au).forEach(function(g){var h=w(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=w(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function cu(){}
cu.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?jm:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=P("INNERTUBE_CONTEXT");if(g){g=ub(g);R("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=P("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;tm();var l="USER_INTERFACE_THEME_LIGHT";xm(165)?l="USER_INTERFACE_THEME_DARK":xm(174)?l="USER_INTERFACE_THEME_LIGHT":!R("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");k=k?l:Qt()||l;h.userInterfaceTheme=k;if(!f){if(k=Cm())h.connectionType=
k;R("web_log_effective_connection_type")&&(k=Dm())&&(g.client.effectiveConnectionType=k)}var n;if(R("web_log_memory_total_kbytes")&&(null==(n=B.navigator)?0:n.deviceMemory)){var p;n=null==(p=B.navigator)?void 0:p.deviceMemory;g.client.memoryTotalKbytes=""+1E6*n}R("web_gcf_hashes_innertube")&&(k=lp())&&(p=k.coldConfigData,n=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},g.client.configInfo.coldConfigData=p,g.client.configInfo.coldHashData=n,g.client.configInfo.hotHashData=
k);p=ul(B.location.href);!R("web_populate_internal_geo_killswitch")&&p.internalcountrycode&&(h.internalGeo=p.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:B.location.href},R("kevlar_woffle")&&km.h&&(p=km.h,h.mainAppWebInfo.pwaInstallabilityStatus=!p.h&&p.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=lm(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):
"TVHTML5"===h.clientName&&(!R("web_lr_app_quality_killswitch")&&(p=P("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:p})),p=P("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:p}));if(!R("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var t=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(J){}t=void 0}t&&(h.timeZone=t)}(t=P("EXPERIMENTS_TOKEN",""))?h.experimentsToken=
t:delete h.experimentsToken;t=Bl();Rt.h||(Rt.h=new Rt);h=Rt.h.h;p=[];n=0;for(var r in h)p[n++]=h[r];g.request=Object.assign({},g.request,{internalExperimentFlags:t,consistencyTokenJars:p});!R("web_prequest_context_killswitch")&&(r=P("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=r);t=tm();r=xm(58);t=t.get("gsml","");g.user=Object.assign({},g.user);r&&(g.user.enableSafetyMode=r);t&&(g.user.lockedSafetyMode=!0);R("warm_op_csn_cleanup")?e&&(f=qt())&&(g.clientScreenNonce=f):
!f&&(f=qt())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=D("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Xt().setLocationOnInnerTubeContext(g);try{var u=xl(),y=u.bid;delete u.bid;g.adSignalsInfo={params:[],bid:y};var z=w(Object.entries(u));for(var H=z.next();!H.done;H=z.next()){var L=w(H.value),I=L.next().value,da=L.next().value;u=I;y=da;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:u,value:""+y})}var T;if(R("add_ifa_to_tvh5_requests")&&"TVHTML5"===(null==
(T=g.client)?void 0:T.clientName)){var N=P("INNERTUBE_CONTEXT");N.adSignalsInfo&&(g.adSignalsInfo.advertisingId=N.adSignalsInfo.advertisingId,g.adSignalsInfo.limitAdTracking=N.adSignalsInfo.limitAdTracking)}}catch(J){Ys(J)}z=g}else Ys(Error("Error: No InnerTubeContext shell provided in ytconfig.")),z={};z={context:z};if(H=this.h(a)){this.i(z,H,b);var ba;b="/youtubei/v1/"+bu(this.j());(H=null==(ba=gs(a.commandMetadata,Pk))?void 0:ba.apiUrl)&&(b=H);ba=b;(b=P("INNERTUBE_HOST_OVERRIDE"))&&(ba=String(b)+
String(ec(ba)));b={};b.key=P("INNERTUBE_API_KEY");R("json_condensed_response")&&(b.prettyPrint="false");ba=vl(ba,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:ba,ib:Dt(ba),Pa:z,config:a};a.config.Vb?a.config.Vb.identity=c:a.config.Vb={identity:c};return a}Ys(new S("Error: Failed to create Request from Command.",a))};
ia.Object.defineProperties(cu.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function du(){}
x(du,cu);du.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",ib:Dt("/getDatasyncIdsEndpoint","GET"),Pa:{}}};
du.prototype.j=function(){return[]};
du.prototype.h=function(){};
du.prototype.i=function(){};var eu={},fu=(eu.GET_DATASYNC_IDS=Zt(du),eu);var gu="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function hu(a,b){var c=void 0===c?!0:c;var d=P("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=dc(window.location.href);e&&d.push(e);e=dc(a);if(0<=eb(d,e)||!e&&0==a.lastIndexOf("/",0))if(d=document.createElement("a"),ii(d,a),a=d.href)if(a=ec(a),a=fc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:qt()},b)),f){var f=parseInt(f,10);isFinite(f)&&0<f&&iu(a,b,f)}else iu(a,b)}
function iu(a,b,c){a=ju(a);b=b?kc(b):"";c=c||5;Et()&&mm(a,b,c)}
function ju(a){for(var b=w(gu),c=b.next();!c.done;c=b.next())a=rc(a,c.value);return"ST-"+$b(a).toString(36)}
;function ku(){try{return!!self.localStorage}catch(a){return!1}}
;function lu(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function mu(a){if(ku()){var b=Object.keys(window.localStorage);b=w(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=lu(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function nu(){if(!ku())return!1;var a=Fm(),b=Object.keys(window.localStorage);b=w(b);for(var c=b.next();!c.done;c=b.next())if(c=lu(c.value),void 0!==c&&c!==a)return!0;return!1}
;function ou(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return R("copy_login_info_to_st_cookie")&&("WEB"===P("INNERTUBE_CLIENT_NAME")||"WEB_CREATOR"===P("INNERTUBE_CLIENT_NAME"))&&a}
function pu(a){if(P("LOGGED_IN",!0)&&ou()){var b=P("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=dc(window.location.href);c&&b.push(c);c=dc(a);0<=eb(b,c)||!c&&0==a.lastIndexOf("/",0)?(b=ec(a),(b=fc(b))?(b=ju(b),b=(b=nm(b)||null)?tl(b):{}):b=null):b=null;null==b&&(b={});c=b;var d=void 0;ou()?(d||(d=P("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&hu(a,b)}}
;function qu(a){var b=Ia.apply(1,arguments);if(!ru(a)||b.some(function(d){return!ru(d)}))throw Error("Only objects may be merged.");
b=w(b);for(var c=b.next();!c.done;c=b.next())su(a,c.value);return a}
function su(a,b){for(var c in b)if(ru(b[c])){if(c in a&&!ru(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});su(a[c],b[c])}else if(tu(b[c])){if(c in a&&!tu(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);uu(a[c],b[c])}else a[c]=b[c];return a}
function uu(a,b){b=w(b);for(var c=b.next();!c.done;c=b.next())c=c.value,ru(c)?a.push(su({},c)):tu(c)?a.push(uu([],c)):a.push(c);return a}
function ru(a){return"object"===typeof a&&!Array.isArray(a)}
function tu(a){return"object"===typeof a&&Array.isArray(a)}
;function vu(a){var b;(b=D("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},C("ytcsi."+(a||"")+"data_",b));return b}
function wu(){var a=vu();a.info||(a.info={});return a.info}
function xu(a){a=vu(a);a.metadata||(a.metadata={});return a.metadata}
function yu(a){a=vu(a);a.tick||(a.tick={});return a.tick}
function zu(a){a=vu(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Au(a){a=zu(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function Bu(a){var b=vu(a).nonce;b||(b=ft(),vu(a).nonce=b);return b}
;function Cu(){var a=D("ytcsi.debug");a||(a=[],C("ytcsi.debug",a),C("ytcsi.reference",{}));return a}
function Du(a){a=a||"";var b=D("ytcsi.reference");b||(Cu(),b=D("ytcsi.reference"));if(b[a])return b[a];var c=Cu(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var W={},Eu=(W.auto_search="LATENCY_ACTION_AUTO_SEARCH",W.ad_to_ad="LATENCY_ACTION_AD_TO_AD",W.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",W["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",W.app_startup="LATENCY_ACTION_APP_STARTUP",W["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",W["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",W["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",W["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
W["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",W["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",W["asset.composition_policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",W["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",W["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",W["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",W["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",W["asset.ownership"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",W["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",W["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",W["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",W["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",W["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",W["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",W["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",
W["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",W["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",W.browse="LATENCY_ACTION_BROWSE",W.cast_splash="LATENCY_ACTION_CAST_SPLASH",W.channels="LATENCY_ACTION_CHANNELS",W.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",W["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",W["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",W["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",
W["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",W["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",W["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",W["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",W["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",W["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",W["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",W["channel.translations"]=
"LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",W["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",W["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",W.chips="LATENCY_ACTION_CHIPS",W.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",W["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",W["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",W["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",W.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",
W.embed="LATENCY_ACTION_EMBED",W.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",W.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",W.explore="LATENCY_ACTION_EXPLORE",W.home="LATENCY_ACTION_HOME",W.library="LATENCY_ACTION_LIBRARY",W.live="LATENCY_ACTION_LIVE",W.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",W.mini_app="LATENCY_ACTION_MINI_APP_PLAY",W.onboarding="LATENCY_ACTION_ONBOARDING",W.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",
W["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",W["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",W["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",W["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",W["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",W["owner.bulk"]="LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",W["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",W["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",W["owner.channels"]=
"LATENCY_ACTION_CREATOR_CMS_CHANNELS",W["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",W["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",W["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",W["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",W["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",W["owner.pitch_music"]=
"LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",W["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",W["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",W["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",W["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",W.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",W.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",W.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",W.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",
W["playlist.videos"]="LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",W["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",W["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",W.prebuffer="LATENCY_ACTION_PREBUFFER",W.prefetch="LATENCY_ACTION_PREFETCH",W.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",W.profile_switcher="LATENCY_ACTION_LOGIN",W.reel_watch="LATENCY_ACTION_REEL_WATCH",W.results="LATENCY_ACTION_RESULTS",W["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",W.search_ui="LATENCY_ACTION_SEARCH_UI",
W.search_suggest="LATENCY_ACTION_SUGGEST",W.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",W.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",W.seek="LATENCY_ACTION_PLAYER_SEEK",W.settings="LATENCY_ACTION_SETTINGS",W.store="LATENCY_ACTION_STORE",W.tenx="LATENCY_ACTION_TENX",W.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",W.watch="LATENCY_ACTION_WATCH",W.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",W["watch,watch7"]="LATENCY_ACTION_WATCH",W["watch,watch7_html5"]="LATENCY_ACTION_WATCH",W["watch,watch7ad"]=
"LATENCY_ACTION_WATCH",W["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",W.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",W.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",W["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",W["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",W["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",W["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",W["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",W["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",
W["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",W["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",W["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",W["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",W["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",W["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",W["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",W.voice_assistant=
"LATENCY_ACTION_VOICE_ASSISTANT",W.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",W.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",W.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",W.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",W),Y={},Fu=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an="adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p=
"httpProtocol",Y.t="transportProtocol",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav=
"kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.pnt="performanceNavigationTiming",Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",
Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs="tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",
Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID=
"requestIds",Y),Gu="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Hu={},Iu=(Hu.ccs="CANARY_STATE_",Hu.mver="MEASUREMENT_VERSION_",Hu.pis="PLAYER_INITIALIZED_STATE_",Hu.yt_pt="LATENCY_PLAYER_",Hu.pa="LATENCY_ACTION_",
Hu.ctop="TOP_ENTITY_TYPE_",Hu.yt_vst="VIDEO_STREAM_TYPE_",Hu),Ju="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Ku(a,b,c){c=zu(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Fu){c=Fu[a];0<=eb(Gu,c)&&(b=!!b);a in Iu&&"string"===typeof b&&(b=Iu[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return qu({},d)}0<=eb(Ju,a)||Zs(new S("Unknown label logged with GEL CSI",a))}
;function Lu(a,b){qp.call(this,1,arguments);this.timer=b}
x(Lu,qp);var Mu=new rp("aft-recorded",Lu);var Nu=B.ytLoggingLatencyUsageStats_||{};C("ytLoggingLatencyUsageStats_",Nu);function Ou(){this.h=0}
function Pu(){Ou.h||(Ou.h=new Ou);return Ou.h}
Ou.prototype.tick=function(a,b,c,d){Qu(this,"tick_"+a+"_"+b)||yn("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
Ou.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Qu(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,yn("latencyActionInfo",a,{cttAuthInfo:c}))};
Ou.prototype.jspbInfo=function(){};
Ou.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Qu(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,yn("latencyActionSpan",a,{cttAuthInfo:c}))};
function Qu(a,b){Nu[b]=Nu[b]||{count:0};var c=Nu[b];c.count++;c.time=U();a.h||(a.h=Hm(function(){var d=U(),e;for(e in Nu)Nu[e]&&6E4<d-Nu[e].time&&delete Nu[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new S("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Zs(c)),!0):!1}
;var Ru=window;function Su(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Tu(){var a;if(R("csi_use_performance_navigation_timing")||R("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==Z?void 0:null==(a=Z.getEntriesByType)?void 0:null==(b=a.call(Z,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=Uu(e.requestStart),e.responseEnd=Uu(e.responseEnd),e.redirectStart=Uu(e.redirectStart),e.redirectEnd=Uu(e.redirectEnd),e.domainLookupEnd=Uu(e.domainLookupEnd),e.connectStart=Uu(e.connectStart),e.connectEnd=
Uu(e.connectEnd),e.responseStart=Uu(e.responseStart),e.secureConnectionStart=Uu(e.secureConnectionStart),e.domainLookupStart=Uu(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Z.timing}else a=Z.timing;return a}
function Uu(a){return Math.round(Vu()+a)}
function Vu(){return(R("csi_use_time_origin")||R("csi_use_time_origin_tvhtml5"))&&Z.timeOrigin?Math.floor(Z.timeOrigin):Z.timing.navigationStart}
var Z=Ru.performance||Ru.mozPerformance||Ru.msPerformance||Ru.webkitPerformance||new Su;var Wu=!1,Xu=!1,Yu={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Va(Z.clearResourceTimings||Z.webkitClearResourceTimings||Z.mozClearResourceTimings||Z.msClearResourceTimings||Z.oClearResourceTimings||cb,Z);function Zu(a,b,c,d){if(null!==b){if("yt_lt"===a){var e="string"===typeof b?b:""+b;xu(c).loadType=e}(a=Ku(a,b,c))&&$u(a,c,d)}}
function $u(a,b){if(!R("web_csi_action_sampling_enabled")||!vu(b).actionDisabled){var c=Du(b||"");qu(c.info,a);a.loadType&&(c=a.loadType,xu(b).loadType=c);qu(Au(b),a);c=Bu(b);b=vu(b).cttAuthInfo;Pu().info(a,c,b)}}
function av(){var a,b,c,d;return(null!=(d=null==Jr().resolve(new Er(hp))?void 0:null==(a=ip())?void 0:null==(b=a.loggingHotConfig)?void 0:null==(c=b.csiConfig)?void 0:c.debugTicks)?d:[]).map(function(e){return Object.values(e)[0]})}
function bv(a,b,c){if(!R("web_csi_action_sampling_enabled")||!vu(c).actionDisabled){var d=Bu(c),e;if(e=R("web_csi_debug_sample_enabled")&&d){(null==Jr().resolve(new Er(hp))?0:ip())&&!Xu&&(Xu=!0,bv("gcfl",U(),c));var f,g,h;e=(null==Jr().resolve(new Er(hp))?void 0:null==(f=ip())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.csiConfig)?void 0:h.debugSampleWeight)||0;if(f=0!==e)b:{f=av();if(0<f.length)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=31*f+
d.charCodeAt(g),g<d.length-1&&(f%=Math.pow(2,47));e=0!==f%1E5%e;vu(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,$u(f,c));vu(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){b||"_"===a[0]||(e=a,Z.mark&&(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),Z.mark(e)));e=Du(c||"");e.tick[a]=b||U();if(e.callback&&e.callback[a])for(e=w(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=zu(c);e.gelTicks&&(e.gelTicks[a]=!0);f=yu(c);e=b||U();R("log_repeated_ytcsi_ticks")?a in f||
(f[a]=e):f[a]=e;f=vu(c).cttAuthInfo;"_start"===a?(a=Pu(),Qu(a,"baseline_"+d)||yn("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):Pu().tick(a,d,b,f);cv(c);return e}}}
function dv(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=dr+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function ev(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);Yb()&&a.setAttribute("nonce",Yb());return c?(a=Z.getEntriesByName(c))&&a[0]&&(a=a[0],c=Vu(),bv("rsf_"+b,c+Math.round(a.fetchStart)),bv("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function fv(){var a=window.location.protocol,b=Z.getEntriesByType("resource");b=gb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=ib(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(bv("wffs",Uu(b.startTime)),bv("wffe",Uu(b.responseEnd)))}
function gv(a){var b=hv("aft",a);if(b)return b;b=P((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=hv(b[d],a);if(e)return e}return NaN}
function hv(a,b){if(a=yu(b)[a])return"number"===typeof a?a:a[a.length-1]}
function cv(a){var b=hv("_start",a),c=gv(a);b&&c&&!Wu&&(wp(Mu,new Lu(Math.round(c-b),a)),Wu=!0)}
function iv(a,b){for(var c=w(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!iv(a[d],b[d]))return!1;return!0}
function jv(){if(Z.getEntriesByType){var a=Z.getEntriesByType("paint");if(a=jb(a,function(b){return"first-paint"===b.name}))return Uu(a.startTime)}a=Z.timing;
return a.we?Math.max(0,a.we):0}
;function kv(a,b){kl(function(){Du("").info.actionType=a;b&&gl("TIMING_AFT_KEYS",b);gl("TIMING_ACTION",a);var c=P("TIMING_INFO",{}),d;for(d in c)c.hasOwnProperty(d)&&Zu(d,c[d]);c={isNavigation:!0,actionType:Eu[P("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};if(d=P("PREVIOUS_ACTION"))c.previousAction=Eu[d]||"LATENCY_ACTION_UNKNOWN";if(d=P("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=P("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=qt())&&"UNDEFINED_CSN"!==d&&(c.clientScreenNonce=d);d=dv();if(1===d||-1===d)c.isVisible=
!0;xu();wu();c.loadType="cold";d=wu();var e=Tu(),f=Vu(),g=P("CSI_START_TIMESTAMP_MILLIS",0);0<g&&!R("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(bv("srt",e.responseStart),1!==d.prerender&&bv("_start",f,void 0));d=jv();0<d&&bv("fpt",d);d=Tu();d.isPerformanceNavigationTiming&&$u({performanceNavigationTiming:!0},void 0);bv("nreqs",d.requestStart,void 0);bv("nress",d.responseStart,void 0);bv("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(bv("nrs",d.redirectStart,void 0),
bv("nre",d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(bv("ndnss",d.domainLookupStart,void 0),bv("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(bv("ntcps",d.connectStart,void 0),bv("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Vu()&&0<d.connectEnd-d.secureConnectionStart&&(bv("nstcps",d.secureConnectionStart,void 0),bv("ntcpe",d.connectEnd,void 0));Z&&"getEntriesByType"in Z&&fv();d=[];if(document.querySelector&&Z&&Z.getEntriesByName)for(var h in Yu)Yu.hasOwnProperty(h)&&
(e=Yu[h],ev(h,e)&&d.push(e));if(0<d.length)for(c.resourceInfo=[],h=w(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});$u(c);c=wu();h=zu();h.preLoggedGelInfos||(h.preLoggedGelInfos=[]);d=h.preLoggedGelInfos;h=Au();e=void 0;for(f=0;f<d.length;f++)if(g=d[f],g.loadType){e=g.loadType;break}if("cold"===xu().loadType&&("cold"===c.yt_lt||"cold"===h.loadType||"cold"===e)){e=yu();f=zu();f=f.gelTicks?f.gelTicks:f.gelTicks={};for(var k in e)if(!(k in f))if("number"===typeof e[k])bv(k,
hv(k));else if(R("log_repeated_ytcsi_ticks")){g=w(e[k]);for(var l=g.next();!l.done;l=g.next())l=l.value,bv(k.slice(1),l)}k={};e=!1;if(R("use_infogel_early_logging"))for(d=w(d),f=d.next();!f.done;f=d.next())e=f.value,qu(h,e),qu(k,e),e=!0;d=w(Object.keys(c));for(f=d.next();!f.done;f=d.next())f=f.value,(f=Ku(f,c[f]))&&!iv(Au(),f)&&(qu(h,f),qu(k,f),e=!0);e&&$u(k)}C("ytglobal.timingready_",!0);k=P("TIMING_ACTION");D("ytglobal.timingready_")&&k&&lv()&&gv()&&cv()})()}
function mv(a,b,c,d){kl(Zu)(a,b,c,d)}
function nv(a,b,c){kl($u)(a,b,void 0===c?!1:c)}
function ov(a,b,c){return kl(bv)(a,b,c)}
function lv(){return kl(function(){return"_start"in yu()})()}
function pv(){kl(function(){var a=Bu();requestAnimationFrame(function(){setTimeout(function(){a===Bu()&&ov("ol",void 0,void 0)},0)})})()}
var qv=window;qv.ytcsi&&(qv.ytcsi.info=mv,qv.ytcsi.Sf=nv,qv.ytcsi.tick=ov);var rv="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD".split(" "),sv=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function tv(a,b,c,d){this.m=a;this.ba=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Sb||(a.Sb={});a.Sb=Object.assign({},fu,a.Sb)}
function uv(a,b,c,d){if(void 0!==tv.h){if(d=tv.h,a=[a!==d.m,b!==d.ba,c!==d.l,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new S("InnerTubeTransportService is already initialized",a);
}else tv.h=new tv(a,b,c,d)}
function vv(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?jm:c;var d=Yt(b,a.m);if(!d)return Zd(new S("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?(pu(e.input),new Ud(function(f){var g,h,k;return A(function(l){if(1==l.h){h="cors"===(null==(g=e.ib)?void 0:g.mode)?"cors":void 0;if(a.l.Xe){var n=e.config,p;n=null==n?void 0:null==(p=n.Vb)?void 0:p.sessionIndex;p=im(0,{sessionIndex:n});k=Object.assign({},wv(h),p);return l.A(2)}return l.yield(xv(e.config,
h),3)}2!=l.h&&(k=l.i);f(yv(a,e,k));l.h=0})})):Zd(new S("Error: Failed to build request for command.",b))}
function zv(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.sequenceMetaData)?0:d.skipProcessing)&&a.j){d=w(rv);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function yv(a,b,c){var d,e,f,g,h,k,l,n,p,t,r,u,y,z,H,L,I,da,T,N,ba,J,ca,ha,V,ab,Nc,Oc,Pc;return A(function(X){switch(X.h){case 1:X.A(2);break;case 3:if((d=X.i)&&!d.isExpired())return X.return(Promise.resolve(d.h()));case 2:if(!(null==(e=b)?0:null==(f=e.Pa)?0:f.context)){X.A(4);break}g=b.Pa.context;X.A(5);break;case 5:h=w([]),k=h.next();case 7:if(k.done){X.A(4);break}l=k.value;return X.yield(l.eg(g),8);case 8:k=h.next();X.A(7);break;case 4:if(null==(n=a.i)||!n.ig(b.input,b.Pa)){X.A(11);break}return X.yield(a.i.Xf(b.input,
b.Pa),12);case 12:return p=X.i,R("kevlar_process_local_innertube_responses_killswitch")||zv(a,p,b),X.return(p);case 11:return(u=null==(r=b.config)?void 0:r.gg)&&a.h.has(u)&&R("web_memoize_inflight_requests")?t=a.h.get(u):(y=JSON.stringify(b.Pa),L=null!=(H=null==(z=b.ib)?void 0:z.headers)?H:{},b.ib=Object.assign({},b.ib,{headers:Object.assign({},L,c)}),I=Object.assign({},b.ib),"POST"===b.ib.method&&(I=Object.assign({},I,{body:y})),(null==(da=b.config)?0:da.Ge)&&ov(b.config.Ge),T=function(){return a.ba.fetch(b.input,
I,b.config)},t=T(),u&&a.h.set(u,t)),X.yield(t,13);
case 13:if((N=X.i)&&"error"in N&&(null==(ba=N)?0:null==(J=ba.error)?0:J.details))for(ca=N.error.details,ha=w(ca),V=ha.next();!V.done;V=ha.next())ab=V.value,(Nc=ab["@type"])&&-1<sv.indexOf(Nc)&&(delete ab["@type"],N=ab);u&&a.h.has(u)&&a.h.delete(u);(null==(Oc=b.config)?0:Oc.He)&&ov(b.config.He);if(N||null==(Pc=a.i)||!Pc.Of(b.input,b.Pa)){X.A(14);break}return X.yield(a.i.Wf(b.input,b.Pa),15);case 15:N=X.i;case 14:return zv(a,N,b),X.return(N||void 0)}})}
function xv(a,b){var c,d,e,f;return A(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Vb)?void 0:d.sessionIndex;var h=g.yield;var k=im(0,{sessionIndex:e});if(!(k instanceof Ud)){var l=new Ud(cb);Vd(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},wv(b),f)))})}
function wv(a){var b={"Content-Type":"application/json"};P("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=P("EOM_VISITOR_DATA"):P("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=P("VISITOR_DATA"));R("enable_eom_webview_header")&&P("WEBVIEW_EOM",!1)&&(b["X-Yt-Webview-Eom"]="1");b["X-Youtube-Bootstrap-Logged-In"]=P("LOGGED_IN",!1);P("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=P("DEBUG_SETTINGS_METADATA"));"cors"!==a&&((a=P("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=
P("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=P("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=P("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var Av=new Dr("INNERTUBE_TRANSPORT_TOKEN");var Bv=["share/get_web_player_share_panel"],Cv=["feedback"],Dv=["notification/modify_channel_preference"],Ev=["browse/edit_playlist"],Fv=["subscription/subscribe"],Gv=["subscription/unsubscribe"];function Hv(){}
x(Hv,cu);Hv.prototype.j=function(){return Fv};
Hv.prototype.h=function(a){return gs(a,Yk)||void 0};
Hv.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ia.Object.defineProperties(Hv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Iv(){}
x(Iv,cu);Iv.prototype.j=function(){return Gv};
Iv.prototype.h=function(a){return gs(a,Xk)||void 0};
Iv.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ia.Object.defineProperties(Iv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Jv(){}
x(Jv,cu);Jv.prototype.j=function(){return Cv};
Jv.prototype.h=function(a){return gs(a,Sk)||void 0};
Jv.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ia.Object.defineProperties(Jv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Kv(){}
x(Kv,cu);Kv.prototype.j=function(){return Dv};
Kv.prototype.h=function(a){return gs(a,Wk)||void 0};
Kv.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function Lv(){}
x(Lv,cu);Lv.prototype.j=function(){return Ev};
Lv.prototype.h=function(a){return gs(a,Vk)||void 0};
Lv.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Mv(){}
x(Mv,cu);Mv.prototype.j=function(){return Bv};
Mv.prototype.h=function(a){return gs(a,Uk)};
Mv.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Nv=new Dr("NETWORK_SLI_TOKEN");function Ov(a){this.h=a}
Ov.prototype.fetch=function(a,b,c){var d=this,e,f,g;return A(function(h){d.h&&(e=bc(cc(5,rc(a,"key")))||"/UNKNOWN_PATH",d.h.start(e));f=b;R("wug_networking_gzip_request")&&(f=Yp(b));g=new window.Request(a,f);return h.return(fetch(g).then(function(k){return d.handleResponse(k,c)}).catch(function(k){Zs(k)}))})};
Ov.prototype.handleResponse=function(a,b){var c=a.text().then(function(d){return(null==b?0:b.qe)&&a.ok?vg(b.qe,d):JSON.parse(d.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Rf(),c=c.then(function(d){Zs(new S("Error: API fetch failed",a.status,a.url,d));return Object.assign({},d,{errorMetadata:{status:a.status}})}));
return c};
Ov[Cr]=[new Er(Nv)];var Pv=new Dr("NETWORK_MANAGER_TOKEN");var Qv;function Rv(){var a,b,c;return A(function(d){if(1==d.h)return a=Jr().resolve(Av),a?d.yield(vv(a),2):(Zs(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return Zs(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Pf;return d.return(c)}Zs(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var Sv=B.caches,Tv;function Uv(a){var b=a.indexOf(":");return-1===b?{qd:a}:{qd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Vv(){return A(function(a){if(void 0!==Tv)return a.return(Tv);Tv=new Promise(function(b){var c;return A(function(d){switch(d.h){case 1:return za(d,2),d.yield(Sv.open("test-only"),4);case 4:return d.yield(Sv.delete("test-only"),5);case 5:d.h=3;d.l=0;break;case 2:if(c=Aa(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Tv)})}
function Wv(a){var b,c,d,e,f,g,h;A(function(k){if(1==k.h)return k.yield(Vv(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return k.yield(Sv.keys(),3)}c=k.i;d=w(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Uv(f),h=g.datasyncId,!h||a.includes(h)||b.push(Sv.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(n){return n})}))})}
function Xv(){var a,b,c,d,e,f,g;return A(function(h){if(1==h.h)return h.yield(Vv(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=Fm("cache contains other");return h.yield(Sv.keys(),3)}b=h.i;c=w(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Uv(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Yv(){Rv().then(function(a){a&&(No(a),Wv(a),mu(a))})}
function Zv(){var a=new Qq;Ji.oa(function(){var b,c,d,e;return A(function(f){switch(f.h){case 1:if(R("ytidb_clear_optimizations_killswitch")){f.A(2);break}b=Fm("clear");if(b.startsWith("V")&&b.endsWith("||")){var g=[b];No(g);Wv(g);mu(g);return f.return()}c=nu();return f.yield(Xv(),3);case 3:return d=f.i,f.yield(Oo(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.wa()?Yv():a.h.add("publicytnetworkstatus-online",Yv,!0,void 0,void 0),f.h=0}})})}
;var ni=ka(["data-"]);function $v(a){a&&(a.dataset?a.dataset[aw()]="true":mi(a))}
function bw(a){return a?a.dataset?a.dataset[aw()]:a.getAttribute("data-loaded"):null}
var cw={};function aw(){return cw.loaded||(cw.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;var dw=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,ew=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function fw(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(dw,""),c=c.replace(ew,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else gw(a,b,c)}
function gw(a,b,c){c=void 0===c?null:c;var d=hw(a),e=document.getElementById(d),f=e&&bw(e),g=e&&!f;f?b&&b():(b&&(f=wr(d,b),b=""+Qa(b),iw[b]=f),g||(e=jw(a,d,function(){if(!bw(e)){$v(e);zr(d);var h=Wa(Ar,d);Fl(h,0)}},c)))}
function jw(a,b,c,d){d=void 0===d?null:d;var e=Gd("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);si(e,Jk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function kw(a){a=hw(a);var b=document.getElementById(a);b&&(Ar(a),b.parentNode.removeChild(b))}
function lw(a,b){a&&b&&(a=""+Qa(b),(a=iw[a])&&yr(a))}
function hw(a){var b=document.createElement("a");ii(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+$b(a)}
var iw={};var mw=[],nw=!1;function ow(){if(!R("disable_biscotti_fetch_for_ad_blocker_detection")&&!R("disable_biscotti_fetch_entirely_for_all_web_clients")&&Et()){var a=P("PLAYER_VARS",{});if("1"!=rb(a)&&!Ft(a)){var b=function(){nw=!0;"google_ad_status"in window?gl("DCLKSTAT",1):gl("DCLKSTAT",2)};
try{fw("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}mw.push(Ji.oa(function(){if(!(nw||"google_ad_status"in window)){try{lw("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}nw=!0;gl("DCLKSTAT",3)}},5E3))}}}
function pw(){var a=Number(P("DCLKSTAT",0));return isNaN(a)?0:a}
;function qw(a){Sr.call(this,void 0===a?"document_active":a);var b=this;this.l=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.B},{from:"document_active",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"flush_logs",action:this.H},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.H},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
x(qw,Sr);qw.prototype.B=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
qw.prototype.m=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
qw.prototype.H=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
qw.prototype.i=function(){this.h=new Map};function rw(a){Sr.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.H},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.m},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.H},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.H},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.m},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.m},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
R("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
x(rw,Sr);rw.prototype.i=function(a,b){a(null==b?void 0:b.event);R("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
rw.prototype.h=function(a,b){a(null==b?void 0:b.event);R("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
rw.prototype.m=function(a,b){a(null==b?void 0:b.event)};
rw.prototype.H=function(a,b){a(null==b?void 0:b.event)};function sw(){this.l=new qw;this.m=new rw}
sw.prototype.install=function(){var a=Ia.apply(0,arguments),b=this;a.forEach(function(c){b.l.install(c)});
a.forEach(function(c){b.m.install(c)})};function tw(a){qp.call(this,1,arguments);this.csn=a}
x(tw,qp);var zp=new rp("screen-created",tw),uw=[],vw=0,ww=new Map,xw=new Map,yw=new Map;
function zw(a,b,c,d,e){e=void 0===e?!1:e;for(var f=Aw({cttAuthInfo:st(b)||void 0},b),g=w(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(pb(k)||!k.trackingParams&&!k.veType)&&Zs(Error("Child VE logged with no data"));if(R("no_client_ve_attach_unless_shown")){var l=Bw(h,b);if(k.veType&&!xw.has(l)&&!yw.has(l)&&!e){ww.set(l,[a,b,c,h]);return}h=Bw(c,b);ww.has(h)?Cw(c,b):yw.set(h,!0)}}d=d.filter(function(n){n.csn!==b?(n.csn=b,n=!0):n=!1;return n});
c={csn:b,parentVe:c.getAsJson(),childVes:hb(d,function(n){return n.getAsJson()})};
"UNDEFINED_CSN"===b?Dw("visualElementAttached",f,c):a?Rs("visualElementAttached",c,a,f):yn("visualElementAttached",c,f)}
function Dw(a,b,c){uw.push({Ae:a,payload:c,Vf:void 0,options:b});vw||(vw=Ap())}
function Bp(a){if(uw){for(var b=w(uw),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,yn(c.Ae,c.payload,c.options));uw.length=0}vw=0}
function Bw(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Cw(a,b){a=Bw(a,b);ww.has(a)&&(b=ww.get(a)||[],zw(b[0],b[1],b[2],[b[3]],!0),ww.delete(a))}
function Aw(a,b){R("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Ew(){this.l=[];this.i=new Map;this.h=new Map;this.j=new Set}
Ew.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=qt(void 0===c?0:c)){a=this.client;d=new jt({trackingParams:d});var e=void 0;if(R("no_client_ve_attach_unless_shown")){var f=Bw(d,c);xw.set(f,!0);Cw(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Aw({cttAuthInfo:st(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);"UNDEFINED_CSN"===c?Dw("visualElementGestured",f,d):a?Rs("visualElementGestured",d,a,f):yn("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
Ew.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new jt({trackingParams:a}),b,void 0===c?0:c)};
Ew.prototype.visualElementStateChanged=function(a,b,c){c=void 0===c?0:c;if(0===c&&this.j.has(c))this.l.push([a,b]);else{var d=c;d=void 0===d?0:d;c=qt(d);a||(a=(a=nt(void 0===d?0:d))?new jt({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Aw({cttAuthInfo:st(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},"UNDEFINED_CSN"===c?Dw("visualElementStateChanged",d,b):a?Rs("visualElementStateChanged",b,a,d):yn("visualElementStateChanged",b,d))}};
function Fw(a,b){if(void 0===b)for(var c=pt(),d=0;d<c.length;d++)void 0!==c[d]&&Fw(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&zw(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function Gw(){sw.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));R("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a))}
x(Gw,sw);Gw.prototype.j=function(){yn("finalPayload",{csn:qt()})};
Gw.prototype.h=function(){ct(dt)};
Gw.prototype.i=function(){var a=Fw;Ew.h||(Ew.h=new Ew);a(Ew.h)};function Hw(){}
function Iw(){var a=D("ytglobal.storage_");a||(a=new Hw,C("ytglobal.storage_",a));return a}
Hw.prototype.estimate=function(){var a,b,c;return A(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(Jw()):d.return()})};
function Jw(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
C("ytglobal.storageClass_",Hw);function wn(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=Al("ytidb_transaction_ended_event_rate_limit_session",.2)}
wn.prototype.Nb=function(a){this.handleError(a)};
wn.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":R("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":R("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Kw(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=Al("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function Kw(a,b){Iw().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Lw(null==c?void 0:c.usage),deviceStorageQuotaMbytes:Lw(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Lw(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function Mw(a,b,c){F.call(this);var d=this;c=c||P("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.i=b||null;this.targetOrigin="*";this.j=c;this.sessionId=null;this.channel="widget";this.B=!!a;this.u=function(e){a:if(!("*"!=d.j&&e.origin!=d.j||d.i&&e.source!=d.i||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.B&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.j=d.targetOrigin=e.origin);d.i=e.source;d.sessionId=f.id;d.h&&(d.h(),d.h=null);break;case "command":d.l&&(!d.m||0<=eb(d.m,f.func))&&d.l(f.func,f.args,e.origin)}}};
this.m=this.h=this.l=null;window.addEventListener("message",this.u)}
x(Mw,F);Mw.prototype.sendMessage=function(a,b){if(b=b||this.i){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){ml(d)}}};
Mw.prototype.S=function(){window.removeEventListener("message",this.u);F.prototype.S.call(this)};function Nw(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new Mw(!!P("WIDGET_ID_ENFORCE")),b=this.De.bind(this);a.l=b;a.m=null;this.h.channel="widget";if(a=P("WIDGET_ID"))this.h.sessionId=a}
m=Nw.prototype;m.De=function(a,b,c){"addEventListener"===a&&b?this.Ec(b[0],c):this.Uc(a,b,c)};
m.Uc=function(){};
m.yc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
m.Ec=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.yc(a,b)),this.j[a]=!0)};
m.addEventListener=function(){};
m.ae=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Bc());this.sendMessage("onReady");fb(this.i,this.xd,this);this.i=[]};
m.Bc=function(){return null};
function Ow(a,b){a.sendMessage("infoDelivery",b)}
m.xd=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.xd({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};var Pw={},Qw=(Pw["api.invalidparam"]=2,Pw.auth=150,Pw["drm.auth"]=150,Pw["heartbeat.net"]=150,Pw["heartbeat.servererror"]=150,Pw["heartbeat.stop"]=150,Pw["html5.unsupportedads"]=5,Pw["fmt.noneavailable"]=5,Pw["fmt.decode"]=5,Pw["fmt.unplayable"]=5,Pw["html5.missingapi"]=5,Pw["html5.unsupportedlive"]=5,Pw["drm.unavailable"]=5,Pw["mrm.blocked"]=151,Pw);var Rw=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function Sw(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Tw(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=w(Rw);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Uw(a,b,c,d){if(Pa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Vw(a){Nw.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Pe.bind(this));this.addEventListener("onVolumeChange",this.Qe.bind(this));this.addEventListener("onApiChange",this.Ke.bind(this));this.addEventListener("onPlaybackQualityChange",this.Me.bind(this));this.addEventListener("onPlaybackRateChange",this.Ne.bind(this));this.addEventListener("onStateChange",this.Oe.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Re.bind(this))}
x(Vw,Nw);m=Vw.prototype;
m.Uc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Sw(a)){var d=b;if(Pa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Tw(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Tw(e);break;case "loadPlaylist":case "cuePlaylist":e=Uw(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Sw(a)&&Ow(this,this.Bc())}};
m.Ec=function(a,b){"onReady"===a?this.api.logApiCall(a+" invocation",b):"onError"===a&&this.l&&(this.api.logApiCall(a+" invocation",b,this.errorCode),this.errorCode=void 0);this.api.logApiCall(a+" registration",b);Nw.prototype.Ec.call(this,a,b)};
m.yc=function(a,b){var c=this,d=Nw.prototype.yc.call(this,a,b);return function(e){"onError"===a?c.api.logApiCall(a+" invocation",b,e):c.api.logApiCall(a+" invocation",b);d(e)}};
m.onReady=function(){var a=this.ae.bind(this);this.h.h=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.errorCode=a?Qw[a]||b:b;this.sendMessage("onError",this.errorCode.toString())}};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Bc=function(){if(!this.api)return null;var a=this.api.getApiInterface();kb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Oe=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Ow(this,a)};
m.Me=function(a){Ow(this,{playbackQuality:a})};
m.Ne=function(a){Ow(this,{playbackRate:a})};
m.Ke=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Qe=function(){Ow(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Pe=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Ow(this,a)};
m.Re=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Ow(this,a)};
m.dispose=function(){Nw.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Ww(a){F.call(this);this.h={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.td,this)}
x(Ww,F);m=Ww.prototype;m.start=function(){this.started||this.aa()||(this.started=!0,this.connection.jb("RECEIVING"))};
m.jb=function(a,b){this.started&&!this.aa()&&this.connection.jb(a,b)};
m.td=function(a,b,c){if(this.started&&!this.aa()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Xw(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Yw(a,c))&&this.jb(a,c))}}};
m.addListener=function(a){if(!(a in this.h)){var b=this.Le.bind(this,a);this.h[a]=b;this.addEventListener(a,b)}};
m.Le=function(a,b){this.started&&!this.aa()&&this.connection.jb(a,this.Ac(a,b))};
m.Ac=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.h&&(this.removeEventListener(a,this.h[a]),delete this.h[a])};
m.S=function(){this.connection.unsubscribe("command",this.td,this);this.connection=null;for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);F.prototype.S.call(this)};function Zw(a,b){Ww.call(this,b);this.api=a;this.start()}
x(Zw,Ww);Zw.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Zw.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Xw(a,b){switch(a){case "loadVideoById":return a=Tw(b),[a];case "cueVideoById":return a=Tw(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Uw(b),[a];case "cuePlaylist":return a=Uw(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Yw(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Zw.prototype.Ac=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Ww.prototype.Ac.call(this,a,b)};
Zw.prototype.S=function(){Ww.prototype.S.call(this);delete this.api};function $w(a){a=void 0===a?!1:a;F.call(this);this.h=new K(a);yc(this,this.h)}
Ya($w,F);$w.prototype.subscribe=function(a,b,c){return this.aa()?0:this.h.subscribe(a,b,c)};
$w.prototype.unsubscribe=function(a,b,c){return this.aa()?!1:this.h.unsubscribe(a,b,c)};
$w.prototype.l=function(a,b){this.aa()||this.h.Za.apply(this.h,arguments)};function ax(a,b,c){$w.call(this);this.j=a;this.i=b;this.id=c}
x(ax,$w);ax.prototype.jb=function(a,b){this.aa()||this.j.jb(this.i,this.id,a,b)};
ax.prototype.S=function(){this.i=this.j=null;$w.prototype.S.call(this)};function bx(a,b,c){F.call(this);this.h=a;this.origin=c;this.i=kr(window,"message",this.j.bind(this));this.connection=new ax(this,a,b);yc(this,this.connection)}
x(bx,F);bx.prototype.jb=function(a,b,c,d){this.aa()||a!==this.h||(a={id:b,command:c},d&&(a.data=d),this.h.postMessage(JSON.stringify(a),this.origin))};
bx.prototype.j=function(a){if(!this.aa()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.aa()||c.l("command",b.command,b.data,a.origin)}}}};
bx.prototype.S=function(){lr(this.i);this.h=null;F.prototype.S.call(this)};function cx(){this.state=1;this.h=null}
m=cx.prototype;m.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){var f=a.interpreterSafeScript;f?((f=f.privateDoNotAccessOrElseSafeScriptWrappedValue)?(f=(d=yb())?d.createScript(f):f,f=new Db(f,Cb)):f=null,d=f):d=null}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=Ik(a.interpreterSafeUrl).toString());dx(this,d,e,a.program,b,c)}else Zs(Error("Cannot initialize botguard without program"))};
function dx(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,fw(c,function(){window[g]?ex(a,d,g,e):(a.state=3,kw(c),Zs(new S("Unable to load Botguard","from "+c)))},f)):b?(f=Gd("SCRIPT"),b instanceof Db?(b instanceof Db&&b.constructor===Db?b=b.h:(Na(b),b="type_error:SafeScript"),f.textContent=b,ri(f)):f.textContent=b,f.nonce=Yb(),document.head.appendChild(f),document.head.removeChild(f),window[g]?ex(a,d,g,e):(a.state=4,Zs(new S("Unable to load Botguard from JS")))):Zs(new S("Unable to load VM; no url or JS provided"))}
m.isLoading=function(){return 2===this.state};
function ex(a,b,c,d){a.state=5;try{var e=new Xh({program:b,ee:c,Ee:R("att_web_record_metrics")});e.Ue.then(function(){a.state=6;d&&d(b)});
a.Pc(e)}catch(f){a.state=7,f instanceof Error&&Zs(f)}}
m.invoke=function(a){a=void 0===a?{}:a;return this.Sc()?this.Gd({cd:a}):null};
m.dispose=function(){this.Pc(null);this.state=8};
m.Sc=function(){return!!this.h};
m.Gd=function(a){return this.h.Ad(a)};
m.Pc=function(a){wc(this.h);this.h=a};function fx(){var a=D("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function gx(){cx.apply(this,arguments)}
x(gx,cx);gx.prototype.Pc=function(a){var b;null==(b=fx())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Ad.bind(a)},C("yt.abuse.playerAttLoader",b),C("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(C("yt.abuse.playerAttLoader",null),C("yt.abuse.playerAttLoaderRun",null))};
gx.prototype.Sc=function(){return!!fx()};
gx.prototype.Gd=function(a){return fx().bgvmc(a)};var hx=new gx;function ix(){return hx.Sc()}
function jx(a){a=void 0===a?{}:a;return hx.invoke(a)}
;function kx(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||tb(b);this.assets=a.assets||{};this.attrs=a.attrs||tb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
kx.prototype.clone=function(){var a=new kx,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Na(c)?a[b]=tb(c):a[b]=c}return a};var lx=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function mx(a){a=a||"";if(window.spf){var b=a.match(lx);spf.style.load(a,b?b[1]:"",void 0)}else nx(a)}
function nx(a){var b=ox(a),c=document.getElementById(b),d=c&&bw(c);d||c&&!d||(c=px(a,b,function(){if(!bw(c)){$v(c);zr(b);var e=Wa(Ar,b);Fl(e,0)}}))}
function px(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Jk(a);qi(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function ox(a){var b=Gd("A");ii(b,new Jb(a,Kb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+$b(a)}
;function qx(a,b,c,d,e){F.call(this);var f=this;this.B=b;this.webPlayerContextConfig=d;this.sc=e;this.Ba=!1;this.api={};this.fa=this.u=null;this.T=new K;this.h={};this.Z=this.ha=this.elementId=this.Ka=this.config=null;this.X=!1;this.j=this.l=null;this.na={};this.uc=["onReady"];this.lastError=null;this.nb=NaN;this.K={};this.ea=0;this.i=this.m=a;yc(this,this.T);rx(this);c?this.ea=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(sx(this),tx(this))}
x(qx,F);m=qx.prototype;m.getId=function(){return this.B};
m.loadNewVideoConfig=function(a){if(!this.aa()){this.ea&&(clearTimeout(this.ea),this.ea=0);var b=a||{};b instanceof kx||(b=new kx(b));this.config=b;this.setConfig(a);tx(this);this.isReady()&&ux(this)}};
function sx(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.B,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.B:a.config.attrs.id=a.B);var c;(null==(c=a.i)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){this.Ka=a;this.config=vx(a);sx(this);if(!this.ha){var b;this.ha=wx(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=zi(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=zi(Number(a)||a))};
function ux(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function xx(a){var b=!0,c=yx(a);c&&a.config&&(b=c.dataset.version===zx(a));return b&&!!D("yt.player.Application.create")}
function tx(a){if(!a.aa()&&!a.X){var b=xx(a);if(b&&"html5"===(yx(a)?"html5":null))a.Z="html5",a.isReady()||Ax(a);else if(Bx(a),a.Z="html5",b&&a.j&&a.m)a.m.appendChild(a.j),Ax(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.l=function(){c=!0;var d=Cx(a,"player_bootstrap_method")?D("yt.player.Application.createAlternate")||D("yt.player.Application.create"):D("yt.player.Application.create");var e=a.config?vx(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.sc);Ax(a)};
a.X=!0;b?a.l():(b=zx(a),Cx(a,"web_player_proxy_new_scriptloader")?Dx(b,a.l):fw(zx(a),a.l),(b=Ex(a))&&(Cx(a,"web_player_proxy_new_styleloader")?Fx(b):mx(b)),Gx(a)&&!c&&C("yt.player.Application.create",null))}}}
function yx(a){var b=Fd(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function Ax(a){if(!a.aa()){var b=yx(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.X=!1;if(!Cx(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Hx(a)}else a.nb=setTimeout(function(){Ax(a)},50)}}
function Hx(a){rx(a);a.Ba=!0;var b=yx(a);if(b){a.u=Ix(a,b,"addEventListener");a.fa=Ix(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Ix(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.u&&a.u(g,a.h[g]);ux(a);a.ha&&a.ha(a.api);a.T.Za("onReady",a.api)}
function Ix(a,b,c){var d=b[c];return function(){var e=Ia.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if("sendAbandonmentPing"!==c)throw f.params=c,a.lastError=f,e=new S("PlayerProxy error in method call",{error:f,method:c,playerId:a.B}),e.level="WARNING",e;}}}
function rx(a){a.Ba=!1;if(a.fa)for(var b in a.h)a.h.hasOwnProperty(b)&&a.fa(b,a.h[b]);for(var c in a.K)a.K.hasOwnProperty(c)&&clearTimeout(Number(c));a.K={};a.u=null;a.fa=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ka};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ba};
m.addEventListener=function(a,b){var c=this,d=wx(this,b);d&&(0<=eb(this.uc,a)||this.h[a]||(b=Jx(this,a),this.u&&this.u(a,b)),this.T.subscribe(a,d),"onReady"===a&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.aa()||(b=wx(this,b))&&this.T.unsubscribe(a,b)};
function wx(a,b){var c=b;if("string"===typeof b){if(a.na[b])return a.na[b];c=function(){var d=Ia.apply(0,arguments),e=D(b);if(e)try{e.apply(B,d)}catch(f){throw d=new S("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.na[b]=c}return c?c:null}
function Jx(a,b){function c(d){var e=setTimeout(function(){if(!a.aa()){try{a.T.Za(b,null!=d?d:void 0)}catch(h){var f=new S("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.B,data:d});f.level="WARNING";throw f;}f=a.K;var g=String(e);g in f&&delete f[g]}},0);
qb(a.K,String(e))}
return a.h[b]=c}
m.getPlayerType=function(){return this.Z||(yx(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function Bx(a){a.cancel();rx(a);a.Z=null;a.config&&(a.config.loaded=!1);var b=yx(a);b&&(xx(a)||!Gx(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){if(this.l)if(Cx(this,"web_player_proxy_new_scriptloader")){var a=zx(this),b=this.l;a&&b&&(a=document.getElementById("ytp-"+a))&&a.removeEventListener("load",b)}else lw(zx(this),this.l);clearTimeout(this.nb);this.X=!1};
m.S=function(){Bx(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new S("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.na=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Ka=this.config=this.api=null;delete this.m;delete this.i;F.prototype.S.call(this)};
function Gx(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function zx(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Ex(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Cx(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function vx(a){for(var b={},c=w(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?tb(e):e}return b}
function Fx(a){var b="ytp-"+a;if(!document.getElementById(b)){var c=document.createElement("link");c.id=b;a=Jk(a);qi(c,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(c)}}
function Dx(a,b){var c="ytp-"+a,d=document.getElementById(c);if(d)d.dataset.loaded?b():d.addEventListener("load",function(){b()});
else{var e=document.createElement("script");e.id=c;e.addEventListener("load",function(){e.dataset.loaded="true";b()});
a=Jk(a);si(e,a);a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild)}}
;var Kx={},Lx="player_uid_"+(1E9*Math.random()>>>0);function Mx(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?Fd(c):c;var e=Lx+"_"+Qa(c),f=Kx[e];if(f&&d)return Nx(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new qx(c,e,a,b,void 0);Kx[e]=f;f.addOnDisposeCallback(function(){delete Kx[f.getId()]});
return f.api}
function Nx(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Ox=null,Px=null,Qx=null;
function Rx(){pv();var a=tm(),b=xm(119),c=1<window.devicePixelRatio;if(document.body&&Ti(document.body,"exp-invert-logo"))if(c&&!Ti(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Ti(d,"inverted-hdpi")){var e=Ri(d);Si(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Ti(document.body,"inverted-hdpi")&&Ui();if(b!=c){b="f"+(Math.floor(119/31)+1);d=ym(b)||0;d=c?d|67108864:d&-67108865;0===d?delete qm[b]:(c=d.toString(16),qm[b]=c.toString());
c=!0;R("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in qm)qm.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(qm[f])));var f=d.join("&");mm(b,f,63072E3,a.i,c)}}
function Sx(){Tx()}
function Ux(){ov("ep_init_pr");Tx()}
function Tx(){var a=Ox.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function Vx(){Ox&&Ox.sendAbandonmentPing&&Ox.sendAbandonmentPing();P("PL_ATT")&&hx.dispose();for(var a=Ji,b=0,c=mw.length;b<c;b++)a.qa(mw[b]);mw.length=0;kw("//static.doubleclick.net/instream/ad_status.js");nw=!1;gl("DCLKSTAT",0);xc(Qx,Px);Ox&&(Ox.removeEventListener("onVideoDataChange",Sx),Ox.destroy())}
;function Wx(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=P("EVENT_ID");d&&(b.ei||(b.ei=d));b&&hu(a,b);if(c)return!1;pu(a);if((window.ytspf||{}).enabled)spf.navigate(a);else{var e=void 0===e?{}:e;var f=void 0===f?"":f;var g=void 0===g?window:g;a=mc(a,e);pu(a);f=a+f;var h=void 0===h?fi:h;a:if(h=void 0===h?fi:h,f instanceof Jb)h=f;else{for(a=0;a<h.length;++a)if(b=h[a],b instanceof di&&b.pe(f)){h=new Jb(f,Kb);break a}h=void 0}g=g.location;h=hi(h||Lb);void 0!==h&&(g.href=h)}return!0}
;C("yt.setConfig",gl);C("yt.config.set",gl);C("yt.setMsg",ut);C("yt.msgs.set",ut);C("yt.logging.errors.log",Ys);
C("writeEmbed",function(){var a=P("PLAYER_CONFIG");if(!a){var b=P("PLAYER_VARS");b&&(a={args:b})}Ot(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=P("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);kv("embed",["ol"]);c=P("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=ul(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;(null==(e=a.args)?0:e.autoplay)&&kv("watch",["pbs","pbu","pbp"]);Ox=Mx(a,c);Ox.addEventListener("onVideoDataChange",Sx);Ox.addEventListener("onReady",Ux);a=P("POST_MESSAGE_ID","player");P("ENABLE_JS_API")?Qx=new Vw(Ox):P("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Px=new bx(window.parent,a,b),Qx=new Zw(Ox,Px.connection));ow();R("ytidb_create_logger_embed_killswitch")||vn();a={};Gw.h||(Gw.h=new Gw);
Gw.h.install((a.flush_logs={callback:function(){Es()}},a));
ar();R("ytidb_clear_embedded_player")&&Ji.oa(function(){var f,g;if(!Qv){var h=Jr(),k={Mc:Pv,Ed:Ov};h.h.set(k.Mc,k);k={bd:{feedbackEndpoint:Zt(Jv),modifyChannelNotificationPreferenceEndpoint:Zt(Kv),playlistEditEndpoint:Zt(Lv),subscribeEndpoint:Zt(Hv),unsubscribeEndpoint:Zt(Iv),webPlayerShareEntityServiceEndpoint:Zt(Mv)}};var l=Xt(),n={};l&&(n.client_location=l);void 0===f&&(f=hm());void 0===g&&(g=h.resolve(Pv));uv(k,g,f,n);f={Mc:Av,Fd:tv.h};h.h.set(f.Mc,f);Qv=h.resolve(Av)}Zv()})});
C("yt.abuse.player.botguardInitialized",D("yt.abuse.player.botguardInitialized")||ix);C("yt.abuse.player.invokeBotguard",D("yt.abuse.player.invokeBotguard")||jx);C("yt.abuse.dclkstatus.checkDclkStatus",D("yt.abuse.dclkstatus.checkDclkStatus")||pw);C("yt.player.exports.navigate",D("yt.player.exports.navigate")||Wx);C("yt.util.activity.init",D("yt.util.activity.init")||or);C("yt.util.activity.getTimeSinceActive",D("yt.util.activity.getTimeSinceActive")||rr);
C("yt.util.activity.setTimestamp",D("yt.util.activity.setTimestamp")||pr);window.addEventListener("load",kl(function(){Rx()}));
window.addEventListener("pageshow",kl(function(a){a.persisted||Rx()}));
window.addEventListener("pagehide",kl(function(a){R("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Vx():a.persisted||Vx()}));
window.onerror=function(a,b,c,d,e){b=void 0===b?"Unknown file":b;c=void 0===c?0:c;var f=!1,g=hl("log_window_onerror_fraction");if(g&&Math.random()<g)f=!0;else{g=document.getElementsByTagName("script");for(var h=0,k=g.length;h<k;h++)if(0<g[h].src.indexOf("/debug-")){f=!0;break}}f&&(f=!1,e?f=!0:("string"===typeof a?g=a:ErrorEvent&&a instanceof ErrorEvent?(f=!0,g=a.message,b=a.filename,c=a.lineno,d=a.colno):(g="Unknown error",b="Unknown file",c=0),e=new S(g),e.name="UnhandledWindowError",e.message=g,
e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d),f?Ys(e):Zs(e))};
je=$s;window.addEventListener("unhandledrejection",function(a){$s(a.reason)});
fb(P("ERRORS")||[],function(a){Ys.apply(null,a)});
gl("ERRORS",[]);R("embeds_web_enable_scheduler_to_player_binary")&&mn();}).call(this);
