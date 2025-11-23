# Installation Methods
  In Cypress there are generally 3 ways for installing mods, patching the jar, adding to jar (exclusive to MultiMC based launchers), and class adding (server only). They have all have thier own use cases.

## Jar Patching
  Jar patching is the universal way of modding as it is supported by any launcher. To start you need a application that can open jars, 7Zip is what is used in any tutorials, and the mods' class files unzipped.
  
  To start, open the jar with 7Zip through Open Archive.

  <img width="987" height="709" alt="image" src="https://github.com/user-attachments/assets/2b85a3ae-2d10-4373-bf3c-f893193c8115" />
  
  Then, drag and drop the class files onto the 7Zip window and copy the files over.

  <img width="1262" height="683" alt="image" src="https://github.com/user-attachments/assets/3156c7e4-f620-410b-81db-2f45f27c5b89" />

  Once completed, install the patched jar as you would regularly for clients, and for servers just run it with the new jar.

  <img width="646" height="898" alt="image" src="https://github.com/user-attachments/assets/156d2477-c7fc-46f4-b386-c6b28fce127d" />
  (Client Image)
  
  ### You're Done!


## Adding to Jar
  Adding to jar is exclusive to MultiMC based launchers, and client mods. It's generally easier to add mods to and update than jar patching.

  First open MultiMC and open the Edit Instance window.

  <img width="1071" height="909" alt="image" src="https://github.com/user-attachments/assets/a8a8c550-e616-41a0-9e5c-4a9d704e019b" />

  Then select Add to Minecraft.jar and select your mods.

  <img width="1477" height="917" alt="image" src="https://github.com/user-attachments/assets/5d17424c-6e97-4336-9d29-ae77b6d3ca93" />

  Finally press "Open" and the Instance window should look like this, now you can run Cypress.

  <img width="1067" height="905" alt="image" src="https://github.com/user-attachments/assets/a947e21d-656a-48e9-94f7-558563e667a6" />

  ### You're Done!

## Class Adding
  Class adding is a modding method exclusive to servers and is the less permanent than jar patching.

  To start open your server folder in cmd.exe.

  <img width="1536" height="985" alt="image" src="https://github.com/user-attachments/assets/86450402-fb24-44e1-9ad3-997f5868da4d" />

  Then, run the server with this template "java -classpath Mod.jar;Server.jar -Xmx1024M -Xms1024M Main". To add more mods add the other mod seperated by a semicolon ex. "java -classpath Mod1.jar;Mod2.jar;Server.jar -Xmx1024M -Xms1024M Main"

  <img width="922" height="547" alt="image" src="https://github.com/user-attachments/assets/fc853cda-5052-44de-87b4-4e285ebd2ad3" />

  Hit enter, and run the server.

  <img width="1350" height="837" alt="image" src="https://github.com/user-attachments/assets/19eebbb0-25f3-4f50-a06a-21f6fc721881" />

  ### You're done!
