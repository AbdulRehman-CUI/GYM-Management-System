# Gym Management System

## Description
A comprehensive Java-based GUI application designed to streamline gym operations. This system allows gym managers to efficiently manage members, trainers, memberships, and various plans. It provides separate dashboards for administrators, members, and trainers, enabling role-based access to relevant features. Built using Java Swing for the user interface and includes data persistence capabilities.

## Features
- **Member Management**: Register new members, view member details, update profiles, and manage memberships.
- **Trainer Management**: Register trainers, assign roles, and oversee trainer activities.
- **Membership Plans**: Define different membership types with varying durations and benefits.
- **Workout and Diet Plans**: Create and assign personalized workout and diet plans for members.
- **Administrative Dashboards**: Dedicated interfaces for gym managers, members, and trainers with role-specific functionalities.
- **Data Persistence**: Store and retrieve gym data using the GymDataManager class.
- **GUI Components**: User-friendly interfaces built with Java Swing, including tables for viewing data and forms for input.

## Requirements
- Java JDK (version 8 or higher recommended)
- Java Swing library (included in JDK)
- Windows/Linux/Mac OS (compatible with Java)

## How to Run
1. Ensure Java JDK is installed and configured in your system PATH.
2. Navigate to the project directory in your terminal or command prompt.
3. Compile all Java source files:
   ```
   javac *.java
   ```
4. Run the application using the main GUI runner:
   ```
   java RunnerGUI
   ```
   Alternatively, you can run:
   ```
   java GymManagementSystem
   ```
5. The GUI will launch, allowing you to interact with the system.

## Project Structure
- **Core Entities**: 
  - `Person.java`: Base class for individuals.
  - `Member.java`: Represents gym members.
  - `Trainer.java`: Represents gym trainers.
  - `Employee.java`: Base for staff.
  - `GymManager.java`: Manages gym operations.
- **Data Models**:
  - `Membership.java`, `MembershipType.java`: Handle membership details.
  - `WorkoutPlan.java`, `DietPlan.java`: Manage plans.
  - `Goal.java`, `Duration.java`: Supporting classes.
- **GUI Components**:
  - Dashboard classes: `ManagerDashboard.java`, `MemberDashboard.java`, `TrainerDashboard.java`.
  - Registration frames: `RegisterAsMember.java`, `RegisterAsTrainer.java`.
  - Management frames: `MembersTableFrame.java`, `TrainersTableFrame.java`, `DeleteMemberFrame.java`, etc.
  - `ComponentsGUI.java`: Shared UI components.
- **Utilities**:
  - `GymDataManager.java`: Handles data storage and retrieval.
  - `Payable.java`: Interface for payment-related classes.
  - `RunnerGUI.java`: Main entry point for the GUI application.
- **Main Class**: `GymManagementSystem.java`: Core system logic.

## Author
  Abdul Rehman
