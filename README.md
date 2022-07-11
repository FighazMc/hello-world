<!DOCTYPE html>
<html>
 <head>
  <title><data:view.title.escaped/></title>
  <b:skin>
   <![CDATA[]]>
  </b:skin>
 <style>
 /* Reset */
 html,body,div,body div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin: 0;padding: 0;border: 0;outline: 0;vertical-align: baseline;background: transparent}
 /* Global */
 body {
 font-family:Arial, Helvetica, sans-serif;
 font-size:medium;
 font-weight:normal;
 background-color:#FFF;
 margin:0px;
 }
 a:link {
 color: #2A78B8;
 text-decoration: none;
 }
 a:hover {
 color: #7BABD1;
 text-decoration: underline;
 }
 a:visited {
 color: #CCC;
 text-decoration: none;
 }
 a img {
 border-width:0;
 }
 /* Kontainer */
 #kontainer {
 width: 100%;
 max-width: 800px;
 margin: 0 auto;
 }
 /* Header */
 #header {
 display: block;
 background-color:#ec3a5c;
 height: auto;
 width: 100%;
 }
 #header.header.section {
 width:100%;
 }
 /* Konten */
 #konten {
 display: block;
 background-color:#2368a2;
 float: left;
 width: 70%;
 }
 #konten.konten.section {
 width:100%;
 }
 /* Sidebar */
 #sidebar {
 display: block;
 background-color:#ebba16;
 float: left;
 width: 30%;
 }
 #sidebar.sidebar.section {
 width:100%;
 }
 #sidebar .widget {
 padding:20px;
 }
 /* Footer */
 #footer {
 display: block;
 background-color:#23a24d;
 height: auto;
 width: 100%;
 }
 </style>
 </head>
 <body>
  <div id="kontainer">
   <!-- Header -->
   <div id="header">
    <b:section id='Header' class='header' name='header' maxwidgets='1' showaddelement='yes'>
     <b:widget id='Header1' locked='true' title='Test (Header)' type='Header'/>
    </b:section>
   </div>
   <!-- Konten -->
   <div id="konten">
    <b:section id='Konten' class='konten' name='Konten' maxwidgets='' showaddelements='yes'>
     <b:widget id='Blog1' locked='false' title='Blog Posts' type='Blog'/>
    </b:section>
   </div>
   <!-- Sidebar -->
   <div id="sidebar">
    <b:section id='Sidebar' class='sidebar' name='Sidebar' maxwidgets='' showaddelements='yes'>
     <b:widget id='ContactForm1' locked='false' title='Formulir Kontak' type='ContactForm'/>
    </b:section>
   </div>
   <div style="clear: both;"/>
   <!-- Footer -->
   <div id="footer">
    <b:section id='Footer' class='footer' name='footer' maxwidgets='' showaddelements='yes'>
     <b:widget id='Attribution1' locked='false' title='Atribusi' type='Attribution'/>
    </b:section>
   </div>
  </div>
 </body>
</html>
