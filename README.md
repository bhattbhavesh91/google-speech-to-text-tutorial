<h1>Getting Started with Google Cloud Speech-To-Text API Using Python for Novices</h1>
<p>Utilizing the Google Speech-To-Text API, you can transform spoken words into written text, transcribe video content, and identify specific custom keywords. In this tutorial, we will embark on a journey to begin working with the Google Speech-to-Text API using Python, starting from the very basics. I will guide you through every step, starting with the creation of a Python script to interact with the Google Cloud Speech-To-Text API. If you are new to Google Cloud services, this video serves as an excellent introductory resource for getting started.</p>
<h2>Click to open the Notebook directly in Google Colab</h2>
<!-- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bhattbhavesh91/google-speech-to-text-tutorial/blob/main/google-speech-to-text-notebook.ipynb)
 -->

<p><a href="https://colab.research.google.com/github/bhattbhavesh91/google-speech-to-text-tutorial/blob/main/google-speech-to-text-notebook.ipynb" target="_blank"><img height="40" alt="Open in Colab" src = "https://colab.research.google.com/assets/colab-badge.svg"></a></p>
<h2>To view the video</h2>
<table>
   <tr>
      <td><a href="http://www.youtube.com/watch?v=jBbLon5esbE" target="_blank"><img height="50" src = "https://img.shields.io/youtube/views/jBbLon5esbE?color=blue&label=Watch%20on%20YouTube&logo=youtube&logoColor=red&style=for-the-badge"></a></td>
   </tr>
</table>

<p>or click on the image below</p>
<p><a href="http://www.youtube.com/watch?v=jBbLon5esbE"><img alt="Google Cloud
" src="http://img.youtube.com/vi/jBbLon5esbE/0.jpg" /></a></p>
<p><a href="https://github.com/sponsors/bhattbhavesh91" target="_blank"><img height="40" alt="GitHub Sponsor" src = "https://img.shields.io/badge/Sponsor me on GitHub-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#white"></a>
<a href="https://t.me/bhattbhavesh91" target="_blank"><img height="40" alt="Telegram Channel Link" src = "https://img.shields.io/badge/Join my Telegram channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a></p>
<p><strong>If you like my work, you can support me by buying me a coffee by clicking the link below</strong></p>
<p><a href="https://www.buymeacoffee.com/bhattbhavesh91" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a></p>
<h3>🛠 Languages &amp; Tools Used:</h3>
<p align="left">
  <a href="https://www.python.org/" target="_blank"> <img alt="Python" src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> </a>
  <a href="https://git-scm.com/" target="_blank"> <img src="https://img.shields.io/badge/Git-282C34?logo=git" alt="Git logo" title="Git" height="25" /> </a>
  <a href="https://jupyter.org/" target="_blank"> <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter%20-%23F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" /> </a>


## Follow Me
<a href="https://twitter.com/_bhaveshbhatt" target="_blank"><img class="ai-subscribed-social-icon" src="https://bhattbhavesh91.github.io/assets/images/tw.png" width="30"></a>
<a href="https://www.youtube.com/bhaveshbhatt8791/" target="_blank"><img class="ai-subscribed-social-icon" src="https://bhattbhavesh91.github.io/assets/images/ytb.png" width="30"></a>
<a href="https://www.youtube.com/PythonTricks/" target="_blank"><img class="ai-subscribed-social-icon" src="https://bhattbhavesh91.github.io/assets/images/python_logo.png" width="30"></a>
<a href="https://github.com/bhattbhavesh91" target="_blank"><img class="ai-subscribed-social-icon" src="https://bhattbhavesh91.github.io/assets/images/gthb.png" width="30"></a>
<a href="https://www.linkedin.com/in/bhattbhavesh91/" target="_blank"><img class="ai-subscribed-social-icon" src="https://bhattbhavesh91.github.io/assets/images/lnkdn.png" width="30"></a>

<h3 align="center">Show your support by starring the repository 🙂</h3>
