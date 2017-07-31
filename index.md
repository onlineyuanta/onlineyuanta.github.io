
<!DOCTYPE html>













<html lang="ko">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=Edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, user-scalable=no, target-densitydpi=medium-dpi">
	<meta name="robots" content="noindex, nofollow" /> 
	<meta name="robots" content="noarchive" /> 
	<meta name="keywords" content="유안타증권 투자정보 포털 - 티레이더 인포">
	<meta name="description" content="유안타증권 투자정보 포털 - 티레이더 인포">	 

	<meta property="og:url" id="og_url" content="https://www.myasset.com/extern/researchPortal/RP_0000000_P1.cmd?v=201707311627">
	<meta property="og:title" id="og_title" content="유안타증권 투자정보 포털      티레이더 인포">
	<meta property="og:type" content="website">
	<meta property="og:image" id="og_image" content="https://www.myasset.com/extern/researchPortal/common/img/mobile/sns_research.png?v=201707311627">
	<meta property="og:description" id="og_description" content="유안타증권 티레이더 인포">
	
	<meta id="twitter_card" name="twitter:card" content="유안타증권 투자정보 포털 - 티레이더 인포">
	<meta id="twitter_url" name="twitter:url" content="https://www.myasset.com/extern/researchPortal/RP_0000000_P1.cmd?v=201707311627">
	<meta id="twitter_title" name="twitter:title" content="유안타증권 투자정보 포털 - 티레이더 인포">
	<meta id="twitter_description" name="twitter:description" content="유안타증권 티레이더 인포">
	<meta id="twitter_image" name="twitter:image" content="https://www.myasset.com/extern/researchPortal/common/img/mobile/sns_research.png?v=201707311627">	

	<link rel="apple-touch-icon-precomposed" href="/templets/resportal/mobile/img/research_logo_152.png" />
	<link rel='shortcut icon' href="/templets/resportal/mobile/img/research_logo_152.png" />
	
	<title>유안타증권 티레이더 인포 - 유안타증권 투자정보 포털</title>

	













<script type="text/javascript">
		
	
			(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
				  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
				  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
				  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');
			
				  ga('create', 'UA-38248489-14', 'auto');
				  ga('send', 'pageview');
			  

//========================================================================================================
var __USER_DN = "";
var __USER_AUTH = "";
var __USER_HSM = "";
var __APPFREE_CERTRELAY = "smartcert.myasset.com";
var __MYNET_LOGIN = "null";
var __INSIDE_IP = "false";
//appfree AUTOINDEX값 저장 [get__APPFREE_AUTOINDEX <--getter함수]
var _APPFREE_AUTOINDEX = encodeURIComponent("");

var _AHNLAB_CHECK = "Y"; //안랩 모듈 설치 체크 여부
var _PENTA_CHECK = "Y"; //펜타 모듈 설치 체크 여부
var _KINGS_CHECK = "Y"; //킹스 모듈 설치 체크 여부
var _CertNewUrl = "http://www.myasset.com/bannerHome.jsp?bannerId=certupdate"; //인증서 갱신 url
var _EXIPRE_CHECK = "1"; //인증서 갱신 안내창 여부

//========================================================================================================

function get__APPFREE_AUTOINDEX(){
	if ( _APPFREE_AUTOINDEX == "" ) {
		_APPFREE_AUTOINDEX = "start";
	}
	return _APPFREE_AUTOINDEX;
}
function get__USER_AUTH(){
    return __USER_AUTH;
}
function isLogin(){
	return false;
}
function get__SESSION_ID(){
	return 'jNFDKLE3fpZpOr2L08CPkmy1Gi766MLYK7F3daMA2rAshnVe9fdAzKKnBVcAmGA2.b2RpbmRvbWFpbi95c3dhczAxXzE=';
}
function get__TIME_ID(){
	return "201707311627"	
}


var __ahnlab = false;
var __penta = false;
var __kings = false;
var __signkorea = false;
var __secureAlertYn = false;

var __SESSION_TIME = 3600;
</script>



<script type="text/javascript">
//콘솔지원 안하는 브라우저에서 사용안함
var consoleFlag = location.host.indexOf('local') >= 0 ? true : false;  //콘솔로그 사용 유무
if (typeof console === "undefined") {
    console = {};
    if(consoleFlag == false){
	    console.log = function() {
	        return;
	    };
    }
}else{
	if(consoleFlag == false){
		console.log = function() {
	        return;
	    };
	}
	
}

//IE7 service 불가:S
function getIeCheckBrowser(){
    var browser = undefined;
    
    var ua =  navigator.userAgent.toLowerCase(),
    rwebkit = /(webkit)[ \/]([\w.]+)/,
    ropera = /(opera)(?:.*version)?[ \/]([\w.]+)/,
    rmsie = /(msie) ([\w.]+)/,
    rmozilla = /(mozilla)(?:.*? rv:([\w.]+))?/;
    var match = rwebkit.exec( ua ) ||ropera.exec( ua ) || rmsie.exec( ua ) || ua.indexOf("compatible") < 0 && rmozilla.exec( ua ) || [];
    
    browser = match[1];  
    if(browser == "msie"){
        //호환성보기를 무시하고 브라우저 버전을 체크 할수있다. IE8부터 유저정보에 추가
        var trident = navigator.userAgent.match(/Trident\/(\d.\d)/i);
        if(trident != null){
            var version = (trident[1]+"");
            if(version == "7.0"){
                browser = "IE11";
            }else if(version == "6.0"){
                browser = "IE10";
            }else if(version == "5.0"){
                browser = "IE9";
            }else if(version == "4.0"){
                browser = "IE8";
            } else{
                //browser = "IE7";
                browser = "IE8";
            }
        }else{
            browser = "IE8";
        }
    }
    return browser;
}

if(getIeCheckBrowser()=="IE7"){
    location.href="/common/security/CS_0500000_P1.jsp";
}

//PC버전 보기, MOBILE버전 보기:S
try{
    (function(){
        var __IS_MOBILE = false;
        

        var __USER_SELECT_DEVICE = "null";
        var __MOBILE_DOMAIN      = "www.myasset.com";
        var __PC_DOMAIN          = "01.myasset.com";

        var hostport = location.port;
        var hostname = location.hostname + (hostport == "" ? "" : ":"+hostport);
        var protocol = location.protocol;
        var needLocationHref = false;

        //1.http 접속인경우 https로 변경

        if(protocol=="http:"||protocol.indexOf("http:")==0){
            needLocationHref = true;
            protocol = "https:";            
            
            /*개발 스테이징에서 websocket https 안되서*/
            if(__PC_DOMAIN == "dev.myasset.com" || __PC_DOMAIN == "stg.myasset.com" || __PC_DOMAIN == "local.myasset.com"){
            	needLocationHref = false;
            }
        }
        
        
		//no1cma.com 으로 접속히 www.no1cma.com 으로 리다이렉트
        if("no1cma.com" == location.hostname){
        	location.href="https://www."+hostname+location.pathname+location.search;
        	return;
        }
		//myasset.co.kr 일경우 -> myasset.com 으로 변환
        if(location.hostname.indexOf("myasset.co.kr") > -1){        	
        	hostname = hostname.replace("myasset.co.kr","myasset.com");        	
        	location.href=protocol+"//"+hostname+location.pathname+location.search;
        	return;
        }
		
        if(location.hostname == "myasset.com"){
	    	location.href=protocol+"//www."+hostname+location.pathname+location.search;
	    	return;
	    }
		        
        if(__PC_DOMAIN != "local.myasset.com"){//개발피시의 경우 리다이렉트 X
        	//needLocationHref = false; //개발, 스테이징 https 미적용 중이라서
            //2.모바일 접속인경우 모바일 URL로 팅김
            /*
            if(__IS_MOBILE){
                if(__USER_SELECT_DEVICE=="tablet"){
                    if(hostname != __PC_DOMAIN){
                        needLocationHref = true;
                        hostname = __PC_DOMAIN;
                    }
                }else if(__USER_SELECT_DEVICE=="mobile"){
                    if(hostname != __MOBILE_DOMAIN){
                        needLocationHref = true;
                        hostname = __MOBILE_DOMAIN;
                    }
                }else{//아무 설정이 없는경우 모바일은 모바일 사이트로 이동
                    if(hostname != __MOBILE_DOMAIN){
                        needLocationHref = true;
                        hostname = __MOBILE_DOMAIN;
                    }
                }
            }else{
                if(__USER_SELECT_DEVICE=="tablet"){
                    if(hostname != __PC_DOMAIN){
                        needLocationHref = true;
                        hostname = __PC_DOMAIN;
                    }
                }else if(__USER_SELECT_DEVICE=="mobile"){
                    if(hostname != __MOBILE_DOMAIN){
                        needLocationHref = true;
                        hostname = __MOBILE_DOMAIN;
                    }
                }
            }
        	*/

        }
        
        if(needLocationHref){            
    	
						location.href="https://"+hostname+location.pathname+location.search;
						//location.href=protocol+"//"+hostname+location.pathname+location.search;
			
        }
    })();

}catch(e){console.log('http >> https redirect error.. ', e);}
//PC버전 보기, MOBILE버전 보기:E


//중복로그인 체크 기능:S

</script>
	
	
	<!-- myasset -->
	<link rel="stylesheet" type="text/css" href="/WEB-APP/webponent/thirdParty/jquery/jquery-ui-1.10.2.custom.css" />
<link rel="stylesheet" type="text/css" href="/WEB-APP/webponent/tab/tab.css" />
<link rel="stylesheet" type="text/css" href="/WEB-APP/webponent/dialog/dialog.css" />
<link rel="stylesheet" type="text/css" href="/WEB-APP/webponent/dialog/layerlink.css" />
<link rel="stylesheet" type="text/css" href="/WEB-APP/webponent/calendar/css/calendar.css" />

				<script type="text/javascript">
					function getDevice(){
						return "pc";
					}
				</script>
			
<script type="text/javascript" src="/WEB-APP/webponent/thirdParty/jquery/jquery-1.11.3.min.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/thirdParty/jquery/jquery-ui-1.10.2.custom.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/ci/agent.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/ci/util.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/ci/ui.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/ci/DataSet.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/tab/tab.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/dialog/dialog.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/dialog/layerlink.js"></script>
<script type="text/javascript" src="/WEB-APP/webponent/calendar/calendar.js"></script>
<script type="text/javascript" src="/myasset/common/js/myasset.ui.js?v=20160429"></script>

	
	<script type="text/javascript" src="/WEB-APP/webponent/thirdParty/jquery/jquery.bxslider.js"></script>	
		
	<link rel="stylesheet" type="text/css" href="/extern/researchPortal/common/css/css.css?=20170605" />
<script type="text/javascript" src="/myasset/common/js/myasset.util.js?v=20170112"></script>
<script type="text/javascript" src="/myasset/common/js/myasset.layer.js?v=20170202"></script>
<script type="text/javascript" src="/myasset/common/js/myasset.loader.js?v=20160429"></script>
<script type="text/javascript" src="/common/security/security.js?v=20170223"></script>
<script type="text/javascript" src="/extern/researchPortal/common/js/util.js?=20170605"></script>
<script type="text/javascript" src="/extern/researchPortal/common/js/web.user.js?=20170605"></script>

	
</head>
<body>
	<!-- accessibility -->
	<div id="accNav">
		<p><a href="#container" class="skip">본문으로 바로가기</a></p>
	</div>
	<!-- //accessibility -->
 
	<!-- //wrap -->
	<div id="wrap">		 
		<!-- header -->	
		








<div id="header"> 
	<div class="inner">
		<div class="logo">
			<a href="https://www.myasset.com" target="_blank" class="link"><img src="/extern/researchPortal/common/img/top_logo2.png" alt=""></a>
			<h1><a href="/extern/researchPortal/RP_0000000_P1.cmd">티레이더인포</a></h1>
		</div>
		<h2 class="tit">유안타증권 티레이더 인포</h2>		
		<div class="lCon">
			<a href="#" class="btnGnb" id="left-panel-trigger-btn"><span class="ico">전체메뉴</span></a>
		</div>
		<div class="rCon">
			<a href="#" class="btnSns btnShare"><span class="ico"></span><em>공유하기</em></a>
			<a href="#" class="btnSch"><span class="ico"></span><em>검색</em></a>					
		</div>
	</div>
	<div class="fundSch">
		<div class="in">
			<label for="topSearch">통합검색</label>
			<div class="inputWrap">
				<form id="HEADER_FORM" name="rs_list" action="RP_0003000_P1.cmd" method="get">
					<input type="text" class="input" id="topSearch" name="keyword" placeholder="검색어를 입력해주세요!" value="">
					<a href="#" class="btn sch"><span class="ico"></span><em>검색</em></a>
				</form>
			</div>
		</div>
	</div>
	
	<!-- all menu -->
	<div class="gnbWrap">
		<div class="titWrap">
			<h1 class="logo"><a href="/extern/researchPortal/RP_0000000_P1.cmd">유안타증권 투자정보포털 티레이더 인포</a></h1>
		</div>
		<div class="inner">
			<div class="scroll">
				<ul class="menu">
					
								<li class="mm m1">
									<a href="/extern/researchPortal/RP_0100000_P1.cmd"><span>투자전략</span></a>
					
											<div class="subWrap">
											<ul>
					
											<li><a href="/extern/researchPortal/RP_0100000_P1.cmd"><span>주식시장분석</span></a></li>
					
											<li><a href="/extern/researchPortal/RP_0101000_P1.cmd"><span>경제/펀드분석</span></a></li>
					
											<li><a href="/extern/researchPortal/RP_0102000_P1.cmd"><span>파생상품분석</span></a></li>
					
											<li><a href="/extern/researchPortal/RP_0103000_P1.cmd"><span>일일체크포인트</span></a></li>
					
											<li><a href="/extern/researchPortal/RP_0104000_P1.cmd"><span>지표캘린더</span></a></li>
					
											<li><a href="/extern/researchPortal/RP_0105000_P1.cmd"><span>투자속보</span></a></li>
					
									</ul>
					
											
									</div>
								</li>
					
								<li class="mm m2">
									<a href="/extern/researchPortal/RP_0200000_P1.cmd"><span>이슈체크</span></a>
					
								<li class="mm m3">
									<a href="/extern/researchPortal/RP_0300000_P1.cmd"><span>기업/산업 분석</span></a>
					
											<div class="subWrap">
											<ul>
					
											<li><a href="/extern/researchPortal/RP_0300000_P1.cmd"><span>기업분석</span></a></li>
					
											<li><a href="/extern/researchPortal/RP_0301000_P1.cmd"><span>산업분석/동향</span></a></li>
					
									</ul>
					
											
									</div>
								</li>
					
								<li class="mm m4">
									<a href="/extern/researchPortal/RP_0400000_P1.cmd"><span>China 투자정보</span></a>
					
								<li class="mm m5">
									<a href="/extern/researchPortal/RP_0500000_P1.cmd"><span>Hot Place</span></a>
					
								<li class="mm m6">
									<a href="/extern/researchPortal/RP_0700000_P1.cmd"><span>리서치 VOD</span></a>
					
				</ul>
				<a href="#" class="btn allMenu">전체메뉴<span class="ico"></span></a>
				<!-- 전체 메뉴 : PC전용 -->
				<div class="allMenuArea">				
					<h2>전체메뉴</h2>
					<div class="allMenuInfo">
						<ul class="row"><!-- row의 li 갯수는 꼭 5개로 맞춰주세요. 메뉴가 없을경우 빈 값으로 넣어주세요. -->
						
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0100000_P1.cmd">투자전략</a></strong>										
							
													<ul class="allMenuSub">
							
												<li><a href="/extern/researchPortal/RP_0100000_P1.cmd">주식시장분석</a></li>
							
												<li><a href="/extern/researchPortal/RP_0101000_P1.cmd">경제/펀드분석</a></li>
							
												<li><a href="/extern/researchPortal/RP_0102000_P1.cmd">파생상품분석</a></li>
							
												<li><a href="/extern/researchPortal/RP_0103000_P1.cmd">일일체크포인트</a></li>
							
												<li><a href="/extern/researchPortal/RP_0104000_P1.cmd">지표캘린더</a></li>
							
												<li><a href="/extern/researchPortal/RP_0105000_P1.cmd">투자속보</a></li>
							
												</ul>
							
										</li>
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0200000_P1.cmd">이슈체크</a></strong>										
							
										</li>
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0300000_P1.cmd">기업/산업 분석</a></strong>										
							
													<ul class="allMenuSub">
							
												<li><a href="/extern/researchPortal/RP_0300000_P1.cmd">기업분석</a></li>
							
												<li><a href="/extern/researchPortal/RP_0301000_P1.cmd">산업분석/동향</a></li>
							
												</ul>
							
										</li>
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0400000_P1.cmd">China 투자정보</a></strong>										
							
										</li>
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0500000_P1.cmd">Hot Place</a></strong>										
							
										</li>
							
											</ul>
							
												<ul class="row">
											
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0600000_P1.cmd">카드  Report</a></strong>										
							
										</li>
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0700000_P1.cmd">리서치 VOD</a></strong>										
							
										</li>
							
										<li>
											<strong class="allsubTit"><a href="/extern/researchPortal/RP_0800000_P1.cmd">경제뉴스 Hot Pick</a></strong>										
							
										</li>
							
							
							
									<li></li>
							
									<li></li>
							
							
						
						</ul>
					</div>					
				</div>
				<!-- //전체 메뉴 : PC전용 -->
				<div class="topLink">
					<div class="in">
						<a href="https://www.tradar.co.kr" class="link2-1" target="_blank"><em>티레이더2.0</em><img src="/extern/researchPortal/common/img/mobile/top_link_ban1.png" alt="인공지능 종목추천시스템 티레이더"></a>
						<a href="/myasset/fundradar/FR_0000000_M2.cmd" class="link2-2" target="_blank"><em>펀드레이더</em><img src="/extern/researchPortal/common/img/mobile/top_link_ban2.png" alt="펀드투자관리 토탈서비스 펀드레이더"></a>
					</div>
				</div>
				<div class="etc">고객지원센터<a href="tel:1588-2600">1588-2600</a></div>
			</div>
		</div>				
		<a href="#" class="close ico"></a>
	</div>
	
	<!-- // all menu -->
</div>
<script type="text/javascript">

	$(document).ready(function() {
		
		// 검색처리
		$('#topSearch').on("keydown", function(event) {
			if ( event.keyCode == 13 ) {
				// 검색어 처리
				
				var keyword = $('#topSearch').val();
				$('#HEADER_FORM').submit();
			}
		});
		
		
		$('.fundSch .btn').on("click", function() {
			var keyword = $('#topSearch').val();
			$('#HEADER_FORM').submit();
		});
		
		
	});


</script>		
		<!-- //header -->
				
		<!-- container -->	
		<div id="container" class="main"><!-- 서브일때는 클래스 sub로 넣어주세요 -->
			<!-- title -->
					
					<div class="mainVb">
						<ul class="bxslider">
							<li style="background-image:url('/extern/researchPortal/common/img/main_vb_im01.jpg');"><a href="#"></a></li>
							<li style="background-image:url('/extern/researchPortal/common/img/main_vb_im02.jpg');"><a href="#"></a></li>
						</ul>
					</div>
									
			<!-- //title -->						
			<!-- content -->
			<div id="content" class="clearfix">
				<!DOCTYPE html>






<script type="text/javascript">		

		// 메인베너 생성
		$(document).ready(function() {
			
			
		});


		// 기본이벤트
		function showlist() {
			var tabObj1 = $('#tm1');			
			
			var class1 = tabObj1.attr("class");
			
			var menuid = "6";
			var title  = "오늘의 리포트";
			
			if ( class1.indexOf("on") > -1 ) {				
				menuid = "6";
				title = "오늘의 리포트 선택";
			} else {				
				menuid = "7";
				title = "조회수 상위 선택";
			}
			
			ci.dialog.open({
				id: "RP_0000000_P1",
				title : title,
				url : '/extern/researchPortal/RP_0000000_L1.cmd?kind=' + menuid,
				focus : $(this),
				width : 512,
				height: 670,
				closebutton : true,
				modal: true,
				close : function () {
					
				}    							
			});
				
		}
		
		function gotourl(kind, seq, url,cd006,cd007,cd008) {
			
			
			//alert ( "cd006[" + cd006 + "] cd007[" + cd007 + "] cd008[" + cd008 + "]" );
			
			var menuid = "";
			// 이벤트 유무
			if (kind != 'evt') {
				// 리스트 유무
				if ( seq == '' ) {
					
					switch(kind) {
						case '0':
							// 투자전략
							menuid = "RP_0100000_P1";
							break;
						case '1':
							// 이슈분석
							menuid = "RP_0100000_P1";
							break;
						case '2':
							// 주식시장분석
							menuid = "RP_0100000_P1";
							break;
						case '3':
							// 애널리스트 이슈체크
							menuid = "RP_0200000_P1";
							break;
						case '4':
							// HotPlace
							menuid = "RP_0500000_P1";
							break;
						case '5':
							// 경제뉴스핫픽
							menuid = "RP_0800000_P1";
							break;
						case '6':
							// 오늘의 리포트
							menuid = "RP_0001000_P1";
							break;
						case '7':
							// 조회수 상위
							menuid = "RP_0001000_P1";
							break;
						case '8':
							// 카드 Report							
							menuid = "RP_0600000_P1";
							break;
						case '9':
							// 리서치 VOD
							menuid = "RP_0700000_P1";
							break;
						case '10':
							// 기업분석
							menuid = "RP_0300000_P1";
							break;
							
						default:
			
							// 기본값은 메인
							menuid = "RP_0000000_P1";
					}
					
					//location.href = resportal.util.getMenuId(cd006,cd007,cd008) + ".cmd";
					location.href = menuid + ".cmd";
					
				} else {
					// 상세뷰화면
					
					menuid = resportal.util.getMenuId(cd006,cd007,cd008);
					
					if (menuid == "RP_0600000_P1") {
						// card report 뷰						
						location.href = "RP_0601000_P1.cmd?menuid=" + menuid + "&res_seq=" + seq;
					} else if (menuid == "RP_0300000_P1") {
						location.href = "RP_0302000_P1.cmd?menuid=" + menuid + "&res_seq=" + seq;
					} else if (menuid == "RP_0800000_P1") {
						// 경제뉴스핫픽
						window.open (url);
						
					} else if (menuid == "RP_0700000_P1") {
						
						/*
						var obj = null;
						if (kind == "6") {
							obj = $("#todaylist");
						} else if (kind == "7") {
							obj = $("#qrycountlist");
						}
						*/
						
						window.open(url);
							
						
					} else {
						location.href = "RP_0001000_P1.cmd?menuid=" + menuid + "&res_seq=" + seq;
					}
					
				}
				
			} else {
				// 이벤트 처리
				location.href = url;
			}
			
			
					
			
			
		}		
</script>

<!-- leftArea -->
<div class="leftArea">
	<!-- ad top -->
	<div class="adTopBan">
		<img src="/extern/researchPortal/common/img/mobile/main_ad_top.png" alt="">
	</div>
	<!-- ad top -->
	<!-- info -->
	<div class="info clearfix">
		<div class="fL">
			<h3 class="tit">투자전략</h3>
			<div class="thum">
				
				<a href="javascript:gotourl('0','123945','','RB','RB09','');" class="im">	
					<p class="txt">[Quant Recipe] 주전과 용병만으로는 이길 수 없다</p>
					<span class="cDim"></span>
					<img src="https://file.myasset.com/sitemanager/upload/2017/0731/07245719/quant analyst.png" alt="">
				</a>
				
			</div>	
		</div>
		<div class="fR">
			<h3 class="tit">이슈분석</h3>
			<div class="thum">
				
				<a href="javascript:gotourl('1','123896','','RH','RH01','');" class="im">	
					<p class="txt">Weekly Macro(7월4주)-예상경로로 성장중인 한국경제</p>
					<span class="cDim"></span>
					<img src="https://file.myasset.com/sitemanager/upload/2017/0728/08244433/economist.png" alt="">
				</a>
				
			</div>		
		</div>
	</div>
	<!-- //info -->

	<!-- issue -->
	<div class="conBox1 issue">
		<h3 class="titH">issue & comment</h3>
		<ul>
			
				<li><a href="javascript:gotourl('2','123958','','RE','RE05','');"><span class="cate">Instant Comment</span>KOSPI 하락, 원인과 전망</a><span class="date">07.31</span></li>
			
				<li><a href="javascript:gotourl('2','123950','','RE','RE08','');"><span class="cate">산업동향</span>조선기계건설:주간 Check Point (2017/07/31)</a><span class="date">07.31</span></li>
			
				<li><a href="javascript:gotourl('2','123964','','RE','RE10','');"><span class="cate">투자속보</span>애널리스트 레포트 UP&amp;DOWN</a><span class="date">07.31</span></li>
			
				<li><a href="javascript:gotourl('2','123956','','CH','CH03','');"><span class="cate">후강퉁 데일리</span>YUANTA China Morning Post (2017.07.31)</a><span class="date">07.31</span></li>
			
				<li><a href="javascript:gotourl('2','123932','','RE','RE02','');"><span class="cate">산업분석</span>지주회사:Weekly(7/24~7/28) : 구리 가격 상승 덕에 LS로 기관투자자 수급 집중</a><span class="date">07.28</span></li>
			
		</ul>
		<a href="javascript:gotourl('2','','','','','');" class="ui"><span class="blind">issue & comment 더보기</span></a>
	</div>
	<!-- //issue -->

	<!-- ad : 배너 비노출시 adBan에 클래스 "off"를 넣어주세요.-->
	<div class="ad1 adBan">
		<ul class="bxslider"><!-- 배너 이미지를 변경할때 인라인으로 넣어주세요. -->		
					
		
		</ul>
	</div>
	<!-- //ad -->
	
	<!-- issue ban -->
	<div class="issueCmt">
		<dl>
			<dt>애널리스트 이슈 체크</dt>
			
			<dd><a href="javascript:gotourl('3','123951','','RP','RP01','RP01A');"><p class="tit">2분기 반도체 수출물량 사상최대.. 3분기에도 호조세 이어질 듯</p><p class="date">2017.07.31</p></a></dd>
			
		</dl>
	</div>
	<!-- //issue ban -->

	<!-- place -->
	<div class="place">	
		<div class="in">
			<div class="titWrap">
				<h3 class="titH">HOT Place</h3>
				<a href="javascript:gotourl('4','','','','','');" class="btnMore">YUANTA 순매수 상위종목 분석</a>
			</div>						
			<div class="tag">
			
						<a href="javascript:gotourl('4','123909','005930','RP','RP01','RP01B');" class="odd"><em>삼성전자</em></a>
			
						<a href="javascript:gotourl('4','123908','000660','RP','RP01','RP01B');" class="even"><em>SK하이닉스</em></a>
			
				
			</div>			
			<span class="date">2017/07/28 기준</span>	
		</div>
	</div>
	<!-- //place -->

	<!-- news -->
	<div class="conBox1 news">
		<div class="titWrap">
			<h3 class="titH">경제뉴스<em class="point">Hot Pick</em></h3>
			<a href="javascript:gotourl('5','','','','','');" class="btnMore"><span class="blind">기업분석 </span>더보기</a>
		</div>
		<ul>
			
			<li><a href="javascript:gotourl('5','123920','http://news.mt.co.kr/mtview.php?no=2017072713591410860&type=2&sec=finance&pDepth2=Ftotal','RP','RP01','RP01C');">전자담배로 맞불 KT&G, 하반기 꽃피는 고배당株</a><span class="date">07.28</span></li>
			
			<li><a href="javascript:gotourl('5','123919','2조원대 자사주 매입·소각 발표 "연내 1차례 더"… 유통주식 감소로 가치 올리고 주가 방어','RP','RP01','RP01C');">'25조+α' 사라지는 삼성전자 자사주 효과는?</a><span class="date">07.28</span></li>
			
			<li><a href="javascript:gotourl('5','123918','http://news.mt.co.kr/mtview.php?no=2017072714170991276&type=2&sec=finance&pDepth2=Ftotal','RP','RP01','RP01C');">실적 롤러코스터 올라탄 정유사, "유가 탓에"</a><span class="date">07.28</span></li>
			
		</ul>			
	</div>
	<!-- //news -->
</div>
<!-- //leftArea -->

<!-- rightArea -->
<div class="rightArea">
	<!-- report -->
	<!-- tab -->
	<div class="tabWrap report">
		<!-- TAB 셀렉터 : START -->
		<ul class="tab-menu">
			<li class="on tm1" id="tm1">
				<a href="#" rel="#tabType01">
				
					<span class="date">2017.07.31</span>
					<span class="tit">오늘의 리포트</span>
					<span class="icoWrap">14</span>					
				</a>
			</li>
			<li class="tm2" id="tm2">
				<a href="#" rel="#tabType02">
					<span class="tit">조회수 상위<br> 리포트</span>
					<span class="icoWrap"><em class="ico">더보기</em></span>
				</a>
			</li>
		</ul>
		<!-- TAB 셀렉터 : END -->

		<!-- TAB 폐널 : START -->
		<div class="tab-panel">
			<div id="tabType01" class="on panel">
				<ul class="list"><!-- 다음 리스트 목록은 탭메뉴에 나온 수치만큼 나와야함 -->
				
					<li><a href="javascript:gotourl('6','123959','','CH','CH03','');" id="todaylist"><span class="cate">China 투자정보</span>차이나데일리 (2017.07.31)</a></li>
				
					<li><a href="javascript:gotourl('6','123956','','CH','CH03','');" id="todaylist"><span class="cate">China 투자정보</span>YUANTA China Morning Post (2017.07.31)</a></li>
				
					<li><a href="javascript:gotourl('6','123950','','RE','RE08','');" id="todaylist"><span class="cate">산업동향</span>조선기계건설:주간 Check Point (2017/07/31)</a></li>
				
					<li><a href="javascript:gotourl('6','123947','본 자료를 참고하여 주시기 바랍니다.본 내용은 투자 판단의 참고 사항이며, 투자판단의 최종 책임은 본 게시물을 열람하시는 이용자에게 있습니다','RB','RB06','');" id="todaylist"><span class="cate">모닝스냅샷</span>Yuanta Morning Snapshot (07.31)</a></li>
				
					<li><a href="javascript:gotourl('6','123946',' Quant Idea (1) - 반도체의 독주는 멈췄다 - 삼성전자, SK하이닉스의 주도력은 Revision과 Momentum으로부터 나옴 - 이익전망치의 상향 ','RB','RB01','RB01A');" id="todaylist"><span class="cate">데일리시황</span>주전과 용병만으로는 이길 수 없다 [요약]</a></li>
				
					<li><a href="javascript:gotourl('6','123945','','RB','RB09','');" id="todaylist"><span class="cate">퀀트분석</span>[Quant Recipe] 주전과 용병만으로는 이길 수 없다</a></li>
				
					<li><a href="javascript:gotourl('6','123944','','RB','RB12','');" id="todaylist"><span class="cate">Daily Issues</span>Daily Market Issues (17.07.31)</a></li>
				
					<li><a href="javascript:gotourl('6','123943','','RE','RE01','');" id="todaylist"><span class="cate">기업분석</span>[BNK금융지주] 예상보다 양호한 실적, 주가 상승에 동행할 것</a></li>
				
					<li><a href="javascript:gotourl('6','123941','','RE','RE01','');" id="todaylist"><span class="cate">기업분석</span>[풍산] 2Q17 Review: 긍정적 외부환경 속 내부적 변화</a></li>
				
					<li><a href="javascript:gotourl('6','123940','','RE','RE01','');" id="todaylist"><span class="cate">기업분석</span>[현대제철] 2Q17 Review: 환경의 변화를 전략의 변화로</a></li>
				
					<li><a href="javascript:gotourl('6','123939','','RB','RB10','');" id="todaylist"><span class="cate">글로벌시장지표</span>글로벌 시장 지표 (17.07.31)</a></li>
				
					<li><a href="javascript:gotourl('6','123938','','RB','RB04','RB04A');" id="todaylist"><span class="cate">주식시장지표</span>주식시장지표 (17.07.31)</a></li>
				
					<li><a href="javascript:gotourl('6','123937','','RC','RC02','');" id="todaylist"><span class="cate">선물옵션지표</span>선물옵션 시장지표 (17.07.31)</a></li>
				
					<li><a href="javascript:gotourl('6','123936','','RF','RF03','RF03C');" id="todaylist"><span class="cate">경제캘린더</span>경제지표 및 이벤트 캘린더 (17.07.31)</a></li>
				
				</ul>
			</div>
			<div id="tabType02" class="panel">
				<ul class="list"><!-- 리포트 목록 다 뿌려져야 함 -->
				
					<li><a href="javascript:gotourl('7','122912','','RB','RB02','RB02A');" id="qrycountlist"><span class="cate">전략하우스뷰</span>[17년 하반기 투자전략] 상반기 달라진 것과 하반기 달라질 것</a></li>
				
					<li><a href="javascript:gotourl('7','122501','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[신세계푸드] 사업부 효율화 + 전방업체 성장</a></li>
				
					<li><a href="javascript:gotourl('7','123338','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[한화ACPC스팩] 다양한 포트폴리오를 보유한 파인다이닝 업체</a></li>
				
					<li><a href="javascript:gotourl('7','123038','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[삼성전기] 10만원이 아닌 10조원 시대가 열립니다!</a></li>
				
					<li><a href="javascript:gotourl('7','122869','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[S-Oil] 2017년 2분기 실적 쇼크가 기회인 이유?</a></li>
				
					<li><a href="javascript:gotourl('7','122980','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[금호석유] 2017년 2분기 크게 기대하지 말자!</a></li>
				
					<li><a href="javascript:gotourl('7','122053','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[강원랜드] 1Q17 매출감소 현상 발생</a></li>
				
					<li><a href="javascript:gotourl('7','122210','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[이노션] 이노션(214320)</a></li>
				
					<li><a href="javascript:gotourl('7','122950','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[풍산] 신뢰를 찾아가고 있는 시간</a></li>
				
					<li><a href="javascript:gotourl('7','122686','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[휴켐스] 2017년 2분기 사상 최대치 경신 가능</a></li>
				
					<li><a href="javascript:gotourl('7','123446','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[솔브레인] 17년 2분기 Preview</a></li>
				
					<li><a href="javascript:gotourl('7','122614','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[POSCO] 전편보다 재미있는 속편이 기다리고 있다</a></li>
				
					<li><a href="javascript:gotourl('7','122148','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[코오롱플라스틱] 코오롱플라스틱(138490):주가 방향전환은 언제쯤일까?</a></li>
				
					<li><a href="javascript:gotourl('7','121909','','RE','RE08','');" id="qrycountlist"><span class="cate">산업동향</span>Chemicals Weekly Data       (2017.5.10일, 엑셀클릭):중국 석화제품 가격 좀 더 떨어질 수 있다!</a></li>
				
					<li><a href="javascript:gotourl('7','121877','','RE','RE02','');" id="qrycountlist"><span class="cate">산업분석</span>문재인 대통령 당선자의 공약 분석: 섹터별 전망</a></li>
				
					<li><a href="javascript:gotourl('7','122056','','RE','RE08','');" id="qrycountlist"><span class="cate">산업동향</span>Chemicals Weekly Data        (2017.5.16일, 엑셀클릭):5/25일, OPEC 추가로 감산할까?</a></li>
				
					<li><a href="javascript:gotourl('7','121836','','RE','RE08','');" id="qrycountlist"><span class="cate">산업동향</span>조선기계건설:주간 Check Point (2017/05/08)</a></li>
				
					<li><a href="javascript:gotourl('7','122049','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[한화생명] 양호한 투자이익으로 어닝 서프라이즈</a></li>
				
					<li><a href="javascript:gotourl('7','122048','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[SK] 1Q Review : E&amp;S 실적 개선을 확인</a></li>
				
					<li><a href="javascript:gotourl('7','122576','','RE','RE01','');" id="qrycountlist"><span class="cate">기업분석</span>[CJ CGV] 2Q17 중국 및 4DX 호실적 기대</a></li>
				
				</ul>
			</div>
			<!-- 다음의 "더보기버튼"은 pc에서만 팝업으로 띄워주세요. -->
			
				<a href="javascript:showlist();" class="btn more"><span class="ico"></span><em>더보기</em></a>
			
		</div>
		<!-- TAB 폐널 : END -->
	</div>
	<!-- //tab -->
	<!-- //report -->
	
	<!-- ad : 배너 비노출시 adBan에 클래스 "off"를 넣어주세요.-->
	
	<!-- //ad -->

	<!-- report2 -->
	<div class="conBox1 report2 clearfix">
		<div class="fL">
			<div class="titWrap">
				<h3 class="tit">카드 Report</h3>
				<a href="javascript:gotourl('8','','','','','');" class="btnMore"><span class="blind">CARD Report </span>더보기</a>
			</div>
			
			<div class="thum">				
				<a href="javascript:gotourl('8','123965','','RP','RP01','RP01D');">									
					<span class="ico play"></span>
					<span class="cDim"></span>
					<img src="http://file.myasset.com/sitemanager/upload/2017/0731/11241135/SW.png" alt="">					
				</a>
			</div>
			<a href="javascript:gotourl('8','123965','','RP','RP01','RP01D');" class="txt">KT, 다시 경험하지 못 할 저평가</a>				
			
		</div>
		<div class="fR">
			<div class="titWrap">
				<h3 class="tit">리서치 VOD</h3>
				<a href="javascript:gotourl('9','','','','','');" data="resvod" class="btnMore"><span class="blind">Research VOD </span>더보기</a>
			</div>
			
			<div class="thum">				
				<a href="https://youtu.be/SIzc3Cn9CGE" target="_blank">									
					<span class="ico play"></span>
					<span class="cDim"></span>
					<span class="im"></span>					
					<img src="http://file.myasset.com/sitemanager/upload/2017/0725/17243303/52014816925995427.png" alt=""> <!-- no image -->
				</a>
			</div>
			<a href="javascript:gotourl('9','123798','https://youtu.be/SIzc3Cn9CGE','RP','RP01','RP01E');" class="txt">테라세미콘 종목 분석</a>	
			
		</div>
	</div>
	<!-- //report2 -->
	
	<!-- analysis -->
	<div class="conBox1 analysis">
		<div class="titWrap">
			<h3 class="tit">기업분석</h3>
			<a href="javascript:gotourl('10','','','','','');" class="btnMore"><span class="blind">기업분석 </span>더보기</a>		
		</div>
		<ul>
			
			<li>
				<a href="javascript:gotourl('10','123943','','RE','RE01','');">
					<strong class="tit">BNK금융지주</strong>
					<p class="txt">예상보다 양호한 실적, 주가 상승에 동행할 것</p>
					<p class="date"></p>
					
					
						
							<span class="badge st1">
								<em>BUY</em>
							</span>
						
						
						
						
						
						
						
						
						
						
					
						
					</span>						
				</a>
			</li>			
			
			<li>
				<a href="javascript:gotourl('10','123941','','RE','RE01','');">
					<strong class="tit">풍산</strong>
					<p class="txt">2Q17 Review: 긍정적 외부환경 속 내부적 변화</p>
					<p class="date"></p>
					
					
						
							<span class="badge st1">
								<em>BUY</em>
							</span>
						
						
						
						
						
						
						
						
						
						
					
						
					</span>						
				</a>
			</li>			
			
		</ul>
	</div>
	<!-- //analysis -->

	<!-- ad : 배너 비노출시 adBan에 클래스 "off"를 넣어주세요.-->
	
	<!-- //ad -->
	
	<!-- ad : pc전용  : 170703 추가 -->
	<div class="ad4 adBan">		
		<ul class="bxslider"><!-- 배너 이미지를 변경할때 인라인으로 넣어주세요. -->		
					
		
		</ul>
	</div>
	<!-- //ad : pc전용 -->

</div>
<!-- //rightArea -->
				<!-- 주문 툴팁 -->
				<div class="layer-link hide" id="divOrder">
					<div class="ar-area ar-bottom center"></div>
					<ul><li><a href="#" class="btn1" id="order">주문</a></li></ul>
					<div class="layer-close"><a href="#" class="layer-close-a"><span>닫기</span></a></div>
				</div>
				<!-- //주문 툴팁 -->
			</div>
			<!-- //content -->
		</div>
		<!-- //container -->
			
		<!-- footer -->
	    

<div id="footer">
	<div class="inner">
		<div>
			<ul class="menu1">
				<li><strong>고객지원센터</strong><span><a href="tel:1588-2600">1588-2600</a></span></li>
				<li><a href="/myasset/customer/beginner/CU_0104000_T1.jsp" target="_blank">지점안내</a></li>
			</ul>
			<ul class="menu2">
				<li><a href="/myasset/hello/open/HU_0100000_P1.cmd?1501046867184" target="_blank">스마트계좌개설</a></li>
				<li><a href="/myasset/static/customer/marketing/CU_0303009_P1.jsp" target="_blank">티레이더M</a></li>
				<li><a href="/myasset/customer/beginner/CU_0104000_T1.jsp" target="_blank">지점안내</a></li>
			</ul>
			<div class="snsWrap"><a href="http://blog.naver.com/tysmyasset" class="sns1" target="_blank"><em>유안타증권 블로그</em><span class="ico"></span></a><a href="https://ko-kr.facebook.com/2016YuantaKorea" class="sns2" target="_blank"><em>유안타증권 페이스북</em><span class="ico"></span></a></div>
			<p class="call">
				<strong class="tit">고객지원센터</strong>
				<a href="tel:1588-2600">1588-2600</a> 
			</p>
			<p class="copy">COPYRIGHT ⓒ Yuanta Securities Korea Co., Ltd. ALL RIGHT RESERVED.</p>
		</div>
	</div>
</div>

<!-- header share popup -->
<div class="popShareWrap" tabindex="0">
	<h2>공유하기</h2>
	<div class="in">
		<div class="shareWrap">
			<ul>
				<li class="sns1"><a href="#" onclick="kakaoShare();return false;"><span class="ico"></span><span class="name">카카오톡</span></a></li>
				<li class="sns2"><a href="#" onclick="facebookShare();return false;"><span class="ico"></span><span class="name">페이스북</span></a></li>
				<li class="sns3"><a href="#" onclick="twitterShare();return false;"><span class="ico"></span><span class="name">트위터</span></a></li>
				<li class="sns4"><a href="#" onclick="lineShare();return false;"><span class="ico"></span><span class="name">라인</span></a></li>
				<li class="sns5"><a href="#"><span class="ico"></span><span class="name">텔레그램</span></a></li>
				<li class="sns6"><a href="#" onclick="urlCopy();return false;"><span class="ico"></span><span class="name">URL복사</span></a></li>
				<li class="sns7"><a href="#" onclick="kakaostoryShare();return false;"><span class="ico"></span><span class="name">카카오스토리</span></a></li>				
			</ul>
		</div>
		<div class="btn_btm"><a href="#" class="close">닫기</a></div>
	</div>
</div>
<!-- //header share popup -->

<!-- top -->
<a href="#" class="quick_top" title="맨 위로 이동"><span class="ico"></span>Top</a>
<!-- //top -->

		<script src="//developers.kakao.com/sdk/js/kakao.min.js"></script>

<script>

	var mobile = (/iphone|ipad|ipod|android/i.test(navigator.userAgent.toLowerCase()));
	
	if (mobile) {
		var userAgent = navigator.userAgent.toLowerCase();
		// 유저에이전트를 불러와서 OS를 구분합니다.
		if ((userAgent.search("iphone") > -1) || (userAgent.search("ipod") > -1)|| (userAgent.search("ipad") > -1)){
			$("#sms").remove();
		}
	} 
	
	var msg = "";
	var title = $("#og_title").attr("content");
	var image = $("#og_image").attr("content");
	var description = $("#og_description").attr("content");
	var url = $("#og_url").attr("content");
	
	__INSIDE_IP = "false";
	if(__INSIDE_IP  == "true"){		
		//내부망 스크립트 막음
		msg = "내부망에서는 공유하기가 불가능합니다.";
	}else{
		var script = document.createElement("script");
		script.src = 'https://connect.facebook.net/ko_KR/all.js';
		script.async = 'true';
		var domel = document.getElementsByTagName('script')[0];
		domel.parentNode.insertBefore(script,domel);
		
		setTimeout(function(){
			window.fbAsyncInit = function() {
			    FB.init({
			      appId      : '1033128943420258',
			      xfbml      : true,
			      version    : 'v2.5'
			    });
			  };

			  (function(d, s, id){
			     var js, fjs = d.getElementsByTagName(s)[0];
			     if (d.getElementById(id)) {return;}
			     js = d.createElement(s); js.id = id;
			     js.src = "//connect.facebook.net/en_US/sdk.js";
			     fjs.parentNode.insertBefore(js, fjs);
			   }(document, 'script', 'facebook-jssdk'));
		},1000);
		
	}
	
	
	function facebookShare(){
		
		var title = $("#og_title").attr("content");
		var image = $("#og_image").attr("content");
		var description = $("#og_description").attr("content");
		var url = $("#og_url").attr("content");
		
		if(msg!="") {
	 		alert(msg);
	 		return false;
	 	}
		
		var share = {
	        method: 'stream.share',
	        caption: title,
	        description: description,
	        picture: image,
	        href: url
	    };
	    
	    
	    /*
	    var share = {
	        method: 'feed',
	        link: url,
	        caption: title,
	        description: description,
	        picture: image
	    };
	    */
	    
	 
	    FB.ui(share, function(response) { console.log(response); });
	}
	 	
	function naverShare(){
		
		var title = $("#og_title").attr("content");
		var image = $("#og_image").attr("content");
		var description = $("#og_description").attr("content");
		var url = $("#og_url").attr("content");
		
		if(msg!=""){
	 			alert(msg);
	 			return false;
	 		}
		window.open("http://share.naver.com/web/shareView.nhn?url="+url+"&title="+description,"","width=400 height=500");
	}
	
	function twitterShare(){
		
		var title = $("#og_title").attr("content");
		var image = $("#og_image").attr("content");
		var description = $("#og_description").attr("content");
		var url = $("#og_url").attr("content");
		
		if(msg!=""){
	 			alert(msg);
	 			return false;
	 		}
	    //var link = "https://local.myasset.com";
	    window.open("http://twitter.com/share?url="+encodeURIComponent(url)+"&text="+description,"pop","width=700, height=435");
	}
	
	
	
	function urlCopy(){
		var link = url;
		var IE=(document.all)?true:false;
		if (IE) {
			if(confirm("주소를 클립보드에 복사하시겠습니까?")){
				window.clipboardData.setData("Text", link);
			} 
		}else {
			temp = prompt("Ctrl+C를 눌러 클립보드로 복사하세요", link);
		}
	}
	
	function kakaoShare(){
	
		var title = $("#og_title").attr("content");
		var image = $("#og_image").attr("content");
		var description = $("#og_description").attr("content");
		var url = $("#og_url").attr("content");
		var time = Date.now();
	
		if ( title == undefined || title == "" ) title = "유안타증권 투자정보 포털 - 티레이더 인포";		
		if ( image == undefined || image == "" ) image = "https://www.myasset.com/myasset/common/img/snsShareTemplet.png";
		if ( description == undefined || description == "" ) description = "유안타증권 투자정보 포털 - 티레이더 인포";		
		if ( url == undefined || url == "" ) url = "http://www.myasset.com/tradarinfo";
		if ( url.indexOf("?") > -1 ) {
			url += "&" + time;	
		} else {
			url += "?" + time;
		}
	
		Kakao.Link.sendTalkLink({
	        label: title,
	        image:{
	        	src : image,
	        	width:"380px",
	        	height:"280px"
	        },
	        webLink:{
	        	text : description,
	        	url : url
	        }
	      });
	}


	setTimeout(function(){
		Kakao.init('7357238e1f01b6c9bfdcc33c6de059e4');
	},500);
	function kakaostoryShare(){
		Kakao.Story.share({
			url: url,
		    text: title
	      });
	}

	
	
	function bandShare(){
		window.open("http://www.band.us/plugin/share?body="+title+"&route="+url, "", "width=410, height=540, resizable=no");
	}
	
	function lineShare(){
		window.open("http://line.me/R/msg/text/?"+title+" "+url, "", "width=410, height=540, resizable=no");	
	}
	
	function gogleShare() {
		window.open("https://plus.google.com/share?url="+url+"&t="+title, "", "width=410, height=540, resizable=no");
	   }


</script>

		<!-- //footer -->
	</div>
	<!-- //wrap -->
</body>	
</html>
