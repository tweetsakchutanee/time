# time
time.html
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="th" lang="th">
 <head>
  <title>Time.is 22:31</title> 
  <script data-cfasync="false">
var freestar=freestar||{};freestar.hitTime=Date.now();freestar.queue=freestar.queue||[];freestar.config=freestar.config||{};freestar.debug=window.location.search.indexOf("fsdebug")===-1?false:true;freestar.config.enabled_slots=[];!function(a,b){var c=b.getElementsByTagName("script")[0],d=b.createElement("script"),e="https://a.pub.network/timeis";e+=freestar.debug?"/qa/pubfig.min.js":"/pubfig.min.js",d.async=!0,d.src=e,c.parentNode.insertBefore(d,c)}(window,document);freestar.initCallback=function(){(freestar.config.enabled_slots.length===0)?freestar.initCallbackCalled=false:freestar.newAdSlots(freestar.config.enabled_slots)}
</script> 
  <!--[if lt IE 9]>
<script>
document.createElement('nav');
document.createElement('section');
document.createElement('article');
document.createElement('footer');
document.createElement('quote');
document.createElement('cite');
document.createElement('time');
</script>
<![endif]--> 
  <script>
var updint=1000,U="undefined",N=null,E=true,F=!E,O="object",S="string",D=document,A=0,fc={a:0},bfc=1,uT="Time.is ",sT,tD,pY=lY=297,cY=syncn=rsy=0,ztrans=0,newzo=0,ss={"0916":"&uarr; 06:08 &darr; 18:17 (12ชม 9นาที)","0917":"&uarr; 06:08 &darr; 18:17 (12ชม 9นาที)"},destT=0,yrp="",csup=1,czo=0,rqT=0,syncT=0,syncquota=10,earliest_syncT=0,xR=1,syncm='',syncdt='',adH=110,mZ=64,ltr=1,ticks=0,Tstate={chosen_loc:0,current_page:"specific_location"};
function _tD(M){sT=M;tD=new Date().getTime()-M-Math.round(lY/2);cY=lY-pY;if(cY<10)cY=10}
_tD(1631806298828)
function gob(e){if(typeof e==O)return e;if(D.getElementById)return D.getElementById(e);return eval(e)}
function bluritem(e){e=gob(e);e.className=e.className.replace('focused','blr');bfc=1}
function focusitem(e){bfc=0;e=gob(e);e.className=e.className.replace('blr','focused');e.className=e.className.replace('submitted','focused')}
function mouseover(e){e.className=e.className.replace('mout','hovered')}
function mouseout(e){e.className=e.className.replace('hovered','mout')}
function setfocus(g){if(typeof fc[g]==U)fc[g]=1;else fc[g]++
if(fc['a']!=0&&fc['a']!=g)losefocus(fc['a'])
fc['a']=g;gob(g).className=gob(g).className.replace('hide','show');bfc=0}
function losefocus(g){if(fc['a']!=g)fc[g]=0;else{fc[g]--;if(fc[g]<1){fc['a']=0;fc[g]=0;gob(g).className=gob(g).className.replace('show','hide');bfc=1}}}
function changeclass(i,x,y){var o=gob(i);if(o)o.className=(o.className.replace(x,'')+' '+y).replace(/  +/,' ')}

dmode=0
function setcookie(n,v){var x=new Date();x.setDate(x.getDate()+365);D.cookie=n+'='+encodeURIComponent(v)+'; expires='+x.toGMTString()+'; path=/'
if(D.cookie.length<1)csup=0}
function httpSync(){
nextSyncT=0
array_name='main'
xR=N
gob('syncH').innerHTML=p_syncing;gob('syncDtl').innerHTML='&nbsp;';gob('msgs').className=gob('msgs').className.replace('hdn','vsbl')
if(window.XMLHttpRequest)xR=new XMLHttpRequest()
else if(window.ActiveXObject)xR=new ActiveXObject("Microsoft.XMLHTTP")
if(xR!=N){
rqT=new Date()
czo=-rqT.getTimezoneOffset()
xR.onreadystatechange=s_C
xR.open('get','/t/?'+l+'.'+syncn+'.'+lY+'.'+tD+'.'+rsy+'p.'+czo+'.'+locs[array_name][conf['h']][1]+'.'+rqT.getTime()+'.'+sT+'.'+yrp,E)
xR.send(N)
yrp=''
}else xR='N/A'
}
var Y=['','']
function s_C(){
var o,dots='...',sym=Y[0],syd=Y[1]
if(xR.readyState==4){
if(xR.status==200){
var rpT=new Date(),n=rpT-rqT,r=xR.responseText.split("\n")
sT=r[1]
var prevST=syncT
syncT=new Date()
syncT.setTime(syncT.getTime()-tD)
if(syncn===0||rsy||n<lY){if(r[0].length==13)r.unshift('ok');if(r.length<7||r[0]!=='ok'){
if(r[0].substr(0,6)=='error:')p_failm=r[0].substr(6)
else gob('msgs').className='w90 pulldowncv nonet'
hideTO=setTimeout('sync_cleanup(0)',4000)
}else{p_failm=p_fail
if(rsy&&(syncT-prevST<60000)){syncquota--
if(syncquota<0)earliest_syncT=new Date(syncT.getTime()+120000)
}else if(earliest_syncT==0)syncquota=10
}
rsy=0
lY=n
_tD(r[1])

Y=T_I.initClock()
sym=Y[0]
syd=Y[1]
}
nextSyncT=new Date()
nextSyncT.setTime(nextSyncT.getTime()-tD+3600000)
if(49<cY&&syncn<1){for(var i=0;i<syncn;i++)dots+='.'
sym=p_syncing+dots
syd=''
syncn++
httpSync()}
else{o=gob('front_loc');if(o)o.style.visibility='visible'
;o=gob('socbuttons');if(o)o.style.visibility='inherit'
}
if(syd=='')syd='&nbsp;'
spdays={}
for(i=5;i<r.length-1;i++)spdays[r[i].substr(0,4)]=r[i].substr(4,r[i].length)
if(zone_id!=='UTC'){// zone_offset=r[2];zone_id=r[3]
}
}else{sym=p_conn_failed
syd=xR.statusText
if(syd!='')syd=' ('+syd+')'
if(!A){if(xR.statusText!="")sym+=syd
syd='<a href="javascript:T_I.check_again()">'+p_try_again+'</a>'
}
}
gob('syncH').innerHTML=sym
gob('syncDtl').innerHTML=syd
var ac=gob('accuracy')
if(ac)ac.innerHTML=syd
setmsgH(0)
}}
function sg(q,sd){
T_I.set_susdiv(sd);o=gob(sd)
if((N!==q.match(/^ตำแหน่ง \d+ \(ไม่บังคับ\)$/))||q=='ป้อนตำแหน่ง'||q=='อัตโนมัติ')return ''
q=q.replace(/ +$/,'').replace(/^ +/, '')
if(q.length<4)q=q.toLowerCase()
var n=sd.replace('susdiv','')
if((typeof complocurls!=U)&&(typeof complocurls[n]!=U)&&(complocurls[n][0]==q))return ''
if(typeof prevq[sd]!==U&&q==prevq[sd]||q==e_loc){o.className=o.className.replace('hide','show')
return ''}
if(q.length<1){o.innerHTML='';chosen_sus[sd]=0;prevq[sd]=q;current_q[sd]=q;return ''}
prevq[sd]=q
if(sus[q]){T_I.populate_sus(sd,q,1);return ''}
var xh=N,xhp=[]
if(window.XMLHttpRequest)xh=new XMLHttpRequest()
else if(window.ActiveXObject)xh=new ActiveXObject('Microsoft.XMLHTTP')
if(xh!=N){rqT=new Date()
xh.onreadystatechange=function(){if(xh.readyState==4)if(xh.status==200){
var xr=xh.responseText.split("\n"),st=xr.shift(),q1=xr.shift()
for(var i in xr){
if(i==='indexOf')break
xr[i]=xr[i].split('	')
}
sus[q1]=xr
if(typeof prevsustime[xhp['sd']]==U||prevsustime[xhp['sd']]<xhp['t']){prevsustime[xhp['sd']]=xhp['t'];T_I.populate_sus(xhp['sd'],xhp['q'],1)}}}
xhp['sd']=sd
xhp['t']=new Date()
if(q=='.')q='.a'
if(q=='..')q='.,'
xhp['q']=q
xh.open("get",'/s/'+l+'/'+q.length+'/'+encodeURIComponent(q.replace(/ /g,'_'))+'?'+xhp['t'].getTime(),E)
xh.send(N)
}else xh='N/A'
}
function arrows(sd,e){var k=e.which||e.keyCode
if(k==40||k==38)T_I.cycle_sus(sd,k-39)
else if(k==9||k==13)T_I.take_chosen(sd,k)
else return E
return F}
function togglesimple(x){var g='',c=bod.className
if(x!==0&&c.indexOf('simplify')!=-1){dmode=0;bod.className=c.replace('simplify','showall');x=1}
else if(x!==1&&c.indexOf('showall')!=-1){dmode=1;bod.className=c.replace('showall','simplify');x=0;g='none'}else x=''
if(x!==''){var gp=gob("___plusone_0");if(gp!=N)gp.style.display=g
setsizes(1);T_I.tick('',0)}}var kacs={f:"js:t_FS()",'.':"js:t_s()",sO:"/customize",sS:"js:tl_a()",sC:"/calendar",sD:"js:setcol((conf['c']*1+1)%2)",sJ:"/just",sM:"js:toggle_menu(2)",sT:"/compare","-":"/countdown",sU:"/UTC",sZ:"js:change_clock_size()","$":"https://currency.world","?":"/howto"}
handle_keys=function(ev){if(!bfc)return E
var i,u,e=ev||event,q,k=e.which||e.keyCode,s=e.shiftKey?'s':''
if(e.altKey||e.metaKey||e.ctrlKey)return E
q=String.fromCharCode(k)
if(q.toUpperCase()!==q.toLowerCase())q=s+q
if(typeof kacs[q]===S){u=kacs[q]
if(u.substr(0,3)=="js:")eval(u.substr(3))
else{if(u.substr(0,4)=="http")open(u,"_blank")
else location=u}return F}

if(k===47||(96<k&&k<123)||(64<k&&k<91)){toggle_menu(0);t_search(1);if(k===47)return F}
i=locs.favs.length-k+48;if((48<k&&k<58)&&U!==typeof locs.favs[i]){location='/'+locs.favs[i][4];return F}
return E}
handle_arrow_keys=function(ev){
if(fc["a"]==1)return E
var e=ev||event,k=e.which||e.keyCode,s=e.shiftKey?'s':''
if(e.altKey||e.metaKey||e.ctrlKey)return E
if(k==27){toggle_menu(0);if(!t_search(0)){togglesimple(1);pstart=[];chosendayid=F;goto_this_year()}return F}
if(k==36){if(window.scrollY!==0)return E;location='/';return F}
if(bfc&&36<k&&k<41&&typeof kacs[s+k]===S){
var u=kacs[s+k]
if(u.substr(0,3)=="js:")eval(u.substr(3))
else location=u
return F
}
return E
}
function toggle_more(){
var t=gob('top'),cn='less'
if(t.className=='less')cn='more'
t.className=cn
set_mw()
}
D.onkeypress=this.handle_keys
D.onkeydown=this.handle_arrow_keys
</script> 
  <meta name="description" content="7 ล้านตำแหน่ง 52 ภาษา ถูกซิงโครไนซ์กับเวลานาฬิกาอะตอม">
  <meta property="og:image" content="https://time.is/img/shareable/time_is_110011.png">
  <meta property="og:image" content="https://time.is/img/shareable/time_is_110011_dark.png">
  <meta property="og:image" content="https://time.is/img/shareable/time_is_with_milliseconds_110742.png">
  <meta property="og:image" content="https://time.is/img/shareable/time_is_with_milliseconds_110742_dark.png">
  <meta name="viewport" content="user-scalable=0, initial-scale=1, maximum-scale=1, minimum-scale=1, width=device-width"> 
  <link rel="image_src" href="/img/shareable/time_is_110011.png">
  <link rel="icon" type="image/x-icon" href="/favicon.ico"> 
  <link rel="apple-touch-icon" href="/img/apple-touch-icon.png"> 
  <link rel="search" type="application/opensearchdescription+xml" title="Time.is" href="/opensearch.xml"> 
  <link rel="alternate" type="application/rss+xml" title="Time Zone News from Time.is" href="https://rss.time.is/time_zone_news.rss">
  <style>
*{margin:0;padding:0;border:0;outline:0}
div,h1,h2,h3,label,time{clear:both}
div,img,form{float:left}
#clock{float:left}
body{background:#fff}
span a,.nw,#clock{white-space:nowrap}
body,select,input,textarea{font:18px/26px 'Times New Roman',Times,FreeSerif,serif;color:#333;letter-spacing:2px}
#nav h3{letter-spacing:1px}
@font-face{
font-family:'Timeis';
font-style:normal;
font-weight:normal;
src:url('/fonts/Time-is-short.ttf') format('truetype');
}
@font-face {
font-family: 'Montserrat';
font-style: normal;
font-weight: 600;
font-display: swap;
src: local('Montserrat SemiBold'), local('Montserrat-SemiBold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_bZF3gnD_g.woff2) format('woff2');
unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
/* latin-ext */
@font-face {
font-family: 'Montserrat';
font-style: normal;
font-weight: 400;
font-display: swap;
src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459Wdhyzbi.woff2) format('woff2');
unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
font-family: 'Montserrat';
font-style: normal;
font-weight: 400;
font-display: swap;
src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459Wlhyw.woff2) format('woff2');
unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
/* latin-ext */
@font-face {
font-family: 'Montserrat';
font-style: normal;
font-weight: 900;
font-display: swap;
src: local('Montserrat Black'), local('Montserrat-Black'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_epG3gfD_u50.woff2) format('woff2');
unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
/* latin */
@font-face {
font-family: 'Montserrat';
font-style: normal;
font-weight: 900;
font-display: swap;
src: local('Montserrat Black'), local('Montserrat-Black'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_epG3gnD_g.woff2) format('woff2');
unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
body.mts,body.mts .clockdate,body.mts .clockplace{font-family:Montserrat,'Arial Black','Arial-BoldMT','Arial Bold',Arial,Helvetica,sans-serif}
.mts time{font-family:Timeis,'Arial Black','Arial-BoldMT','Arial Bold',Arial,Helvetica,sans-serif}
time#clock{font-weight:900}
.mts h1,.mts h2,.mts h3,.mts .clockdate{font-weight:900;font-style:normal}
.mts .clockdate,.mts .clockplace{font-weight:normal}
.mts div,.mts select,.mts .txtin,.mts .button,.mts textarea,.mts .clockdate,.mts .clockplace{font-family:Montserrat,Arial,Helvetica,sans-serif}
.mts #favs li span{color:#000;font-weight:400;font-size:20px}
.d #favs li span{color:#fff}
.mts #favs li .time,.mts .event_summary,.mts #msgdiv h1{font-weight:400}
.mts #msgdiv h1 span,.mts #msgdiv h1#syncH{font-weight:900}
body.mts,.mts select,.mts input,.mts textarea,.mts h1,.mts h2,body.mts .clockdate,.mts .tbx div{letter-spacing:0}
.mts #nav h3{letter-spacing:0;font-weight:400}
.mts #nav a.logo{color:#fff;text-transform:uppercase;letter-spacing:4px}
.mts nav .logo{font-family:Montserrat;font-weight:900}
.mts nav .slogan{font-weight:900}

#clock{font-size:100px;line-height:normal;position:relative;font-weight:bold}
#clock span{display:inline-block;text-align:center}
.mon,.caln td div span{display:inline-block;text-align:center;width:12px}
#clock0_bg{margin:60px 0}
div.lg a:link,div.lg a:visited{text-transform:uppercase;font-weight:600;font-size:16px;padding:20px 30px;letter-spacing:3px}
blockquote{font-weight:900}
#favs li .time span{display:inline-block;text-align:center;width:13px}
@media only screen and (max-width:639px){.mon{width:10px}}
@media only screen and (max-width:1280px){#clock0_bg{margin:60px 0}}
@media only screen and (max-width:1024px){#clock0_bg{margin:30px 0}}
@media only screen and (max-width:768px){#clock0_bg{margin:20px 0}}
@media only screen and (max-height:720px){#clock0_bg{margin:20px 0}}
@media only screen and (max-width:400px){div.lg a:link,div.lg a:visited{font-size:14px;padding:15px 20px;letter-spacing:2px}}.divider{color:#ccc}
.lsp{float:right;color:#333}
.lsp ul{list-style:none;text-align:right}
a:link,a:visited{color:#333;text-decoration:none;border-bottom:1px solid #ccc}
h1,h2,.clockdate,.clockplace{font-size:36px;line-height:40px;font-weight:normal;letter-spacing:1px}
.w90{margin-left:5%;width:90%}
#c{padding-bottom:40px}
#msgdiv{float:left}
div#msgs h1{margin-right:30px;float:left}
.lg a:link,.lg a:visited{background:#c35;float:left;display:block;color:#fff;border:0;padding:20px;font:26px/20px Montserrat,Arial,sans-serif;font-weight:900;letter-spacing:2px}
.lg{z-index:9;position:relative}
#pl,#popmsg{display:none}
time{cursor:pointer;direction:ltr}
#fs-video-container,#fs-video-container div,#cnx-autoplay-container div{float:none}

#top{width:90%;margin:0 5%}
#clock0_bg{width:100%}
#clock0,.clockplace,#lC,.clockdate,#daydiv{text-align:right}
select{height:40px}
#pL a:link,#pL a:visited,#pL1 a,#lC,#daydiv,#daydiv1{color:#333}

#pL,#pL1{margin-bottom:20px}
#favs{width:100%;list-style:none;margin:0 0 10px 0;padding:0;float:right}
#favs span{color:#999}
.tbx div{clear:none;float:left;text-align:left;white-space:nowrap;font-size:18px;line-height:22px;font-style:normal;font-weight:normal;letter-spacing:2px}
.tbx a{display:block;margin:0 0 10px 10px;padding:10px 20px;border:1px solid #eee;background:#eee;text-decoration:none}
.txtin,.dateinput{background:#eee;border:1px solid #ddd;width:138px;padding:10px;color:#333}
.mout{border-color:#eee}
</style>
  <link rel="stylesheet" href="/css/t2021-06-23c.css"> 
 </head> 
 <body id="bdy" onload="scrollTo(0,1)" class="showall mts l  landscape"> 
  <div id="popmsg">
   <div id="popmsgpos">
    <div id="popmsgbg" onclick="remove_popmsg()"> 
     <div id="popmsg-close-btn">
      ×
     </div> 
     <div id="popmsgtext"></div> 
    </div>
   </div>
  </div> 
  <div id="mainwrapper"> 
   <div id="top"> 
    <div class="lg">
     <h2><a href="https://time.is/" target="_top" title="Time.is">Time.is</a></h2>
    </div> 
    <div class="icon-nav tr"> 
     <a href="#nav" onclick="return toggle_menu(1)" title="เมนู"> 
      <div style="margin-top:2px;width:100%;border-top:5px solid #aaa;padding:3px 0 2px 0;border-bottom:5px solid #aaa;margin-bottom:5px"></div> 
      <div style="width:100%;border-top:5px solid #aaa;padding:2px 0;margin-bottom:4px"></div> </a> 
    </div> 
    <script>
function t_search(x){var qi=gob('q'),w=600
if(x){
scrollTo(0,0)
qi.focus()
if(ww<915)w=ww*.9-80
if(qi.value.indexOf('')!=-1)qi.value=qi.value.replace('','');setfocus('susdiv');sg(qi.value,'susdiv');focusitem(qi);if(dmode)bod.className=bod.className.replace('simplify','showall');gob('qbox').className='fcs'
}else{
if(gob('qbox').className!=='fcs')return F;
qi.blur()
w=100
if(ww<915)w=100
if(ww<641||Tstate.current_page=='Unix_time_now')w=0
if(qi.value==='')qi.value=''
losefocus('susdiv')
bluritem(qi)
if(dmode)bod.className=bod.className.replace('showall','simplify')
setTimeout("gob('qbox').className=''",200)
}
qi.style.width=w+'px'
return E}
</script> 
    <form id="qbox" class="tr" action="/" method="get" autocomplete="off" accept-charset="UTF-8" onsubmit="return T_I.submit(gob('q').value)"> 
     <input type="text" id="q" name="q" value="" tabindex="1" maxlength="100" accesskey="3" class="txtin blr mout" onfocus="t_search(1)" onblur="t_search(0)" onmouseover="mouseover(this)" onmouseout="mouseout(this)" onkeydown="arrows('susdiv',event)" onkeyup="sg(this.value,'susdiv')"> 
     <div id="susdiv" class="susdiv" onmouseover="setfocus('susdiv')" onmouseout="losefocus('susdiv')"></div> 
    </form> 
   </div>
   <div id="time_section" class="w1" style="margin-top: 0px;">
    <div id="msgs" class="tr w90 vsbl">
     <div id="msgdiv">
      <h1 id="syncH" style="float:left">กำลังซิงโครไนซ์</h1>
     </div>
     <div id="syncDtl" class="w1">
      &nbsp;
     </div>
     <div id="front_loc" class="w1" style="visibility:hidden">
      เวลาใน 
      <a href="Songkhla,_Songkhla">สงขลา, จังหวัดสงขลา, ไทย</a> ในขณะนี้:
     </div>
    </div>
    <div style="width:100%;position:relative">
     <div id="clock0_bg" onclick="clockclick(event)">
      <time id="clock" style="font-size: 237px; line-height: 165px; margin-left: 121.5px;"><span style="width:216px;margin-left:-54px">2</span><span style="width:216px;margin-left:-54px">2</span><span class="sep" style="width:129px;margin-left:-54px">:</span><span style="width:216px;margin-left:-54px">3</span><span style="width:216px;margin-left:-54px">1</span><span class="sep" style="width:129px;margin-left:-54px">:</span><span style="width:216px;margin-left:-54px">4</span><span style="width:216px;margin-left:-54px">0</span></time>
     </div>
    </div>
    <noscript>
     <h2 class="w90 error">นาฬิกาจะอัปเดตโดยอัตโนมัติหากคุณเปิด JavaScript ในเบราว์เซอร์ของคุณ</h2>
    </noscript>
    <div id="dd" class="w90 tr clockdate" onclick="location='/calendar'" title="คลิกเพื่อดูปฏิทิน">
     วันพฤหัสบดีที่ 16 กันยายน 2021 
     <span class="nw">สัปดาห์ 37</span>
    </div>
    <div id="daydiv" class="w90 tr noprint">
     <a target="_blank" href="https://en.wikipedia.org/wiki/International_Day_for_the_Preservation_of_the_Ozone_Layer">International Day for the Preservation of the Ozone Layer</a>
    </div>
    <div id="lC" class="w90 tr">
     <span id="locw">ดวงอาทิตย์: <span id="sun" class="nw">↑ 06:08 ↓ 18:17 (12ชม 9นาที)</span> <a href="Songkhla,_Songkhla#time_zone">ข้อมูลเพิ่มเติม</a></span>
     <div class="lsp w90 tr"></div>
    </div>
    <div class="w90 tr">
     <ul id="favs" class="tbx">
      <li id="favbox-0"><a href="Tokyo" id="time-0">โตเกียว<br><span class="time"><span class="mon">0</span><span class="mon">0</span>:<span class="mon">3</span><span class="mon">1</span></span></a></li>
      <li id="favbox-1"><a href="Beijing" id="time-1">ปักกิ่ง<br><span class="time"><span class="mon">2</span><span class="mon">3</span>:<span class="mon">3</span><span class="mon">1</span></span></a></li>
      <li id="favbox-2"><a href="Moscow" id="time-2">มอสโก<br><span class="time"><span class="mon">1</span><span class="mon">8</span>:<span class="mon">3</span><span class="mon">1</span></span></a></li>
      <li id="favbox-3"><a href="Paris" id="time-3">ปารีส<br><span class="time"><span class="mon">1</span><span class="mon">7</span>:<span class="mon">3</span><span class="mon">1</span></span></a></li>
      <li id="favbox-4"><a href="London" id="time-4">ลอนดอน<br><span class="time"><span class="mon">1</span><span class="mon">6</span>:<span class="mon">3</span><span class="mon">1</span></span></a></li>
      <li id="favbox-5"><a href="New_York" id="time-5">นครนิวยอร์ก<br><span class="time"><span class="mon">1</span><span class="mon">1</span>:<span class="mon">3</span><span class="mon">1</span></span></a></li>
      <li id="favbox-6"><a href="Los_Angeles" id="time-6">ลอสแอนเจลิส<br><span class="time"><span class="mon">0</span><span class="mon">8</span>:<span class="mon">3</span><span class="mon">1</span></span></a></li>
     </ul>
    </div>
    <div id="recover" style="width:100%">
     <div class="tr" style="width:90%;padding:0 5% 20px 5%">
      <div class="rad" style="float:right;padding-top:0">
       <div id="time.is_728x90_970x90_970x250_300x250_320x50_ATF" style="position:relative;float:right">
        <script data-cfasync="false">
freestar.config.enabled_slots.push({placementName:"time.is_728x90_970x90_970x250_300x250_320x50_ATF",slotId:"time.is_728x90_970x90_970x250_300x250_320x50_ATF"});
</script>
       </div>
       <div id="time.is_728x90_970x90_970x250_300x250_320x50_ATF2" style="position:relative;float:right;clear:none;margin-right:20px">
        <script data-cfasync="false">
freestar.config.enabled_slots.push({placementName:"time.is_728x90_970x90_970x250_300x250_320x50_ATF2",slotId:"time.is_728x90_970x90_970x250_300x250_320x50_ATF2"});
</script>
       </div>
      </div>
     </div>
    </div> 
   </div> 
   <script>
bod=gob('bdy')
var l='th',conf={d:'วัน%lที่ %j %F %Y %W',t:'H:i:s',f:'mts',c:'2',o:'',z:'1',a:'1',b:'51ea29.4e4185.28571f.2d99db.80265.1bb85e.1c3b23',w:'0',v:'20210916',h:0,i:'1',Z:'1',m:'',u:''},locs={favs:[['1850147','444','โตเกียว','โตเกียว, ญี่ปุ่น','Tokyo','35.68950','139.69171','8,336,599',''],['1816670','43d','ปักกิ่ง','ปักกิ่ง, จีน','Beijing','39.90750','116.39723','11,716,620',''],['524901','71d','มอสโก','มอสโก, รัสเซีย','Moscow','55.75222','37.61556','10,381,222',''],['2988507','71f','ปารีส','ปารีส, ฝรั่งเศส','Paris','48.85341','2.34880','2,138,551',''],['2643743','716','ลอนดอน','ลอนดอน, สหราชอาณาจักร','London','51.50853','-0.12574','7,556,900',''],['5128581','161','นครนิวยอร์ก','นครนิวยอร์ก, สหรัฐอเมริกา','New_York','40.71427','-74.00597','8,175,133','10'],['5368361','14e','ลอสแอนเจลิส','ลอสแอนเจลิส, รัฐแคลิฟอร์เนีย, สหรัฐอเมริกา','Los_Angeles','34.05223','-118.24368','3,971,883','89']],main:[['1606147','40a','สงขลา','สงขลา, จังหวัดสงขลา, ไทย','Songkhla,_Songkhla','7.19882','100.59510','84,264','']]},zones={'40a':['Asia/Bangkok','+07',[420]],'444':['Asia/Tokyo','JST',[540]],'43d':['Asia/Shanghai','CST',[480]],'71d':['Europe/Moscow','MSK',[180]],'71f':['Europe/Paris','CEST',[120,1635642000,60]],'716':['Europe/London','BST',[60,1635642000,0]],'161':['America/New_York','EDT',[-240,1636264800,-300]],'14e':['America/Los_Angeles','PDT',[-420,1636275600,-480]]},
susdest='/'
zone_id='Asia/Bangkok'
zone_code='clientside'
zone_offset=-new Date().getTimezoneOffset()
zones['clientside']=['','',[zone_offset]]
p_time_diff="ต่างจาก Time.is %t (±%D) "
p_time_diff_short="ต่างกัน: %t (±%D) "
p_failh="การซิงโครไนซ์ไม่สำเร็จ "
p_fail="ไม่สามารถให้ผลลัพธ์ที่มีความแม่นยำสูงได้เนื่องจากการเชื่อมต่อหรือคอมพิวเตอร์ของคุณช้าหรือทำงานหนัก "
p_syncing="กำลังซิงโครไนซ์"
p_conn_failed="ไม่สามารถเชื่อมต่อกับเซิร์ฟเวอร์"
p_try_again="ลองอีกครั้งหรือไม่?"
p_no_match="ไม่มีรายการที่ตรงกัน"
p_no_au="ขออภัย จำเป็นต้องใช้ Firefox, Opera หรือ Safari เวอร์ชันล่าสุดเพื่อใช้นาฬิกาแบบมีเสียง!"
p_no_cookie_support="error_no_cookie_support"
p_td="วันนี้"
e_loc="ป้อนตำแหน่ง"

days=["อาทิตย์","จันทร์","อังคาร","พุธ","พฤหัสบดี","ศุกร์","เสาร์"]
daysh=["อา.","จ.","อ.","พ.","พฤ.","ศ.","ส."]
daysI=["อา","จ","อ","พ","พฤ","ศ","ส"]
months=["มกราคม","กุมภาพันธ์","มีนาคม","เมษายน","พฤษภาคม","มิถุนายน","กรกฎาคม","สิงหาคม","กันยายน","ตุลาคม","พฤศจิกายน","ธันวาคม"]
monthsh=["ม.ค.","ก.พ.","มี.ค.","เม.ย.","พ.ค.","มิ.ย.","ก.ค.","ส.ค.","ก.ย.","ต.ค.","พ.ย.","ธ.ค."]
p_exactt="เวลาของคุณตรงกับเวลาตามจริง!"
p_t_is="เวลาปัจจุบันตามจริงคือ:"
p_w="สัปดาห์ "
p_wn="สัปดาห์ %n"
p_d="วัน"
p_ds=" วัน"
p_h=" ชั่วโมง"
p_hs=" ชั่วโมง"
p_m=" นาที"
p_ms=" นาที"
p_s=" วินาที"
p_ss=" วินาที"
p_ss_short=" วินาที"
p_ur_late="นาฬิกาของคุณช้าไป %t"
p_ur_early="นาฬิกาของคุณเร็วไป %t"
p_acc="ความแม่นยำในการซิงโครไนซ์คือ ±%t"
p_acc_short="ความแม่นยำในการซิงค์: ±%t"
p_last_s="ซิงโครไนซ์ล่าสุดเมื่อ: %t"
p_last_s_short="ซิงค์ล่าสุดเมื่อ: %t"
p_dec_sym="."
p_and=" และ "
p_time_remaining="เวลาที่เหลือ: %t"
p_time_since="เวลาตั้งแต่นั้นมา: %t"

p_now='ขณะนี้'
p_yesterday='เมื่อวาน'
p_tomorrow='พรุ่งนี้'
p_today='วันนี้'
p_in_n='ใน %n'
p_ago='%n ที่ผ่านมา'
p_In_x_days='ใน %n %days'
p_x_days_ago='%n %days ที่ผ่านมา'
p_x_days_before='[%n %days ก่อน] %other_date'
p_x_days_after='[%n %days หลัง] %other_date'

p_today_date='[วันนี้]: %d'
units=[p_ss,p_ms,p_hs,p_ds],units_sing=[p_s,p_m,p_h,' '+p_d]

p_enter_loc='ป้อนตำแหน่ง'

p_default_time_format='H:i:s'
p_date_formats=['วัน%lที่ %j %F %Y %W',
'%l %d/%m/%y %W',
'%l %d/%m/%y',
'%Y-%m-%d']


spdays={'0916':'<a target="_blank" href="https://en.wikipedia.org/wiki/International_Day_for_the_Preservation_of_the_Ozone_Layer">International Day for the Preservation of the Ozone Layer</a>'}
noctp=1;adheight=0;;show_big_clock=1;force24=0;beginning_of_time()
onresize=function(){setsizes(2)}
</script> 
   <div class="w90">
    <div class="noprint tr faded adjustright" style="position:relative;float:right;margin-right:-10px"> 
     <script>
w_p='status=no,location=no,toolbar=no,menubar=no,width=700,height=500,left=100,top=100'
tweet_text='ตรวจสอบว่าเวลาของคุณเป็นเวลาตามจริงหรือไม่และเป็นเวลาเท่าใดในแต่ละโซนเวลา'
</script> 
     <div class="social_buttons"> 
      <div class="fb-button" onclick="open('https://www.facebook.com/sharer.php?u='+encodeURIComponent(location),'Share',w_p)" title="Share on Facebook"> 
       <svg xmlns="http://www.w3.org/2000/svg" viewbox="0 0 320 512">
        <path d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z"></path>
       </svg> 
      </div> 
      <div class="twitter-button" onclick="open('https://twitter.com/intent/tweet?text='+encodeURIComponent(tweet_text)+'&amp;url='+encodeURIComponent(location)+'&amp;via=Time_is','Share',w_p)" title="Share on Twitter"> 
       <svg xmlns="http://www.w3.org/2000/svg" viewbox="0 0 512 512">
        <path d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"></path>
       </svg> 
      </div> 
     </div> 
     <div class="noprint tr" style="font-size:14px;float:right;margin:0 10px 10px 10px">
      แชร์หน้านี้!
     </div>
    </div> 
   </div>
  </div>
  <section id="top_cities_tmp"> 
   <div class="cloud w90 d">
    <a href="Addis_Ababa" class="s9">Addis Ababa</a> 
    <a href="Auckland,_New_Zealand" class="s15">Auckland</a> 
    <a href="Baghdad" class="s7">Baghdad</a> 
    <a href="Istanbul" class="s2 bold">Istanbul</a> 
    <a href="Bangkok" class="s7">Krung Thep</a> 
    <a href="Tel_Aviv" class="s13">Tel Aviv</a> 
    <a href="Washington,_D.C." class="s15">Washington, D.C.</a> 
    <a href="Guangzhou" class="s8">กว่างโจว</a> 
    <a href="Kuala_Lumpur" class="s11">กัวลาลัมเปอร์</a> 
    <a href="Kathmandu" class="s11">กาฐมาณฑุ</a> 
    <a href="Caracas" class="s9">การากัส</a> 
    <a href="Karachi" class="s2 bold">การาจี</a> 
    <a href="Kinshasa" class="s6 bold">กินชาซา</a> 
    <a href="Jakarta" class="s5 bold">จาการ์ตา</a> 
    <a href="Chicago" class="s5 bold">ชิคาโก</a> 
    <a href="Santiago" class="s7">ซันติอาโก</a> 
    <a href="San_Francisco" class="s13">ซานฟรานซิสโก</a> 
    <a href="Sydney" class="s4 bold">ซิดนีย์</a> 
    <a href="Dublin" class="s13">ดับลิน</a> 
    <a href="Dubai" class="s4 bold">ดูไบ</a> 
    <a href="Dhaka" class="s4 bold">ธากา</a> 
    <a href="New_York" class="s1 bold">นครนิวยอร์ก</a> 
    <a href="New_Delhi" class="s16">นิวเดลี</a> 
    <a href="Nuuk" class="s16">นุก</a> 
    <a href="Brussels" class="s13">บรัสเซลส์</a> 
    <a href="Boston" class="s14">บอสตัน</a> 
    <a href="Buenos_Aires" class="s3 bold">บัวโนสไอเรส</a> 
    <a href="Barcelona" class="s11">บาร์เซโลนา</a> 
    <a href="Prague" class="s13">ปราก</a> 
    <a href="Beijing" class="s1 bold">ปักกิ่ง</a> 
    <a href="Paris" class="s3 bold">ปารีส</a> 
    <a href="Manila" class="s3 bold">มนิลา</a> 
    <a href="Moscow" class="s2 bold">มอสโก</a> 
    <a href="Mecca" class="s12">มักกะฮ์</a> 
    <a href="Madrid" class="s8">มาดริด</a> 
    <a href="Milan" class="s12">มิลาน</a> 
    <a href="Mumbai" class="s3 bold">มุมไบ</a> 
    <a href="Yangon" class="s8">ย่างกุ้ง</a> 
    <a href="Riyadh" class="s8">ริยาด</a> 
    <a href="Rio_de_Janeiro" class="s7">รีโอเดจาเนโร</a> 
    <a href="London" class="s1 bold">ลอนดอน</a> 
    <a href="Los_Angeles" class="s1 bold">ลอสแอนเจลิส</a> 
    <a href="Las_Vegas" class="s15">ลาสเวกัส</a> 
    <a href="Lima" class="s6">ลิมา</a> 
    <a href="Luanda" class="s9">ลูอันดา</a> 
    <a href="Warsaw" class="s11">วอร์ซอ</a> 
    <a href="Stockholm" class="s12">สตอกโฮล์ม</a> 
    <a href="Singapore" class="s4 bold">สิงคโปร์</a> 
    <a href="Oslo" class="s15">ออสโล</a> 
    <a href="Antananarivo" class="s12">อันตานานาริโว</a> 
    <a href="Amsterdam" class="s14">อัมสเตอร์ดัม</a> 
    <a href="Abu_Dhabi" class="s14">อาบูดาบี</a> 
    <a href="Hanoi" class="s12">ฮานอย</a> 
    <a href="Havana" class="s10">ฮาวานา</a> 
    <a href="Hong_Kong" class="s5 bold">ฮ่องกง</a> 
    <a href="Cape_Town" class="s8">เคปทาวน์</a> 
    <a href="Kyiv" class="s9">เคียฟ</a> 
    <a href="Saint_Petersburg" class="s7">เซนต์ปีเตอร์สเบิร์ก</a> 
    <a href="São_Paulo" class="s2 bold">เซาเปาลู</a> 
    <a href="Shenzhen" class="s9">เซินเจิ้น</a> 
    <a href="Shanghai" class="s3 bold">เซี่ยงไฮ้</a> 
    <a href="Delhi" class="s2 bold">เดลี</a> 
    <a href="Tehran" class="s6">เตหะราน</a> 
    <a href="Berlin" class="s10">เบอร์ลิน</a> 
    <a href="Mexico_City" class="s1 bold">เม็กซิโกซิตี</a> 
    <a href="Reykjavik" class="s16">เรคยาวิก</a> 
    <a href="Lagos" class="s5 bold">เลกอส</a> 
    <a href="Vienna" class="s11">เวียนนา</a> 
    <a href="Athens" class="s14">เอเธนส์</a> 
    <a href="Helsinki" class="s15">เฮลซิงกิ</a> 
    <a href="Frankfurt" class="s14">แฟรงค์เฟิร์ต</a> 
    <a href="Vancouver" class="s10">แวนคูเวอร์</a> 
    <a href="Seoul" class="s4 bold">โซล</a> 
    <a href="Tokyo" class="s1 bold">โตเกียว</a> 
    <a href="Toronto" class="s8">โทรอนโต</a> 
    <a href="Bogotá" class="s6">โบโกตา</a> 
    <a href="Rome" class="s10">โรม</a> 
    <a href="Osaka" class="s10">โอซะกะ</a> 
    <a href="Honolulu" class="s16">โฮโนลูลู</a> 
    <a href="Cairo" class="s6">ไคโร</a> 
    <a href="Taipei" class="s5 bold">ไทเป</a> 
    <a href="Miami" class="s16">ไมแอมี</a> 
    <br> 
    <br> 
    <a class="s6" href="UTC">UTC</a> 
    <a class="s6" href="GMT">GMT</a> 
    <a class="s6" href="CET">CET</a>
    <br> 
    <a class="s6" href="PT">Pacific Time</a> 
    <a class="s6" href="MT">Mountain Time</a> 
    <a class="s6" href="CT">Central Time</a> 
    <a class="s6" href="ET">Eastern Time</a> 
    <a class="s6" href="China_Standard_Time">China Standard Time</a> 
    <a class="s6" href="IST">India Standard Time</a> 
   </div> 
   <div class="cad">
    <div id="time.is_728x90_970x90_970x250_300x250_320x50_Middle" style="position:relative;float:right">
     <script data-cfasync="false">
freestar.config.enabled_slots.push({placementName:"time.is_728x90_970x90_970x250_300x250_320x50_Middle",slotId:"time.is_728x90_970x90_970x250_300x250_320x50_Middle"});
</script>
    </div>
   </div> 
   <div id="freestar-video-desktop"></div> 
   <div id="freestar-video-mobile"></div> 
  </section> 
  <section id="quote"> 
   <blockquote>
    "People who cannot find time for recreation are obliged sooner or later to find time for illness."
   </blockquote> 
   <cite>John Wanamaker</cite> 
  </section>
  <div id="menupositioner"> 
   <div id="close-menu" class="close-btn" onclick="toggle_menu(0)">
    ×
   </div> 
   <div id="menutransformer"> 
    <nav id="nav"> 
     <div> 
      <h3><a href="/" class="logo">Time.is</a> <span class="slogan"><span>- </span>ดูเวลาจริงของโซนเวลานั้นๆ</span></h3> 
      <div id="menulinks">
       <ul>
        <li class="chosen"><a href="/">เวลาจริงในขณะนี้</a></li>
        <li><a href="/compare">เวลาที่นี่และที่นั่น</a></li>
        <li><a href="/time_zones">โซนเวลา</a></li>
        <li><a href="/DST_2021">เวลาออมแสง</a></li>
        <li><a href="/just">แสดงเวลาเท่านั้น</a></li>
        <li><a href="/calendar">ปฏิทิน</a></li>
        <li id="aub"><a href="sound">นาฬิกาแบบมีเสียง</a></li>
       </ul>
       <ul>
        <li><a href="/apps">แอป</a></li>
        <li><a href="/widgets">วิดเจ็ต</a></li>
        <li><a href="/time_zone_news">ข่าวโซนเวลา</a></li>
        <li><a href="/mailing_list">จดหมายข่าว</a></li>
       </ul>
       <ul>
        <li><a href="/UTC">UTC</a></li>
        <li><a href="/Unix_time_now">นาฬิกา Unix</a></li>
        <li><a href="/Unix_time_converter">ตัวแปลงเวลา Unix</a></li>
       </ul>
       <ul>
        <li><a href="/customize">ปรับแต่ง</a></li>
        <li><a href="/FAQ">คำถามที่พบบ่อย</a></li>
        <li><a href="/howto">How to use Time.is</a></li>
        <li><a href="/about">เกี่ยวกับ</a></li>
        <li><a href="/contact">ติดต่อ</a></li>
       </ul>
      </div>
     </div> 
     <div id="follow_app" class=""> 
      <div id="follow">
       <div>
        ติดตามเรา
       </div> 
       <a href="https://www.facebook.com/exact.time.is" target="_blank" rel="nofollow,noreferer,noopener" style="background:url('/img/social_icons5.png') 224px 32px" onmouseover="Zpos(this,224,0)" onmouseout="Zpos(this,224,32)" title="ติดตาม Time.is บน Facebook">Facebook</a> 
       <a href="https://twitter.com/Time_is" target="_blank" rel="nofollow,noreferer,noopener" style="background:url('/img/social_icons5.png') 192px 32px" onmouseover="Zpos(this,192,0)" onmouseout="Zpos(this,192,32)" title="ติดตาม Time.is บน Twitter">Twitter</a> 
      </div> 
      <div id="appbadge">
       <a href="https://itunes.apple.com/app/time.is-exact-time-for-any/id857189816?ls=1&amp;mt=8"><img src="/img/app_store_badge/Download_on_the_App_Store_Badge_TH_135x40.svg" alt="Download on the App Store"></a>
      </div> 
     </div> 
    </nav> 
    <script>
place_badges()
</script> 
    <footer id="footer">
     <nav>
      <ul class="hzlist" style="padding-bottom:0">
       <li class="first"><a href="/advertise">โฆษณา</a></li>
       <li class="last"><a href="/terms_of_use">เงื่อนไขการใช้งาน</a></li>
       <li><a href="/terms_of_use#privacy_policy">นโยบายความเป็นส่วนตัว</a></li>
      </ul>
     </nav> 
     <div>
       Time.is แสดงเวลาตามนาฬิกาจริงที่ถูกต้องอย่างละเอียดในโซนเวลาแต่ละโซน (กว่า 7 ล้านตำแหน่ง) ใน 52 ภาษา
      <br> การเข้าถึงอัตโนมัติถูกห้าม จำเป็นต้องมีการรองรับคุกกี้และ JavaScript 
      <br> สงวนลิขสิทธิ์ © 2009-2021 Time.is AS 
      <span class="nw">สงวนสิทธิ์ทุกประการ</span> 
     </div> 
     <div id="footerlangs"> 
      <br> 
      <a href="/?lang=en" title="English">What time is it?</a> 
      <a href="/?lang=zh" title="Chinese (simplified) / 中文">几点了？</a> 
      <a href="/?lang=hi" title="Hindi / हिंदी">क्या समय हुआ है?</a> 
      <a href="/?lang=es" title="Spanish / español">¿Qué hora es?</a> 
      <a href="/?lang=fr" title="French / français">Quelle heure est-il ?</a> 
      <a href="/?lang=ar" title="Arabic / العربية">كم الساعة</a> 
      <a href="/?lang=bn" title="Bengali / বাংলা">এখন কয়টা বাজে?</a> 
      <a href="/?lang=ru" title="Russian / русский">Который час?</a> 
      <a href="/?lang=pt_br" title="Portuguese (Brazil) / português (Brasil)">Que horas são?</a> 
      <a href="/?lang=id" title="Indonesian / bahasa Indonesia">Jam berapa?</a> 
      <a href="/?lang=ur" title="Urdu / اردو زبان">؟ےہ اوہ تقو ایک</a> 
      <a href="/?lang=de" title="German / Deutsch">Wieviel Uhr ist es?</a> 
      <a href="/?lang=ja" title="Japanese / 日本語">今何時ですか？</a> 
      <a href="https://saatkac.info.tr/" title="Turkish / Türkçe">Saat kaç?</a> 
      <a href="/?lang=ta" title="Tamil / தமிழ்">என்ன நேரம்?</a> 
      <a href="/languages">≫ choose language</a> 
     </div> 
     <div>
      Time.is automatically displays the time in your time zone by using your IP address to detect your location. 
      <a href="https://ip.fish/">Your IP address is 124.122.229.149.</a> Your detected location is 
      <a href="Songkhla,_Songkhla">สงขลา, จังหวัดสงขลา, ไทย</a>.
     </div> 
    </footer> 
   </div> 
  </div>
  <script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');
ga('create','UA-69493661-1','auto')
ga('set','anonymizeIp',true)
ga('set','contentGroup1','main_page')
ga('send','pageview')
</script>
 </body>
</html>
