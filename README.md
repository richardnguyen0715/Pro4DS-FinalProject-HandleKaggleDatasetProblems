## **Programming for Data Science - Lập Trình cho khoa học dữ liệu**
### **HCMUS - Trường Đại học khoa học tự nhiên - Nov 2024.**
### **Final Project - Handle Kaggle Dataset Problems**
#### **Due:** 16/12/2024.
#### **Lớp:** 22_21.
#### **Giảng viên hướng dẫn:** Thầy Phạm Trọng Nghĩa - Thầy Lê Nhựt Nam.
#### **Tên Nhóm:** 3TT
#### **MSSS - Tên thành viên:**
1. 22120384 - Nguyễn Đình Trí.
2. 22120398 - Vũ Hoàng Nhật Trường.
3. 22120412 - Nguyễn Anh Tường.
 
---

## Quick Guide
1. Install kaggle library: `pip install kaggle`.
2. Get the kaggle API Token to use in data collection step.

   2.1 *Login to Kaggle*:

   - Go to the [Kaggle](https://www.kaggle.com/) homepage and log in to your account.

   2.2 *Download API Token*:

   - Click on your profile picture in the upper right corner and select **"My Account"**.

   - Scroll down to the **"API"** section, then click the **"Create New API Token"** button.

   - A file named `kaggle.json` will be downloaded. This file contains the authentication information (username and API key).

   2.3 *Put `kaggle.json` in the right place*:
    - **Linux/MacOS**:
        - Create a hidden folder `.kaggle` in your root directory (if it doesn't exist already):
           ```bash
           mkdir ~/.kaggle
           ```
      - Move the `kaggle.json` file into the `.kaggle` folder:
           ```bash
           mv /path/to/kaggle.json ~/.kaggle/
           ```
      - Set permissions for the file:
           ```bash
           chmod 600 ~/.kaggle/kaggle.json
               ```
   - **Windows**:
     - Move the `kaggle.json` file into the folder:
       ```
       C:\Users\<YourUsername>\.kaggle\kaggle.json
       ```
     - If the `.kaggle` folder does not exist, create it manually.

3. Run Data Collection: `Source\DataCollection.ipynb`
4. Run Data Preprocessing: `Source\DataPreprocessing.ipynb`
5. Run Data Exploration: `Source\DataExploration.ipynb`

---

## Repository Introducing:

### **Dataset folder:**
1. heart_2020_cleaned.csv: First download dataset.
2. Heart_2020_Processed.csv: The data set after preprocessing and encoding will be used for the next steps.
3. encode_meaning.txt: Meaning of categories after being encoded.
### **Requirement folder:**
  Requirements to be implemented in this project.
### **Source folder:** 
1. Data Collection stage: `Source\DataCollection.ipynb`
2. Data Preprocessing and Statistic Exploration stage: `Source\DataPreprocessing.ipynb`
3. Data Exploration stage: `Source\DataExploration.ipynb`

---

## Our Teamưork Tracking website:
Link here : [Pro4DS-FinalProject-Kaggle vs Real-World Problems](https://pool-argument-1f9.notion.site/Pro4DS-FinalProject-Real-World-Problems-1500a9b1c8bb80f89a1bd04bf2f1f98f?pvs=4)
