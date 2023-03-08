# max-min<br>
Java Eclipse<br>
## max for문<br>

package 자바;

public class 순서도 {
	
	static int maxpara(int a, int b, int c) {
		int max = a;
		if(b > max)
			max = b;
		if(c > max)
			max = c;
		
			return max;
	}	
	static int minpara(int a, int b, int c) {
		int min = a;
		if(b < min)
			min = b;
		if(c < min)
			min = c;
				
			return min;
	}
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.out.println("maxpara(10,9,8) :"+maxpara(10,9,8));
		System.out.println("maxpara(5,19,2) :"+maxpara(5,19,2));
		System.out.println("maxpara(10,9,8) :"+minpara(10,4,1));
		System.out.println("maxpara(5,19,2) :"+minpara(5,20,3));
	}

}

## 실행된 이미지<br>
![image](https://user-images.githubusercontent.com/126844692/223636557-7facb484-8396-4d1e-9da8-ed59d66969bc.png)

## min for문<br>

package 자바;

import java.util.Scanner;

public class 순서도2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner stdin = new Scanner(System.in);
		System.out.println("한 개의 정수를 입력하세요.");
		int a = stdin.nextInt();
		System.out.println("한 개의 정수를 입력하세요.");
		int b = stdin.nextInt();
		System.out.println("한 개의 정수를 입력하세요.");
		int c = stdin.nextInt();
		
		int max = a;
		if(b > max) max = b;
		if(c > max) max = c;
		
		System.out.println("셋 중 가장 큰 값은 "+max+"입니다.");
		
		System.out.println();
		
		System.out.println("한 개의 정수를 입력하세요.");
		int d = stdin.nextInt();
		System.out.println("한 개의 정수를 입력하세요.");
		int e = stdin.nextInt();
		System.out.println("한 개의 정수를 입력하세요.");
		int f = stdin.nextInt();
		
		int min = d;
		if(b < min) min = e;
		if(c < min) min = f;
		
		System.out.println("셋 중 가장 작은 값은 "+min+"입니다.");
	}

}

## 실행된 이미지<br>
![image](https://user-images.githubusercontent.com/126844692/223636799-6dbb90a8-0a1d-4fa4-aa0b-02658e228636.png)
