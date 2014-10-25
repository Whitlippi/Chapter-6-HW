Chapter-6-HW
============

 Problems:
 
 2: 
  a) f
  b) f
  c) f can at times be acceptable to use single letter variable names
  d) t
  e) f 
  
3: Symbolic constants simplify program maintenance, make code more readable, and its easy to change them into variables if you need to. 
4:
 B

5:
  Compiled
  
6:
 a) 0
 b) 0
 c) 5.0
 d) 5.0 
 e) 3
 
7:
 a) 105
 b) 19.0

8:
  count += (total/pages - 5) * words - 1;
9:
  Changed 1 to 1.0 so that it wouldnt equal zero anymore and got rid of unnecessary (
  
  final double g = 16.0;
  double t = 35.5;
  System.out.print ("The travel distance is ");
  System.out.println(1.0/2 *g*t*t);
  
12:
  Should be: 
     double temp;
13:
public int digitSwitch(int n) {
  int unit = n%10;
  int tens = n%100;
  int rest = n/100;
  return (rest * 100) + (unit * 10) + (tens/10);
}

14:
	public int dayOfWeekJan(int day, int dayOfWeek1) {
		int dayOfWeek = 0;
		if (day == 1){
			dayOfWeek = dayOfWeek1;
		}else {
			if (dayOfWeekJan(day-1,dayOfWeek1) < 6){
				dayOfWeek = dayOfWeekJan(day-1,dayOfWeek1) + 1;
			}else if (dayOfWeekJan(day-1,dayOfWeek1) == 6){
				dayOfWeek = 0;
			}
		}
		return dayOfWeek;
	}
	
15:
 int minDiff = (60-curMin + depMin)%60;
 if ((60-curMin + depMin)<60) depHour -= 1; 
 System.out.println((depHour-curHour) + " hours and " + minDiff + " minutes.";
16:
  See Github file
