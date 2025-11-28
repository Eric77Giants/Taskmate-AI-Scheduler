# Taskmate-AI-Scheduler
A Serverless Daily Task Scheduler built with AWS PartyRock and Generative AI.


**AWS PartyRock Project: TaskMate Pro – Daily Productivity Partner**

**Eric Richmann**

**richmanneric@gmail.com**

**[https://www.linkedin.com/in/eric-richmann](https://www.linkedin.com/in/eric-richmann)**

**November 28, 2025**

** **

** **

**Project Summary**

**Project Goal:** To rapidly design and deploy a dynamic, AI-powered "Daily Task Scheduler" application that generates structured schedules, personalized productivity tips, and visual motivation based on user-defined inputs.

**Skills Demonstrated:** Generative AI Application Development, Prompt Engineering, Rapid Prototyping, UI/UX Design, and familiarity with the AWS cloud ecosystem (AWS PartyRock/Bedrock).

**Key AWS Tool:** **AWS PartyRock** (a platform utilizing underlying Generative AI services like Amazon Bedrock).

**Deployment Status:** Publicly deployed and accessible (Insert Live Demo Link Here).

**I. Architecture and Generative AI Logic**

The application leverages multiple generative AI widgets within a serverless flow to provide instant, personalized scheduling.



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")


** **

**Core Widget Functions:**


<table>
  <tr>
   <td><strong>Widget Name</strong>
   </td>
   <td><strong>Function</strong>
   </td>
   <td><strong>AI Skill Focus</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Tasks</strong> (Input)
   </td>
   <td>User inputs the activities to be scheduled (e.g., "Walk the dog, Go to the gym").
   </td>
   <td>Data Capture
   </td>
  </tr>
  <tr>
   <td><strong>Time</strong> (Input)
   </td>
   <td>User inputs the required duration for each task.
   </td>
   <td>Data Capture
   </td>
  </tr>
  <tr>
   <td><strong>Schedule</strong>
   </td>
   <td><strong>Generates a time-sequenced schedule</strong> by linking the <strong>Tasks</strong> and <strong>Time</strong> inputs.
   </td>
   <td><strong>Prompt Engineering/Structured Output</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Productivity Tips</strong>
   </td>
   <td>Provides analysis and tips based on the generated schedule.
   </td>
   <td><strong>Text Analysis and Generation</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Motivational Image</strong>
   </td>
   <td>Creates a relevant, custom image to serve as a visual motivator.
   </td>
   <td><strong>Image Generation Model Control</strong>
   </td>
  </tr>
</table>


 

**II. Design Process and Optimization (Iterative Refinement)**

A key focus of this project was demonstrating the ability to evaluate and refine AI-generated solutions to meet specific requirements.

**1. Initial Deployment and Vague Prompting**



* The project began with the general prompt: "Generate a daily task manager".
* The initial output was basic, requiring modification for a true scheduling feature.



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")
**2. Iterative Refinement and Widget Enhancement**

To achieve the required functionality, the following modifications were implemented:



* **Custom Input Widget:** Added a new **Time** input widget to capture the approximate duration required for tasks.
* **Prompt Modification:** The core **Schedule** widget's prompt was edited to specifically reference and include the data from both the **New Task Input** and the new **Time** widget.



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")


**3. Key Lesson Learned: The Power of Precision**

This project highlighted the importance of providing precise instructions to Generative AI models.



* **Initial Prompt:** "Generate a daily task manager".
* **Optimal Prompt:** "Generate a daily task scheduler application which takes tasks and time required for tasks as input and provides a schedule, a motivational quote, and a motivational image".
* The optimal prompt would eliminate manual modifications and accelerate the development process.

**III. Skills Summary**


<table>
  <tr>
   <td><strong>Cloud/Technical Skill</strong>
   </td>
   <td><strong>Project Application</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Prompt Engineering</strong>
   </td>
   <td>Wrote specific, interlinked prompts to control AI output, converting simple inputs into structured schedules and personalized tips.
   </td>
  </tr>
  <tr>
   <td><strong>Generative AI</strong>
   </td>
   <td>Successfully integrated and controlled both Text Generation and Image Generation models.
   </td>
  </tr>
  <tr>
   <td><strong>Rapid Prototyping</strong>
   </td>
   <td>Built and published a fully functional application quickly using the AWS PartyRock framework.
   </td>
  </tr>
  <tr>
   <td><strong>UI/UX Design</strong>
   </td>
   <td>Enhanced an AI-generated application by adding critical input fields (Time) and structuring the final output for optimal user experience.
   </td>
  </tr>
</table>


 
