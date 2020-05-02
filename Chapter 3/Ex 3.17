 import java.util.Scanner;

public class CodingExam {
	public static void main (String[] args) {
		System.out.print("scissor (0), rock (1), paper (2): ");
		Scanner userInput = new Scanner(System.in);
		int user = userInput.nextInt();
		int computer = (int)(Math.random() * (3));
		
		if (user == 0) {
			if (computer == 0) {
				System.out.println("The computer is scissors. You are scissors too. It is a draw");
			} else if (computer == 1) {
				System.out.println("The computer is rock. You are scissors. Computer won");
			} else if (computer == 2) {
				System.out.println("The computer is paper. You are scissors. You won");
			}
		} else if (user == 1) {
			if (computer == 0) {
				System.out.println("The computer is scissors. You are rock. You won");
			} else if (computer == 1) {
				System.out.println("The computer is rock. You are rock too. It is a draw");
			} else if (computer == 2) {
				System.out.println("The computer is paper. You are rock. Computer won");
			}
		} else {
			if (computer == 0) {
				System.out.println("The computer is scissors. You are paper. Computer won");
			} else if (computer == 1) {
				System.out.println("The computer is rock. You are paper. You won");
			} else if (computer == 2) {
				System.out.println("The computer is paper. You are paper too. It is a draw");
			}
		}
	}
}
