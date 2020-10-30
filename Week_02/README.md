# Week two

## 1. Class Relationships

* Realization 
* Inheritence/Generalization
* Dependence
* Association
* Aggregation
* Composition

## 2. Java Fundermentals
 * Static Instance Variable
 * Static Method
 * Static Class
 * Volatile 
    * Visibility Problem
    * Useful Resource: http://tutorials.jenkov.com/java-concurrency/volatile.html
 * Single-checked Locking VS Double-checked Locking
    * Performance Drawback - Acquire a potentially unnecessary lock. 

## 3 Singleton
  * Resource: https://www.journaldev.com/1377/java-singleton-design-pattern-best-practices-examples
  * Not Recommended
    * Eager Initialization
      * Pro
        * Easy implementation
        * Thread Safe
      * Con
        * No Lazy Loading - Memory Waste
    * Static Block Initialization
      * Pro
        * Easy implementation
        * Thread Safe
      * Con
        * No Lazy Loading - Memory Waste
    * Lazy Initialization
      * Pro
        * Lazy Loading
        * Single Thread Only
      * Con
        * Not Thread Safe
    * Single-Checked Locking
      * Pro
        * Thread Safe
      * Con
        * Performance Drawback - Acquire a potentially unnecessary lock
  * Recommended
    * Double-checked Locking
    * Bill Pugh - Static Class
    * Enum
  * Singleton Example
    * java.lang.Runtime.java 
    
