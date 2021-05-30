(function(g){var window=this;'use strict';var t4=function(a){g.V.call(this,{D:"div",K:"ytp-miniplayer-ui"});this.Yf=!1;this.player=a;this.N(a,"minimized",this.Ig);this.N(a,"onStateChange",this.kC)},u4=function(a){g.fM.call(this,a);
this.i=new t4(this.player);this.i.hide();g.TL(this.player,this.i.element,4);a.De()&&(this.load(),g.L(a.getRootNode(),"ytp-player-minimized",!0))};
g.v(t4,g.V);g.k=t4.prototype;
g.k.JA=function(){this.tooltip=new g.zP(this.player,this);g.G(this,this.tooltip);g.TL(this.player,this.tooltip.element,4);this.tooltip.scale=.6;this.jc=new g.WM(this.player);g.G(this,this.jc);this.jg=new g.V({D:"div",K:"ytp-miniplayer-scrim"});g.G(this,this.jg);this.jg.Aa(this.element);this.N(this.jg.element,"click",this.Nw);var a=new g.V({D:"button",Ca:["ytp-miniplayer-close-button","ytp-button"],U:{"aria-label":"Close"},S:[g.iK()]});g.G(this,a);a.Aa(this.jg.element);this.N(a.element,"click",this.Lh);
a=new g.W_(this.player,this);g.G(this,a);a.Aa(this.jg.element);this.Mn=new g.V({D:"div",K:"ytp-miniplayer-controls"});g.G(this,this.Mn);this.Mn.Aa(this.jg.element);this.N(this.Mn.element,"click",this.Nw);var b=new g.V({D:"div",K:"ytp-miniplayer-button-container"});g.G(this,b);b.Aa(this.Mn.element);a=new g.V({D:"div",K:"ytp-miniplayer-play-button-container"});g.G(this,a);a.Aa(this.Mn.element);var c=new g.V({D:"div",K:"ytp-miniplayer-button-container"});g.G(this,c);c.Aa(this.Mn.element);this.oI=new g.wO(this.player,
this,!1);g.G(this,this.oI);this.oI.Aa(b.element);b=new g.tO(this.player,this);g.G(this,b);b.Aa(a.element);this.nextButton=new g.wO(this.player,this,!0);g.G(this,this.nextButton);this.nextButton.Aa(c.element);this.pg=new g.mP(this.player,this);g.G(this,this.pg);this.pg.Aa(this.jg.element);this.Dc=new g.BO(this.player,this);g.G(this,this.Dc);g.TL(this.player,this.Dc.element,4);this.Aw=new g.V({D:"div",K:"ytp-miniplayer-buttons"});g.G(this,this.Aw);g.TL(this.player,this.Aw.element,4);a=new g.V({D:"button",
Ca:["ytp-miniplayer-close-button","ytp-button"],U:{"aria-label":"Close"},S:[g.iK()]});g.G(this,a);a.Aa(this.Aw.element);this.N(a.element,"click",this.Lh);a=new g.V({D:"button",Ca:["ytp-miniplayer-replay-button","ytp-button"],U:{"aria-label":"Close"},S:[g.nK()]});g.G(this,a);a.Aa(this.Aw.element);this.N(a.element,"click",this.OQ);this.N(this.player,"presentingplayerstatechange",this.Cc);this.N(this.player,"appresize",this.ob);this.N(this.player,"fullscreentoggled",this.ob);this.ob()};
g.k.show=function(){this.kd=new g.gn(this.Go,null,this);this.kd.start();this.Yf||(this.JA(),this.Yf=!0);0!==this.player.getPlayerState()&&g.V.prototype.show.call(this);this.Dc.show();this.player.unloadModule("annotations_module")};
g.k.hide=function(){this.kd&&(this.kd.dispose(),this.kd=void 0);g.V.prototype.hide.call(this);this.player.De()||(this.Yf&&this.Dc.hide(),this.player.loadModule("annotations_module"))};
g.k.va=function(){this.kd&&(this.kd.dispose(),this.kd=void 0);g.V.prototype.va.call(this)};
g.k.Lh=function(){this.player.stopVideo();this.player.Ma("onCloseMiniplayer")};
g.k.OQ=function(){this.player.playVideo()};
g.k.Nw=function(a){if(a.target===this.jg.element||a.target===this.Mn.element)g.R(this.player.T().experiments,"kevlar_miniplayer_play_pause_on_scrim")?g.lJ(this.player.rb())?this.player.pauseVideo():this.player.playVideo():this.player.Ma("onExpandMiniplayer")};
g.k.Ig=function(){g.L(this.player.getRootNode(),"ytp-player-minimized",this.player.De())};
g.k.Td=function(){this.Dc.Tb();this.pg.Tb()};
g.k.Go=function(){this.Td();this.kd&&this.kd.start()};
g.k.Cc=function(a){g.U(a.state,32)&&this.tooltip.hide()};
g.k.ob=function(){g.MO(this.Dc,0,this.player.Wa().getPlayerSize().width,!1);g.DO(this.Dc)};
g.k.kC=function(a){this.player.De()&&(0===a?this.hide():this.show())};
g.k.ac=function(){return this.tooltip};
g.k.pe=function(){return!1};
g.k.Fe=function(){return!1};
g.k.Hh=function(){return!1};
g.k.mx=function(){};
g.k.Ol=function(){};
g.k.Vp=function(){};
g.k.em=function(){return null};
g.k.zi=function(){return new g.ag(0,0,0,0)};
g.k.handleGlobalKeyDown=function(){return!1};
g.k.handleGlobalKeyUp=function(){return!1};
g.k.Oo=function(a,b,c,d,e){var f=0,h=d=0,l=g.Bg(a);if(b){c=g.sn(b,"ytp-prev-button")||g.sn(b,"ytp-next-button");var m=g.sn(b,"ytp-play-button"),n=g.sn(b,"ytp-miniplayer-expand-watch-page-button");c?f=h=12:m?(b=g.zg(b,this.element),h=b.x,f=b.y-12):n&&(h=g.sn(b,"ytp-miniplayer-button-top-left"),f=g.zg(b,this.element),b=g.Bg(b),h?(h=8,f=f.y+40):(h=f.x-l.width+b.width,f=f.y-20))}else h=c-l.width/2,d=25+(e||0);b=this.player.Wa().getPlayerSize().width;e=f+(e||0);l=g.de(h,0,b-l.width);e?(a.style.top=e+"px",
a.style.bottom=""):(a.style.top="",a.style.bottom=d+"px");a.style.left=l+"px"};
g.k.showControls=function(){};
g.k.dk=function(){};
g.k.Dj=function(){return!1};g.v(u4,g.fM);u4.prototype.create=function(){};
u4.prototype.Uh=function(){return!1};
u4.prototype.load=function(){this.player.hideControls();this.i.show()};
u4.prototype.unload=function(){this.player.showControls();this.i.hide()};g.lM.miniplayer=u4;})(_yt_player);
