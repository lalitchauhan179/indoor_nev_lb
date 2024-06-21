# indoor_nev_lb
 


https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/0cdb9587-17c9-4a33-bd76-5b687de95c56

![labsnew](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/cd3037ca-772f-47d0-bb0e-7ef7b47278a7)
![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/9fd944c5-7a3c-4998-bdba-84c7db04e1df)
OVERVIEW

Step 1: Setup Development Environment
1.	Install Unity:
•	Download and install the Unity Hub from the official Unity website.
•	Create a new Unity project, selecting the appropriate settings for your platform (Android).
•	 ![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/268bcfba-fade-4ce8-9630-66146ee4e556)

2.	Install Visual Studio:
•	Install Visual Studio or Visual Studio Code for writing C# code.
•	 ![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/0f2fca13-b033-425c-ab4c-81b826ec7e55)

3.	Set Up ARCore:
•	Download and install the ARCore SDK for Unity from the Google Developers website.
•	Import the ARCore package into your Unity project.

Step 2: Design Indoor Environment
         
1.	Create 2D MiniMap:
 ![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/26bff52a-ac2c-47e1-8c1b-ece9b23b49c4)

2.	Create 3D Models:
•	Design or import 3D models representing the indoor environment. Include walls, floors, and any significant objects.
•	 
 ![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/fc90519b-b6cc-4c9b-9f39-17c908eb85b7)


![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/53bcda5b-05d2-4bb5-80cb-32b72e34d371)

3.	Set Up NavMesh:

•	Use Unity's NavMesh system to define walkable areas in your indoor space.
•	Bake the NavMesh to generate navigation data.
•	 
![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/a9271bf2-4802-43ab-bf9c-0f47a4319785)


Step 3: Implement Wayfinding Algorithm
1.	Write Wayfinding Code:
•	Create C# scripts to handle wayfinding logic.
•	Utilize Unity's AI NavMesh components and APIs for pathfinding.
•	


Step 4: Integrate ARCore and ARFoundation
1.	Set Up ARCamera:
•	Configure the ARCamera within your scene.
•	Ensure it is set up to use ARCore as the tracking provider.
•	 ![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/3b836a7b-a58d-46fd-9b0e-cfe2318d9bc2)

2.	Implement AR Interactions:
•	Write scripts to handle AR interactions, such as placing virtual markers or arrows for navigation.
•	Use ARFoundation components to interact with the AR environment.

Step 5: Design the User Interface
1.	Create UI Elements:
•	Design UI elements for user input, such as destination selection.
•	Implement a user-friendly interface for interacting with the navigation system.
2.	Integrate UI with Wayfinding:
•	Connect the UI elements with the wayfinding algorithm to set destinations and trigger navigation instructions.
•	 
![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/37082615-616d-405c-a80f-87d450c0fbc9)

Step 6: Test and Debug
1.	Test on Real Devices:
•	Deploy the project to an Android device with ARCore support.
•	Test the application in real-world indoor environments.
•	 ![image](https://github.com/lalitchauhan179/indoor_nev_lb/assets/95102162/7f6dd74b-3545-4217-93e6-606b934e4f72)

2.	Debug and Optimize:
•	Identify and fix any navigation, AR interactions, or performance issues.
•	Optimize the application for a smooth user experience.


