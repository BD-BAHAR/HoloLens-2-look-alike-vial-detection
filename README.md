# HoloLens-2-look-alike-vial-detection
 
![20240909_224417_HoloLens](https://github.com/user-attachments/assets/b4920845-ee08-4abb-8540-84caea2ba0b0)

![20240909_224530_HoloLens](https://github.com/user-attachments/assets/770cf21a-b7d9-4d43-b900-9d3e85695e4e)


![20240909_121513_HoloLens](https://github.com/user-attachments/assets/8a2e04bf-3587-478e-b0aa-01c712918296)
Accurate identification of medicine vials is crucial for emergency medical services, especially for vials that resemble one another but have different labels, volumes, and concentrations  .



Accurate Medical Vial Identification Through Mixed Reality: A HoloLens 2 Implementation
This project introduces a cutting-edge system that uses Microsoft HoloLens 2 and mixed reality (MR) technology to accurately detect and identify medical vials in real-time. The solution is designed to aid healthcare professionals, particularly in high-pressure emergency scenarios, where rapid and accurate identification of look-alike medical vials is critical for patient safety.

Key Features
Mixed Reality Integration: Utilizes the HoloLens 2 to overlay digital information onto the physical world, enabling hands-free vial identification.
Hybrid Detection System: Combines HoloLens 2 camera capabilities with an external Bluetooth barcode scanner to ensure the detection of both large and small barcodes.
Real-Time Processing: Achieves up to 98% detection accuracy with minimal latency under controlled conditions.
Secure Data Handling: Integrates an SQL server to manage vial and barcode data securely, ensuring HIPAA compliance.
Optimized for Medical Environments: Designed to function effectively in dynamic lighting conditions and with various vial sizes.
Project Structure
/Assets: Unity project files, including scripts for barcode detection and MR interface design.
/Scripts: Core scripts implementing image processing techniques  and server communication.
/Documentation: Includes the research paper, technical flowcharts, and implementation details.
/Database: Sample SQL scripts and JSON format for barcode data storage.
Methodology
The project was implemented in three phases:

Data Collection and Preprocessing: Collected real-world vial data and prepared it for detection.
Application Development: Built an MR application using Unity and the Mixed Reality Toolkit (MRTK) for the HoloLens 2.
Performance Evaluation: Tested under various lighting conditions, barcode sizes, and detection distances.
Key algorithms and methods include:


Barcode Decoding: Implemented using the ZXing library and Reed-Solomon error correction.
Server Communication: Utilized HTTP GET requests to retrieve vial information from an SQL database.
System Requirements
Hardware: Microsoft HoloLens 2, Bluetooth Barcode Scanner.
Software: Unity 2022.3.1f1, Mixed Reality Toolkit (MRTK).
Additional Tools: SQL server for data storage and management.
Installation and Setup
Clone the repository:
bash
Copy code
git clone https://github.com/BD-BAHAR/HoloLens-2-look-alike-vial-detection.git
cd HoloLens-2-look-alike-vial-detection
Open the project in Unity 2022.3.1f1.
Install the Mixed Reality Toolkit (MRTK) via Unity Package Manager.
Deploy the application to the HoloLens 2 using the Unity build settings for UWP.
Set up the SQL server using the provided database scripts in /Database.
Results
Detection Accuracy:
Large barcodes: 98% accuracy.
Small barcodes: Detected with the external scanner.
Performance:
Frame rates between 10–52.5 fps depending on camera resolution and conditions.
Average processing time: 57.6 ms for detection and retrieval.
Future Work
Future developments will include:

Integration of deep learning models for appearance-based vial detection.
Enhanced camera resolution and computational capabilities for improved performance.
Citation
If you use this project, please cite: Mahmud, B.U.; Hong, G.Y.; Sharmin, A.; Asher, Z.D.; Hoyle, J.D., Jr. Accurate Medical Vial Identification Through Mixed Reality: A HoloLens 2 Implementation. Electronics 2024, 13, 4420. https://doi.org/10.3390/electronics13224420
