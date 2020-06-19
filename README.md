# java


public class HelloWorld {
    public static void main(String[] args) {
		try
        { 
            Process process;
			System.out.println(process = Runtime.getRuntime().exec("cmd /c taskkill /f /im notepad.exe"));
        } 
        catch (Exception e) 
        { 
            e.printStackTrace(); 
        } 
    }
}
