# WinUI-3-Notebook
## C#
#### Creating a new project


![image](https://github.com/user-attachments/assets/96645056-b23a-4381-af40-e6743fcea8fd)

#### Running it for the first time

![image](https://github.com/user-attachments/assets/188d2c65-c519-4954-9ca2-ba86502e8872)

#### Adding a Backdrop
In the MainWindow.xaml file add the following tag as a child of the Window tag:
```xaml
<Window.SystemBackdrop>
        <MicaBackdrop Kind="Base"/>
</Window.SystemBackdrop>
```
![image](https://github.com/user-attachments/assets/83a02fbb-38f8-4582-a744-71055d1e4a8e)

![image](https://github.com/user-attachments/assets/45816925-653c-43c2-8bce-e0398035a149)

#### Legacy App Icon
The one which is visible in the Alt+Tab menus, the Task Manager and alike.
An ICO file with any aspect ratio works but a 1:1 ratio or a larger horizontal axis is recommended as it gets streched out horizontally in Task Manager.

#### Extending the Title Bar
In the MainWindow.xaml.cs file, go to the constructor for MainWindow and set the property ExtendsContentIntoTitleBar to true.
