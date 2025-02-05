package base;

import java.time.Duration;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class TestBase {
	protected WebDriver driver;
	
	public void setUp() {
	driver = new ChromeDriver();
    // Open the OrangeHRM login page
    driver.get("https://opensource-demo.orangehrmlive.com/web/index.php/auth/login");
    // Maximize the browser window
    driver.manage().window().maximize();
    // Set implicit wait for element loading
    driver.manage().timeouts().implicitlyWait(Duration.ofSeconds(50));
}
	}