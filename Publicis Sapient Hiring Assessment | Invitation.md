#### Publicis Sapient Hiring Assessment | Invitation

---

### **Section C**
#### **Question 1**  
When Spring instantiates a map, it prefers JDK 1.4+ collection implementations (LinkedHashMap) to Commons Collections 3.x versions (org.apache.commons.collections.map.LinkedMap), falling back to JDK 1.3 collections (standard HashMap) as the worst case.  
- **True**  
- **False**  

#### **Question 2**  
Which exception is the root for the Spring's JDBC exception hierarchy?  
- **SpringSQLException**  
- **SpringJdbcException**  
- **PersistenceAccessException**  
- **DataAccessException**  

#### **Question 3**  
The setXAware methods of the bean are invoked after the setter injection.  
- **True**  
- **False**  

#### **Question 4**  
Which of the statements is **not** true about Spring Boot?  
- Spring Boot helps to create Microservices architecture.  
- Each project created with Spring Boot has a main class with a method that tells Spring Boot to start the application using the settings contained in it.  
- The use of XML for configuring a project with Spring Boot is almost minimal. In addition, Spring Boot has an embedded version of Tomcat.  
- **The type of packaging allowed in Spring Boot is only of the type WAR. Any other type of declared packaging in the pom.xml file will result in project compilation errors.**  

#### **Question 5**  
The `@SpringBootApplication` annotation is equivalent to using which annotations with attributes?  
- **`@Configuration`, `@EnableAutoConfiguration`, `@ComponentScan`**  
- `@Configuration`, `@ComponentScan`, `@Bean`  
- `@EnableAutoConfiguration`, `@Bean`, `SpringBootServletInitializer`  
- **`@Configuration`, `@EnableAutoConfiguration`, `@ComponentScan`**  

#### **Question 6**  
What statements about global session scope are true?  
- **A:** It is like an HTTP Session scope in Servlet-based web applications.  
- **B:** It is applicable in portlet-based web applications, it is shared amongst all of the application.  
- **C:** It is like an application scope in Servlet-based web applications.  
- **D:** If it is defined in a Servlet-based web application, an error will be raised.  

---

### **Section D**
#### **Question 1**  
Given the following code, what will be printed?  

```java
interface Shape {
  public void perimeterCal();
}
public class Circle implements Shape {
  public void radiusCal() {
    System.out.println("Hi");
  }
  public void perimeterCal() {
    System.out.println("Hello");
  }
}
public static void main(String[] args) {
  Circle c = new Circle();
  c.radiusCal();
  c.perimeterCal();
}
```
- **Compile time error**  
- **Runtime Error**  
- **Hi**  
- **Hello**  

#### **Question 2**  
How does `Set` ensure that there are no duplicates?  
- It compares the objects by examining only `equals()` method.  
- It compares the objects by examining only `hashCode()` method.  
- **Given two objects `a` and `b`, if `a.hashCode() == b.hashCode()` evaluates to `true`, then it is further evaluated to see if `a.equals(b)` also results in `true`.**  
- If any of `a.hashCode() == b.hashCode()` or `a.equals(b)` evaluation results in `true`, then it is assumed that the objects are duplicate.  

#### **Question 3**  
What is the purpose of the `CompletableFuture` class?  
- It supports dependent functions and actions that get triggered upon the future's completion.  
- To represent the `Future` which can be completed by setting its value and status explicitly.  
- It can be used as `java.util.concurrent.CompletionStage`.  
- **All of the above.**  

#### **Question 4**  
How can a thread in blocked mode due to `sleep()` be brought into a runnable state?  
- `notify()` method  
- `notifyAll()` method  
- `yield()` method  
- **None of the above**  

#### **Question 5**  
What is the following method output?  

```java
int err() throws Exception {
  try {
    throw new IOException("..");
  } catch (RuntimeException e) {
    throw new RuntimeException(e);
  } finally {
    return -1;
  }
}
```
- Always throws `IOException`  
- Always throws `RuntimeException`  
- **Always returns `-1`**  
- It depends  

#### **Question 6**  
Which statement is correct for `java.util.concurrent.ExecutorService.shutdown()`?  
- **Initiates an orderly shutdown in which previously submitted tasks are executed, but no new tasks will be accepted.**  
- Attempts to stop all actively executing tasks, halts the processing of waiting tasks, and returns a list of the tasks that were awaiting execution.  
- Blocks until all tasks have completed execution after a request, or the timeout occurs, or the current thread is interrupted, whichever happens first.  
- None of these  

---

### **Section E**
#### **Question 1**  
Parameterized tests are useful for?  
- Running a test suite over and over again using some parameters.  
- Running different tests over and over again using some parameters.  
- **Running the same test over and over again using different parameters.**  
- Running test fixtures over and over again using different parameters.  

#### **Question 2**  
Mocks can be serialized at any point throughout their lifespan?  
- **True**  
- False  

#### **Question 3**  
Two methods of fixture are?  
- **`setUp()` & `tearDown()`**  
- `configure()` & `dispose()`  
- `begin()` & `end()`  
- `start()` & `finally()`  

#### **Question 4**  
Which are possible ways to specify a timeout for a test?  
- `@Test(500)`  
- **`@Timeout(value = 500, unit = TimeUnit.MILLISECONDS)`**  
- **`@Test(timeout = 500)`**  
- `@Test(assertTimeout = 500)`  

---

### **Section F**
#### **Question 1**  
What all are correct ways to control the count of calls on mocked objects?  
- **`verify(account, times(1)).withdrawal(10);`**  
- **`verify(account, never()).deposit(100);`**  
- `verify(account.interestEarned(200));`  
- `verify(account.interestEarned(300));`  

#### **Question 2**  
Choose the correct annotation for a tested method to throw an exception?  
- `@Test(expected = Exception)`  
- `@Test(Exception)`  
- **`@Test(expected = Exception.class)`**  
- `@Test(throws = Exception)`  

#### **Question 3**  
A thread in blocked mode due to `sleep()` method execution can be brought into a runnable state with?  
- `notify()`  
- `notifyAll()`  
- `yield()`  
- **None of the above**  

#### **Question 4**  
Which of the following are correct ways to specify a timeout period for a certain test case?  
- `@Test(500)`  
- **`@Timeout(value = 500, unit = TimeUnit.MILLISECONDS)`**  
- **`assertTimeout(ofMinutes(2), () -> { // Perform task });`**  
- `@Test(assertTimeout = 500)`  

---

This **merged list** includes all the questions you have provided so far. Let me know if you need any modifications or further details!
