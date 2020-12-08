# UFS Spring Labs

- Accessing Data with **JPA**
  - <https://spring.io/guides/gs/accessing-data-jpa>
    - git clone https://github.com/spring-guides/gs-accessing-data-jpa.git
- Serving Web Content with Spring **MVC**
  - <https://spring.io/guides/gs/serving-web-content>
    - git clone https://github.com/spring-guides/gs-serving-web-content.git


- Web Content with Vaadin
  - https://spring.io/guides/gs/crud-with-vaadin
    - git clone https://github.com/spring-guides/gs-crud-with-vaadin.git



# Build Java Web Apps with VS Code

Source - https://code.visualstudio.com/docs/java/java-tutorial?WT.mc_id=java-0000-ropreddy 

![Greeting from Java](https://code.visualstudio.com/assets/docs/java/java-tutorial/greeting-from-spring.png?WT.mc_id=java-0000-ropreddy)

## Before you begin

Before running and deploying this sample, you must have JDK and Maven on your local development environment. If not, please install them.

Download and install the Java SE Development Kit (JDK), version 8:

[Download JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

> **Note**: The `JAVA_HOME` environment variable must be set to the install location of the JDK to complete this tutorial.

Download Apache Maven version 3 or greater:

[Download Apache Maven](https://maven.apache.org/download.cgi)

Install Apache Maven for your local development environment:

[Install Apache Maven](https://maven.apache.org/install)



## Download and test the Spring Boot app

Clone the [Spring Boot Getting Started](https://github.com/spring-guides/gs-spring-boot) sample project to your local machine. You can clone a Git repository with the **Git: Clone** command in the **Command Palette** (Ctrl+Shift+P). Paste `https://github.com/microsoft/gs-spring-boot.git` as the URL of the remote repository and then decide the parent directory under which to put the local repository. After that, you can open the cloned repository in VS Code.

> **Note**: You can install Visual Studio Code from [https://code.visualstudio.com/?WT.mc_id=java-0000-ropreddy](https://code.visualstudio.com/?WT.mc_id=java-0000-ropreddy) and Git from [https://git-scm.com](https://git-scm.com/).

![Clone Spring Repository](https://code.visualstudio.com/assets/docs/java/java-tutorial/clone-repository.gif?WT.mc_id=java-0000-ropreddy)

After cloning the repo, navigate to the `complete` folder that contains the project which is ready to run. Open any of the Java files in the repository (for example `complete\src\main\java\hello\Application.java`). If you haven't got the Java related extensions installed with your VS Code, you will be prompted to install the Java Extension Pack. Just follow the instruction and install the Java Extension Pack from Microsoft. Reload VS Code after the installation.

![Install Java Extensions](https://code.visualstudio.com/assets/docs/java/java-tutorial/install-extensions.gif?WT.mc_id=java-0000-ropreddy)

Once you have the Extension Pack installed, it will automatically build the project for you (this may take several minutes). You can run the application within VS Code by pressing F5 and selecting the **Java** environment. The Java Debug extension will generate a debugging configuration file `launch.json` for you under a `.vscode` folder in your project. You can see the progress in the VS Code Status Bar and see the final active debug configuration displayed.

![debug configuration in the Status Bar](https://code.visualstudio.com/assets/docs/java/java-tutorial/debugging-status-bar.png?WT.mc_id=java-0000-ropreddy)

You can learn more about how VS Code launches your app at [Launch Configurations](https://code.visualstudio.com/docs/editor/debugging?WT.mc_id=java-0000-ropreddy#_launch-configurations). Press F5 again to launch the debugger.

![Run Spring Boot](https://code.visualstudio.com/assets/docs/java/java-tutorial/run-spring-boot.gif?WT.mc_id=java-0000-ropreddy)

Test the web app by browsing to `http://localhost:8080` using a web browser. You should see the following message displayed: "Greetings from Spring Boot!".

![Greeting from Spring](https://code.visualstudio.com/assets/docs/java/java-tutorial/greeting-from-spring.png?WT.mc_id=java-0000-ropreddy)

## Make a change

Let's now edit `HelloController.java` to change "Greetings from Spring Boot!" to something else like "Hello World". VS Code provide a great editing experience for Java, check out [Editing and Navigating Code](https://code.visualstudio.com/docs/languages/java?WT.mc_id=java-0000-ropreddy#_editing-and-navigating-code) to learn about VS Code's editing and code navigation features.

Simply click the Restart button on the top of the editor to reload the app and see result by reloading the browser.

![Restart Application](https://code.visualstudio.com/assets/docs/java/java-tutorial/restart-application.png?WT.mc_id=java-0000-ropreddy)

## Debug the application

Set a breakpoint in the application source code, and reload your browser to hit the breakpoint.

![Debug Application](https://code.visualstudio.com/assets/docs/java/java-tutorial/debugging.png?WT.mc_id=java-0000-ropreddy)