# Simulation-of-Telephone-System
YouTube link: https://youtu.be/F1etQqilzbA?si=1r9JcwdPOPe79wpF in nepali.

This project simulates telephone call handling scenarios with two main modes: Lost Call System and Delay Call System.
Project Structure
1. Welcome.java (Main Entry Point)
   
    Purpose: Serves as the launch screen with a telephone background
   
    Features:
   
        Two buttons to navigate to either LostCallSystem or DelayCallSystem
   
        Menu bar with "About Us", "Help", and "Contact Us" options
   
        Visually appealing interface with background image
   
3. LostCallSystem.java
4. 
    Simulation Type: Models lost call scenarios
   
    Key Components:
   
        Tables displaying:
   
            Next call information (From, To, Duration, Arrival Time)
   
            Line status (8 telephone lines with busy/free indicators)
   
            Active calls (up to 3 concurrent calls)
   
            Call counters (Processed, Completed, Blocked, Busy)
   
            System clock
   
            Link utilization (Max Links/Used Links)

5. DelayCallSystem.java
    Simulation Type: Models delayed call scenarios
   
    Key Components:
   
        Similar tables to LostCallSystem but with delayed call handling
   
        Additional queue management for delayed calls
   
        Different algorithms for call processing

Common Features
Menu Bar Functionality

All frames include:

    About Us:
    
        Displays version information and developer credits
        
        Formatted with HTML for better presentation
        
    Help:
    
        Provides user instructions and troubleshooting tips
        
        Organized in sections with clear headings
        
    Contact Us:
    
        Shows support contact information
        
        Includes phone, email, and address details
        
Simulation Mechanics

    Call Generation:
    
        Random generation of calls with varying durations
        
        Automatic replenishment of call queue
        
        Time-based arrival patterns
        
    Visual Indicators:
    
        Color-coded tables for different statuses
        
        Real-time clock showing simulation time
        
        Automatic updates to all display elements
        
Technical Implementation

Core Components

    Swing Framework:
    
        Uses JFrame for main windows
        
        JTables for data presentation
        
        JMenuBar for navigation
        
        JOptionPane for dialog boxes
    
    Simulation Logic:
    
        Timer-based event processing
        
        Priority queues for call handling
        
        State management for lines and calls
        
        Statistical tracking
        
Special Considerations

    Frame Management:
    
        Proper handling of window close operations
        
        Parent-child relationship between Welcome screen and simulation frames
        
        DISPOSE_ON_CLOSE instead of EXIT_ON_CLOSE to maintain application lifecycle

How to Run

    Execute Welcome.java as the main class

    Use the buttons to select simulation mode
    
    Observe the simulation in action
    
    Use menu items for additional information
    
This project demonstrates core simulation concepts while providing a practical example of Swing-based GUI development with proper event handling and state management.
