# Windows
  
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.11.x
  
  Open command prompt and type
  ```
  git clone https://github.com/rashidlone/youtubeBot.git
  ```
  ```
  cd youtubeBot
  ```
  ```
  python -m pip install --upgrade pip wheel
  ```
  ```
  pip install "setuptools<59"
  ```
  ```
  pip install -r requirements.txt
  ```

* ## Important
   * If you've got a large free proxies collection, you should run this command to filter Good proxies. Then use **GoodProxy.txt** for proxy in **youtube_viewer.py**
      ```
      python proxy_check.py
      ```

   * After closing program, if chromedrivers are still running. You may want to double click **killdrive.bat** to close all chrome instances.

   * *urls.txt* or *search.txt* can't be empty. Otherwise you will see errors. Use both for better results.

* ## Usage
   * Open command prompt in YouTube-Viewer folder and run
        ```
        python youtube_viewer.py
        ```
   * Rest is self explanatory.

# Linux / Mac
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.11.x
  
  Open your favourite terminal and run
   ```
  git clone https://github.com/rashidlone/youtubeBot.git
  ```
  ```
  cd youtubeBot
  ```
  ```
  python3 -m pip install --upgrade pip wheel
  ```
  ```
  pip3 install "setuptools<59"
  ```
  ```
  pip3 install -r requirements.txt
  ```

