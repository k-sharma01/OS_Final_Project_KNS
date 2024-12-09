## **Wordsmith_KNS**  

Wordsmith is a multiplayer word game where two players compete to create valid words and earn points. The game features a server-client architecture, real-time gameplay, and a competitive scoring system.  

---

## **Features**  
- **Multiplayer Matchmaking**: Automatically pairs players in a game session.  
- **Letter Assignment System**: Random letters are assigned to players.  
- **Word Validation**: Submitted words are validated against a predefined word list.  
- **Scoring System**: Points are calculated based on letter point values.  
- **Game Over Logic**: The game ends when no more letters are available.  

## **Getting Started**  

### **1. Clone the Repository**  
git clone https://github.com/k-sharma01/Wordsmith_KNS.git
cd wordsmith-game

### **2. Compile the files**
javac *.java

## **How to Run the Game**

### **1. Start the Server**
java Application

### **2. Start the Clients**
Open two terminals and run the WordsmithClient class in both
java WordsmithClient

Both clients should connect to the server, and then you may follow the on-screen instructions to play.
