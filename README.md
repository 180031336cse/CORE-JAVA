# CORE-JAVA
CORE JAVA

Welcome to the CORE-JAVA!

CORE JAVA

#  When a programmar writes JAVA code - it creates (File_Name.java) .java file.
#  After Running a command in terminal - Javac File_Name.java, It creates (File_Name.class) .class file is nothing Byte Code (which can be run on any where by JVM=JAVA VIRTUAL MACHINE).
# JVM is platform dependent because it has to run on specific os only (if we download macos JVM in Windows it wont work) and JVM calls for "main" method in JAVA CODE, from there it will start execution.
# But Byte code is platform independent it can be run on anywhere.
#  JDK = JAVA DEVELOPMENT KIT contains => JRE => JVM + Libraries.
#  JRE = JAVA RUN TIME ENVIRONMENT contains "JVM" + "Libraries".
# JAVA is Write once run anywhere = "WORA"
# NOW JDK Compiles .java file ->to-> .class file, now JRE which contains JVM (java virtual machine)  uses .class file (byte code) converts into machine code.

--------------- JDK + JRE  + JVM --------------------
Final Flow Summary:
1️⃣ JDK (Java Development Kit)

Compiles .java file → .class file (bytecode).
Uses javac (Java Compiler) for this process.
2️⃣ JRE (Java Runtime Environment)

Contains JVM (Java Virtual Machine).
JVM reads the .class file (bytecode) and translates it into machine code that your computer understands.
3️⃣ JVM Execution (Inside JRE)

Converts bytecode → native machine code using:
Interpreter (executes line by line).
JIT (Just-In-Time) Compiler (compiles frequently used bytecode into fast machine code for better performance).

----------------MORE ON JRE -----------------
Yes! JRE contains core libraries that provide essential functionality to Java programs. These libraries are a collection of pre-written Java classes that Java programs can use instead of writing everything from scratch.

1️⃣ What Libraries Does JRE Have?
JRE contains the Java Standard API (Application Programming Interface), which includes:

A. Core Java Libraries (Essential for Every Java Program)

<img width="757" alt="Screenshot 2025-02-10 at 1 52 09 AM" src="https://github.com/user-attachments/assets/ba9be780-f5e7-4f97-a598-539193ef9397" />

2️⃣ Who Created These Libraries?
These libraries are developed and maintained by Oracle Corporation (previously by Sun Microsystems, which created Java).
They are bundled with the Java SE (Standard Edition) and are part of every JRE distribution.
3️⃣ How Does JRE Access These Libraries?
When a Java program runs, the JVM automatically loads required libraries from the JRE’s runtime environment.
