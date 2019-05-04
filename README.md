# SCROLL
=========

  SCROLL  is  a  oakjava7   framework  invented in  OAKJAVA7  by wilmix jemin  for Mobile/ Remotewebapplication at  year  2018.


Period  of   project  :  (2014- 2017)

 


SYNTAX:
=======

<SCROLL>




public class classname {

public  static void  main(String args[])
{


<!  Logic  !>


 
}

}


</SCROLL>


ADVANTAGES:
==========

A)  USED  only  with  Latest  JAVA  version  (OAK JAVA) JAVA7
 
 B) It is used to publish java web application like struts,spring ,hibernate, and JSF

in mobiles.

C) IT has attractive syntax.

D) Developer need to concenterate only on core java so it is learnable. in other framework developer had to learn more syntax.





Program-1:
===========

<SCROLL>




public class index {

public  static void  main(String args[])
{


HTML.displayhtml("Register.html");


 
}

}


</SCROLL>



Program-2:
===========



<SCROLL>

import  java.util.*;

import jxl.read.biff.BiffException;
import java.io.*;
import java.util.regex.Pattern;
import java.util.regex.Matcher;
public  class  Jquerytest

{
public  static  void  main(String args[]) throws  BiffException,IOException,Exception

{


 

 ArrayList<String> arm1= new  ArrayList<String>();

arm1.add("name");
arm1.add("uname");arm1.add("password");
arm1.add("state");
arm1.add("country");
arm1.add("spwd");
arm1.add("stext");
arm1.add("familydet");
arm1.add("Indent");
arm1.add("CIndent");

arm1.add("!");





ArrayList <String>  armg=SPLITREQUEST.RESULT(arm1,"Jquerytest.dsn",10,1);

// extract  the  contents  of  dsn  file  and print  it  in webpage

//dsn  file contains  parameters  data ,  where as   10 indicates  no  of  fields  present  in register  form  and  1 indicates  the adjustment counter

// for  selecting  10 fields 



System.out.println("<table style='width:100%' bgcolor=gold>");
  
System.out.println("<tr>");
  
System.out.println("  <th>Name</th>");
  
System.out.println("  <th>Username</th>"); 
  
System.out.println("  <th>Password</th>");
  
System.out.println("  <th>State</th>");
  
System.out.println("  <th>Country</th>");
  
System.out.println("  <th>Confirm Password</th>");

System.out.println("  <th>Secret Password</th>");

System.out.println("  <th> FamilyDetails </th>");
System.out.println("  <th>Percentage of Marks Scored</th>");
System.out.println("  <th>Subject</th>");
   
System.out.println(" </tr>");
   
System.out.println(" <tr>");


Iterator  it = armg.iterator();

while  (it.hasNext())
{

Object el=it.next();
   System.out.println("<td>"+el+"</td>");
   
 }

  
System.out.println(" </tr>");
 
  
System.out.println("</table>");



}
}


</SCROLL>
