# Robocode with .NET
The Robocode wiki has some pretty good information on creating a Robocode robot using .NET.
But it is a bit lacking in some of the set up information.
The goal of this README is to augment that information.
You can find the Robocode setup instructions [here](), but make sure to do the steps in this README _before_ continuing the rest of the instructions from Robocode.

## Install Java
The Robocode setup instructions mention installing Java, but don't give any additional details.
Oracle doesn't make it easy because they want you to sign up for an Oracle account in order to download Java.
If you don't want to create an Oracle account you can download the 64-bit version of JDK 8 for Windows directly [here](https://download.oracle.com/otn-pub/java/jdk/8u281-b09/89d678f2be164786b292527658ca1605/jdk-8u281-windows-x64.exe).

You may want to add the Java bin directory to your path (to make installing the jar files in the next section easier).
If you use the default install location, the directory you will want to add to your path is `C:\Program Files\Java\jdk1.8.0_281\bin` (or something similar if you install a different version of Java).

## Install Robocode and .NET Plugin
The Robocode setup instructions mention installing Robocode and the .NET plugin.
If fails to mention that the version of Robocode and the version of the .NET plugin have to match.
At the time of this writing, the latest version of the .NET plugin is 1.9.3.3.
You can download that version of the plugin and the matching version of Robocode [here](https://sourceforge.net/projects/robocode/files/robocode/1.9.3.3/).

Install Robocode before installing the plugin. Install Robocode by running the following command: `java -jar robocode-1.9.3.3-setup.jar`.
You may also be able to double click on the jar file.
To install the plugin, run the following command: `java -jar robocode.dotnet-1.9.3.3-setup.jar`.

## Install Visual Studio
The Robocode setup instructions mention Visual Studio 2005 and 2008, but the instructions work with the latest version of Visual Studio 2019.
You can download the latest version of Visual Studio 2019 [here](https://visualstudio.microsoft.com/vs/community/).
According the the setup instructions, the .NET plugin will _not_ work with Mono.
Presumably it also will _not_ work with .NET Core, but you're welcome to experiment with that if you want to.