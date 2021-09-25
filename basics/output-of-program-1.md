# Output of Java Program 1

## Question 1

Given the following code.

```java

interface Syrupable {
    void getSugary();
}

abstract class Cake implements Syrupable {}

class CheeseCake implements Cake {
    public void getSugary() {
    }
}

class JapaneseCheeseCake extends CheeseCake {
    void getSugary(int n) {

    }
}

```

Choose **ONE** correct answer and explain your choice.

- [ ] Compilation succeeds.
- [ ] Compilation fails.

## Question 2

What is the output of the following program?

```java

class Question2 {
    public static void main(String[] args) {
        int mask = 0x000F;
        int value = 0x2222;
        System.out.println(value & mask);
    }
}

```

Choose **ONE** correct answer and explain your choice.

- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4

## Question 3

What is the output of the following code?

```java
class Question3 {
    public static void main(String[] args) {
        for(int i = 0; 1; i++) {
            System.out.println("Hello");
            break;
        }
    }
}
```

Choose **ONE** correct answer and explain your choice.

- [ ] Compilation fails.
- [ ] The program compiles and prints out "Hello".
- [ ] The program compiles and runs infinitely.
