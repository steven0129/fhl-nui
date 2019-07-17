<!DOCTYPE html>
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta property="og:title" content="信望愛聖經工具"><meta property="og:type" content="website"><meta property="og:url" content="https://bkbible.fhl.net/~sean/bible/index.html"><meta property="og:image" content="static/images/FHLLOGO.png"><meta property="og:site_name" content="FHL信望愛聖經工具"><meta property="og:description" content=""><script src="NUI_files/jquery-3.js"></script><script src="NUI_files/jquery-ui.js"></script><style type="text/css">.bstw {
      font-family: "bstw";
    }

    @font-face {
      font-family: "bstw";
      src: url("static/font/open_han.ttf") format("trueType"), url("static/font/open_han.woff2") format("woff2"), url("static/font/open_han.svg") format("svg"), url("static/font/open_han.woff") format("woff");
    }</style><link rel="stylesheet" type="text/css" href="NUI_files/jquery-ui.css"><script src="NUI_files/react-0.js"></script><script src="NUI_files/linq.js"></script><script src="NUI_files/jquery.js"></script><script src="NUI_files/vue.js"></script><link rel="stylesheet" href="NUI_files/leaflet.css" integrity="sha512-puBpdR0798OZvTTbP4A8Ix/l+A4dHDD0DGqYW6RQ+9jxkRFclaxxQb/SJAWZfWAkuyeQUytO7+7N4QKrDh+drA==" crossorigin=""><script src="NUI_files/leaflet.js" integrity="sha512-nMMmRyTVoLYqjP9hrbed9S+FzjZHW5gY1TWCHA5ckwXZBadntCNs8kEqAWdrb9O7rxbCaA4lKTIWjDXZxflOcA==" crossorigin=""></script><script src="NUI_files/fhlmap.js"></script><script src="NUI_files/fhlmap_main.js"></script><script src="NUI_files/FHL.js"></script><script src="NUI_files/bible-constants.js"></script><script src="NUI_files/eachFitDo.js"></script><script src="NUI_files/UrlParameter.js"></script><script src="NUI_files/FhlUrlParameter.js"></script><title>信望愛聖經工具</title><link rel="shortcut icon" href="https://bible.fhl.net/NUI/static/images/FHLLOGO.ico" type="image/x-icon"><link rel="stylesheet" href="NUI_files/fhl.css"><link rel="stylesheet" href="NUI_files/font-awesome.css"><script src="NUI_files/jquery_002.js"></script><script src="NUI_files/processbar.js"></script><script src="NUI_files/audio.js"></script><link href="NUI_files/ob_api.css" rel="stylesheet"><link href="NUI_files/ob_table.css" rel="stylesheet"><script src="NUI_files/obphp.js"></script><script src="NUI_files/sephp_007.js"></script><script src="NUI_files/abvphp_api.js"></script><script src="NUI_files/fhl_api.js"></script><link href="NUI_files/search.css" rel="stylesheet"><script src="NUI_files/qsbphp.js"></script><script src="NUI_files/sephp_003.js"></script><script src="NUI_files/qsbphp_002.js"></script><script src="NUI_files/sephp_006.js"></script><script src="NUI_files/sephp.js"></script><script src="NUI_files/sephp_005.js"></script><script src="NUI_files/sephp_002.js"></script><script src="NUI_files/sephp_004.js"></script><script src="NUI_files/qsb.js"></script><script src="NUI_files/tsk.js"></script><script src="NUI_files/tsk_002.js"></script><script src="NUI_files/preach_api.js"></script><script src="NUI_files/audiobible_api.js"></script><script src="NUI_files/copyright_api.js"></script><!--[if IE]>
  <link rel="stylesheet" href="./static/libs/ie.css" type="text/css" media="screen, projection" />
  <![endif]--><style>#fhlInfoContent { height: 100%; }</style><script>var fhlUrlParameter = new FHL.FhlUrlParameter()
    var pageState;
    var currentSWVer = "1.2";
    var isfirstob; // ob 典藏用

    function setPageState(ps) {

      $(document).trigger('go', {
        chineses: ps.chineses,
        chap: ps.chap,
        sec: ps.sec
      });
      // 這個 go, 會使變數存起來, 下起開啟網頁還是會保留原本的 history
    }
    function pageStateInit() {
      pageState = {
        // 'Gen'
        engs: "Gen",
        // '創'
        chineses: "創",
        // 1
        chap: 1,
        // 1
        sec: 1,
        // bookIndex, book 這個先被用掉了.
        bookIndex: 1,
        // ['unv', 'svc']
        version: ["unv"],
        // 0
        strong: 0,
        // 0
        gb: 0,
        // book 別以為是 bookIndex, 因為 book 先被注釋用掉了 sc.php 參數
        book: 3, N: 0, k: "", cname: ["和合本"], realTimePopUp: 0, titleId: "fhlInfoComment",
        history: [{ chineses: "創", chap: 1 }], fontSize: 12, commentBackgroundChap: 1, commentBackgroundSec: 1,
        leftBtmWinShow: true, searchTitleMsg: "", audio: 0, swVer: currentSWVer,
        ispho: false, ispos: false
      };
    }

    function windowAdjust() {
      if (!document.mozFullScreen && !document.webkitIsFullScreen) {
        $("#mainWindow").css({ top: "40px" });
        //$("#bookSelectPopUp").css({top: "100px"});
      }

      /* for leftWindow height */
      var height = $(window).height() - $('#fhlTopMenu').height() - 12;
      if (document.mozFullScreen || document.webkitIsFullScreen)
        height += $('#fhlTopMenu').height();
      $('#fhlLeftWindow').css({ height: height + 'px' });

      $('#viewHistory').css({ top: $('#fhlLeftWindow').height() - $('#viewHistory').height() - 12 + 'px' });
      $('#versionSelect').css({ height: $('#fhlLeftWindow').height() - $('#settings').height() - $('#viewHistory').height() - 36 + 'px' });

      /* for MidWindow and fhlInfo height */

      //var mainWindow = document.querySelector("#mainWindow");
      height = $(window).height() - $('#fhlTopMenu').height() - $('#fhlToolBar').height() - 36 - 1;
      if (document.mozFullScreen || document.webkitIsFullScreen)
        height += $('#fhlTopMenu').height();

      $('#fhlMidWindow').css({
        height: height + 'px'
      });

      $('#fhlInfo').css({
        height: height + 'px'
      });

      /* for MidBottomWindow height */

      if ($("#fhlMidBottomWindowControl").hasClass('selected'))
        height -= ($("#fhlMidBottomWindow").height() + 12);

      $('#fhlLecture').css({
        height: height + 'px'
      });

      $('#fhlMidBottomWindow').css({ 'top': height + 12 + 'px' });

      /* for fhlMidWinow width */

      var width = $(window).width() - 24;

      if ($("#fhlLeftWindowControl").hasClass('selected'))
        width -= ($("#fhlLeftWindow").width() + 12);

      if ($('#fhlInfoWindowControl').hasClass('selected'))
        width -= ($("#fhlInfo").width() + 12);

      $("#fhlMidWindow").css({
        'width': width + 'px'
      });


      /* for fhlInfo width */

      var fhlInfoLeft = 10;
      if ($('#fhlInfoWindowControl').hasClass('selected')) {
        $('#fhlInfo').css({
          'left': $(window).width() - $('#fhlInfo').width() - 12 + 'px'
        });
      }
      else {
        $('#fhlInfo').css({
          'left': $(window).width() + 15 + 'px'
        });
      }

      /*  */
      $('#lecMain').scrollTop($('#lecMain').scrollTop() + $('#lecMain').find('.lec.selected').position().top - 80);
    }

    $(window).resize(function (e) {
      if (e.target == window) {
        windowAdjust();

        fhlLecture.reshape(pageState);//ps的全域即是 pageState, 只是這裡沒有傳過來, 只好偷存取全域的 snow-add
      }

    });

    $(function () {
      //fhlTopMenu.init(pageState);
      //fhlTopMenu.render(pageState);
      //Check cache
      if (localStorage.getItem("fhlPageState") != null) {
        //console.log(localStorage.getItem("fhlPageState"));
        var tmp = JSON.parse(localStorage.getItem("fhlPageState"));
        if (tmp.swVer != currentSWVer) {
          // pageState 版本變更
          pageStateInit();
          setPageState(pageState);
        } else {
          // 從 localStorage 載入
          pageState = tmp;
          setPageState(pageState);
        }
      } else {
        pageStateInit();
        // 2017.07 若人家是直接貼上url含有 書卷章節, 就從裡面取代
        setPageState(pageState);
      }

      $('#problemsReport').attr("href", "mailto:sean@fhl.net,tjm@fhl.net,snowray712000@gmail.com?subject=[問題回報] 信望愛聖經工具NUI");
      fhlToolBar.init(pageState);
      fhlLeftWindow.init(pageState);
      fhlMidWindow.init(pageState);
      fhlInfo.init(pageState);
      registerEvents(pageState);


    });
    //var urlJSON = "http://bkbible.fhl.net/json/"; // 小雪本機開發要用這個. 上線後要用下面那個 2015.10.24(六)
    var urlJSON = "https://bkbible.fhl.net/json/";

    // 2017.07 下面整理與NUI2一致.

    var chineseNumber = FHL.CONSTANT.Bible.CHINESE_NUMBERS;
    var book = FHL.CONSTANT.Bible.CHINESE_BOOK_ABBREVIATIONS;
    var bookGB = FHL.CONSTANT.Bible.CHINESE_BOOK_ABBREVIATIONS_GB;
    var bookFullName = FHL.CONSTANT.Bible.CHINESE_BOOK_NAMES;
    var bookFullName2 = FHL.CONSTANT.Bible.CHINESE_BOOK_NAMES_GB;
    var bookChapters = FHL.CONSTANT.Bible.BOOK_CHAPTERS;
    var bookEng = FHL.CONSTANT.Bible.ENGLISH_BOOK_ABBREVIATIONS;

    function getAjaxUrl(func, ps, idx) {
      var paramArr = new Array("engs", "chineses", "chap", "sec", "version",
        "strong", "gb", "book", "N", "k");
      var urlParams = {
        sc: [0, 2, 3, 6, 7],
        qb: [1, 2, 4, 5, 6],
        qp: [0, 2, 3, 6],
        sd: [6, 8, 9]
      };
      var getFullAjaxUrl = function (func, ps, idx) {
        var ret = urlJSON + func + ".php?";
        for (var i = 0; i < urlParams[func].length; i++) {
          var paramKey = paramArr[urlParams[func][i]];

          if (paramKey == "version") {
            ret += paramKey;
            ret += "=";
            ret += encodeURIComponent(ps[paramKey][idx]);
            ret += "&";
          } else {
            ret += paramKey;
            ret += "=";
            ret += encodeURIComponent(ps[paramKey]);
            ret += "&";
          }
        };

        ret = ret.substring(0, ret.length - 1);
        //console.log(ret); //https://bkbible.fhl.net/json/qp.php?engs=Rom&chap=16&sec=27&gb=0
        return ret;
      }
      return getFullAjaxUrl(func, ps, idx);
    }

    function getBookFunc(func, bookName) {
      var i;
      // 2016.11, 簡體中文, 會取出 null, 修正完畢
      for (i = 0; i < book.length; i++) {
        if (FHL.CONSTANT.Bible.CHINESE_BOOK_ABBREVIATIONS[i] == bookName) break;
        if (FHL.CONSTANT.Bible.CHINESE_BOOK_ABBREVIATIONS_GB[i] == bookName) break;
      }

      var ret;
      switch (func) {
        case "index":
          ret = i;
          break;
        case "indexByEngs":
          for (i = 0; i < bookEng.length; i++)
            if (bookEng[i] == bookName) break;
          ret = i;
          break;
        case "bookFullName":
          ret = (pageState.gb == 1) ? bookFullName2[i] : bookFullName[i];
          break;
        case "bookChapters":
          ret = bookChapters[i];
          break;
        case "bookEng":
          ret = bookEng[i];
          break;
        default:
          ret = "failed";
          break;
      }
      return ret;
    }

    function requestFullscreen() {
      $("#mainWindow").css({ top: "0px" });
      //$("#bookSelectPopUp").css({top: "0px"});
      var mainWindow = document.querySelector("#mainWindow");
      if ((document.fullScreenElement !== undefined && document.fullScreenElement === null) || (document.msFullscreenElement !== undefined && document.msFullscreenElement === null) || (document.mozFullScreen !== undefined && !document.mozFullScreen) || (document.webkitIsFullScreen !== undefined && !document.webkitIsFullScreen)) {
        if (mainWindow.requestFullScreen) {
          mainWindow.requestFullScreen();
        } else if (mainWindow.mozRequestFullScreen) {
          mainWindow.mozRequestFullScreen();
        } else if (mainWindow.webkitRequestFullScreen) {
          mainWindow.webkitRequestFullScreen(Element.ALLOW_KEYBOARD_INPUT);
        } else if (mainWindow.msRequestFullscreen) {
          mainWindow.msRequestFullscreen();
        }
      }
    }

    function registerEvents(ps) {
      /* scrolling register */
      /*setTimeout(function() {
          $('div').scroll(function() {
              $(this).addClass('scrolling');
              clearTimeout( $.data( this, "scrollCheck" ) );
              $.data( this, "scrollCheck", setTimeout(function() {
                  $('div').removeClass('scrolling');
              }, 350) );
          });
      }, 2000);*///等到其他function 跑完 (backup 用)

      /*shortcut register*/
      $(document).bind('keydown', 'alt+shift+f', function () {
        $('[data-ic-class="search-trigger"]').trigger("click");
        setTimeout(function () { $('[data-ic-class="search-clear"]').trigger("click"); }, 1);
      });
      $(document).bind('keydown', 'esc', function () {
        $('#helpingPopUp').css({
          'visibility': 'hidden',
          'opacity': '0'
        });
      });
      $(document).keyup(function (e) {
        if (e.keyCode == 27) { // escape key maps to keycode `27`
          // exit from fullscreen
          windowAdjust();
          $('#fullscreenControl').removeClass('selected');
        }
      });
      $(document).bind('keydown', 'alt+shift+l', function () {
        //document.documentElement.webkitRequestFullScreen();
        requestFullscreen();
        $('#fullscreenControl').addClass('selected');
      });
      $(document).bind('keydown', 'alt+shift+s', function () {
        var idx = getBookFunc("index", ps.chineses);
        var position = $('#bookSelect').position();
        position.left = '40%';//$('#bookSelect').position().left;
        position.top = '20%';//$('#bookSelect').position().top+$('#bookSelect').height()+10;
        bookSelectChapter.init(ps, $('#bookSelectChapter'), idx, position);
        bookSelectChapter.registerEvents(ps);
        //isBookSelectChapterPopUp=true;
        //bookselectchapter.dom.hide();
        bookSelectChapter.dom.show();
        //alert(pageState.chineses);
      });
      $(document).bind('keydown', 'alt+shift+z', function () {
        $('#fhlLeftWindowControl').trigger("click");
      });
      $(document).bind('keydown', 'alt+shift+x', function () {
        $('#fhlMidBottomWindowControl').trigger("click");
      });
      $(document).bind('keydown', 'alt+shift+c', function () {
        $('#fhlInfoWindowControl').trigger("click");
      });
      $(document).bind('keydown', 'alt+shift+/', function () {
        $('#help').trigger("click");
      });
      $(document).bind('keydown', 'ctrl+c', function () {
        var copyTextarea = document.querySelector('#test');
        //copyTextarea.style.backgroundColor = "red";
        copyTextarea.select();
      });

      /*in search input*/
      $('[data-ic-class="search-input"]').bind('keydown', 'alt+shift+f', function () {
        $('[data-ic-class="search-trigger"]').trigger("click");
        setTimeout(function () { $('[data-ic-class="search-clear"]').trigger("click") }, 1);
      });
      $('[data-ic-class="search-input"]').bind('keydown', 'esc', function () {
        $('[data-ic-class="search-input"]').val('');
        $('[data-ic-class="search-trigger"]').removeClass('active');
      });
      $('[data-ic-class="search-input"]').bind('keydown', 'return', function () {
        $('.searchBtn').trigger("click");
      });
    }

    /***** Start of fhlToolBar *****/

    var fhlToolBar = {
      init: function (ps) {
        //this.registerEvents();
        help.init(ps, $('#help'));
        windowControl.init(ps, $('#windowControl'));
        windowControl.registerEvents(ps);
        bookSelect.init(ps, $('#bookSelect'));
        searchTool.init(ps, $('#searchTool'));
        searchTool.registerEvents(ps);
      }
    };
    var help = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
        helpingPopUp.init(ps, $('#helpingPopUp'));
      },
      registerEvents: function (ps) {
        this.dom.on('click', function () {
          $('#helpingPopUp').css({
            'visibility': 'visible',
            'opacity': '1'
          });
        });
      },
      render: function (ps, dom) {
        var html = "";
        html += '?';
        dom.html(html);
        this.registerEvents(ps);
      }
    };

    var helpingPopUp = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        $('#helpCloseButton').click(function () {
          $('#helpingPopUp').css({
            'visibility': 'hidden',
            'opacity': '0'
          });
        });
      },
      render: function (ps, dom) {
        var html = "";
        html += '<div><div id="helpCloseButton"><i class="fa fa-times"></i></div><ul>\
                            <li>Alt + Shift + F: 搜尋</li>\
                            <li>Alt + Shift + S: 快速選章</li>\
                            <li>Alt + Shift + L: 全螢幕</li>\
                            <li>Alt + Shift + Z: 設定視窗開關</li>\
                            <li>Alt + Shift + X: 搜尋視窗開關</li>\
                            <li>Alt + Shift + C: 輔助視窗開關</li>\
                            <li>Alt + Shift + /: 幫助</li>\
                            <li>Esc: 跳出</li></ul></div>';
        $('#helpingPopUpInside').html(html);
        this.registerEvents(ps);
      }
    }

    var windowControl = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
        this.registerEvents(ps);
      },
      registerEvents: function (ps) {
        $('#windowControlIcon').click(function (e) {
          if ($(this).hasClass('selected')) {
            var that = $(this);
            that.animate({ left: '0px' });
            $("#windowControl").animate({ width: '30px' }, function () {
              that.removeClass('selected');
            });
            $("#windowControlButtons").animate({ opacity: 0 }, 100);
          }
          else {
            var that = $(this);
            that.animate({ left: '20px' });
            $("#windowControl").animate({ width: '350px' }, function () {
              that.addClass('selected');
            });
            $("#windowControlButtons").animate({ opacity: 1 }, 800);
          }
          e.stopPropagation();
        });
        $(document).click(function () {
          if ($('#windowControlIcon').hasClass('selected')) {
            //$('#windowControlIcon').trigger( "click" );
          }
        });
        $('#fhlLeftWindowControl').click(function () {
          if ($(this).hasClass('selected')) {
            var that = $(this);
            var fhlLeftWindowWidth = $("#fhlLeftWindow").width();
            $("#fhlLeftWindow").animate({ left: -fhlLeftWindowWidth - 15 + 'px' });
            $("#fhlToolBar").animate({ left: '12px' });
            $("#fhlMidWindow").animate({ left: '12px', width: $("#fhlMidWindow").width() + fhlLeftWindowWidth + 12 + 'px' }, function () {
              that.removeClass('selected');

              fhlLecture.reshape(ps);
            });
          }
          else {
            var that = $(this);
            var fhlLeftWindowWidth = $("#fhlLeftWindow").width();
            $("#fhlLeftWindow").animate({ left: '12px' });
            $("#fhlToolBar").animate({ left: fhlLeftWindowWidth + 24 + 'px' });
            $("#fhlMidWindow").animate({ left: fhlLeftWindowWidth + 12 + 12 + 'px', width: $("#fhlMidWindow").width() - fhlLeftWindowWidth - 12 + 'px' }, function () {
              that.addClass('selected');

              fhlLecture.reshape(ps);
            });
          }

        });
        $('#fhlMidBottomWindowControl').click(function () {
          if ($(this).hasClass('selected')) {
            var that = $(this);
            var fhlMidBottomWindowHeight = $("#fhlMidBottomWindow").height();
            $("#fhlMidBottomWindow").animate({ top: $('#fhlMidWindow').height() + 15 + 'px', bottom: -fhlMidBottomWindowHeight - 15 + 'px' });
            $("#fhlLecture").animate({ bottom: '0px', height: $("#fhlLecture").height() + fhlMidBottomWindowHeight + 12 + 'px' }, function () {
              that.removeClass('selected');
            });
          }
          else {
            var that = $(this);
            var fhlMidBottomWindowHeight = $("#fhlMidBottomWindow").height();
            $("#fhlMidBottomWindow").animate({ top: $('#fhlMidWindow').height() - fhlMidBottomWindowHeight + 'px', bottom: '0px' });
            $("#fhlLecture").animate({ bottom: fhlMidBottomWindowHeight + 'px', height: $("#fhlLecture").height() - fhlMidBottomWindowHeight - 12 + 'px' }, function () {
              that.addClass('selected');
            });
          }
        });
        $('#fhlInfoWindowControl').click(function () {
          if ($(this).hasClass('selected')) {
            var that = $(this);
            var fhlInfoWidth = $("#fhlInfo").width();
            $("#fhlInfo").animate({ left: $(window).width() + 15 + 'px', right: -fhlInfoWidth - 15 + 'px', width: fhlInfoWidth });
            $("#fhlMidWindow").animate({ right: '12px', width: $("#fhlMidWindow").width() + fhlInfoWidth + 12 + 'px' }, function () {
              that.removeClass('selected');

              fhlLecture.reshape(ps);
            });
          }
          else {
            var that = $(this);
            var fhlInfoWidth = $("#fhlInfo").width();
            $("#fhlInfo").animate({ left: $(window).width() - fhlInfoWidth - 12 + 'px', right: '12px' });
            $("#fhlMidWindow").animate({ right: fhlInfoWidth + 'px', width: $("#fhlMidWindow").width() - fhlInfoWidth - 12 + 'px' }, function () {
              that.addClass('selected');

              fhlLecture.reshape(ps);
            });
          }
        });
        $('#fullscreenControl').click(function () {
          if ($(this).hasClass('selected')) {
            var that = $(this);
            setTimeout(function () { that.removeClass('selected'); }, 1);
          }
          else {
            var that = $(this);
            requestFullscreen();
            setTimeout(function () { that.addClass('selected'); }, 1);
          }
        });
        $('#windowControl').click(function (e) {
          e.stopPropagation();
        });
      },
      render: function (ps, dom) {
        var html = "<i id='windowControlIcon' class='fa fa-tv fa-fw selected'></i><div id='windowControlButtons'><span id='fhlLeftWindowControl' class='selected' ><i class='fa fa-wrench fa-fw'></i></span><span id='fhlMidBottomWindowControl'><i class='fa fa-search-plus fa-fw'></i></span><span id='fhlInfoWindowControl' class='selected'><i class='fa fa-file-text-o fa-fw'></i></span><space style='margin: 0px 10px; cursor: default; color: #D0D0D0;'>|</space><span id='fullscreenControl'><i class='fa fa-arrows-alt fa-fw'></i></span></div>";
        dom.html(html);
      }
    };

    var bookSelect = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
        bookSelectPopUp.init(ps, $('#bookSelectPopUp'));
        bookSelectPopUp.registerEvents(ps);
      },
      registerEvents: function (ps) {
        var that = this;
        $('#bookSelect').unbind().click(function (e) {// 加上unbind() 讓創世記第二節之後的dropdown不會自動消失
          if (bookSelectPopUp.dom.is(":visible")) {
            bookSelectPopUp.dom.fadeOut('0.2');
            setTimeout(function () {
              bookSelect.dom.css({ 'color': '#D0D0D0' });
            }, 200);
          }
          else {
            bookSelectPopUp.dom.fadeIn('0.2');
            bookSelect.dom.css({ 'color': '#00A0FF' });
          }
          e.stopPropagation();
        });
        $('#bookSelectPopUp').click(function () {
          bookSelectPopUp.dom.fadeOut('0.2');
          setTimeout(function () { bookSelect.dom.css({ 'color': '#D0D0D0' }); }, 200);
        });
        $(document).click(function () {
          bookSelectPopUp.dom.fadeOut('0.2');
          setTimeout(function () { bookSelect.dom.css({ 'color': '#D0D0D0' }); }, 200);
        });
        $('#bookSelectName').click(function (e) {
          e.stopPropagation();
        });
        $('#bookSelect').mouseenter(function () {
          if (!bookSelectPopUp.dom.is(":visible")) {
            bookSelect.dom.css({ 'color': '#00A0FF' });
          }
        });
        $('#bookSelect').mouseleave(function () {
          if (!bookSelectPopUp.dom.is(":visible")) {
            bookSelect.dom.css({ 'color': '#D0D0D0' });
          }
        });
      },
      render: function (ps, dom) {
        var bookName = getBookFunc("bookFullName", ps.chineses);
        var html = "";
        if (bookName != "詩篇" && bookName != "诗篇")
          html = bookName + "： 第" + chineseNumber[ps.chap] + "章";
        else
          html = bookName + "： 第" + chineseNumber[ps.chap] + "篇";
        html += '&nbsp;&#9660;';
        dom.html(html);
        this.registerEvents(ps);
      }
    };

    var bookSelectPopUp = {
      init: function (ps, dom) {
        this.dom = dom;
        bookSelectName.init(ps, $('#bookSelectName'));
        bookSelectName.registerEvents(ps);
        this.dom.hide();
      },
      registerEvents: function (ps) {
        var that = this;
        this.dom.click(function (e) {
          e.stopPropagation();
        });
      }
    };

    var bookSelectName = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        var that = this.dom;
        var isBookSelectChapterPopUp = false;

        this.dom.find('li li').click(function () {
          var that = $(this);
          var selectedColumnIndex = $(this).parents('li').index();
          //var previousColumnIndex = bookSelectName.dom.find('#old-testament>ul>li.selected').index();
          //var previousRowIndex = bookSelectName.dom.find('li li.selected').index();
          //console.log(previousColumnIndex);
          bookSelectName.dom.find('#old-testament>ul>li').removeClass('selected');

          if (bookSelectName.dom.find('li li.selected').attr('chineses') == $(this).attr('chineses'))
            $('.testaments>ul>li').animate({ left: '0px' }, { queue: false, duration: 300 });
          else
            $(this).parents('li').addClass('selected');
          setTimeout(function () {
            if (isBookSelectChapterPopUp === true && that.hasClass('selected')) {
              isBookSelectChapterPopUp = true;
              bookSelectName.dom.find('li li').removeClass('selected');
              bookSelectChapter.dom.hide();
            }
            else {
              $('#old-testament>ul>li:lt(' + selectedColumnIndex + ')').animate({ left: '-75px' }, { queue: false, duration: 200 });
              $('#old-testament>ul>li:eq(' + selectedColumnIndex + ')').animate({ left: '-75px' }, { queue: false, duration: 200 });
              $('#old-testament>ul>li:gt(' + selectedColumnIndex + ')').animate({ left: '75px' }, { queue: false, duration: 200 });
              var idx = getBookFunc("index", that.attr('chineses'));
              var isIE11 = !!navigator.userAgent.match(/Trident.*rv\:11\./);

              if (/msie/.test(navigator.userAgent.toLowerCase())) //replace 2016.11, 參照: http://www.fwolf.com/blog/post/35
              // if ($.browser.msie || isIE11) ( jQuery 1.90之後就不支援了)//mark 2016.11
              {
                var position = that.offset();
                position.left = $('#old-testament').offset().left + 128 * (selectedColumnIndex) + 50;
                position.top = $('#old-testament').offset().top + 30;
                bookSelectChapter.init(ps, $('#bookSelectChapter'), idx, position);
              }
              else {
                var position = that.offset();
                position.left = $('#old-testament').position().left + that.position().left + 128 * (selectedColumnIndex) + 40;
                position.top = $('#old-testament').position().top + 25;
                bookSelectChapter.init(ps, $('#bookSelectChapter'), idx, position);
              }
              bookSelectChapter.registerEvents(ps);
              bookSelectName.dom.find('li li').removeClass('selected');
              that.addClass('selected');
              isBookSelectChapterPopUp = true;
              bookSelectChapter.dom.show();
            }
          }, 1);
        });
      },
      render: function (ps, dom) {
        var html = "<div id='bookSelectTitle'>經卷選擇</div><div id='bookSelectChapter'></div>";
        html += "<div id='old-testament' class='testaments'><ul><li></li><li><span class='bookClass'>摩西五經</span><ul>";
        for (var i = 0; i < 5; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul><span class='bookClass'>舊約歷史書</span><ul>";
        for (var i = 5; i < 17; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul></li><li><span class='bookClass'>詩歌智慧書</span><ul>";
        for (var i = 17; i < 22; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul><span class='bookClass'>大先知書</span><ul>";
        for (var i = 22; i < 27; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul></li><li><span class='bookClass'>小先知書</span><ul>";
        for (var i = 27; i < 39; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul></li><li><span class='bookClass'>福音書</span><ul>";
        for (var i = 39; i < 43; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul><span class='bookClass'>新約歷史書</span><ul>";
        for (var i = 43; i < 44; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul></li><li><span class='bookClass'>保羅書信</span><ul>";
        for (var i = 44; i < 57; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul></li><li><span class='bookClass'>其他書信</span><ul>";
        for (var i = 57; i < 65; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul><span class='bookClass'>預言書</span><ul>";
        for (var i = 65; i < 66; i++)
          html += "<li><span>" + bookFullName[i] + "<i class='fa fa-angle-right fa-fw'></i></span></li>";
        html += "</ul></li><li></li></ul></div>";

        dom.html(html);

        for (var i = 0; i < bookFullName.length; i++) {
          dom.find('li li:eq(' + i + ')').attr('chineses', book[i]);
        }
        /*for(var i=0;i<bookFullName.length;i++){
          dom.find('li:eq('+i+')').attr('chineses',book[i]);
        }*/
      }
    };

    var bookSelectChapter = {
      init: function (ps, dom, idx, position) {
        this.dom = dom;
        this.idx = idx;
        this.dom.css({
          'position': 'fixed',
          'left': position.left,
          'top': position.top,
          'box-shadow': 'inset 0px 0px 5px 1px rgba(0,0,0,0.75)',
        });
        this.render(ps, this.dom, this.idx);
      },
      registerEvents: function (ps) {
        var that = this;
        this.dom.find('li').click(function () {
          ps.chineses = book[that.idx];
          ps.engs = bookEng[that.idx];
          ps.chap = parseInt($(this).attr('chap'));
          ps.sec = 1;
          ps.bookIndex = that.idx + 1; // 0-based轉1-based (book已經被注釋用掉了)
          setPageState(ps);
          bookSelect.render(ps, bookSelect.dom);
          fhlLecture.render(ps, fhlLecture.dom);
          viewHistory.render(ps, viewHistory.dom);
          fhlInfo.render(ps);
          bookSelectPopUp.dom.hide();
          //bookselectchapter.dom.hide();
          bookSelect.dom.css({ 'color': '#FFFFFF' });

          $(that).trigger('chapchanged');
        });
        $(document).click(function () {
          //bookselectchapter.dom.hide('0.2');
        });
        this.dom.mouseenter(function () {
          clearTimeout($.data($('#bookSelectChapter')[0], "bookSelectChapterAutoCloseTimeout"));
        });
      },
      render: function (ps, dom, idx) {
        var numOfChapters = bookChapters[idx];
        var html = "<div><ul>";
        for (var i = 1; i <= numOfChapters; i++) {
          html += "<li>" + i + "</li>";
        }
        html += "</ul></div>";
        dom.html(html);
        for (var i = 0; i < numOfChapters; i++) {
          dom.find('li:eq(' + i + ')').attr('chap', i + 1);
        }
      }
    };


    /***** End of fhlToolBar *****/

    /***** Start of fhlLeftWindow *****/

    var fhlLeftWindow = {
      init: function (ps) {
        settings.init(ps, $('#settings'));
        settings.registerEvents(ps);
        versionSelect.init(ps, $('#versionSelect'));
        //versionSelect.registerEvents(ps);
        viewHistory.init(ps, $('#viewHistory'));
        this.registerEvents();
      },
      registerEvents: function () {
        $('#fhlLeftWindow').resizable({
          handles: 'e',
          maxWidth: 300,
          minWidth: 170,
          resize: function (event, ui) {
            var currentWidth = ui.size.width;
            var fhlMidWindowWidth;
            if ($('#fhlInfoWindowControl').hasClass('selected'))
              fhlMidWindowWidth = $(window).width() - $("#fhlInfo").width() - currentWidth;
            else
              fhlMidWindowWidth = $(window).width() - currentWidth + 12;
            $("#fhlMidWindow").css({
              'width': fhlMidWindowWidth - 12 * 4 + 'px',
              'left': currentWidth + 12 + 12 + 'px'
            });
            $('#fhlToolBar').css({
              //'width': $(window).width()-$("#fhlLeftWindow").width()-36+'px',
              'left': currentWidth + 12 + 12 + 'px',
              'right': '12px'
            });

            // snow add 2016-07
            fhlLecture.reshape(pageState);
          }
        });
        $('.ui-resizable-handle.ui-resizable-e').html('<span>&#9776;</span>');
      }
    };

    var settings = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
        snSelect.init(ps, $('#snSelect'));
        snSelect.registerEvents(ps);
        realTimePopUpSelect.init(ps, $('#realTimePopUpSelect'));
        realTimePopUpSelect.registerEvents(ps);
        gbSelect.init(ps, $('#gbSelect'));
        gbSelect.registerEvents(ps);
        show_mode.init(ps, $('#show_mode'));
        show_mode.registerEvents(ps);
        mapTool.init(ps, $('#mapTool'));
        mapTool.registerEvents(ps);
        imageTool.init(ps, $('#imageTool'));
        imageTool.registerEvents(ps);
        fontSizeTool.init(ps, $('#fontSizeTool'));
        fontSizeTool.registerEvents(ps);
      },
      registerEvents: function (ps) {
        $('#settings p')
          .on('click', function () {
            var html = $(this).html() == "▼&nbsp;設定" ? "&#9654;&nbsp;設定" : "&#9660;&nbsp;設定";
            $(this).html(html);
            if ($(this).html() == "▼&nbsp;設定") {
              var settingsHeight = Math.min(260, $('#fhlLeftWindow').height() - 38 - $('#viewHistory').height() - 36);
              $("#settings").animate({ height: settingsHeight + 'px' }, { queue: false, duration: 500 });
              var versionSelectHeight = settingsHeight < 260 ? 38 : $("#versionSelect").height() - settingsHeight + 38;//bug: 前面會變37不會變38不知道為什麼，所以用這行修正
              $("#versionSelect").animate({ top: settingsHeight + 12 + 'px', height: versionSelectHeight + 'px' }, { queue: false, duration: 500 });
              var html = versionSelectHeight == 38 ? "&#9654;&nbsp;聖經版本選擇" : "&#9660;&nbsp;聖經版本選擇";
              $('#versionSelect p').html(html);
            }
            else {
              var versionSelectHeight = $("#versionSelect").height() + $("#settings").height() - 38;
              $("#versionSelect").animate({ top: 38 + 12 + 'px', height: versionSelectHeight + 'px' }, { queue: false, duration: 500 });
              $("#settings").animate({ height: '38px' }, { queue: false, duration: 500 });
              $("#versionSelect p").html("&#9660;&nbsp;聖經版本選擇");
            }
          });
        $('#settings').resizable({
          handles: 's',
          maxHeight: 280,
          minHeight: 38,
          resize: function (event, ui) {
            var maxHeight = $('#fhlLeftWindow').height() - 38 - $('#viewHistory').height() - 36;
            if (ui.size.height > maxHeight) {//不可以超過其他的bar
              ui.size.height = maxHeight;
              $("#versionSelect p").html("&#9654;&nbsp;聖經版本選擇");
            }
            var height = $('#fhlLeftWindow').height() - $('#viewHistory').height() - ui.size.height;
            $("#versionSelect").css({
              'top': ui.size.height + 12 + 'px',
              'height': height - 36 + 'px'
            });
            $(this).css({
              width: 'auto',
              right: '0px'
            });
            var html = $(this).css('height') == '38px' ? "&#9654;&nbsp;設定" : "&#9660;&nbsp;設定";
            $('#settings p').html(html);
            var html = $('#versionSelect').css('height') == '38px' ? "&#9654;&nbsp;聖經版本選擇" : "&#9660;&nbsp;聖經版本選擇";
            $('#versionSelect p').html(html);
          }
        });
        $('.ui-resizable-handle.ui-resizable-s').html('<span>&#9776;</span>');
        $('#settingsScrollDiv').scroll(function () {
          $(this).addClass('scrolling');
          clearTimeout($.data(this, "scrollCheck"));
          $.data(this, "scrollCheck", setTimeout(function () {
            $('#settingsScrollDiv').removeClass('scrolling');
          }, 350));
        });
      },
      render: function (ps, dom) {
        //dom.html("設定");
      }
    };

    var snSelect = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        $('#snOnOffSwitch').change(
          function () {
            if ($(this).is(':checked')) {
              ps.strong = 1;
              fhlLecture.render(ps, fhlLecture.dom);
            }
            else {
              ps.strong = 0;
              fhlLecture.render(ps, fhlLecture.dom);
            }
            setPageState(ps);
          });
      },
      render: function (ps, dom) {
        var html = "<div>原文編號:</div>";
        html += '<div class="onOffSwitch">\
                                <input type="checkbox" name="snOnOffSwitch" class="onOffSwitch-checkbox" id="snOnOffSwitch">\
                                <label class="onOffSwitch-label" for="snOnOffSwitch">\
                                    <span class="onOffSwitch-inner"></span>\
                                    <span class="onOffSwitch-switch"></span>\
                                </label>\
                            </div>';
        dom.html(html);
        $('#snOnOffSwitch').attr("checked", (ps.strong == 1) ? true : false);
      }
    };
    var gbSelect = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        $('#gbSelectSwitch').change(
          function () {
            if ($(this).is(':checked')) {
              ps.gb = 1;
              //ps.chineses = bookGB[book.indexOf(ps.chineses)];
              fhlLecture.render(ps, fhlLecture.dom);
            }
            else {
              ps.gb = 0;
              //ps.chineses = book[bookGB.indexOf(ps.chineses)];
              fhlLecture.render(ps, fhlLecture.dom);
            }
            setPageState(ps);
          });
      },
      render: function (ps, dom) {
        var html = "<div>繁簡切換:</div>";
        html += '<div class="onOffSwitch">\
                                <input type="checkbox" name="gbSelectSwitch" class="onOffSwitch-checkbox" id="gbSelectSwitch">\
                                <label class="onOffSwitch-label" for="gbSelectSwitch">\
                                    <span class="onOffSwitch-inner traditional-simpleSwitch"></span>\
                                    <span class="onOffSwitch-switch"></span>\
                                </label>\
                            </div>';
        //html += '<span style="color: #770000;">施工中...</span>';
        dom.html(html);
        $('#gbSelectSwitch').attr("checked", (ps.gb == 1) ? true : false);
      }
    };
    var show_mode = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
        if (ps.show_mode == null)
          ps.show_mode = 1;
      },
      registerEvents: function (ps) {
        $('#show_modeSwitch').change(
          function () {
            if ($(this).is(':checked')) {
              // checked 是指開啟圓圈移到右邊. 那就應該是 出現「交錯」
              ps.show_mode = 2;
              //ps.chineses = bookGB[book.indexOf(ps.chineses)];
              fhlLecture.render(ps, fhlLecture.dom);
            }
            else {
              // 出現「並列」
              ps.show_mode = 1;
              //ps.chineses = book[bookGB.indexOf(ps.chineses)];
              fhlLecture.render(ps, fhlLecture.dom);
            }
            setPageState(ps);
          });
      },
      render: function (ps, dom) {
        var html = "<div>顯示切換:</div>";
        html += '<div class="onOffSwitch">\
                                <input type="checkbox" name="show_modeSwitch" class="onOffSwitch-checkbox" id="show_modeSwitch">\
                                <label class="onOffSwitch-label" for="show_modeSwitch">\
                                    <span class="onOffSwitch-inner showmodeSwitch"></span>\
                                    <span class="onOffSwitch-switch"></span>\
                                </label>\
                            </div>';
        //html += '<span style="color: #770000;">施工中...</span>';
        dom.html(html);
        $('#show_modeSwitch').attr("checked", (ps.show_mode == 2) ? true : false);
      }
    };
    var realTimePopUpSelect = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        $('#realTimeOnOffSwitch').change(
          function () {
            if ($(this).is(':checked')) {
              ps.realTimePopUp = 1;
              fhlLecture.render(ps, fhlLecture.dom);
              fhlInfo.render(ps, fhlInfoContent.dom);
            }
            else {
              ps.realTimePopUp = 0;
              fhlLecture.render(ps, fhlLecture.dom);
              fhlInfo.render(ps, fhlInfoContent.dom);
            }
            setPageState(ps);
          });
      },
      render: function (ps, dom) {
        var html = "<div>即時顯示:</div>";
        html += '<div class="onOffSwitch">\
                                <input type="checkbox" name="realTimeOnOffSwitch" class="onOffSwitch-checkbox" id="realTimeOnOffSwitch">\
                                <label class="onOffSwitch-label" for="realTimeOnOffSwitch">\
                                    <span class="onOffSwitch-inner"></span>\
                                    <span class="onOffSwitch-switch"></span>\
                                </label>\
                            </div>';
        dom.html(html);
        $('#realTimeOnOffSwitch').attr("checked", (ps.realTimePopUp == 1) ? true : false);
      }
    };
    var mapTool = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        $('#mapToolOnOffSwitch').change(
          function () {
            if ($(this).is(':checked')) {
              // checked 是指開啟圓圈移到右邊. 那就應該是 出現「ON」
              ps.ispos = true;
              fhlLecture.render(ps, fhlLecture.dom);
            }
            else {
              // 出現「Off」
              ps.ispos = false;
              fhlLecture.render(ps, fhlLecture.dom);
            }
            setPageState(ps);
          });
      },
      render: function (ps, dom) {
        var html = "<div>地圖顯示:</div>";
        html += '<div class="onOffSwitch">\
                                <input type="checkbox" name="mapToolOnOffSwitch" class="onOffSwitch-checkbox" id="mapToolOnOffSwitch">\
                                <label class="onOffSwitch-label" for="mapToolOnOffSwitch">\
                                    <span class="onOffSwitch-inner"></span>\
                                    <span class="onOffSwitch-switch"></span>\
                                </label>\
                            </div>';
        //html += '<span style="color: #770000;">施工中...</span>';
        dom.html(html);
        $('#mapToolOnOffSwitch').attr("checked", ps.ispos);
      }
    };
    var imageTool = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        $('#imageToolOnOffSwitch').change(
          function () {
            if ($(this).is(':checked')) {
              // checked 是指開啟圓圈移到右邊. 那就應該是 出現「ON」
              ps.ispho = true;
              fhlLecture.render(ps, fhlLecture.dom);
            }
            else {
              // 出現「Off」
              ps.ispho = false;
              fhlLecture.render(ps, fhlLecture.dom);
            }
            setPageState(ps);
          });
      },
      render: function (ps, dom) {
        var html = "<div>圖片顯示:</div>";
        html += '<div class="onOffSwitch">\
                                <input type="checkbox" name="imageToolOnOffSwitch" class="onOffSwitch-checkbox" id="imageToolOnOffSwitch">\
                                <label class="onOffSwitch-label" for="imageToolOnOffSwitch">\
                                    <span class="onOffSwitch-inner"></span>\
                                    <span class="onOffSwitch-switch"></span>\
                                </label>\
                            </div>';
        //html += '<span style="color: #770000;">施工中...</span>';
        dom.html(html);
        $('#imageToolOnOffSwitch').attr("checked", ps.ispho);
      }
    };
    function renderTsk(ps){
      if ( ps.titleId == "fhlInfoTsk" ){
        var dom2 = document.getElementById("fhlInfoContent");
          if (dom2 != null) {
            var pfn_search_sn = function (sn) {
              doSearch(sn, ps, false);
            };

            var jret = tsk.tskapi(ps.engs, ps.chap, ps.sec, ps.gb ? true : false);
            var r = React.createElement(tsk.R.frame, {
              txt_ori: jret.record[0].com_text,
              default_book: ps.engs,
              default_version: "unv",
              isSN: ps.strong == 1 ? true : false,
              isGB: ps.gb ? true : false,
              cy: $(dom2).height(),
              pfn_search_sn: pfn_search_sn, //指定按下sn的結果
              fontSize: ps.fontSize, //
            });
            React.render(r, dom2);
            var renderobj = React.render(r, dom2);
          }
      }
    }
    function makeSureSizeBetween6and60(){
      if ($('#fhlLectureFontSize').val() > 60)
        $('#fhlLectureFontSize').val(60);
      else if ($('#fhlLectureFontSize').val() < 6)
        $('#fhlLectureFontSize').val(6);
    }
    function onFontSizeToolSizeChanged(sz,ps){
      // sz: parseInt($('#fhlLectureFontSize').val())
      $('#fhlLectureFontSizeSliderBar').val(sz);

      $('#fhlLecture .lec').css({
        'font-size': sz + 'pt',
        'line-height': sz * 1.25 + 'pt',
        'margin': sz * 1.25 - 15 + 'px 0px'
      });
      $('#commentScrollDiv').css({
        'font-size': $('#fhlLectureFontSize').val() + 'pt',
        'line-height': sz * 1.25 + 'pt',
        'margin': sz * 1.25 - 15 + 'px 0px'
      });
      $('#fhlInfoContent .parsingTop').css({
        'font-size': $('#fhlLectureFontSize').val() + 'pt',
        'line-height': sz * 1.25 + 'pt',
        'margin': sz * 1.25 - 15 + 'px 0px'
      });
      $('#parsingTable').css({
        'font-size': $('#fhlLectureFontSize').val() + 'pt',
        'line-height': sz * 1.25 + 'pt',
        'margin': sz * 1.25 - 15 + 'px 0px'
      });
      $('#fhlLecture .lecContent.bhs.hebrew').css({
        'font-size': (sz + 6) + 'pt',
        'line-height': (sz + 6) * 1.25 + 'pt',
        'margin': sz * 1.25 - 15 + 'px 0px'
      });
      ps.fontSize = sz;
      renderTsk(ps);
    }
    var fontSizeTool = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        $('#fhlLectureFontSizeSliderBar').change(function () {
          $("#fhlLectureFontSize").val($('#fhlLectureFontSizeSliderBar').val());
          makeSureSizeBetween6and60();
          onFontSizeToolSizeChanged(parseInt($('#fhlLectureFontSize').val()),ps); 
          fhlLecture.reshape(ps);//show add, 經文排整齊
        });
        $('#fhlLectureFontSize').change(function () {
          makeSureSizeBetween6and60();
          onFontSizeToolSizeChanged(parseInt($('#fhlLectureFontSize').val()),ps);            
          fhlLecture.reshape(ps);//show add, 經文排整齊
        });
        $('#fhlLectureFontSizeSmaller').click(function () {
          $('#fhlLectureFontSize').val(parseInt($('#fhlLectureFontSize').val()) - 2);
          makeSureSizeBetween6and60();
          onFontSizeToolSizeChanged(parseInt($('#fhlLectureFontSize').val()),ps);
          fhlLecture.reshape(ps);//show add, 經文排整齊
        });
        $('#fhlLectureFontSizeLarger').click(function () {
          $('#fhlLectureFontSize').val(parseInt($('#fhlLectureFontSize').val()) + 2);
          makeSureSizeBetween6and60();
          onFontSizeToolSizeChanged(parseInt($('#fhlLectureFontSize').val()),ps);
          fhlLecture.reshape(ps);//show add, 經文排整齊
        });
      },
      render: function (ps, dom) {
        var html = "<div>字體大小:</div>";
        html += ' <div id="fhlLectureFontSizeSmaller">A<span>-</span></div>\
                            <div id="fhlLectureFontSizeLarger">A<span>+</span></div>\
                            <div style="display: block; margin-top: 5px; height: 30px;">\
                                <input id="fhlLectureFontSizeSliderBar" type="range" min="6" max="60" value="'+ ps.fontSize + '" step="1" style="width: 95px;"/>\
                                <input id="fhlLectureFontSize" type="text" value="'+ ps.fontSize + '" style="width:16px;"/>\
                            </div>\
                            ';
        dom.html(html);
      }
    };

    function getVersionIdx(book) {
      return $('#versionSelect').find("li[book=" + book + "]").index();
    }
    function insertVersion(ps, dom) {
      var book = dom.attr('book');
      var cname = dom.attr('cname');
      var versionIdx = getVersionIdx(book);
      var inserted = false;
      //console.log('book='+book+",cname="+cname+",idx="+versionIdx);
      for (var i = 0; i < ps.version.length; i++) {
        if (versionIdx < getVersionIdx(ps.version[i])) {
          ps.version.splice(i, 0, book);
          ps.cname.splice(i, 0, cname);
          inserted = true;
          break;
        }
      }
      if (inserted == false) {
        ps.version.push(book);
        ps.cname.push(cname);
      }
    }

    var versionSelect = {
      init: function (ps, dom) {
        this.dom = dom;
        var that = this;
        var ajaxUrl = urlJSON + "uiabv.php";
        $.ajax({
          url: ajaxUrl
        }).done(function (d, s, j) {
          if (j) {
            //console.log(j.responseText);
            var jsonObj = JSON.parse(j.responseText);
            that.data = jsonObj;
          }
          that.render(ps, dom, that.data);
        });
        var versionSelectHeight = $('#fhlLeftWindow').height() - $('#settings').height() - $('#viewHistory').height() - 36;
        $('#versionSelect').css({ height: versionSelectHeight + 'px' });
      },
      registerEvents: function (ps) {
        $('#versionSelect p').on('click', function () {
          var html = $(this).html() == "▼&nbsp;聖經版本選擇" ? "&#9654;&nbsp;聖經版本選擇" : "&#9660;&nbsp;聖經版本選擇";
          $(this).html(html);
          if ($(this).html() == "▼&nbsp;聖經版本選擇") {
            var versionSelectHeight = $('#fhlLeftWindow').height() - $('#settings').height() - 38 - 36;
            var viewHistoryTop = $('#fhlLeftWindow').height() - 38 - 12;
            $("#versionSelect").animate({ height: versionSelectHeight + 'px' }, { queue: false, duration: 500 });
            $("#viewHistory").animate({ height: '38px', top: viewHistoryTop + 'px' }, { queue: false, duration: 500 });
            $("#viewHistory p").html("&#9654;&nbsp;歷史紀錄");
          }
          else {
            var viewHistoryHeight = $('#fhlLeftWindow').height() - $('#settings').height() - 38 - 36;
            var viewHistoryTop = $('#fhlLeftWindow').height() - viewHistoryHeight - 12;
            $("#versionSelect").animate({ height: '38px' }, { queue: false, duration: 500 });
            $("#viewHistory").animate({ height: viewHistoryHeight + 'px', top: viewHistoryTop + 'px' }, { queue: false, duration: 500 });
            $("#viewHistory p").html("&#9660;&nbsp;歷史紀錄");
          }
        });
        var that = this;
        this.dom.find('li').click(function (e) {
          $(this).toggleClass('selected');
          if ($(this).hasClass('selected')) {
            insertVersion(ps, $(this));
            /*
            ps.version.push($(this).attr('book'));
            ps.cname.push($(this).attr('cname'));
            */
            //$(this).html("&#x2713"+$(this).html());
          } else {
            var idx = ps.version.indexOf($(this).attr('book'));
            ps.version.splice(idx, 1);
            ps.cname.splice(idx, 1);
            //$(this).html($(this).html().substr(1, $(this).html().length-1));
          }
          //Set Default version?
          if (ps.version.length == 0) {
            var o = that.dom.find('li:eq(0)');
            $(o).addClass("selected");
            ps.version.push(o.attr('book'));
            ps.cname.push(o.attr('cname'));
          }
          setPageState(ps);
          fhlLecture.render(ps, fhlLecture.dom);
          e.stopPropagation();
        });
        $('#versionSelect').resizable({
          handles: 's',
          maxHeight: 1006,
          minHeight: 38,
          resize: function (event, ui) {
            var maxHeight = $('#fhlLeftWindow').height() - $('#settings').height() - 38 - 36;
            if (ui.size.height > maxHeight) {//不可以超過其他的bar
              ui.size.height = maxHeight;
            }
            var viewHistoryHeight = $('#fhlLeftWindow').height() - $('#settings').height() - ui.size.height - 36;
            var top = $('#settings').height() + ui.size.height + 24;
            var versionSelectHeight = ui.size.height;
            $("#viewHistory").css({
              'height': viewHistoryHeight + 'px',
              'top': top + 'px'
            });
            $(this).css({
              width: 'auto',
              right: '0px',
              height: versionSelectHeight + 'px'
            });
            var html = $(this).css('height') == '38px' ? "&#9654;&nbsp;聖經版本選擇" : "&#9660;&nbsp;聖經版本選擇";
            $('#versionSelect p').html(html);
            var html = $('#viewHistory').css('height') == '38px' ? "&#9654;&nbsp;歷史紀錄" : "&#9660;&nbsp;歷史紀錄";
            $('#viewHistory p').html(html);
          }
        });
        $('.ui-resizable-handle.ui-resizable-s').html('<span>&#9776;</span>');
        $('#versionSelectScrollDiv').scroll(function () {
          $(this).addClass('scrolling');
          clearTimeout($.data(this, "scrollCheck"));
          $.data(this, "scrollCheck", setTimeout(function () {
            $('#versionSelectScrollDiv').removeClass('scrolling');
          }, 350));
        });
      },
      render: function (ps, dom, data) {

        var that = this;
        var html = "<div class='secondLevelInside'><p>&#9660;&nbsp;聖經版本選擇</p><div id='versionSelectScrollDiv'><ul>";
        for (var i = 0; i < data.record_count; i++) {
          var o = data.record[i];
          html += "<li>" + o.cname + "</li>";
          /*if(o.cname)
          console.log(o.cname);
          else
              console.log("nothing");*/
          if (o.cname === "原文直譯(參考用)") //()括號在parse 時會出錯
            o.cname = "原文直譯";
        }

        html += "</ul></div></div>";
        dom.html(html);
        for (var i = 0; i < data.record_count; i++) {
          var o = data.record[i];
          dom.find('li:eq(' + i + ')').attr(o);
        }
        dom.find('li').removeClass('selected');
        for (var i = 0; i < ps.version.length; i++) {
          var v = ps.version[i];
          var li = dom.find('li[book="' + v + '"]');
          if (li != null) {
            li.each(function () {
              $(this).addClass('selected');
              var html = "";/*&#x2713*/
              html += $(this).html();
              $(this).html(html);
            });
          }
        }
        that.registerEvents(ps);
      }
    };

    function setBook(ps, bookName) {
      var idx = null;
      if (book.indexOf(bookName) != -1) {
        idx = book.indexOf(bookName);
      }
      else if (bookGB.indexOf(bookName) != -1) {
        idx = bookGB.indexOf(bookName);
      }
      else if (bookEng.indexOf(bookName) != -1) {
        idx = book.indexOf(bookName);
      } else {
        idx = null;
      }
      if (idx != null) {
        ps.chineses = book[idx];
        ps.engs = bookEng[idx];
      } else {
        console.log('setBook error:idx is null');
      }
    }
    // 因為 document 的事件愈來愈多自訂的, 就不知道有哪些了,
    // 所以新增一個物件來管理 document 的事件
    var docEvent = (function () {
      var $doc = $(document);
      function DocEvent() { };
      var fn = DocEvent.prototype;

      fn.when_vh_init = function (fn) {
        /// <summary> view history init </summary>
        /// <param type="fn(e,p1)" name="fn" parameterArray="false">初始化完成時執行</param>
        $doc.on({
          vh_init: fn
        });
      };
      fn.when_vh_idxchanged = function (fn) {
        /// <summary> view history idx changed </summary>
        /// <param type="fn(e,p1)" name="fn" parameterArray="false">_idx 改變時執行 </param>
        $doc.on({
          vh_idxchanged: fn
        });
      };
      fn.when_vh_itemschanged = function (fn) {
        /// <summary> view history idx changed </summary>
        /// <param type="fn(e,p1)" name="fn" parameterArray="false"> 內容改變時執行 </param>
        $doc.on({
          vh_itemschanged: fn
        });
      };

      fn.when_go = function (fn) {
        /// <summary> setPageState() 被呼叫時, 將會觸發 go </summary>
        /// <param type="fn(e,p1)" name="fn" parameterArray="false">p1:{chineses,chap,sec}</param>
        $doc.on({
          go: fn
        });
      };

      return new DocEvent();
    })();
    $(document).ready(function () {
      (function () {
        var _datas = [];
        var _idx = -1;

        function trigger_init() {
          $(document).trigger('vh_init', { datas: _datas, idx: _idx });
          trigger_vh_idxchanged();
          trigger_vh_itemschanged();
        }
        function trigger_vh_idxchanged() {
          $(document).trigger('vh_idxchanged', { datas: _datas, idx: _idx });
        }
        function trigger_vh_itemschanged() {
          $(document).trigger('vh_itemschanged', { datas: _datas, idx: _idx });
        }

        // callback
        // viewHistory主界面, 按下其中一個選項的時候, 觸發 idx changed
        viewHistory.when_liclick(function (e, p1) {
          _idx = p1.idx;
          trigger_vh_idxchanged();
        });
        // viewHistory主界面, 按下清除所有的時候, 觸發 items changed
        viewHistory.when_clearall(function (e) {
          _datas = [_datas[0]];
          _idx = 0;
          trigger_vh_itemschanged();
        });
        // 當別的地方切換章節的時候, 要新增到 datas, 並觸發事件
        docEvent.when_go(function (e, p1) {
          if (_idx == -1) {
            _datas = pageState.history;
            _idx = 0;
            trigger_init();
          }
          // 若只是「切換節」而不是「書卷或是章」，就不處理
          else if (_datas[_idx].chap != p1.chap || _datas[_idx].chineses != p1.chineses) {
            // 清空 idx 前
            var a1 = _datas.slice(_idx, _datas.length);
            a1.unshift(p1);
            _datas = a1;
            _idx = 0;

            trigger_vh_itemschanged();
          }
        });
        // 當 history 改變的時候, 要儲存 ps (其實這個不知道放到哪個class較好, 就先放在這)
        docEvent.when_vh_itemschanged(function (e, p1) {
          pageState.history = p1.datas;
          setBook(pageState, pageState.chineses);
          localStorage.setItem("fhlPageState", JSON.stringify(pageState));
        });
        // 當 fhlLecture 中的 back click 或 nextclick 被按的時候
        fhlLecture.when_bclick_or_nclick(function () {
          if (_idx < _datas.length - 1) {
            _idx++;
            trigger_vh_idxchanged();

            // 下面是原本的code 還沒完全被取代掉 (切換章節,卻不送出go event)
            var ps = pageState;
            setBook(ps, _datas[_idx].chineses);
            ps.chap = _datas[_idx].chap;
            ps.sec = 1;
            //setPageState(ps); // 不要 trigger 出 'go'
            bookSelect.render(ps, bookSelect.dom);
            fhlInfo.render(ps, fhlInfo.dom);
            fhlLecture.render(ps, fhlLecture.dom);
          }
        }, function () {
          if (_idx > 0) {
            _idx--;
            trigger_vh_idxchanged();

            // 下面是原本的code 還沒完全被取代掉 (切換章節,卻不送出go event)
            var ps = pageState;
            setBook(ps, _datas[_idx].chineses);
            ps.chap = _datas[_idx].chap;
            ps.sec = 1;
            //setPageState(ps); // 不要 trigger 出 'go'
            bookSelect.render(ps, bookSelect.dom);
            fhlInfo.render(ps, fhlInfo.dom);
            fhlLecture.render(ps, fhlLecture.dom);
          }
        });
        // 等待 ps.history ok 就觸發觸始化
        (function () {
          function tryit() {
            if (pageState == null || pageState.history == null || pageState.history.length == 0)
              setTimeout(tryit, 777);//try it again
            else
              $(document).trigger('go', { chineses: pageState.chineses, chap: pageState.chap, sec: pageState.sec });
          }
          setTimeout(tryit, 777);
        })();

        // 模擬 1
        //_datas.push({ chineses: '創', chap: 1 });
        //_datas.push({ chineses: '出', chap: 1 });
        // _idx = 0;
        // trigger_init();

        // 模擬 2
        //setTimeout(function () {
        //  _idx = 1;
        //  trigger_vh_idxchanged();
        //}, 2000);

        // 模擬 3
        //setTimeout(function () {
        //  _datas.push({ chineses: '創', chap: 3 });
        //  _idx = 0;

      })();
    });

    var viewHistory = (function () {
      function ViewHistory() { };
      var fn = ViewHistory.prototype;

      fn.when_liclick = function (fn) {
        /// <summary> ul 清單中的 li 被 click 的時候</summary>
        /// <param type="fn(e,p1)" name="fn" parameterArray="false">{idx},回傳的是ul指在清單中的idx,</param>
        $(viewHistory.dom).on({
          liclick: fn
        }, 'li');
      };
      fn.when_clearall = function (fn) {
        /// <summary> 清除所有 被按下去的時候 </summary>
        /// <param type="fn(e)" name="fn" parameterArray="false"></param>
        $(viewHistory.dom).on({
          clearall: fn
        }, '.clearHistory');
      };
      fn.init = function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
        var viewHistoryTop = $('#fhlLeftWindow').height() - 38 - 12;
        $('#viewHistory').css({ top: viewHistoryTop });


        var $vh = $('#viewHistory');
        function renderList(datas) {
          /// <summary> 用於畫 li 清單, ul先被清空, 再一一加入 </summary>
          /// <param type="[{.chineses, .chap},{},{}]" name="datas" parameterArray="true">清單</param>
          var ul = $vh.find('ul').first();
          ul.empty();
          Enumerable.From(datas).ForEach(function (a1) {
            ul.append($("<li chineses=" + a1.chineses + " chap=" + a1.chap + ">" + a1.chineses + ":" + a1.chap + "</li>"));
          })
        }
        $(document).on({
          vh_init: function (e, p1) {
            renderList(p1.datas);
          },
          vh_itemschanged: function (e, p1) {
            renderList(p1.datas);
          }
        });

        $vh.on({
          click: function (e) {

            // 傳出第幾個被點 ( 考慮 可5 可8 可5 ... 到底哪個可5被點 ) 0-based
            var ul = $vh.find('ul').first();
            var lis = ul.children();
            for (var i = 0; i < lis.length; i++) {
              if (lis[i] == this)
                break;
            }

            $(this).trigger('liclick', {
              idx: i,
              chineses: $(this).attr('chineses'),
              chap: parseInt($(this).attr('chap'))
            });

            // 下面是原本的code 還沒完全被取代掉
            setBook(ps, $(this).attr('chineses'));
            ps.chap = parseInt($(this).attr('chap'));
            ps.sec = 1;
            //setPageState(ps); // 不要 trigger 出 'go'
            bookSelect.render(ps, bookSelect.dom);
            fhlInfo.render(ps, fhlInfo.dom);
            fhlLecture.render(ps, fhlLecture.dom);
            // that.render(ps, that.dom); // 已經處理了. vh_itemchanged 會處理
          }
        }, 'li').on({
          click: function (e) {
            $(this).trigger('clearall');
          }
        }, '.clearHistory');
      }
      fn.registerEvents = function (ps) {
        var that = this;
        $('#viewHistory p')
          .on('click', function () {
            var html = $(this).html() == "▼&nbsp;歷史紀錄" ? "&#9654;&nbsp;歷史紀錄" : "&#9660;&nbsp;歷史紀錄";
            $(this).html(html);
            if ($(this).html() == "▼&nbsp;歷史紀錄") {
              var viewHistoryHeight = Math.min(36 * ps.history.length + 64, $('#fhlLeftWindow').height() - $('#settings').height() - 38 - 36);
              var viewHistoryTop = $('#fhlLeftWindow').height() - viewHistoryHeight - 12;
              if (viewHistoryHeight == 36 * ps.history.length + 64) {
                var versionSelectHeight = $("#versionSelect").height() + $("#viewHistory").height() - viewHistoryHeight;
                $("#versionSelect").animate({ height: versionSelectHeight + 'px' }, { queue: false, duration: 500 });
              }
              else {
                $("#versionSelect").animate({ height: '38px' }, { queue: false, duration: 500 });
                $("#versionSelect p").html("&#9654;&nbsp;聖經版本選擇");
              }
              $("#viewHistory").animate({ height: viewHistoryHeight + 'px', top: viewHistoryTop + 'px' }, { queue: false, duration: 500 });
              $("#viewHistory p").html("&#9660;&nbsp;歷史紀錄");
            }
            else {
              var versionSelectHeight = $('#fhlLeftWindow').height() - $('#settings').height() - 38 - 36;
              var viewHistoryTop = $('#fhlLeftWindow').height() - 38 - 12;
              $("#versionSelect").animate({ height: versionSelectHeight + 'px' }, { queue: false, duration: 500 });
              $("#versionSelect p").html("&#9660;&nbsp;聖經版本選擇");
              $("#viewHistory").animate({ height: '38px', top: viewHistoryTop + 'px' }, { queue: false, duration: 500 });
              $("#viewHistory p").html("&#9654;&nbsp;歷史紀錄");
            }
          });
        //$('.clearHistory').click(function () {
        //  ps.history = [{ chineses: ps.chineses, chap: ps.chap }];
        //  setPageState(ps);
        //  viewHistory.render(ps, viewHistory.dom);
        //});
        //this.dom.find('li')
        //.css({ cursor: "pointer" })
        //.click(function () {
        //  setBook(ps, $(this).attr('chineses'));
        //  ps.chap = parseInt($(this).attr('chap'));
        //  ps.sec = 1;
        //  setPageState(ps);
        //  bookSelect.render(ps, bookSelect.dom);
        //  fhlInfo.render(ps, fhlInfo.dom);
        //  fhlLecture.render(ps, fhlLecture.dom);
        //  that.render(ps, that.dom);
        //});
        $('#viewHistoryScrollDiv').scroll(function () {
          $(this).addClass('scrolling');
          clearTimeout($.data(this, "scrollCheck"));
          $.data(this, "scrollCheck", setTimeout(function () {
            $('#viewHistoryScrollDiv').removeClass('scrolling');
          }, 350));
        });
      }
      fn.render = function (ps, dom) {
        /*
            <div id="viewHistory">
              <div class="secondLevelInside">
                <p>&#9654;&nbsp;歷史記錄</p>
                <span class="clearHistory">清除記錄</span>
                <div id="viewHistoryScrollDiv">
                  <ul class="viewHistoryList"></ul>
                </div>
              </div>
            </div>
        */
        var vh = $("#viewHistory");
        if (vh.height() == 38)
          vh.find('p').first().html('&#9654;&nbsp;歷史記錄');
        else
          vh.find('p').first().html('&#9660;&nbsp;歷史記錄');
        //var html="<div class='secondLevelInside'>";
        //if($("#viewHistory").height()==38)
        //  html+="<p>&#9654;&nbsp;歷史紀錄</p>";
        //else
        //  html+="<p>&#9660;&nbsp;歷史紀錄</p>";
        //html+="<span class='clearHistory'>清除記錄</span><div id='viewHistoryScrollDiv'><ul class='viewHistoryList'>";
        //for(var i=ps.history.length-1;i>=0;i--){
        //  var r=ps.history[i];
        //  html+="<li chineses="+r.chineses+" chap="+r.chap+">";
        //  html+=r.chineses+":"+r.chap+"</li>";
        //}
        //html+="</ul></div></div>";
        //dom.html(html);

        this.registerEvents(ps);
      }
      return new ViewHistory();
    })();

    /***** End of fhlLeftWindow *****/

    /***** Start of fhlMidWindow *****/
    var fhlMidWindow = {
      init: function (ps, dom) {
        this.dom = dom;
        fhlLecture.init(pageState, $('#fhlLecture'));
        fhlMidBottomWindow.init(pageState, $('#fhlMidBottomWindow'));
        this.render(ps, dom);
      },
      render: function (ps, dom) {
        var width = $(window).width() - $("#fhlLeftWindow").width() - $("#fhlInfo").width() - 12 * 4;
        $("#fhlMidWindow").css({
          'width': width + 'px'
        });
      }
    }

    function setCSS(col, ps) {
      var totalWidth = 100;
      $('.lecContent').css('width', (totalWidth / col) + "%");
      $('.lecVersion').css('width', (totalWidth / col) + "%");
    }

    function setFont() {
      $('.bhs').addClass('hebrew');
      $('.nwh').addClass('greek');
      $('.lxx').addClass('greek');
    }

    function getBibleText(col, ps, cbk, defCbk) {
      var sem = col;
      //console.log("enter getBibleText");
      for (var i = 0; i < col; i++) {
        //console.log("launch ajax"+i);
        //added by sean 2015.10.20
        var temp_ps = ps;
        if (ps.gb == 1 && bookGB.indexOf(ps.chineses) == -1) {
          temp_ps.chineses = bookGB[book.indexOf(ps.chineses)];
        }
        else if (ps.gb == 0 && book.indexOf(ps.chineses) == -1) {
          temp_ps.chineses = book[bookGB.indexOf(ps.chineses)];
        }

        var ajaxUrl = getAjaxUrl("qb", temp_ps, i);
        $.ajax({
          url: ajaxUrl
        }).done(function (d, s, j) {
          if (j) {
            //console.log(j.responseText);
            var jsonObj = JSON.parse(j.responseText);
            cbk(jsonObj);
            sem--;
          }
        });
      }//for each icol
      var def = setInterval(function () {
        if (sem == 0) {
          defCbk();
          clearInterval(def);
        }
      }, 100);
    }

    function checkOldNew(ps) {
      //0 - Old
      //1 - New
      return (book.indexOf(ps.chineses) >= 39) ? 0 : 1;
    }

    function parseBibleText(text, ps, isOld, bibleVersion) {
      var ret;
      checkOldNew(ps);
      switch (ps.strong) {
        case 0:
          ret = text;
          break;
        case 1:
          //console.log(text);
          if (bibleVersion == "和合本" || bibleVersion == "KJV") {

            function snReplace(s) {
              //console.log(s);
              if (s.substr(0, 4) === '{<WT') {
                s = s.replace(/{<WT[G,H]+/g, "<span class='sn' N=" + isOld + ">{(");
                s = s.replace(/>}/g, ")}</span>");
              }
              else if (s.substr(0, 3) === '{<W') {
                s = s.replace(/{<W[A,G,H]+/g, "<span class='sn' N=" + isOld + ">{&lt;");
                s = s.replace(/>}/g, "&gt;}</span>");
              }
              else if (s.substr(0, 3) === '<WT') {
                s = s.replace(/<WT[G,H]+/g, "<span class='sn' N=" + isOld + ">(");
                s = s.replace(/>/g, ")</span>");
              }
              else if (s.substr(0, 2) === '<W') {
                s = s.replace(/<W[A,G,H]+/g, "<span class='sn' N=" + isOld + ">&lt;");
                s = s.replace(/>/g, "&gt;</span>");
              }
              else
                console.debug('sn parsing error!');
              return s;
            }
            text = text.replace(/[{]*<W[A,T,G,H]+[0-9]+a?>[}]*/g, snReplace);

            //text=text.replace(/[{}]/g,"");
            //text=text.replace(/>/g,"&gt;</span>");
            //text=text.replace(/<W[a-zA-Z]*/g,"<span class='sn' N="+isOld+">&lt;");

          }
          //console.log(text);
          ret = text;
          break;
        default:
          ret = text;
          break;
      }
      if (bibleVersion == "舊約馬索拉原文" || bibleVersion == "新約WH原文") {
        ret = ret.replace(/</g, "&lt");
        ret = ret.replace(/>/g, "&gt");
        ret = ret.replace(/\r\n/g, "<br>");
      }
      return ret;
    }

    function getRecord(r, b, c, s) {
      var ret = null;
      for (var i = 0; i < r.length; i++) {
        if (r[i] == null)
          break;
        if (r[i].chap == c && r[i].sec == s) {
          ret = r[i];
          break;
        }
      }
      return ret;
    }

    function sortBibleVersion(r, ps) {
      var tmpArr = new Array();
      for (var i = 0; i < ps.version.length; i++) {
        var version = ps.version[i];
        for (var j = 0; j < r.length; j++) {
          if (version == r[j].version) {
            tmpArr.push(r[j]);
          }
        }
      }
      return tmpArr;
    }

    var fhlLecture = (function () {
      function FhlLecture() {
        this.that = this
      };

      var fn = FhlLecture.prototype;
      var $lecture;
      fn.init = function (ps, dom) {
        this.dom = dom;
        this.render(ps, dom);
        $lecture = $(this.dom);
        var $lecMain = $('#lecMain');
        var that = this
        // chapnext prev 變成1次事件就夠了
        $('.chapBack').click(function (e) {
          var idx = getBookFunc("index", ps.chineses); // 0-based
          if (ps.chap == 1) {
            idx--;
            ps.chineses = book[idx];
            ps.engs = bookEng[idx];
            ps.chap = bookChapters[idx];
          } else {
            if (ps.chap == 0) {
              ps.chap = ps.commentBackgroundChap;
              ps.sec = ps.commentBackgroundSec;
            }
            ps.chap--;
          }
          ps.bookIndex = idx + 1; // 此idx回傳是 0-based
          ps.sec = 1;
          setPageState(ps);
          viewHistory.render(ps, viewHistory.dom);
          fhlLecture.render(ps, fhlLecture.dom);
          fhlInfo.render(ps);
          bookSelect.render(ps, bookSelect.dom);
          e.stopPropagation();

          $(that).trigger('chapchanged');
        });
        $('.chapNext').click(function (e) {
          var idx = getBookFunc("index", ps.chineses);
          if (ps.chap == bookChapters[idx]) {//if last chapter
            idx++;
            ps.chineses = book[idx];//book+1
            ps.engs = bookEng[idx];
            ps.chap = 1;
          } else {
            if (ps.chap == 0) {
              ps.chap = ps.commentBackgroundChap;
              ps.sec = ps.commentBackgroundSec;
            }
            ps.chap++;
          }
          ps.bookIndex = idx + 1; // 此idx回傳是 0-based

          ps.sec = 1;
          setPageState(ps);
          viewHistory.render(ps, viewHistory.dom);
          fhlLecture.render(ps, fhlLecture.dom);
          fhlInfo.render(ps);
          bookSelect.render(ps, bookSelect.dom);
          e.stopPropagation();

          $(that).trigger('chapchanged');
        });
        $('#lecMain').scroll(function () {
          $(this).addClass('scrolling');
          clearTimeout($.data(this, "scrollCheck"));
          $.data(this, "scrollCheck", setTimeout(function () {
            $('#lecMain').removeClass('scrolling');
          }, 350));
        });
        // title 中的 version name lecMainTitle 是固定的, 加在 這個事件一次即可
        $('#lecMainTitle').on({
          click: function (e) {
            var idx = ps.version.indexOf(versionSelect.dom.find('li[cname=' + $(this).children('.closeButton').attr('cname') + ']').attr('book'));
            ps.version.splice(idx, 1);
            ps.cname.splice(idx, 1);
            versionSelect.dom.find('li[cname=' + $(this).children('.closeButton').attr('cname') + ']').removeClass('selected');
            //Set Default version?
            if (ps.version.length == 0) {
              var o = versionSelect.dom.find('li:eq(0)');
              ps.version.push(o.attr('book'));
              ps.cname.push(o.attr('cname'));
              versionSelect.dom.find('li:eq(0)').addClass('selected');
            }
            setPageState(ps);
            fhlLecture.render(ps, fhlLecture.dom);
            e.stopPropagation();
          }
        }, '.versionName');
        // 內容中的 lecMain 是固定的, 加在這個事件一次即可
        $lecMain.on({
          click: function (e) {
            if ($(this).hasClass('copyright')) //版本宣告,應該不能click snow add 2016.01.22(五)
              return;
            var mode = $lecMain.attr('mode'); //0: 原本, 1:好選擇

            var oldsec = ps.sec
            var oldchap = ps.chap

            ps.sec = parseInt($(this).attr('sec'));
            ps.chap = parseInt($(this).attr('chap'));

            if (mode == 0) {
              $(that).find('.lec').removeClass('selected');
              $(this).addClass('selected');
            }
            else if (mode == 1 || mode == 2) {
              var vers = $lecMain.find(".vercol");
              vers.children().removeClass('selected');//這個要將前一次的selected去掉.不然會累積一堆
              var verses = vers.find('[sec=' + ps.sec + ']');
              verses.addClass('selected');
            }

            setPageState(ps);
            fhlInfo.render(ps);

            // 因為搜尋還沒有加事件, 這個是暫時用的 2017.09
            var idx = getBookFunc("index", ps.chineses);
            ps.bookIndex = idx + 1; // 此idx回傳是 0-based

            // 2017.08
            if (oldsec != ps.sec || oldchap != ps.chap)
              $(that).trigger('secchanged')
          }
        }, '.lec');
        // sn 的部分
        $lecMain.on({
          click: function () {
            if (ps.realTimePopUp != 1) {
              var offset = $(this).offset();
              offset.top += $(this).height();
              ps.N = $(this).attr('N');
              // console.log($(this).html()) // &lt;09002&gt; 就是 <09002>
              var k = $(this).html().replace(/&lt;/g, "").replace(/&gt;/g, "");
              k = k.replace(/\(/g, "").replace(/\)/g, ""); // 可能是 (09002)
              k = k.replace(/\{/g, "").replace(/\}/g, "");// 可能是 {09002}
              ps.k = k; // 9002
              parsingPopUp.render(ps, parsingPopUp.dom, offset);
            }
          },
          mouseenter: function () {
            if (ps.realTimePopUp == 1) {
              var offset = $(this).offset();
              //console.log(offset.top);
              offset.top += $(this).height();
              //console.log(offset.top);
              //console.log('');
              ps.N = $(this).attr('N');
              var k = $(this).html().replace(/&lt;/g, "").replace(/&gt;/g, "");
              k = k.replace(/\(/g, "").replace(/\)/g, "");
              k = k.replace(/\{/g, "").replace(/\}/g, "");
              ps.k = k;
              setTimeout(function () { parsingPopUp.render(ps, parsingPopUp.dom, offset) }, 100);
            }
          },
          mouseleave: function () {
            if (ps.realTimePopUp == 1) {
              $.data($('#parsingPopUp')[0], "parsingPopUpAutoCloseTimeout", setTimeout(function () {
                if ($('#parsingPopUp').css('display') == 'block') {
                  $('#parsingPopUp').hide();
                }
              }, 100));
            }
          }
        }, '.sn');
        // 向後巡覽 / 向前巡覽
        var $vhb = $('#viewHistoryButton');
        $vhb.on({
          click: function (e) {
            $lecture.trigger('bclick');// fhlLecture
          }
        }, '.b').on({
          click: function (e) {
            $lecture.trigger('nclick');// fhlLecture
          }
        }, '.n');
        (function () {
          function recolor(e, p1) {
            /// <summary> 當 viewHistory 資料或 idx 變的時候, 要判斷是不是灰色 (document的vh_idxchanged事件與vh_itemschanged事件) </summary>
            if (p1.datas.length - 1 == p1.idx)
              $vhb.find('.b').css('color', 'darkgray');
            else
              $vhb.find('.b').css('color', 'black');
            if (p1.idx == 0)
              $vhb.find('.n').css('color', 'darkgray');
            else
              $vhb.find('.n').css('color', 'black');
          }
          $(document).on(
            {
              vh_idxchanged: recolor,
              vh_itemschanged: recolor
            });
        })();

        // .ft 注腳 click
        $lecMain.on({
          click: function (e) {
            //console.log(this); //範例: <span class=ft ft=42 ver=tcv chap=2>【42】</span>
            // http://bkbible.fhl.net/json/rt.php?engs=Gen&chap=2&version=tcv&gb=0&id=42

            var offset = $(this).offset();
            offset.top += $(this).height() + 10;
            parsingPopUp.render(ps, parsingPopUp.dom, offset, "ft");

            var ftid = $(this).attr('ft');
            var engs = $(this).attr('engs');
            var chap = $(this).attr('chap');
            var ver = $(this).attr('ver');

            var url = "rt.php?engs=" + engs + "&chap=" + chap + "&version=" + ver + "&id=" + ftid;
            if (ps.gb == 1)
              url += "&gb=1";
            fhl.json_api_text(url, function (a1, a2) {
              var json = JSON.parse(a1);
              if (json.status == "success" && json.record.length > 0) {
                var txt = json.record[0].text;
                $('#parsingPopUpInside').text(txt);
                $('#parsingPopUpInside').css("width", "100%");
                $('#parsingPopUpInside').css("max-width", "323px"); //cy:200px乘黃金比例1.618
                $('#parsingPopUpInside').css("white-space", "normal");
              }
              else {
                $('#parsingPopUpInside').text("錯誤:可回報下訊息- " + a1);
              }
            }, function (a1, a2) {
              $('#parsingPopUpInside').text("錯誤:於" + url + "時發生");
            }, null);
          }
        }, '.ft');

        // 地圖(綠色那個)click時, 發出sobj_pos訊息給地圖那邊接受
        $lecMain.on({
          'click': function (e) {
            try {
              var sobj = $(this).parent(".sobj");
              var sid = sobj.attr('sid');
              $(document).trigger('sobj_pos', { sid: sid });
            } catch (ex) { }
          }
        }, 'img.pos');
      };// fn.init

      fn.when_bclick_or_nclick = function (fnb, fnn) {
        /// <summary> fhlLecture 提供的 event </summary>
        /// <param type="fn(e)" name="fnb" parameterArray="false">older history view</param>
        /// <param type="fn(e)" name="fnn" parameterArray="false">newer history view</param>
        $lecture.on({
          bclick: fnb,
          nclick: fnn
        });
      };

      fn.selectLecture = function (book, chap, sec) {
        var that = this.dom;
        that.find('.lec').removeClass('selected');
        var obj = that.find('.lec' + '[sec="' + sec + '"]');
        if (obj) {
          obj.addClass('selected');
          if (obj.position()) {
            var lecMain = $('#lecMain');
            if (obj.position().top > lecMain.height() || obj.position().top < 0)
              lecMain.scrollTop(lecMain.scrollTop() + obj.position().top - lecMain.height() / 2);
            else
              lecMain.scrollTop(lecMain.scrollTop());
          }
          else {
            console.log("no position");
          }
        }
      };
      fn.reshape = function (ps) {
        /// <summary> 目前主要是 mode=1 時, align 要重新排過, 會用到的有 fontSize, resize,(在windowAdjust裡呼叫) 裡面會有 show_mode 判斷式, 只要直接呼叫即可 </summary>
        if (ps.show_mode == 1) {
          /// @verbatim 對齊必須在 dom.html(html) 之後才作, 因為那時候才會有實體, 否則取出來的 height() 會是 0@endverbatim
          var $lecMain = $('#lecMain');
          var cols = $lecMain.children();
          var qcols = Enumerable.From(cols);
          var qvers = qcols.Select(function (a1) { return $(a1).children(); });
          // console.log(qvers.ToArray());
          var maxRecordCnt = qvers.Max('$.length');
          //console.log(maxRecordCnt);

          for (var i = 0; i < maxRecordCnt; i++) {
            var qvers2 =
              qvers.Select(function (a1) { if (a1[i] == null) return null; return a1[i] });
            qvers2.ForEach(function (a1) { if (a1 != null) $(a1).height('100%'); }); //要先變為auto, 才能正確算 最大的 cy
            var maxcy = qvers2.Max(function (a1) { return a1 == null ? 0 : $(a1).height() });
            //var maxcy = Math.max.apply(Math, qvers2.Select(function (a1) { return $(a1).height(); }).ToArray());
            //console.log(maxcy);
            qvers2.ForEach(function (a1) { if (a1 != null) $(a1).height(maxcy); });
          }
        }
      };

      fn.registerEvents = function (ps) {
        var that = this.dom;

        // snow add
        var $lecMain = $('#lecMain');
        var mode = $lecMain.attr('mode'); //0: 原本, 1:好選擇

        // 移到 init 完成
        //that.find('.lec').click(function(){

        // 移到 init 完成
        //$('.versionName').click(function(e){

        // 移到 init 完成
        //if(ps.realTimePopUp==1){

        //下面3個已經拉到 init , 只需1次
        //$('.chapBack').click(function(e){});
        //$('.chapNext').click(function(e){});
        //$('#lecMain').scroll(function () { });

        // .ft click 也移到 init 完成
      };
      fn.render = function (ps, dom) {
        //console.log('start of fhlLecture render');
        function reverse(s) {
          var o = '';
          for (var i = s.length - 1; i >= 0; i--)
            o += s[i];
          return o;
        }
        var $lec = $(this.dom);
        var that = this;
        var htmlTitle = "";
        var htmlContent = "";
        var col = ps.version.length;
        var rspArr = new Array();
        var idx = 0;
        getBibleText(col, ps, function (o) {
          rspArr.push(o);
        }, function () {
          var isOld = checkOldNew(ps);

          // 恢復本 2018.03 snow add
          for (j = 0; j < rspArr.length; j++) {
            if (rspArr[j].version == 'recover') {
              if (rspArr[j].record[0].sec == 0) {
                var sec1 = rspArr[j].record[1];
                var sec0 = rspArr[j].record[0];
                sec1.bible_text = "(" + sec0.bible_text + ")" + sec1.bible_text;

                rspArr[j].record.shift();
                --rspArr[j].record_count;
              }
              break;
            }
          }

          rspArr = sortBibleVersion(rspArr, ps);

          // nextchap prevchap
          var bookName = getBookFunc("bookFullName", ps.chineses);
          if (bookName != "failed") {
            if (ps.chineses == book[0] && ps.chap == 1) {
              $lec.find('.chapBack').first().css('display', 'none');
            } else {
              $lec.find('.chapBack').first().css('display', 'block');
            }
            if (ps.chineses == book[65] && ps.chap == 22) {
              $lec.find('.chapNext').first().css('display', 'none');
            } else {
              $lec.find('.chapNext').first().css('display', 'block');
            }
          }

          // get maxRecordCnt maxRecordIdx
          var maxRecordCnt = 0;
          var maxRecordIdx = 0;
          for (var i = 0; i < rspArr.length; i++) {
            if (rspArr[i].record_count > maxRecordCnt) {
              maxRecordCnt = rspArr[i].record_count;
              maxRecordIdx = i;
              //console.log("maxRecordCnt:"+maxRecordCnt+",maxRecordIdx:"+maxRecordIdx);
            }
          }

          // title
          var dtitle = $('#lecMainTitle');
          dtitle.empty();
          for (var i = 0; i < rspArr.length; i++) {
            var o = rspArr[i];
            if (o.v_name === "原文直譯(參考用)")
              dtitle.append($("<div class=lecContent><div class=versionName>" + o.v_name + "<span class='closeButton' cname='" + "原文直譯" + "'>&#215</span></div></div>"));
            else
              dtitle.append($("<div class=lecContent><div class=versionName>" + o.v_name + "<span class='closeButton' cname='" + o.v_name + "'>&#215</span></div></div>"));
          }

          //var mode = 1;// 原本的. 就切回0
          var mode = ps.show_mode;
          switch (mode) {
            case 0:
              {
                // 每一節 i, 以最大的那個版本為主 maxR
                for (var i = 0; i < maxRecordCnt; i++) {
                  var maxR = rspArr[maxRecordIdx].record[i];
                  htmlContent += "<div class=lec style='font-size: " + ps.fontSize + "pt; line-height: " + ps.fontSize * 1.25 + "pt; margin-top: " + (ps.fontSize * 1.25 - 15) + "px'>";
                  //htmlContent+="<div class=lecTitle>"+maxR.chap+":"+maxR.sec+"</div>";
                  for (j = 0; j < rspArr.length; j++) {
                    var chap = maxR.chap, sec = maxR.sec;
                    var rec = getRecord(rspArr[j].record, null, chap, sec);
                    //var r=rspArr[j].record[i];
                    if (rec != null) {
                      var bibleText = parseBibleText(rec.bible_text, ps, isOld, rspArr[j].v_name);
                      if (bibleText == "a")
                        bibleText = "【併入上節】";
                    } else {
                      bibleText = "";
                    }
                    if (rspArr[j].version == "bhs") {
                      var bibleText = bibleText.split(/\n/g).reverse().join("<br>");
                      //console.log(bibleText);
                    }
                    else if (rspArr[j].version == "cbol") {
                      var bibleText = bibleText.split(/\n/g).join("<br>");
                      //console.log(bibleText);
                    }
                    else if (rspArr[j].version == "nwh") {
                      var bibleText = bibleText.split(/\n/g).join("<br>");
                    }

                    var className = '';
                    if (rspArr[j].version == "thv12h") // 2018.01 客語特殊字型(太1)
                      className += 'bstw '

                    htmlContent += "<div class='lecContent " + rspArr[j].version + "'><div class='bstw' style='margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;'><span class='verseNumber'>" + maxR.sec + "</span><span class='verseContent'>" + bibleText + "</span></div></div>";
                  }
                  htmlContent += "</div>";
                }
              }
              break;
            case 1:
              {
                // 注意, 這個變數, 只是暫存的, 它輽出的結果是 html 文字, 不包含自己, 所以lecMain屬性是在另種設定, 不是在這
                // 不要再從這裡改 <div style=padding:10px 50px></div>, 不會有效果的.
                var $htmlContent = $("<div id='lecMain'></div>");

                var cx1 = 100 / rspArr.length;
                for (j = 0; j < rspArr.length; j++) {
                  // 分3欄
                  var onever = $("<div class='vercol' style='width:" + cx1 + "%;display:inline-block;vertical-align:top;font-size: " + ps.fontSize + "pt; line-height: " + ps.fontSize * 1.25 + "pt; margin-top: " + (ps.fontSize * 1.25 - 15) + "px'></div>");
                  $htmlContent.append(onever);
                }

                // 每1欄內容
                for (j = 0; j < rspArr.length; j++) { //each version
                  for (var i = 0; i < rspArr[j].record_count; i++) {//each sec
                    var maxR = rspArr[j].record[i]; //原 var maxR = rspArr[maxRecordIdx].record[i];
                    var chap = maxR.chap, sec = maxR.sec;
                    var rec = rspArr[j].record[i]; //原 var rec = getRecord(rspArr[j].record, null, chap, sec);

                    var bibleText = "";
                    if (rec != null)
                      bibleText = parseBibleText(rec.bible_text, ps, isOld, rspArr[j].v_name);
                    else
                      bibleText = "";
                    if (bibleText == "a") {
                      bibleText = "【併入上節】";
                    }

                    if (rspArr[j].version == "bhs") {
                      bibleText = bibleText.split(/\n/g).reverse().join("<br>");
                      //console.log(bibleText);
                    }
                    else if (rspArr[j].version == "cbol") {
                      bibleText = bibleText.split(/\n/g).join("<br>");
                      //console.log(bibleText);
                    }
                    else if (rspArr[j].version == "nwh") {
                      bibleText = bibleText.split(/\n/g).join("<br>");
                    }

                    // 2018.01 客語特殊字型(太1)
                    var className = 'verseContent ';
                    if (rspArr[j].version == "thv12h" || rspArr[j].version == 'ttvh')
                      className += ' bstw'

                    $htmlContent.children().eq(j).append(
                      $("<div ver='" + rspArr[j].version + "' chap=" + chap + " sec=" + sec + " class='lec'><div style='margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;'><span class='verseNumber'>" + sec + "</span><span class='" + className + "'>" + bibleText + "</span></div></div>"));

                  }//for each verse
                }//for each version

                // add 2016.10 地圖與照片
                if (ps.ispos || ps.ispho) {
                  var url2 = "sobj.php?engs=" + ps.engs + "&chap=" + ps.chap;
                  if (ps.gb == 1)
                    url2 += "&gb=1";
                  fhl.json_api_text(url2, function (aa1, aa2) {
                    var jrr1 = JSON.parse(aa1);
                    //console.log(jrr1);

                    var id2reg = {};
                    var id2obj = {};
                    $.each(jrr1.record, function (aaa1, aaa2) {
                      var id = aaa2.id.toString();
                      var nas = {};//Egyte,埃及,埃及. 就可以排除同樣名稱的
                      nas[aaa2.cname] = 1;
                      nas[aaa2.c1name] = 1;
                      nas[aaa2.c2name] = 1;
                      if (aaa2.ename != null && aaa2.ename.trim().length != 0)
                        nas["[ ,\\n:;\\.]" + aaa2.ename + "[ ,\\n:;\\.]"] = 1;//斷開英文可能結尾「空白,逗號,句號,冒號, 2016.11
                      //nas[aaa2.ename] = 1;

                      var nas2 = [];
                      $.each(nas, function (b1, b2) {
                        // 2016.10 nas2 若出現 ()會造成一定成立.
                        if (b1 != null && b1.trim().length != 0)
                          nas2.push(b1);
                      });

                      var regstr = "((" + nas2.join(")|(") + "))"; // ((羅馬)|([空白字元]Rome[空白字元]))
                      var regex = new RegExp(regstr, "i");
                      id2obj[id] = aaa2;
                      id2reg[id] = regex;
                    }, null);
                    $htmlContent.find(".verseContent").each(function (c1, c2) {
                      var str = c2.innerHTML;
                      var ischanged = false;

                      // 每1節都要測所有的 regex, 並取代
                      $.each(id2reg, function (b1, b2) {
                        var b3 = id2obj[b1];
                        var issite = b3.objpath == null || b3.objpath.trim().length == 0 ? false : true;
                        var isphoto = true; //目前無法判定是不是相片,全都當是 TODO

                        // 再優化部分(能不regex,就略過)
                        if (ps.ispos && ps.ispho == false && issite == false)
                          return;//next reg
                        else if (ps.ispho && ps.ispos == false && isphoto == false)
                          return;//next reg

                        if (b2.test(str)) {
                          ischanged = true;
                          //var strpho = (ps.ispho == false || isphoto == false) ? "" : "<img class='pho'></img>";
                          var strpho = (ps.ispho == false || isphoto == false) ? "" : "<a target='_blank' href='http://bible.fhl.net/object/sd.php?gb=0&LIMIT=" + b1 + "'><img class='pho'></img></a>";
                          var strsite = (ps.ispos == false || issite == false) ? "" : "<img class='pos'></img>";

                          str = str.replace(b2, "<span class='sobj' sid=" + b1 + "><span>$1</span>" + strsite + strpho + "</span>");

                        }
                      });

                      if (ischanged) {
                        c2.innerHTML = str;
                      }
                    });//each
                    htmlContent = $htmlContent.html();//.html()不包含自己 ... 所以這裡不是設 lecMain 有用的地方
                  }, function (aa1, aa2) {
                    console.error(aa1);
                  }, null, false); //第4個參數要false,要同步,否則$htmlContent還沒好就被拿來用會出問題
                }
                else
                  htmlContent = $htmlContent.html();//.html()不包含自己 ... 所以這裡不是設 lecMain 有用的地方

              }
              break;
            case 2:
              {
                // 注意, 這個變數, 只是暫存的, 它輽出的結果是 html 文字, 不包含自己, 所以lecMain屬性是在另種設定, 不是在這
                // 不要再從這裡改 <div style=padding:10px 50px></div>, 不會有效果的.
                var $htmlContent = $("<div id='lecMain'></div>");

                var onever = $("<div class='vercol' style='vertical-align:top;font-size: " + ps.fontSize + "pt; line-height: " + ps.fontSize * 1.25 + "pt; margin-top: " + (ps.fontSize * 1.25 - 15) + "px'></div>");
                $htmlContent.append(onever);

                // 每一節內容
                for (var i = 0; i < maxRecordCnt; i++) {
                  var maxR = rspArr[maxRecordIdx].record[i]; //原 var maxR = rspArr[maxRecordIdx].record[i];
                  var chap = maxR.chap, sec = maxR.sec;

                  for (var j = 0; j < rspArr.length; j++) {
                    var r1 = rspArr[j];
                    if (rspArr.length > 1)
                      var vname = "<span class='ver'> (" + r1.v_name + ")</span> "; //新譯本 合和本 etc
                    else
                      var vname = ""; //只有一種版本就不要加了

                    if (i >= r1.record_count) {
                      //此版本 本章節比較少,
                      var className = 'verseContent ';
                      if (rspArr[j].version == "thv12h" || rspArr[j].version == 'ttvh') // 2018.01 客語特殊字型(太1)
                        className += ' bstw'

                      onever.append(
                        $("<div ver='" + rspArr[j].version + "' chap=" + chap + " sec=" + sec + " class='lec'><div style='margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;'><span class='verseNumber'>" + sec + "</span><span class='" + className + "'>" + vname + "</span></div></div>"));
                    }
                    else {

                      var rec = rspArr[j].record[i]; //原 var rec = getRecord(rspArr[j].record, null, chap, sec);
                      var bibleText = "";
                      if (rec != null)
                        bibleText = parseBibleText(rec.bible_text, ps, isOld, rspArr[j].v_name);
                      else
                        bibleText = "";
                      if (bibleText == "a") {
                        bibleText = "【併入上節】";
                      }
                      if (rspArr[j].version == "bhs") {
                        bibleText = bibleText.split(/\n/g).reverse().join("<br>");
                        //console.log(bibleText);
                      }
                      else if (rspArr[j].version == "cbol") {
                        bibleText = bibleText.split(/\n/g).join("<br>");
                        //console.log(bibleText);
                      }
                      else if (rspArr[j].version == "nwh") {
                        bibleText = bibleText.split(/\n/g).join("<br>");
                      }

                      var className = 'verseContent';
                      if (rspArr[j].version == "thv12h" || rspArr[j].version == 'ttvh') // 2018.01 客語特殊字型(太1)
                        className += ' bstw'
                      onever.append(
                        $("<div ver='" + rspArr[j].version + "' chap=" + chap + " sec=" + sec + " class='lec'><div style='margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;'><span class='verseNumber'>" + sec + "</span><span class='" + className + "'>" + bibleText + vname + "</span></div></div>"));

                    }

                  }
                }

                // add 2016.10 地圖與照片
                if (ps.ispos || ps.ispho) {
                  var url2 = "sobj.php?engs=" + ps.engs + "&chap=" + ps.chap;
                  if (ps.gb == 1)
                    url2 += "&gb=1";
                  fhl.json_api_text(url2, function (aa1, aa2) {
                    var jrr1 = JSON.parse(aa1);
                    //console.log(jrr1);

                    var id2reg = {};
                    var id2obj = {};
                    $.each(jrr1.record, function (aaa1, aaa2) {
                      var id = aaa2.id.toString();
                      var nas = {};
                      nas[aaa2.cname] = 1;
                      nas[aaa2.c1name] = 1;
                      nas[aaa2.c2name] = 1;
                      nas[aaa2.ename] = 1;

                      var nas2 = [];
                      $.each(nas, function (b1, b2) {
                        // 2016.10 nas2 若出現 ()會造成一定成立.
                        if (b1 != null && b1.trim().length != 0)
                          nas2.push(b1);
                      });

                      var regstr = "((" + nas2.join(")|(") + "))"; // ((羅馬)|(Rome))
                      var regex = new RegExp(regstr, "i");
                      id2obj[id] = aaa2;
                      id2reg[id] = regex;
                    }, null);
                    $htmlContent.find(".verseContent").each(function (c1, c2) {
                      var str = c2.innerHTML;
                      var ischanged = false;

                      // 每1節都要測所有的 regex, 並取代
                      $.each(id2reg, function (b1, b2) {
                        var b3 = id2obj[b1];
                        var issite = b3.objpath == null || b3.objpath.trim().length == 0 ? false : true;
                        var isphoto = true; //目前無法判定是不是相片,全都當是 TODO

                        // 再優化部分(能不regex,就略過)
                        if (ps.ispos && ps.ispho == false && issite == false)
                          return;//next reg
                        else if (ps.ispho && ps.ispos == false && isphoto == false)
                          return;//next reg

                        if (b2.test(str)) {
                          ischanged = true;
                          //var strpho = (ps.ispho == false || isphoto == false) ? "" : "<img class='pho'></img>";
                          var strpho = (ps.ispho == false || isphoto == false) ? "" : "<a target='_blank' href='http://bible.fhl.net/object/sd.php?gb=0&LIMIT=" + b1 + "'><img class='pho'></img></a>";
                          var strsite = (ps.ispos == false || issite == false) ? "" : "<img class='pos'></img>";

                          str = str.replace(b2, "<span class='sobj' sid=" + b1 + "><span>$2</span>" + strsite + strpho + "</span>");
                        }
                      });

                      if (ischanged) {
                        c2.innerHTML = str;
                      }
                    });//each
                    htmlContent = $htmlContent.html();//.html()不包含自己 ... 所以這裡不是設 lecMain 有用的地方
                  }, function (aa1, aa2) {
                    console.error(aa1);
                  }, null, false); //第4個參數要false,要同步,否則$htmlContent還沒好就被拿來用會出問題
                }
                else
                  htmlContent = $htmlContent.html();//.html()不包含自己 ... 所以這裡不是設 lecMain 有用的地方
              } break;
          }


          $lec.find('#lecMain').first()
            .html(htmlContent)
            .attr('mode', mode);

          fhlLecture.reshape(ps);

          // 2016.01.21(四) 版權宣告 snow
          {
            var div_copyrigh = $('<div id="div_copyright" class="lec copyright"></div>');
            $('#lecMain').append(div_copyrigh); // 放在 lecMain 才會在最下面. 因為 parent 有設 position 屬性
            rr = React.createElement(copyright_api.R.frame, { ver: ps.version });
            ss = React.render(rr, document.getElementById("div_copyright"));  // snow add 2016.01.21(四),
            // bug 小心: 版權宣告 render 必須在 dom.html 之後唷, 這樣才找到的 divCopyright 實體
          }

          if (mode == 0) {
            for (var i = 0; i < maxRecordCnt; i++) {
              var r = rspArr[maxRecordIdx].record[i];
              dom.find('.lec:eq(' + i + ')').attr('chap', r.chap);
              dom.find('.lec:eq(' + i + ')').attr('sec', r.sec);
            }
          }
          setCSS(col, ps);
          setFont();
          that.selectLecture(null, null, ps.sec);

          {// 2016.08 snow, 注腳
            $lec.find('.lec').each(function (a1, a2) {
              var ver = $(a2).attr('ver');
              $(this).find('.verseContent').each(function (aa1, aa2) {
                aa2.innerHTML = aa2.innerHTML.replace(/【(\d+)】/g, "<span class=ft ft=$1 ver='" + ver + "' chap=" + ps.chap + " engs='" + ps.engs + "'>【$1】</span>");
              });

              //if ( ver == 'fhlwh')
              //{// 2016.10 snow, 新約原文,要套用字型 (剛剛好也是每個 .lec, 所以就搭注腳的forEach順風車)
              //  $(a2).css('font-family', 'COBSGreekWeb');
              //  		}
            });
          }



          that.registerEvents(ps);


        });
      };

      return new FhlLecture();
    })();

    // 2017.08
    $(function () {
      $(fhlUrlParameter).on('bible', function () {
        console.log('bible trigger')
        // console.log(fhlUrlParameter.bibleResult) // {book: 1, chap: 12, sec: 9}
        if (pageState != undefined) {
          pageState.chineses = FHL.CONSTANT.Bible.CHINESE_BOOK_ABBREVIATIONS[fhlUrlParameter.bibleResult.book - 1]
          pageState.engs = FHL.CONSTANT.Bible.ENGLISH_BOOK_ABBREVIATIONS[fhlUrlParameter.bibleResult.book - 1]
          if (fhlUrlParameter.bibleResult.book > 0) {

            pageState.bookIndex = fhlUrlParameter.bibleResult.book
            pageState.chap = fhlUrlParameter.bibleResult.chap >= 0 ? fhlUrlParameter.bibleResult.chap : 1
            pageState.sec = fhlUrlParameter.bibleResult.sec >= 0 ? fhlUrlParameter.bibleResult.sec : 1

            fhlLecture.render(pageState, fhlLecture.dom); // 內容
            bookSelect.render(pageState, bookSelect.dom); // 內容的 title
          }
        }
      }) // bible event
      $(window).trigger('hashchange')

      $(fhlLecture).on('chapchanged', function () {
        var bookEn = FHL.CONSTANT.Bible.ENGLISH_BOOK_SHORT_ABBREVIATIONS[pageState.bookIndex - 1]
        history.pushState(null, null, '#/bible/' + bookEn + '/' + pageState.chap)
      });
      $(fhlLecture).on('secchanged', function () {
        var bookEn = FHL.CONSTANT.Bible.ENGLISH_BOOK_SHORT_ABBREVIATIONS[pageState.bookIndex - 1];
        history.replaceState(null, null, '#/bible/' + bookEn + '/' + pageState.chap + '/' + pageState.sec)
      });
      $(fhlLecture).trigger('secchanged')

      $(bookSelectChapter).on('chapchanged', function () {
        var bookEn = FHL.CONSTANT.Bible.ENGLISH_BOOK_SHORT_ABBREVIATIONS[pageState.bookIndex - 1]
        history.pushState(null, null, '#/bible/' + bookEn + '/' + pageState.chap)
      })
    });


    var fhlMidBottomWindow = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, dom);
        this.registerEvents(ps);
      },
      registerEvents: function (ps) {
        $('#fhlMidBottomWindow').resizable({
          handles: 'n',
          maxHeight: 600,
          minHeight: 100,
          resize: function (event, ui) {
            var height = $('#mainWindow').height() - ui.size.height - 115 + 15;
            $("#fhlLecture").css({
              'height': height + 'px',
            });
            $(this).css({
              'width': '100%'
            });
          }
        });
        $('.ui-resizable-handle.ui-resizable-n').html('<span>&#9776;</span>');
      },
      render: function (ps, dom) {
        $('#fhlMidBottomWindow').css({ 'top': $('#fhlLecture').height() + 12 + 'px' });
        var div_pre_search = document.createElement("div");
        div_pre_search.id = "pre_search";
        $(div_pre_search).css("font-size", "10pt");
        var div_search_result = document.createElement("div");
        div_search_result.id = "search_result";
        $(div_search_result).css("font-size", "10pt");
        document.getElementById("fhlMidBottomWindowContent").innerHTML = "";
        document.getElementById("fhlMidBottomWindowContent").appendChild(div_pre_search);
        document.getElementById("fhlMidBottomWindowContent").appendChild(div_search_result);
      }
    };
    /***** End of fhlMidWindow *****/

    /***** Start of fhlInfo *****/
    var fhlInfo = {
      init: function (ps) {
        bibleAudio.init(ps, $('#bibleAudio'));
        bibleAudio.registerEvents(ps);
        fhlInfoTitle.init(ps, $('#fhlInfoTitle'));
        fhlInfoTitle.registerEvents(ps);
        fhlInfoContent.init(ps, $('#fhlInfoContent'));
        fhlInfoContent.registerEvents(ps);
        parsingPopUp.init(ps, $('#parsingPopUp'));
        this.registerEvents();
        this.render(ps);
        var fhlInfoWidth = 500;//這邊改了，css裡面也要改
        $('#fhlInfo').css({ 'left': $(window).width() - fhlInfoWidth - 12 + 'px' });// 12 是外面border

        // snow add, 2016.10 經文中的地點mark被click,
        $(document).on({
          'sobj_pos': function (e, p1) {
            if (ps.titleId == "fhlInfoMap") {
              rfhlmap.set_active(p1.sid);
            }
          }
        });
      },
      registerEvents: function () {
        $('#fhlInfo').resizable({
          handles: 'w',
          maxWidth: 1000,
          minWidth: 300,
          resize: function (event, ui) {
            var currentWidth = ui.size.width;
            var width = 0;
            if ($("#fhlLeftWindow").css('left') == '12px')
              width = $(window).width() - $("#fhlLeftWindow").width() - currentWidth;
            else
              width = $(window).width() - currentWidth + 12;
            $("#fhlMidWindow").css({
              'width': width - 48 + 'px',
              'right': currentWidth + 'px'
            });

            // snow add 2016-07
            fhlLecture.reshape(pageState);
          }
        });
        $('.ui-resizable-handle.ui-resizable-w').html('<span>&#9776;</span>');
      },
      render: function (ps) {
        //fhlInfoTitle.render(ps,$('#fhlInfoTitle'));
        fhlInfoContent.render(ps, fhlInfoContent.dom);
      }
    };

    var bibleAudio = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {

      },
      render: function (ps, dom) {
        //var html="有聲聖經 ";
        //if(ps.chineses==book[0]&&ps.chap==1){
        //  html+="";
        //}else{
        //  html+="<img class='menuImage' src='./static/images/lastChapter.png'/>";
        //}
        //if(ps.audio==0){
        //  html+="<img class='menuImage' src='./static/images/audioPlay.png'/>";
        //}else{
        //  html+="<img class='menuImage' src='./static/images/audioPause.png'/>";
        //}
        //if(ps.chineses==book[65]&&ps.chap==22){
        //  html+="";
        //}else{
        //  html+="<img class='menuImage' src='./static/images/nextChapter.png'/>";
        //}
        //dom.html(html);
      }
    }

    var fhlInfoTitle = {
      init: function (ps, dom) {
        this.dom = dom;
        this.title = [
          { "name": "原文", "id": "fhlInfoParsing" },
          { "name": "註釋", "id": "fhlInfoComment" },
          { "name": "講道", "id": "fhlInfoPreach" },
          { "name": "串珠", "id": "fhlInfoTsk" },
          { "name": "典藏", "id": "fhlInfoOb" },
          { "name": "有聲", "id": "fhlInfoAudio" },
          { "name": "地圖", "id": "fhlInfoMap" }
        ];
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        //select all elements of info title
        var selectAll = "";
        for (var i = 0; i < this.title.length; i++) {
          selectAll += "#" + this.title[i].id + ",";
        }
        selectAll = selectAll.substring(0, selectAll.length - 1);
        $(selectAll).click(function () {
          $(selectAll).removeClass('selected');
          $(this).addClass('selected');
          ps.titleIdold = ps.titleId; // add 2015.12.10(四) 為了有聲聖經,切換問題
          ps.titleId = $(this).attr('id');
          setPageState(ps);
          fhlInfoContent.render(ps, fhlInfoContent.dom);
        });
      },
      render: function (ps, dom) {
        var html = "<ul>";
        for (var i = 0; i < this.title.length; i++) {
          html += "<li>" + this.title[i].name + "</li>";
        }
        html += "</ul>";
        dom.html(html);
        for (var i = 0; i < this.title.length; i++) {
          dom.find('li:eq(' + i + ')').attr('id', this.title[i].id);
        }
        $('#' + ps.titleId).addClass('selected');
      }
    };

    var fhlInfoContent = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        var that = this;
        switch (ps.titleId) {
          case "fhlInfoParsing":
            if (ps.realTimePopUp == 1) {
              $('.parsing').mouseenter(function () {
                var offset = $(this).offset();
                offset.top += $(this).height() + 10;
                ps.N = $(this).attr('N');
                ps.k = $(this).attr('k');
                var par = decodeURIComponent($(this).attr('par'));
                parsingPopUp.render(ps, parsingPopUp.dom, offset, par);
              });
              /*$('.parsing').mouseleave(function(){
                parsingPopUp.dom.hide();
              });*/
              $('.parsingTableSn').mouseenter(function () {
                var offset = $(this).offset();
                offset.top += $(this).height() + 10;
                ps.N = $(this).attr('N');
                ps.k = $(this).attr('k');
                parsingPopUp.render(ps, parsingPopUp.dom, offset);
              });
              /*$('.parsingTable').mouseleave(function(){
                parsingPopUp.dom.hide();
              });*/
            } else {
              $('.parsing').click(function () {
                var offset = $(this).offset();
                offset.top += $(this).height() + 10;
                ps.N = $(this).attr('N');
                ps.k = $(this).attr('k');
                var par = decodeURIComponent($(this).attr('par'));
                parsingPopUp.render(ps, parsingPopUp.dom, offset, par);
              });
              $('.parsingTableSn').click(function () {
                var offset = $(this).offset();
                offset.top += $(this).height() + 10;
                ps.N = $(this).attr('N');
                ps.k = $(this).attr('k');
                parsingPopUp.render(ps, parsingPopUp.dom, offset);
              });
            }

            $('.parsingTableSn').mouseleave(function () {
              if (ps.realTimePopUp == 1) {
                $.data($('#parsingPopUp')[0], "parsingPopUpAutoCloseTimeout", setTimeout(function () {
                  if ($('#parsingPopUp').css('display') == 'block') {
                    $('#parsingPopUp').hide();
                  }
                }, 100));
              }
            });
            $('.parsingSecBack, .parsingSecNext').click(function () {
              var oldEngs = ps.engs;
              var oldChap = ps.chap;
              ps.engs = $(this).attr('engs');
              var idx = getBookFunc('indexByEngs', ps.engs);
              ps.chineses = book[idx];
              ps.chap = $(this).attr('chap');
              ps.sec = $(this).attr('sec');
              setPageState(ps);
              bookSelect.render(ps, bookSelect.dom);
              if (oldEngs != ps.engs || oldChap != ps.chap)
                fhlLecture.render(ps, fhlLecture.dom);
              fhlInfo.render(ps);
              fhlLecture.selectLecture(null, null, ps.sec);
              viewHistory.render(ps, viewHistory.dom);
            });
            break;
          case "fhlInfoComment":
            // 2017.12
            $('.sn').click(function () {
              var sn = $(this).attr('sn');
              var offset = $(this).offset();
              offset.top += $(this).height() + 10;
              // ps.N = $(this).attr('N');
              ps.N = 1;
              ps.k = sn;
              parsingPopUp.render(ps, parsingPopUp.dom, offset, null);
            });

            $('.commentSecBack, .commentSecNext, .commentJump').click(function () {
              var oldEngs = ps.engs;
              var oldChap = ps.chap;
              ps.engs = $(this).attr('engs');
              var idx = getBookFunc('indexByEngs', ps.engs);
              ps.chineses = book[idx];
              ps.chap = $(this).attr('chap');
              ps.sec = $(this).attr('sec');
              setPageState(ps);
              bookSelect.render(ps, bookSelect.dom);
              /*if(oldEngs!=ps.engs||oldChap!=ps.chap)
                fhlLecture.render(ps,fhlLecture.dom);*/
              fhlLecture.render(ps, fhlLecture.dom);
              fhlInfo.render(ps);
              $('#fhlInfoContent').scrollTop(0);
              viewHistory.render(ps, viewHistory.dom);
            });

            $('.commentBackground').click(function () {
              if (ps.chap != 0 && ps.chap != 0) {
                ps.commentBackgroundChap = ps.chap;
                ps.commentBackgroundSec = ps.sec;
                ps.engs = $(this).attr('engs');
                var idx = getBookFunc('indexByEngs', ps.engs);
                ps.chineses = book[idx];
                ps.chap = $(this).attr('chap');
                ps.sec = $(this).attr('sec');
                fhlInfo.render(ps);
                $('#fhlInfoContent').scrollTop(0);
              }
              else {
                ps.chap = ps.commentBackgroundChap;
                ps.sec = ps.commentBackgroundSec;
                fhlInfo.render(ps);
              }
            });

            $('.commentJump').css({
              "display": "inline-block",
              "cursor": "pointer",
              "color": "rgba(50, 50, 100, 1)"
            }).hover(function () {
              $(this).css({
                "color": "rgba(200, 0, 0, 1)",
                "text-decoration": "underline"
              });
            }, function () {
              $(this).css({
                "color": "rgba(50, 50, 100, 1)",
                "text-decoration": "none"
              });
            }
            );
            $('#commentScrollDiv').scroll(function () {
              $(this).addClass('scrolling');
              clearTimeout($.data(this, "scrollCheck"));
              $.data(this, "scrollCheck", setTimeout(function () {
                $('#commentScrollDiv').removeClass('scrolling');
              }, 350));
            });
            break;
          default:
            break;
        }
      },
      render: function (ps, dom) {
        var that = this;
        switch (ps.titleId) {
          case "fhlInfoParsing":
            var html = "";
            var ajaxUrl = getAjaxUrl("qp", ps);
            $.ajax({
              url: ajaxUrl
            }).done(function (d, s, j) {
              //console.log(d);// d 是回傳 純文字版, 但直接 JSON.parse 就要要用到的資料 (羅16:24有問題)
              //console.log(s);// s 是回傳 success 字串
              //console.log(j);// j 是回傳 ??物件, 總之 j.responseText 即是 d
              if (j) {
                var jsonObj = JSON.parse(j.responseText);
                // console.log(jsonObj);
                var v_name = jsonObj.v_name;
                var version = jsonObj.version;
                var prev_chineses = jsonObj.prev.chineses;
                var prev_engs = jsonObj.prev.engs;
                var prev_chap = jsonObj.prev.chap;
                var prev_sec = jsonObj.prev.sec;
                var next_chineses = jsonObj.next.chineses;
                var next_engs = jsonObj.next.engs;
                var next_chap = jsonObj.next.chap;
                var next_sec = jsonObj.next.sec;
                var proc = jsonObj.proc;
                var div_name = ps.titleId;
                if (version == "cbol") proc = 10;//原文直譯
                var orig_font;
                var head_str = "";
                var chap_ctrl_str = "";
                var body_str = "";
                var clrstr = "";
                var clrcnt = 0;
                var N = jsonObj.N;
                if (N == 0) orig_font = "g1";
                else orig_font = "g2";
                var html = jsonObj.N + "</br>";
                for (var i = 0; i < jsonObj.record.length; i++) {
                  var wid = jsonObj.record[i].wid;
                  var word = jsonObj.record[i].word;
                  //console.log("word= " + word);
                  var exp = jsonObj.record[i].exp;
                  var id = jsonObj.record[i].id;
                  var parallel = "";
                  var align_str = "";
                  if (wid == 0) {
                    // 處理上面半部, 原文與中文部分 wid = 0 ( 下面 wid != 就是畫成 table 部分 )
                    if (N == 0)//NT (新約)
                    {
                      var wstr = "";
                      var wd = word.split("+");
                      //console.log("wd= " + wd);
                      if (wd.length > 0) {
                        for (var ii = 0; ii < wd.length; ii++) {
                          if (ii % 3 == 0)
                            wstr = wstr + wd[ii];
                          else if (ii % 3 == 1)
                            wstr = wstr + "(韋：" + wd[ii] + ")";
                          else if (ii % 3 == 2)
                            wstr = wstr + "(聯：" + wd[ii] + ")";
                        }
                        word = wstr;
                        //console.log(word);
                      }
                    }
                    else if (N == 1) //OT (舊約)
                    {
                      var remark = jsonObj.record[i].remark;
                      var engs = jsonObj.record[i].engs;
                      if (remark.length > 0) {
                        parallel = "平行經文：" + remark;
                      }
                      align_str = "align=\"right\" style=\"padding:0px 10px 0px 0px;\"";
                    }

                    var bookName = getBookFunc("bookFullName", ps.chineses);

                    // record[0]中的 word,
                    if (bookName != "failed") {
                      if (ps.chineses == book[0] && ps.chap == 1 && ps.sec == 1) {
                        chap_ctrl_str += "";
                      } else {
                        chap_ctrl_str += "<div class='parsingSecBack' ";
                        chap_ctrl_str += "engs=" + prev_engs + " chap=" + prev_chap + " sec=" + prev_sec;
                        chap_ctrl_str += "><span>&#x276e;</span></div>";
                      }
                      if (ps.chineses == book[65] && ps.chap == 22 && ps.sec == 21) {
                        chap_ctrl_str += "";
                      } else {
                        chap_ctrl_str += "<div class='parsingSecNext' ";
                        chap_ctrl_str += "engs=" + next_engs + " chap=" + next_chap + " sec=" + next_sec;
                        chap_ctrl_str += "><span>&#x276f;</span></div>";
                      }
                      chap_ctrl_str += "<div style='position: absolute; top: 10px; left: 15px; /*transform: translate(-50%, 0%);*/ font-size: 12pt; color: rgba(100, 100, 100, 0.5);'>" + bookName;
                      chap_ctrl_str += "&nbsp&nbsp" + ps.chap + ":" + ps.sec + "</div>";
                    }
                    /*
                    var poverhead="",noverhead="";
                    if (prev_chineses!=chineses||prev_chap!=chap)
                        poverhead=";Gclick=false;Gsec="+prev_sec+";read_bible('"+chineses+"',"+prev_chap+");";
                    if (next_chineses!=chineses||next_chap!=chap)
                        noverhead=";Gclick=false;Gsec="+next_sec+";read_bible('"+chineses+"',"+next_chap+");";
                        head_str="<span style=\"font-size:150%;\"><a href=\"javascript:spar('"+prev_engs+"',"+prev_chap+","+prev_sec+",'"+div_name+"')"+
                        poverhead+"\">&lt;</a> <span class=\"psn\">"+
                        chinesef+"  "+chap+":"+sec
                        +"</span> <a href=\"javascript:spar('"+next_engs+"',"+next_chap+","+next_sec+",'"+div_name+"')"+
                        noverhead+"\">&gt;</a></span> "+parallel+"<br/>";
                    */
                    var nword = word.split("\n");// [0].word變 nword(舊約split後會反序,不知為何)
                    var nexp = exp.split("\n");
                    if (N == 1) {//OT
                      var wid = 1;
                      console.log("nword length=" + nword.length);
                      for (var ii = 0; ii < nword.length; ii++) {
                        var t = nword[nword.length - ii - 1].split(" +"); // " +"是必須同時存在,不是其中1個符號存在即可.
                        if (t.length !== 1)
                          console.dir("t.length=" + t.length);
                        head_str += "<div>";
                        for (var iii = 0; iii < t.length; iii++) {
                          if (t[iii].indexOf(" ") == -1 && t[iii].indexOf("-") == -1) {
                            // 大部分都不成立, 都是另1個.
                            var sn = jsonObj.record[wid].sn;
                            var wform = jsonObj.record[wid].wform;
                            var orig = jsonObj.record[wid].orig;
                            var remark = jsonObj.record[wid].remark;
                            var exp1 = jsonObj.record[wid].exp;
                            var par = encodeURIComponent(wform + '|' + orig + '|' + exp1 + '|' + remark + '|');
                            head_str += "<span class=parsing N=1 k=" + sn + " par=" + par + ">";
                            head_str += t[iii] + "&nbsp</span>";
                            wid++;
                          } else {
                            var no_padding_str = t[iii];
                            for (var index = t[iii].length - 1; ; index--) {
                              if (t[iii].charAt(index) != " " && t[iii].charAt(index) != "\n") {
                                // console.log(t[iii] + " index:"+index +" t[iii].length:"  +  t[iii].length);
                                no_padding_str = t[iii].substr(0, index + 1);
                                break;// 大部分是 t[iii].length-1, 第1個, 就是成立的(不是空白也不是\n)
                              }
                            }
                            var start_pos = no_padding_str.search(/[^\u000A-\u0020]/); // 開始的符號(其中包含0x20空白, 回車0x10, 換行0x13
                            // console.log("start_pos="+start_pos);
                            do {
                              try {
                                var sn = jsonObj.record[wid].sn;
                                var wform = jsonObj.record[wid].wform;
                                var orig = jsonObj.record[wid].orig;
                                var remark = jsonObj.record[wid].remark;
                                var exp1 = jsonObj.record[wid].exp;
                                var par = encodeURIComponent(wform + '|' + orig + '|' + exp1 + '|' + remark + '|');
                              } catch (e) {
                                console.log("e" + e)
                              }
                              head_str += "<span class=parsing N=1 k=" + sn + " par=" + par + ">";
                              wid++;

                              var next_s = no_padding_str.indexOf(" ", start_pos); // s: space
                              var next_m = no_padding_str.indexOf("-", start_pos); // m:
                              var str;
                              if (next_m != -1 &&
                                (next_s == -1 || next_m < next_s)) {
                                // aaa-bbb ddd 這種 case. 或 aaa-bbb 這種case 先是'-'遇到.
                                str = no_padding_str.substr(start_pos, next_m - start_pos);
                                console.log(str + ".length=" + str.length);
                                if (str.length == 1)
                                  console.log(str.charCodeAt(0));
                                start_pos = next_m + 1;
                                head_str += str + "-</span>";
                              }
                              else if (next_s != -1 &&
                                (next_m == -1 || next_s < next_m)) {
                                // aaa bbb-ddd 這種 case. 或 aaa bbb 這種case 先是' '遇到.
                                str = no_padding_str.substr(start_pos, next_s - start_pos);
                                console.log(str + ".length=" + str.length);
                                if (str.length == 1)
                                  console.log(str.charCodeAt(0));

                                start_pos = next_s + 1;
                                head_str += str + "&nbsp</span>";//空白
                              }
                              else {
                                console.log("m:" + next_m + " s:" + next_s);
                                //end
                                // aaa 這種case. 就是最後1個字了.
                                str = no_padding_str.substr(start_pos, no_padding_str.length - start_pos);
                                head_str += str + "</span>";
                                break;
                              }
                              //console.log("next_s=" + next_s + " next_m=" + next_m + " str=" + str + " str.length=" + str.length);
                            } while (next_m != -1 || next_s != -1);

                            /*var s=t[iii].split(/[ -]/);
                              console.log("s="+s);
                            for(iiii=0;iiii<s.length;iiii++){
                              var sn=jsonObj.record[wid].sn;
                              var wform=jsonObj.record[wid].wform;
                              var orig=jsonObj.record[wid].orig;
                              var remark=jsonObj.record[wid].remark;
                              var exp1=jsonObj.record[wid].exp;
                              var par=encodeURIComponent(wform+'|'+orig+'|'+exp1+'|'+remark+'|');
                              head_str+="<span class=parsing N=1 k="+sn+" par="+par+">";
                              if(iiii==0)
                                head_str+=s[iiii]+iiii+"&nbsp</span>";
                              else
                                head_str+=s[iiii]+iiii+"&nbsp</span>";
                              wid++;
                            }*/
                          }
                        }
                        head_str += "</div>";
                        head_str += "<div>" + nexp[ii] + "</div>";
                      }
                    }
                    else if (N == 0) {
                      var wid = 1;
                      for (var ii = 0; ii < nword.length; ii++) {
                        nword[ii] = nword[ii].trim();
                        var t = nword[ii].split(" ");
                        head_str += "<div>";
                        for (var iii = 0; iii < t.length; iii++ , wid++) {
                          var r1 = jsonObj.record[wid];  // 2017.12 馬可福音 1:34 原文
                          if (r1 == null)
                            continue;

                          var sn = jsonObj.record[wid].sn;
                          var pro = jsonObj.record[wid].pro;
                          var wform = jsonObj.record[wid].wform;
                          var orig = jsonObj.record[wid].orig;
                          var remark = jsonObj.record[wid].remark;
                          var exp1 = jsonObj.record[wid].exp;
                          var par = encodeURIComponent(pro + '|' + wform + '|' + orig + '|' + exp1 + '|' + remark + '|');
                          head_str += "<span class=parsing N=0 k=" + sn + " par=" + par + ">";
                          head_str += t[iii] + "&nbsp</span>";
                        }
                        head_str += "</div>";
                        head_str += "<div>" + nexp[ii] + "</div>";
                      }
                    }
                  }// 以上是 wid = 0 的條件, 也就是處理上半部
                  else {
                    if (N == 0 && word == "+") {
                      /*
                        clrcnt=(clrcnt+1)%3;
                        if (clrcnt==0) clrstr="";
                        else if (clrcnt==1) clrstr="#ffff99";
                        else if (clrcnt==2) clrstr="#ffcccc";
                        msg=skip1tag(msg,"record");
                        */
                      continue;
                    }
                    var sn = jsonObj.record[i].sn;
                    var pro = jsonObj.record[i].pro;
                    var wform = jsonObj.record[i].wform;
                    var orig = jsonObj.record[i].orig;
                    var remark = jsonObj.record[i].remark;
                    var pt = remark.indexOf("[#");
                    var pt1 = remark.indexOf("#]");
                    while (N == 1 && pt >= 0 && pt1 > pt) {
                      var nstr = "";
                      var pstr = remark.substring(pt + 2, pt1);
                      pstr = pstr.replace(/１/g, "1");
                      pstr = pstr.replace(/２/g, "2");
                      pstr = pstr.replace(/３/g, "3");
                      pstr = pstr.replace(/４/g, "4");
                      pstr = pstr.replace(/５/g, "5");
                      pstr = pstr.replace(/６/g, "6");
                      pstr = pstr.replace(/７/g, "7");
                      pstr = pstr.replace(/８/g, "8");
                      pstr = pstr.replace(/９/g, "9");
                      pstr = pstr.replace(/．/g, ".");
                      subheb = pstr.split(",");
                      nstr = "§";
                      for (si = 0; si < subheb.length; si++) {
                        subheb[si] = subheb[si].trim();
                        if (subheb[si].length == 0) continue;
                        spt = subheb[si].split("-");
                        nstr = nstr + "<a href=\"/new/pimg/" + spt[0] + ".png\" target=\"grammer\">" + subheb[si] + "</a> ";
                      }
                      remark = remark.substring(0, pt) + nstr + remark.substring(pt1 + 2);
                      pt = remark.indexOf("[#");
                      pt1 = remark.indexOf("#]");
                    }
                    body_str = body_str + "<tr bgcolor=\"" + clrstr + "\"><td class=\"" + orig_font + "\">" + word + "</td><td class=\"g0\"><span class=\"parsingTableSn\" N=" + N + " k=" + sn + ">" + sn + "</span></td><td class=\"g0\">";
                    if (N == 0)
                      body_str = body_str + pro + "</td><td class=\"g0\">";
                    body_str = body_str + wform + "</td><td class=\"" + orig_font + "\">" + orig + "</td><td class=\"g0\">" + exp + "</td><td class=\"g0\">"
                      + remark + "</td></tr>";
                  }//else
                }//for I
                var ptg = "";
                if (N == 0)
                  ptg = "<td class=\"g0\">詞性</td>";
                  var strFontSizeStyle = "font-size: " + ps.fontSize + "pt; line-height: " + ps.fontSize * 1.25 + "pt; margin-top: " + (ps.fontSize * 1.25 - 15) + "px";
                  var headDivStyle = "<div class='parsingTop' style=\"position: absolute; left: 0px; right: 0px; top: 0px; height: 200px; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow:auto; padding: 30px 50px 10px; box-shadow: inset 0px -4px 7px #808080;"+ strFontSizeStyle +";" + ((N == 1) ? "text-align:right;" : "") +
                  "\">";

                var html = chap_ctrl_str + headDivStyle + head_str + "</div><div id='parsingTable' style=\""+strFontSizeStyle+";position: absolute; top: 212px; left: 0px; right: 0px; bottom: 0px; padding: 10px; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow:auto;box-shadow: inset 0px 4px 7px #808080;\"><table border=\"1\">" + "<tr><td class=\"g0\">原文字</td><td class=\"g0\">SN</td>" + ptg + "<td class=\"g0\">字彙分析</td><td class=\"g0\">原型</td><td class=\"g0\">原型簡義</td><td class=\"g0\">備註</td>" + body_str + "</table></div>";

                html = "<div style='position: absolute; top: 200px; left: 0px; right: 0px; height: 12px; background: #A0A0A0;'></div>" + html + "";

                dom.html(html);
                that.registerEvents(ps);
              }//if j
            });
            //tjm
            break;
          case "fhlInfoComment":
            var html = "";
            var ajaxUrl = getAjaxUrl("sc", ps);
            //console.log(ajaxUrl);
            $.ajax({
              url: ajaxUrl
            }).done(function (d, s, j) {
              if (j) {
                function parseComment(t) {
                  t = t.replace(/\n/g, "</br>");
                  t = t.replace(/ /g, "&nbsp");
                  var pt, pt1;
                  var tok, tok_str;
                  var span_str;
                  var i = 0;

                  // 2017.12 詩篇 30 篇 #30| 按下去會變 undefined Bug
                  FHL.STR.eachFitDo(/#([0-9]+)\|/, t, function (m1) {
                    //var replaceTag = '<span class="commentJump" engs="Ps" chap="30" sec="1">30</span>';
                    var chap = m1[1];
                    var replaceTag = '<span class="commentJump" engs="' + ps.engs + '" chap="' + chap + '" sec="1">' + chap + '</span>';
                    t = t.replace(m1[0], replaceTag);
                  });

                  while (true) {
                    pt = t.indexOf("#");
                    pt1 = t.indexOf("|");
                    if (pt < 0 || pt1 < 0 || pt1 <= pt)
                      break;
                    tok_str = t.substring(pt + 1, pt1);
                    span_str = "";

                    while (tok_str.length !== 0) {
                      var firstTokEnd = tok_str.indexOf(";");
                      if (firstTokEnd === -1)
                        firstTokEnd = tok_str.length;
                      tok = tok_str.substring(0, firstTokEnd);
                      tok_str = tok_str.substring(firstTokEnd + 1, tok_str.length);

                      span_str += "&nbsp;<span class='commentJump' engs=";
                      var secNumberEnd = tok.indexOf("-");
                      if (secNumberEnd === -1)
                        secNumberEnd = tok.length;
                      var chapNumberEnd = tok.indexOf(":");
                      var secNumber = tok.substring(chapNumberEnd + 1, secNumberEnd);
                      if (!isNaN(tok[0])) { // parse 在同一卷書裡面跳的
                        var chapNumber = tok.substring(0, chapNumberEnd);
                        span_str += ps.engs;
                      }
                      else { // parse 有中文字在前面的
                        var bookNameEnd = tok.indexOf("&nbsp");
                        var bookName = tok.substring(0, bookNameEnd);
                        var chapNumber = tok.substring(bookNameEnd + 5, chapNumberEnd);//+5是因為&nbsp
                        span_str += bookEng[book.indexOf(bookName)];
                      }
                      span_str += " chap=" + chapNumber + " sec='" + secNumber + "'>" + tok + "</span>&nbsp;";
                    }
                    t = t.substring(0, pt) + span_str + t.substring(pt1 + 1);
                  }

                  // 2017.12
                  var tmp = t
                  FHL.STR.eachFitDo(/SNH([0-9]+)/, tmp, function (m1) {
                    var sn = m1[1];
                    // var newTag = '<span class="sn" sn="09001">09001</span>'
                    var newTag = '<span class="sn" sn="' + sn + '">' + sn + '</span>';
                    t = t.replace(m1[0], newTag);
                  });
                  tmp = t
                  FHL.STR.eachFitDo(/SNG([0-9]+)/, tmp, function (m1) {
                    var sn = m1[1];
                    // var newTag = '<span class="sn" sn="09001">09001</span>'
                    var newTag = '<span class="sn" sn="' + sn + '">' + sn + '</span>';
                    t = t.replace(m1[0], newTag);
                  });

                  return t;
                }

                var jsonObj = JSON.parse(j.responseText);
                var prev_engs;
                var prev_chap;
                var prev_sec;
                var next_engs;
                var next_chap;
                var next_sec;
                var head_str = "";
                var control_str = "";
                if (jsonObj.status === "success" && jsonObj.record_count !== 0) {

                  //console.log("display");

                  if (jsonObj.hasOwnProperty('prev') && !(jsonObj.prev.chap == 0 && jsonObj.prev.sec == 0)) {
                    prev_engs = jsonObj.prev.engs;
                    prev_chap = jsonObj.prev.chap;
                    prev_sec = jsonObj.prev.sec;
                    control_str += "<div class='commentSecBack' ";
                    control_str += "engs='" + prev_engs + "' chap=" + prev_chap + " sec=" + prev_sec;
                    control_str += "><span>&#x276e;</span></div>";
                  }

                  if (jsonObj.hasOwnProperty('next') && ps.chap != 0 && ps.sec != 0) {
                    next_engs = jsonObj.next.engs;
                    next_chap = jsonObj.next.chap;
                    next_sec = jsonObj.next.sec;
                    control_str += "<div class='commentSecNext' ";
                    control_str += "engs='" + next_engs + "' chap=" + next_chap + " sec=" + next_sec;
                    control_str += "><span>&#x276f;</span></div>";
                  }

                  head_str += "<div id='commentTitle'>";
                  if (ps.chap != 0 && ps.sec != 0) {
                    head_str += jsonObj.record[0].title;
                    head_str += "</div>"
                    head_str += "<div class='commentBackground' ";
                    head_str += "engs='" + ps.engs + "' chap=" + 0 + " sec=" + 0;
                    head_str += ">書卷背景</div>";
                  }
                  else {
                    var idx = getBookFunc('indexByEngs', ps.engs);
                    head_str += bookFullName[idx] + "&nbsp;背景資料";
                    head_str += "</div>"
                    head_str += "<div class='commentBackground' ";
                    head_str += "engs='" + ps.engs + "' chap=" + 0 + " sec=" + 0;
                    head_str += ">返回註釋</div>";
                  }


                  var html = jsonObj.record[0].com_text; //注釋內文

                  html = parseComment(html);
                  var strFontSizeStyle = "font-size: " + ps.fontSize + "pt; line-height: " + ps.fontSize * 1.25 + "pt; margin-top: " + (ps.fontSize * 1.25 - 15) + "px";
                  html = "<div style='position: static; padding: 0px; top: 0px; bottom: 0px; overflow: auto;'>" + head_str + '<div id="commentContent">' + control_str + "<div id='commentScrollDiv' style='"+strFontSizeStyle+";position: absolute; top: 0px; left: 0px; right: 0px; bottom: 0px; padding: 80px 10px 70px; overflow: auto;'>" + html + "</div></div></div>";
                  dom.html(html);
                }
                else {
                  dom.html("<div style='position: absolute; left: 50%; top: 50%; transform: translate(-50%, -50%); '>施工中...</div>");
                }
                that.registerEvents(ps);
              }

            });
            break;
          case "fhlInfoPreach":
            do_preach(ps, dom);
            break;
          case "fhlInfoTsk":
            // 串珠 snow
            renderTsk(ps);
            break;
          case "fhlInfoOb":
            // 典藏 snow
            var dom2 = document.getElementById("fhlInfoContent");
            if (dom2 != null) {
              var rProp = {
                ibook: getBookFunc("indexByEngs", ps.engs),
                ichap: ps.chap,
                isec: ps.sec,
                isgb: ps.gb ? true : false,
                cy: $(dom2).height()
              };
              var r = React.createElement(obphp.R.frame, rProp);// r:react Ob:(Old Bible) Frame
              var renderobj = React.render(r, dom2);
            }
            break;
          case "fhlInfoAudio":

            // 有聲聖經 snow
            {
              var pfn_callback = function fn_after_set(ibook, ichap) {
                ps.chineses = book[idx];
                ps.chap = ichap + 1; //因為是0-based 與 1-based
                ps.sec = 1;
                bookSelect.render(pageState, bookSelect.dom);
                fhlLecture.render(pageState, fhlLecture.dom);
                fhlInfo.render(pageState);
              };
              var idx = getBookFunc("index", ps.chineses); // 0-based

              // add 2015.12.10(四) snow, 若是沒加這個條件, (前兩個, 點到節的時候會重播...但根本是同一章,不該重播), (第3個...若只加前2個條件, 不加第3個, 在從其它功能(例如典藏...切回來有聲...就不會render了)
              if (audiobible.g_audiobible.m_ibook != idx || audiobible.g_audiobible.m_ichap != ps.chap - 1 || ps.titleId != ps.titleIdold) {
                //ps.chap; // 1-based
                audiobible.g_audiobible.set_book_chap(idx, ps.chap - 1, dom[0]);
                audiobible.g_audiobible.m_pfn_after_set = pfn_callback;
              }
            }
            break;
          case "fhlInfoMap":
            // 地圖 map
            fhlmap_render(ps, dom);
            // dom.html("<div style='position: absolute; left: 50%; top: 50%; transform: translate(-50%, -50%); '>施工中...</div>");
            break;
        }
        fhlmap_titleId_prev = ps.titleId; //地圖 map 會用到, 因為切換走分頁, 再切換回來要 re-create render object. see also: fhlmap_render
      }
    };

    function parseDic(text) {
      var ps = pageState;
      text = text.replace(/(定義|自希伯來文|於|自|參|與|同義詞|和|見|from|and|See|see entry)(\s+)/g,
        function replacer(match, p1, offset, string) { return p1; });
      text = text.replace(/ /g, "&nbsp;");
      text = text.replace(/(於|自|參|與|同義詞|和|見|from|and|See|see entry)(\d+)/g,
        function replacer(match, p1, p2, offset, string) {
          return p1 + "<span class='snParse' N=" + ps.N + ">" + p2 + "</span>";
        });
      text = text.replace(/自希伯來文(\d+)/g, function replacer(match, p1, offset, string) {
        return "自希伯來文<span class='snParse' N=1>" + p1 + "</span>";
      });
      text = text.replace(/定義(\d+)/g, function replacer(match, p1, offset, string) {
        return "定義<span class='snParse' N=" + ps.N + ">" + p1 + "</span>";
      });
      text = text.replace(/#(.*?)\|/g, function replacer(match, p1, offset, string) {
        return "<span class='searchBibleVerse'>" + p1 + "</span>";
      });
      text = text.replace(/\r\n/g, "</br>");
      return text;
    }

    var parsingPopUp = {
      init: function (ps, dom) {
        this.dom = dom;
        this.dom.hide();
      },
      registerEvents: function (ps) {
        var that = this;

        this.dom.on("mousedown", function (e) {
          if (e.which == 3)
            $(this).addClass("right");
        }).on("mouseleave", function (e) {
          if (!$(this).hasClass("right"))
            that.dom.hide();
        }).on("mouseenter", function (e) {
          clearTimeout($.data($('#parsingPopUp')[0], "parsingPopUpAutoCloseTimeout"));
          if ($(this).hasClass("right"))
            setTimeout(function () { $('#parsingPopUp').removeClass("right"); }, 1);
        });

        $('.snParse').click(function () {
          //var offset=parsingPopUp.dom.offset;
          ps.N = $(this).attr('N');
          ps.k = $(this).html();
          parsingPopUp.render(ps, parsingPopUp.dom, null);
        });
        $('.searchBibleVerse').click(function () {
          var searchText = $(this).html();
          searchText = searchText.replace(/&nbsp;/g, " ");
          searchText = "#" + searchText + "|";

          // replace 2015.08.01(六)
          doSearch(searchText, ps);

          // mark 2015.08.01(六)
          // doSearch("#" + searchText + "|", "search", 0);
        });

        $('.searchSN').click(function () {
          if (!$('#fhlMidBottomWindowControl').hasClass('selected')) {
            $('#fhlMidBottomWindowControl').trigger("click");
          }
          var keywords = $(this).attr('k'); // sn
          //keywords = '3478'; //example;

          //replace 2015.08.01(六)
          doSearch(keywords, ps, false);

          // mark 2015.08.01(六)
          //doSearch($(this).attr('k'),"search",parseInt($(this).attr('N'))+1);
        });
      },
      render: function (ps, dom, offset, par) {
        var that = this;
        if (par == "ft") {
          var html = '<div id="parsingPopUpTriangle"></div><div id="parsingPopUpInside">' + "取得資料中..." + '</div>';
          dom.html(html);
          var winH = $(window).height();
          var domH = (that.dom.height() > 200) ? 200 + 30 : that.dom.height();

          if (offset != null) {
            if (offset.top + domH + 12 + 15 > winH) {
              offset.top -= domH + 40;
              offset.left -= 40;
              $("#parsingPopUpTriangle").addClass("parsingPopUpLowerTriangle");
            }
            else {
              offset.top += 0;
              offset.left -= 40;
              $("#parsingPopUpTriangle").addClass("parsingPopUpUpperTriangle");
            }
          }

          that.dom.show();
          dom.offset(offset);
          that.registerEvents(ps);
        }
        else if (par == "psn") {
          var ajaxUrl = getAjaxUrl('sd', ps);
          $.ajax({
            url: ajaxUrl
          }).done(function (d, s, j) {
            var jsonObj = JSON.parse(j.responseText);
            var html = jsonObj.record[0].dic_text;
            html = parseDic(html);


            html = '<div id="parsingPopUpTriangle"></div><div id="parsingPopUpInside">' + html + '</div>';
            dom.html(html);
            var winH = $(window).height();
            var domH = (that.dom.height() > 200) ? 200 + 40 : that.dom.height();
            whenoverwindow_offset_modified();
            if (offset != null) {
              if (offset.top + domH + 12 + 15 > winH) {
                offset.top -= domH + 40;
                offset.left -= 40;
                $("#parsingPopUpTriangle").addClass("parsingPopUpLowerTriangle");
              }
              else {
                offset.top += 0;
                offset.left -= 40;
                $("#parsingPopUpTriangle").addClass("parsingPopUpUpperTriangle");
              }
              that.dom.show();
              dom.offset(offset);
            }

            /*dom.html(html);
            if(offset!=null){
              var lecTop=164;
              var lecTopOffset=120;
              var RightWinH=$('#fhlInfo').height();
              var domH=dom.height();
            //console.log("top:"+offset.top+",domH:"+domH+",RightWinH:"+RightWinH);

              if(domH>RightWinH){
                //set css to auto scroll
              }else if(offset.top+domH>RightWinH){
                offset.top-=(offset.top>domH)?domH:offset.top;
                offset.left+=70;
              }
              that.dom.show();
              dom.offset(offset);
            }        */
            that.registerEvents(ps);
          });
        } else if (par != null) {
          var html = par;
          dom.html(html);
          that.dom.show();
          if (offset != null) {
            dom.offset(offset);
          }
          //that.dom.scrollTop(0);
          that.registerEvents(ps);
        } else {
          var ajaxUrl = getAjaxUrl('sd', ps);
          $.ajax({
            url: ajaxUrl
          }).done(function (d, s, j) {
            var jsonObj = JSON.parse(j.responseText);

            // replace 2015.10.29(四) snow
            // 使用 j.responseText 的 .sn=00430, 但顯示是 0430, 要用 0430作為關鍵字, 才會被畫上藍色, 因為00430不等於0430 (snow) 2015.10.29(四)
            // 因此. 出現經文按下去的時候. 若是k=00430, 就不會有正確的畫出藍色
            // "record":[{"sn":"00430","dic_text":"0430  ... 這是 j.responseText 局部
            var snShow = /[0-9]+/.exec(jsonObj.record[0].dic_text); //add 2015.10.29(四)
            var title = "";
            if (snShow == null)
              title = "<span class='searchSN' N=" + jsonObj.record[0].dic_type + " k=" + jsonObj.record[0].sn + ">";//原本的
            else
              title = "<span class='searchSN' N=" + jsonObj.record[0].dic_type + " k=" + snShow[0] + ">";
            //var title="<span class='searchSN' N="+jsonObj.record[0].dic_type+" k="+jsonObj.record[0].sn+">"; //mark 2015.10.29(四) snow
            title += "出現經文</span></br>";
            var html = jsonObj.record[0].dic_text;
            html = parseDic(html);
            html = '<div id="parsingPopUpTriangle"></div><div id="parsingPopUpInside">' + title + html + '</div>';
            dom.html(html);
            var winH = $(window).height();
            var domH = (that.dom.height() > 200) ? 200 + 40 : that.dom.height();
            //whenoverwindow_offset_modified();
            if (offset != null) {
              if (offset.top + domH + 12 + 15 > winH) {
                offset.top -= domH + 30;
                offset.left -= 40;
                $("#parsingPopUpTriangle").addClass("parsingPopUpLowerTriangle");
              }
              else {
                offset.top += 10;
                offset.left -= 40;
                $("#parsingPopUpTriangle").addClass("parsingPopUpUpperTriangle");
              }
              that.dom.show();
              dom.offset(offset);
            }
            that.registerEvents(ps);
          });
        }
      }
    };
            /***** End of fhlInfo *****/</script><script>var searchTool = {
      init: function (ps, dom) {
        this.dom = dom;
        this.render(ps, this.dom);
      },
      registerEvents: function (ps) {
        var that = this;

        var $searchTrigger = $('[data-ic-class="search-trigger"]'),
          $searchInput = $('[data-ic-class="search-input"]'),
          $searchClear = $('[data-ic-class="search-clear"]');

        $searchTrigger.click(function () {
          var $this = $('[data-ic-class="search-trigger"]');
          $this.addClass('active');
          $searchInput.focus();
        });

        $searchInput.blur(function () {
          if ($searchInput.val().length > 0) {
            return false;
          } else {
            $searchTrigger.removeClass('active');
          }
        });

        $searchClear.click(function () {
          $searchInput.val('');
        });

        $searchInput.focus(function () {
          $searchTrigger.addClass('active');
        });

        $('.searchBtn').click(function () {
          //ps.leftBtmWinShow = true;
          setPageState(ps);
          fhlMidBottomWindow.render(ps, fhlMidBottomWindow.dom);
          //doSearch($('.searchBox').val(),"search",0);
          doSearch($('.searchBox').val(), ps);
          $searchInput.val('');
          $searchInput.blur();
          $searchTrigger.removeClass('active');
          if (!$('#fhlMidBottomWindowControl').hasClass('selected')) {
            $('#fhlMidBottomWindowControl').trigger("click");
          }
        });
      },
      render: function (ps, dom) {
        var html = "";/*&#x1f50d;*/
        html += ' <div class="wrapper">\
                                  <div class="icon-search-container" data-ic-class="search-trigger">\
                                    <span class="search"><i class="fa fa-search fa-fw"></i></span>\
                                    <input type="text" class="searchBox search-input" data-ic-class="search-input" placeholder="Search" on/>\
                                    <span class="times-circle" data-ic-class="search-clear">×</span>\
                                  </div>\
                                  <span class="searchBtn">快速搜尋</span>\
                                </div>'
        dom.html(html);
      }
    };
    function doSearch(keyword, ps, isAll) {
      /// <summary> 新版本 (2015.08.01, 搜尋</summary>
      /// <param type="string" name="keyword" parameterArray="false">Ex: #賽 21:1| or 3478 or 當把</param>
      /// <param type="bool" name="isAll" parameterArray="false">SN搜尋的時候,它若是在新約的時候,click,就只找新約,default:true</param>
      $('#fhlMidBottomWindowTitle').html('搜尋：' + keyword);
      if (isAll == undefined)
        isAll = true;

      sephp.act_sn_button_click = function (pdata) {
        //console.log('ex: {engs: "Dan",keyword: "03478",ver: "unv"}');
        $('.searchBox').val(pdata.data.keyword);
      };

      // 2015.07.29(三)
      sephp.act_ref_button_click = function (pdata) {
        /// <summary> 會傳入 engs, chap, sec, ver 資訊. 通常是用來切換章節</summary>
        // console.log("act_ref_button_click not assign., 會傳入 engs, chap, sec, ver 資訊. 通常是用來切換章節");
        var idx = getBookFunc("indexByEngs", pdata.data.engs);
        ps.chineses = book[idx];
        ps.engs = bookEng[idx];
        ps.chap = pdata.data.chap;
        ps.sec = pdata.data.sec;
        setPageState(ps);
        bookSelect.render(pageState, bookSelect.dom);
        fhlLecture.render(pageState, fhlLecture.dom);
        fhlLecture.selectLecture(ps.engs, ps.chap, ps.sec);
        fhlInfo.render(pageState);
      }; //設定按下查詢之後的空白圓圈圈要作的事

      var issn = false;
      if (ps.strong == 1)
        issn = true;
      var isgb = false;
      if (ps.gb == 1)
        isgb = true;
      sephp.node_pre_search = document.getElementById("pre_search");
      sephp.node_search_result = document.getElementById("search_result");
      sephp.search(keyword, issn, isgb, ps.version, ps.engs, isAll);

      {//卷軸與介面.2015.07.29(三)
        //console.log($('#fhlMidBottomWindowContent').width());
        //console.log($('#fhlMidBottomWindowContent').height());
        //$(sephp.node_pre_search).width($('#fhlMidBottomWindowContent').width());
        //$(sephp.node_search_result).height($('#fhlMidBottomWindowContent').height() - $(sephp.node_pre_search).height());
        //$(sephp.node_search_result).css("overflow-y", "scroll");
        $('#pre_search').scroll(function () {
          $(this).addClass('scrolling');
          clearTimeout($.data(this, "scrollCheck"));
          $.data(this, "scrollCheck", setTimeout(function () {
            $('#pre_search').removeClass('scrolling');
          }, 350));
        });
        $('#search_result').scroll(function () {
          $(this).addClass('scrolling');
          clearTimeout($.data(this, "scrollCheck"));
          $.data(this, "scrollCheck", setTimeout(function () {
            $('#search_result').removeClass('scrolling');
          }, 350));
        });
      }//卷軸與介面.
    }</script><script>var rRender_Preach;
    var r_Preach;
    var onset_Preach = function (engs, chap, sec) {
      //console.log("外部onset");
      rRender_Preach.setProps({ "engs": engs, "chap": chap, "sec": sec });
    };
    function do_preach(ps, dom) {
      var dom2 = document.getElementById("fhlInfoContent");
      if (dom2 != null) {
        r_Preach = React.createElement(preach_api.R.frame, {
          "engs": ps.engs,
          "chap": ps.chap,
          "sec": ps.sec,
          "onset": onset_Preach
        });
        rRender_Preach = React.render(r_Preach, dom2);
      }




      //// 設定 callback function (scphp.set會呼叫)
      //scphp.pfn_set_after = function pfn_set_after(rediv) {
      //  dom.html(rediv);

      //  // 四個樣式可設定 (可變更...現在只是隨便設)
      //  //for (var idx in scphp.divbooknames)//主題
      //  //  $(scphp.divbooknames[idx]).addClass("search_type");
      //  //for (var idx in scphp.divtitles)//範圍
      //  //  $(scphp.divtitles[idx]).addClass("search_type");
      //  for (var idx in scphp.divnexts)//範圍
      //    $(scphp.divnexts[idx]).addClass("search_type");
      //  for (var idx in scphp.divprevs)//範圍
      //    $(scphp.divprevs[idx]).addClass("search_type");
      //}; // 設定 callback function (scphp.set會呼叫)

      //// 設定 callback function (onclick時會呼叫)
      //scphp.pfn_goto_sec = function pfn_(engs, chap, sec) {
      //  var idx = getBookFunc("indexByEngs", engs);
      //  ps.chineses = book[idx];
      //  ps.engs = engs;
      //  ps.chap = chap;
      //  ps.sec = sec;
      //  bookSelect.render(pageState, bookSelect.dom);
      //  fhlLecture.render(pageState, fhlLecture.dom);
      //  fhlInfo.render(pageState);
      //}; // 設定 callback function (onclick時會呼叫)

      //scphp.set(ps.engs, ps.chap, ps.sec);
    }//do_preach</script><style>img.pos {
      background-image: url('static/images/site.png');
      min-width: 12px;
      min-height: 22px;
      background-repeat: no-repeat;
      background-size: cover;
      background-position: center center;
      cursor: pointer;
    }

    img.pho {
      background-image: url('static/images/camera.png');
      min-width: 29px;
      min-height: 22px;
      background-repeat: no-repeat;
      background-size: cover;
      background-position: center center;
      cursor: pointer;
    }

    @font-face {
      font-family: 'COBSGreekWeb';
      src: url('static/font/COBSGreekWeb.ttf') format('truetype');
    }</style></head><body><div id="app"><div><nav id="fhlTopMenu"><div><img id="logoFHL" src="NUI_files/FHLLOGO.png"> <a id="title">信望愛聖經工具&nbsp;<span>v1.2</span></a></div> <ul class="menu"><li><a href="#"><span>讀經</span></a> <ul class="menu-hover"><li><a target="_blank" href="https://bkbible.fhl.net/NUI/"> 讀經介面(new)</a></li> <li><a target="_blank" href="https://bible.fhl.net/new/record.html"> 閱讀計劃</a></li> <li><a target="_blank" href="https://bible.fhl.net/daily/sy_fhl.php"> 讀經計劃表</a></li> <li><a target="_blank" href="http://a2z.fhl.net/fore/"> 主題研經</a></li> <li><a target="_blank" href="http://a2z.fhl.net/bible/"> 專卷研經</a></li></ul></li> <li><a href="#"><span>教學</span></a> <ul class="menu-hover"><li><a target="_blank" href="http://bible.fhl.net/kim/index.php"> 原文解經(new)</a></li> <li><a target="_blank" href="https://bible.fhl.net/new/audio_hb.php?version=7"> 希伯來文朗讀</a></li> <li><a target="_blank" href="http://bible.fhl.net/kim/HebrewBibleSong.fsp.mp4/"> 希臘文朗讀</a></li> <li><a target="_blank" href="http://bible.fhl.net/kim/HebrewBibleSong.fsp.mp4/"> 希伯來文歌</a></li> <li><a target="_blank" href="https://bible.fhl.net/annouce/annouce84.html"> 中國教會史</a></li> <li><a target="_blank" href="https://bible.fhl.net/isa/isa1.html"> 聖經課程</a></li> <li><a target="_blank" href="http://fungclass.fhl.net/"> 多媒體教學</a></li></ul></li> <li><a href="#"><span>查詢</span></a> <ul class="menu-hover"><li><a target="_blank" href="http://bible.fhl.net/new/topic.html"> 主題查詢</a></li> <li><a target="_blank" href="http://bible.fhl.net/new/search.html"> 經文查詢</a></li> <li><a target="_blank" href="https://bible.fhl.net/new/smap.html"> 物件地理查詢</a></li> <li><a target="_blank" href="http://church.fhl.net/"> 教會查詢</a></li> <li><a target="_blank" href="http://bible.fhl.net/new/sdict.html"> 其他查詢</a></li> <li><a target="_blank" href="http://music.fhl.net/song/"> 聖詩查詢</a></li></ul></li> <li><a href="#"><span>工具</span></a> <ul class="menu-hover"><li><a target="_blank" href="http://bible.fhl.net/new/parsing.html"> 舊約字彙分析</a></li> <li><a target="_blank" href="http://bible.fhl.net/new/fhlwhparsing.html"> 新約字彙分析</a></li> <li><a target="_blank" href="https://bible.fhl.net/new/measurement.html"> 度量衡</a></li> <li><a target="_blank" href="http://bible.fhl.net/new/listall.html"> 簡寫對照</a></li> <li><a target="_blank" href="https://bible.fhl.net/new/heb.html"> 文法對照</a></li></ul></li> <li><a href="#"><span>專欄</span></a> <ul class="menu-hover"><li><a target="_blank" href="https://www.fhl.net/main/what_new.html"> 電子報</a></li> <li><a target="_blank" href="http://a2z.fhl.net/history/"> 歷史走廊</a></li> <li><a target="_blank" href="https://bible.fhl.net/wu/"> 英雄本色</a></li> <li><a target="_blank" href="http://a2z.fhl.net/textual/"> 經文鑑別</a></li> <li><a target="_blank" href="https://bible.fhl.net/cover/"> 信望愛論壇</a></li> <li><a target="_blank" href="https://bible.fhl.net/preach/"> 神學與生活</a></li> <li><a target="_blank" href="https://bible.fhl.net/sundayschool/"> 主日學教育</a></li> <li><a target="_blank" href="https://bible.fhl.net/writer/"> 網路作家</a></li> <li><a target="_blank" href="https://bible.fhl.net/food/"> 靈糧選集</a></li></ul></li> <li><a href="#"><span>連結</span></a> <ul class="menu-hover"><li><a target="_blank" href="https://www.fhl.net/main/"> 信望愛WWW</a></li> <li><a target="_blank" href="https://bible.fhl.net/"> 聖經資源</a></li> <li><a target="_blank" href="http://taigi.fhl.net/"> 台語信望愛</a></li> <li><a target="_blank" href="http://hakka.fhl.net/"> 客語信望愛</a></li> <li><a target="_blank" href="http://sloan.fhl.net/"> 盲人點字</a></li> <li><a target="_blank" href="http://ttlib.fhl.net/"> 神學圖書</a></li> <li><a target="_blank" href="http://photo.fhl.net/main/"> 圖片資源</a></li> <li><a target="_blank" href="http://music.fhl.net/"> 音樂網</a></li></ul></li> <li><a href="#"><span>義工</span></a> <ul class="menu-hover"><li><a target="_blank" href="https://bible.fhl.net/annouce/"> 公告</a></li> <li><a target="_blank" href="http://www.fhl.net/main/fhl/fhl4.html"> 關於我們</a></li> <li><a target="_blank" href="http://bible.fhl.net/new/"> COBS工作區</a></li> <li><a target="_blank" href="https://bible.fhl.net/credit.html"> 義工群</a></li> <li><a target="_blank" href="http://www.fhl.net/main/fhl/fhl2.html"> 徵稿</a></li> <li><a target="_blank" href="https://www.fhl.net/main/fhl/fhl6.html"> 捐款</a></li> <li><a target="_blank" href="http://www.fhl.net/cgi-bin/rogbook.cgi?webwork"> 刊登消息</a></li> <li><a target="_blank" href="http://www.fhl.net/statistics/bible.fhl.net/"> 流量</a></li></ul></li></ul> <a id="problemsReport" href="mailto:sean@fhl.net,tjm@fhl.net,snowray712000@gmail.com?subject=[%E5%95%8F%E9%A1%8C%E5%9B%9E%E5%A0%B1] %E4%BF%A1%E6%9C%9B%E6%84%9B%E8%81%96%E7%B6%93%E5%B7%A5%E5%85%B7NUI"><div style="width: 30px; margin: auto;"><i class="fa fa-envelope-o fa-2x"></i></div> <div style="width: 60px; margin: auto;">
      問題回報
    </div></a></nav> <div id="mainWindow"><div id="fhlToolBar"><div id="help">?</div> <div id="windowControl"><i id="windowControlIcon" class="fa fa-tv fa-fw selected"></i><div id="windowControlButtons"><span id="fhlLeftWindowControl" class="selected"><i class="fa fa-wrench fa-fw"></i></span><span id="fhlMidBottomWindowControl"><i class="fa fa-search-plus fa-fw"></i></span><span id="fhlInfoWindowControl" class="selected"><i class="fa fa-file-text-o fa-fw"></i></span><space style="margin: 0px 10px; cursor: default; color: #D0D0D0;">|</space><span id="fullscreenControl"><i class="fa fa-arrows-alt fa-fw"></i></span></div></div> <div id="bookSelect" style="color: rgb(208, 208, 208);">馬可福音： 第四章&nbsp;▼</div> <div id="searchTool" class="smallText"> <div class="wrapper">                                  <div class="icon-search-container" data-ic-class="search-trigger">                                    <span class="search"><i class="fa fa-search fa-fw"></i></span>                                    <input type="text" class="searchBox search-input" data-ic-class="search-input" placeholder="Search" on="">                                    <span class="times-circle" data-ic-class="search-clear">×</span>                                  </div>                                  <span class="searchBtn">快速搜尋</span>                                </div></div></div> <div id="fhlLeftWindow" class="leftWindow ui-resizable"><div class="leftWindowInside"><div id="settings" class="ui-resizable"><div class="secondLevelInside"><p>▼&nbsp;設定</p> <div id="settingsScrollDiv"><ul><li><div id="snSelect"><div>原文編號:</div><div class="onOffSwitch">                                <input type="checkbox" name="snOnOffSwitch" class="onOffSwitch-checkbox" id="snOnOffSwitch">                                <label class="onOffSwitch-label" for="snOnOffSwitch">                                    <span class="onOffSwitch-inner"></span>                                    <span class="onOffSwitch-switch"></span>                                </label>                            </div></div></li> <li><div id="realTimePopUpSelect"><div>即時顯示:</div><div class="onOffSwitch">                                <input type="checkbox" name="realTimeOnOffSwitch" class="onOffSwitch-checkbox" id="realTimeOnOffSwitch">                                <label class="onOffSwitch-label" for="realTimeOnOffSwitch">                                    <span class="onOffSwitch-inner"></span>                                    <span class="onOffSwitch-switch"></span>                                </label>                            </div></div></li> <li><div id="gbSelect"><div>繁簡切換:</div><div class="onOffSwitch">                                <input type="checkbox" name="gbSelectSwitch" class="onOffSwitch-checkbox" id="gbSelectSwitch">                                <label class="onOffSwitch-label" for="gbSelectSwitch">                                    <span class="onOffSwitch-inner traditional-simpleSwitch"></span>                                    <span class="onOffSwitch-switch"></span>                                </label>                            </div></div></li> <li><div id="show_mode"><div>顯示切換:</div><div class="onOffSwitch">                                <input type="checkbox" name="show_modeSwitch" class="onOffSwitch-checkbox" id="show_modeSwitch">                                <label class="onOffSwitch-label" for="show_modeSwitch">                                    <span class="onOffSwitch-inner showmodeSwitch"></span>                                    <span class="onOffSwitch-switch"></span>                                </label>                            </div></div></li> <li><div id="mapTool"><div>地圖顯示:</div><div class="onOffSwitch">                                <input type="checkbox" name="mapToolOnOffSwitch" class="onOffSwitch-checkbox" id="mapToolOnOffSwitch">                                <label class="onOffSwitch-label" for="mapToolOnOffSwitch">                                    <span class="onOffSwitch-inner"></span>                                    <span class="onOffSwitch-switch"></span>                                </label>                            </div></div></li> <li><div id="imageTool"><div>圖片顯示:</div><div class="onOffSwitch">                                <input type="checkbox" name="imageToolOnOffSwitch" class="onOffSwitch-checkbox" id="imageToolOnOffSwitch">                                <label class="onOffSwitch-label" for="imageToolOnOffSwitch">                                    <span class="onOffSwitch-inner"></span>                                    <span class="onOffSwitch-switch"></span>                                </label>                            </div></div></li> <li><div id="fontSizeTool"><div>字體大小:</div> <div id="fhlLectureFontSizeSmaller">A<span>-</span></div>                            <div id="fhlLectureFontSizeLarger">A<span>+</span></div>                            <div style="display: block; margin-top: 5px; height: 30px;">                                <input id="fhlLectureFontSizeSliderBar" type="range" min="6" max="60" value="12" step="1" style="width: 95px;">                                <input id="fhlLectureFontSize" type="text" value="12" style="width:16px;">                            </div>                            </div></li></ul></div></div><div class="ui-resizable-handle ui-resizable-s" style="z-index: 1000;"><span>☰</span></div></div> <div id="versionSelect" style="height: 586px;" class="ui-resizable"><div class="secondLevelInside"><p>▼&nbsp;聖經版本選擇</p><div id="versionSelectScrollDiv"><ul><li book="unv" cname="和合本" proc="0" strong="1" ntonly="0" candownload="1" otonly="0" version="2019/07/11 05:50:01" class="selected">和合本</li><li book="ncv" cname="新譯本" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">新譯本</li><li book="tcv" cname="現代中文譯本修訂版" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">現代中文譯本修訂版</li><li book="recover" cname="恢復本" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">恢復本</li><li book="csb" cname="中文標準譯本" proc="0" strong="0" ntonly="1" candownload="0" otonly="0" version="">中文標準譯本</li><li book="rcuv" cname="和合本2010" proc="0" strong="1" ntonly="0" candownload="1" otonly="0" version="">和合本2010</li><li book="wlunv" cname="深文理和合本" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2012-09-06 05:50:01">深文理和合本</li><li book="ddv" cname="委辦譯本" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2016-04-16 05:50:01">委辦譯本</li><li book="cnet" cname="NET聖經中譯本" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">NET聖經中譯本</li><li book="cccbst" cname="聖經公會四福音書共同譯本" proc="0" strong="0" ntonly="1" candownload="0" otonly="0" version="">聖經公會四福音書共同譯本</li><li book="nt1864" cname="新遺詔聖經" proc="0" strong="0" ntonly="1" candownload="1" otonly="0" version="2015-07-08 05:50:01">新遺詔聖經</li><li book="mor1823" cname="神天聖書" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="">神天聖書</li><li book="cbol" cname="原文直譯" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2015-11-03 05:50:01">原文直譯(參考用)</li><li book="esv" cname="ESV" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">ESV</li><li book="kjv" cname="KJV" proc="0" strong="1" ntonly="0" candownload="1" otonly="0" version="2012-09-06 05:50:01">KJV</li><li book="bbe" cname="BBE" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2013-04-22 05:50:01">BBE</li><li book="web" cname="WEB" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2014-01-10 05:50:01">WEB</li><li book="asv" cname="ASV" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2013-04-22 05:50:01">ASV</li><li book="darby" cname="Darby" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2015-07-08 05:50:01">Darby</li><li book="erv" cname="ERV" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2015-07-08 05:50:01">ERV</li><li book="bhs" cname="舊約馬索拉原文" proc="2" strong="0" ntonly="0" candownload="1" otonly="1" version="2014-01-10 05:50:01">舊約馬索拉原文</li><li book="fhlwh" cname="新約原文" proc="1" strong="0" ntonly="1" candownload="1" otonly="0" version="2016-04-16 05:50:01">新約原文</li><li book="lxx" cname="七十士譯本" proc="0" strong="0" ntonly="0" candownload="1" otonly="1" version="2014-07-08 05:50:01">七十士譯本</li><li book="tte" cname="聖經公會現代臺語全羅" proc="0" strong="0" ntonly="1" candownload="0" otonly="0" version="">聖經公會現代臺語全羅</li><li book="ttvh" cname="聖經公會現代臺語漢字" proc="0" strong="0" ntonly="1" candownload="0" otonly="0" version="">聖經公會現代臺語漢字</li><li book="apskcl" cname="紅皮聖經全羅" proc="3" strong="0" ntonly="1" candownload="0" otonly="0" version="">紅皮聖經全羅</li><li book="apskhl" cname="紅皮聖經漢羅" proc="3" strong="0" ntonly="1" candownload="0" otonly="0" version="">紅皮聖經漢羅</li><li book="bklcl" cname="巴克禮全羅" proc="3" strong="0" ntonly="0" candownload="1" otonly="0" version="2014-07-08 05:50:01">巴克禮全羅</li><li book="bklhl" cname="巴克禮漢羅" proc="3" strong="0" ntonly="0" candownload="1" otonly="0" version="2014-07-08 05:50:01">巴克禮漢羅</li><li book="prebklcl" cname="馬雅各全羅" proc="3" strong="0" ntonly="0" candownload="1" otonly="0" version="2012-09-06 05:50:01">馬雅各全羅</li><li book="prebklhl" cname="馬雅各漢羅" proc="3" strong="0" ntonly="0" candownload="1" otonly="0" version="2012-09-06 05:50:01">馬雅各漢羅</li><li book="thv2e" cname="聖經公會現代客語全羅" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">聖經公會現代客語全羅</li><li book="thv12h" cname="聖經公會現代客語漢字" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">聖經公會現代客語漢字</li><li book="hakka" cname="客語聖經" proc="3" strong="0" ntonly="1" candownload="1" otonly="0" version="2012-09-06 05:50:01">客語聖經</li><li book="sgebklcl" cname="全民台語聖經全羅" proc="3" strong="0" ntonly="0" candownload="1" otonly="0" version="2015-11-03 05:50:01">全民台語聖經全羅</li><li book="sgebklhl" cname="全民台語聖經漢羅" proc="3" strong="0" ntonly="0" candownload="1" otonly="0" version="2015-11-03 05:50:01">全民台語聖經漢羅</li><li book="vietnamese" cname="越南聖經" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2012-09-06 05:50:01">越南聖經</li><li book="russian" cname="俄文聖經" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2012-09-06 05:50:01">俄文聖經</li><li book="korean" cname="韓文聖經" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2012-09-06 05:50:01">韓文聖經</li><li book="jp" cname="日語聖經" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2015-11-03 05:50:01">日語聖經</li><li book="rukai" cname="聖經公會魯凱語聖經" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">聖經公會魯凱語聖經</li><li book="tsou" cname="聖經公會鄒語聖經" proc="0" strong="0" ntonly="1" candownload="0" otonly="0" version="">聖經公會鄒語聖經</li><li book="ams" cname="聖經公會阿美語全書" proc="0" strong="0" ntonly="0" candownload="0" otonly="0" version="">聖經公會阿美語全書</li><li book="ttnt94" cname="聖經公會達悟語新約聖經" proc="0" strong="0" ntonly="1" candownload="0" otonly="0" version="">聖經公會達悟語新約聖經</li><li book="tibet" cname="藏語聖經" proc="0" strong="0" ntonly="0" candownload="1" otonly="0" version="2018-04-16 05:50:01">藏語聖經</li></ul></div></div><div class="ui-resizable-handle ui-resizable-s" style="z-index: 1000;"><span>☰</span></div></div> <div id="viewHistory" style="top: 880px;"><div class="secondLevelInside"><p>▶&nbsp;歷史記錄</p> <span class="clearHistory">清除記錄</span> <div id="viewHistoryScrollDiv"><ul class="viewHistoryList"><li chineses="可" chap="4">可:4</li><li chineses="創" chap="1">創:1</li></ul></div></div></div></div><div class="ui-resizable-handle ui-resizable-e" style="z-index: 1000;"><span>☰</span></div></div> <div id="fhlMidWindow" style="width: 1117px;"><div id="fhlLecture"><div class="chapBack chapControl" style="display: block;"><span>❮</span></div> <div class="chapNext chapControl" style="display: block;"><span>❯</span></div> <span id="viewHistoryButton" style="position: absolute; right: 10px; cursor: pointer; font-size: 28px; font-weight: 800;"><span class="b noselect" style="color: rgb(0, 0, 0);">←</span><span class="n noselect" style="color: darkgray;">→</span></span> <div id="lecMainTitle"><div class="lecContent" style="width: 100%;"><div class="versionName">和合本<span class="closeButton" cname="和合本">×</span></div></div></div> <div id="lecMain" style="padding: 10px 50px;" mode="1"><div class="vercol" style="width:100%;display:inline-block;vertical-align:top;font-size: 12pt; line-height: 15pt; margin-top: 0px"><div ver="unv" chap="4" sec="1" class="lec selected" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">1</span><span class="verseContent ">耶穌又在海邊教訓人。有許多人到他那裡聚集，他只得上船坐下。船在海裡，眾人都靠近海，站在岸上。</span></div></div><div ver="unv" chap="4" sec="2" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">2</span><span class="verseContent ">耶穌就用比喻教訓他們許多道理。在教訓之間，對他們說：</span></div></div><div ver="unv" chap="4" sec="3" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">3</span><span class="verseContent ">「你們聽啊！有一個撒種的出去撒種。</span></div></div><div ver="unv" chap="4" sec="4" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">4</span><span class="verseContent ">撒的時候，有落在路旁的，飛鳥來吃盡了；</span></div></div><div ver="unv" chap="4" sec="5" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">5</span><span class="verseContent ">有落在土淺石頭地上的，土既不深，發苗最快，</span></div></div><div ver="unv" chap="4" sec="6" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">6</span><span class="verseContent ">日頭出來一曬，因為沒有根，就枯乾了；</span></div></div><div ver="unv" chap="4" sec="7" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">7</span><span class="verseContent ">有落在荊棘裡的，荊棘長起來，把它擠住了，就不結實；</span></div></div><div ver="unv" chap="4" sec="8" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">8</span><span class="verseContent ">又有落在好土裡的，就發生長大，結實有三十倍的，有六十倍的，有一百倍的」；</span></div></div><div ver="unv" chap="4" sec="9" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">9</span><span class="verseContent ">又說：「有耳可聽的，就應當聽！」</span></div></div><div ver="unv" chap="4" sec="10" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">10</span><span class="verseContent ">無人的時候，跟隨耶穌的人和十二個門徒問他這比喻的意思。</span></div></div><div ver="unv" chap="4" sec="11" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">11</span><span class="verseContent ">耶穌對他們說：「　神國的奧祕只叫你們知道，若是對外人講，凡事就用比喻，</span></div></div><div ver="unv" chap="4" sec="12" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">12</span><span class="verseContent ">叫他們看是看見，卻不曉得；聽是聽見，卻不明白；恐怕他們回轉過來，就得赦免。」</span></div></div><div ver="unv" chap="4" sec="13" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">13</span><span class="verseContent ">又對他們說：「你們不明白這比喻嗎？這樣怎能明白一切的比喻呢？</span></div></div><div ver="unv" chap="4" sec="14" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">14</span><span class="verseContent ">撒種之人所撒的就是道。</span></div></div><div ver="unv" chap="4" sec="15" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">15</span><span class="verseContent ">那撒在路旁的，就是人聽了道，撒但立刻來，把撒在他心裡的道奪了去。</span></div></div><div ver="unv" chap="4" sec="16" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">16</span><span class="verseContent ">那撒在石頭地上的，就是人聽了道，立刻歡喜領受，</span></div></div><div ver="unv" chap="4" sec="17" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">17</span><span class="verseContent ">但他心裡沒有根，不過是暫時的，及至為道遭了患難，或是受了逼迫，立刻就跌倒了。</span></div></div><div ver="unv" chap="4" sec="18" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">18</span><span class="verseContent ">還有那撒在荊棘裡的，就是人聽了道，</span></div></div><div ver="unv" chap="4" sec="19" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">19</span><span class="verseContent ">後來有世上的思慮、錢財的迷惑，和別樣的私慾進來，把道擠住了，就不能結實。</span></div></div><div ver="unv" chap="4" sec="20" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">20</span><span class="verseContent ">那撒在好地上的，就是人聽道，又領受，並且結實，有三十倍的，有六十倍的，有一百倍的。」</span></div></div><div ver="unv" chap="4" sec="21" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">21</span><span class="verseContent ">耶穌又對他們說：「人拿燈來，豈是要放在斗底下，床底下，不放在燈臺上嗎？</span></div></div><div ver="unv" chap="4" sec="22" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">22</span><span class="verseContent ">因為掩藏的事，沒有不顯出來的；隱瞞的事，沒有不露出來的。</span></div></div><div ver="unv" chap="4" sec="23" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">23</span><span class="verseContent ">有耳可聽的，就應當聽！」</span></div></div><div ver="unv" chap="4" sec="24" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">24</span><span class="verseContent ">又說：「你們所聽的要留心。你們用甚麼量器量給人，也必用甚麼量器量給你們，並且要多給你們。</span></div></div><div ver="unv" chap="4" sec="25" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">25</span><span class="verseContent ">因為有的，還要給他；沒有的，連他所有的也要奪去。」</span></div></div><div ver="unv" chap="4" sec="26" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">26</span><span class="verseContent ">又說：「　神的國如同人把種撒在地上。</span></div></div><div ver="unv" chap="4" sec="27" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">27</span><span class="verseContent ">黑夜睡覺，白日起來，這種就發芽漸長，那人卻不曉得如何這樣。</span></div></div><div ver="unv" chap="4" sec="28" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">28</span><span class="verseContent ">地生五穀是出於自然的：先發苗，後長穗，再後穗上結成飽滿的子粒；</span></div></div><div ver="unv" chap="4" sec="29" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">29</span><span class="verseContent ">穀既熟了，就用鐮刀去割，因為收成的時候到了。」</span></div></div><div ver="unv" chap="4" sec="30" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">30</span><span class="verseContent ">又說：「　神的國，我們可用甚麼比較呢？可用甚麼比喻表明呢？</span></div></div><div ver="unv" chap="4" sec="31" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">31</span><span class="verseContent ">好像一粒芥菜種，種在地裡的時候，雖比地上的百種都小，</span></div></div><div ver="unv" chap="4" sec="32" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">32</span><span class="verseContent ">但種上以後，就長起來，比各樣的菜都大，又長出大枝來，甚至天上的飛鳥可以宿在它的蔭下。」</span></div></div><div ver="unv" chap="4" sec="33" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">33</span><span class="verseContent ">耶穌用許多這樣的比喻，照他們所能聽的，對他們講道。</span></div></div><div ver="unv" chap="4" sec="34" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">34</span><span class="verseContent ">若不用比喻，就不對他們講；沒有人的時候，就把一切的道講給門徒聽。</span></div></div><div ver="unv" chap="4" sec="35" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">35</span><span class="verseContent ">當那天晚上，耶穌對門徒說：「我們渡到那邊去吧。」</span></div></div><div ver="unv" chap="4" sec="36" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">36</span><span class="verseContent ">門徒離開眾人，耶穌仍在船上，他們就把他一同帶去；也有別的船和他同行。</span></div></div><div ver="unv" chap="4" sec="37" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">37</span><span class="verseContent ">忽然起了暴風，波浪打入船內，甚至船要滿了水。</span></div></div><div ver="unv" chap="4" sec="38" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">38</span><span class="verseContent ">耶穌在船尾上，枕著枕頭睡覺。門徒叫醒了他，說：「夫子！我們喪命，你不顧嗎？」</span></div></div><div ver="unv" chap="4" sec="39" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">39</span><span class="verseContent ">耶穌醒了，斥責風，向海說：「住了吧！靜了吧！」風就止住，大大地平靜了。</span></div></div><div ver="unv" chap="4" sec="40" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">40</span><span class="verseContent ">耶穌對他們說：「為甚麼膽怯？你們還沒有信心嗎？」</span></div></div><div ver="unv" chap="4" sec="41" class="lec" style="height: 37px;"><div style="margin: 0px 20px 0px 1px; padding: 7px 0px; height: 100%;"><span class="verseNumber">41</span><span class="verseContent ">他們就大大地懼怕，彼此說：「這到底是誰，連風和海也聽從他了。」</span></div></div></div><div id="div_copyright" class="lec copyright"><div data-reactid=".0"></div></div></div></div> <div id="fhlMidBottomWindow" style="top: 867px;" class="ui-resizable"><div id="fhlMidBottomWindowTitle"></div> <div id="fhlMidBottomWindowContent"><div id="pre_search" style="font-size: 10pt;"></div><div id="search_result" style="font-size: 10pt;"></div></div><div class="ui-resizable-handle ui-resizable-n" style="z-index: 1000;"><span>☰</span></div></div></div> <div id="fhlInfo" class="ui-resizable" style="left: 1343px;"><div id="fhlInfoTitle"><ul><li id="fhlInfoParsing" class="selected">原文</li><li id="fhlInfoComment">註釋</li><li id="fhlInfoPreach">講道</li><li id="fhlInfoTsk">串珠</li><li id="fhlInfoOb">典藏</li><li id="fhlInfoAudio">有聲</li><li id="fhlInfoMap">地圖</li></ul></div> <div id="fhlInfoContent"><div style="position: absolute; top: 200px; left: 0px; right: 0px; height: 12px; background: #A0A0A0;"></div><div class="parsingSecBack" engs="Mark" chap="3" sec="35"><span>❮</span></div><div class="parsingSecNext" engs="Mark" chap="4" sec="2"><span>❯</span></div><div style="position: absolute; top: 10px; left: 15px; /*transform: translate(-50%, 0%);*/ font-size: 12pt; color: rgba(100, 100, 100, 0.5);">馬可福音&nbsp;&nbsp;4:1</div><div class="parsingTop" style="position: absolute; left: 0px; right: 0px; top: 0px; height: 200px; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow:auto; padding: 30px 50px 10px; box-shadow: inset 0px -4px 7px #808080;font-size: 12pt; line-height: 15pt; margin-top: 0px;"><div><span class="parsing" n="0" k="02532" par="%E9%80%A3%E6%8E%A5%E8%A9%9E%7C%7C%CE%BA%CE%B1%E1%BD%B7%7C%E4%B8%A6%E4%B8%94%E3%80%81%E7%84%B6%E5%BE%8C%E3%80%81%E5%92%8C%7C%7C">Καὶ&nbsp;</span><span class="parsing" n="0" k="03825" par="%E5%89%AF%E8%A9%9E%7C%7C%CF%80%E1%BD%B1%CE%BB%CE%B9%CE%BD%7C%E5%8F%88%E3%80%81%E5%86%8D%E3%80%81%E5%8F%A6%E4%B8%80%E6%96%B9%E9%9D%A2%7C%7C">πάλιν&nbsp;</span><span class="parsing" n="0" k="00757" par="%E5%8B%95%E8%A9%9E%7C%E7%AC%AC%E4%B8%80%E7%B0%A1%E5%96%AE%E9%81%8E%E5%8E%BB%20%E9%97%9C%E8%BA%AB%20%E7%9B%B4%E8%AA%AA%E8%AA%9E%E6%B0%A3%20%E7%AC%AC%E4%B8%89%E4%BA%BA%E7%A8%B1%20%E5%96%AE%E6%95%B8%20%7C%E1%BC%84%CF%81%CF%87%CF%89%7C%E7%AE%A1%E7%90%86%E3%80%81%E7%B5%B1%E6%B2%BB%EF%BC%8C%E9%97%9C%E8%BA%AB%E6%99%82%E6%84%8F%E6%80%9D%E6%98%AF%E3%80%8C%E9%96%8B%E5%A7%8B%E3%80%8D%7C%7C">ἤρξατο&nbsp;</span><span class="parsing" n="0" k="01321" par="%E5%8B%95%E8%A9%9E%7C%E7%8F%BE%E5%9C%A8%20%E4%B8%BB%E5%8B%95%20%E4%B8%8D%E5%AE%9A%E8%A9%9E%20%20%20%20%20%7C%CE%B4%CE%B9%CE%B4%E1%BD%B1%CF%83%CE%BA%CF%89%7C%E6%95%99%E5%B0%8E%7C%7C">διδάσκειν&nbsp;</span><span class="parsing" n="0" k="03844" par="%E4%BB%8B%E7%B3%BB%E8%A9%9E%7C%7C%CF%80%CE%B1%CF%81%E1%BD%B1%7C%E5%BE%8C%E6%8E%A5%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%E6%99%82%E6%84%8F%E6%80%9D%E6%98%AF%E3%80%8C%E6%B2%BF%E8%91%97...%E3%80%81%E6%97%81%E9%82%8A%E3%80%8D%7C%7C">παρὰ&nbsp;</span><span class="parsing" n="0" k="03588" par="%E5%86%A0%E8%A9%9E%7C%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%E1%BD%81%20%E1%BC%A1%20%CF%84%E1%BD%B9%7C%E8%A6%96%E6%83%85%E6%B3%81%E7%BF%BB%E8%AD%AF%EF%BC%8C%E6%9C%89%E6%99%82%E5%8F%AF%E8%AD%AF%E6%88%90%E3%80%8C%E9%80%99%E5%80%8B%E3%80%8D%E3%80%81%E3%80%8C%E9%82%A3%E5%80%8B%E3%80%8D%E7%AD%89%7C%7C">τὴν&nbsp;</span><span class="parsing" n="0" k="02281" par="%E5%90%8D%E8%A9%9E%7C%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%CE%B8%E1%BD%B1%CE%BB%CE%B1%CF%83%CF%83%CE%B1%7C%E6%B5%B7%E3%80%81%E6%B9%96%7C%7C">θάλασσαν·&nbsp;</span></div><div>而他又開始在海邊教導；
</div><div><span class="parsing" n="0" k="02532" par="%E9%80%A3%E6%8E%A5%E8%A9%9E%7C%7C%CE%BA%CE%B1%E1%BD%B7%7C%E4%B8%A6%E4%B8%94%E3%80%81%E7%84%B6%E5%BE%8C%E3%80%81%E5%92%8C%7C%7C">καὶ&nbsp;</span><span class="parsing" n="0" k="04863" par="%E5%8B%95%E8%A9%9E%7C%E7%8F%BE%E5%9C%A8%20%E8%A2%AB%E5%8B%95%20%E7%9B%B4%E8%AA%AA%E8%AA%9E%E6%B0%A3%20%E7%AC%AC%E4%B8%89%E4%BA%BA%E7%A8%B1%20%E5%96%AE%E6%95%B8%20%7C%CF%83%CF%85%CE%BD%E1%BD%B1%CE%B3%CF%89%7C%E8%81%9A%E9%9B%86%E3%80%81%E5%8F%AC%E9%9B%86%7C%7C">συνάγεται&nbsp;</span><span class="parsing" n="0" k="04314" par="%E4%BB%8B%E7%B3%BB%E8%A9%9E%7C%7C%CF%80%CF%81%E1%BD%B9%CF%82%7C%E5%BE%8C%E6%8E%A5%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%E6%99%82%E6%84%8F%E6%80%9D%E6%98%AF%E3%80%8C%E5%B0%8D%E8%91%97%E3%80%81%E5%88%B0%E3%80%8D%7C%7C">πρὸς&nbsp;</span><span class="parsing" n="0" k="00846" par="%E4%BA%BA%E7%A8%B1%E4%BB%A3%E5%90%8D%E8%A9%9E%7C%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%E7%AC%AC%E4%B8%89%E4%BA%BA%E7%A8%B1%20%7C%CE%B1%E1%BD%90%CF%84%E1%BD%B9%CF%82%7C%E4%BB%96%7C%7C">αὐτὸν&nbsp;</span><span class="parsing" n="0" k="03793" par="%E5%90%8D%E8%A9%9E%7C%E4%B8%BB%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%20%20%7C%E1%BD%84%CF%87%CE%BB%CE%BF%CF%82%7C%E7%BE%A4%E7%9C%BE%E3%80%81%E4%BA%BA%E6%B0%91%7C%7C">ὄχλος&nbsp;</span><span class="parsing" n="0" k="04183" par="%E5%BD%A2%E5%AE%B9%E8%A9%9E%7C%E4%B8%BB%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%E6%9C%80%E9%AB%98%E7%B4%9A%20%7C%CF%80%CE%BF%CE%BB%E1%BD%BB%CF%82%7C%E8%A8%B1%E5%A4%9A%7C%7C">πλεῖστος,&nbsp;</span></div><div>有許多人群聚集到他那裡，
</div><div><span class="parsing" n="0" k="05620" par="%E9%80%A3%E6%8E%A5%E8%A9%9E%7C%7C%E1%BD%A5%CF%83%CF%84%CE%B5%7C%E5%9B%A0%E6%AD%A4%E3%80%81%E4%BB%A5%E8%87%B4%E6%96%BC%7C%7C">ὥστε&nbsp;</span><span class="parsing" n="0" k="00846" par="%E4%BA%BA%E7%A8%B1%E4%BB%A3%E5%90%8D%E8%A9%9E%7C%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%E7%AC%AC%E4%B8%89%E4%BA%BA%E7%A8%B1%20%7C%CE%B1%E1%BD%90%CF%84%E1%BD%B9%CF%82%7C%E4%BB%96%7C%7C">αὐτὸν&nbsp;</span><span class="parsing" n="0" k="01519" par="%E4%BB%8B%E7%B3%BB%E8%A9%9E%7C%7C%CE%B5%E1%BC%B0%CF%82%7C%E5%BE%8C%E6%8E%A5%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%EF%BC%8C%E6%84%8F%E6%80%9D%E6%98%AF%E3%80%8C%E6%88%90%E7%82%BA%E3%80%81%E9%80%B2%E5%85%A5...%E4%B9%8B%E5%85%A7%E3%80%8D%7C%7C">εἰς&nbsp;</span><span class="parsing" n="0" k="04143" par="%E5%90%8D%E8%A9%9E%7C%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E4%B8%AD%E6%80%A7%20%20%20%7C%CF%80%CE%BB%CE%BF%E1%BF%96%CE%BF%CE%BD%7C%E8%88%B9%7C%7C">πλοῖον&nbsp;</span><span class="parsing" n="0" k="01684" par="%E5%8B%95%E8%A9%9E%7C%E7%AC%AC%E4%BA%8C%E7%B0%A1%E5%96%AE%E9%81%8E%E5%8E%BB%20%E4%B8%BB%E5%8B%95%20%E5%88%86%E8%A9%9E%20%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%7C%E1%BC%90%CE%BC%CE%B2%CE%B1%E1%BD%B7%CE%BD%CF%89%7C%E4%B9%98%E8%88%B9%E3%80%81%E4%B8%8A%E5%8E%BB%7C%7C">ἐμβάντα&nbsp;</span><span class="parsing" n="0" k="02521" par="%E5%8B%95%E8%A9%9E%7C%E7%8F%BE%E5%9C%A8%20%E8%A2%AB%E5%8B%95%E5%BD%A2%E4%B8%BB%E5%8B%95%E6%84%8F%20%E4%B8%8D%E5%AE%9A%E8%A9%9E%20%20%20%20%20%7C%CE%BA%E1%BD%B1%CE%B8%CE%B7%CE%BC%CE%B1%CE%B9%7C%E5%9D%90%E3%80%81%E5%B1%85%E4%BD%8F%E3%80%81%E5%81%9C%E7%95%99%7C%7C">καθῆσθαι&nbsp;</span></div><div>以致於他只好上船坐下
</div><div><span class="parsing" n="0" k="01722" par="%E4%BB%8B%E7%B3%BB%E8%A9%9E%7C%7C%E1%BC%90%CE%BD%7C%E5%BE%8C%E6%8E%A5%E9%96%93%E6%8E%A5%E5%8F%97%E6%A0%BC%EF%BC%8C%E6%84%8F%E6%80%9D%E6%98%AF%E3%80%8C%E5%9C%A8...%E4%B9%8B%E5%85%A7%E3%80%81%E8%97%89%E8%91%97%E3%80%8D%7C%7C">ἐν&nbsp;</span><span class="parsing" n="0" k="03588" par="%E5%86%A0%E8%A9%9E%7C%E9%96%93%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%E1%BD%81%20%E1%BC%A1%20%CF%84%E1%BD%B9%7C%E8%A6%96%E6%83%85%E6%B3%81%E7%BF%BB%E8%AD%AF%EF%BC%8C%E6%9C%89%E6%99%82%E5%8F%AF%E8%AD%AF%E6%88%90%E3%80%8C%E9%80%99%E5%80%8B%E3%80%8D%E3%80%81%E3%80%8C%E9%82%A3%E5%80%8B%E3%80%8D%E7%AD%89%7C%7C">τῇ&nbsp;</span><span class="parsing" n="0" k="02281" par="%E5%90%8D%E8%A9%9E%7C%E9%96%93%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%CE%B8%E1%BD%B1%CE%BB%CE%B1%CF%83%CF%83%CE%B1%7C%E6%B5%B7%E3%80%81%E6%B9%96%7C%7C">θαλάσσῃ,&nbsp;</span></div><div>在海上，
</div><div><span class="parsing" n="0" k="02532" par="%E9%80%A3%E6%8E%A5%E8%A9%9E%7C%7C%CE%BA%CE%B1%E1%BD%B7%7C%E4%B8%A6%E4%B8%94%E3%80%81%E7%84%B6%E5%BE%8C%E3%80%81%E5%92%8C%7C%7C">καὶ&nbsp;</span><span class="parsing" n="0" k="03956" par="%E5%BD%A2%E5%AE%B9%E8%A9%9E%7C%E4%B8%BB%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%20%20%7C%CF%80%E1%BE%B6%CF%82%7C%E6%89%80%E6%9C%89%E7%9A%84%E3%80%81%E6%AF%8F%E4%B8%80%E5%80%8B%7C%7C">πᾶς&nbsp;</span><span class="parsing" n="0" k="03588" par="%E5%86%A0%E8%A9%9E%7C%E4%B8%BB%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%20%20%7C%E1%BD%81%20%E1%BC%A1%20%CF%84%E1%BD%B9%7C%E8%A6%96%E6%83%85%E6%B3%81%E7%BF%BB%E8%AD%AF%EF%BC%8C%E6%9C%89%E6%99%82%E5%8F%AF%E8%AD%AF%E6%88%90%E3%80%8C%E9%80%99%E5%80%8B%E3%80%8D%E3%80%81%E3%80%8C%E9%82%A3%E5%80%8B%E3%80%8D%E7%AD%89%7C%7C">ὁ&nbsp;</span><span class="parsing" n="0" k="03793" par="%E5%90%8D%E8%A9%9E%7C%E4%B8%BB%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%BD%E6%80%A7%20%20%20%7C%E1%BD%84%CF%87%CE%BB%CE%BF%CF%82%7C%E7%BE%A4%E7%9C%BE%E3%80%81%E4%BA%BA%E6%B0%91%7C%7C">ὄχλος&nbsp;</span><span class="parsing" n="0" k="04314" par="%E4%BB%8B%E7%B3%BB%E8%A9%9E%7C%7C%CF%80%CF%81%E1%BD%B9%CF%82%7C%E5%BE%8C%E6%8E%A5%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%E6%99%82%E6%84%8F%E6%80%9D%E6%98%AF%E3%80%8C%E5%B0%8D%E8%91%97%E3%80%81%E5%88%B0%E3%80%8D%7C%7C">πρὸς&nbsp;</span><span class="parsing" n="0" k="03588" par="%E5%86%A0%E8%A9%9E%7C%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%E1%BD%81%20%E1%BC%A1%20%CF%84%E1%BD%B9%7C%E8%A6%96%E6%83%85%E6%B3%81%E7%BF%BB%E8%AD%AF%EF%BC%8C%E6%9C%89%E6%99%82%E5%8F%AF%E8%AD%AF%E6%88%90%E3%80%8C%E9%80%99%E5%80%8B%E3%80%8D%E3%80%81%E3%80%8C%E9%82%A3%E5%80%8B%E3%80%8D%E7%AD%89%7C%7C">τὴν&nbsp;</span><span class="parsing" n="0" k="02281" par="%E5%90%8D%E8%A9%9E%7C%E7%9B%B4%E6%8E%A5%E5%8F%97%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%CE%B8%E1%BD%B1%CE%BB%CE%B1%CF%83%CF%83%CE%B1%7C%E6%B5%B7%E3%80%81%E6%B9%96%7C%7C">θάλασσαν&nbsp;</span></div><div>所有人群都靠近海，
</div><div><span class="parsing" n="0" k="01909" par="%E4%BB%8B%E7%B3%BB%E8%A9%9E%7C%7C%E1%BC%90%CF%80%E1%BD%B7%7C%E5%BE%8C%E6%8E%A5%E6%89%80%E6%9C%89%E6%A0%BC%E6%99%82%E6%84%8F%E6%80%9D%E6%98%AF%E3%80%8C%E5%9C%A8...%E4%B9%8B%E4%B8%8A%E3%80%81%E5%9C%A8...%E4%B9%8B%E5%89%8D%E3%80%8D%7C%7C">ἐπὶ&nbsp;</span><span class="parsing" n="0" k="03588" par="%E5%86%A0%E8%A9%9E%7C%E6%89%80%E6%9C%89%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%E1%BD%81%20%E1%BC%A1%20%CF%84%E1%BD%B9%7C%E8%A6%96%E6%83%85%E6%B3%81%E7%BF%BB%E8%AD%AF%EF%BC%8C%E6%9C%89%E6%99%82%E5%8F%AF%E8%AD%AF%E6%88%90%E3%80%8C%E9%80%99%E5%80%8B%E3%80%8D%E3%80%81%E3%80%8C%E9%82%A3%E5%80%8B%E3%80%8D%E7%AD%89%7C%7C">τῆς&nbsp;</span><span class="parsing" n="0" k="01093" par="%E5%90%8D%E8%A9%9E%7C%E6%89%80%E6%9C%89%E6%A0%BC%20%E5%96%AE%E6%95%B8%20%E9%99%B0%E6%80%A7%20%20%20%7C%CE%B3%E1%BF%86%7C%E5%9C%B0%7C%7C">γῆς&nbsp;</span><span class="parsing" n="0" k="01510" par="%E5%8B%95%E8%A9%9E%7C%E4%B8%8D%E5%AE%8C%E6%88%90%20%E4%B8%BB%E5%8B%95%20%E7%9B%B4%E8%AA%AA%E8%AA%9E%E6%B0%A3%20%E7%AC%AC%E4%B8%89%E4%BA%BA%E7%A8%B1%20%E8%A4%87%E6%95%B8%20%7C%CE%B5%E1%BC%B0%CE%BC%E1%BD%B7%7C%E6%98%AF%E3%80%81%E6%9C%89%7C%7C">ἦσαν.&nbsp;</span></div><div>站在岸上。</div></div><div id="parsingTable" style="font-size: 12pt; line-height: 15pt; margin-top: 0px;position: absolute; top: 212px; left: 0px; right: 0px; bottom: 0px; padding: 10px; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow:auto;box-shadow: inset 0px 4px 7px #808080;"><table border="1"><tbody><tr><td class="g0">原文字</td><td class="g0">SN</td><td class="g0">詞性</td><td class="g0">字彙分析</td><td class="g0">原型</td><td class="g0">原型簡義</td><td class="g0">備註</td></tr><tr bgcolor=""><td class="g1">Καὶ</td><td class="g0"><span class="parsingTableSn" n="0" k="02532">02532</span></td><td class="g0">連接詞</td><td class="g0"></td><td class="g1">καί</td><td class="g0">並且、然後、和</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">πάλιν</td><td class="g0"><span class="parsingTableSn" n="0" k="03825">03825</span></td><td class="g0">副詞</td><td class="g0"></td><td class="g1">πάλιν</td><td class="g0">又、再、另一方面</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ἤρξατο</td><td class="g0"><span class="parsingTableSn" n="0" k="00757">00757</span></td><td class="g0">動詞</td><td class="g0">第一簡單過去 關身 直說語氣 第三人稱 單數 </td><td class="g1">ἄρχω</td><td class="g0">管理、統治，關身時意思是「開始」</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">διδάσκειν</td><td class="g0"><span class="parsingTableSn" n="0" k="01321">01321</span></td><td class="g0">動詞</td><td class="g0">現在 主動 不定詞     </td><td class="g1">διδάσκω</td><td class="g0">教導</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">παρὰ</td><td class="g0"><span class="parsingTableSn" n="0" k="03844">03844</span></td><td class="g0">介系詞</td><td class="g0"></td><td class="g1">παρά</td><td class="g0">後接直接受格時意思是「沿著...、旁邊」</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">τὴν</td><td class="g0"><span class="parsingTableSn" n="0" k="03588">03588</span></td><td class="g0">冠詞</td><td class="g0">直接受格 單數 陰性   </td><td class="g1">ὁ ἡ τό</td><td class="g0">視情況翻譯，有時可譯成「這個」、「那個」等</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">θάλασσαν</td><td class="g0"><span class="parsingTableSn" n="0" k="02281">02281</span></td><td class="g0">名詞</td><td class="g0">直接受格 單數 陰性   </td><td class="g1">θάλασσα</td><td class="g0">海、湖</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">καὶ</td><td class="g0"><span class="parsingTableSn" n="0" k="02532">02532</span></td><td class="g0">連接詞</td><td class="g0"></td><td class="g1">καί</td><td class="g0">並且、然後、和</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">συνάγεται</td><td class="g0"><span class="parsingTableSn" n="0" k="04863">04863</span></td><td class="g0">動詞</td><td class="g0">現在 被動 直說語氣 第三人稱 單數 </td><td class="g1">συνάγω</td><td class="g0">聚集、召集</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">πρὸς</td><td class="g0"><span class="parsingTableSn" n="0" k="04314">04314</span></td><td class="g0">介系詞</td><td class="g0"></td><td class="g1">πρός</td><td class="g0">後接直接受格時意思是「對著、到」</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">αὐτὸν</td><td class="g0"><span class="parsingTableSn" n="0" k="00846">00846</span></td><td class="g0">人稱代名詞</td><td class="g0">直接受格 單數 陽性 第三人稱 </td><td class="g1">αὐτός</td><td class="g0">他</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ὄχλος</td><td class="g0"><span class="parsingTableSn" n="0" k="03793">03793</span></td><td class="g0">名詞</td><td class="g0">主格 單數 陽性   </td><td class="g1">ὄχλος</td><td class="g0">群眾、人民</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">πλεῖστος</td><td class="g0"><span class="parsingTableSn" n="0" k="04183">04183</span></td><td class="g0">形容詞</td><td class="g0">主格 單數 陽性 最高級 </td><td class="g1">πολύς</td><td class="g0">許多</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ὥστε</td><td class="g0"><span class="parsingTableSn" n="0" k="05620">05620</span></td><td class="g0">連接詞</td><td class="g0"></td><td class="g1">ὥστε</td><td class="g0">因此、以致於</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">αὐτὸν</td><td class="g0"><span class="parsingTableSn" n="0" k="00846">00846</span></td><td class="g0">人稱代名詞</td><td class="g0">直接受格 單數 陽性 第三人稱 </td><td class="g1">αὐτός</td><td class="g0">他</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">εἰς</td><td class="g0"><span class="parsingTableSn" n="0" k="01519">01519</span></td><td class="g0">介系詞</td><td class="g0"></td><td class="g1">εἰς</td><td class="g0">後接直接受格，意思是「成為、進入...之內」</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">πλοῖον</td><td class="g0"><span class="parsingTableSn" n="0" k="04143">04143</span></td><td class="g0">名詞</td><td class="g0">直接受格 單數 中性   </td><td class="g1">πλοῖον</td><td class="g0">船</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ἐμβάντα</td><td class="g0"><span class="parsingTableSn" n="0" k="01684">01684</span></td><td class="g0">動詞</td><td class="g0">第二簡單過去 主動 分詞 直接受格 單數 陽性 </td><td class="g1">ἐμβαίνω</td><td class="g0">乘船、上去</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">καθῆσθαι</td><td class="g0"><span class="parsingTableSn" n="0" k="02521">02521</span></td><td class="g0">動詞</td><td class="g0">現在 被動形主動意 不定詞     </td><td class="g1">κάθημαι</td><td class="g0">坐、居住、停留</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ἐν</td><td class="g0"><span class="parsingTableSn" n="0" k="01722">01722</span></td><td class="g0">介系詞</td><td class="g0"></td><td class="g1">ἐν</td><td class="g0">後接間接受格，意思是「在...之內、藉著」</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">τῇ</td><td class="g0"><span class="parsingTableSn" n="0" k="03588">03588</span></td><td class="g0">冠詞</td><td class="g0">間接受格 單數 陰性   </td><td class="g1">ὁ ἡ τό</td><td class="g0">視情況翻譯，有時可譯成「這個」、「那個」等</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">θαλάσσῃ</td><td class="g0"><span class="parsingTableSn" n="0" k="02281">02281</span></td><td class="g0">名詞</td><td class="g0">間接受格 單數 陰性   </td><td class="g1">θάλασσα</td><td class="g0">海、湖</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">καὶ</td><td class="g0"><span class="parsingTableSn" n="0" k="02532">02532</span></td><td class="g0">連接詞</td><td class="g0"></td><td class="g1">καί</td><td class="g0">並且、然後、和</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">πᾶς</td><td class="g0"><span class="parsingTableSn" n="0" k="03956">03956</span></td><td class="g0">形容詞</td><td class="g0">主格 單數 陽性   </td><td class="g1">πᾶς</td><td class="g0">所有的、每一個</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ὁ</td><td class="g0"><span class="parsingTableSn" n="0" k="03588">03588</span></td><td class="g0">冠詞</td><td class="g0">主格 單數 陽性   </td><td class="g1">ὁ ἡ τό</td><td class="g0">視情況翻譯，有時可譯成「這個」、「那個」等</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ὄχλος</td><td class="g0"><span class="parsingTableSn" n="0" k="03793">03793</span></td><td class="g0">名詞</td><td class="g0">主格 單數 陽性   </td><td class="g1">ὄχλος</td><td class="g0">群眾、人民</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">πρὸς</td><td class="g0"><span class="parsingTableSn" n="0" k="04314">04314</span></td><td class="g0">介系詞</td><td class="g0"></td><td class="g1">πρός</td><td class="g0">後接直接受格時意思是「對著、到」</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">τὴν</td><td class="g0"><span class="parsingTableSn" n="0" k="03588">03588</span></td><td class="g0">冠詞</td><td class="g0">直接受格 單數 陰性   </td><td class="g1">ὁ ἡ τό</td><td class="g0">視情況翻譯，有時可譯成「這個」、「那個」等</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">θάλασσαν</td><td class="g0"><span class="parsingTableSn" n="0" k="02281">02281</span></td><td class="g0">名詞</td><td class="g0">直接受格 單數 陰性   </td><td class="g1">θάλασσα</td><td class="g0">海、湖</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ἐπὶ</td><td class="g0"><span class="parsingTableSn" n="0" k="01909">01909</span></td><td class="g0">介系詞</td><td class="g0"></td><td class="g1">ἐπί</td><td class="g0">後接所有格時意思是「在...之上、在...之前」</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">τῆς</td><td class="g0"><span class="parsingTableSn" n="0" k="03588">03588</span></td><td class="g0">冠詞</td><td class="g0">所有格 單數 陰性   </td><td class="g1">ὁ ἡ τό</td><td class="g0">視情況翻譯，有時可譯成「這個」、「那個」等</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">γῆς</td><td class="g0"><span class="parsingTableSn" n="0" k="01093">01093</span></td><td class="g0">名詞</td><td class="g0">所有格 單數 陰性   </td><td class="g1">γῆ</td><td class="g0">地</td><td class="g0"></td></tr><tr bgcolor=""><td class="g1">ἦσαν</td><td class="g0"><span class="parsingTableSn" n="0" k="01510">01510</span></td><td class="g0">動詞</td><td class="g0">不完成 主動 直說語氣 第三人稱 複數 </td><td class="g1">εἰμί</td><td class="g0">是、有</td><td class="g0"></td></tr></tbody></table></div></div><div class="ui-resizable-handle ui-resizable-w" style="z-index: 1000;"><span>☰</span></div></div> <div id="bookSelectPopUp" style="display: none;"><div id="bookSelectName"><div id="bookSelectTitle">經卷選擇</div><div id="bookSelectChapter"></div><div id="old-testament" class="testaments"><ul><li></li><li><span class="bookClass">摩西五經</span><ul><li chineses="創"><span>創世記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="出"><span>出埃及記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="利"><span>利未記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="民"><span>民數記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="申"><span>申命記<i class="fa fa-angle-right fa-fw"></i></span></li></ul><span class="bookClass">舊約歷史書</span><ul><li chineses="書"><span>約書亞記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="士"><span>士師記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="得"><span>路得記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="撒上"><span>撒母耳記上<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="撒下"><span>撒母耳記下<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="王上"><span>列王紀上<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="王下"><span>列王紀下<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="代上"><span>歷代志上<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="代下"><span>歷代志下<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="拉"><span>以斯拉記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="尼"><span>尼希米記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="斯"><span>以斯帖記<i class="fa fa-angle-right fa-fw"></i></span></li></ul></li><li><span class="bookClass">詩歌智慧書</span><ul><li chineses="伯"><span>約伯記<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="詩"><span>詩篇<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="箴"><span>箴言<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="傳"><span>傳道書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="歌"><span>雅歌<i class="fa fa-angle-right fa-fw"></i></span></li></ul><span class="bookClass">大先知書</span><ul><li chineses="賽"><span>以賽亞書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="耶"><span>耶利米書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="哀"><span>耶利米哀歌<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="結"><span>以西結書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="但"><span>但以理書<i class="fa fa-angle-right fa-fw"></i></span></li></ul></li><li><span class="bookClass">小先知書</span><ul><li chineses="何"><span>何西阿書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="珥"><span>約珥書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="摩"><span>阿摩司書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="俄"><span>俄巴底亞書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="拿"><span>約拿書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="彌"><span>彌迦書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="鴻"><span>那鴻書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="哈"><span>哈巴谷書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="番"><span>西番雅書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="該"><span>哈該書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="亞"><span>撒迦利亞書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="瑪"><span>瑪拉基書<i class="fa fa-angle-right fa-fw"></i></span></li></ul></li><li><span class="bookClass">福音書</span><ul><li chineses="太"><span>馬太福音<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="可"><span>馬可福音<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="路"><span>路加福音<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="約"><span>約翰福音<i class="fa fa-angle-right fa-fw"></i></span></li></ul><span class="bookClass">新約歷史書</span><ul><li chineses="徒"><span>使徒行傳<i class="fa fa-angle-right fa-fw"></i></span></li></ul></li><li><span class="bookClass">保羅書信</span><ul><li chineses="羅"><span>羅馬書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="林前"><span>哥林多前書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="林後"><span>哥林多後書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="加"><span>加拉太書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="弗"><span>以弗所書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="腓"><span>腓立比書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="西"><span>歌羅西書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="帖前"><span>帖撒羅尼迦前書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="帖後"><span>帖撒羅尼迦後書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="提前"><span>提摩太前書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="提後"><span>提摩太後書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="多"><span>提多書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="門"><span>腓利門書<i class="fa fa-angle-right fa-fw"></i></span></li></ul></li><li><span class="bookClass">其他書信</span><ul><li chineses="來"><span>希伯來書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="雅"><span>雅各書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="彼前"><span>彼得前書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="彼後"><span>彼得後書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="約一"><span>約翰壹書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="約二"><span>約翰貳書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="約三"><span>約翰參書<i class="fa fa-angle-right fa-fw"></i></span></li><li chineses="猶"><span>猶大書<i class="fa fa-angle-right fa-fw"></i></span></li></ul><span class="bookClass">預言書</span><ul><li chineses="啟"><span>啟示錄<i class="fa fa-angle-right fa-fw"></i></span></li></ul></li><li></li></ul></div></div></div> <div id="parsingPopUp" style="display: none;"></div> <div id="helpingPopUp"><div id="helpingPopUpInside"><div><div id="helpCloseButton"><i class="fa fa-times"></i></div><ul>                            <li>Alt + Shift + F: 搜尋</li>                            <li>Alt + Shift + S: 快速選章</li>                            <li>Alt + Shift + L: 全螢幕</li>                            <li>Alt + Shift + Z: 設定視窗開關</li>                            <li>Alt + Shift + X: 搜尋視窗開關</li>                            <li>Alt + Shift + C: 輔助視窗開關</li>                            <li>Alt + Shift + /: 幫助</li>                            <li>Esc: 跳出</li></ul></div></div></div> <div id="dictionaryPopUp"></div></div></div></div><script type="text/javascript" src="NUI_files/manifest.js"></script><script type="text/javascript" src="NUI_files/vendor.js"></script><script type="text/javascript" src="NUI_files/app.js"></script></body></html>