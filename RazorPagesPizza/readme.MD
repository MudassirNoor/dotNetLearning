# Create web UI with ASP.NET Core

- Create page: 
    > `dotnet new page --name Pizza --namespace RazorPagesPizza.Pages --output Pages`
    - Creates the `Pizza.cshtml` Razor page
    - Creates the `Pizza.cshtml.cs` `PageModel` class
- `@page` directive indicates a Razor page and signifies its capability to handle HTTP requests. Must be the first directive on the Razor page.
- `@model` indicates the model type made available to the Razor page.
- Implement the `Models` and `PizzaService` classes for working with the data.
- Modify Pizza.cshtml.cs file to create the respective handlers and data bindings.
- Modify the Pizza.cshtml file.
- Link to the Pizza page through Page/Shared/Layout.cshtml 