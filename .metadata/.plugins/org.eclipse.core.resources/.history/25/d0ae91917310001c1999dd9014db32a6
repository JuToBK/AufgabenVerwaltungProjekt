package aufgabenVerwaltungPackage;
import java.net.*;

public class DBConnection {
	
    String username="ankur",password="ankur",fname="Shubhendu",ip="12345",lname="Goswami";
    String up= "username=" + username + "&password=" + password + "&fname=" + fname + "&lname=" + lname + "&ip="+ ip;
    URL url=new URL("http://127.0.0.1:80/alias1/index.php?"+up);
    URLConnection urlc=url.openConnection();
    urlc.connect();

}
