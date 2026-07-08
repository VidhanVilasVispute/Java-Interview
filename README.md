# Java Interview Questions - Topic-Wise Comprehensive List

## 1. CORE JAVA FUNDAMENTALS

### 1.1 Java Basics & JVM
1. What is Java and what are its key features?
2. Is Java 100% object-oriented? What are the advantages of Java being partially object-oriented?
3. What is the difference between primitive and non-primitive data types? Can primitive data types be null?
4. Can we declare pointers in Java?
5. What is the difference between JVM, JRE, and JDK?
6. What are the key components of JVM Architecture?
7. Can a Java application be run without installing the JRE?
8. Is it possible to have JDK without JRE?
9. What makes Java "write once, run anywhere"?
10. What is the Java Virtual Machine (JVM) and how does it work?
11. What are the types of memory areas allocated by JVM? Which is faster to access between heap and stack?
12. What is the role of the JIT (Just-In-Time) compiler?
13. What is a classloader in Java? How does class loading affect memory usage?
14. Is it possible to unload a class in Java?
15. How does garbage collection work in Java? What's the role of finalize() method?
16. Can you tell what algorithm JVM uses for garbage collection?
17. What is the difference between Young Generation and Old Generation memory spaces?
18. How can memory leaks occur in Java even with automatic garbage collection?
19. What is Java Flight Recorder (JFR)?
20. Which version of Java are you using?

### 1.2 Main Method & Program Structure
21. Explain public static void main(String[] args).
22. Can we write static public void main() instead of public static void main()?
23. What will happen if we don't declare the main method as static?
24. Can we override the main method?
25. Can we overload the main method? Can JVM execute our overloaded main method?
26. If no command-line arguments are passed, what is the value in String[] args?
27. Are delete, null, main, exit, or next keywords in Java?
28. Can a .java file be empty? Is it valid?
29. Can we execute a program without the main() method?
30. Can we print something on the console without the main method in Java?

### 1.3 Access Control & Modifiers
31. What are the different access specifiers in Java?
32. What is the default access modifier if none is specified?
33. Can a top-level class be private or protected in Java?
34. What is the purpose of the static keyword in variables and methods?
35. What is a static variable and static method?
36. What is a static block? Where is it stored in memory?
37. Can a static block throw an exception?
38. Difference between static and instance methods
39. Is it possible to access non-static members from within a static method?
40. What is the default value of local variables in Java?
41. What is the final keyword in Java? What are common use cases?
42. What is a final variable, method, and class?
43. What is a blank final variable? How is it initialized?
44. How does the final keyword contribute to immutability and thread safety?
45. Can you modify a final object reference in Java?
46. What is the impact of declaring a method as final on inheritance?
47. What is transient keyword?
48. What is the purpose of serialVersionUID in Java serialization?

### 1.4 Data Types & Wrappers
49. What are wrapper classes? Why do we need them?
50. Why do we use wrapper classes in collections?
51. Can you explain unboxing and autoboxing?
52. Can autoboxing lead to unexpected behavior or NullPointerException?

## 2. OBJECT-ORIENTED PROGRAMMING

### 2.1 OOP Fundamentals
53. What is the object-oriented paradigm?
54. What is the difference between object-oriented and object-based languages?
55. What are the four pillars of OOP (Encapsulation, Inheritance, Abstraction, Polymorphism)?
56. What is a class and object in Java? Difference between class and object?
57. What is the parent class of all Java classes?
58. What are the methods available in the Object class, and how are they used?

### 2.2 OOP Concepts in Depth
59. What is encapsulation and its advantages? How does it enhance security?
60. What is inheritance and why is it used?
61. What is abstraction? How is it implemented in Java?
62. What is polymorphism? Explain compile-time vs runtime polymorphism.
63. Difference between Abstraction and Encapsulation?
64. What is dynamic method dispatch in Java?
65. Can constructors be polymorphic?
66. What is the difference between inheritance and composition?
67. Discuss "composition over inheritance" with an example.
68. What is the difference between association, aggregation, and composition?
69. Explain IS-A (inheritance) and Has-A (composition) relationships.
70. What is object cloning? How is it done in Java?

### 2.3 Constructors
71. What is a constructor in Java? Types of constructors?
72. What is the purpose of the default constructor?
73. Does a constructor return any value?
74. Is a constructor inherited?
75. Can a constructor be final, static, or abstract?
76. Can we overload constructors?
77. What is a copy constructor in Java?
78. Difference between constructors and methods
79. How does constructor chaining work?
80. Can we use a private constructor?
81. Can constructors be overloaded?

### 2.4 Keywords: this and super
82. What is this keyword in Java? What are its uses?
83. Can we assign a reference to this variable?
84. Can this be used to refer to static members?
85. How does constructor chaining work with this()?
86. Advantages of passing this to methods/constructors
87. What is the purpose of the super keyword?
88. Uses of super and how constructor chaining works with it
89. Differences between this and super
90. Can we use this() and super() in the same constructor?
91. Can this be used in a static method or block?
92. What happens if you attempt to use the super keyword in a class that doesn't have a superclass?
93. How does super play a role in polymorphism?

### 2.5 Inheritance & Object Relationships
94. Why does Java not support multiple inheritance (via classes)?
95. Is multiple inheritance supported in Java? How do you use it using interfaces?
96. What is the diamond problem in Java and how does Java address it?
97. What is aggregation vs composition?
98. Can a class extend itself?

### 2.6 Method Overloading & Overriding
99. What is method overloading? What are the rules?
100. Can method overloading be done with static methods or return types?
101. How does the Java compiler determine which overloaded method to call?
102. Is it possible to overload methods that differ only by their return type?
103. Can method overloading be determined at runtime?
104. What is type promotion in method overloading?
105. What is method overriding? What are the rules?
106. Can we override static, private, or final methods?
107. Can we change the return type or access modifier while overriding?
108. How does the @Override annotation influence method overriding?
109. What happens if a subclass overrides a method with different throws clause?
110. What happens if a superclass method is overridden by more than one subclass?

### 2.7 Interfaces & Abstract Classes
111. What is an abstract class and an abstract method?
112. Can an abstract class have static or final methods?
113. Can an abstract method exist outside an abstract class?
114. Can abstract classes be instantiated?
115. What is an interface in Java?
116. Can interface methods be static or protected/private?
117. What is a marker interface? Provide a scenario for custom marker interface.
118. Differences between interface and abstract class
119. When to use abstract class vs interface?
120. Can an interface contain a class or vice versa?
121. What is a functional interface? Can it extend another interface?
122. Difference between functional and normal interface
123. Difference between final and abstract method
124. Can an interface contain static methods? How are they different from default methods?
125. What is a static method in an interface, and how is it different from a default method?
126. What are the differences in interfaces from Java 7 to Java 8?
127. Can an interface with multiple default methods still be a functional interface?
128. Suppose you have multiple interfaces with default methods that a class implements. How would you resolve method conflicts?

## 3. STRINGS

### 3.1 String Fundamentals
129. What is a String in Java? Is it a class or a data type?
130. Why is String immutable?
131. Is String thread-safe?
132. What is the String constant pool? When might it not be beneficial?
133. How is String stored in memory?
134. Ways to create a String object?
135. What happens when you do String s1 = "abc"; vs String s2 = new String("abc");?
136. How are Strings represented in memory?

### 3.2 String Operations & Methods
137. Common methods of the String class? (substring, charAt, length, replace, split, etc.)
138. What does the intern() method do in Strings?
139. How to reverse a String?
140. How to check if a String is palindrome?
141. Difference between contains() and matches()?
142. What's the use of String.valueOf()?
143. What is a StringTokenizer?
144. What is the use of String.join() in Java 8?

### 3.3 String Comparison & Mutable Alternatives
145. Difference between == and .equals() for String comparison?
146. When should you use .equalsIgnoreCase()?
147. Can you tell me about String and StringBuffer?
148. Difference between String, StringBuilder, and StringBuffer?
149. When should you use StringBuilder instead of String?
150. Why is StringBuilder faster than StringBuffer?
151. Is StringBuffer thread-safe?
152. What is the memory impact of using String vs StringBuilder?
153. Give a scenario where StringBuffer is better than String.

## 4. EXCEPTION HANDLING

### 4.1 Exception Handling Basics
154. What is an exception in Java?
155. Difference between error and exception?
156. What is the exception hierarchy?
157. Difference between checked and unchecked exceptions?
158. What is the difference between Throwable and Exception?
159. Can you create your own custom exception class?
160. What is ClassNotFoundException vs NoClassDefFoundError?

### 4.2 Try-Catch-Finally Mechanism
161. How does try-catch-finally work?
162. What is throw, throws, and finally?
163. Can a try block exist without a catch? Can it exist without a finally?
164. Can finally be used without catch?
165. What is the use of the finally block? Will it always be executed?
166. In try-catch-finally with return statements, which one takes precedence?
167. Can we return from finally block? What happens to exceptions then?
168. What happens if an exception is thrown inside a catch block?
169. What is the role of each try, catch, and finally block?
170. What happens if a return statement is executed inside the try or catch block? Does the finally block still execute?
171. Is it possible to execute a program without a catch block? If so, how would you use try and finally together?
172. Can you tell a condition where the finally block will not be executed?
173. Can we write multiple finally blocks in Java?
174. Discuss the difference between finalize() and finally. Under what circumstances might finalize() not get called?

### 4.3 Exception Handling Techniques
175. What is the difference between throw and throws?
176. Can we throw multiple exceptions using throw?
177. Can multiple catch blocks be used? How does exception matching work?
178. Order of exception handling in catch blocks?
179. Can we rethrow an exception?
180. What is multi-catch block (Java 7 feature)?
181. Can we catch multiple exceptions in a single catch block?
182. How would you handle multiple exceptions in a single catch block?
183. What are suppressed exceptions in Java 7?
184. What is try-with-resources? How is it better than try-finally?
185. What is AutoCloseable interface? How does it relate to try-with-resources?

## 5. COLLECTIONS FRAMEWORK

### 5.1 Collections Framework Overview
186. What is the Java Collections Framework? Why is it used?
187. What is the root interface of the Java Collection hierarchy?
188. What are the main interfaces of JCF? (Collection, List, Set, Map, Queue)
189. What is the difference between Collection and Collections?
190. What is the difference between Iterable and Iterator?
191. What are the differences between Iterator, ListIterator, and Enumeration?
192. What are the differences between array and collection?
193. What is the difference between array and ArrayList?
194. What are the differences between the length of an array and the size of an ArrayList?
195. What are the advantages of using generics in collections?
196. How to synchronize List, Set, and Map?
197. What do you understand by fail-fast and fail-safe iterators?
198. What collections have you used in your project?
199. Can you name the data structures you are using in your current project?
200. What enhancements were made to the Java Collection Framework in Java 8?
201. Which algorithms are used by Arrays.sort() and Collections.sort()?

### 5.2 List Implementations
202. What is the difference between ArrayList and LinkedList?
203. Differences between ArrayList, LinkedList, and Vector?
204. When to use ArrayList vs LinkedList? Which is faster and in what scenarios?
205. Is ArrayList thread-safe? How to make it synchronized?
206. What happens when ArrayList exceeds its capacity?
207. How does ArrayList grow internally?
208. Can we store null in ArrayList? How many?
209. How to reverse an ArrayList?
210. How to sort ArrayList in descending order?
211. Can we use generics with ArrayList?
212. Difference between new ArrayList<>() and Arrays.asList()?
213. How to remove duplicates from ArrayList?
214. How to convert ArrayList to Array and Array to ArrayList?
215. How to make Java ArrayList read-only?
216. What is CopyOnWriteArrayList and when should you use it?
217. How do you choose the initial capacity in an ArrayList constructor when the list is repeatedly cleared and reused?

### 5.3 Set Implementations
218. What is a Set in Java?
219. What is the difference between HashSet, LinkedHashSet, and TreeSet?
220. How does HashSet work internally? (HashMap-based)
221. Can we store duplicate elements in Set? What happens?
222. Can we store null in HashSet or TreeSet?
223. Is HashSet ordered?
224. How to iterate over a Set?
225. HashSet vs TreeSet: which one is better in which scenario?
226. What is hash-collision and how is it handled?
227. What is the equals() and hashCode() contract?
228. What happens if only equals() or only hashCode() is implemented?
229. What happens if hashCode returns the same value always?
230. Why is it important to override hashCode() when you override equals()?
231. How does a HashSet ensure no duplicates?
232. Can you give an example where a TreeSet is more appropriate than a HashSet?
233. How does TreeSet sort elements when it stores objects and not wrapper classes?

### 5.4 Map Implementations
234. What is a Map in Java?
235. Differences between HashMap, Hashtable, TreeMap, and ConcurrentHashMap?
236. What is the difference between HashMap and TreeMap?
237. What is the difference between HashMap and IdentityHashMap in terms of how they handle keys?
238. What is the use of HashMap and LinkedHashMap?
239. Can we store null in a HashMap? What about keys and values?
240. What is the internal structure of HashMap? How does it work?
241. What is the purpose of Map.Entry interface?
242. How does load factor work in HashMap?
243. What happens when we insert duplicate keys in HashMap?
244. Explain hash collisions and how they are resolved in HashMap.
245. What changes were made to HashMap in Java 8?
246. Can we use a class/object as a key in HashMap?
247. What are the time complexities of operations in HashMap?
248. What if a key object's hashCode() changes after it is used as a key?
249. What are weak and soft references? How are they useful in collections?
250. What is a WeakHashMap?
251. What is a ConcurrentHashMap and how does it improve performance?
252. How to iterate over a Map in Java?
253. In what scenarios would you prefer to use a TreeMap over a HashMap?
254. Can we add objects as keys in a TreeMap?

### 5.5 Queue Implementations
255. What is a Queue in Java?
256. Differences between Stack and Queue?
257. What is the difference between Queue and Deque?
258. What is a PriorityQueue? How does it work?
259. Can we use PriorityQueue to sort a list?
260. What are blocking queues? Give an example (e.g., ArrayBlockingQueue).
261. Describe a scenario where you used a PriorityQueue, and explain why it was chosen over other types of queues.

### 5.6 Sorting, Comparators, and Custom Ordering
262. What is the difference between Comparable and Comparator?
263. How to sort a list using Comparator?
264. How does Collections.sort() work internally?
265. What would happen if you try to sort a list containing null elements using Collections.sort()?
266. Can you sort a list of custom objects using Collections.sort() without providing a Comparator?
267. What is the difference between using Collections.sort() and Stream.sorted() in Java 8+?

### 5.7 Utility and Advanced Topics
268. Difference between Array and Vector?
269. What is the Dictionary class?
270. What is the advantage of using a Properties file?
271. What is Optional in Java and how does it help (especially when working with collections)?
272. What is the role of ExecutorService in the Executor Framework? What methods does it provide?

## 6. MULTITHREADING & CONCURRENCY

### 6.1 Thread Basics
273. What is a thread in Java? How do threads work?
274. How to create a thread by implementing the Runnable interface?
275. What is the difference between the Thread class and the Runnable interface?
276. Can we start a thread twice?
277. What are the differences between implementing Runnable and extending Thread in Java?
278. What is the Thread class and its lifecycle?
279. What is the purpose of the sleep() and wait() methods?
280. Difference between sleep() and wait() in synchronization context
281. What is a deadlock, and how can we avoid it?
282. How would you handle a scenario where two threads need to update the same data structure?

### 6.2 Synchronization & Concurrency
283. Explain the synchronized keyword in Java.
284. How can you ensure a method is thread-safe in Java?
285. What are volatile variables?
286. What is thread synchronization and why is it important?
287. Can you describe a scenario where you would use wait() and notify() methods in thread communication?
288. What challenges might you face with multithreaded programs in Java?
289. What is the Java Memory Model and how is it linked to threads?
290. What is the Exchanger class?
291. What are concurrent collections in Java?
292. What is the use of CopyOnWriteArrayList and ConcurrentHashMap?

## 7. JAVA 8+ FEATURES

293. Can you tell me some new features introduced in Java 8?
294. Why were the Optional class, Lambda Expressions, and Stream API introduced in Java 8?
295. What are functional interfaces and their advantages?
296. What is the difference between Lambda Expressions and Anonymous Classes?
297. What is the difference between filter() and map() in the Stream API?
298. Explain the difference between Stream API map() and flatMap().
299. Explain the difference between peek() and map(). In what scenarios should peek() be used with caution?
300. Explain intermediate and terminal operations in Streams.
301. Which is faster, a traditional for loop or Streams? When to prefer each?
302. What is the diamond operator, and how does it work?
303. What is Type Erasure?
304. What is generic type inference?
305. Why can't we create an array of generic types in Java?
306. Can you tell me some new features introduced in Java 11?
307. Can you tell me some new features introduced in Java 17?
308. Can you tell me some new features introduced in Java 21?

## 8. ENUMS, INNER CLASSES & REFLECTION

309. What are enums in Java and how are they useful?
310. Can an enum extend another class in Java?
311. How do you iterate over all values of an enum?
312. Explain inner classes in Java.
313. Can inner classes have static declarations?
314. What is the significance of an anonymous inner class?
315. What are anonymous classes and their advantages?
316. What is reflection in Java?

## 9. SERIALIZATION & PACKAGES

317. What is the concept of Serialization in Java?
318. What is the purpose of serialVersionUID in Java serialization?
319. What happens if the serialVersionUID of a class changes during deserialization?
320. How can you prevent certain fields from being serialized in Java?
321. Can a class be serialized if one of its member fields is not serializable?
322. What is the difference between writeObject() and readObject() methods?
323. Is it possible to serialize static fields in Java? Why or why not?
324. How do you serialize an object with circular references in Java?
325. What happens if an exception is thrown during the serialization process?
326. What if your Serializable class contains a member which is not serializable? How do you fix it?
327. What are packages in Java? Why are packages used?
328. How do imports affect compilation and class loading?
329. What is the difference between import and static import?
330. What is the impact of static imports on code readability and maintainability?
331. How do you access a package-private class from another package?
332. What happens if two packages have the same class name?

## 10. DESIGN PATTERNS & PRINCIPLES

333. What is a design pattern in Java and why do we use it?
334. Can you list and explain a few common design patterns used in Java programming?
335. How can design patterns affect the performance of a Java application?
336. Which design pattern would you use to manage database connections efficiently?
337. How do you choose the appropriate design pattern for a particular problem?
338. What is the Builder Pattern? How is it different from the Factory Pattern?
339. What is a Singleton class? How can we create one? Are they thread-safe?
340. What are SOLID Principles?

## 11. SCENARIO-BASED QUESTIONS

341. Scenario-Based: How would you handle a situation where you need to compare the content equality of two custom object instances?
342. Scenario-Based: Suppose you're storing user session data in a HashMap. How would you ensure thread safety?
343. Scenario-Based: How would you handle a situation where you need to sort a collection of custom objects based on multiple fields?
344. Scenario-Based: How would you design a thread-safe cache using Java collections?
345. Scenario-Based: How would you implement a producer-consumer problem using Java?
346. Scenario-Based: How would you handle exception propagation in a layered architecture?
347. Scenario-Based: How would you optimize a Java application that's experiencing memory leaks?
348. Scenario-Based: How would you implement a retry mechanism for failed operations?
349. Can you create a server in a Java application without using Spring or any other framework?
