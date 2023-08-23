# Rotating-the-Gaming-Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step1:
Start
### Start2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Start3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Start4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

### Start5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Start6:
Create a folder name Coding and create a C# file to add the coding in it.

### Start7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Start8:
Stop

## Program:
Name :S.S.SRIRAM

Reg.no : 212222230150
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class exp01 : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.right, Vector3.up, 60 * Time.deltaTime);
    }
}

```

## Output:
![WhatsApp Image 2023-08-23 at 20 40 33](https://github.com/sriramss4880/Rotating-the-Gaming-Object/assets/120554177/d3ebd331-009a-4b34-b1b9-fe9291bd5db9)
![WhatsApp Image 2023-08-23 at 20 40 34](https://github.com/sriramss4880/Rotating-the-Gaming-Object/assets/120554177/a44535f5-5acb-431b-b8a6-1e5ce52897ce)


## Result:
Thus a 3D application for rotating the gaming objects in unity was developed.
