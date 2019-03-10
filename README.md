# study
Study in college
package 名片制作;

import java.util.Scanner;

public class 名片制作 {

	public static void main(String[] args) {
		// TODO 自动生成的方法存根
		Scanner input=new Scanner(System.in);
		System.out.println("please input the information what about yourself");
		System.out.print("姓名：");
		String name=input.next();
		System.out.print("QQ：");
		String QQ=input.next();
		System.out.print("手机号：");
		String number=input.next();
		System.out.print("公司地址：");
		String place=input.next();
		System.out.println("==================");
		System.out.println("姓名："+name);
		System.out.println("QQ："+QQ);
		System.out.println("手机号："+number);
		System.out.println("公司地址"+place);
		System.out.println("==================");
	}

}
