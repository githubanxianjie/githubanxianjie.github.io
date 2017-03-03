
<!doctype html>



  


<html class="theme-next mist use-motion">
<head>
  <meta charset="UTF-8"/>
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"/>



<meta http-equiv="Cache-Control" content="no-transform" />
<meta http-equiv="Cache-Control" content="no-siteapp" />












  
  
  <link href="/vendors/fancybox/source/jquery.fancybox.css?v=2.1.5" rel="stylesheet" type="text/css" />




  
  
  
  

  
    
    
  

  

  

  

  

  
    
    
    <link href="//fonts.googleapis.com/css?family=Lato:300,300italic,400,400italic,700,700italic&subset=latin,latin-ext" rel="stylesheet" type="text/css">
  






<link href="/vendors/font-awesome/css/font-awesome.min.css?v=4.4.0" rel="stylesheet" type="text/css" />

<link href="/css/main.css?v=5.0.1" rel="stylesheet" type="text/css" />


  <meta name="keywords" content="Android," />








  <link rel="shortcut icon" type="image/x-icon" href="/favicon.ico?v=5.0.1" />






<meta name="description" content="现在Android的开发者基本上都使用Android Studio进行开发(如果你还在使用eclipse那也行，毕竟你乐意怎么样都行)。使用好Android Studio插件能大量的减少我们的工作量。
1.GsonFormat快速将json字符串转换成一个Java Bean，免去我们根据json字符串手写对应Java Bean的过程。

使用方法：快捷键Alt+S也可以使用Alt+Insert选择">
<meta property="og:type" content="article">
<meta property="og:title" content="Android Studio插件整理">
<meta property="og:url" content="http://yoursite.com/2016/06/28/Android-Studio插件整理/index.html">
<meta property="og:site_name" content="习惯沉默的Blog">
<meta property="og:description" content="现在Android的开发者基本上都使用Android Studio进行开发(如果你还在使用eclipse那也行，毕竟你乐意怎么样都行)。使用好Android Studio插件能大量的减少我们的工作量。
1.GsonFormat快速将json字符串转换成一个Java Bean，免去我们根据json字符串手写对应Java Bean的过程。

使用方法：快捷键Alt+S也可以使用Alt+Insert选择">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7654/screenshot_15729.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7369/screenshot_14384.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7595/screenshot_14834.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7595/screenshot_14833.png">
<meta property="og:image" content="https://segmentfault.com/image?src=http://img.blog.csdn.net/20160416104459926&objectId=1190000005092842&token=ab29ed79d41be9e42b3a3d2ed1ec3bef">
<meta property="og:image" content="http://plugins.jetbrains.com/files/8076/screenshot_15509.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7742/screenshot_15071.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7742/screenshot_15070.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7275/screenshot_14294.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7275/screenshot_14295.png">
<meta property="og:image" content="http://plugins.jetbrains.com/oldimg/screenshots/FindBugs-IDEA_2541.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7856/screenshot_15153.png">
<meta property="og:image" content="https://github.com/succlz123/AndroidPixelDimenGenerator/raw/master/snapshot/1.jpeg">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7838/screenshot_15113.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7972/screenshot_15340.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7972/screenshot_15339.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7972/screenshot_15338.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15535.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15691.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15533.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15537.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15536.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15534.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15532.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7658/screenshot_15351.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7298/screenshot_14292.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7298/screenshot_14291.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7298/screenshot_14290.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7269/screenshot_14278.png">
<meta property="og:image" content="http://stormzhang.com/image/leakcaneray.png">
<meta property="og:image" content="http://plugins.jetbrains.com/files/7775/screenshot_15042.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7366/screenshot_14379.png">
<meta property="og:image" content="https://github.com/square/dagger-intellij-plugin/raw/master/images/inject-to-provide.gif">
<meta property="og:image" content="https://camo.githubusercontent.com/d9b1b39eda21e0e33b656e2821f01897d915f7c5/68747470733a2f2f6c68332e676f6f676c6575736572636f6e74656e742e636f6d2f2d51364e7970315864594c772f556a73325a5175666634492f414141414141414144624d2f624d704c516742664d6b632f773538372d683330392d6e6f2f696465615f677261646c655f706c7567696e2e706e67">
<meta property="og:image" content="https://camo.githubusercontent.com/0327cda5b531ab6f2b803abe295c42225668d28d/687474703a2f2f7777772e7533636f64696e672e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031362f30362f312e676966">
<meta property="og:image" content="http://7xrnko.com1.z0.glb.clouddn.com/androidproguard1.gif">
<meta property="og:image" content="https://github.com/square/otto-intellij-plugin/raw/master/images/produce-to-subscribe.gif">
<meta property="og:image" content="https://github.com/square/otto-intellij-plugin/raw/master/images/event-to-subscribe.gif">
<meta property="og:image" content="https://raw.githubusercontent.com/kgmyshin/eventbus-intellij-plugin/master/art/cap.gif">
<meta property="og:image" content="https://github.com/nicoulaj/idea-markdown/raw/assets/screenshots/preview.png">
<meta property="og:image" content="http://d.hiphotos.baidu.com/zhidao/wh%3D600%2C800/sign=f57bdd37f0246b607b5bba72dbc83674/4b90f603738da9777260054fb651f8198618e303.jpg">
<meta property="og:image" content="http://h.hiphotos.baidu.com/zhidao/wh%3D600%2C800/sign=77e4e517fdf2b211e47b8d48fab04900/1c950a7b02087bf46d0dd48df4d3572c10dfcff5.jpg">
<meta property="og:image" content="http://h.hiphotos.baidu.com/zhidao/wh%3D600%2C800/sign=5cd9b28564d9f2d320442ce999dca62b/34fae6cd7b899e51289eb77044a7d933c8950d45.jpg">
<meta property="og:image" content="https://github.com/dmytrodanylyk/folding-plugin/raw/master/screenshots/Preview.png">
<meta property="og:image" content="https://camo.githubusercontent.com/ce3be2aaa3b1f70b90f5b825c529694509d70313/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f6469616c6f672e706e67">
<meta property="og:image" content="https://camo.githubusercontent.com/598d3b5c9efc5f0b57b58c25a79a323d06307fad/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f616374696f6e2e706e67">
<meta property="og:image" content="https://camo.githubusercontent.com/7a8f977de7a1ba6cd23fb64cbd37566690c27cdc/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f6d656e752e706e67">
<meta property="og:image" content="http://img.blog.csdn.net/20160311101644127">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7405/screenshot_14417.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7405/screenshot_14418.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7405/screenshot_14416.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7405/screenshot_14501.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7405/screenshot_14419.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7405/screenshot_14415.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/8006/screenshot_15722.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/8006/screenshot_15723.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/8006/screenshot_15721.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7495/screenshot_14960.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7495/screenshot_14958.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7495/screenshot_14959.png">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7896/screenshot_15818.png">
<meta property="og:image" content="https://github.com/Skykai521/ECTranslation/raw/master/img/translation_img.png">
<meta property="og:image" content="https://github.com/shiraji/permissions-dispatcher-plugin/raw/master/website/images/pd.gif">
<meta property="og:image" content="https://plugins.jetbrains.com/files/7425/screenshot_14794.png">
<meta property="og:image" content="https://github.com/pedrovgs/AndroidWiFiADB/raw/master/art/screenshot1.gif">
<meta property="og:image" content="https://github.com/pedrovgs/AndroidWiFiADB/raw/master/art/android_devices_window.png">
<meta property="og:image" content="https://raw.githubusercontent.com/westlinkin/AndroidLocalizationer/master/screen_shot_3.png">
<meta property="og:image" content="https://raw.githubusercontent.com/westlinkin/AndroidLocalizationer/master/screen_shot_2.png">
<meta property="og:image" content="https://raw.githubusercontent.com/YiiGuxing/TranslationPlugin/master/images/1.png">
<meta property="og:image" content="https://raw.githubusercontent.com/YiiGuxing/TranslationPlugin/master/images/3.png">
<meta property="og:image" content="https://github.com/luhaoaimama1/SingletonTest/raw/master/demo/tip1.png">
<meta property="og:image" content="https://github.com/luhaoaimama1/SingletonTest/raw/master/demo/tip2.png">
<meta property="og:image" content="https://github.com/luhaoaimama1/SingletonTest/raw/master/demo/tip3.png">
<meta property="og:image" content="https://github.com/boredream/BorePlugin/raw/master/screenshot/LayoutCreator.gif">
<meta property="og:image" content="http://zeroturnaround.com/wp-content/uploads/2015/04/Android_Card1_2x.png">
<meta property="og:image" content="http://zeroturnaround.com/wp-content/uploads/2015/04/Android_Card2_2x.png">
<meta property="og:image" content="http://zeroturnaround.com/wp-content/uploads/2015/04/Android_Card3_2x.png">
<meta property="og:image" content="https://camo.githubusercontent.com/95469d65798f62a50a9fcabe21e2cc303a1b859c/687474703a2f2f692e696d6775722e636f6d2f384a734a587a6e2e6a7067">
<meta property="og:image" content="http://ww1.sinaimg.cn/large/86e2ff85gw1f383wa95tej21ge0m5ai0.jpg">
<meta property="og:image" content="https://github.com/konifar/android-strings-search-plugin/raw/master/art/demo.gif">
<meta property="og:image" content="http://upload-images.jianshu.io/upload_images/1825722-8b55d9654777599e.gif?imageMogr2/auto-orient/strip">
<meta property="og:image" content="https://raw.githubusercontent.com/likfe/eventbus3-intellij-plugin/master/art/cap.gif">
<meta property="og:image" content="http://exynap.com/images/anim01.gif">
<meta property="og:image" content="https://camo.githubusercontent.com/cb48bca7f8bd0b513f350f7320c74054d1b9fbce/687474703a2f2f6936352e74696e797069632e636f6d2f726a687863382e706e67">
<meta property="og:image" content="https://github.com/githubwing/MVPHelper/raw/master/img/mvp_presenter.gif">
<meta property="og:image" content="https://raw.githubusercontent.com/lypeer/Matchmaker/master/gif/plugin.gif">
<meta property="og:image" content="https://github.com/shiraji/emoji/raw/master/website/images/commit.gif">
<meta property="og:image" content="https://camo.githubusercontent.com/aa9d4468da25629928fc71256834a81fdaf2bebc/687474703a2f2f66696e6765726172742e71696e6975646e2e636f6d2f323031362d31302d31322d6f70656e5f75706c6f616465725f707265766965772e676966">
<meta property="og:image" content="https://camo.githubusercontent.com/d43ec0344dcce348e663ba57303fa6a26e4d1bf2/687474703a2f2f7777342e73696e61696d672e636e2f6c617267652f3836653266663835677731663933356c306b77696c6a32316b77307433616b6d2e6a7067">
<meta property="og:image" content="https://camo.githubusercontent.com/1eb2599f0689134d0bfc728b0ae38a4ead4010d3/687474703a2f2f7777342e73696e61696d672e636e2f6c617267652f38366532666638356777316638796a3073656a64366a323133343062656e31732e6a7067">
<meta property="og:image" content="https://github.com/OriginalLove/Android-ButterKnife-Plugin-Plus/raw/master/img/1.png">
<meta property="og:image" content="https://github.com/OriginalLove/Android-ButterKnife-Plugin-Plus/raw/master/img/2.png">
<meta property="og:image" content="https://raw.githubusercontent.com/nukc/ApkMultiChannelPlugin/master/art/choose-apk.png">
<meta property="og:image" content="https://raw.githubusercontent.com/nukc/ApkMultiChannelPlugin/master/art/setting.png">
<meta property="og:image" content="https://raw.githubusercontent.com/nukc/ApkMultiChannelPlugin/master/art/output.png">
<meta property="og:image" content="http://7xjtfr.com1.z0.glb.clouddn.com/codemaker.gif">
<meta property="og:image" content="https://github.com/pbreault/adb-idea/raw/master/website/find_actions.png">
<meta property="og:image" content="https://user-gold-cdn.xitu.io/2017/2/6/69aa3f002477b228bf49b2478fce1d2b">
<meta property="og:updated_time" content="2017-02-12T04:24:56.000Z">
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="Android Studio插件整理">
<meta name="twitter:description" content="现在Android的开发者基本上都使用Android Studio进行开发(如果你还在使用eclipse那也行，毕竟你乐意怎么样都行)。使用好Android Studio插件能大量的减少我们的工作量。
1.GsonFormat快速将json字符串转换成一个Java Bean，免去我们根据json字符串手写对应Java Bean的过程。

使用方法：快捷键Alt+S也可以使用Alt+Insert选择">
<meta name="twitter:image" content="http://plugins.jetbrains.com/files/7654/screenshot_15729.png">



<script type="text/javascript" id="hexo.configuration">
  var NexT = window.NexT || {};
  var CONFIG = {
    scheme: 'Mist',
    sidebar: {"position":"right","display":"post"},
    fancybox: true,
    motion: true,
    duoshuo: {
      userId: 0,
      author: '博主'
    }
  };
</script>




  <link rel="canonical" href="http://yoursite.com/2016/06/28/Android-Studio插件整理/"/>

  <title> Android Studio插件整理 | 习惯沉默的Blog </title>
</head>

<body itemscope itemtype="http://schema.org/WebPage" lang="zh-Hans">

  










  
  
    
  

  <div class="container one-collumn sidebar-position-right page-post-detail ">
    <div class="headband"></div>

    <header id="header" class="header" itemscope itemtype="http://schema.org/WPHeader">
      <div class="header-inner"><div class="site-meta ">
  

  <div class="custom-logo-site-title">
    <a href="/"  class="brand" rel="start">
      <span class="logo-line-before"><i></i></span>
      <span class="site-title">习惯沉默的Blog</span>
      <span class="logo-line-after"><i></i></span>
    </a>
  </div>
  <p class="site-subtitle"></p>
</div>

<div class="site-nav-toggle">
  <button>
    <span class="btn-bar"></span>
    <span class="btn-bar"></span>
    <span class="btn-bar"></span>
  </button>
</div>

<nav class="site-nav">
  

  
    <ul id="menu" class="menu">
      
        
        <li class="menu-item menu-item-home">
          <a href="/" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-home"></i> <br />
            
            首页
          </a>
        </li>
      
        
        <li class="menu-item menu-item-categories">
          <a href="/categories" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-th"></i> <br />
            
            分类
          </a>
        </li>
      
        
        <li class="menu-item menu-item-about">
          <a href="/about" rel="section">
            
              <i class="menu-item-icon fa fa-fw fa-user"></i> <br />
            
            关于
          </a>
        </li>
      

      
    </ul>
  

  
</nav>

 </div>
    </header>

    <main id="main" class="main">
      <div class="main-inner">
        <div class="content-wrap">
          <div id="content" class="content">
            

  <div id="posts" class="posts-expand">
    

  
  

  
  
  

  <article class="post post-type-normal " itemscope itemtype="http://schema.org/Article">

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
            
            
              
                Android Studio插件整理
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">
            <span class="post-meta-item-icon">
              <i class="fa fa-calendar-o"></i>
            </span>
            <span class="post-meta-item-text">发表于</span>
            <time itemprop="dateCreated" datetime="2016-06-28T09:34:50+08:00" content="2016-06-28">
              2016-06-28
            </time>
          </span>

          
            <span class="post-category" >
              &nbsp; | &nbsp;
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              <span class="post-meta-item-text">分类于</span>
              
                <span itemprop="about" itemscope itemtype="https://schema.org/Thing">
                  <a href="/categories/Android开发/" itemprop="url" rel="index">
                    <span itemprop="name">Android开发</span>
                  </a>
                </span>

                
                

              
            </span>
          

          
            
              <span class="post-comments-count">
                &nbsp; | &nbsp;
                <a href="/2016/06/28/Android-Studio插件整理/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count ds-thread-count" data-thread-key="2016/06/28/Android-Studio插件整理/" itemprop="commentsCount"></span>
                </a>
              </span>
            
          

          

          
          

          
        </div>
      </header>
    


    <div class="post-body" itemprop="articleBody">

      
      

      
        <p>现在Android的开发者基本上都使用Android Studio进行开发(如果你还在使用eclipse那也行，毕竟你乐意怎么样都行)。使用好Android Studio插件能大量的减少我们的工作量。</p>
<h1 id="1-GsonFormat"><a href="#1-GsonFormat" class="headerlink" title="1.GsonFormat"></a>1.<a href="http://plugins.jetbrains.com/plugin/7654?pr=androidstudio" target="_blank" rel="external">GsonFormat</a></h1><p>快速将json字符串转换成一个Java Bean，免去我们根据json字符串手写对应Java Bean的过程。</p>
<p><img src="http://plugins.jetbrains.com/files/7654/screenshot_15729.png" alt=""></p>
<p>使用方法：快捷键Alt+S也可以使用Alt+Insert选择GsonFormat</p>
<h1 id="2-Android-ButterKnife-Zelezny"><a href="#2-Android-ButterKnife-Zelezny" class="headerlink" title="2.Android ButterKnife Zelezny"></a>2.<a href="http://plugins.jetbrains.com/plugin/7369?pr=androidstudio" target="_blank" rel="external">Android ButterKnife Zelezny</a></h1><p>配合ButterKnife实现注解，从此不用写findViewById，想着就爽啊。在Activity，Fragment，Adapter中选中布局xml的资源id自动生成butterknife注解。</p>
<p><img src="http://plugins.jetbrains.com/files/7369/screenshot_14384.png" alt=""></p>
<p>使用方法：Ctrl+Shift+B选择图上所示选项</p>
<h1 id="3-Android-Code-Generator"><a href="#3-Android-Code-Generator" class="headerlink" title="3.Android Code Generator"></a>3.<a href="http://plugins.jetbrains.com/plugin/7595?pr=androidstudio" target="_blank" rel="external">Android Code Generator</a></h1><p>根据布局文件快速生成对应的Activity，Fragment，Adapter，Menu。</p>
<p><img src="http://plugins.jetbrains.com/files/7595/screenshot_14834.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7595/screenshot_14833.png" alt=""></p>
<h1 id="4-Android-Parcelable-code-generator"><a href="#4-Android-Parcelable-code-generator" class="headerlink" title="4.Android Parcelable code generator"></a>4.<a href="http://plugins.jetbrains.com/plugin/7332?pr=androidstudio" target="_blank" rel="external">Android Parcelable code generator</a></h1><p>JavaBean序列化，快速实现Parcelable接口。</p>
<p><img src="https://segmentfault.com/image?src=http://img.blog.csdn.net/20160416104459926&amp;objectId=1190000005092842&amp;token=ab29ed79d41be9e42b3a3d2ed1ec3bef" alt=""></p>
<h1 id="5-Android-Methods-Count"><a href="#5-Android-Methods-Count" class="headerlink" title="5.Android Methods Count"></a>5.<a href="http://plugins.jetbrains.com/plugin/8076?pr=androidstudio" target="_blank" rel="external">Android Methods Count</a></h1><p>显示依赖库中得方法数</p>
<p><img src="http://plugins.jetbrains.com/files/8076/screenshot_15509.png" alt=""></p>
<h1 id="6-Lifecycle-Sorter"><a href="#6-Lifecycle-Sorter" class="headerlink" title="6.Lifecycle Sorter"></a>6.<a href="http://plugins.jetbrains.com/plugin/7742?pr=androidstudio" target="_blank" rel="external">Lifecycle Sorter</a></h1><p>可以根据Activity或者fragment的生命周期对其生命周期方法位置进行先后排序，快捷键Ctrl + alt + K</p>
<p><img src="http://plugins.jetbrains.com/files/7742/screenshot_15071.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7742/screenshot_15070.png" alt=""></p>
<h1 id="7-CodeGlance"><a href="#7-CodeGlance" class="headerlink" title="7.CodeGlance"></a>7.<a href="http://plugins.jetbrains.com/plugin/7275?pr=androidstudio" target="_blank" rel="external">CodeGlance</a></h1><p>在右边可以预览代码，实现快速定位</p>
<p><img src="http://plugins.jetbrains.com/files/7275/screenshot_14294.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7275/screenshot_14295.png" alt=""></p>
<h1 id="8-findBugs-IDEA"><a href="#8-findBugs-IDEA" class="headerlink" title="8.findBugs-IDEA"></a>8.<a href="http://plugins.jetbrains.com/plugin/3847?pr=androidstudio" target="_blank" rel="external">findBugs-IDEA</a></h1><p>查找bug的插件，Android Studio也提供了代码审查的功能（Analyze-Inspect Code…）</p>
<p><img src="http://plugins.jetbrains.com/oldimg/screenshots/FindBugs-IDEA_2541.png" alt=""></p>
<h1 id="9-ADB-WIFI"><a href="#9-ADB-WIFI" class="headerlink" title="9.ADB WIFI"></a>9.<a href="http://plugins.jetbrains.com/plugin/7856?pr=androidstudio" target="_blank" rel="external">ADB WIFI</a></h1><p>使用wifi无线调试你的app，无需root权限<br>也可参考以下文章：<br><a href="http://www.jianshu.com/p/21d1b65d92a4" target="_blank" rel="external">Android wifi无线调试App新玩法ADB WIFI</a></p>
<p><img src="http://plugins.jetbrains.com/files/7856/screenshot_15153.png" alt=""></p>
<h1 id="10-AndroidPixelDimenGenerator"><a href="#10-AndroidPixelDimenGenerator" class="headerlink" title="10.AndroidPixelDimenGenerator"></a>10.<a href="https://github.com/succlz123/AndroidPixelDimenGenerator" target="_blank" rel="external">AndroidPixelDimenGenerator</a></h1><p>Android Studio自动生成dimen.xml文件插件</p>
<p><img src="https://github.com/succlz123/AndroidPixelDimenGenerator/raw/master/snapshot/1.jpeg" alt=""></p>
<h1 id="11-JsonOnlineViewer"><a href="#11-JsonOnlineViewer" class="headerlink" title="11.JsonOnlineViewer"></a>11.<a href="http://plugins.jetbrains.com/plugin/7838?pr=androidstudio" target="_blank" rel="external">JsonOnlineViewer</a></h1><p>在Android Studio中请求、调试接口</p>
<p><img src="http://plugins.jetbrains.com/files/7838/screenshot_15113.png" alt=""></p>
<h1 id="12-Android-Styler"><a href="#12-Android-Styler" class="headerlink" title="12.Android Styler"></a>12.<a href="http://plugins.jetbrains.com/plugin/7972?pr=androidstudio" target="_blank" rel="external">Android Styler</a></h1><p>根据xml自动生成style代码的插件</p>
<p><img src="http://plugins.jetbrains.com/files/7972/screenshot_15340.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7972/screenshot_15339.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7972/screenshot_15338.png" alt=""></p>
<h2 id="Usage"><a href="#Usage" class="headerlink" title="Usage:"></a>Usage:</h2><p>a. copy lines with future style from your layout.xml file<br>b. paste it to styles.xml file with Ctrl+Shift+D (or context menu)<br>c. enter name of new style in the modal window<br>d. your style is prepared! </p>
<h1 id="13-Android-Drawable-Importer"><a href="#13-Android-Drawable-Importer" class="headerlink" title="13.Android Drawable Importer"></a>13.<a href="http://plugins.jetbrains.com/plugin/7658?pr=androidstudio" target="_blank" rel="external">Android Drawable Importer</a></h1><p>这是一个非常强大的图片导入插件。它导入Android图标与Material图标的Drawable ，批量导入Drawable ，多源导入Drawable（即导入某张图片各种dpi对应的图片）</p>
<p><img src="http://plugins.jetbrains.com/files/7658/screenshot_15535.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7658/screenshot_15691.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7658/screenshot_15533.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7658/screenshot_15537.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7658/screenshot_15536.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7658/screenshot_15534.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7658/screenshot_15532.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7658/screenshot_15351.png" alt=""></p>
<h1 id="14-SelectorChapek-for-Android"><a href="#14-SelectorChapek-for-Android" class="headerlink" title="14.SelectorChapek for Android"></a>14.<a href="http://plugins.jetbrains.com/plugin/7298?pr=androidstudio" target="_blank" rel="external">SelectorChapek for Android</a></h1><p>通过资源文件命名自动生成Selector文件。</p>
<p><img src="http://plugins.jetbrains.com/files/7298/screenshot_14292.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7298/screenshot_14291.png" alt=""><br><img src="http://plugins.jetbrains.com/files/7298/screenshot_14290.png" alt=""></p>
<h1 id="15-GenerateSerialVersionUID"><a href="#15-GenerateSerialVersionUID" class="headerlink" title="15.GenerateSerialVersionUID"></a>15.<a href="http://plugins.jetbrains.com/plugin/185?pr=androidstudio" target="_blank" rel="external">GenerateSerialVersionUID</a></h1><p>实现Serializable序列化bean</p>
<p>Adds a new action ‘SerialVersionUID’ in the generate menu (alt + ins). The action adds an serialVersionUID field in the current class or updates it if it already exists, and assigns it the same value the standard ‘serialver’ JDK tool would return. The action is only visible when IDEA is not rebuilding its indexes, the class is serializable and either no serialVersionUID field exists or its value is different from the one the ‘serialver’ tool would return.</p>
<h1 id="16-genymotion"><a href="#16-genymotion" class="headerlink" title="16.genymotion"></a>16.<a href="http://plugins.jetbrains.com/plugin/7269?pr=androidstudio" target="_blank" rel="external">genymotion</a></h1><p>速度较快的android模拟器</p>
<p><img src="http://plugins.jetbrains.com/files/7269/screenshot_14278.png" alt=""></p>
<h1 id="17-LeakCanary"><a href="#17-LeakCanary" class="headerlink" title="17.LeakCanary"></a>17.<a href="https://github.com/square/leakcanary" target="_blank" rel="external">LeakCanary</a></h1><p>帮助你在开发阶段方便的检测出内存泄露的问题，使用起来更简单方便。<br>可以参考以下文章：<br><a href="http://www.liaohuqiu.net/cn/posts/leak-canary-read-me/" target="_blank" rel="external">LeakCanary 中文使用说明</a></p>
<p><img src="http://stormzhang.com/image/leakcaneray.png" alt=""></p>
<h1 id="18-Android-Postfix-Completion"><a href="#18-Android-Postfix-Completion" class="headerlink" title="18.Android Postfix Completion"></a>18.<a href="http://plugins.jetbrains.com/plugin/7775?pr=androidstudio" target="_blank" rel="external">Android Postfix Completion</a></h1><p>可根据后缀快速完成代码，这个属于拓展吧，系统已经有这些功能，如sout、notnull等，这个插件在原有的基础上增添了一些新的功能，我更想做的是通过原作者的代码自己定制功能，那就更爽了</p>
<p><img src="http://plugins.jetbrains.com/files/7775/screenshot_15042.png" alt=""></p>
<h1 id="19-Android-Holo-Colors-Generator"><a href="#19-Android-Holo-Colors-Generator" class="headerlink" title="19.Android Holo Colors Generator"></a>19.<a href="https://plugins.jetbrains.com/plugin/7366?pr=" target="_blank" rel="external">Android Holo Colors Generator</a></h1><p>通过自定义Holo主题颜色生成对应的Drawable和布局文件</p>
<p><img src="https://plugins.jetbrains.com/files/7366/screenshot_14379.png" alt=""></p>
<h1 id="20-dagger-intellij-plugin"><a href="#20-dagger-intellij-plugin" class="headerlink" title="20.dagger-intellij-plugin"></a>20.<a href="https://github.com/square/dagger-intellij-plugin" target="_blank" rel="external">dagger-intellij-plugin</a></h1><p>dagger可视化辅助工具</p>
<p><img src="https://github.com/square/dagger-intellij-plugin/raw/master/images/inject-to-provide.gif" alt=""></p>
<h1 id="21-GradleDependenciesHelperPlugin"><a href="#21-GradleDependenciesHelperPlugin" class="headerlink" title="21.GradleDependenciesHelperPlugin"></a>21.<a href="https://github.com/ligi/GradleDependenciesHelperPlugin" target="_blank" rel="external">GradleDependenciesHelperPlugin</a></h1><p>maven gradle 依赖支持自动补全</p>
<p><img src="https://camo.githubusercontent.com/d9b1b39eda21e0e33b656e2821f01897d915f7c5/68747470733a2f2f6c68332e676f6f676c6575736572636f6e74656e742e636f6d2f2d51364e7970315864594c772f556a73325a5175666634492f414141414141414144624d2f624d704c516742664d6b632f773538372d683330392d6e6f2f696465615f677261646c655f706c7567696e2e706e67" alt=""></p>
<h1 id="22-RemoveButterKnife"><a href="#22-RemoveButterKnife" class="headerlink" title="22.RemoveButterKnife"></a>22.<a href="https://github.com/u3shadow/RemoveButterKnife" target="_blank" rel="external">RemoveButterKnife</a></h1><p>ButterKnife这个第三方库每次更新之后，绑定view的注解都会改变，从bind,到inject，再到bindview，搞得很多人都不敢升级，一旦升级，就会有巨量的代码需要手动修改，非常痛苦<br>当我们有一些非常棒的代码需要拿到其他项目使用，但是我们发现，那个项目对第三方库的使用是有限制的，我们不能使用butterknife，这时候，我们又得从注解改回findviewbyid<br>针对上面的两种情况，如果view比较少还好说，如果有几十个view，那么我们一个个的手动删除注解，写findviewbyid语句，简直是一场噩梦（别问我为什么知道这是噩梦）<br>所以，这种有规律又重复简单的工作为什么不能用一个插件来实现呢？于是RemoveButterKnife的想法就出现了。</p>
<p><a href="http://www.u3coding.com/2016/06/24/androidstudio-plugin-removebutterknife-di/" target="_blank" rel="external">具体介绍</a></p>
<p><img src="https://camo.githubusercontent.com/0327cda5b531ab6f2b803abe295c42225668d28d/687474703a2f2f7777772e7533636f64696e672e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031362f30362f312e676966" alt=""></p>
<h1 id="23-AndroidProguardPlugin"><a href="#23-AndroidProguardPlugin" class="headerlink" title="23.AndroidProguardPlugin"></a>23.<a href="https://github.com/zhonghanwen/AndroidProguardPlugin" target="_blank" rel="external">AndroidProguardPlugin</a></h1><p>一键生成项目混淆代码插件，值得你安装~(不过目前可能有些第三方项目的混淆还未添加完全)</p>
<p><img src="http://7xrnko.com1.z0.glb.clouddn.com/androidproguard1.gif" alt=""></p>
<h1 id="24-otto-intellij-plugin"><a href="#24-otto-intellij-plugin" class="headerlink" title="24.otto-intellij-plugin"></a>24.<a href="https://github.com/square/otto-intellij-plugin" target="_blank" rel="external">otto-intellij-plugin</a></h1><p>otto事件导航工具。</p>
<p><img src="https://github.com/square/otto-intellij-plugin/raw/master/images/produce-to-subscribe.gif" alt=""><br><img src="https://github.com/square/otto-intellij-plugin/raw/master/images/event-to-subscribe.gif" alt=""></p>
<h1 id="25-eventbus-intellij-plugin"><a href="#25-eventbus-intellij-plugin" class="headerlink" title="25.eventbus-intellij-plugin"></a>25.<a href="https://github.com/kgmyshin/eventbus-intellij-plugin" target="_blank" rel="external">eventbus-intellij-plugin</a></h1><p>eventbus导航插件(对于最新版的 EventBus 3.0.0 好像无效,请替换为eventbus3-intellij-plugin此插件地址在本文第51个)</p>
<p><img src="https://raw.githubusercontent.com/kgmyshin/eventbus-intellij-plugin/master/art/cap.gif" alt=""></p>
<h1 id="26-idea-markdown"><a href="#26-idea-markdown" class="headerlink" title="26.idea-markdown"></a>26.<a href="https://github.com/nicoulaj/idea-markdown" target="_blank" rel="external">idea-markdown</a></h1><p>markdown插件</p>
<p><img src="https://github.com/nicoulaj/idea-markdown/raw/assets/screenshots/preview.png" alt=""></p>
<h1 id="27-Sexy-Editor"><a href="#27-Sexy-Editor" class="headerlink" title="27.Sexy Editor"></a>27.<a href="https://plugins.jetbrains.com/plugin/1833?pr=androidstudio" target="_blank" rel="external">Sexy Editor</a></h1><p>设置AS代码编辑区的背景图</p>
<p>首先点击界面的设置按钮 进入设置界面，选中Plugins,右边选择 Browser … ，输入Sexy … 下面自动弹出候选插件，右边点击Install 安装<br><img src="http://d.hiphotos.baidu.com/zhidao/wh%3D600%2C800/sign=f57bdd37f0246b607b5bba72dbc83674/4b90f603738da9777260054fb651f8198618e303.jpg" alt=""><br>安装成功 后需要重启AS<br><img src="http://h.hiphotos.baidu.com/zhidao/wh%3D600%2C800/sign=77e4e517fdf2b211e47b8d48fab04900/1c950a7b02087bf46d0dd48df4d3572c10dfcff5.jpg" alt=""><br>重启完成之后 进入设置界面 选择other Setting 下的Sexy Editor ， 右侧 insert 一张或多张图片即可，上面的其他设置可以设置方位 间隔时间 透明度等等，设置完成后，要关闭打开的文件，重新打开项目文件即可在代码编辑区显示插入的图片，作为代码编辑区的背景图。<br><img src="http://h.hiphotos.baidu.com/zhidao/wh%3D600%2C800/sign=5cd9b28564d9f2d320442ce999dca62b/34fae6cd7b899e51289eb77044a7d933c8950d45.jpg" alt=""></p>
<h1 id="28-folding-plugin"><a href="#28-folding-plugin" class="headerlink" title="28.folding-plugin"></a>28.<a href="https://github.com/dmytrodanylyk/folding-plugin" target="_blank" rel="external">folding-plugin</a></h1><p>布局文件分组的插件</p>
<p><img src="https://github.com/dmytrodanylyk/folding-plugin/raw/master/screenshots/Preview.png" alt=""></p>
<h1 id="29-Android-DPI-Calculator"><a href="#29-Android-DPI-Calculator" class="headerlink" title="29.Android-DPI-Calculator"></a>29.<a href="https://github.com/JerzyPuchalski/Android-DPI-Calculator" target="_blank" rel="external">Android-DPI-Calculator</a></h1><p>DPI计算插件</p>
<p><img src="https://camo.githubusercontent.com/ce3be2aaa3b1f70b90f5b825c529694509d70313/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f6469616c6f672e706e67" alt=""></p>
<p>使用：<br><img src="https://camo.githubusercontent.com/598d3b5c9efc5f0b57b58c25a79a323d06307fad/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f616374696f6e2e706e67" alt=""><br>或者<br><img src="https://camo.githubusercontent.com/7a8f977de7a1ba6cd23fb64cbd37566690c27cdc/68747470733a2f2f7261772e6769746875622e636f6d2f4a65727a7950756368616c736b692f416e64726f69642d4450492d43616c63756c61746f722f6d61737465722f696d672f6d656e752e706e67" alt=""></p>
<h1 id="30-gradle-retrolambda"><a href="#30-gradle-retrolambda" class="headerlink" title="30.gradle-retrolambda"></a>30.<a href="https://github.com/evant/gradle-retrolambda" target="_blank" rel="external">gradle-retrolambda</a></h1><p>在java 6 7中使用 lambda表达式插件</p>
<p>修改编译的jdk为java8:<br><img src="http://img.blog.csdn.net/20160311101644127" alt=""></p>
<h1 id="31-Android-Studio-Prettify"><a href="#31-Android-Studio-Prettify" class="headerlink" title="31.Android Studio Prettify"></a>31.<a href="https://plugins.jetbrains.com/plugin/7405" target="_blank" rel="external">Android Studio Prettify</a></h1><p>可以将代码中的字符串写在string.xml文件中</p>
<p>选中字符串鼠标右键选择图中所示<br><img src="https://plugins.jetbrains.com/files/7405/screenshot_14417.png" alt=""></p>
<p>这个插件还可以自动书写findViewById<br><img src="https://plugins.jetbrains.com/files/7405/screenshot_14418.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/7405/screenshot_14416.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/7405/screenshot_14501.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/7405/screenshot_14419.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/7405/screenshot_14415.png" alt=""></p>
<h1 id="32-Material-Theme-UI"><a href="#32-Material-Theme-UI" class="headerlink" title="32.Material Theme UI"></a>32.<a href="https://plugins.jetbrains.com/plugin/8006?pr=" target="_blank" rel="external">Material Theme UI</a></h1><p>添加Material主题到你的AS</p>
<p><img src="https://plugins.jetbrains.com/files/8006/screenshot_15722.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/8006/screenshot_15723.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/8006/screenshot_15721.png" alt=""></p>
<h1 id="33-ignore"><a href="#33-ignore" class="headerlink" title="33..ignore"></a>33.<a href="https://plugins.jetbrains.com/plugin/7495?pr=" target="_blank" rel="external">.ignore</a></h1><p>我们都知道在Git 中想要过滤掉一些不想提交的文件，可以把相应的文件添加到.gitignore 中，而.gitignore 这个Android Studio 插件根据不同的语言来选择模板，就不用自己在费事添加一些文件了，而且还有自动补全功能，过滤文件再也不要复制文件名了。我们做项目的时候，并不是所有文件都是要提交的，比如构建的build 文件夹，本地配置文件，每个Module 生成的iml 文件，但是我们每次add，commit 都会不小心把它们添加上去，而gitignore 就是解决这种痛点的，如果你不想提交的文件，就可以在创建项目的时候将这个文件中添加即可，将一些通用的东西屏蔽掉。</p>
<p><img src="https://plugins.jetbrains.com/files/7495/screenshot_14960.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/7495/screenshot_14958.png" alt=""></p>
<p><img src="https://plugins.jetbrains.com/files/7495/screenshot_14959.png" alt=""></p>
<h1 id="34-CheckStyle-IDEA"><a href="#34-CheckStyle-IDEA" class="headerlink" title="34.CheckStyle-IDEA"></a>34.<a href="https://plugins.jetbrains.com/plugin/1065?pr=" target="_blank" rel="external">CheckStyle-IDEA</a></h1><p>CheckStyle-IDEA 是一个检查代码风格的插件，比如像命名约定，Javadoc，类设计等方面进行代码规范和风格的检查，你们可以遵从像Google Oracle 的Java 代码指南 ，当然也可以按照自己的规则来设置配置文件，从而有效约束你自己更好地遵循代码编写规范。</p>
<h1 id="35-Markdown-Navigator"><a href="#35-Markdown-Navigator" class="headerlink" title="35.Markdown Navigator"></a>35.<a href="https://plugins.jetbrains.com/plugin/7896?pr=" target="_blank" rel="external">Markdown Navigator</a></h1><p>github:<a href="https://github.com/vsch/idea-multimarkdown/wiki" target="_blank" rel="external">Markdown Navigator</a><br>Markdown插件</p>
<p><img src="https://plugins.jetbrains.com/files/7896/screenshot_15818.png" alt=""></p>
<h1 id="36-ECTranslation"><a href="#36-ECTranslation" class="headerlink" title="36.ECTranslation"></a>36.<a href="https://github.com/Skykai521/ECTranslation" target="_blank" rel="external">ECTranslation</a></h1><p>Android Studio Plugin,Translate English to Chinese. Android Studio 翻译插件,可以将英文翻译为中文。</p>
<p><img src="https://github.com/Skykai521/ECTranslation/raw/master/img/translation_img.png" alt=""></p>
<h1 id="37-PermissionsDispatcher-plugin"><a href="#37-PermissionsDispatcher-plugin" class="headerlink" title="37.PermissionsDispatcher plugin"></a>37.<a href="https://plugins.jetbrains.com/plugin/8349" target="_blank" rel="external">PermissionsDispatcher plugin</a></h1><p>github:<a href="https://github.com/shiraji/permissions-dispatcher-plugin" target="_blank" rel="external">PermissionsDispatcher plugin</a><br>自动生成6.0权限的代码</p>
<p><img src="https://github.com/shiraji/permissions-dispatcher-plugin/raw/master/website/images/pd.gif" alt=""></p>
<h1 id="38-WakaTime"><a href="#38-WakaTime" class="headerlink" title="38.WakaTime"></a>38.<a href="https://plugins.jetbrains.com/plugin/7425?pr=" target="_blank" rel="external">WakaTime</a></h1><p>github:<a href="https://github.com/wakatime/jetbrains-wakatime" target="_blank" rel="external">WakaTime</a><br>记录你在IDE上的工作时间</p>
<p><img src="https://plugins.jetbrains.com/files/7425/screenshot_14794.png" alt=""></p>
<h1 id="39-AndroidWiFiADB"><a href="#39-AndroidWiFiADB" class="headerlink" title="39.AndroidWiFiADB"></a>39.<a href="https://github.com/pedrovgs/AndroidWiFiADB" target="_blank" rel="external">AndroidWiFiADB</a></h1><p>无线调试应用</p>
<p><img src="https://github.com/pedrovgs/AndroidWiFiADB/raw/master/art/screenshot1.gif" alt=""></p>
<p><img src="https://github.com/pedrovgs/AndroidWiFiADB/raw/master/art/android_devices_window.png" alt=""></p>
<h1 id="40-AndroidLocalizationer"><a href="#40-AndroidLocalizationer" class="headerlink" title="40.AndroidLocalizationer"></a>40.<a href="https://github.com/westlinkin/AndroidLocalizationer" target="_blank" rel="external">AndroidLocalizationer</a></h1><p>可用于将项目中的 string 资源自动翻译为其他语言的 Android Studio/IntelliJ IDEA 插件</p>
<p><img src="https://raw.githubusercontent.com/westlinkin/AndroidLocalizationer/master/screen_shot_3.png" alt=""></p>
<p><img src="https://raw.githubusercontent.com/westlinkin/AndroidLocalizationer/master/screen_shot_2.png" alt=""></p>
<h1 id="41-TranslationPlugin"><a href="#41-TranslationPlugin" class="headerlink" title="41.TranslationPlugin"></a>41.<a href="https://github.com/YiiGuxing/TranslationPlugin" target="_blank" rel="external">TranslationPlugin</a></h1><p>又一翻译插件,可中英互译。</p>
<p><img src="https://raw.githubusercontent.com/YiiGuxing/TranslationPlugin/master/images/1.png" alt=""></p>
<p><img src="https://raw.githubusercontent.com/YiiGuxing/TranslationPlugin/master/images/3.png" alt=""></p>
<h1 id="42-SingletonTest"><a href="#42-SingletonTest" class="headerlink" title="42.SingletonTest"></a>42.<a href="https://github.com/luhaoaimama1/SingletonTest" target="_blank" rel="external">SingletonTest</a></h1><p>快速生成单例模式的预设</p>
<p><img src="https://github.com/luhaoaimama1/SingletonTest/raw/master/demo/tip1.png" alt=""></p>
<p><img src="https://github.com/luhaoaimama1/SingletonTest/raw/master/demo/tip2.png" alt=""></p>
<p><img src="https://github.com/luhaoaimama1/SingletonTest/raw/master/demo/tip3.png" alt=""></p>
<h1 id="43-BorePlugin"><a href="#43-BorePlugin" class="headerlink" title="43.BorePlugin"></a>43.<a href="https://github.com/boredream/BorePlugin" target="_blank" rel="external">BorePlugin</a></h1><p>Android Studio 自动生成布局代码插件</p>
<p><img src="https://github.com/boredream/BorePlugin/raw/master/screenshot/LayoutCreator.gif" alt=""></p>
<h2 id="代码生成规则"><a href="#代码生成规则" class="headerlink" title="代码生成规则"></a>代码生成规则</h2><p>a.自动遍历目标布局中所有带id的文件, 无id的不会识别处理<br>b.控件生成的变量名默认为id名称, 可以在弹出确认框右侧的名称输入栏中自行修改<br>c.所有的Button或者带clickable=true的控件, 都会自动在代码中生成setOnClickListener相关代码<br>d.所有EditText控件, 都会在代码中生成非空判断代码, 如果为空会提示EditText的hint内容, 如果hint为空则提示xxx字符串不能为空字样, 最后会把所有输入框的验证合并到一个submit方法中<br>e.会自动识别布局中的include标签, 并读取对应布局中的控件</p>
<h1 id="44-jimu-Mirror"><a href="#44-jimu-Mirror" class="headerlink" title="44.jimu Mirror"></a>44.<a href="http://www.jimumirror.com/mirror-downloads/" target="_blank" rel="external">jimu Mirror</a></h1><p>能够实时预览Android布局，它会监听布局文件的改动，如果有代码变化，就会立即刷新UI。</p>
<h1 id="45-jRebel-For-Android"><a href="#45-jRebel-For-Android" class="headerlink" title="45.jRebel For Android"></a>45.<a href="http://zeroturnaround.com/software/jrebel-for-android/" target="_blank" rel="external">jRebel For Android</a></h1><p>不仅能够做到UI布局的实时预览，它甚至做到了让你更改java代码后就能实时替换apk中的类文件，达到应用实时刷新，官网的介绍是：Skip build, install and run，因此它可以节约我们很多很多的时间，它的效果也十分不错。</p>
<p><img src="http://zeroturnaround.com/wp-content/uploads/2015/04/Android_Card1_2x.png" alt=""></p>
<p><img src="http://zeroturnaround.com/wp-content/uploads/2015/04/Android_Card2_2x.png" alt=""></p>
<p><img src="http://zeroturnaround.com/wp-content/uploads/2015/04/Android_Card3_2x.png" alt=""></p>
<h1 id="46-sdk-manager-plugin"><a href="#46-sdk-manager-plugin" class="headerlink" title="46.sdk-manager-plugin"></a>46.<a href="https://github.com/JakeWharton/sdk-manager-plugin" target="_blank" rel="external">sdk-manager-plugin</a></h1><p>SDK管理插件，自动检测更新并下载。(图片与插件无关哈)</p>
<p><img src="https://camo.githubusercontent.com/95469d65798f62a50a9fcabe21e2cc303a1b859c/687474703a2f2f692e696d6775722e636f6d2f384a734a587a6e2e6a7067" alt=""></p>
<h1 id="47-Codota"><a href="#47-Codota" class="headerlink" title="47.Codota"></a>47.<a href="http://www.codota.com/" target="_blank" rel="external">Codota</a></h1><p>搜索最好的Android代码。(Studio里面直接可以搜到此插件)</p>
<h1 id="48-LayoutFormatter"><a href="#48-LayoutFormatter" class="headerlink" title="48.LayoutFormatter"></a>48.<a href="https://github.com/drakeet/LayoutFormatter" target="_blank" rel="external">LayoutFormatter</a></h1><p>drakeet 开发一个一键格式化你的 XML 文件的 Android Studio 插件，至于为什么不用 Android Studio 自带的格式化功能而用这个插件，可以看下作者的一篇 Blog -&gt; <a href="https://drakeet.me/layoutformatter" target="_blank" rel="external">当我们谈 XML 布局文件代码的优雅性</a></p>
<p><img src="http://ww1.sinaimg.cn/large/86e2ff85gw1f383wa95tej21ge0m5ai0.jpg" alt=""></p>
<h1 id="49-android-strings-search-plugin"><a href="#49-android-strings-search-plugin" class="headerlink" title="49.android-strings-search-plugin"></a>49.<a href="https://github.com/konifar/android-strings-search-plugin" target="_blank" rel="external">android-strings-search-plugin</a></h1><p>一个可以通过输入文字找到strings.xml资源的插件</p>
<p><img src="https://github.com/konifar/android-strings-search-plugin/raw/master/art/demo.gif" alt=""></p>
<h1 id="50-ideaVim"><a href="#50-ideaVim" class="headerlink" title="50.ideaVim"></a>50.<a href="http://plugins.jetbrains.com/plugin/164?pr=androidstudio" target="_blank" rel="external">ideaVim</a></h1><p>vim 本身就是一款很优秀的文本编辑器，而Android Studio 更是一款编写APP应用的神器。如果两个款优秀的软件结合在一起感觉会怎样呢？<br>详细请看文章:<a href="http://www.jianshu.com/p/43862126b88f" target="_blank" rel="external">Android Studio ＋Vim</a></p>
<p><img src="http://upload-images.jianshu.io/upload_images/1825722-8b55d9654777599e.gif?imageMogr2/auto-orient/strip" alt=""></p>
<h1 id="51-eventbus3-intellij-plugin"><a href="#51-eventbus3-intellij-plugin" class="headerlink" title="51.eventbus3-intellij-plugin"></a>51.<a href="https://github.com/likfe/eventbus3-intellij-plugin/blob/master/README-zh.md" target="_blank" rel="external">eventbus3-intellij-plugin</a></h1><p>引导 EventBus 的 post 和 event(对于最新版的 EventBus 3.0.0 有效)<br>主要Bug修复工作：<br>修改包名和方法名以适应 EventBus 3.X<br>替换一个在新版的 intellij plugin SDK 已经不存在的类<br>增加若干 try-catch ，防止插件崩溃</p>
<p><img src="https://raw.githubusercontent.com/likfe/eventbus3-intellij-plugin/master/art/cap.gif" alt=""></p>
<h1 id="52-Exynap"><a href="#52-Exynap" class="headerlink" title="52.Exynap"></a>52.<a href="http://exynap.com/" target="_blank" rel="external">Exynap</a></h1><p>Exynap 一个帮助开发者自动生成样板代码的 AndroidStudio 插件</p>
<p><img src="http://exynap.com/images/anim01.gif" alt=""></p>
<h1 id="53-gradle-cleaner-intellij-plugin"><a href="#53-gradle-cleaner-intellij-plugin" class="headerlink" title="53.gradle-cleaner-intellij-plugin"></a>53.<a href="https://github.com/Softwee/gradle-cleaner-intellij-plugin" target="_blank" rel="external">gradle-cleaner-intellij-plugin</a></h1><p>Force clear delaying &amp; no longer needed Gradle tasks.</p>
<p><img src="https://camo.githubusercontent.com/cb48bca7f8bd0b513f350f7320c74054d1b9fbce/687474703a2f2f6936352e74696e797069632e636f6d2f726a687863382e706e67" alt=""></p>
<h1 id="54-MVPHelper"><a href="#54-MVPHelper" class="headerlink" title="54.MVPHelper"></a>54.<a href="http://androidwing.net/index.php/27" target="_blank" rel="external">MVPHelper</a></h1><p>一款Intellj IDEA 和Android Studio的插件，可以为MVP生成接口以及实现类，解放双手。<br>具体请查看<a href="http://androidwing.net/index.php/27" target="_blank" rel="external">Android Studio插件之MVPHelper，一键生成MVP代码</a>一文</p>
<p><img src="https://github.com/githubwing/MVPHelper/raw/master/img/mvp_presenter.gif" alt=""></p>
<h1 id="55-Matchmaker"><a href="#55-Matchmaker" class="headerlink" title="55.Matchmaker"></a>55.<a href="https://github.com/lypeer/Matchmaker" target="_blank" rel="external">Matchmaker</a></h1><p>这是一款专为微信小程序开发的插件，目前可在 IntelliJ IDEA 中使用。它可以帮你完成重复机械无趣麻烦的绑定方法的过程，自动的将需要新建的方法注入到 js 文件中去。</p>
<p><img src="https://raw.githubusercontent.com/lypeer/Matchmaker/master/gif/plugin.gif" alt=""></p>
<h1 id="56-Emoji-Support-Plugin"><a href="#56-Emoji-Support-Plugin" class="headerlink" title="56.Emoji Support Plugin"></a>56.<a href="https://plugins.jetbrains.com/plugin/9174" target="_blank" rel="external">Emoji Support Plugin</a></h1><p>让 Intellij 支持 Emoji 输入提醒</p>
<p><img src="https://github.com/shiraji/emoji/raw/master/website/images/commit.gif" alt=""></p>
<h1 id="57-Open-Uploader"><a href="#57-Open-Uploader" class="headerlink" title="57.Open-Uploader"></a>57.<a href="https://github.com/fingerart/Open-Uploader" target="_blank" rel="external">Open-Uploader</a></h1><p>上传apk文件到指定的地址，提供自定义参数</p>
<p><img src="https://camo.githubusercontent.com/aa9d4468da25629928fc71256834a81fdaf2bebc/687474703a2f2f66696e6765726172742e71696e6975646e2e636f6d2f323031362d31302d31322d6f70656e5f75706c6f616465725f707265766965772e676966" alt=""></p>
<h1 id="58-MultiTypeTemplates"><a href="#58-MultiTypeTemplates" class="headerlink" title="58.MultiTypeTemplates"></a>58.<a href="https://github.com/drakeet/MultiTypeTemplates" target="_blank" rel="external">MultiTypeTemplates</a></h1><p>生成MultiType和itemviewprovider(关于MultiType请查看<a href="http://gank.io/post/5823bcf6421aa90e799ec2ad" target="_blank" rel="external">Android 复杂的列表视图新写法 MultiType</a>)</p>
<p><img src="https://camo.githubusercontent.com/d43ec0344dcce348e663ba57303fa6a26e4d1bf2/687474703a2f2f7777342e73696e61696d672e636e2f6c617267652f3836653266663835677731663933356c306b77696c6a32316b77307433616b6d2e6a7067" alt=""></p>
<p><img src="https://camo.githubusercontent.com/1eb2599f0689134d0bfc728b0ae38a4ead4010d3/687474703a2f2f7777342e73696e61696d672e636e2f6c617267652f38366532666638356777316638796a3073656a64366a323133343062656e31732e6a7067" alt=""></p>
<h1 id="59-Android-ButterKnife-Plugin-Plus"><a href="#59-Android-ButterKnife-Plugin-Plus" class="headerlink" title="59.Android-ButterKnife-Plugin-Plus"></a>59.<a href="https://github.com/OriginalLove/Android-ButterKnife-Plugin-Plus" target="_blank" rel="external">Android-ButterKnife-Plugin-Plus</a></h1><p>Android Studio 的插件，方便快速实现ButterKnife注解框架，包含了android-butterknife-zelezny 1.6版本的所有功能，并在此基础上新增如下功能：</p>
<p>1.可以自由选择是否在当前类中对ButterKnife进行初始化，避免了原版本只要使用插件初始化控件会自动在onCreate中进行ButterKnife.bind(this)的尴尬。</p>
<p><img src="https://github.com/OriginalLove/Android-ButterKnife-Plugin-Plus/raw/master/img/1.png" alt=""></p>
<p>这样就可以在基类中进行ButterKnife的初始化，不必要每个类中都要初始化，对开发框架的搭建更加方便。</p>
<p>2.在Android Studio的设置界面，对在当前类中是否强制初始化提供了默认值设置，这样就可以让插件使用更符合自己的操作习惯。</p>
<p><img src="https://github.com/OriginalLove/Android-ButterKnife-Plugin-Plus/raw/master/img/2.png" alt=""></p>
<h1 id="60-ApkMultiChannelPlugin"><a href="#60-ApkMultiChannelPlugin" class="headerlink" title="60. ApkMultiChannelPlugin"></a>60. <a href="https://github.com/nukc/ApkMultiChannelPlugin" target="_blank" rel="external">ApkMultiChannelPlugin</a></h1><p>这是一个为了方便 Android 多渠道打包的 Android Studio / IDEA 插件</p>
<p><strong>安装:</strong></p>
<ul>
<li>打开 Android Studio: 打开 Setting/Preferences -&gt; Plugins -&gt; Browse repositories 然后搜索 ApkMultiChannel 安装重启</li>
</ul>
<p>或者</p>
<ul>
<li>下载 <a href="https://plugins.jetbrains.com/idea/plugin/9369" target="_blank" rel="external">ApkMultiChannelPlugin.jar</a> 然后 Setting/Preferences -&gt; Plugins -&gt; Install plugin from disk 选择 ApkMultiChannelPlugin.jar 安装重启</li>
</ul>
<p><strong>使用方式:</strong></p>
<ol>
<li><p>选择 apk</p>
<p>选择一个 apk 然后右键，点击 Build MultiChannel<br><img src="https://raw.githubusercontent.com/nukc/ApkMultiChannelPlugin/master/art/choose-apk.png" alt=""></p>
</li>
<li><p>配置</p>
<p>配置签名信息，打包方式和渠道等<br><img src="https://raw.githubusercontent.com/nukc/ApkMultiChannelPlugin/master/art/setting.png" alt=""></p>
<p>配置说明：</p>
<p>Key Store Path: 签名文件的路径</p>
<p>Key Store Password: 签名文件的密码</p>
<p>Key Alias: 密钥别名</p>
<p>Key Password: 密钥密码 </p>
<p>Zipalign Path: zipalign文件的路径（用于优化 apk；zipalign 可以确保所有未压缩的数据均是以相对于文件开始部分的特定字节对齐开始，这样可减少应用消耗的 RAM 量。）</p>
<p>Signer Version: 选择签名版本：apksigner 和 jarsigner </p>
<p>Build Type: 打包方式 </p>
<p>Channels: 渠道列表，每行一个，最前面可加 &gt; 或不加（保存信息的时候，程序会自行加上）</p>
</li>
<li><p>开始打包</p>
<p>配置完成之后按 OK 就会开始进行渠道打包，文件会输出在选中的apk的当前目录下的channels目录中<br><img src="https://raw.githubusercontent.com/nukc/ApkMultiChannelPlugin/master/art/output.png" alt=""></p>
</li>
</ol>
<h1 id="61-CodeMaker"><a href="#61-CodeMaker" class="headerlink" title="61.CodeMaker"></a>61.<a href="https://github.com/x-hansong/CodeMaker" target="_blank" rel="external">CodeMaker</a></h1><p>一个 IDEA 的代码生成插件，通过 Velocity 支持自定义代码模板来生成代码。详细介绍<a href="http://blog.xiaohansong.com/2017/02/03/codemaker/?hmsr=toutiao.io&amp;utm_medium=toutiao.io&amp;utm_source=toutiao.io" target="_blank" rel="external">IDEA代码生成插件CodeMaker</a></p>
<p><img src="http://7xjtfr.com1.z0.glb.clouddn.com/codemaker.gif" alt=""></p>
<h1 id="62-adb-idea"><a href="#62-adb-idea" class="headerlink" title="62.adb-idea"></a>62.<a href="https://github.com/pbreault/adb-idea" target="_blank" rel="external">adb-idea</a></h1><p>可以一键清理缓存并重启APP</p>
<p><img src="https://github.com/pbreault/adb-idea/raw/master/website/find_actions.png" alt=""></p>
<p>此插件来自zhoutianling@ltbl.cn的分享，感谢<a href="">zhoutianling@ltbl.cn</a>的分享</p>
<h1 id="63-JVM-Debugger-Memory-View"><a href="#63-JVM-Debugger-Memory-View" class="headerlink" title="63.JVM Debugger Memory View"></a>63.<a href="https://blog.jetbrains.com/idea/2016/08/jvm-debugger-memory-view-for-intellij-idea/" target="_blank" rel="external">JVM Debugger Memory View</a></h1><p>Android Studio和IDEA中一个很有用的内存调试插件</p>
<p>详细可参考<a href="https://zhuanlan.zhihu.com/p/25110433" target="_blank" rel="external">说一说Android Studio和IDEA中一个很有用的内存调试插件</a>一文。</p>
<p><img src="https://user-gold-cdn.xitu.io/2017/2/6/69aa3f002477b228bf49b2478fce1d2b" alt=""></p>
<p>本文会持续更新（如果发现有好玩，好用的插件，欢迎通过Email:<a href="">ydmmocoo@gmail.com</a>告诉我），请持续关注。哈哈！</p>

      
    </div>

    <div>
      
        
      
    </div>

    <div>
      
        
  <div style="padding: 10px 0; margin: 20px auto; width: 90%; text-align: center;">
    <div>坚持原创技术分享，您的支持将鼓励我继续创作！</div>
    <button id="rewardButton" disable="enable" onclick="var qr = document.getElementById('QR'); if (qr.style.display === 'none') {qr.style.display='block';} else {qr.style.display='none'}">
      <span>赏</span>
    </button>
    <div id="QR" style="display: none;">
      
        <div id="wechat" style="display: inline-block">
          <img id="wechat_qr" src="http://7xvlr6.com1.z0.glb.clouddn.com/IMG_0537_%E5%89%AF%E6%9C%AC.png" alt="大弃 WeChat Pay"/>
          <p>微信打赏</p>
        </div>
      
      
        <div id="alipay" style="display: inline-block">
          <img id="alipay_qr" src="http://7xvlr6.com1.z0.glb.clouddn.com/IMG_0533_%E5%89%AF%E6%9C%AC.png" alt="大弃 Alipay"/>
          <p>支付宝打赏</p>
        </div>
      
    </div>
  </div>


      
    </div>

    <footer class="post-footer">
      
        <div class="post-tags">
          
            <a href="/tags/Android/" rel="tag">#Android</a>
          
        </div>
      

      
        <div class="post-nav">
          <div class="post-nav-next post-nav-item">
            
              <a href="/2016/06/24/Android自定义加载中Dialog/" rel="next" title="Android自定义加载中Dialog">
                <i class="fa fa-chevron-left"></i> Android自定义加载中Dialog
              </a>
            
          </div>

          <div class="post-nav-prev post-nav-item">
            
              <a href="/2016/06/30/Android调用微信扫一扫和支付宝扫一扫/" rel="prev" title="Android调用微信扫一扫和支付宝扫一扫">
                Android调用微信扫一扫和支付宝扫一扫 <i class="fa fa-chevron-right"></i>
              </a>
            
          </div>
        </div>
      

      
      
    </footer>
  </article>



    <div class="post-spread">
      
        <div class="ds-share flat" data-thread-key="2016/06/28/Android-Studio插件整理/"
     data-title="Android Studio插件整理"
     data-content=""
     data-url="http://yoursite.com/2016/06/28/Android-Studio插件整理/">
  <div class="ds-share-inline">
    <ul  class="ds-share-icons-16">

      <li data-toggle="ds-share-icons-more"><a class="ds-more" href="javascript:void(0);">分享到：</a></li>
      <li><a class="ds-weibo" href="javascript:void(0);" data-service="weibo">微博</a></li>
      <li><a class="ds-qzone" href="javascript:void(0);" data-service="qzone">QQ空间</a></li>
      <li><a class="ds-qqt" href="javascript:void(0);" data-service="qqt">腾讯微博</a></li>
      <li><a class="ds-wechat" href="javascript:void(0);" data-service="wechat">微信</a></li>

    </ul>
    <div class="ds-share-icons-more">
    </div>
  </div>
</div>
      
    </div>
  </div>


          </div>
          


          
  <div class="comments" id="comments">
    
      <div class="ds-thread" data-thread-key="2016/06/28/Android-Studio插件整理/"
           data-title="Android Studio插件整理" data-url="http://yoursite.com/2016/06/28/Android-Studio插件整理/">
      </div>
    
  </div>


        </div>
        
          
  
  <div class="sidebar-toggle">
    <div class="sidebar-toggle-line-wrap">
      <span class="sidebar-toggle-line sidebar-toggle-line-first"></span>
      <span class="sidebar-toggle-line sidebar-toggle-line-middle"></span>
      <span class="sidebar-toggle-line sidebar-toggle-line-last"></span>
    </div>
  </div>

  <aside id="sidebar" class="sidebar">
    <div class="sidebar-inner">

      

      
        <ul class="sidebar-nav motion-element">
          <li class="sidebar-nav-toc sidebar-nav-active" data-target="post-toc-wrap" >
            文章目录
          </li>
          <li class="sidebar-nav-overview" data-target="site-overview">
            站点概览
          </li>
        </ul>
      

      <section class="site-overview sidebar-panel ">
        <div class="site-author motion-element" itemprop="author" itemscope itemtype="http://schema.org/Person">
          <img class="site-author-image" itemprop="image"
               src="/images/avatar.gif"
               alt="大弃" />
          <p class="site-author-name" itemprop="name">大弃</p>
          <p class="site-description motion-element" itemprop="description">追求技术的路上永远不能停下脚步。。。</p>
        </div>
        <nav class="site-state motion-element">
          <div class="site-state-item site-state-posts">
            <a href="/">
              <span class="site-state-item-count">5</span>
              <span class="site-state-item-name">日志</span>
            </a>
          </div>

          
            <div class="site-state-item site-state-categories">
              <a href="/categories">
                <span class="site-state-item-count">1</span>
                <span class="site-state-item-name">分类</span>
              </a>
            </div>
          

          
            <div class="site-state-item site-state-tags">
              
                <span class="site-state-item-count">1</span>
                <span class="site-state-item-name">标签</span>
              
            </div>
          

        </nav>

        

        <div class="links-of-author motion-element">
          
        </div>

        
        

        
        

      </section>

      
        <section class="post-toc-wrap motion-element sidebar-panel sidebar-panel-active">
          <div class="post-toc">
            
              
            
            
              <div class="post-toc-content"><ol class="nav"><li class="nav-item nav-level-1"><a class="nav-link" href="#1-GsonFormat"><span class="nav-number">1.</span> <span class="nav-text">1.GsonFormat</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#2-Android-ButterKnife-Zelezny"><span class="nav-number">2.</span> <span class="nav-text">2.Android ButterKnife Zelezny</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#3-Android-Code-Generator"><span class="nav-number">3.</span> <span class="nav-text">3.Android Code Generator</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#4-Android-Parcelable-code-generator"><span class="nav-number">4.</span> <span class="nav-text">4.Android Parcelable code generator</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#5-Android-Methods-Count"><span class="nav-number">5.</span> <span class="nav-text">5.Android Methods Count</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#6-Lifecycle-Sorter"><span class="nav-number">6.</span> <span class="nav-text">6.Lifecycle Sorter</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#7-CodeGlance"><span class="nav-number">7.</span> <span class="nav-text">7.CodeGlance</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#8-findBugs-IDEA"><span class="nav-number">8.</span> <span class="nav-text">8.findBugs-IDEA</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#9-ADB-WIFI"><span class="nav-number">9.</span> <span class="nav-text">9.ADB WIFI</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#10-AndroidPixelDimenGenerator"><span class="nav-number">10.</span> <span class="nav-text">10.AndroidPixelDimenGenerator</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#11-JsonOnlineViewer"><span class="nav-number">11.</span> <span class="nav-text">11.JsonOnlineViewer</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#12-Android-Styler"><span class="nav-number">12.</span> <span class="nav-text">12.Android Styler</span></a><ol class="nav-child"><li class="nav-item nav-level-2"><a class="nav-link" href="#Usage"><span class="nav-number">12.1.</span> <span class="nav-text">Usage:</span></a></li></ol></li><li class="nav-item nav-level-1"><a class="nav-link" href="#13-Android-Drawable-Importer"><span class="nav-number">13.</span> <span class="nav-text">13.Android Drawable Importer</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#14-SelectorChapek-for-Android"><span class="nav-number">14.</span> <span class="nav-text">14.SelectorChapek for Android</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#15-GenerateSerialVersionUID"><span class="nav-number">15.</span> <span class="nav-text">15.GenerateSerialVersionUID</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#16-genymotion"><span class="nav-number">16.</span> <span class="nav-text">16.genymotion</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#17-LeakCanary"><span class="nav-number">17.</span> <span class="nav-text">17.LeakCanary</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#18-Android-Postfix-Completion"><span class="nav-number">18.</span> <span class="nav-text">18.Android Postfix Completion</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#19-Android-Holo-Colors-Generator"><span class="nav-number">19.</span> <span class="nav-text">19.Android Holo Colors Generator</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#20-dagger-intellij-plugin"><span class="nav-number">20.</span> <span class="nav-text">20.dagger-intellij-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#21-GradleDependenciesHelperPlugin"><span class="nav-number">21.</span> <span class="nav-text">21.GradleDependenciesHelperPlugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#22-RemoveButterKnife"><span class="nav-number">22.</span> <span class="nav-text">22.RemoveButterKnife</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#23-AndroidProguardPlugin"><span class="nav-number">23.</span> <span class="nav-text">23.AndroidProguardPlugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#24-otto-intellij-plugin"><span class="nav-number">24.</span> <span class="nav-text">24.otto-intellij-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#25-eventbus-intellij-plugin"><span class="nav-number">25.</span> <span class="nav-text">25.eventbus-intellij-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#26-idea-markdown"><span class="nav-number">26.</span> <span class="nav-text">26.idea-markdown</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#27-Sexy-Editor"><span class="nav-number">27.</span> <span class="nav-text">27.Sexy Editor</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#28-folding-plugin"><span class="nav-number">28.</span> <span class="nav-text">28.folding-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#29-Android-DPI-Calculator"><span class="nav-number">29.</span> <span class="nav-text">29.Android-DPI-Calculator</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#30-gradle-retrolambda"><span class="nav-number">30.</span> <span class="nav-text">30.gradle-retrolambda</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#31-Android-Studio-Prettify"><span class="nav-number">31.</span> <span class="nav-text">31.Android Studio Prettify</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#32-Material-Theme-UI"><span class="nav-number">32.</span> <span class="nav-text">32.Material Theme UI</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#33-ignore"><span class="nav-number">33.</span> <span class="nav-text">33..ignore</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#34-CheckStyle-IDEA"><span class="nav-number">34.</span> <span class="nav-text">34.CheckStyle-IDEA</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#35-Markdown-Navigator"><span class="nav-number">35.</span> <span class="nav-text">35.Markdown Navigator</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#36-ECTranslation"><span class="nav-number">36.</span> <span class="nav-text">36.ECTranslation</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#37-PermissionsDispatcher-plugin"><span class="nav-number">37.</span> <span class="nav-text">37.PermissionsDispatcher plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#38-WakaTime"><span class="nav-number">38.</span> <span class="nav-text">38.WakaTime</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#39-AndroidWiFiADB"><span class="nav-number">39.</span> <span class="nav-text">39.AndroidWiFiADB</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#40-AndroidLocalizationer"><span class="nav-number">40.</span> <span class="nav-text">40.AndroidLocalizationer</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#41-TranslationPlugin"><span class="nav-number">41.</span> <span class="nav-text">41.TranslationPlugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#42-SingletonTest"><span class="nav-number">42.</span> <span class="nav-text">42.SingletonTest</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#43-BorePlugin"><span class="nav-number">43.</span> <span class="nav-text">43.BorePlugin</span></a><ol class="nav-child"><li class="nav-item nav-level-2"><a class="nav-link" href="#代码生成规则"><span class="nav-number">43.1.</span> <span class="nav-text">代码生成规则</span></a></li></ol></li><li class="nav-item nav-level-1"><a class="nav-link" href="#44-jimu-Mirror"><span class="nav-number">44.</span> <span class="nav-text">44.jimu Mirror</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#45-jRebel-For-Android"><span class="nav-number">45.</span> <span class="nav-text">45.jRebel For Android</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#46-sdk-manager-plugin"><span class="nav-number">46.</span> <span class="nav-text">46.sdk-manager-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#47-Codota"><span class="nav-number">47.</span> <span class="nav-text">47.Codota</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#48-LayoutFormatter"><span class="nav-number">48.</span> <span class="nav-text">48.LayoutFormatter</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#49-android-strings-search-plugin"><span class="nav-number">49.</span> <span class="nav-text">49.android-strings-search-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#50-ideaVim"><span class="nav-number">50.</span> <span class="nav-text">50.ideaVim</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#51-eventbus3-intellij-plugin"><span class="nav-number">51.</span> <span class="nav-text">51.eventbus3-intellij-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#52-Exynap"><span class="nav-number">52.</span> <span class="nav-text">52.Exynap</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#53-gradle-cleaner-intellij-plugin"><span class="nav-number">53.</span> <span class="nav-text">53.gradle-cleaner-intellij-plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#54-MVPHelper"><span class="nav-number">54.</span> <span class="nav-text">54.MVPHelper</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#55-Matchmaker"><span class="nav-number">55.</span> <span class="nav-text">55.Matchmaker</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#56-Emoji-Support-Plugin"><span class="nav-number">56.</span> <span class="nav-text">56.Emoji Support Plugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#57-Open-Uploader"><span class="nav-number">57.</span> <span class="nav-text">57.Open-Uploader</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#58-MultiTypeTemplates"><span class="nav-number">58.</span> <span class="nav-text">58.MultiTypeTemplates</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#59-Android-ButterKnife-Plugin-Plus"><span class="nav-number">59.</span> <span class="nav-text">59.Android-ButterKnife-Plugin-Plus</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#60-ApkMultiChannelPlugin"><span class="nav-number">60.</span> <span class="nav-text">60. ApkMultiChannelPlugin</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#61-CodeMaker"><span class="nav-number">61.</span> <span class="nav-text">61.CodeMaker</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#62-adb-idea"><span class="nav-number">62.</span> <span class="nav-text">62.adb-idea</span></a></li><li class="nav-item nav-level-1"><a class="nav-link" href="#63-JVM-Debugger-Memory-View"><span class="nav-number">63.</span> <span class="nav-text">63.JVM Debugger Memory View</span></a></li></ol></div>
            
          </div>
        </section>
      

    </div>
  </aside>


        
      </div>
    </main>

    <footer id="footer" class="footer">
      <div class="footer-inner">
        <div class="copyright" >
  
  &copy; 
  <span itemprop="copyrightYear">2017</span>
  <span class="with-love">
    <i class="fa fa-heart"></i>
  </span>
  <span class="author" itemprop="copyrightHolder">大弃</span>
</div>

<div class="powered-by">
  由 <a class="theme-link" href="http://hexo.io">Hexo</a> 强力驱动
</div>

<div class="theme-info">
  主题 -
  <a class="theme-link" href="https://github.com/iissnan/hexo-theme-next">
    NexT.Mist
  </a>
</div>

        

        
      </div>
    </footer>

    <div class="back-to-top">
      <i class="fa fa-arrow-up"></i>
    </div>
  </div>

  

<script type="text/javascript">
  if (Object.prototype.toString.call(window.Promise) !== '[object Function]') {
    window.Promise = null;
  }
</script>









  



  
  <script type="text/javascript" src="/vendors/jquery/index.js?v=2.1.3"></script>

  
  <script type="text/javascript" src="/vendors/fastclick/lib/fastclick.min.js?v=1.0.6"></script>

  
  <script type="text/javascript" src="/vendors/jquery_lazyload/jquery.lazyload.js?v=1.9.7"></script>

  
  <script type="text/javascript" src="/vendors/velocity/velocity.min.js?v=1.2.1"></script>

  
  <script type="text/javascript" src="/vendors/velocity/velocity.ui.min.js?v=1.2.1"></script>

  
  <script type="text/javascript" src="/vendors/fancybox/source/jquery.fancybox.pack.js?v=2.1.5"></script>


  


  <script type="text/javascript" src="/js/src/utils.js?v=5.0.1"></script>

  <script type="text/javascript" src="/js/src/motion.js?v=5.0.1"></script>



  
  

  
  <script type="text/javascript" src="/js/src/scrollspy.js?v=5.0.1"></script>
<script type="text/javascript" src="/js/src/post-details.js?v=5.0.1"></script>



  


  <script type="text/javascript" src="/js/src/bootstrap.js?v=5.0.1"></script>



  

  
    
  

  <script type="text/javascript">
    var duoshuoQuery = {short_name:"ydmmocoo"};
    (function() {
      var ds = document.createElement('script');
      ds.type = 'text/javascript';ds.async = true;
      ds.id = 'duoshuo-script';
      ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';
      ds.charset = 'UTF-8';
      (document.getElementsByTagName('head')[0]
      || document.getElementsByTagName('body')[0]).appendChild(ds);
    })();
  </script>

  
    
  






  
  
  

  

  

</body>
</html>
