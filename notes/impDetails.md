### 🌟 1. **Core Pillars of OOD**

These are the foundation:

| Pillar              | Description |
|---------------------|-------------|
| **Encapsulation**   | Bundling data + behavior (methods) in one unit (class). Hides internal details.  
| **Abstraction**     | Focus on *what* an object does, not *how* it does it.  
| **Inheritance**     | One class inherits properties of another (DRY principle).  
| **Polymorphism**    | Same interface, different behaviors. Promotes flexibility.

---

### 🎨 2. **Design Principles (Mental Guidelines)**

These help write clean, scalable OOD code:

| Principle                     | What it means |
|-------------------------------|---------------|
| **SOLID** Principles          | Set of 5 core principles for OOD.  
| **DRY** – Don’t Repeat Yourself | Avoid duplication. Reuse code.  
| **KISS** – Keep It Simple     | Simplicity > Cleverness.  
| **YAGNI** – You Aren’t Gonna Need It | Don’t over-engineer. Build only what's needed.

---

### 🧩 3. **Design Patterns (Reusable Solutions)**

These are proven OOD solutions to common problems:

| Category       | Example Patterns |
|----------------|------------------|
| **Creational** | Singleton, Factory, Builder  
| **Structural** | Adapter, Composite, Decorator  
| **Behavioral** | Observer, Strategy, Command

---

### 🛠 4. **Modeling with UML (Unified Modeling Language)**

UML is like **blueprints** for your design:

- **Class Diagrams** – Show structure (classes, fields, methods, inheritance)
- **Sequence Diagrams** – Show how objects interact over time
- **State Diagrams** – Show state transitions of objects
- **Use Case Diagrams** – Represent user interactions

---

### 🧠 5. **Thinking in Objects, Not Functions**

Instead of:
> "What function should I write?"

You think:
> "What **object** should handle this responsibility?"

This promotes better **responsibility distribution** and **code reuse**.

---

### 🔄 6. **Object Lifecycle Awareness**

- Object **creation** (constructors, factories)
- Object **communication** (method calls, events)
- Object **destruction** (RAII, destructors, garbage collection)

---

### 🧬 7. **Design for Change & Extensibility**

- Anticipate **change** (new features, new requirements).
- Use **interfaces**, **abstract classes**, and **composition over inheritance**.


**Motivation Behind Design Principles**
To improve code quality, reduce complexity, and make systems more maintainable.
Help developers think clearly about software structure before coding.

**Motivation Behind Design Patterns**
To provide tested, proven solutions to common design problems.
To promote reuse of design and reduce the risk of reinventing the wheel.
To offer a common language among developers (e.g., "Let’s use a Factory here").

**Design Patterns are based on Design Principles.**
For example, the Strategy Pattern implements Open/Closed Principle.
The Dependency Injection Pattern supports the Dependency Inversion Principle.

![image](https://github.com/user-attachments/assets/9557b028-d780-440c-8ee8-473d3547cbd9)
