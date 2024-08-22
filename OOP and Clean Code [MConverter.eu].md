**[WHY OOP ?]{.mark}**

[If you don't use Object-Oriented Programming (OOP) principles, you may
encounter several challenges and limitations in your software
development process.]{.mark}

### **[1. Increased Code Duplication]{.mark}** {#increased-code-duplication}

[Without OOP, you might end up duplicating code across different parts
of your application because there's no concept of reusing and inheriting
common functionality.]{.mark}

[**Example**: If you have multiple functions for calculating salaries
for different types of employees and these functions contain similar
code, it leads to redundancy.]{.mark}

[**Impact**: Code duplication makes maintenance harder because any
change to the shared logic requires updating every instance where it's
duplicated.]{.mark}

### **[2. Lack of Modularity]{.mark}** {#lack-of-modularity}

[Without OOP, your code may be more procedural, with functions operating
on data structures directly. This approach can lead to a tangled
codebase where related data and functions are not grouped
together.]{.mark}

[**Example**: Instead of grouping employee-related functions and data
together, you might have scattered functions handling various aspects of
employees across your code.]{.mark}

[**Impact**: Lack of modularity makes it harder to understand, maintain,
and extend the code. Changes to one part of the code can inadvertently
affect other parts.]{.mark}

### **[3. Difficulty in Extending Code]{.mark}** {#difficulty-in-extending-code}

[Without OOP principles like inheritance and polymorphism, extending or
modifying functionality can be cumbersome. You might need to rewrite or
duplicate code to accommodate new requirements.]{.mark}

[**Example**: If you need to add a new type of employee with different
salary calculations, you would have to create new functions or modify
existing ones extensively.]{.mark}

[**Impact**: This approach makes the codebase rigid and harder to
extend, leading to more error-prone and difficult-to-manage
code.]{.mark}

### **[4. Tangled Code]{.mark}** {#tangled-code}

[In a non-OOP paradigm, different parts of your codebase may become
tightly coupled. Functions that operate on data structures might
directly modify them, leading to tangled code that's difficult to debug
and test.]{.mark}

[**Example**: If you have various functions modifying a global employee
data structure, the interactions between these functions and the data
can become complex and difficult to trace.]{.mark}

[**Impact**: Tight coupling between data and functions makes it harder
to isolate and fix bugs, as changes in one part of the code can have
unintended consequences in other parts.]{.mark}

### **[5. Difficulty in Managing State and Behavior]{.mark}** {#difficulty-in-managing-state-and-behavior}

[Without OOP, managing the state and behavior of complex objects becomes
more challenging. Procedural programming might involve managing state
through global variables, which can lead to conflicts and difficulties
in tracking changes.]{.mark}

[**Example**: Managing an employee's state (like employment status) and
behavior (like calculating salary) through global variables and
functions can be error-prone and hard to manage.]{.mark}

[**Impact**: This approach can lead to bugs and unexpected behavior, as
the state might be modified by various parts of the codebase in
unpredictable ways.]{.mark}

### **[6. Increased Complexity in Code Organization]{.mark}** {#increased-complexity-in-code-organization}

[In procedural programming, organizing code for large-scale applications
can become chaotic. Without OOP, the separation of concerns becomes
harder, and organizing code logically around different entities (like
employees, orders, etc.) is more complex.]{.mark}

[**Example**: A large codebase dealing with various entities might end
up with a long list of unrelated functions operating on different data
structures.]{.mark}

[**Impact**: Code organization becomes a significant challenge, making
it harder to navigate and understand the codebase, leading to longer
development and debugging times.]{.mark}

### **[7. Less Reusability]{.mark}** {#less-reusability}

[OOP promotes code reusability through mechanisms like inheritance and
polymorphism. Without these features, reusing code across different
parts of your application becomes more challenging, often requiring
duplication or extensive refactoring.]{.mark}

[**Example**: If different parts of your application need similar logic
for handling employees, without OOP, you might end up duplicating this
logic in different places.]{.mark}

[**Impact**: The lack of reusability leads to more code to maintain and
a higher likelihood of introducing bugs due to inconsistent
logic.]{.mark}

### **[Illustrative Example Without OOP]{.mark}**

[Imagine a simple payroll system in a procedural style:]{.mark}

![](media/image32.png){width="6.5in" height="5.013888888888889in"}

### **[With OOP Approach]{.mark}**

[In contrast, using OOP:]{.mark}

![](media/image28.png){width="6.5in" height="7.472222222222222in"}

**[Classes and Objects :]{.mark}**

[Why we need Classes and Objects ?]{.mark}

[In simple terms, we need classes and objects in programming for these
reasons:]{.mark}

### **[1. Organize Code]{.mark}** {#organize-code}

[**Classes**: Think of a class as a blueprint. It helps you organize
related data and functions together in one place. For example, a Car
class keeps all the car-related information (like make and model) and
actions (like driving) together.]{.mark}

[**Objects**: Objects are specific instances of a class. They let you
create multiple cars from the Car class, each with its own
details.]{.mark}

### **[2. Encapsulate Data]{.mark}** {#encapsulate-data}

[**Classes**: They bundle data and the methods that operate on that data
into a single unit. This keeps your data safe and ensures it can only be
changed in controlled ways.]{.mark}

[**Objects**: Each object has its own data and methods. You can interact
with the object without needing to know how it works internally.]{.mark}

### **[3. Reuse Code]{.mark}** {#reuse-code}

[**Classes**: Once you define a class, you can create many objects from
it without rewriting the code. For example, you can create multiple Car
objects using the same Car class.]{.mark}

[**Objects**: Each object represents a specific example of a class,
saving you from duplicating code.]{.mark}

### **[4. Extend Functionality]{.mark}** {#extend-functionality}

[**Classes**: You can create new classes based on existing ones,
inheriting their features and adding new ones. This lets you build on
top of existing code.]{.mark}

[**Objects**: When you create new objects from a class, they
automatically get the functionality defined in the class.]{.mark}

### **[5. Simplify Interaction]{.mark}** {#simplify-interaction}

[**Classes**: They define clear ways to interact with data and
functions. This makes it easier to understand how to use and modify
them.]{.mark}

[**Objects**: They use these clear definitions to perform tasks or
display information, making your code easier to manage and use.]{.mark}

### **[In Summary]{.mark}**

- [**Classes**: Organize and define what data and actions an object will
  > have.]{.mark}

- [**Objects**: Create specific instances from the class and use its
  > features.]{.mark}

[Using classes and objects helps make your code more organized,
reusable, and easier to understand.]{.mark}

**[Example: Managing Books]{.mark}**

[1. Define the Book Class]{.mark}

[This class includes attributes (fields) for the book\'s title and
author, and methods to display the book\'s details.]{.mark}

![](media/image64.png){width="5.770833333333333in" height="5.625in"}

[2. Create and Use Objects of the Book Class]{.mark}

[In the Main class, we create instances (objects) of Book and use them
to display information.]{.mark}

![](media/image46.png){width="6.5in" height="3.9722222222222223in"}

### [Why Classes and Objects?]{.mark}

- [Classes: Provide a blueprint to define what data (title, author) and
  > actions (displayInfo()) a book has.]{.mark}

- [Objects: Allow you to create specific books with different titles and
  > authors and interact with them using the methods defined in the Book
  > class.]{.mark}

[This example demonstrates how classes help organize and structure code,
while objects allow you to create and manage instances of that structure
in a clear and manageable way.]{.mark}

# **Inheritance in Java**

[What is Inheritance and Why Inheritance ?]{.mark}

[In Simple words, making a class from another class or inheriting
another class.]{.mark}

- You might have heard people saying **your nose is similar to your
  > father or mother**. Or, more formally, we can say that you\'ve
  > inherited the genes from your parents due to which you look similar
  > to them.

- The **same phenomenon of inheritance** is also valid in programming.

- In Java, one class can easily inherit the attributes and methods from
  > some other class. This mechanism of acquiring objects and properties
  > from some other class is known as inheritance in Java.

- **Inheritance is used to borrow properties & methods from an existing
  > class.**

- Inheritance helps us **create classes based on existing classes**,
  > which increases the code\'s reusability.

![](media/image41.jpg){width="5.729166666666667in"
height="2.0833333333333335in"}

**Types of Inheritance :**

![](media/image15.png){width="6.25in" height="5.1875in"}

**Single Inheritance :**

![](media/image20.jpg){width="6.5in" height="4.875in"}

Things to notice :

**Derived class can retrieve properties from Base class, but Base class
can not retrieve properties from a Base class.**

**Multi-level Inheritance :**

![](media/image38.jpg){width="3.3020833333333335in" height="2.46875in"}

Heres a code :

![](media/image43.png){width="6.5in" height="7.861111111111111in"}

### Explanation:

1.  Animal: The base class with a method eat().

2.  Mammal: This class extends Animal and adds a new method breathe().

3.  Dog: This class extends Mammal and adds a new method bark().

**Hierarchical Inheritance :**

![](media/image22.jpg){width="3.9531255468066493in"
height="2.5092530621172355in"}

Heres a code :

![](media/image51.png){width="6.5in" height="9.817708880139982in"}

**Why is multiple inheritance not supported in java?**

**Creates a Diamond problem.**

**Here -**

![](media/image19.jpg){width="5.677083333333333in" height="3.46875in"}

Multiple Inheritance face problems when there exist methods with the
**same signature** in the **both super classes.**

**Solutions ?**

Due to such support **Java does not support multiple inheritance** but
similar goal can be achieved using **interfaces.**

**Polymorphism :**

Polymorphism can be broadly categorized into two types:

1.  Compile-time Polymorphism (Method **Overloading**)

2.  Runtime Polymorphism (Method **Overriding**)

![](media/image48.jpg){width="5.890625546806649in"
height="3.7083333333333335in"}

### 

### 

### **1. Compile-time Polymorphism (Method Overloading)** {#compile-time-polymorphism-method-overloading}

Compile-time polymorphism, or method overloading, occurs when multiple
methods have the same name but different parameters within the same
class. The method to be invoked is determined at compile time based on
the method signature.

![](media/image44.png){width="6.828125546806649in"
height="4.916666666666667in"}

### **2. Runtime Polymorphism (Method Overriding)** {#runtime-polymorphism-method-overriding}

### Runtime polymorphism, or method overriding, occurs when a subclass provides a specific implementation of a method that is already defined in its superclass. The method to be invoked is determined at runtime based on the actual object type. {#runtime-polymorphism-or-method-overriding-occurs-when-a-subclass-provides-a-specific-implementation-of-a-method-that-is-already-defined-in-its-superclass.-the-method-to-be-invoked-is-determined-at-runtime-based-on-the-actual-object-type.}

![](media/image53.png){width="6.5in" height="7.930555555555555in"}

### **Real-Life Analogy: Payment System**

Imagine you have a payment system that needs to handle different types
of payments. The system needs to process credit card payments, bank
transfers, and digital wallet payments. Each type of payment has a
different process but can be handled in a similar way from the
perspective of the payment system.

### **Compile-Time Polymorphism (Method Overloading)** {#compile-time-polymorphism-method-overloading-1}

Scenario: In the payment system, you might want to provide different
methods for processing payments based on the payment type or the
currency used.

Code example :

![](media/image62.png){width="6.979166666666667in"
height="5.800986439195101in"}

### **Runtime Polymorphism (Method Overriding)** {#runtime-polymorphism-method-overriding-1}

**Scenario:** You have a base class PaymentMethod that defines a common
interface for processing payments. Subclasses like CreditCard,
BankTransfer, and DigitalWallet each have their specific implementation
of how to process the payment.

![](media/image47.png){width="6.994792213473316in"
height="6.947916666666667in"}

### **What is Abstraction?**

Abstraction involves creating a **simplified model of a system** by
defining a set of properties and behaviors while **ignoring the complex
details**. This is achieved through **abstract classes** and
**interfaces** in Java.

Abstract Classes:

- Definition: An abstract class is a class that cannot be instantiated
  > on its own and may contain abstract methods (methods without
  > implementations) as well as concrete methods (methods with
  > implementations).

- ![](media/image57.png){width="6.5in" height="8.375in"}Purpose:
  > Abstract classes are used when you have a base class that should not
  > be instantiated directly but should be inherited by other classes.
  > They provide a partial implementation that can be shared among
  > multiple subclasses.

![](media/image11.png){width="6.5in" height="9.902777777777779in"}

Interfaces:

- Definition: An interface in Java is a reference type that can contain
  > method signatures (abstract methods), constants, default methods,
  > and static methods. Interfaces define a contract that implementing
  > classes must follow.

- Purpose: Interfaces allow you to define a set of methods that must be
  > implemented by any class that implements the interface. They enable
  > multiple inheritance of method signatures and provide a way to
  > achieve polymorphism.

Example :

### **Payment Methods**

**Scenario**: Suppose you are building an e-commerce application that
supports multiple payment methods such as credit cards, PayPal, and bank
transfers. You want to define a common interface for handling payments
so that you can easily add new payment methods in the future.

![](media/image21.png){width="4.979166666666667in" height="2.90625in"}

![](media/image23.png){width="6.5in" height="5.263888888888889in"}

![](media/image25.png){width="6.5in" height="3.8055555555555554in"}

**Abstract Class Vs Interfaces :**

**We can extend multiple abstract classes but we can implement multiple
interfaces at a time.**

**You can not modify properties in interfaces as they are final.**

**Encapsulation:**

### Key Concepts of Encapsulation

1.  Private Data:

    - Private Access Modifier: Data (attributes) within a class is
      > usually made private, which means it cannot be accessed directly
      > from outside the class. This protects the data from unauthorized
      > access and modification.

2.  Public Methods:

    - Public Access Modifier: Public methods are provided to allow
      > controlled access to the private data. These methods are often
      > called \"getters\" and \"setters.\"

      - Getters: Methods used to retrieve or \"get\" the value of
        > private attributes.

      - Setters: Methods used to set or modify the value of private
        > attributes.

3.  Controlled Access:

    - Encapsulation allows for validation and control over how data is
      > accessed or modified, enforcing constraints and business rules.

### Benefits of Encapsulation

1.  Data Protection:

    - By making fields private and providing public methods to access or
      > modify them, you can protect the data from being changed in
      > unexpected or harmful ways.

2.  Modularity:

    - Encapsulation helps in organizing code into manageable,
      > self-contained units. This makes the code easier to understand,
      > maintain, and extend.

3.  Flexibility and Maintenance:

    - Internal implementation details can be changed without affecting
      > code that relies on the class, as long as the public interface
      > remains consistent.

4.  Ease of Use:

    - Users of a class interact with it through a well-defined
      > interface, making it easier to understand and use the class
      > without needing to know its internal details.

![](media/image37.png){width="5.84375in" height="9.192708880139982in"}

**Clean Code**

**Chapter 1 : Clean Code**

### **1. What is Clean Code?** {#what-is-clean-code}

Martin defines clean code as code that is easy to read, understand, and
maintain. Clean code helps developers work efficiently and minimizes the
risk of bugs. It is not just about following specific rules or patterns,
but about writing code in a way that is clear and expressive.

### **2. Characteristics of Clean Code** {#characteristics-of-clean-code}

- **Readable**: The code should be easily understandable. This means
  > using meaningful names for variables, functions, and classes, and
  > ensuring that the code structure is intuitive.

- **Simple**: Avoid unnecessary complexity. The code should do what it
  > needs to do with the least amount of code possible. This means
  > following the KISS principle---\"Keep It Simple, Stupid.\"

- **Refactorable**: Clean code should be easy to refactor. As
  > requirements change, the code should be adaptable without becoming
  > overly complex.

### **3. The Role of the Developer** {#the-role-of-the-developer}

Martin emphasizes that writing clean code is a skill that developers
must practice. It requires discipline and the willingness to
continuously improve and refactor code. Developers should strive to
write code that others can understand and maintain.

### **4. The Importance of Clean Code** {#the-importance-of-clean-code}

- **Maintainability**: Clean code is easier to maintain and extend. It
  > reduces the cost of fixing bugs and adding new features.

- **Readability**: Code that is easy to read and understand helps team
  > members collaborate more effectively. Clear code helps new team
  > members get up to speed quickly.

- **Efficiency**: While writing clean code may take more time initially,
  > it saves time in the long run by reducing the need for extensive
  > debugging and rework.

### **5. Examples of Clean vs. Dirty Code** {#examples-of-clean-vs.-dirty-code}

Martin provides examples to illustrate the difference between clean and
dirty code. Clean code examples follow best practices such as meaningful
naming, proper organization, and minimal complexity. Dirty code
examples, on the other hand, are cluttered, hard to read, and difficult
to maintain.

### **6. The Importance of Naming** {#the-importance-of-naming}

Effective naming is a key component of clean code. Good names
communicate intent and make the code more understandable. Poor names can
obscure the purpose of the code and make it harder to work with.

### **7. Conclusion** {#conclusion}

Martin concludes that writing clean code is not just a matter of
following a set of rules but involves a mindset and commitment to
quality. Developers should continuously seek to improve their code and
strive for simplicity, clarity, and maintainability.

**Chapter 2 : Meaningful Names**

### **1. The Importance of Meaningful Names** {#the-importance-of-meaningful-names}

Martin emphasizes that meaningful names are crucial because they make
the code more readable and understandable. Good names help convey the
purpose and intent of the code, making it easier for developers to
follow and maintain.

### **2. Choosing Descriptive Names** {#choosing-descriptive-names}

- **Use Intent-Revealing Names:** Names should reveal the intention
  > behind the code. For example, calculateInterest() is more
  > descriptive than calculate() because it specifies what the
  > calculation is for.

> Bad example of Intent-Revealing Names:
>
> ![](media/image58.png){width="3.9270833333333335in"
> height="2.7083333333333335in"}
>
> What does this function do? The name calc does not convey its purpose.
>
> Good example of Intent-Revealing Names:
>
> ![](media/image13.png){width="6.302083333333333in"
> height="2.7083333333333335in"}
>
> The name calculateDiscount reveals that the function computes a
> discount based on price and quantity.

- **Avoid Dispensable Abbreviations:** Abbreviations can be ambiguous
  > and obscure the meaning. Use full words unless the abbreviation is
  > well-known (e.g., URL or HTML). For example, calculateTotalAmount()
  > is preferable to calcTotAmt().

> Bad example of Avoid Dispensable Abbreviations :
>
> ![](media/image14.png){width="4.71875in"
> height="2.7083333333333335in"}
>
> Abbreviations like calcIntAmt, p, and q make the code harder to
> understand.
>
> Good example of Avoid Dispensable Abbreviations :
>
> ![](media/image4.png){width="6.5in" height="2.5416666666666665in"}
>
> Full names like calculateInterestAmount, principal, and years are more
> descriptive.

- **Use Pronounceable Names:** Names should be easy to pronounce. This
  > helps when discussing code with colleagues and can improve the
  > clarity of the code. For example, getCustomerAddress() is better
  > than getCustAddr().

> Bad example of Use Pronounceable Names :
>
> ![](media/image59.png){width="2.96875in"
> height="2.7083333333333335in"}
>
> The name procOrd is not easily pronounceable or descriptive.
>
> Good example of Use Pronounceable Names
> :![](media/image9.png){width="3.40625in"
> height="2.7083333333333335in"}
>
> The name processOrder is easier to pronounce and clearly describes the
> method's purpose.

- **Use Searchable Names:** Names should be easy to search for in the
  > codebase. For example, findUserById() is preferable to getUser()
  > because it specifies the search criteria.

> Bad example of Use Searchable Names :
>
> ![](media/image54.png){width="2.875in" height="2.7083333333333335in"}
>
> The name getUser is vague and does not describe the method's action
> well.
>
> Good example of Use Searchable Names :
>
> ![](media/image40.png){width="4.71875in"
> height="2.7083333333333335in"}
>
> The name getUserIdByEmail makes it clear that the method retrieves a
> user ID based on an email.

### **3. Naming Conventions** {#naming-conventions}

- Class Names: Class names should be nouns or noun phrases that
  > represent the purpose of the class. For instance, OrderProcessor is
  > a good class name because it clearly indicates the role of the
  > class.

- Method Names: Method names should be verbs or verb phrases that
  > describe the action the method performs. For example, processOrder()
  > describes the action being performed.

- Variable Names: Variable names should be descriptive and convey their
  > role. For example, orderDate is better than date because it
  > specifies what the date represents.

### **4. Avoiding Misleading Names** {#avoiding-misleading-names}

- **Avoid Negative Names:** Names that are negative or contain negations
  > (e.g., isNotValid) can be confusing. Instead, use positive names
  > (e.g., isValid).

- **Avoid Ambiguous Names:** Names should be specific and avoid
  > ambiguity. For example, calculateDiscount() is clearer than apply().

### **5. Naming with Context** {#naming-with-context}

- **Context Matters:** The context in which a name is used can influence
  > its clarity. Ensure that names are meaningful within their context.
  > For example, list in orderList is clear because the context is about
  > orders.

> Bad example of Naming with context
>
> ![](media/image16.png){width="6.5in" height="3.638888888888889in"}
>
> Good example of Naming with context
>
> ![](media/image29.png){width="6.5in" height="3.4305555555555554in"}
>
> In the good example, itemsInCart provides additional context about
> where the items are being used. This makes it clear that the list
> represents items specifically in the shopping cart, improving
> readability and understanding of the code.

### **6. Consistency** {#consistency}

- **Consistency in Naming:** Consistent naming conventions throughout
  > the codebase help maintain clarity and reduce confusion. For
  > instance, if you use getUser() for one method, avoid using
  > retrieveUser() for another method that performs a similar function.

### **7. Naming for Readability** {#naming-for-readability}

- **Avoid Encodings:** Do not encode type information in names (e.g.,
  > orderListArray). Instead, focus on the purpose of the variable
  > (e.g., orders).

- **Use Meaningful Comments When Necessary:** If names alone cannot
  > convey the purpose of the code, use comments to provide additional
  > context. However, strive to make names as descriptive as possible to
  > minimize the need for comments.

**Chapter 3 : Functions**

**Function Size**: Functions should be small. The smaller and more
focused a function is, the easier it is to understand and maintain.
Martin suggests that functions should ideally fit on a single screen.

Bad Example of Function Size:

![](media/image35.png){width="6.5in" height="5.166666666666667in"}

Good example of Function Size :

![](media/image27.png){width="6.5in" height="7.375in"}

**Function Names**: Function names should clearly convey their purpose
and what they do. Names should be descriptive enough that the function's
intent is obvious to anyone reading the code.

Bad Example of Function Name:

![](media/image42.png){width="4.28125in" height="2.90625in"}

Good Example of Function Name:
![](media/image8.png){width="4.364583333333333in"
height="3.1041666666666665in"}

**Function Arguments**: Functions should have as few arguments as
possible. Ideally, a function should have zero or one argument. If more
than one argument is needed, consider if the function can be refactored
or if an object could be passed instead.

Bad Example of Function Arguments :

![](media/image6.png){width="6.5in" height="2.0972222222222223in"}

Good Example of Function Arguments :

![](media/image33.png){width="4.71875in" height="4.458333333333333in"}

**Function Behavior**: Functions should do one thing and do it well.
This single responsibility principle helps in keeping functions focused
and predictable.

Bad Example of Function behavior :

![](media/image2.png){width="4.375in" height="3.6875in"}

Good Example of Function behaviour :

![](media/image31.png){width="4.635416666666667in"
height="3.4895833333333335in"}

**Error Handling**: Functions should handle errors gracefully. They
should not just fail silently but should provide meaningful error
messages and ensure that errors do not propagate in a way that disrupts
the system.

Bad example of Error Handling :

![](media/image26.png){width="5.510416666666667in" height="2.90625in"}

Good example of Error Handling :

![](media/image61.png){width="6.5in" height="3.2083333333333335in"}

**Function Side Effects**: Functions should avoid side effects. A
function that changes the state of the system in unexpected ways can be
difficult to understand and debug.

Bad example of Function Side Effects :

![](media/image49.png){width="6.5in" height="2.7083333333333335in"}

Good example of Function Side Effects :

![](media/image18.png){width="6.5in" height="2.138888888888889in"}

**Function Structure**: Functions should be structured so that they are
easy to read and follow. This includes using consistent indentation,
spacing, and comments where necessary.

Bad Example of Function Structure :

![](media/image17.png){width="5.947916666666667in" height="3.875in"}

Good Example of Function Structure :

![](media/image34.png){width="6.5in" height="6.555555555555555in"}

**Function Decomposition**: If a function is doing too much, it should
be decomposed into smaller functions. This makes the code more modular
and easier to test and understand.

Bad example of Function Decomposition :

![](media/image52.png){width="6.5in" height="3.2777777777777777in"}

Good example of Function Decomposition :

![](media/image63.png){width="6.5in" height="4.986111111111111in"}

**Chapter Four : Comments**

**Comments Should Not Be Used to Explain Bad Code:**

- Principle: Comments should not be a crutch for poor code. If the code
  > is clear and well-written, comments should be unnecessary.

- Practice: Refactor code to make it self-explanatory instead of relying
  > on comments to clarify its purpose.

> Bad Example :
>
> ![](media/image12.png){width="6.5in" height="2.4583333333333335in"}
>
> Good Example :
>
> ![](media/image36.png){width="6.5in" height="2.375in"}

**Good Comments Provide Intent and Context:**

- Principle: Use comments to explain why something is done, not what is
  > done. Good comments clarify the intent behind complex or non-obvious
  > decisions.

- Practice: Use comments to explain the rationale behind complex
  > algorithms or design choices.

> Bad Example :
>
> ![](media/image55.png){width="4.458333333333333in" height="2.90625in"}
>
> Good Example :
>
> ![](media/image60.png){width="6.5in" height="2.875in"}

**Avoid Redundant Comments:**

- Principle: Comments that merely restate what the code does are
  > redundant and do not add value.

- Practice: Ensure comments provide additional insights or explanations
  > that are not immediately apparent from the code itself.

> Bad Example :
>
> ![](media/image50.png){width="3.2291666666666665in"
> height="2.5208333333333335in"}
>
> Good Example :
>
> ![](media/image30.png){width="4.71875in"
> height="2.5208333333333335in"}

**Use Comments for Important Information:**

- Principle: Use comments to highlight important information such as
  > assumptions, potential pitfalls, or areas needing future work.

- Practice: Include comments for important notes like TODOs, FIXME, or
  > explanations of specific behaviors.

Bad Example :

![](media/image39.png){width="4.979166666666667in" height="2.90625in"}

Good Example :

![](media/image24.png){width="6.5in" height="2.0416666666666665in"}

**Keep Comments Up-to-Date:**

- Principle: Outdated comments can be misleading and harmful. They
  > should be maintained alongside code changes.

- Practice: Regularly review and update comments as the code evolves to
  > ensure accuracy.

> Bad Example :
>
> ![](media/image56.png){width="6.5in" height="3.2916666666666665in"}
>
> Good Example :
>
> ![](media/image3.png){width="6.302083333333333in" height="3.875in"}

**Avoid Commented-Out Code:**

- Principle: Commented-out code can clutter the codebase and is often a
  > sign of code that should be removed or refactored.

- Practice: Remove unused code rather than commenting it out. If it's
  > important to keep, use version control systems to track historical
  > changes.

> Bad Example : ![](media/image45.png){width="6.208333333333333in"
> height="2.5208333333333335in"}
>
> Good Example :
>
> ![](media/image7.png){width="6.041666666666667in"
> height="2.3229166666666665in"}

**Use Descriptive Headers:**

- Principle: Use comments to provide descriptive headers or section
  > separators in larger files to improve navigation.

- Practice: Include headers for different sections or modules to enhance
  > code readability.

> Bad Example :
>
> ![](media/image65.png){width="4.020833333333333in"
> height="2.5208333333333335in"}
>
> Good Example :
>
> ![](media/image10.png){width="5.072916666666667in"
> height="3.1041666666666665in"}

**Write Comments in a Professional Tone:**

- Principle: Comments should be written in a clear, professional tone
  > and be free of slang or informal language.

- Practice: Use proper grammar and clear language to ensure comments are
  > easily understandable by others.

Bad Example :

![](media/image1.png){width="4.104166666666667in"
height="2.5208333333333335in"}

Good Example :

![](media/image5.png){width="6.5in" height="2.25in"}
