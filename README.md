# pepsi2
![Меню](https://github.com/SssolidPrincesss/pepsi2/blob/main/pics/image.png)

```java
import java.util.*;
import static java.lang.Math.*;

public class Main {
	public static void main(String[] args) {

		int ref = 234545;
		int sum = 0;
		int s = 0;
		int count = 0;
		
		do {
			count++;
			int x = 10;
			sum += abs(ref) % x;
			ref = abs(ref) / x;
			
		}
		while(ref > 0);

		System.out.println(count + " " +  sum);

	}
}
```
