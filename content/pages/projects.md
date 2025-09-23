---
content_type: page
description: Projects section includes the sample ideas of creating projects for both
  spring and summer 2005.
learning_resource_types:
- Projects
ocw_type: CourseSection
title: Projects
uid: 90597971-7232-6fbb-a506-09fb4b637498
video_metadata:
  youtube_id: null
---

This course is based on the work of the MIT-African Internet Technology Initiative (MIT-AITI). MIT-AITI is an innovative approach by MIT students to integrate computers and internet technology into the education of students in African schools. MIT-AITI achieves this goal by sending MIT students to three African nations in order to teach both students and teachers through intensive classroom and lab sessions for six weeks.

This course Web site has two major components:

1.  Content from the spring 2005 preparatory seminar offered by the MIT-AITI leadership.
2.  A snapshot of the MIT-AITI summer 2005 program in Kenya.

Project information for the summer 2005 session is included below.

Summer 2005
-----------

### MIT-AITI Kenya 2005 Strathmore University Self-Learning Initiative (OCW): Final Project

Overview

OCW students will design and implement a final project individually or with a team of up to five people. You will both submit a design proposal and will present a live demonstration of your project to the class. You may also collaborate between teams and work on different components of a larger project, although each team must still present their component individually.

This is an open-ended project and we encourage you to be creative and to try and tackle a challenging problem. Some sample project ideas are listed below. You may approach this problem as if you are developing a commercial product and will be demonstrating it to potential customers. The more useful the software, the better you present it, and the more working functionality has, the more likely you will sell the software. If it is an experimental or theoretical project, you may treat it as something you would present at an academic conference.

You may either implement an entirely new design, or build on an existing open source Java® project. You should use any available resource and may integrate any code that is available under an open source or free license like GNU or Creative Commons. Sites like {{% resource_link "a70f50d6-e119-4174-9a21-01c1090c55a7" "SourceForge" %}} have literally thousands of projects available for download. This might be a good place to start for motivation and source code examples. You should consider posting your own project on SourceForge under an open source license following the course. We may also ask your permission to post some of the best projects on MIT's OpenCourseWare or AITI Web sites.

It is acceptable if you do not achieve all the goals stated in your proposal. Part of the experience is learning how to plan software projects, gauge your own productivity, and coping with inevitable problems. That being said, we expect you to push yourself and produce a significantly complex, interesting, and useful project. Working intensely to ship code before a tight deadline is part of the software development business. You will have an entire week of lab time to work on the project and should be able to implement a fairly complex design.

Important Dates

*   Session 21 - Submit a project proposal.
*   Session 22 and 23 - Meet with staff to review your proposal.
*   Session 29 - Present a live demonstration of your project to the class.

Project Proposal

Your project proposal is mostly for your own benefit, although we will meet with you to discuss it. The act of writing it should help you design and plan your project. Include a brief summary of what your project is and what it is supposed to do. Describe how you are going to tackle the problem. This should include a timeline with goals and milestones. If you are working with a team, describe how your team will divide the work. If you are collaborating with other teams, describe how you will coordinate with them. Describe what computing resources you will need, such as special network or server access.

Include contingency plans in your design document and try to anticipate problems ahead of time. For example, what if a team member fails to deliver their code or do their share of the work? What if a required server is down for your code demo? What if someone accidentally deletes the latest version of the code? How will your team members concurrently work on source code? Think these through and briefly address how you will address these issues in your design proposal.

Project Demonstration

Your project demonstration can be of any format or length you'd like, but should try to make it as professional and polished as you can. Act as if you're trying to convince someone to buy this project. Tell us how much time you want for your demonstration and what resources you need in advance.

You may either copy your code to run on our laptops and use our projector, or can demonstrate your code in the labs. You may wish to include a PowerPoint presentation. We may be able to set up a wireless network among our laptops if needed (see note on network projects below).

Design Advice

Try to focus on first getting at least one main feature or core functionality working so you have something to demonstrate to the class. Then start focusing on getting additional functionality working before the presentation.

The project proposal should include a brief API. It is advised that you try not to go into too much detail or make this too complex, because it will most certainly change as you work on your project. It's recommended that you use Java's® built-in _javadoc®_ support to automatically generate HTML APIs.

Try to design your project as modularly as possible, so team members can work as independently as possible. You may wish to design your modules as Java® packages, since it's a convenient way of organizing code. Try to design each module so that it can be independently tested and debugged. Figure out the dependencies between modules and try to plan your project so that the whole team does not get stuck waiting for some core module to be finished. If necessary, you can implement skeleton modules until the real code is implemented.

Network Access Issues

Strathmore has a very restrictive network access policy that only allows HTTP traffic through a proxy. We are working on making sure you can set up servers and open arbitrary network sockets, however cannot guarantee that you will be able to. Take this into account if you plan on doing a networked project. You may need to write classes to run clients and servers on a single machine and simulate network access.

Sample Project Ideas

These are just sample ideas to give you an idea of the depth of project that you can probably design in a week. You should feel free to do any of these ideas, or choose one of your own.

*   Games - Invent something fun. See {{% resource_link "6bcf7dfe-d2e5-4c79-bb97-b8517eccf9de" "Game Play" %}} for motivation.
*   Social Networking - Design a stand-alone or Web-based version of a social network site like Friendster®, MySpace®, or Orkut®.
*   Photo Browsing Software - Design an application to view and organize a collection of photos, like iPhoto® or similar applications.
*   Peer-to-Peer File Sharing - Design a peer-to-peer file network, or implement a client for an existing application like BitTorrent. (See existing Java® BitTorrent applications.)
*   Messaging Software - Design a chat-room or instant messaging application.
*   Enhanced Shell - Design a command-line interface (CLI) shell that offers more functionality than an OS's native shell. For example, something more powerful and useful than Window's® DOS shell.
*   Hybrid GUI/CLI Shell - Design a hybrid GUI/CLI shell that shows both a graphical representation of the directory structure as well as a command prompt.
*   Simulation Software - Model and simulate some complex system, e.g. biological, sociological, or physical systems.
*   Sport Statistics Analysis - Analyze sports statistics to produce rankings or betting predictions. Test your model against past real-world data.
*   Financial Analysis - Analyze stock market or financial data or model financial systems. (_Talk to TA if you're interested in this and want some ideas._)
*   Online Shopping or Auction Site - Like Amazon.com® or EBay®.
*   Database Management Tools - Interface with MySQL® or some other DBMS.

### MIT-AITI Kenya 2005 Strathmore University Regular Track: Final Project

Sudoku is a Japanese puzzle game that has recently become quite popular in England. The puzzle board is a 9x9 grid. There is only one rule to solving the puzzle:

*   Fill in the grid so that every row, every column, and every 3 x 3 region contains the digits 1 through 9.

Puzzles start out with a number of cells called **givens** that are already filled in and cannot be changed. Here is a sample Sudoku puzzle:

{{< resource 06368769-be39-578c-c2f2-c685dd367729 >}}

Sample Sudoku puzzle. (Image by MIT OpenCourseWare.)

A filled-in row must have one of each digit. That means that each digit appears only once in the row. For example, the above puzzle's top row could be filled in as:

{{< resource 7f737bfe-260d-ad40-3f56-3a0be3b2a032 >}}

Sudoku sample puzzle's top row. (Image courtesy of MIT-AITI Kenya 2005 team.)

Similarly, each digit must appear in a filled-in column exactly once. The first column could be filled as is shown below:

{{< resource d038662e-813a-f3a2-c429-8fdfe7c2c099 >}}

Sudoku sample puzzle's first column. (Image courtesy of MIT-AITI Kenya 2005 team.)

There are nine 3x3 boxes, or **regions** surrounded by thick lines that must contain each digit exactly once. The top-left region could be filled as:

{{< resource 53349611-0386-705e-5773-a82e44787a65 >}}

Sudoku sample puzzle's top-left region. (Image courtesy of MIT-AITI Kenya 2005 team.)

Note that these example values may not be consistent with the actual solution. Try to solve it for yourself. Designing good puzzles is an art. Properly formed puzzles have exactly one solution and often the givens are presented in a symmetrical pattern. Badly designed puzzles could have many solutions or none at all.

Your Assignment

For this final project, you will take the provided source code and implement the missing functionality. The missing functionality will be noted by "/\* TODO: … \*/" comments in the code. You should try to implement as much of this functionality as possible. Each piece of missing code can be implemented independently of the others, so you may proceed in any order.

For more information on Sudoku:

{{% resource_link "c2e8f932-9ba8-49f9-bb5d-17f763736055" "Sudoku" %}}

{{% resource_link "3ae524c7-9162-406d-9f66-b2c913c2e518" "Wikipedia: Sudoku" %}}

{{% resource_link "212d1d10-ff8b-4b1d-bd92-22a210203cda" "Sudoku List" %}}

Happy hacking!

Sudoku Supporting Files and Documentation ({{% resource_link 9fffdc5f-66bc-53c6-4fba-c2d1b320977c "ZIP" %}}) (The ZIP file contains: 7 .java files, 17 .class files, 72 .html files, 1 .css file, and 1 .gif file.)

### MIT-AITI Kenya 2005 Alliance High School: Final Project

This project will test your practical Java® programming and design skills. You are provided with a project specification and must implement a solution. Your project solution will be graded on whether it meets the specified functionality, as well as its organization and clarity. Someone else should be able to run your code and properly interact with it.

Partial credit will be given. It is recommended that you first write empty methods that return null or zero values before implementing the actual functionality. Your code should be properly commented and formatted. Put a brief comment at the top of each method explaining what you are trying to do. This will be especially helpful for partial credit if your program does not compile. It gives us an idea of what you are trying to accomplish. But please try to make sure your program compiles at the very least.

Problem Motivation

You are asked to create a small database for a Football team, make an ArrayList that contains information of players (in other words, each element within the list is a FootballPlayer object), and have this information accessible/editable through a GUI (Graphical User Interface). For this, you will design a **FootballPlayer** class and a **GUI** class used to implement the methods and interact with the user.

FootballPlayer Class

Write a **FootballPlayer** Class. This class should have the player's name, player's jersey number and salary (in KShs). These fields should be accepted as arguments in the constructor. The **FootballPlayer** class should include a **getName**, a **getNumber** and a **getSalary** method which return the name, the number, and the salary of the player, respectively. You should implement two more **methods** of your choice. For example, a **setPosition** method.

GUI Class

Write a **GUI Class**. This class should keep track of the players that are on the roster. It should also have an **addPlayer** method which adds a player to the roster. It should also have a **removePlayer** method which is given a player name and deletes this player from the roster. If you would like, you may do this all in a separate **Roster class** and only have the following in the **GUI** class.

In this class, design the constructor to be a GUI to facilitate the addition and removal of players from the roster. Your GUI should have an "Add Player" button, a "Remove Player" button and a "Show Roster" button. These buttons should be found in one JPanel where as the other JPanel should have a JTextArea to show output.

When the "Add Player" button is clicked, the program should pop up a window to ask the user for a player name and after that is given, another window to ask for a player salary. These shall be used to instantiate this player and add him/her to the roster. You may use JOptionPane.showInputDialog(String) method for this.

When the "Remove Player" button is clicked, the program should ask the user for a player name, go through the roster and eliminate the requested player.

When the "Show Roster" button is clicked, the program should display the roster on a JTextArea. This means that the player, jersey number, salary and any other information should be displayed.

Useful Code Hints

*   To set the String answer to whatever the user inputs, you can do:  
    String answer = JOptionPane.showInputDialog("How are you?");
    *   This will show a pop-up window with the question, "How are you" and then the String answer will be set to whatever the user enters.
*   Make sure you look at the different available layouts for the content pane
*   To convert from a string to an integer, do the following (this will be useful for converting a String input to an integer and the same can be done with a double-Double.parseDouble(String))
    *   String num = 9;
    *   int jerseyNUm = Integer.parseInt(num);
*   Please use the API found on the JavaDocs® loaded on some computers. To use API
    *   Select API and Language at the top of the page
    *   Select Java® 2 Platform Specification (first link)
    *   You can then use the left-hand menu to select the class of interest