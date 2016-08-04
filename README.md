# Android-ocr-app-supporting-simple-math-equations-using-tesseract
tesseract ocr for andoid with simple mathematical equations rocognition.Used equ.traineddata file and box files.

-This is project hosted already on Github using tesseract,However I have made some modifications to read simple 
mathematical equations and allowed it to use box files for better accuracy.

-This is a ready to clone project and doesnt need anything extra to compile.

-Please use the Tess two folder as library in eclipse.

-Steps to make it usable.
  - 1:  Download/clone the project to your local system.
  
  - 2:  Open eclipse and add the project to work space.
  
  - 3:  Now you heve Simple-Android-OCR and tess two inside the workspace.Tess-two folder has the tessract and leptonica libraries
        among others which you need for ocr function.Click on Simple-Android-OCR and select properties -> android -> chek Is library 
        ->add and select tess-two project -> apply -> add and close.
  - 4:  Now go to Simple-Android-OCR -> right click and run as android application.
  
  - 5: Try to read with the simple text and simple equations first.
  
  
  NOTE:the regex filter on line 466 in Simple-Android-OCR is disabled.Customize this to get favourable results.
      
      I will try to improve it further.However I need further contributions and suggestions.    Thanks.!!
      
      Thanks to  http://gaut.am/ and Robert Theis for the original contributions.
