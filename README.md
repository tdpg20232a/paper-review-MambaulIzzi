<h1> Augmented Reality Map Navigation with Freehand Gestures </h1>

<h2> Introduction </h2>
This paper examines the use of freehand gestures for digital map navigation in Augmented Reality (AR), with a focus on improving user experience and reducing arm fatigue. This research explores new techniques for multiscale navigation, such as pan and zoom, using disembodied horizontal map displays. This study also evaluates the influence of hand dominance (unimanual and bimanual) and input mapping (position-based and rate-based) on user performance and comfort during multiscale navigation. The results show that transitions between input mappings can reduce perceived arm fatigue without sacrificing user performance.
<br/> <br/>
This research focuses on the use of freehand movements for multiscale navigation in Augmented Reality (AR) applications, especially in the context of digital map exploration. By exploring the benefits of integrating position- and velocity-based input mapping, this research aims to improve user experience and reduce arm fatigue during navigation tasks. The introduction of new hybrid techniques, such as DiveZoom and TerraceZoom, allows seamless transitions between different input mappings, providing a good balance between performance, comfort and ease of learning for users. The research findings show that this hybrid method can effectively improve the usability of AR applications for map navigation, paving the way for more intuitive and ergonomic interaction methods in the future.

![image](https://github.com/tdpg20232a/paper-review-MambaulIzzi/assets/69846753/c1ecf3f8-dc1b-4645-ab0d-da30252c4f19)

In this research, various devices and technologies are used to support the implementation and testing of the interaction techniques developed. The following is an overview of the devices used in this research:

1. **AR See-Through Video Setup**:
    - Uses an HTC Vive equipped with a Zed Mini RGB stereo camera to capture scenes in high resolution with a 110 degree field of view.
    - Leap Motion is installed on the headset for participant hand tracking.
    - A desktop computer with an Intel i7 processor, 32GB RAM, and Nvidia GeForce GTX 1080 is used to ensure a fairly high frame rate (60-100 FPS).
    - The map viewport size is 1m x 1m.
    - A simple grid was used instead of a map in this study  .

2. **Display-Control Gain Transfer Function and Visual Feedback**:
    - Used the sigmoid gain transfer function from reference [52] for both input mappings.
    - The function parameters are adjusted through preliminary studies to find parameters suitable for most users.
    - Simple visual feedback is used to indicate detected pinch and displacement for the Joystick technique  .

<h2>Methodology</h2>
In this research, the methodology used includes a series of steps to test and evaluate interaction techniques developed for digital map navigation with AR. The following is a summary of the methodology used in this research:

1. **Research Design**:
    - The research was carried out in two different study stages to evaluate the interaction techniques developed.
    - The first study focused on mapping input and handedness in a panning task, while the second study compared four interaction techniques in a zooming task [T1], [T2].

2. **Participants**:
    - A total of 16 participants (13 men, 3 women) who were all right-handed were recruited for this study.
    - Participants came from the institution where the author works, with an age range of 18 to 44 years.
    - Some participants had previous experience with VR/AR, while others did not [T6].

3. **Experimental Procedure**:
    - The study consists of two different parts: a panning task and an integrated pan and zoom task.
    - Each interaction technique is evaluated by providing sufficient training to participants before performing the specified tasks.
    - Study duration ranges between 20-30 minutes for the first part and 50-60 minutes for the second part, with a break between the two parts [T6].

4. **Data Analysis**:
    - User performance data, such as task completion time, arm fatigue and user preferences, are analyzed using appropriate statistical methods.
    - Statistical analysis is performed to compare results between different interaction techniques and evaluate effectiveness and user preferences [T6].

By using a structured and experimental methodological approach, this research can provide deep insight into the performance and user preferences of interaction techniques developed for digital map navigation with AR.

In this research, various interaction techniques are used to explore the potential of using freehand gestures in digital map navigation with AR. The following is an overview of the interaction techniques used in this research:

![image](https://github.com/tdpg20232a/paper-review-MambaulIzzi/assets/69846753/d013a568-137e-42b1-9d28-2c1382185d4a)


1. **Hybrid Technique**:
    - **DiveZoom**: The DiveZoom technique was developed to integrate position-based and rate-based input mapping in map navigation. This technique is designed to reduce arm fatigue without compromising user performance   .
    - **TerraceZoom**: The TerraceZoom technique is also a hybrid technique that allows a seamless transition between position-based and rate-based input mapping, with a focus on user comfort and efficiency   .

2. **Unimanual and Bimanual Input**:
    - This study considers the use of unimanual and bimanual input in map navigation. The bimanual approach has been shown to provide better control over pan and zoom operations in parallel   .
    - The aim of developing unimanual techniques is to allow the integration of other operations besides pan and zoom, so that the user can perform various actions with one hand   .

3. **Input Mapping**:
    - Position-based and rate-based input mapping is used in the development of hybrid techniques. This mapping allows users to control map navigation with intuitive and efficient hand movements   .

By using these various interaction techniques, this research succeeded in developing an innovative and ergonomic approach for digital map navigation using freehand gestures in an AR context.

In this study, a panning task (moving the gaze horizontally) was used as part of the evaluation of the interaction techniques developed. The following is an overview of the panning tasks in this study:
    - Panning tasks involve the user in moving the map view from a starting location to a specified target location.
    - In the initial stages of a panning task, zooming is disabled to allow evaluation of input mapping performance without zoom integration
    
![image](https://github.com/tdpg20232a/paper-review-MambaulIzzi/assets/69846753/dc98c124-6e28-4aa8-8868-f55102f337e5)

Integration between pan (moving the view) and zoom (enlarge/reduce the view) functions is an important aspect in developing interaction techniques for digital map navigation with AR. The following is an overview of the integration of pan and zoom in this research:

1. **Importance of Pan and Zoom Integration**:
    - When performing multiscale navigation, especially when zooming to a desired target, integration between pan and zoom allows the user to direct the view more precisely  .
    - However, when panning for regional exploration, integrated zooming is undesirable as it may interfere with the panning task.
  
![image](https://github.com/tdpg20232a/paper-review-MambaulIzzi/assets/69846753/aadae84b-912b-4e8f-825c-b9fa0f31e829)


2. **Indirect Grab and Joystick Technique Modification**:
    - Indirect Grab and Joystick techniques are modified by distinguishing between pan actions only (Pan) and integrated actions (Zoom+Pan)  .
    - The Zoom+Pan region is represented as two opposing cones with an apex angle of 90 degrees, which allows panning and zooming to be performed simultaneously.
    - When the hand is in the Zoom+Pan area, the user can pan and zoom simultaneously. However, when the hand is outside the Zoom+Pan region, only panning is possible.

3. **Pan and Zoom Integration Goal**:
    - Pan and zoom integration aims to support efficient and comfortable navigation for the user, by enabling local control with small movements around the comfortable area of the hand  .
    - Taking into account user hand movements and navigation needs, pan and zoom integration is designed to provide a better user experience in digital map navigation with AR.

![image](https://github.com/tdpg20232a/paper-review-MambaulIzzi/assets/69846753/bc162e5a-82f5-4465-b430-2c6a62448a60)


By intelligently integrating pan and zoom functions, the interaction technique developed in this research can provide an effective and intuitive solution for digital map navigation with AR.
<h2> Result and Conclusion </h2>
In this research, the results of the studies conducted provide valuable insights into user performance in using interaction techniques for digital map navigation with AR. The following is a summary of the results and conclusions that can be drawn from this research:

1. **Study 1**:
    - The first study focuses on mapping input and handedness in a panning task without zoom integration.
    - There is no main effect of input mapping on completion time, but there is a significant distance effect.
    - Indirect Grab is rated as more tiring than Joystick in terms of arm fatigue   ,  .

2. **Study 2**:
    - The second study compared four different interaction techniques in a zooming task.
    - The Indirect Grab and DiveZoom techniques were rated as the most liked by the participants.
    - DiveZoom is rated to have lower arm fatigue compared to TerraceZoom and Indirect Grab   ,   .

3. **Hybrid Input Mapping Design**:
    - Two new techniques using hybrid input mapping are introduced to support remote navigation and local control.
    - Pan and zoom integration is designed to enable efficient and convenient navigation for users   .

4. **Conclusion**:
    - The integration of pan and zoom is a key aspect in the development of interaction techniques for digital map navigation with AR.
    - Developed interaction techniques, such as Indirect Grab and DiveZoom, show good performance and are liked by users.
    - Hybrid input mapping can be an effective approach to overcome challenges in digital map navigation with AR   ,   ,   .

Thus, this research makes an important contribution to the development of effective and convenient interaction techniques for digital map navigation with AR, as well as providing valuable insights for the future development of AR applications.

