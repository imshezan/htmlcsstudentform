<html xmlns:style="http://www.w3.org/1999/xhtml">
    <head>
    <title>HOME</title>
        <style type="text/css">

        h1{
    text-align:center;
    background:#0B3A67;
    color:white;
    font-family:"Times New Roman";
    }
    li{
    display:inline-block;

    }
    ul{
    list-style-type:none;
    }
    a{
    margin:5px 20px;
    text-decoration:none;
    color:#0B3A67;
    }
    ul{
    text-align:center;
    background:white;
    padding:7px;
    color: rgba(0,0,0,0.6);
    text-shadow: 2px 8px 6px rgba(0,0,0,0.2),
                     0px -5px 35px rgba(255,255,255,0.3);
    }
    td{
    color: white;
    }

html,body{
	height:100%;
	margin:0
}

#viewport{
	min-height:100%;
	position:relative;
	width:100%
}

.content{
	padding-bottom:35px
}

footer{
	bottom:0;
	font-size:10pt;
	height:35px;
	width:100%
}

#gog{
	padding:3px 8px 0
}

.gac_m td{
	line-height:17px
}

body,td,a,p,.h{
	font-family:arial,sans-serif
}

.h{
	color:#1a0dab;
	font-size:20px
}

.q{
	color:#00c
}

.ts td{
	padding:0
}

.ts{
	border-collapse:collapse
}

em{
	font-weight:bold;
	font-style:normal
}

.ds{
	display:inline-block;
}

span.ds{
	margin: 3px 0 4px 4px;
}

.ctr-p{
	margin:0 auto;
	min-width:980px
}

a.gb1,a.gb2,a.gb3,a.gb4{
	color:#1a0dab !important
}

body{
	background:#0B3A67;
	color:#222
}

a{
	color:#1a0dab;
	text-decoration:none
}

a:hover,a:active{
	text-decoration:underline
}

.fl a{
	color:#1a0dab
}

a:visited{
	color:#609
}

a.gb1,a.gb4{
	text-decoration:underline
}

a.gb3:hover{
	text-decoration:none
}

#ghead a.gb2:hover{
	color:#fff !important
}

.sblc{
	padding-top:5px
}

.sblc a{
	display:block;
	margin: 2px 0 2px 13px;
	font-size:11px
}

.lsbb{
	height:30px;
	display:block
}

.ftl,#footer a{
	color:#666;
	margin:2px 10px 0
}

#footer a:active{
	color:#dd4b39
}

.lsb{
	border:none;
	color:#000;
	cursor:pointer;
	height:30px;
	margin:0;
	outline:0;
	vertical-align:top
}

.lst:focus{
	outline:none
}

body,html{
	font-size:small
}

h1,ol,ul,li{
	margin:0;
	padding:0
}

.nojsv{
	visibility:hidden
}

.hp #logocont.nojsv{
	display:none
}

#body,#footer{
	display:block
}

.igehp{
	display:none
}

#flci{
	float:left;
	margin-left:0;
	text-align:left;
	width:0
}

#fll{
	float:right;
	text-align:right;
	width:100%
}

#ftby{
	padding-left:0
}

#ftby>div,#fll>div,#footer a{
	display:inline-block
}

@media only screen and (min-width:1222px){
	#ftby{
		margin:0 44px
	}

}

.logo-subtext{
	color:#4285f4;
	font:16px/16px roboto-regular, arial, sans-serif;
	left:215px;
	position:relative;
	top:76px;
	white-space:nowrap
}


    </style>
    
    
    
    </head>
 <body>
 <div>
    <img src = "logo.jpg">
        <h1 style="text-align: center">Student</h1>
            <h4 style="text-align: center" > Developed by: Shezan Mahmud. </h4>
            <ul >
            <li><a href="main.html" title="Home Page">REGISTERATION</a></li>
           </ul>
    <form align = "center">
        <table align = "center">
            <tr>
              <td>  Select image to upload:</td>
                <td> <input type="file" name="fileToUpload" id="fileToUpload"></td>
                <td> <input type="submit" value="Upload Image" name="submit"></td>
            </tr>
        </table>
    </form>

    <form method="POST">
     <table align="center">
           <tr>
                <td>Fast Name:</td>
                <td><input type="text" name="Fast Name"></td>
                <td>Last name:</td>
                <td><input type="text" name="Last Name"></td>
           </tr>

           <td>Program:</td>
           <td>
               <select name="program" value="Select Program">
                    <option selected="selected" value="default">-select program-</option>
                    <option value="sandwich">Bsc</option>
                    <option value="BSC">BBA</option>
                    <option value="PGD">BA</option>
                    <option value="Masters">Masters</option>
                    <option value="Phd">Phd</option>
               </select>
           </td>

           <tr>
            <td>Department:</td>
            <td>
                <select name="department" value="Select department">
                    <option selected="selected" value="default">-select Department-</option>
                    <option value="Computer Science">Computer Science</option>
                    <option value="Computer Science & Engineering ">Computer Science & Engineering</option>
                    <option value="Electrical engineering">Electrical engineering</option>
                </select>
             </td>
            </tr>

       <td>Faculty:</td>
       <td>
           <select name="Facuty">
                 <option selected = "selected" value="deafult">-Select Faculty-</option>
                 <option value="Engineering">Engineering</option>
                 <option value="Science">Science</option>
                 <option value="Managment">Managment</option>
                 <option value="Art">Art</option>
                 <option value="Medicine">Medicine</option>
           </select>
       </td>

   <tr>
        <td>City:</td>
        <td>
            <select name="State">
                <option selected="selected">-Select Divition-</option>
                <option value="Dhaka">Dhaka</option>
                <option value="Chittagong">Chittogong</option>
                <option value="Barisal">Barisal</option>
                <option value="Sylet">Sylet</option>
                <option value="Rajshahi">Rajshahi</option>
                <option value="Khulna">Khulna</option>
                <option value="Rangpur">Rangpur</option>
                <option value="Moynamoti">Moynamoti</option>
            </select>

     <td>Nationality:</td>
      <td>
          <select name= "Country">
            <option selected="selected">-Select Country-</option>
            <option value="Bangladesh">Bangladesh</option>
            <option value="India">India<ption>
            <option value="Srilanka">Srilanka</option>
            <option value="Pakistan">Pakistan</option>
          </select>
          </td>
        </tr>
     <tr>
        <td>Date of Birth (YYYY-MM-DD)</td>
        <td><input type="text" name="dob"></td>
        <td>Place Of Birth:</td>
        <td><input type="text" name="pob"></td>
     </tr>

     <tr>
        <td>Gender:</td>
        <td>
            <select name="gender">
                <option selected="selected">Select Sex</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
            </select>


         <td>Email:</td>
        <td><input type="text" name="email"></td>
     </tr>

     <tr>
        <td>Marrital Status:</td>
        <td>
            <select name="Maritalstatus">
                <option selected="selected">-Select Marital Status-</option>
                <option value="single">Single</option>
                <option value="Married">Married</option>
            </select>
        </td>


      <td>Religion:</td>

      <td>
         <select name="Religion">
             <option selected="selected" value="default">-Select Religion-</option>
             <option value="muslim">Muslim</option>
             <option value="Hindu">Hindu</option>
         </select>
      </td>
     </tr>

      <tr style: align="center">
          <td><input type="submit" name="submit" value="Submit"></td>
          <td><input type="Reset" name="Reset"value="Clear"></td>
      </tr>
    </table>
   </form>
  </div>
 </body>
</html>
