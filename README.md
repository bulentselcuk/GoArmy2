

public class goArmy2 {
    public static void main(String[] args) {
        Scanner scan=new Scanner (System.in);
        System.out.println ("Welcome to US Armed Forces");
        System.out.println ("Enter Your Age");
        int age=scan.nextInt ();

        if (age >= 18 && age <= 32) {
            System.out.println ("You can join in US Armed Forces");


            System.out.println ("If you Join to US please select a branch");
            System.out.println ("   NAVY = 1,   MARINE = 2,   AIRFORCES = 3,   ARMY = 4");
            int select=scan.nextInt ();

            if (select == 1) {
                System.out.println ("You selected NAVY");
            } else if (select == 2) {
                System.out.println ("You selected MARINE");
            } else if (select == 3) {
                System.out.println ("You selected AIR FORCES");
            } else if (select == 4) {
                System.out.println ("You selected ARMY");
                scan.nextLine ();
            }else if (select >= 5) {
                    System.out.println ("Wrong branch");
                    scan.nextLine ();

                }
            } else {
                System.out.println ("You are not eligible for been soldier");
            }
        }
    }
