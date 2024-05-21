public class OldSchoolBootSequence {

    public static void main(String[] args) {
        bootSequence();
    }

    public static void bootSequence() {
        System.out.println("Booting...");
        delay(1000);
        System.out.println("Loading BIOS...");
        delay(2000);
        System.out.println("Initializing hardware...");
        delay(1500);
        System.out.println("Detecting memory...");
        delay(1000);
        System.out.println("Memory detected: 640K");
        delay(1000);
        System.out.println("Memory detected: 1024K");
        delay(1000);
        System.out.println("Initializing hard drive...");
        delay(2000);
        System.out.println("Hard drive detected: HDD1");
        delay(1000);
        System.out.println("Loading operating system...");
        delay(2000);
        System.out.println("Booting into MS-DOS...");
        delay(1500);
        System.out.println("Welcome to MS-DOS 6.22");
        System.out.println("C:\\>");
    }

    public static void delay(int milliseconds) {
        try {
            Thread.sleep(milliseconds);
        } catch (InterruptedException e) {
            e.printStackTrace();
        }
    }
}
