# Experiment-04-RMI-Calculator
Java RMI
A Java Remote Method Invocation (RMI) practice project.

🎯 Objective
Learn how a Java program can invoke methods on an object running in another Java process.

🧠 Concepts
Remote interfaces and remote methods
Remote and RemoteException
UnicastRemoteObject, if used
RMI server and client
Registry lookup and service binding
▶️ Running the Project
The exact commands depend on the classes and package names in this folder.

Compile the Java source files.
Start the RMI registry if the implementation requires a separately started registry.
Start the server.
Start the client in a separate terminal.
Example command pattern for a simple, package-free project:

javac *.java
Then run the actual registry, server, and client classes specified by the source code. Do not assume class names without checking the files.

⚠️ Troubleshooting
Ensure the client and server use matching remote interface definitions.
Confirm the registry port and host configuration.
Check firewall and network settings if using different machines.
Keep all required classes on the classpath.
📌 Notes
Replace this generic run sequence with exact commands after confirming the source filenames and package structure.
