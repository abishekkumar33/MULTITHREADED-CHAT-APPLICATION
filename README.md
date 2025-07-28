# MULTITHREADED-CHAT-APPLICATION
COMPANY: CODTECH IT SOLUTIONS

NAME: ABISHEKKUMAR R

INTERN ID: CT06DH667

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

DESCRIPTION:

Objective:

The objective of this task is to design and implement a basic Client-Server Chat Application in Java that allows multiple clients to communicate with each other in real-time. The goal is to demonstrate core skills in Java network programming, socket handling, and multithreading.

Project Overview:

This project consists of two core components:

Server Program (Server.java)

Client Program (Client.java)

The server listens for incoming client connections using Java’s ServerSocket. For every client that connects, the server spawns a new thread to handle its communication. This ensures multiple clients can send and receive messages concurrently—an essential use case of Java multithreading.

Each client, when started, connects to the server using a Socket, enters a username, and then can send messages to all other connected users. The server broadcasts every message to all active clients using output streams.

Key Features:

Console-based, real-time group chat system

Multiple client handling using Java Threads

Technologies Used:

Java

Socket Programming: ServerSocket, Socket

Multithreading: Thread class

I/O Streams: BufferedReader, PrintWriter, InputStreamReader

Development Environment:

IDE: Visual Studio Code

Java Version: Java 8+

Executed in terminal via Command Prompt using:

javac to compile, java to run server/client programs

OUTPUT

Server

<img width="1919" height="1083" alt="17536994697622718714751475946155" src="https://github.com/user-attachments/assets/ff84e322-5200-4b5e-b3b9-12ce1d768653" />

Client

<img width="1919" height="1048" alt="17536996415511340101551560017017" src="https://github.com/user-attachments/assets/b4f92c5f-66a0-4fbb-bd88-8d0567040571" />
