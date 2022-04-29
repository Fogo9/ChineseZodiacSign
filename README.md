# **CHINESE ZODIAC**

# Information

* **You can find out your Chinese zodiac sign by entering your year of birth.**

# Technologies Used

* **JAVA**

# Codes

```Java

       import java.util.Scanner;

        public class chinesezodiac{

            public static void main(String[] args) {

            int year, remainder;

            String zodiacsign = "";

            Scanner input = new Scanner(System.in);

            System.out.print("Enter Your Year of Birth : ");

            year = input.nextInt();

```

```Java

            remainder = year % 12;

            switch(remainder){

            case 0:

                zodiacsign = "Monkey";

                break;

            case 1:

                zodiacsign = "Cockerel";

                break;

            case 2:

                zodiacsign = "Dog";

                break;

            case 3:

                zodiacsign = "Pig";

                break;

            case 4:

                zodiacsign = "Mouse";

                break;

            case 5:

                zodiacsign = "Ox";

                break;

            case 6:

                zodiacsign = "Tiger";

                break;

            case 7:

                zodiacsign = "Rabbit";

                break;

            case 8:

                zodiacsign = "Dragon";

                break;

            case 9:

                zodiacsign = "Snake";

                break;

            case 10:

                zodiacsign = "Horse";

                break;

            case 11:

                zodiacsign = "Sheep";

                break;

        }
        System.out.println("Your Chinese Zodiac Sign : " + zodiacsign);


    }
}

```
```bash

        Enter Your Year of Birth : 1990
        Your Chinese Zodiac Sign : Horse

```

<br />

# LINK

* Click here https://github.com/Fogo9/ChineseZodiacSign.git to access the Github page for this project.

<br />

# LICENSE

* This software is licensed By Tuncay Demir under the MIT license.

<br />

>[Patika.dev](https://app.patika.dev/fogomurphy)

<br/>

| Name |  Email |
| ---- |  ----- |
| Tuncay | tuncaydemir682@gmail.com |
