This project aims to automatically detect violent actions and weapons in videos. 
The datasets used in this project are publicly available:

- The **Real-life Violent Activities Dataset** is taken from [here](https://ieee-dataport.org/documents/real-life-violence-situations-dataset).  
- The **Weapons Detection Dataset** is taken from [this repository](https://github.com/ari-dasci/OD-WeaponDetection).
Only 250 violent and 250 non-violent videos and weapons data annotated in YOLOv8 format were used for the project.

## ⚙️ Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/violent-activity-detection.git
   cd violent-activity-detection
   ```
2. **Download the Datasets**
Download the dataset from [IEEE Dataport](https://ieee-dataport.org/documents/real-life-violence-situations-dataset) and [OD-WeaponDetection repository](https://github.com/ari-dasci/OD-WeaponDetection) and place them in the repository folder

3. **Preprocess the Data**
Run the Violence Detection.ipynb notebook to prepare the data for training and training.

4. **Run the Application**
Launch the web application using:
```bash
python app.py
```
You can upload a video file or use the web cam for live analysis. The system will detect and present the results on the video and also log them in a csv file.
