# chess-java - Project By Shreyas (43275), Yash (43276) and Harish (43280)

**JavaChess**

**Description:**
JavaChess is a chess game developed in Java, featuring a graphical user interface (GUI) built with Java Swing. It employs Remote Method Invocation (RMI) and a client/server architecture to enable multiplayer functionality, allowing up to 6 players to engage in chess simultaneously.

**How to Run the Program:**

**Step 1:** Install Java Version 8u92 or later (32-bit or 64-bit).

**Step 2:** Navigate to `<this folder>\JavaChess\Server\`.

**Step 3:** Run `JavaChessServer.jar`.

**Step 4:** Navigate to `<this folder>\JavaChess\Client\`.

**Step 5:** Execute 2 or more instances of `JavaChessClient.jar` on any PC(s) connected to the same network as the one running `JavaChessServer.jar`.

**Step 6:** Each client will prompt you to enter an IP address to connect. Input the IPv4 address of the PC running `JavaChessServer.jar` and click "Enter".

**Step 7:** Both clients will open windows displaying hosted game sessions. Click "Join Game 1" on both clients, and they will be able to play chess. To exit or conclude the game, simply close the window or declare victory. You'll then return to the session window, where you can either close the program or initiate another game.

**Note:** If you intend to compile the code yourself, ensure that you place the .png image files in the same folder as `ChessClient.class`, or the program will not execute correctly.
