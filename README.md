public class MahindraScorpioSpecs {
    public static void main(String[] args) {
       
        String carModel = "Mahindra Scorpio S11";
	String engineType = "mHAWK 4 Cylinder";
	int displacement = 2184; // in cc
        int maxPowerBhp = 130;   // bhp
        int maxPowerRpm = 3750;  // rpm
        int maxTorqueNm = 300;   // Nm
        int torqueMinRpm = 1600;
        int torqueMaxRpm = 2800;
        int numberOfCylinders = 4;
        int valvesPerCylinder = 4;

        
        String fuelSupplySystem = "CRDi";
	boolean TurboCharger = true;
        String transmissionType = "Manual";
        String gearbox = "6-Speed";
        String driveType = "RWD";

        

       

        System.out.println("Mahindra Scorpio specifications");
        System.out.println("===================================");
        System.out.println("Engine & Transmission");
        System.out.println("-----------------------------------");
        System.out.println("Engine Type           : " + engineType);
        System.out.println("Displacement          : " + displacement + " cc");
        System.out.println("Max Power             : " + maxPowerBhp + " bhp @" + maxPowerRpm + " rpm");
        System.out.println("Max Torque            : " + maxTorqueNm + " Nm @" + torqueMinRpm + "-" + torqueMaxRpm + " rpm");
        System.out.println("No. of Cylinders      : " + numberOfCylinders);
        System.out.println("Valves Per Cylinder   : " + valvesPerCylinder);
        System.out.println("Fuel Supply System    : " + fuelSupplySystem);
        System.out.println("Turbo Charger         : " + (TurboCharger ? "Yes" : "No"));
        System.out.println("Transmission Type     : " + transmissionType);
        System.out.println("Gearbox               : " + gearbox);
        System.out.println("Drive Type            : " + driveType);
    }
}
