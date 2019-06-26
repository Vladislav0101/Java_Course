public class Learn {
    public static void main(String[] args) {
        int y = 0;
        int x = 4;
        boolean high = ((y >= 0 && y<= 4)&&(x>= -2 && x<=2));
        boolean low = ((y <= 0 && y>= -3)&&(x >= -4 && x<=4));
        boolean answer = ((high)||(low));
        System.out.println(answer);
    }
}
