# HoloLens-2-look-alike-vial-detection
 
![20240909_224417_HoloLens](https://github.com/user-attachments/assets/b4920845-ee08-4abb-8540-84caea2ba0b0)

![20240909_224530_HoloLens](https://github.com/user-attachments/assets/770cf21a-b7d9-4d43-b900-9d3e85695e4e)


![20240909_121513_HoloLens](https://github.com/user-attachments/assets/8a2e04bf-3587-478e-b0aa-01c712918296)
Accurate identification of medicine vials is crucial for emergency medical services, especially for vials that resemble one another but have different labels, volumes, and concentrations  .



# Accurate Medical Vial Identification Through Mixed Reality: A HoloLens 2 Implementation

This project introduces an advanced system for real-time detection and identification of medical vials using Microsoft HoloLens 2 and Mixed Reality (MR) technology. Designed for high-pressure medical environments, this solution enhances patient safety by reducing the likelihood of vial misidentification.

---

## 🔑 Key Features
- **Mixed Reality Integration**: Hands-free vial detection with HoloLens 2.
- **Hybrid Detection**: Combines HoloLens 2 and an external Bluetooth barcode scanner for optimal performance.
- **Real-Time Processing**: High accuracy and fast processing with live feedback.
- **Database Integration**: Connects to an SQL server to retrieve detailed vial information.
- **Dynamic Environment Support**: Effective under varying lighting and vial positioning.

---

## 📂 Project Structure
- **`/Assets`**: Unity project files for HoloLens 2 application development.
- **`/Scripts`**: Core logic for barcode detection, image processing, and server communication.
- **`/Documentation`**: Flowcharts, methodology, and implementation details.
- **`/Database`**: SQL scripts and example data for managing vial information.

---

## 🛠️ System Requirements
- **Hardware**:
  - Microsoft HoloLens 2
  - External Bluetooth Barcode Scanner
- **Software**:
  - Unity 2022.3.1f1
  - Mixed Reality Toolkit (MRTK)
  - SQL Server for database management

---

## 🚀 Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/BD-BAHAR/HoloLens-2-look-alike-vial-detection.git
   cd HoloLens-2-look-alike-vial-detection

##🔧 Open in Unity
#Launch Unity: Open Unity version 2022.3.1f1. If not installed, download it from the Unity Download Archive.
#Open the Project Folder:
From the Unity Hub, click Open Project and select the folder containing the cloned repository.
Install the Mixed Reality Toolkit (MRTK):
Open Window > Package Manager.
Click + Add package from Git URL... and enter:
bash
Copy code
**https://github.com/microsoft/MixedRealityToolkit-Unity.git#release/2.7.3
Wait for the toolkit to download and install.
🚀 Build and Deploy
Set Build Platform:
Go to File > Build Settings.
Select Universal Windows Platform (UWP) and click Switch Platform.
In the Build Settings, ensure:
Target Device: HoloLens.
Architecture: ARM64.
Build Type: D3D Project.
Build the Application:
Click Build and choose an empty folder to save the build output.
Once the build process completes, navigate to the folder and open the .sln file in Visual Studio.
Deploy to HoloLens 2:
In Visual Studio:
Set the Solution Configuration to Release and ARM64.
Select Device as the target platform.
Connect your HoloLens 2 to your computer.
Click Deploy to install the app on the HoloLens.
##🗄️ Set Up the Database
Create the SQL Database:
Use the SQL scripts provided in the /Database folder to create and populate the database.
Run the scripts in your SQL server environment to set up the tables and data.
Configure Server Connection:
Ensure the Unity application can communicate with the SQL server. This may involve setting up a local network or cloud-hosted server for real-time database access.


## 📜 Citation
If you use this project, please cite: Mahmud, B.U.; Hong, G.Y.; Sharmin, A.; Asher, Z.D.; Hoyle, J.D., Jr. Accurate Medical Vial Identification Through Mixed Reality: A HoloLens 2 Implementation. Electronics 2024, 13, 4420. https://doi.org/10.3390/electronics13224420


