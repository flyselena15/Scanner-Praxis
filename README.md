# Scanner-Praxis

An application used to import images from a camera, process them, and output in an OCR PDF. 

Due to a series of poor choices, the application is in java and the GUI is in javafx. 

Note: Many of the operations require JDK-9 and above.

Pre-Requirements:

ScanTailor
http://scantailor.org

Image Magick
https://www.imagemagick.org/

Tesseract OCR
https://github.com/tesseract-ocr/tesseract

PDFtk Server
https://www.pdflabs.com/tools/pdftk-server/

Mac Install:                    | Linux Install:
-----------------------------   | --------------------------
sudo port selfupdate            | sudo apt-get update
sudo port install scantailor-universal    | sudo apt-get install scantailor-universal
sudo port install ImageMagick   | sudo apt-get install imagemagick
sudo port install tesseract     | sudo apt-get install tesseract-ocr
sudo port install tesseract-eng | sudo apt-get install libtesseract-dev
                                | sudo apt install pdftk


There are two versions of Scanner-Praxis 
* <strong>Dual Camera Version</strong></br>
Source code: /ScannerGUI</br>
It allowed people to scan pictures and turn it to PDF when your computer can connect both cameras.</br>
After chossing left camera and right camera, you can click easy run to download pictures from both camera and automatically rotate, tail, combine and turn into PDF.</br>

* <strong>Switch Camera Version (Download from one camera each time)</strong></br>
Source code: /ScannerGUI_SwitchCamera/src</br>
If your computer cannot connect to 2 cameras at the same time, you will need to have "switcher".</br>
This version of Scanner-Praxis allows you to download from one camera and it will ask you to switch to another to do the rest of work.</br>
