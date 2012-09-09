R.simple
=======

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<!-- theme made by Rafael López Fanjul URL:raphacoot.tumblr.com -->

<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>

<title>{Title}</title>
    <!-- DEFAULT VARIABLES -->
    <meta name="color:Background" content="#ffffff" />
    <meta name="color:Text" content="#000" />
    <meta name="font:Title" content="Verdana" />
    <meta name="font:Body" content="Verdana, Arial" />
    <meta name="font:Accent" content="Lucida Sans" />
    <meta name="if:Show Tags" content="1">
    <meta name="if:Show Album Art on Audio Posts" content="1" />
    <meta name="if:Enable Jump Pagination" content="0">
    <meta name="image:Header" content="" />
    <meta name="image:Background" content="" />
    <meta name="custom:Link" content"" />
    <meta name="text:Custom Link One" content="" />
    <meta name="text:Custom Link One Title" content="" />
    <meta name="text:Custom Link Two" content="" />
    <meta name="text:Custom Link Two Title" content="" />
    <meta name="text:Disqus Shortname" content"" />
    
    
    
    <style type="text/css">
            
            body { 
                background: {color:Background} url('{image:Background}') top left fixed repeat;
               margin: 0;
                padding: 0;
                font-family: {font:Body};
                }
                
                
            a.linksy {
                
                word-spacing: 30px;
            }
            
            a.linksy2 {
                
                text-decoration: underline;
            }    
            
            #wrapper {
                width: 500px;
                margin: 0 auto;
            }
              
                     .clear {
            clear: both;
            height: 0px;
            overflow: hidden;
        }     
              
             #wrapper #upbar {
                 margin: 10px 0;
                 width: 520px;
                 float; left;
                 border-radius: 4px;
                 background: #fff;
                 text-align: center;
                 padding-bottom: 20px;
                 {block:AskEnabled}display: block;{/Block:AskEnabled}
                 {block:SubmissionsEnabled}display: block;{Block:SubmissionsEnabled}
             } 
            
            #wrapper #upbar #links {
                word-spacing: 30px;
            }    
            
            #content {
                background-color: {color:Content Background};
                color: {color:Text};
                font: 12px {font:Body};
               
                
            }
            
            h1 {
              font-family: Verdana;
         font-size: 30px;
         text-align: center;
    
            }
            
            #wrapper #content {
                margin: 20px 0px;
                width: 520px;
                float: left;
                border-radius: 4px;
               
                
                
            }    
          
          
          
          #wrapper #content .post{
                width: 520px;
                font-family: {font:Body};               
                background: #fff;
                position: relative;
                border-radius: 4px;
                margin-bottom: 30px;
                
                
               
                }
                
            
           #wrapper #content .post .copy {
               color: #000;
               padding: 3px 10px 3px 10px;
               font-size: 13px;
               line-height: 15px;
               
               
           } 
           
           #wrapper #content .post .copy2 {
               color: #000;
               padding: 3px 123px 3px 10px;
               margin-top: -30px;
               font-size: 13px;
               line-height: 15px;
               background: #989898;
               margin-bottom: 0px;
               float: left;
               
           }
           
           #wrapper #content .post .title {
               color: #000;
               font-size: 16px;
               font-weight: bold;
               padding: 13px 10px 0px 10px;
           }   
           
           
           
            #wrapper #content .post .title2 {
               color: #000;
               font-size: 16px;
               font-weight: bold;
               padding: 9px 10px 0px 10px;
               margin-left: 8px;
               font-family: {font:Body}; 
               
           }   
           
           
           
           #wrapper #content .post .media {
           text-align: center;
           padding: 10px 0px ;
           }
           
           
           #wrapper #content .post .album_art {
               padding: 10px;
               position: relative;
               float: right;
               right: 15px;
               top: 5px;
              
           }  
           
            #wrapper #content .post .audio {
                        background: #989898;
                        float:left;
                        padding: 7px;
                        margin-bottom: 10px;
                        margin-left: 25px;
                        margin-top: 42px;
                        -moz-border-radius: 4px;
                        -webkit-border-radius: 4px;
                        border-radius: 0px;
                        position: relative;
            }
            
            
            
            #wrapper #content .post .audio .player {
                            float: left;
                            padding: 0px 0px 0px 0px;
                            
            }
            
            #wrapper #content .post .audio .meta {
                            padding: 8px 13px;
                            height: 13px;
                            float: left;
                            color: #fff;
                            font-family: {font:Accent};
                            font-size: 11px;
                            text-transform: lowercase;
             }
             
             #wrapper #content .post .quote {
                        color: #000;
                        font-weight: normal;
                        padding: 20px 20px 5px 20px;
                    }
                    
             #wrapper #content .post .quote.short {
                        font-size: 28px;
                        line-height: 31px;
                    }
                    
             #wrapper #content .post .quote.medium {
                        font-size: 20px;
                        line-height: 23px;
                    }
                    
             #wrapper #content .post .quote.long {
                        font-size: 12px;
                        line-height: 15px;
                    }
             
             #wrapper #content .post .quote_source{
                            padding-bottom: 10px;
                        }
                        
                       
                 #wrapper #content .post .quotebg {
                        font-family: georgia, serif;
                        font-size: 150px;
                        color: {color:Background};
                        opacity: 0.2;
                        filter: alpha(opacity=20);
                        -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=20)";
                        position: absolute;
                        top: 70px;
                        left: 10px;       
                        }
                        
                        #wrapper #content .post .question {
                        color: #494949;
                        font-size: 16px;
                        font-weight: bold;
                        background: #f1f1f1;
                        -moz-border-radius: 8px;
                        -webkit-border-radius: 8px;
                        border-radius: 4px;
                        margin: 0 0 15px 0;
                        padding: 15px 20px;
                        position: relative;
                    }
                    
                    #wrapper #content .post .question .nipple {
                            width: 13px;
                            height: 7px;
                            background: #f1f1f1 url('http://assets.tumblr.com/themes/redux/ask-mask.png');
                            position: absolute;
                            bottom: -7px;
                            left: 30px;
                        }
                        
                    #wrapper #content .post .asker_container {
                        margin: 0 0 20px 24px;
                        color: #000;
                    }
                    
                        #wrapper #content .post .asker_container img {
                            margin: 0 12px -7px 0;
                            color: #000;
                        }
                        
                        #wrapper #content .post .asker_container a.asker {
                            color: {color:Body};
                        }
                        
                        #ask { 
font-size:10px;
line-height:12px;
background-color: {color:label background};
padding:4px;
margin-bottom:4px;}

            #wrapper #content .post .chat {
                        background-color: #fff;
                        
                        margin: 16px 18px 0 10px;
                        font-size: 14px;
                        padding-top: 10px;
                    }
                                        
                        #wrapper #content .post .chat .lines {
                            margin-left: 5px;
                          
                        }
                        
                            #wrapper #content .post .chat .lines .line {
                                background-color: #eaeaea;
                                color: #494949;
                                margin-bottom: 1px;
                                padding: 3px 5px;
                                
                            }
                            
                            #wrapper #content .post .chat .lines .line.even {
                                background-color: #dedddd;
                            }
                            
                            
                            #wrapper #content .post .link {
                            margin: 4px 0 2px 0;
                            font-size: 16px;
                            line-height: 25px;
                            padding-left: 2px;
                            padding-top: 10px;
                            padding-bottom: 10px;
                        }
                            
                            #wrapper #content .post .link a {
                               
                                color: {color:Background};
                                padding: 5px 7px;
                                -moz-border-radius: 4px;
                                -webkit-border-radius: 4px;
                                border-radius: 0px;
                            }
                            
                            #wrapper #content .post .link a:hover {
                                opacity: 0.9;
                                filter: alpha(opacity=90);
                                -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=90)";
                            }

   
         #wrapper #content .post .footer {
                        background: #eaeaea;
                        -moz-border-radius: 4px;
                        -webkit-border-radius: 4px;
                        border-radius: 0px;
                        font-family: {font:Accent};
                        font-size: 11px;
                        color: #666;
                        padding: 5px 10px;
                        margin-top: 10px;
                    }
                        
                        #wrapper #content .post .footer.for_permalink:hover {
                            opacity: 0.9;
                            filter: alpha(opacity=90);
                            -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=90)";
                        }
                        
                        #wrapper #content .post .footer .date {
                            width: 67%;
                            float: left;
                            color: #666;
                        }
                        
                        #wrapper #content .post .footer .notes {
                            width: 33%;
                            float: right;
                            text-align: right;
                            color: #666;
                        }
                            
                            #wrapper #content .post .footer .notes a {
                                color: #666;
                            }
                            
                            #wrapper #content .post .footer .tags a {
                                color: #4a4a51;
                               
                            }
                            
                                #wrapper #content .post .footer .tags .tag-commas:last-child {
                                    display: none;
                                }
                            
                            #wrapper #content .post .footer.with_source_url .tags {
                                max-width: 330px;
                                float: left;
                            }
                            
                            #wrapper #content .post .footer.with_source_url .source_url {
                                float: right;
                                max-width: 160px;
                                overflow: hidden;
                                white-space: nowrap;
                                
                            }
                            
                                #wrapper #content .post .footer.with_source_url .source_url img {
                                    vertical-align: top;
                                    -moz-opacity: 0.5;
                                    opacity: 0.5;
                                }
                                
                                #wrapper #content .post .footer.with_source_url .source_url:hover img {
                                    -moz-opacity: 0.7;
                                    opacity: 0.7;
                                }
                                
                                #wrapper #content .bottom {
                            background: url('http://assets.tumblr.com/themes/redux/shadow-post.png') top center no-repeat transparent;
                            width: 0px;
                            height: 30px;
                            margin: 0 auto;
                        }
                        
                        #wrapper #content #navigation {
                            text-align: right;
                            padding-bottom: 35px;
                            text-transform: lowercase;
                        }
                        
                            #wrapper #content #navigation a {
                                background-color: #fff;
                                color: {color:Background};
                                padding: 5px 10px;
                                text-decoration: none;
                                margin-left: 25px;
                                border-radius: 4px;
                            }
                            
                            #wrapper #content #navigation a:hover {
                                opacity: 0.9;
                                filter: alpha(opacity=90);
                                -ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=90)";
                            }
                            
                        #wrapper #content #navigation.jump_pagination {}
                            
                            #wrapper #content #navigation.jump_pagination a {
                                margin: 0 0 0 4px;
                            }
                            
                            #wrapper #content #navigation.jump_pagination .current_page {
                                color: #fff;
                                background-color: rgba(255,255,255, 0.1);
                                border: 2px solid #fff;
                                padding: 3px 8px;
                                margin: 0 0 0 4px;
                                cursor: default;
                            }
                            
                            #wrapper #content #navigation.jump_pagination .jump_page {}
                            
                            
                             #wrapper #content .post .notecontainer {
                                background: #eaeaea;
                                -moz-border-radius: 4px;
                                -webkit-border-radius: 4px;
                                border-radius: 4px;
                                font-family: {font:Accent};
                                font-size: 11px;
                                color: #666;
                                margin-top: 10px;
                                margin-bottom: -10px;
                            }
                            
                                    #wrapper #content .post .notecontainer a {
                                        color: #666;
                                        text-decoration: underline;
                                    }
                                    
                                    #wrapper #content .post .notecontainer ol.notes {
                                        padding: 0px 0 10px 0;
                                        list-style-type: none;
                                        font-size: 11px;
                                    }
                                    
                                        #wrapper #content .post .notecontainer ol.notes li.note {
                                            padding: 10px 10px 0 10px;
                                        }
                                        
                                            #wrapper #content .post .notecontainer ol.notes li.note img.avatar {
                                                vertical-align: -4px;
                                                margin-right: 10px;
                                                width: 16px;
                                                height: 16px;
                                            }
                                            
                                            #wrapper #content .post .notecontainer ol.notes li.note span.action {
                                                font-weight: normal;
                                            }
                                            
                                            #wrapper #content .post .notecontainer ol.notes li.note .answer_content {
                                                font-weight: normal;
                                            }
                                            
                                            #wrapper #content .post .notecontainer ol.notes li.note blockquote {
                                                border-left: 2px solid #666;
                                                padding: 4px 10px;
                                                margin: 10px 0px 0px 25px;
                                            }
                                            
                                                #wrapper #content .post .notecontainer ol.notes li.note blockquote a {
                                                    text-decoration: none;
                                                }
   
    </style>
    
</head>
<body bgcolor="{color:Background}" link="#000" vlink="#000" alink="#000">
        <div id="content">
           <div id="wrapper">
           
           <div id="upbar">
           
           {block:IfHeaderImage}<img src="{image:Header}"/>{/block:IfHeaderImage}
        {block:IfNotHeaderImage}<h1>{Title}</h1>{/block:IfNotHeaderImage}
           <div id="links">
           {block:ifCustomLinkOneTitle}<a href="{text:Custom Link One}" class="linksy" style="color:#000">{text:Custom Link One Title}{/block:ifCustomLinkOneTitle}</a>
          
          {block:ifCustomLinkTwoTitle}<a href="{text:Custom Link Two}" class="linksy" style="color:#000">{text:Custom Link Two Title}{/block:ifCustomLinkTwoTitle}</a>
             
   <a href="http://raphacoot.tumblr.com" style="color:#000">Theme</a>
           
           <u>{block:AskEnabled}<a href="/ask" class="links" style="color:#000">Ask</a>{/block:AskEnabled}</u>
           <u>{block:SubmissionsEnabled}<a href="/submit" class="links"style="color:#000">Submit</a>{/block:SubmissionsEnabled}</u>
           
           </div>    
            </div>
           
          
<div id="content">
          
    {block:Posts}
              
            <div class="post">
            
            
            {block:Text}
              
             {block:Title}<div class="title">{Title}</div>{/block:Title}
             <div class="copy">{Body} </div>
                
            {/block:Text}
       

            {block:Photo}
                        <div class="media">{LinkOpenTag}<img src="{PhotoURL-500}" alt="{PhotoAlt}" />{LinkCloseTag}</div>
                        {block:Caption}<div class="copy">{Caption}</div>{/block:Caption}
            {/block:Photo}
            
            
            {block:Video}
                        <div class="media">{Video-500}</div>
                        {block:Caption}<div class="copy">{Caption}</div>{/block:Caption}
            {/block:Video}
            
            
            {block:Audio}
                        {block:IfShowAlbumArtOnAudioPosts}
                            {block:AlbumArt}
                                <div class="album_art">
                                    <img src="{AlbumArtURL}" alt="{block:Artist}{Artist}{/block:Artist}{block:TrackName} - {TrackName}{/block:TrackName}" style="margin-bottom:10px;" width="100" height="100"/>
                                </div>
                            {/block:AlbumArt}
                        {/block:IfShowAlbumArtOnAudioPosts}
                        
                        <div class="audio">
                            <div class="player">{AudioPlayerWhite}</div>
                            <div class="meta">{PlayCountWithLabel}{block:ExternalAudio}<span class="download_external_audio"> &bull; <a href="{ExternalAudioURL}">{lang:Download}</a></span>{/block:ExternalAudio}</div>
                   </div>
                            
                            
                        
                        <div class="clear"></div>
                        
               {/block:Audio}    
                
               {block:Quote}
                        <div class="quote {Length}">{Quote}</div>
                        <div class="copy">
                            <div class="quotebg">“</div>
                            {block:Source}
                                <table border="0" cellpadding="0" cellspacing="0" width="100%">
                                    <tr>
                                        <td valign="top" style="width:20px;">&mdash;</td>
                                        <td valign="top" class="quote_source">
                                            {Source}
                                        </td>
                                    </tr>
                                </table>
                            {/block:Source}
                        </div>
                 {/block:Quote} 
                
                 {block:Answer}
                        <div class="question">
                            <div class="nipple"></div>
                            {Question}
                        </div>
                        <div class="asker_container"><img src="{AskerPortraitURL-24}" >{Asker}</div>
                        <div class="copy">{Answer}</div>
                 {/block:Answer}
                
                 {block:Chat}
                        {block:Title}<div class="title2">{Title}</div>{/block:Title}
                        <div class="chat">
                            <div class="lines">
                                {block:Lines}
                                    <div class="line {Alt}">{block:Label}<strong>{Label}</strong>{/block:Label} {Line}</div>
                                {/block:Lines}
                            </div>
                        </div>
                        <div class="clear"></div>
                        <div style="height:10px;"></div>
                    {/block:Chat}
                    
                    
                    {block:Link}
                        <div class="link"><a href="{URL}" {Target}>{Name} &raquo;</a></div>
                        {block:Description}<div class="copy">{Description}</div>{/block:Description}
                    {/block:Link}
                    
                    
                    {block:Date}
                        <a href="{Permalink}">
                            <div class="footer for_permalink">
                                <div class="date">
                                    {block:Reblog}
                                        {lang:Reblogged TimeAgo from ReblogParentName} {block:RebloggedFromReblog}(<span style="text-transform:lowercase;">{lang:Originally from ReblogRootName}</span>){/block:RebloggedFromReblog}
                                    {/block:Reblog}
                                    
                                    {block:NotReblog}
                                        {lang:Posted TimeAgo from source}
                                    {/block:NotReblog}
                                </div>
                                <div class="notes">{block:NoteCount}{NoteCountWithLabel}{/block:NoteCount} {block:IfDisqusShortname}{block:NoteCount}&bull;{/block:NoteCount} <a href="{Permalink}#disqus_thread">{lang:View comments}</a>{/block:IfDisqusShortname}</div>
                                <div class="clear"></div>
                            </div>
                        </a>
                    {/block:Date}
                    
                    <div class="footer {block:ContentSource}with_source_url{/block:ContentSource}" style="
                        display:none;
                        {block:IfShowTags}{block:HasTags}display:block;{/block:HasTags}{/block:IfShowTags}
                        {block:ContentSource}display:block;{/block:ContentSource}
                    " >
                        {block:IfShowTags}
                            {block:HasTags}<div class="tags">{lang:Tagged}: {block:Tags}<a href="{TagURL}">{Tag}</a><span class="tag-commas">, </span>{/block:Tags}.</div>{/block:HasTags}
                        {/block:IfShowTags}
                        
                        {block:ContentSource}
                            <a href="{SourceURL}" class="source_url" style="color:#000">
                                {lang:Source}:
                                {block:SourceLogo}<img src="{BlackLogoURL}" width="{LogoWidth}" height="{LogoHeight}" alt="{SourceTitle}" />{/block:SourceLogo}
                                {block:NoSourceLogo}{SourceTitle}{/block:NoSourceLogo}
                            </a>
                        {/block:ContentSource}
                        
                        <div class="clear"></div>
                    </div>
                    {block:PostNotes}<div class="notecontainer">{PostNotes}</div>{/block:PostNotes}
                    
                    {block:IfDisqusShortname}
                        {block:Permalink}
                            <div class="notecontainer" style="margin:20px 0 1px 0; padding:1px 10px 10px 10px;">
                                <div id="disqus_thread"></div>
                                <script type="text/javascript" src="http://disqus.com/forums/{text:Disqus Shortname}/embed.js"></script>
                                <noscript><a href="http://{text:Disqus Shortname}.disqus.com/?url=ref">{lang:View the discussion thread}</a></noscript>
                            </div>
                            <div style="text-align:right; margin-top:5px;">
                                {lang:Blog comments powered by Disqus 2}
                            </div>
                        {/block:Permalink}
                    {/block:IfDisqusShortname}
                    
            </div>
            
            
            
           
   {/block:Posts} 
   {block:Pagination}
                <div id="navigation" {block:IfEnableJumpPagination}class="jump_pagination"{/block:IfEnableJumpPagination}>
                    {block:PreviousPage}<a href="{PreviousPage}">&larr; {lang:Previous}</a>{/block:PreviousPage}
                    
                    {block:IfEnableJumpPagination}
                        {block:JumpPagination length="5"}
                            {block:CurrentPage}
                                <span class="current_page">{PageNumber}</span>
                            {/block:CurrentPage}
                            
                            {block:JumpPage}
                                <a class="jump_page" href="{URL}">{PageNumber}</a>
                            {/block:JumpPage}
                            
                        {/block:JumpPagination}
                    {/block:IfEnableJumpPagination}
                    
                    {block:NextPage}<a href="{NextPage}">{lang:Next page} &rarr;</a>{/block:NextPage}
                </div>
            {/block:Pagination}
   
   
   
</div>           

           
            </div>
         </div>
    
</body>