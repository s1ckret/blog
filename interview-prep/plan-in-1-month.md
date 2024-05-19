---
description: Preparation plan
---

# Plan in 1 month

1. **Java Language and Core Concepts:**
   * Advanced topics in Java programming language (generics, collections, etc.).
     * [notify vs notifyAll](https://stackoverflow.com/questions/37026/java-notify-vs-notifyall-all-over-again)
     * [hashCode() and equals() contract](https://www.baeldung.com/java-equals-hashcode-contracts)
     * syncronized method is synchronised on `this`
     * [List contravarience and varience](https://medium.com/@yuhuan/covariance-and-contravariance-in-java-6d9bfb7f6b8e)
   * Multithreading and concurrency in Java.
     * [data race vs race condition](https://www.youtube.com/watch?v=KGnXr62bgHM\&list=PLhfHPmPYPPRk6yMrcbfafFGSbE2EPK\_A6\&index=27\&ab\_channel=DefogTech)
     * [https://www.baeldung.com/java-thread-lifecycle](https://www.baeldung.com/java-thread-lifecycle)
     * [https://www.baeldung.com/java-lang-thread-state-waiting-parking](https://www.baeldung.com/java-lang-thread-state-waiting-parking)
   * Java memory management (Garbage Collection, memory leaks, etc.).\
     [https://docs.oracle.com/en/java/javase/17/gctuning/index.html](https://docs.oracle.com/en/java/javase/17/gctuning/index.html)
   * Design patterns and best practices in Java.
     * [Double-checked locking](https://en.wikipedia.org/wiki/Double-checked\_locking#Usage\_in\_Java)
     * [Active Object](https://en.wikipedia.org/wiki/Active\_object)
     * [Pretty much all of the patterns from the Design Guru](https://refactoring.guru/design-patterns/catalog)
2. Databases
   1.

       <figure><img src="../.gitbook/assets/image (2).png" alt="" width="375"><figcaption></figcaption></figure>
   2. [ACID](https://www.databricks.com/glossary/acid-transactions) is an acronym that refers to the set of 4 key properties that define a transaction: Atomicity, Consistency, Isolation, and Durability.
   3. 'Object-Relational Impedance Mismatch' (sometimes called the 'paradigm mismatch') is just a fancy way of saying that object models and relational models do not work very well together
   4. [Hibernate basics](https://medium.com/@mohamed.elhamra/hibernate-framework-basics-and-architecture-fe2bea5911ae)
   5.  [Hibernate lifecycle](https://nikhilsukhani.medium.com/hibernate-lifecycle-states-in-hibernate-transient-persistent-detached-removed-40ba2f689b07)

       <figure><img src="../.gitbook/assets/image (3).png" alt="" width="375"><figcaption></figcaption></figure>


3. **Advanced AWS Services:**
   * AWS Lambda
   * AWS DynamoDB
   * AWS ECS
4. **Microservices Architecture:**
   * Spring
     * How to inject runtime prototype: @Lookup or Provider<> injection
   * Principles of microservices architecture.
   * Service discovery and communication (RESTful APIs, gRPC, messaging queues).
     *   Idempotence - when the same action leads to the same result.\
         Safety means that sending a request will not change the state of the server or the resource at all

         <figure><img src="../.gitbook/assets/image (4).png" alt="" width="375"><figcaption></figcaption></figure>
   * Containerization (Docker) and orchestration (Kubernetes).
   * Monitoring and logging for microservices.
5. **System Design and Scalability:**
   * Designing scalable and fault-tolerant systems.
   * Load balancing and caching strategies.
   * Horizontal and vertical scaling.
   * Database sharding and replication.
6. **DevOps and CI/CD:**
   * Continuous Integration and Continuous Deployment practices.
   * Jenkins, GitHub CI
7. **Performance Optimization:**
   * Profiling and debugging Java applications.
   * Performance tuning of JVM.
   * Optimizing database queries and indexing strategies.
8. **Security Best Practices:**
   * Securing APIs and data in transit.
   * Encryption mechanisms.
   * OWASP Top 10 vulnerabilities and mitigation strategies.
9. **Soft Skills and Leadership:**
   * Communication skills and ability to mentor junior developers.
   * Problem-solving and decision-making skills.
   * Experience in leading and managing technical projects.
