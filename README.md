# 📚 C++ Modules Overview - CPP00 to CPP04

A comprehensive journey through **Object-Oriented Programming** fundamentals using **C++98 standard** at **42 School**.

---

## 🎯 Learning Path Summary

This repository contains implementations for the first five C++ modules, each building upon previous concepts to create a solid foundation in modern C++ programming and object-oriented design principles.

---

## 📦 Module Breakdown

### 🔰 [CPP00 - Basics of Object-Oriented Programming](https://github.com/phlvnhalime/CPP00/blob/master/README.md)

**Core Concepts:** Introduction to C++ syntax and basic OOP
- **Classes & Objects** - First steps into OOP
- **Member Functions** - Encapsulation basics  
- **I/O Streams** - `std::cout`, `std::cin` usage
- **Namespaces** - Code organization
- **Orthodox Canonical Form** - Introduction to proper class design

**Key Projects:**
- `Megaphone` - String manipulation and basic I/O
- `PhoneBook` - Classes, data encapsulation, formatting
- `Account` - Interface implementation from logs

**Skills Gained:** C to C++ transition, basic class design, proper I/O handling

---

### 🧠 [CPP01 - Memory Allocation, Pointers, References](https://github.com/phlvnhalime/CPP01/blob/ac289c82e9a7b68357e3625414912cec6ea31665/README.md)

**Core Concepts:** Advanced memory management and C++ specific features
- **Dynamic Memory** - `new`/`delete` operators
- **Stack vs Heap** - Memory allocation strategies
- **References** - Alternative to pointers
- **Pointers to Member Functions** - Advanced function handling
- **File I/O** - Stream-based file operations

**Key Projects:**
- `Zombie` classes - Memory allocation comparison
- `HumanA/HumanB` - References vs pointers design patterns
- `Harl` - Function pointers for clean architecture
- File replacement tool - String manipulation without STL

**Skills Gained:** Memory management, reference semantics, function pointers, file handling

---

### ⚙️ [CPP02 - Operator Overloading & Orthodox Canonical Form](https://github.com/phlvnhalime/CPP02/blob/master/README.md)

**Core Concepts:** Making custom classes behave like built-in types
- **Orthodox Canonical Form** - The "Big Four" (Constructor, Copy Constructor, Assignment Operator, Destructor)
- **Operator Overloading** - Natural syntax for custom types
- **Fixed-Point Arithmetic** - Alternative to floating-point
- **Ad-hoc Polymorphism** - Function overloading
- **Copy Semantics** - Deep vs shallow copying

**Key Projects:**
- `Fixed` class - Complete numeric type implementation
- Full operator set - Arithmetic, comparison, increment/decrement
- Stream insertion operator - Custom output formatting
- BSP algorithm - Practical geometric application

**Skills Gained:** Operator overloading mastery, proper copy semantics, numeric type design

---

### 🏗️ [CPP03 - Inheritance](https://github.com/phlvnhalime/CPP03/blob/master/README.md)

**Core Concepts:** Code reuse and hierarchical relationships
- **Class Inheritance** - "is-a" relationships
- **Constructor/Destructor Chaining** - Proper initialization order
- **Protected Access** - Controlled inheritance access
- **Method Overriding** - Customizing inherited behavior
- **Code Reusability** - DRY principle through inheritance

**Key Projects:**
- `ClapTrap` hierarchy - Base combat mechanics
- `ScavTrap` & `FragTrap` - Specialized robot classes
- Different stats and abilities - Inheritance customization

**Skills Gained:** Inheritance design, constructor chaining, method overriding, hierarchical thinking

---

### 🎭 [CPP04 - Subtype Polymorphism & Abstract Classes](https://github.com/phlvnhalime/CPP04/blob/master/README.md)

**Core Concepts:** Runtime polymorphism and advanced OOP patterns
- **Virtual Functions** - Dynamic dispatch mechanism
- **Subtype Polymorphism** - Objects treated through base interface
- **Abstract Classes** - Pure virtual functions
- **Virtual Destructors** - Proper cleanup in inheritance
- **Deep Copy Management** - Safe copying with dynamic memory

**Key Projects:**
- `Animal` hierarchy - Virtual function demonstration
- `Brain` system - Deep copy and memory management
- Abstract `Animal` - Pure virtual function implementation
- Polymorphic containers - Runtime type resolution

**Skills Gained:** Virtual functions, polymorphic design, abstract classes, advanced memory management

---

## 🛠️ Technical Standards

### **Compilation Requirements**
```bash
c++ -Wall -Wextra -Werror -std=c++98 *.cpp
```

### **Design Principles Applied**
- **Orthodox Canonical Form** - Proper resource management
- **RAII** - Resource Acquisition Is Initialization
- **DRY** - Don't Repeat Yourself
- **SOLID** - Object-oriented design principles
- **Memory Safety** - Leak prevention and proper cleanup

### **Forbidden Elements**
- ❌ STL containers (until CPP08)
- ❌ C++11+ features
- ❌ External libraries
- ❌ C-style functions (`*printf`, `*alloc`, `free`)

---

## 📈 Progressive Learning Curve

```
CPP00: Basic Syntax → Classes → Objects
  ↓
CPP01: Memory Management → References → Advanced Features  
  ↓
CPP02: Operator Overloading → Copy Semantics → Custom Types
  ↓
CPP03: Inheritance → Code Reuse → Hierarchical Design
  ↓
CPP04: Polymorphism → Virtual Functions → Abstract Design
```

---

## 🎓 Skills Mastered

### **Fundamental Concepts**
- **Object-Oriented Programming** - Encapsulation, Inheritance, Polymorphism
- **Memory Management** - Stack, heap, RAII principles
- **Class Design** - Proper interfaces and implementations
- **Copy Semantics** - Deep vs shallow copying strategies

### **Advanced Techniques**
- **Operator Overloading** - Natural syntax for custom types
- **Virtual Functions** - Runtime polymorphism
- **Abstract Classes** - Interface design patterns
- **Function Pointers** - Flexible function dispatch
- **Reference Semantics** - Efficient parameter passing

### **Best Practices**
- **Orthodox Canonical Form** - Standard class structure
- **Virtual Destructors** - Safe inheritance hierarchies
- **CONST Correctness** - Immutability where appropriate
- **Memory Leak Prevention** - Proper resource management
- **Code Organization** - Header guards, separation of concerns

---

## 🏆 Project Highlights

| Module | Standout Project | Key Learning |
|--------|------------------|--------------|
| CPP00 | PhoneBook | Class design & data encapsulation |
| CPP01 | Harl 2.0 | Function pointers & clean architecture |
| CPP02 | Fixed-point class | Complete operator overloading |
| CPP03 | ClapTrap hierarchy | Inheritance & specialization |
| CPP04 | Animal polymorphism | Virtual functions & abstract design |

---

## 🚀 What's Next?

These modules provide the foundation for:
- **Advanced Design Patterns** (Strategy, Factory, Observer)
- **Template Programming** (Generic programming)
- **STL Mastery** (Containers, algorithms, iterators)
- **Exception Handling** (Error management strategies)
- **Modern C++** (Smart pointers, RAII, move semantics)

---

## 📝 Personal Growth

This C++ journey transformed my understanding of:
- **System-level programming** with high-level abstractions
- **Memory management** as a core programming skill
- **Object-oriented design** for scalable software architecture
- **Code organization** for maintainable projects
- **Problem-solving** through proper abstraction

---

## 🔗 Repository Structure

```
cpp-modules/
├── CPP00/          # OOP Basics & Introduction
├── CPP01/          # Memory & References
├── CPP02/          # Operators & Canonical Form
├── CPP03/          # Inheritance
├── CPP04/          # Polymorphism & Abstract Classes
└── README.md       # This overview
```

---

**Author:** Halime Pehlivan.  
**School:** 42 Heilbronn  
**Standard:** C++98  

*"The journey from procedural C to object-oriented C++ - mastering the fundamentals that make great software possible!"* 🚀
