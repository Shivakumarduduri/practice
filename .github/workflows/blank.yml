package tests;

import base.BaseTest;
import org.testng.Assert;
import org.testng.annotations.Test;
import pages.HomePage;

public class HomepageTest extends BaseTest {

    @Test
    public void verifyHomePageLoads() {
        HomePage homePage = new HomePage(driver);
        
        // 16. Open the website and verify that the home page loads[cite: 1]
        homePage.open();
        Assert.assertTrue(homePage.isHomePageLoaded(), "Home page failed to load!");
    }
}
