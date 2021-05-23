import java.util.Properties;
import java.io.FileReader;
import java.io.IOException;

public class Jala {
	public static void main(String[] args) throws IOException {
		FileReader fr =new FileReader("file.properties");  
	      
	    Properties p = new Properties();  
	    p.load(fr);  
	      
	    System.out.println(p.getProperty("name"));  
	    System.out.println(p.getProperty("age"));  
	}
}
