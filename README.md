Public class fitness{
private static AndriodDriverdriver;
public status void main(String []args) throws exception{
File userDir =new File ( Sytem.getProperty("user.dir"));
File appDir =new file(userDir,"/Apps/Fitness/");
File application = new File(appDir,"in.Fitnes.andriod.apk");
Desiredcapabikitiesscapt= new Desiredcapabilities();
capt.setCapability("device name","Redmi Note 6");
capt.setCapability("platformName","Andriod");
capt.setCapability("app",app.getAbsolutePath()):
capt.setCapability("appPackagae","in.Fitness.andriod");
capt.setCapability("appActivity","com.Fitness.Homeactivity");

driver=new AndriodDriver(new URL("https://127.0.0.1:4723/wd/hub").capt);
driver.managar().timeouts().implicityWait(20,TimeUnit.SECONDS);
driver.close();
}

}
