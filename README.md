# Johnny-Rivers-
first
public class Fiba {
	public static void main(String [] args){
		
		//Fibonacci numbers Each new term in the Fibonacci sequence is generated by adding the previous two terms. 
		//By starting with 1 and 2, the first 10 teeven-valued terms.rms will be:1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...
		//By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the 
		//
		//числа Фибоначчи Каждый новый член последовательности Фибоначчи образуется путем добавления двух предыдущих условий
		//Начиная с 1 и 2 , первые 10 чисел будут равны:1 , 2 , 3 , 5 , 8 , 13 , 21 , 34 , 55 , 89 , ...
		//Рассматривая условия в последовательности Фибоначчи , значения не превышают четыре миллиона , найти сумму
		 long a = 1;
	     long b = 2;
	     long c = 0;
	     long f = 0;
	     
	     for(long i = 0; c <4000000; i++){
	         c = a + b;
	         a = b;
	         b = c;
	         	if (c%2==0){  
	         		f += c;
	         	}
	     	} 
	    System.out.println("Ответ = " + f );//сумма чисел от 1 до 4млн в числах Фибоначчи с началом 1 и 2
	        }
	    }
