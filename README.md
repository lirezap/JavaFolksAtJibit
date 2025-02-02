### Java Folks @Jibit

Hello, hope all is well dear friend 😎

Here at Jibit, we are seeking Mid-Level to Senior-Level Java Developers, who are passionate about Java, Financial
Software Development and Data. If you like, you can read this file carefully and send your CV
[to us](https://career.hrcando.ir/co/IvanRayanPayam).

However, before sending your resume, please make sure you can find reasonable answers to the following questions. These
are some example questions or required background that we expect candidates to be familiar with, before our first online
meeting.

#### Senior-Level Candidate; Example Questions

- What are safety, live-ness and performance issues of using threads?

- What are the side effects of scheduling, or interleaving of the execution by the runtime?

- What are race condition, atomicity and visibility?

- What is compound action? Can you name some forms of that?

- What has re-entrant lock to offer for OOP in Java?

- What is stale data? Explain in context of Nonatomic 64-bit operations.

- What is the meaning of thread confinement? How to achieve that in Java?

- How to design an immutable object in Java?

- Why Java's compiler or runtime can reorder instructions? How to restrict this behaviour?

- How does JIT and AOT work exactly?

- What is wrong with the following piece of java code?

```java
public class Publication {

    public Publication(EventSource source) {
        source.registerListener(new EventListener() {
            public void onEvent(Event e) {
                doSomething(e);
            }
        });
    }
}
```

#### Mid-Level Candidate; Example Questions

- What are the differences between compiled and interpreted languages?

- Name some important interfaces of Java collections; What are pros and cons of them?

- Name some important design patterns; Where do they help?

- What is switch expression?

- How does exception handling work in Java?

- What are hashCode and equals methods?

- What is a thread of execution?

- What is the meaning of thread-safety?

- What are the consequences of using a synchronized block?

- How does the fork-join-pool work?

- What is wrong with the following piece of java code?

```java
public class A {
    private String a;

    public A(String a) {
        this.a = a;
        System.out.println(length());
    }

    public int length() {
        return a.length();
    }
}

class B extends A {
    private String b;

    public B(String a, String b) {
        super(a);
        this.b = b;
        System.out.println(length());
    }

    @Override
    public int length() {
        return b.length();
    }
}
```
