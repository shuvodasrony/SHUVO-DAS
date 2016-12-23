// ==UserScript==
// @name        10 Files
// @namespace   10 Files
// @Credit      SHUVO DAS
// @include     http://indianvisa-bangladesh.nic.in/visa/Get_Appointment
// @include     http://indianvisa-bangladesh.nic.in/visa/Allotment
// @include     http://indianvisa-bangladesh.nic.in/visa/Appointment_Login.jsp
// @version     2.32
// @grant       none
// ==/UserScript==



javascript:(function(){


  
  
  
function file1(){
  //
////// FILE 1 //////

var bgd      = "BGDDW2B70A16";
var bgd2     = "BGDDW2B68616";
var bgd3     = "BGDDW2B6E616";
var bgd4     = "BGDDW2B7FC16";
var bgd5     = "BGDDW2B84F16";
var bgd6     = "BGDDW2B96316";
      
var pn       = "BE0160898";
  
var gn       = "MDAWLADHOSSAIN";
var bp       = "MADARIPUR";
var fn       = "MDSULTANKHAN";
var mn       = "SAYADUNNESA";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';


  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};

function file2(){ 
  
// FILE 2 // 

var bgd      = "BGDDW264FF16";
var bgd2     = "BGDDW2650116";
var bgd3     = "BGDDW264FE16";
var bgd4     = "BGDDW2650A16";

var bgd5     = "BGDDW2650E16";
var bgd6     = "BGDDW2651616";
      
var pn       = "BF0162145";
  
var gn       = "MDMOYEN";
var bp       = "DHAKA";
var fn       = "MOSLEMUDDIN";
var mn       = "HOSNEARABAGUM";
// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
    document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};


function file3(){ 
  
// FILE 3 // 

var bgd      = "BGDDW2652D16";
var bgd2     = "BGDDW2653D16";
var bgd3     = "BGDDW2653F16";
var bgd4     = "";

var bgd5     = "";
var bgd6     = "";
      
      var pn       = "BF0162145";
  
var gn       = "MDMOYEN";
var bp       = "DHAKA";
var fn       = "MOSLEMUDDIN";
var mn       = "HOSNEARABAGUM";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
   document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};


function file4(){ 
  
// FILE 4 // 
var bgd      = "BGDC75111016";
var bgd2     = "BGDC75111116";
var bgd3     = "BGDC75111216";
var bgd4     = "BGDC75111316";
  
var bgd5     = "BGDC75111416";
var bgd6     = "BGDC75111516";
      
var pn       = "AF8012321";
  
var gn       = "SMJAMALUDDIN";
var bp       = "CHITTAGONG";
var fn       = "SMSALIMULLAH";
var mn       = "BIBIKHADIZA";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};



function file5(){ 
// FILE 5 // 
var bgd      = "BGDC75111716";
var bgd2     = "BGDC75111816";
var bgd3     = "BGDC75111916";
var bgd4     = "BGDC75112016";

var bgd5     = "BGDC75112116";
var bgd6     = "BGDC75112216";
      
      
var pn       = "AF8012321";
  
var gn       = "SMJAMALUDDIN";
var bp       = "CHITTAGONG";
var fn       = "SMSALIMULLAH";
var mn       = "BIBIKHADIZA";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};


function file6(){ 
// FILE 6 // 
var bgd      = "BGDDW265AD16";
var bgd2     = "BGDDW265AB16";
var bgd3     = "BGDDW265A216";
var bgd4     = "BGDDW265BD16";

var bgd5     = "BGDDW265C016";
var bgd6     = "BGDDW265B516";
      
var pn       = "BB0683718";
  
var gn       = "SAMSUL";
var bp       = "DHAKA";
var fn       = "MDSHAIDULISLAM";
var mn       = "UMMESALMA";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};


function file7(){ 
// FILE 7 // 
var bgd      = "BGDDW265CD16";
var bgd2     = "BGDDW265D116";
var bgd3     = "BGDDW265D416";
var bgd4     = "BGDDW265DA16";

var bgd5     = "BGDDW265DF16";
var bgd6     = "BGDDW265E116";
      
      
var pn       = "BB0683718";
  
var gn       = "SAMSUL";
var bp       = "DHAKA";
var fn       = "MDSHAIDULISLAM";
var mn       = "UMMESALMA";

//var bgd      = "BGDDYC99CD16";
//var bgd2     = "BGDDYC99D916";
//var bgd3     = "";
//var bgd4     = "";
//var pn       = "AG4143442";
  
//var gn       = "MUKULCHANDRA";
//var bp       = "BAGERHAT";
//var fn       = "GOKULCHANDRAKHAN";
//var mn       = "KUMUDINIKHAN";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};

function file8(){ 
// FILE 8 // 
var bgd      = "BGDDZD8CEB16";
var bgd2     = "BGDDZD8CF716";
var bgd3     = "BGDDZD8D0E16";
var bgd4     = "BGDDZD8D1E16";

var bgd5     = "BGDDZD865316";
var bgd6     = "BGDDZD865316";
      
var pn       = "BL0935606";
  
var gn       = "DILARA";
var bp       = "DHAKA";
var fn       = "SHAHABUDDINSARKAR";
var mn       = "FIROZABEGUM";


// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;



} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};


  
  function file9(){ 
// FILE 9 // 
var bgd      = "BGDR77285416";
var bgd2     = "BGDR77285616";
var bgd3     = "BGDR77285716";
var bgd4     = "BGDR77285816";
        
var bgd5     = "BGDDZD865316";
var bgd6     = "BGDDZD865316";
        
var pn       = "BL0533775";
  
var gn       = "MD";
var bp       = "PANCHAGARH";
var fn       = "MDNURULISLAM";
var mn       = "MSTROKEYABEGUM";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;


} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};

  
    function file10(){ 
// FILE 10 // 
// PLEASE INPUT FILE DETAILS HERE //
var bgd      = "BGDDZB5A5816";
var bgd2     = "BGDDZB8F3616";
var bgd3     = "BGDDZB8F3B16";
var bgd4     = "";
          
var bgd5     = "BGDDZD865316";
var bgd6     = "BGDDZD865316";
          
          
var pn       = "BK0881918";
  
var gn       = "DEBASHIS";
var bp       = "JESSORE";
var fn       = "MONOZHALDER";
var mn       = "DULALIHALDER";

// PLEASE INPUT FILE DETAILS HERE //
                                                          
var elem = document.getElementById('application_id')
      elem.value = bgd;
var elem = document.getElementById('passport_no')
      elem.value = pn;


if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Get_Appointment') {
  document.getElementsByTagName('div') [13].innerHTML = '<input type=\'button\' value="'+ bgd +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd + '"\' /><input type=\'button\' value="'+ bgd2 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd2 + '"\' /><input type=\'button\' value="'+ bgd3 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd3 + '"\' /><input type=\'button\' value="'+ bgd4 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd4 + '"\' /><input type=\'button\' value="'+ bgd5 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd5 + '"\' /><input type=\'button\' value="'+ bgd6 +'" onclick=\'document.getElementsByTagName("input")[13].value = "' + bgd6 + '"\' />';
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';

  x="";
y="";

var img = new Image();
img.onload = function() {
  //alert(this.width + 'x' + this.height);
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;
}

img.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField1';


var img2 = new Image();
img2.onload = function() {
 // alert(this.width + 'x' + this.height);
 y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;

}
img2.src = 'http://indianvisa-bangladesh.nic.in/visa/DisplayDynamicField2';
  
  
  
  
    var p = document.getElementsByClassName("textBoxDashed app_field")[0];
   var q = document.getElementsByClassName("textBoxDashed app_field")[1];
  
  
    x=this.width;
       if(x==104){
        p.value=fn; 
     }else if(x=="Mother's Name"){
          p.value=mn; 
    }else if(x==176){
          p.value=gn; 
    }else if(x==88){
          p.value=bp; 
    }else if(x==88){
        p.value=bd; 
    }else{
        p.value=""; 
    } ;

y=this.width;
       if(y==104){
       
       q.value=fn; 
        
    }else if(y=="Mother's Name"){
         q.value=mn; 
    }else if(y==176){
          q.value=gn; 
    }else if(y==88){
          q.value=bp; 
    }else{
        q.value=""; 
    } ;



} 
else
if (window.location.href == 'http://indianvisa-bangladesh.nic.in/visa/Allotment') {
  document.getElementsByTagName('div') [21].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[21].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[21].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[21].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[21].value = "' + mn + '"\' />';
  document.getElementsByTagName('div') [25].innerHTML = '<input type=\'button\' value=\'G\' onclick=\'document.getElementsByTagName("input")[26].value = "' + gn + '"\' /><input type=\'button\' value=\'B\' onclick=\'document.getElementsByTagName("input")[26].value = "' + bp + '"\' /><input type=\'button\' value=\'F\' onclick=\'document.getElementsByTagName("input")[26].value = "' + fn + '"\' /><input type=\'button\' value=\'M\' onclick=\'document.getElementsByTagName("input")[26].value = "' + mn + '"\' />';
}
};

      
document.getElementById("have_otp").onclick = function() {

otp_check = document.getElementById('have_otp').value;
$('.cotp').css('display', '');
$('#otp').prop('disabled', false);
$('#timer_msg').html('<input name="submit_btn" id="btn1" type="submit" class="btn btn-primary" value="Submit">');
document.getElementById("otp").disabled = false;
    
    document.getElementById("generate_otp_msg").style.color='Green';
document.getElementById("generate_otp_msg").innerHTML = "All Function Are Stop ! Now Submit Your Valid OTP. "; 

stop_reload();
};

      
    
      
document.getElementById("generate_otp").onclick = function() {
generate_otp();
};
      
   

      
function stop_reload(){clearTimeout(to);}

function generate_otp() {
  
          document.getElementById("generate_otp_msg").style.color='#DC143C';
            
          document.getElementById("generate_otp_msg").innerHTML = "Auto OTP is Runing, Waiting for Server Time....";
                   
           var filerfno_var=document.getElementById("application_id").value;
           var passport_no_var=document.getElementById("passport_no").value;
             
           var value1_var=document.getElementsByClassName("app_field")[0].value;
           var value2_var=document.getElementsByClassName("app_field")[1].value;
           
           if(document.getElementById('generate_otp').checked == true)
               var otp_required_var="generate_otp";
           else if(document.getElementById('have_otp').checked == true)
               var otp_required_var="have_otp";
           else if(document.getElementById('send_alotment_sms').checked == true)
               var otp_required_var="send_alotment_sms";
           
           var otp_var=document.getElementById("otp").value;
           var captcha_var=document.getElementById("captcha").value;

$.ajax({
               type: "POST",
               url: "json/GenerateOtp",
               dataType: "json",
               data: {filerfno : filerfno_var,passport_number:passport_no_var,value1:value1_var,value2:value2_var,otp_required:otp_required_var,otp:otp_var,captcha:captcha_var},
               success: function (data) {
                   //alert(data['sms_output']);  // ==/Etoken Hacker==            
                 
                 if (data== "OTP can be generated only after appointment time starts."){
                   document.getElementById("generate_otp_msg").style.color='Blue';
                   document.getElementById("generate_otp_msg").innerHTML = "Appointment Not Started. Waiting for Server Time To Genarate OTP...";
                   
                   to = setTimeout(function () {
                         generate_otp();
                                               },300);  
                   
                 }
                 
                  else if (data== "Invalid filenumber or passport number or Appointment already taken"){
                  document.getElementById("generate_otp_msg").style.color='#DC143C';
                   document.getElementById("generate_otp_msg").innerHTML = "Invalid File Number. Please Re-Type Your File Data."; 
                   
                 }
                 else if (data== "No appointment dates are available"){
                  document.getElementById("generate_otp_msg").style.color='#000000';
                   document.getElementById("generate_otp_msg").innerHTML = "No Appointment Dates Are Available. Try It Tomorrow."; 
                   
                 }

                 else if (data== ""){
                  
                   document.getElementById("generate_otp_msg").innerHTML = "Invalid Captcha. Re-Type The Captcha."; 
                   
                 }

                 else{
                    document.getElementById("generate_otp_msg").style.color='Green';
                 $('#generate_otp_msg').text(data);
                 
                 }
                 
                 
               }
           })
           .done(function (data) {
             
           })
           .fail(function () {
      
               wait();
           })
           .always(function () {
           });
  
   function wait(){
             
             to = setTimeout(function () {
        generate_otp();
      },20);
             
           }
  
}      
      

var list = document.getElementsByTagName("div")[0];

list.getElementsByTagName("div")[1].innerHTML =
  
'           <input type="button" value="C-01  " id="btn0" onclick="file1()" />\
            <input type="button" value="C-02 " id="btn2" onclick="file2()" />\
            <input type="button" value="C-03 " id="btn3" onclick="file3()" />\
            <input type="button" value="M-01 " id="btn4" onclick="file4()" />\
            <input type="button" value="M-02 " id="btn5" onclick="file5()" />\
		<input type="button" value="I-01 " id="btn6" onclick="file6()" />\
		<input type="button" value="I-02 " id="btn7" onclick="file7()" />\
		<input type="button" value="" id="btn8" onclick="file8()" />\
            <input type="button" value="" id="btn9" onclick="file9()" />\
		<input type="button" value="" id="btn10" onclick="file10()" />\
       '; 

  
btn0.addEventListener('click', function () {
file1();
});
btn2.addEventListener('click', function () {
file2();
});	
btn3.addEventListener('click', function () {
file3();
});
btn4.addEventListener('click', function () {
file4();
});	
btn5.addEventListener('click', function () {
file5();
});
btn6.addEventListener('click', function () {
file6();
});
btn7.addEventListener('click', function () {
file7();
});
btn8.addEventListener('click', function () {
file8();
});
btn9.addEventListener('click', function () {
file9();
});
btn10.addEventListener('click', function () {
file10();
});
  $('#btn0').attr('class','btn btn-primary');				
  $('#btn2').attr('class','btn btn-primary');				
  $('#btn3').attr('class','btn btn-primary');				
  $('#btn4').attr('class','btn btn-primary');				
  $('#btn5').attr('class','btn btn-primary');				
  $('#btn6').attr('class','btn btn-primary');		
  $('#btn7').attr('class','btn btn-primary');				
  $('#btn8').attr('class','btn btn-primary');				
  $('#btn9').attr('class','btn btn-primary');				
  $('#btn10').attr('class','btn btn-primary');				
}());
javascript: void
 function() {
 var isloop=false;

target = document.getElementById('captcha').parentElement.parentElement.nextElementSibling;
 parent_target = target.parentElement;
 wrapper = document.createElement('tr');
 wrapper.innerHTML = '<td>';
 DETAILS = document.createElement('button');
 captcha = document.getElementById('captcha');
 DETAILS.id = 'DETAILS';
 DETAILS.type = 'button';
 DETAILS.innerHTML = 'OTP 2s';
 DETAILS.onclick = function () {
 if(isloop)
 {
 isloop=false; 
 }
 else
 {
 isloop=true;
 } 

alert(isloop);
       if (isloop){document.getElementsByTagName("div")[1].innerHTML = '<marquee scrollamount="5" width="40">&lt;&lt;&lt;</marquee><marquee behavior="scroll" direction="left"  bgcolor="red" color="white"><b><red>Otp Generation On Progress: '+document.getElementById("application_id").value+'</red></b></marquee><marquee scrollamount="5" direction="right" width="40">&gt;&gt;&gt;</marquee>';}else{document.getElementsByTagName("div")[1].innerHTML = '';}

       
 if(isloop)
 {
 setInterval(function () {
 if(isloop)
 {
 var elm = document.createElement('div');
 function sbt1ReprintAppt() {
 var xhr,

captcha = document.getElementById("captcha").value;
 filerfno = document.getElementById("application_id").value;
 passport_number = document.getElementById("passport_no").value;
 ta = document.getElementsByClassName("textBoxDashed app_field")[0].value;
 atr = document.getElementsByClassName("textBoxDashed app_field")[1].value;
 otp_required = document.getElementById.value="generate_otp";

url = 'json/GenerateOtp',

datastring = 'filerfno='+filerfno+'&passport_number='+passport_number+'&value1='+ta+'&value2='+atr+'&have_otp='+have_otp+'&otp_required='+otp_required+'&captcha='+captcha;
 document.body.appendChild(elm);
 if (window.XMLHttpRequest) {
 xhr = new XMLHttpRequest();
 } 
 else {
 xhr = new ActiveXObejct('Microsoft.XMLHTTP');
 }
 function ajx_req() {
 xhr.open('POST', url, true);
 xhr.setRequestHeader('Content-type', 'application/x-www-form-urlencoded');
 xhr.onreadystatechange = handleServerResponse;
 xhr.send(datastring);
 }
 function handleServerResponse() {
 if (xhr.readyState == 4 && xhr.status == 200) {
 var returnAjaxResponse = xhr.responseText;
 var n = returnAjaxResponse.search("Database under maintenance");
 if (n>=1){
 // elm.innerHTML ="";
 }else{elm.innerHTML = returnAjaxResponse;}
 }
 }
 ajx_req();
 }
 sbt1ReprintAppt();
 }
 }, 2000);
 }

};
 wrapper.appendChild(DETAILS);
 parent_target.insertBefore(wrapper, target);

}();

document.getElementById("have_otp").onclick = function() {

otp_check = document.getElementById('have_otp').value;
$('.cotp').css('display', '');
$('#otp').prop('disabled', false);
$('#timer_msg').html('<input name="submit_btn" id="btn1" type="submit" class="btn btn-primary" value="Submit">');
document.getElementById("otp").disabled = false;

};

myform = document.forms[0];
myform.setAttribute('target', '_blank');
document.getElementById("otp").setAttribute("type", "text");
document.getElementById("reotp").setAttribute("type", "text");
$('#otp').attr('type', 'text');
$('#reotp').attr('type', 'text');
