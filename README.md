# shoestring-hackathon-2020
Automated machine vision inspection using machine learning for small SMEs

Code used for the IfM Hackathon 2020, regarding Automated Machine Vision Quality Inspection:
Develop a vision system for inspecting products against predefined quality standards

- Used ImageAI open source code to train h5 file to bottle image dataset
- Can change object of interest by retraining data and changing h5 file
- Detects bottle, barcode, scans barcode, estimates height of bottle, and writes all the data to an external spreadsheet file
- Alerts the user if any abnormalities are detected
- Used ImageAI Image Detection, panda for handling spreadsheets, OpenCV for machine vision and detection
