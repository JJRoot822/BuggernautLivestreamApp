# Buggernaut

In this project, we will be building a bug tracker app in .NET over the course of several livestreams. This app will be built using the following technologies:

 - ASP.NET Core Razor Pages (NOT Blazor)
 - C#
 - Entity Framework Core (For managing our database access code)
 - ASP.NET Core Identity (For individual account authentication)
 - - Visual Studio Community 2022 (IDE)
 - Bootstrap (For styling)

# Livestream 1 - Nov 1, 2024

In this livestream, we did the following in the project:
 - Scaffolded out registration, log in, and log out pages from ASP.NET Core Identity
 - Tore out the HTML code containing the social logins and modified the code to have two div elements for padding so the registration form appears in the center of the screen
 - Added a short link only accessible to screen reader users that jumps the user's screen reader to the main content of the page to improve accessibility.
 - Removed the objects that were only relevant for social logins and other stuff that will not be used from the constructor of the registration page's underlying PageModel, so they are not being injected into the registration page.