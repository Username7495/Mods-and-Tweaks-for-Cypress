# Mods-and-Tweaks-for-Cypress
  A collection of a few mods for Minecraft 1.0.16.05_20 Cypress. These include a client mod allowing for easy rebinding of hardcoded keys, and a server mod essentially like bukkit.

## Controls+ 
  A client-side mod that allows to rebind some hardcoded and keys only bindable through the console.
  
<img width="1535" height="958" alt="image" src="https://github.com/user-attachments/assets/47485fdd-4c12-4aad-9297-6498ce95305c" />


## Hmod Cypress
  A bukkit-type modification for Minecraft Alpha allowing for plugins on the server, and better server customization.
  
<img width="858" height="508" alt="image" src="https://github.com/user-attachments/assets/7ec7eb1e-4e21-4a5b-a873-18cac69c96de" />

## MixxitPlugin
  A universal plug-in for Hmod for dealing damage to mobs and players that supports tools, armor, and food.


# Installation Guide
  ## Controls+
  Any and all client mods for Cypress can be installed in two ways, patching the jar and adding to jar (MultiMC/Prism only). Patching the jar will work with any launcher, it requires a computer and 7Zip, WinRAR, or file editor of choice. Adding to the jar can only be done in Multi MC and it's derivatives.

  ### Adding to Jar
  To add to a jar, you will need: A MultiMC based Minecraft launcher, a Cypress instance using the REOBFUSCATED jar and any mods you would like to install.
  
<img width="1536" height="984" alt="image" src="https://github.com/user-attachments/assets/f07ec145-a96e-47c7-a328-72c105b7a9cd" />

(To learn how to install Cypress there is a guide [here](https://alphaver.miraheze.org/wiki/Tutorial:Installing_AlphaVers), and the reobfuscated jar [here](https://github.com/FMG793/1.0.16.05_20-Cypress-Mods-And-Deobfuscated-Code/releases/tag/new))

Then, with the Edit Instance window open, select "Add to Minecraft.jar" and select the mod's zip file

<img width="1536" height="986" alt="image" src="https://github.com/user-attachments/assets/d716de45-ea75-4e64-a3db-4a210b9b7800" />

When complete it should look like the top when using vanilla, and bottom with optipine

NOTE: For optipine, the order matters!

<img width="579" height="158" alt="image" src="https://github.com/user-attachments/assets/3fccd2a9-1384-46b8-9c2f-3d8a5d600209" />

<img width="589" height="228" alt="image" src="https://github.com/user-attachments/assets/48ec73a3-2c15-41be-8c81-770b4673f7d2" />

  ### Patching the Jar (Recommended)
  Patching the jar can be done with any jar, Vanilla, QOL, Reobf, etc. All you need is the mods, the jar, and 7zip/WinRAR. (Default Jar and 7Zip used for demonstration)

  Unzip the contents of the mods, then with 7Z left click the jar and select "Open Archive".

  <img width="987" height="709" alt="image" src="https://github.com/user-attachments/assets/2b85a3ae-2d10-4373-bf3c-f893193c8115" />

  Drag the contents of the zip onto the jar (For optipine, add controls+ and optipine, then controls+ optipine)

  <img width="1262" height="683" alt="image" src="https://github.com/user-attachments/assets/3156c7e4-f620-410b-81db-2f45f27c5b89" />

  Once completed close 7zip and launch Cypress with the patched jar.
  
## Hmod
Hmod can be installed by patching the server jar or can be run via console.

Example: "java -classpath hmod_QoL.jar;ext1605_20_server_QoL.jar -Xmx1024M -Xms1024M Main".

<img width="827" height="542" alt="image" src="https://github.com/user-attachments/assets/22c272d3-e18f-4d4e-8933-2019d66e1155" />

When properly run, it should look like this:

<img width="856" height="512" alt="image" src="https://github.com/user-attachments/assets/407c4a58-df56-44ba-bcf5-88ee3a0efa19" />

### Plugins
In order to use plugins, insert it in the "plugins" folder in the directory where hmod server is located, then add plugins="filename"(without .jar at the end) in "plugins" field in server.properties.

<img width="1413" height="847" alt="image" src="https://github.com/user-attachments/assets/38bb7884-4a92-42d4-b310-7d985cdbb65c" />

If done properly a .properties file would have been made for it in the server folder, and it should appear as loaded in the server window

<img width="1445" height="748" alt="image" src="https://github.com/user-attachments/assets/43381e56-9137-459c-865c-6dbb481bf833" />

## Mixxit
Mixxit is a plugin for Hmod that allows PVP and monsters in a Cypress server.

When playing with Mixxit in a server, note that you must left click to equip armor and eat food, also if your difficulty is set to peaceful monsters will be invisible but will still damage you!

<img width="854" height="480" alt="image" src="https://github.com/user-attachments/assets/4c536ce0-ff5b-48ee-a0e0-12a44e5d5cf8" />
  
  ### How to use
  Mixxit is installed like any other Hmod plugin, you can configure it via its .properties file. Boomers controls Creeper spawning, PVP toggles combat, and drop-inventory controls if inventory is lost on death.
  
  <img width="580" height="397" alt="image" src="https://github.com/user-attachments/assets/d97dd664-ea1f-48f4-8cea-4ff3978c219c" />
  
