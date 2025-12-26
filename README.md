--------------------------------------------------------------------------------------------------------------------------
# NASSCOM-Packaging-Fundamentals_of_Design_and_Testing - 2025

Semiconductor - Packaging Workshop: Fundamentals and Testing Workshop
-------------------------------------------------------------------

1. Packaging Evolution: From Basics to 3D Integration:
   ---------------------------------------------------

   - 1 - Introduction To Semiconductor Packaging And Industry Overview

   - 2 - Understanding Package Requirements And Foundational Package Types

   - 3 - Evolving Package Architectures - From Single Chip To Multi-Chip Modules

   - 4 - Interposers Re-distribution Layers And 2.5D/3D Packaging Approaches

   - 5 - Comparative Analysis And Selecting The Right Packaging Solution

2. From Wafer to Package: Assembly and Manufacturing Essentials:
   ---------------------------------------------------

   - 1 - Setting The Stage - Supply Chain And Facilities

   - 2 - Wafer Pre-Preparation - Grinding And Dicing

   - 3 - Wire Bond Packaging - Die Attach To Molding

   - 4 - Flip Chip Assembly - Bump Formation And Underfill

   - 5 - Wafer Level Packaging And Conclusion
     

3. Labs: Thermal Simulation of Semiconductor Packages with ANSYS:
    -------------------------------------------------------------
      
   - 1 - Introduction And Getting Started With ANSYS Electronics Desktop

   - 2 - Setting Up A Flip-Chip BGA Package

   - 3 - Material Definitions And Thermal Power Sources

   - 4 - Meshing And Running The Thermal Analysis

   - 5 - Viewing Results And Exploring Other Package Types
     

- Setting up new ICEPACK Project <img width="1916" height="851" alt="image" src="https://github.com/user-attachments/assets/85d1b75b-5c34-4428-b807-837751797459" />

- Setting up new FLIPCHIP_BGA Project <img width="1918" height="885" alt="image" src="https://github.com/user-attachments/assets/6b3d026f-6eb0-4275-9e48-c52439249c54" />

  * Complete Package <img width="1918" height="885" alt="image" src="https://github.com/user-attachments/assets/4da66f30-8d2e-4c45-ab87-f735ff35aa28" />
  * Die <img width="1919" height="885" alt="image" src="https://github.com/user-attachments/assets/68bc8c23-c1ab-46e2-8278-d87a79bb373c" />
  * Via - That connect from Die to Substrate <img width="1919" height="887" alt="image" src="https://github.com/user-attachments/assets/39c0d01b-1695-4123-a689-33537a73fd35" />
  * Undefill - That is between Die and substrate <img width="1919" height="884" alt="image" src="https://github.com/user-attachments/assets/3715c1f0-f82a-4fee-9e1f-4454ca3170e6" />
  * Substrate <img width="1919" height="880" alt="image" src="https://github.com/user-attachments/assets/70e53aef-64df-4cb4-98c1-930320d4ac35" />
  * Ball Grids - That is bottom of substrate, that is used to connect on a board such as PCB's <img width="1919" height="880" alt="image" src="https://github.com/user-attachments/assets/5b70bfc5-0ace-4e2e-b8ed-7ae3955ebb82" /> <img width="1917" height="890" alt="image" src="https://github.com/user-attachments/assets/03d6aa41-de04-43c7-b52a-d08fff1e64aa" />

- Thermal Conditions setup - For the die Source(1 Watt) <img width="1919" height="879" alt="image" src="https://github.com/user-attachments/assets/4130a088-70e3-424d-bced-b76b39b724cb" />
  - Source bondary condition setup on substrate(Temperature of substrate) <img width="1919" height="882" alt="image" src="https://github.com/user-attachments/assets/6aacb97c-ea95-44f8-b246-d6c2502d0c29" />

- Assigning temperature Monitors for Substrate, Die and Underfill(Die) <img width="1915" height="866" alt="image" src="https://github.com/user-attachments/assets/6be9a275-ebe8-4ce2-a42f-b0091db5da4a" />

- Start and Generate Meshing <img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/5bfed38d-b742-447d-8125-b8a4c7ec0132" />

- Setting Analysis and then Run validate(validating) and Run Analyze All <img width="1914" height="935" alt="image" src="https://github.com/user-attachments/assets/41b1baa8-ecc5-406d-aa30-0317a34fd7cc" />
  - After simulation complete, to plot the field, select whole package... <img width="1919" height="967" alt="image" src="https://github.com/user-attachments/assets/abbfe836-d735-452b-840f-46d0b5d29841" /> <img width="557" height="418" alt="image" src="https://github.com/user-attachments/assets/8e16256d-e9f3-49b1-abab-dc82581bf3cf" />

- Temperature Analysis Results <img width="1919" height="931" alt="image" src="https://github.com/user-attachments/assets/9941de08-4f12-4e57-8b89-33368810b48d" /> <img width="1918" height="937" alt="image" src="https://github.com/user-attachments/assets/6155313f-48aa-4e0a-a305-d1058024dd76" />

4. From Wafer to Package: Assembly and Manufacturing Essentials:
    ------------------------------------------------------------

   - 1 - Introduction to Package Testing and Electrical Functionality Checks

   - 2 - Reliability and Performance Testing of Semiconductor Packages


5. Package Design ans Modelling: Building a Semiconductor Package from Scratch
   -----------------------------------------------------------------------------
   
   - 1 - Introduction to Package Cross-Section Modelling in ANSYS Electronics Desktop (AEDT)

   - 2 - Creating the Die and Substrate in AEDT

   - 3 - Adding Die Attach Material and Bond Pads
     
   - 4 - Wire Bond Creation and Material Assignment

   - 5 - Applying Mold Compound and Finalizing the Package Model

  
- Setting up new package from stratch, Setting up a Q3DDesign project <img width="1919" height="814" alt="image" src="https://github.com/user-attachments/assets/a9b21de2-34ad-44b9-898d-795db05b5af7" />
- Creating a die (3mm x 3mm) with thickness of 0.2mm (silicon material )<img width="1919" height="819" alt="image" src="https://github.com/user-attachments/assets/f56273d0-c629-4d34-9760-adfbf064b3c7" />
- Creating a substrate with thickness of 0.5mm(with proper axis's) <img width="1910" height="815" alt="image" src="https://github.com/user-attachments/assets/9c55d84d-572b-4be6-b00a-e0f64a36804d" />
- Creating space b/w Die and substrate of 0.1um to add die-attach material <img width="1919" height="823" alt="image" src="https://github.com/user-attachments/assets/835479ee-593c-4e3a-bf3a-7c871effb6b0" />
  - Adding die attach material <img width="1909" height="818" alt="image" src="https://github.com/user-attachments/assets/12174707-4062-499a-b563-b46f04e3c01e" />
- Creating Bondpads on Substrate and Die with 0.005um thickness <img width="1916" height="822" alt="image" src="https://github.com/user-attachments/assets/11f122ae-678a-4ba7-a040-10c5b94a337e" />
- Connecting the Bondpads with Bondwire <img width="1919" height="814" alt="image" src="https://github.com/user-attachments/assets/c2bb4a46-f664-40b6-ad88-e6ea89990ec6" />
- Completing the package
  - Die <img width="1919" height="815" alt="image" src="https://github.com/user-attachments/assets/a95994dc-a460-4ee4-8eb6-5adb4c1ad43a" />
  - Die-attach <img width="1919" height="815" alt="image" src="https://github.com/user-attachments/assets/a961e4b0-66a0-4ef6-b939-6a536acbadf7" />
  - Substrate <img width="1919" height="814" alt="image" src="https://github.com/user-attachments/assets/0c5f91e2-8bd5-4175-8c84-b7530b9dd2b2" />
  - Die bondpads <img width="1918" height="815" alt="image" src="https://github.com/user-attachments/assets/ce09b97d-3a45-48d0-ad72-b8698d36ecf0" />
  - Substrate bondpads <img width="1919" height="811" alt="image" src="https://github.com/user-attachments/assets/b5b2c48a-afe9-4d28-a8b0-acfe45afa862" />
  - Bondwires connecting the Die bondpads and Substrate bondpads <img width="1915" height="818" alt="image" src="https://github.com/user-attachments/assets/51c3f40c-d8d8-440e-8efe-f4a86132edcf" />





 
- Adding Mold/Epoxy material over substrate <img width="1919" height="816" alt="image" src="https://github.com/user-attachments/assets/2a0af421-d96a-4024-a852-b97e5844dec1" /> <img width="1919" height="818" alt="image" src="https://github.com/user-attachments/assets/b5316fd3-df0e-48c4-9209-4d49d58bfbac" />












--------------------------------------------------------------------------------------------------------------------------











