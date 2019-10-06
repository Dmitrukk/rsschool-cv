# CV
1. My name is **Darya Dmitruk**

2. ### Contact info:
Mobile phone: +375 29 821 63 57 
E-mail:  dashanya-00@mail.ru

Besides You can contact me on different messages and social networks.
For example, telegram and viber *(+375298216357)* as well as Facebook *(Dasha Dmitruk)* and VKontakte *(Дмитрук Даша)*

3. ### Self-presentation:
As I'm a junior developer I can't boast the great job experience, but now I'm ready to improve my abilities and deepen my knowledge.

4. ### Professional skills:
* Programming in Java,  C ++; 
* Basic knowledge of markup languages for web-sites: HTML, CSS; 
* Basic knowledge of SQL;
* Basic knowledge of computer networks (TCP/IP, UDP, HTTP)
* Knowledge of MS Office, Adobe Photoshop
5. #### Code examples:
* 
        <div class="fon1">
            <img src="resources/2.png">

        <div class="header1">
        <div class="header_logo"></div>
        <nav>
        <a href="">Home</a>
        <a href="">Services</a>
        <a href="">About</a>
        <a href="">Work</a>
        <a href="">Contacts</a>
        <a href="" id="menu"class="icon">&#9776;</a>
        </nav>
* import static java.lang.Thread.sleep;
import java.util.Scanner;


public class Main { 
static public double t1,t2,t3,tt5=60,tt4; 
static public int kol; 
static public double TIME; 
static public double max; 
public static void main(String[] args) { 

System.out.print("Введите количество покупателей\n"); 
Scanner s1 = new Scanner(System.in); 
kol = s1.nextInt(); 
System.out.print("Введите время обслуживания одного покупателя(сек)\n"); 
System.out.print("КАССА 1: "); 
Scanner s2 = new Scanner(System.in); 
t1 = s2.nextDouble(); 
System.out.print("КАССА 2: "); 
Scanner s3 = new Scanner(System.in); 
t2 = s3.nextDouble(); 
System.out.print("КАССА 3: "); 
Scanner s4 = new Scanner(System.in); 
t3 = s4.nextDouble(); 

//if(kol!=0){ 
//for(int i=0;i<45;i++){ 

CashBox1 thread1 = new CashBox1(); 
thread1.start(); 
CashBox2 thread2 = new CashBox2(); 
thread2.start(); 
CashBox3 thread3 = new CashBox3(); 
thread3.start(); 


}
}




import java.util.logging.*;

class CashBox1 extends Thread { 
static public double tt1; 
static public int client1; 
@Override 

public void run() { 
while(Main.kol>0){ 
if(tt1!=45.0 && tt1!=100.0 && tt1!=155.0 && tt1!=210 && tt1!=265 && tt1!=320){ 
Main.kol--; 
tt1 += Main.t1; 
client1++; 
System.out.print("\nПОТОК 1 ОБСЛУЖИЛ "+client1+" ОСТАЛОСЬ "+Main.kol); 
try {
        sleep((long)(Main.t1*100));
    } catch (InterruptedException ex) {
        Logger.getLogger(CashBox2.class.getName()).log(Level.SEVERE, null, ex);
    }
}
else {
    System.out.print("\n1ЫЙ УШЁЛ НА ПЕРЕРЫВ");
    tt1+=10.0;
    try{ 
    sleep((long)(1000)); 
}catch(InterruptedException e){} 
} 
    
}


System.out.println("\nКасса 1: "+tt1+" мин, "+client1+" чел");
}
} 




import java.util.logging.*;

class CashBox2 extends Thread { 
static public double tt2; 
static public int client2;
@Override 

public void run() { 
while(Main.kol>0){ 
if(tt2!=45.0 && tt2!=100.0 && tt2!=155.0 && tt2!=210 && tt2!=265 && tt2!=320){ 
Main.kol--; 
tt2 += Main.t2; 
client2++; 
System.out.print("\nПОТОК 2 ОБСЛУЖИЛ "+client2+" ОСТАЛОСЬ "+Main.kol); 
try {
        sleep((long)(Main.t2*100));
    } catch (InterruptedException ex) {
        Logger.getLogger(CashBox2.class.getName()).log(Level.SEVERE, null, ex);
    }
}
else {
    System.out.print("\n2ОЙ УШЁЛ НА ПЕРЕРЫВ");
    tt2+=10.0;
    try{ 
    sleep((long)(1000)); 
}catch(InterruptedException e){} 
} 
    
}


System.out.println("\nКасса 2: "+tt2+" мин, "+client2+" чел");
}
} 





import java.util.logging.*;

class CashBox3 extends Thread { 
static public double tt3=0; 
static public int client3=0; 
@Override 

public void run() { 
while(Main.kol>0){ 
if(tt3!=45.0 && tt3!=100.0 && tt3!=155.0 && tt3!=210 && tt3!=265 && tt3!=320){ 
Main.kol--; 
tt3 += Main.t3; 
client3++; 
System.out.print("\nПОТОК 3 ОБСЛУЖИЛ "+client3+" ОСТАЛОСЬ "+Main.kol); 
try {
        sleep((long)(Main.t3*100));
    } catch (InterruptedException ex) {
        Logger.getLogger(CashBox2.class.getName()).log(Level.SEVERE, null, ex);
    }
}
else {
    System.out.print("\n3ИЙ УШЁЛ НА ПЕРЕРЫВ");
    tt3+=10.0;
    try{ 
    sleep((long)(1000)); 
}catch(InterruptedException e){} 
} 
    
}


System.out.println("\nКасса 3: "+tt3+" мин, "+client3+" чел");
}
} 

6. ##### Experience:
-   creating graphic content as well as writing posts in English as a part of the internship
-	poster making for events in the University
-	translating documents from Russian into Belarussian and English
-	representing projects and organizing different events as a part of university’s life

7. #### Education: incomplete higher education
- 2017-2021	- Belarussian State University of Informatics and Radioelectronics,economist-programmer

**Courses, internships:**
- 2019 - SMM internship (international IT conference EMERGE)
- 2018 - Online Marketing Course
- 2015-2018 - English	

8. **English** - B2
- I've learning English since my first form at school (2006 year). 
- English courses in 2015-2017
- Enslish-speaking camp in Switzerland in 2016
- Self-education in English (2018-2019)