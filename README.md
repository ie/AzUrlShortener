<h1 align="center">IE AzUrlShortener</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-3-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/ie/AzUrlShortener/actions" target="_blank">
    <img alt="GitHub Actions Build Status" src="https://img.shields.io/github/actions/workflow/status/ie/AzUrlShortener/azure-static-web-apps-happy-island-081f53710.yml" />
  </a>
  <a href="https://serverlesslibrary.net/sample/1c809aa2-2d4f-4fee-bc27-0c2c36844ac8" target="_blank">
    <img alt="Azure Functions" src="https://img.shields.io/badge/Serverless%20Library-%E2%9C%94%EF%B8%8Fyes-blue?style=flat&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABkAAAAZCAMAAADzN3VRAAACx1BMVEUAAAAAAAAAAP8Af38AVaoAf78AVaoAbbYAXLkAc7kAZqoAWqUAY7gAZrIAZa4AYKwAY7QAZ7YAZ7MAZ7UAZLMAY7MAZLUAZrIAZLcAY7QAZrIAZLMAZLYAZ7YAZLYAZrcAZbgAZLMAZ7YAZbIAZLQAYrMAY7UAZLUAZLYAZbQAZrcAZbMAZbgAZbQAZrQAZrgAZrcAZbgAaLkAZbUAZbYAZ7YAZbUAZrUAZ7YAZ7cAZbcAZrcAZ7cAZrcAZ7cAZrcAZrcAZbcAZ7YAZ7cAZrcAZrYAZrcAZbYAZrcAZ7cAZrYAZrcAZrcAZ7cAZ7gAZrcAZrcAZ7cAZ7gAZ7gBaLcCaLcDabgEaLYFabUGarQGa7oHarMIbLoKbbsMbrsOb7wPcLwQcb0Rcb0SbawTcr0Xdb4Ydb8Zdr8dc6UeecEfdKQgcqMhe8Eic6IkdqEkfcIndJ4of8MqeJ0rgcQsdpsseZwxhMY2eZQ3iMc7fZI7gJJBjstCfYxGkcxHkcxMh4hNlc5TmM9VioFVmtBYnNFZnNFbndFbntFcntFcntJdn9Jfh3lhodNiodNnpNVopdVsi3Bsp9Ztj3BulXFuqdZuqddwqtd0mG11mG12j2l7mml9kWWGn2KMlluUpVmWpliaqFWpoEeusEivokOz0uq31Ou51eu61uy7pju81+2/2O3BqDfB2u7C2u7C2+7DqTbD2+7EuTrF3O/F3e/G3e/H3e/H3u/ItTbKqzLKuzbL4PDOsjDOvTTW5vTb6vXdwyrgsyPg7ffitCLk7/jm8PjqyCLq8/ns9PrttxrwuBjxuBfyzB3zvBfzzBzz+Pz0uRb1uRX1+fz2+v33+v34+/35uxL5/P36/P77wxP70Bf7/f78yhT8yxT8zBX8zRX8zhX8zxb80Bb8/f79vA/9vQ/9vhD9vxD9wBH9whH9xBL9xhP9xxP9yBOZ2sNJAAAAU3RSTlMAAQECAwQGBwsLDxESFCMlKSovOz1AQkNHSFBRUVFUVVpbW11gYmRlZmdoaWlqbXByc3V5e36AgYOIubrBysvR09XX2drd3ub2+vv7/Pz8/f7+/mxm4TkAAAHCSURBVHgBXcz1U1VBHEDxr90d2N2KLYbYAbZwVAzB7g6xOxS7OzCwu8UQFVtEBUMxWFeeoX+Ee5e5bxg+v56ZI155itesX80nl6STpYJ/EI5uzUplShsKtwVGP4+LexEff7hlQfHy7YKxU6kkrZ+NI7CsG2pj3VLql9YbgZ5lxCraHRjJDKW+an2qzwgg0A6zdQSWvhm/V6nf+tXkWS/nAi0ymFILWJEY0fuuSv6hd8H21wuA0qa0hrXvVzJHqb/6egiwKWERNBfJBxtM4IBSKfpJTEzM8b7rExbTOadUZNunCOj3UH3+6fF49NuZsC5xOT7SaOv3VcBCZSXpPRir3y2rIk1vx4YBS/ZHRh5SynMuBCP0wbE64jfl8clQrC3q39MJGGFno4dXlcqEPzqRmi4kp6yx4XT0UIpJAZgWe3QgMPbjn4M2nLk6hB65RdrDpHtRJu34dn8YMOj85cHgLyJ1gTF3jvTnxod5Trh0xQTKmZIjABh1MXzil30Y86Oc0CazGCWDcOy+OQBXp0JiNcZxbTpe1SVVRr9gmLoZV1df8SoRwOxebuhQRNLIXq8dVnCrGlklnfyVGjZpUD6vuP4DQn3cxeG842QAAAAASUVORK5CYII=" />
  </a>
</p>


Forked from [microsoft/AzUrlShortener](https://github.com/microsoft/AzUrlShortener)

A simple and easy to use and to deploy budget-friendly Url Shortener for everyone. It runs in your Azure (Microsoft cloud) subscription.

Features:
  - Redirect different destination base on schedules.
  - Keep statistics of your clicks.
  - Budget-friendly and 100% open-source.
  - Extensible for more enterprise-friendly configurations
  - Simple step by step deployment.

This uses Azure's [Static Web App](https://learn.microsoft.com/en-us/azure/static-web-apps/overview) (SWA) service to deploy both the FE (Blazor) and BE (Azure Functions) using GitHub Actions.

## Pre-requisites

- Install [Azure Functions Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=windows%2Cisolated-process%2Cnode-v4%2Cpython-v2%2Chttp-trigger%2Ccontainer-apps&pivots=programming-language-csharpswa)
- Install [Azure Static Web Apps CLI](https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-install)
- Access to the `url_shortener` Resource Group within IE's non-prod Azure directory (Engineering Director or Associate Director can grant access)
- Add your user identity to the SWA by following these [steps](https://github.com/microsoft/AzUrlShortener/wiki/How-to-deploy-TinyBlazorAdmin#create-invite-to-add-users-to-the-admin-role)
- Contribution permissions to this repo if you want to make updates


## How To Deploy

This is done through the GitHub Actions [workflow file](https://github.com/ie/AzUrlShortener/blob/main/.github/workflows/azure-static-web-apps-happy-island-081f53710.yml).

It will automatically begin when the main branch either has a commit pushed or a PR has been created/modified.

A `workflow_dispatch` trigger has been set up so that you can manually run a deployment - view [this](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/manually-running-a-workflow) to see how.


### Completed steps

The initial deployment to Azure within the Resource Group has been completed by following the original repository steps to:

1. Deploy the FE TinyBlazorAdmin app. Please read the steps [here](https://github.com/microsoft/AzUrlShortener/wiki/How-to-deploy-TinyBlazorAdmin).
2. Deploy the Azure Function and supported resources. Please read the steps [here](https://github.com/microsoft/AzUrlShortener/wiki/How-to-deploy-your-AzUrlShortener).


## Local Development

This project uses the Admin UI (Tiny Blazor Admin) app by default instead of directly accessing the Azure Function.

**Function App**

1. Create a `local.settings.json` file from `local.settings.example.json` in the root of the Azure Functions project
2. Replace `Values.DataStorage` with the connection string from the Storage Account → Security + networking → Access keys
3. If you want to start just the function app you can run `func start` from the project root otherwise continue the steps below

**Static Web App**

SWA CLI is used to run the FE app and API together - read more [here](https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-overview) about why a SWA CLI emulator is required which will answer many questions including the mock authentication/authorization server. In short - it will proxy requests sent to the local SWA port to the Client (TinyBlazorAdmin) or API (Functions) respective ports and allow us to debug both projects from the same port.

Configuration values are defined in `swa-cli.config.json` so that defining options at runtime aren't required. See the [docs](https://learn.microsoft.com/en-us/azure/static-web-apps/static-web-apps-cli-configuration) for more information on the schema.

For local development:

1. Run `swa start app` command from the repo root
2. Wait for both Azure Function and Blazor to start up and the emulator to launch
3. Access the emulator at `http://localhost:4280/`
4. When logging in with the mock auth flow - ensure you add the value `admin` to `User's roles`

See: https://learn.microsoft.com/en-us/azure/static-web-apps/local-development

### Debugging

Depending on your preference, you can debug in Visual Studio Code, Browser, or Visual Studio.

#### Visual Studio

1. Run `swa start debug` from the repo root
2. In VS press `F5` or the `Start Debugging` icon
   - ⚠️ Ensure your browser to launch the app is Chromium-based. It **will not** work with Firefox. Do this by selecting the dropdown next to the run/debug button
3. Once the browser has launched, you can begin debugging in VS by doing actions that will hit any breakpoints set

#### Browser

1. Run `swa start app` from the repo root
2. In your Chromium-based browser at `http://localhost:4280/` start remote debugging by pressing `Shift+Alt+d`
3. You will see a new tab open with the title `Unable to find debuggable browser tab` to state remote debugging is disabled
4. Enable it by following the instructions based on your browser to enable it
5. A new browser window will open up with the app
6. Close the original browser windows and use this new one
7. Start remote debugging by pressing `Shift+Alt+d`
8. A new tab will open with dev tools and an image of the app
9. Move this tab to a separate window instance to remove the `The tab is inactive` message
10. You can navigate through the `file://` node to set breakpoints on the client-side code and begin the debugging process

**Note**: This debugs the client-side app through the browser but not the API. If you want to debug the API specifically you should run both client/server applications separately. You can do this by following the Visual Studio debugging method.

See: [Debug Blazor WebAssembly with Google Chrome or Microsoft Edge](https://learn.microsoft.com/en-us/aspnet/core/blazor/debug?view=aspnetcore-8.0&preserve-view=true&tabs=visual-studio-code#debug-blazor-webassembly-with-google-chrome-or-microsoft-edge)

#### Visual Studio Code

// TODO

See Microsoft's documentation [here](https://learn.microsoft.com/en-us/aspnet/core/blazor/debug?view=aspnetcore-8.0&preserve-view=true&tabs=visual-studio) for more information.

## How To Use It

AzUrlShortener is an API without admin UI by default. However, for IE we are using the Tiny Blazor Admin app by default and not the API.

### Static Web App
You can access the domain by retrieving the URL from the `URL-Shortener-Admin` SWA resource within Azure Portal.

**Tiny Blazor Admin**

[README.md](./src/Cloud5mins.ShortenerTools.TinyBlazorAdmin/README.md)


![Tiny Blazor Admin looks](/Media/TinyBlazorAdmin.gif)


## Optional steps

- **Azure Storage Explorer** - you can use this tool to access the storage service - please read how to set it up [here](https://github.com/microsoft/AzUrlShortener/wiki/How-to-Use-Azure-Storage-Explorer-as-Admin-Tools-for-AzUrlShortener)


## Notes

The upstream repo uses a dedicated Azure Function resource to access it via. an API. This may be outdated information as Azure SWA Free plan only supports Azure Functions in their Managed APIs (as opposed to Bring Your Own APIs).

That is the reason why we explicitly set the `api_location` in the workflow file.

Source: https://learn.microsoft.com/en-us/azure/static-web-apps/apis-overview


## Future considerations

1. Integrate Application Insights
2. Custom domain
3. Migrate (deprecrated) Microsoft.Azure.Cosmos.Table to Azure.Data.Tables

