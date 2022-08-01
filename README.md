# `Language-Recognition with SVM in python` 🐍:

This project aims to create a pipeline that extract youtube videos and perform transcription on their related audios. 
The code gets a list of youtube channels and scraps all videos that are tagged with some keywords (defined in keyword file). After downloading audios, comments and available transcriptions. A language detection model detects the language spoken in the video and perform transcription. The supported languages are:  **`Swahili`**, **`Wolof`**, **`French`**, **`English`**, **`Arabic`** and **`Dyula`**.



In order to Run the code. 
- Run the `Getting videos Urls` first to get all videos with specified tags in the Keywords files and channels names in youtube_channels file.
- After that, run the `Youtube-video-transcriptor` notebook to get video transcription.

- Model performance: Here are the results obtained after training the model

      wolof:  {'precision': 0.9956011730205279, 'recall': 0.9883551673944687, 'f1-score': 0.9919649379108838, 'support': 687}
      french:  {'precision': 0.9971264367816092, 'recall': 0.9788434414668548, 'f1-score': 0.9879003558718862, 'support': 709}
      swahili:  {'precision': 1.0, 'recall': 0.9849108367626886, 'f1-score': 0.9923980649619903, 'support': 729}
      english:  {'precision': 0.9683195592286501, 'recall': 0.9736842105263158, 'f1-score': 0.9709944751381215, 'support': 722}
      arabic:  {'precision': 0.9363354037267081, 'recall': 0.9741518578352181, 'f1-score': 0.9548693586698337, 'support': 619}
      dyula:  {'precision': 1.0, 'recall': 1.0, 'f1-score': 1.0, 'support': 691}

- 📫 Feel free to contact me if anything is wrong or if anything needs to be changed 😎!  **isbainemouhamed@gmail.com**

