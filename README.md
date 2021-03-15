This is a clean Blazor server-side project with only MudBlazor installed according to https://mudblazor.com/getting-started/installation
Simply changing ASPNETCORE_ENVIRONMENT from "Development" to anything else, will make the Blazor not work and the app won't render correctly. 
I usually don't get an error, but one time I got:
Microsoft.AspNetCore.Components.Server.Circuits.RemoteRenderer: Warning: Unhandled exception rendering component: Could not find 'mudElementRef.getBoundingClientRect' ('mudElementRef' was undefined).
Error: Could not find 'mudElementRef.getBoundingClientRect' ('mudElementRef' was undefined).
at https://localhost:44311/_framework/blazor.server.js:1:67390
