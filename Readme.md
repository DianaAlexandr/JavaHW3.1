# Main.java

public class Main {
    public static void main(String[] args) {
        
        BonusMilesService service = new BonusMilesService();
        int price = 10_000;
        int miles = service.calculate(price);
        System.out.println(miles);
    }
}

# BonusMilesService.java

public class BonusMilesService {
    
    public int calculate(int cost) {
        int miles = cost / 20;
        return miles;
    }
}
