## AI

### AI introduction

Model training

- learn from data

- Labels: reference outputs

- Generated output

- Model before training: initial model (M⁰)

- Training: update parameters

- AFter training: Trained model (M*)

Model testing

Problems in training data

- Determines quality of model

- Small training dataset -> may not be able to learn the general characteristics

- Noisy dataset -> learn from information that is not helpful

- Unbalanced dataset -> Insufficient data for learning characteristics of the minor class

Artificial neural network (ANN)

- inspired by human brain

- Deep neural network (DNN): ANN with many layers

- Accept input through input layer, computes in hidden layer and output at output layer

Generative AI

- Neural networks used to generate new content (e.g. text, images)

- e.g. ChatGPT
  
  - family of language model named GPT (Generative Pre-trained Transformers)
  
  - Can understand human inputs (prompts) 

- Generative agents
  
  - Generate human like behaviour in game

- Image generation tools
  
  - Text prompt -> generated images

### AI ethical issues

UNESCO recommendation

- Human-friendly and Earth-friendly

- Guideline of ethical AI, recommendations of AI ethical principles

- Policy actions

- Adopted by 193 member states as the first global standard

AI principle and ethical issues

- Transparency: Explainability of process carried out by AI-powered applications for end users

- Justice and fairness
  
  - Ensure equality, inclusion and diversity
  
  - Rules of fair play
  
  - Promote justice and eliminate all types of discrimination
  
  - e.g. interviewing in hiring
    
    - Done effectively, act like HR professional analysing interviewee's performance
    
    - follow set of patterns in interview dialog, conduct dialog with sufficient variation
    
    - Can be biased (gender/age), make mistakes, not feel comfortable with a non-human interviewer 

- Beneficence
  
  - Development and application must not do any harm
  
  - Promote well-being, preserve dignity and enhance stability
  
  - Developed for the common good and benefit of all humanity
  
  - e.g. Airport security robots -> Good for security

- Responsibility
  
  - must uphold accountability and honesty
  - development of AI systems and comparison to human values should ensure the well-being of humanity
  - e.g. Self driving car in trolley problem: What moral choice should be programmed into AI models
    - Responsible: AI programmers, manufacturers, drivers, policy makers
    - Considerations: Safety, compliance with applicable traffic laws

- Privacy
  
  - consume massive volume of data -> privacy issues and ethical dilemmas
  
  - Privacy: protect and secure sensitive data
  
  - e.g. Data collected by mobile devices
    
    - Name, website visited, email addresses, contact details, geolocation, social network contacts
    
    - When clicking or typing, browsing or purchasing, taking or uploading photos and videos, contacting friends...

### Computer vision

How see

- Image made out of pixels

- Colour 
  
  - Greyscale: 0(black) - 255(white)
  
  - Colour: R, G, B, 0-255 -> combination becomes colours
  
  - Represented as numbers e.g. (0, 255, 0)

What is Computer Vision (CV)

- e.g. Image classification
  
  - classify image to be a class among a set of pre-defined classes
  
  - How human classify
    
    - Using distinctive characteristics: **Features**
    
    - e.g. bird has sharp beaks
  
  - How AI classify
    
    - Difficult to use human features 
  
  - **Convolutional Neural Networks** (CNN)
    
    - Use deep learning to capture features 
    
    - Class of deep learning models frequently used in CV tasks
    
    - have **Convolutional layers**, Pooling layer and Fully-connected layer
    
    - Have multiple **filters** -> capture different features during training
    
    - Earlier layers -> **lower-level features** (smaller region)
    
    - Later layers -> **Higher-level features** (larger region)

## App Inventor

Introduction

- Application(App)
  
  - program designed for mobile devices
  
  - popular application store: Google Play Store and Apple App Store

- App Inventor
  
  - Tool to build mobile applications
  
  - Cloud based platform, files stored in server, developers access it via web browser
  
  - By joining puzzle-piece shaped "programming blocks" together
  
  - Employs event driven programming
  
  - Advantages: Easy, Only need to drag and drop components and programming blocks, lowers risks of syntax errors

User interface

- Designer
  
  - Create app interface
  
  - Palette: Contain all available components grouped by category
  
  - Viewer: Preview of app screen, design UI
  
  - Components: Tree view listing components, for renaming or deleting
  
  - Properties: Display / Change properties of selected component

- Blocks editor
  
  - Program app's behavior
  
  - Built-in Drawers: Blocks for general behaviours 
  
  - Component-specific drawers: Behaviour for specific components
  
  - Block: Snap blocks together
  
  - Viewer: Drag blocks to here

Layout Settings

- Layout components
  
  - HorizontalArrangement
  
  - VerticalArrangement
  
  - TableArrangement
  
  - HorizontalScrollArrangement
  
  - VerticalScrollArrangement

- Layout properties
  
  - Width (Automatic, Fill parent, fixed number of pixels)
  
  - Height (Automatic, Fill parent, fixed number of pixels)
  
  - Align Horizontal (Left, Center, Right)
  
  - Align Vertical (Top, Center, Bottom)
  
  - Background color (Color / Hex code)
  
  - Image (Upload image file)
  
  - Visible (True / False)

- Layouts can be nested

Programming

- Blocks editor
  
  - Control (Gold)
  
  - Logic (Green)
  
  - Math (Blue)
  
  - Text (Purple)
  
  - Variables (Orange)
  
  - Procedures (Violet)

- Event-Driven Programming
  
  - Event handler block (when blocks)
  
  - Event: e.g. Button1.Click
  
  - Handler: e.g. when Button1.Click do
  
  - Action: set Label1.Text to "Hello!"

- Variable
  
  - Named container that stores a value
  
  - initialize global name to
  
  - initialize local name to in
  
  - get variable
  
  - set variable to

- Control structures
  
  - If ... then
  
  - If ... then ... else
  
  - for each item in list
  
  - for each number from ... to ...
  
  - while ... do

- Procedures (Functions)
  
  - to procedure \_\_\_ do ...
  
  - to procedure \_\_\_ result ... (returns a value)

- Lists
  
  - create empty list
  
  - make a list (item1, ...)
  
  - add items to list
  
  - select list item (list, index)
  
  - length of list
  
  - remove list item

Inserting media

- Media files
  - non-text resources
  - Image: .png, .jpg, .gif
  - sound: .mp3, .wav
  - Video: .mp4, .avi
- Uploading media
  1. Open project in Designer view
  
  2. Find section named Media
  
  3. Click upload file
  
  4. Click Choose File, then choose file
  
  5. Click OK

Displaying image

- Designer panel -> Palette panel -> User Interface -> Image component -> Drag into Viewer 

- -> Property panel -> Picture property -> choose the media file

- Useful properties: Picture, Width, Height, ScalePictureToFit, Visible

Playing video

- Palette -> Media category -> VideoPlayer -> Properties panel -> Source property -> Source -> choose video file -> set Width and Height

- Useful properties: Source, Width / Height, Volume, Visible

- Common Block: ...

Playing a Sound

- Media -> Sound component -> Source property: Uploaded sound file -> Blocks Editor -> Sound1.Play 

- Sound for short Player for long

Changing Media

- set Image1.Picture to "penguin.png"

- set VideoPlayer1.Source to "penguinWalking.mp4"

Other

- Camera

- Camcorder

Colour Picker

- 
