<h1>Creating New App</h1>

> \>dotnet new webapp -o MyFirstASPApp --no-https -f net7.0

<h3>■Praramenters</h3>
<p>The webApp parameter selects what template to use when creating your app.<br/>
The -o parameter creates a directory named MyWebApp where your app is stored.<br/>
The --no-https flag specifies not to enable HTTPS.<br/>
The -f parameter indicates you're creating a .NET 7 application.<p>

<h3>■Files</h3>
<p>Program.cs contains the app startup code and middleware configuration.<br>
The Pages directory contains some example web pages for the application.<br>
MyWebApp.csproj defines some project settings, such as, .NET SDK version to target.<br>
The launchSettings.json file inside the Properties directory defines different profile settings for the local development environment. <br>
A port number ranging between 5000-5300 is automatically assigned at project creation and saved on this file.</p>
<br/>
<h1>Running App</h1>

> \>cd MyWebApp <br/>
\>dotnet watch

