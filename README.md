# Time-Flip-App-
TimeFlip App is a simple educational quiz application designed to help users test their knowledge of historical facts using true or false questions. 

Project Report: TimeFlip App 

During the development of the TimeFlip App, several technical challenges were encountered and resolved to ensure the application ran smoothly on an Android device using Android Studio. One of the main issues was the app crashing immediately upon launch. This was caused by not using a compatible theme with AppCompatActivity. The fix involved correctly setting the theme in AndroidManifest.xml to use Theme.AppCompat and ensuring the theme was properly defined in themes.xml.

Another persistent error was related to resource linking during the build process. Android Studio showed the message Android resource linking failed, which was mainly caused by hardcoded text in XML layout files and missing attributes such as layout_width or layout_height. To resolve this, all hardcoded text in views like Buttons and TextViews was moved into the strings.xml file, following best practices for localization. Missing or incorrect references to images, drawables, and other resources were also corrected to allow successful builds.

Several errors in MainActivity.kt and ReviewActivity.kt involved unresolved references, such as AppCompatActivity, setContentView, and UI components like tvQuestion. These were resolved by checking import statements, ensuring proper class declarations, and using the correct view IDs matching those defined in the layout files.

There were also challenges with deprecated methods like getColor(), which was updated to use the modern ContextCompat.getColor() approach. Additionally, there was confusion around file directory structure — for example, ReviewActivity.kt was stored in the ui.theme folder, which did not match its package declaration. This was fixed by moving the file to the correct directory or updating the package path.

Lastly, to enhance the visual appearance and interactivity of the app, suggestions were implemented to include icons or images, basic animations or transitions, and detailed inline comments within the code for better understanding and maintainability. A custom logo was also requested for the TimeFlip App to give it a more professional look and branding identity.

Through these adjustments and problem-solving steps, the app became stable, functional, and responsive, and is now ready for further enhancements or deployment.

![image](https://github.com/user-attachments/assets/7c99a5da-a238-4f50-a588-35eb147c4e4a)


Application ScreenShoots: 

![image](https://github.com/user-attachments/assets/365a6459-c66c-40e5-a934-48bfc95ebfcd)



