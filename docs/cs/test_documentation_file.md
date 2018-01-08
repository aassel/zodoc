﻿<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=Edge" />
        <meta name="description" />
        <meta name="keywords" content="static content generator,static site generator,static site,HTML,web development,.NET,C#,Razor,Markdown,YAML" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="shortcut icon" href="/zodoc/assets/img/favicon.ico" type="image/x-icon">
        <link rel="icon" href="/zodoc/assets/img/favicon.ico" type="image/x-icon">
        <title>ZODOC - Testovac&#xED; dokumentace</title>
        <link href="/zodoc/assets/css/mermaid.css" rel="stylesheet">
        <link href="/zodoc/assets/css/highlight.css" rel="stylesheet">
        <link href="/zodoc/assets/css/bootstrap/bootstrap.css" rel="stylesheet" />
        <link href="/zodoc/assets/css/adminlte/AdminLTE.css" rel="stylesheet" />
        <link href="/zodoc/assets/css/theme/theme.css" rel="stylesheet" />
        <link href="//fonts.googleapis.com/css?family=Roboto+Mono:400,700|Roboto:400,400i,700,700i" rel="stylesheet">
        <link href="/zodoc/assets/css/font-awesome.min.css" rel="stylesheet" type="text/css">
        <link href="/zodoc/assets/css/override.css" rel="stylesheet" />
        <script src="/zodoc/assets/js/jquery-2.2.3.min.js"></script>
        <script src="/zodoc/assets/js/bootstrap.min.js"></script>        
        <script src="/zodoc/assets/js/app.min.js"></script>         
        <script src="/zodoc/assets/js/highlight.pack.js"></script>   
        <script src="/zodoc/assets/js/jquery.slimscroll.min.js"></script>
        <script src="/zodoc/assets/js/jquery.sticky-kit.min.js"></script>
        <script src="/zodoc/assets/js/mermaid.min.js"></script>
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/3.2.2/anchor.min.js"></script>
        <!--[if lt IE 9]>
        <script src="/zodoc/assets/js/html5shiv.min.js"></script>
        <script src="/zodoc/assets/js/respond.min.js"></script>
        <![endif]-->  

        
    </head>
    <body class="hold-transition wyam layout-boxed  ">    
        <div class="top-banner"></div>
        <div class="wrapper with-container">
            <!-- Header -->
            <header class="main-header">   
                     
                <a href="/zodoc/" class="logo">
                            <span>ZODOC</span>
                </a>   
                         
                <nav class="navbar navbar-static-top" role="navigation">
                    <!-- Sidebar toggle button-->
                        <a href="#" class="sidebar-toggle visible-xs-block" data-toggle="offcanvas" role="button">
                            <span class="sr-only">Toggle side menu</span>
                            <i class="fa fa-chevron-circle-right"></i>
                        </a>
                                        
                    <div class="navbar-header">
                        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse">
                            <span class="sr-only">Toggle side menu</span>
                            <i class="fa fa-chevron-circle-down"></i>
                        </button>
                    </div>
            
                    <!-- Collect the nav links, forms, and other content for toggling -->
                    <div class="collapse navbar-collapse pull-left" id="navbar-collapse">
                        <ul class="nav navbar-nav">                            
                                    <li class="active"><a href="/zodoc/docs">Docs</a></li>
        <li><a href="/zodoc/exercises">Exercises</a></li>
        <li><a href="/zodoc/blog">Blog</a></li>
 
                        </ul>       
                    </div>
                    <!-- /.navbar-collapse -->
                
                    <!-- Navbar Right Menu -->
                </nav>
            </header>
            
            <!-- Left side column. contains the logo and sidebar -->
            <aside class="main-sidebar ">
                <section class="infobar" data-spy="affix" data-offset-top="60" data-offset-bottom="200"> 
                    	
        <div><p><a href="https://github.com/tesar-tech/zodoc/tree/master/input/docs/cs/test_documentation_file.md"><i class="fa fa-pencil-square" aria-hidden="true"></i> Edit Content</a></p></div>
    <div id="infobar-headings"></div>

                </section>
                <section class="sidebar">                    
                    

                    <ul class="sidebar-menu">
                        
                <li class="treeview">
                    <a href="/zodoc/docs/en">Documentation (English)</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                                        <li><a href="/zodoc/docs/en/matlab_start">Basic Operations on Images 1</a></li>
                <li><a href="/zodoc/docs/en/matlab_start2">Basic Operations on Images 2</a></li>
                <li><a href="/zodoc/docs/en/histogram">Histogram-based operations on images</a></li>
                <li><a href="/zodoc/docs/en/autofocus">Image sharpness detection and autofocus</a></li>
                <li><a href="/zodoc/docs/en/spectrum">Image spectra, fourier transformation, low-pass and high-pass filter</a></li>

                    </ul>
                </li>
                <li class="treeview active">
                    <a href="/zodoc/docs/cs">Dokumentace (&#x10C;esky)</a> <a href="#" class="expand"></a>
                    <ul class="treeview-menu">
                                        <li class="selected"><a href="/zodoc/docs/cs/test_documentation_file.md">Testovac&#xED; dokumentace</a></li>

                    </ul>
                </li>

                    </ul>
                </section>                
            </aside>
            
            <!-- Content Wrapper. Contains page content -->
            <div class="content-wrapper">
                



	<section class="content-header">
		<h1>Testovac&#xED; dokumentace</h1>
	</section>
	<section class="content">



	



		



	</section>
                
            </div>           
            
            <!-- Footer -->
            <footer class="main-footer">
            </footer>
            
        </div>
        <div class="wrapper bottom-wrapper">
            <footer class="bottom-footer">
                Generated by <a href="https://wyam.io">Wyam</a>
            </footer>
        </div>
        <a href="javascript:" id="return-to-top"><i class="fa fa-chevron-up"></i></a>
        
        <script>           
            // Close the sidebar if we select an anchor link
            $(".main-sidebar a[href^='#']:not('.expand')").click(function(){
                $(document.body).removeClass('sidebar-open');
            });
            
            $(document).load(function() {
                mermaid.initialize(
                {
                    flowchart:
                    {
                        htmlLabels: false,
                        useMaxWidth:false
                    }
                });  
                mermaid.init(undefined, ".mermaid")
                $('svg').addClass('img-responsive');
                
                $('pre code').each(function(i, block) {
                    hljs.highlightBlock(block);
                });  
            });
            hljs.initHighlightingOnLoad();

            // Back to top
            $(window).scroll(function() {
                if ($(this).scrollTop() >= 200) {        // If page is scrolled more than 50px
                    $('#return-to-top').fadeIn(1000);    // Fade in the arrow
                } else {
                    $('#return-to-top').fadeOut(1000);   // Else fade out the arrow
                }
            });
            $('#return-to-top').click(function() {      // When arrow is clicked
                $('body,html').animate({
                    scrollTop : 0                       // Scroll to top of body
                }, 500);
            });

        </script>
        <script type="text/javascript">
    anchors.options.placement = 'left';
    anchors.add();
</script>
    </body>
</html>