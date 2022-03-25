package BT;

import java.util.Scanner;
	public class BT1 {
	  public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    System.out.print("Nhập vào chuỗi cần kiểm tra: ");
	    String input = sc.nextLine();
	    input = input.replaceAll("\\s", "");
	    System.out.println("Chuỗi sau khi xóa khoảng trắng: " + input);
	}
}
