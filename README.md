# Speech Recognition and Translation

This is a Windows Forms application that uses Google Cloud services to perform speech recognition and translation. The application allows you to select an audio or video file, and then it will transcribe the speech in the file to text. You can then translate the text to another language.

## Features

*   Transcribe speech from audio and video files
*   Translate text to other languages
*   Support for multiple languages
*   Punctuation restoration
*   Syntactic analysis of text

## Dependencies

*   Google Cloud Speech API
*   Google Cloud Natural Language API
*   Google Cloud Translation API
*   NAudio
*   MediaToolkit

## How to Run

1.  Clone the repository.
2.  Open the solution in Visual Studio.
3.  Restore the NuGet packages.
4.  You will need to create a Google Cloud Platform project and enable the Speech, Natural Language, and Translation APIs.
5.  You will also need to create a service account and download the credentials as a JSON file.
6.  Update the `jsonPath` variable in `Form1.cs` to point to the location of your credentials file.
7.  Run the application.
