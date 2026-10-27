# OOP Java Lab (CEUE203) - Practicals 1 to 14

Every `pracN` folder contains
* `partA*` folders - the Part A practice programs (each program has its `.java` and compiled `.class` file)
* `partB_MiniBank` - the MiniBank project as it stands at the end of that lab (cumulative)

Compiled with JDK target 17, so the `.class` files run on JDK 17 or newer.

## Run a program
    cd prac1/partA
    java VendingMachine

Programs from prac6 onward use packages (model, util, service, exception). Run from the `partB_MiniBank` folder:

    cd prac8/partB_MiniBank
    java MiniBank

Recompile after editing (from inside the folder):

    javac -d . $(find . -name '*.java' ! -path './tests/*')

Runnable JARs: `prac6/partB_MiniBank/minibank.jar`, `prac6/partA_discount/discount-engine.jar`, `prac14/partB_MiniBank/minibank.jar`
    java -jar minibank.jar

## Notes
* prac14 JUnit tests are in `tests/BankServiceTest.java` (needs the JUnit 5 library). `tests/SelfTest.java` runs the same checks without it.
* Git/GitHub steps (repository, commits, tags lab-NN) and the README/screenshot submissions are for you to do.
