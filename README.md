<p align="center">
<img width="880" src="https://github.com/ashtonland/unity-ecs-snippets/assets/65512990/944e48ba-dcfb-4786-9a86-af2e937c5d3c" />
</p>

<div align="center">
	<h3 align="center">Unity ECS/DOTS Snippets for VSCode</h3>
	<p align="center">
    Write Unity DOTS code faster with Systems, Components, & Jobs Snippets
    <br />
    <a href="https://github.com/ashtonland/unity-ecs-snippets"><strong>See on Github »</strong></a>
   	<br />
  </p>
</div>

## About
Coding in Unity DOTS indroduces new boilerplate that needs to be remembered. From creating components, to shared components, to manged components referencing external resources—just to name a few—there is a lot of repetitive setup code when making each which becomes burdensome. However, this extension provides snippets for creating the boilerplate for most all scripts in Unity DOTS and will continue to expand. Instead of repeatedly typing the same lines 38 line setup for an ISystem with the additional start & stop callbacks, just type "dcsss" and start writting game code in seconds.

## ECS Snippets In Action
<p align="center">
<img width="800" src="https://github.com/ashtonland/unity-ecs-snippets/assets/65512990/664a39c7-59d1-425a-a48b-9f89a82b3f5d" />
</p>

## Snippets
| Command             |      Action      |
| :------------------- | :------------------- |
| dcs       |      Create a Unity DOTS System with the ISystem interface       |
| dcsss |     Create a Unity DOTS ISystem with onStartRunning & onStopRunning callbacks      |
| dcsb |     Create a managed Unity DOTS System with the SystemBase class      |
| dcc |     Create a Unity DOTS unmanaged component (recommended if using blittable types)      |
| dcmc |     Create a Unity DOTS managed component (only if using NON-blittable types)      |
| dcmcer |     Create a Unity DOTS managed component referencing an external resource      |
| dcsc |     Create a Unity DOTS unmanaged shared component (for components used on many entities & with the same values)      |
| dcmsc |     Create a Unity DOTS managed shared component (for shared components using non-blittable types)      |
| dcj |     Create a Unity DOTS Job (no `using Unity.Entities` added with this command, for it is likely added to a System file & not standalone)      |
| dcb       |      Create a Unity DOTS component baker & its authoring monobehavior class       |
| dcbd       |      Create a Unity DOTS component baker referencing another data source (i.e. mesh, gameObject, scriptable obj...)       |
| dca       |      Create a Unity DOTS aspect (used to group related components)       |
| dcrc       |      Create a Unity Physics (the DOTS package) raycast.      |

### Naming Convention
The commands above all begin with dc standing for "Dots Create ..." which means you can always just type dc and use the dropdown to find or read more about any command. For example, `dcsc` stands for Dots Create Shared Component.

## Supported Version of Unity DOTS
- Unity DOTS 1.0.11 (The current production release as of July 2023)

## Contributing
Feel free to open a pr on the github repository any time to create new snippets that you want to see! Also if you are not familiar with creating snippets, open up an issue requesting a new snippet 🤝

## Contributors
<a href="https://github.com/ashtonland">
  <img alt="Ashton Dev" src="https://avatars.githubusercontent.com/u/65512990?v=4" width="80" />
</a> 

