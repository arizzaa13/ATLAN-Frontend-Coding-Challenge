# Atlan Front End Coding Challenge

> Given the recent surge in interest in AI models and LLMs, tasked with building an application that showcases the various models deployed by organisations and developers alike.

### Hosted at: https://mohdarman-atlanfrontendchallenge.netlify.app/

----------

### 1. Overview: How I went about completing this challenge

| Breakdown  |   |
|---|---|
| Ideation 💡  |  The challenge as I saw it was have been tasked with building an application that showcases the various models deployed by organisations and developers alike.Having Interest in AI related content I was very excited to work on such kind of interface building Task  |
| Design 🧑🏻‍🎨  | The most intuitive way to develop this application was with a `Main Page layout` - with clear sections for Home, Models, Case Studies, Resources, Contact. With having a Main Heading at the Middle of the site "Explore AI Models" makes user interested to go through the complete website. After this users can see some of the models that they are shown at the screen and can follow to choose a right Subscription plan . After this there is a FAQ section which contains some common questions on AI Models |
| Implementation ⚒️  |  With a focus on good Interface and Functionality, I decided to add different appropriate sections to the webpage, be it "Get Started" ,"Learn More","Login","Register" followed by display of different models and different Subscription plans that users might be interested in and some common FAQ questions which makes the website more engaging to users. |

----------

### 2. Specification

- JavaScript framework used = **React**
----------

### 3. Page load time

I used Chrome Dev Tool's `Performance Insights` to measure perceived load time. The two metrics I looked are are: First Contentful Paint (FCP) and Largest Contentful Paint (LCP).
- FCP is when the browser renders the first bit of content from the DOM, providing the first feedback to the user that the page is actually loading.
- LCP is when the browser renders the largest visual pieces on the DOM, in our case this would be the Main page layout etc.
- LCP < 2.5 seconds is absolutely must for a good user experience. Less than 1 second leads to great user experience.


|   |   |
|---|---|
| During my testing (on a DELL Inspiron I5 3000 Interl core), the score I got was between **0.93** (always under 0.95s)   |  ![image](https://github.com/arizzaa13/ATLAN-Frontend-Coding-Challenge/assets/78647475/fa5b07a6-86d6-48ec-8c45-b369056a499b) |


----------

### 4. Optimizations

- I was able to avoid loading any heaving external assets (images, etc), but in a real product this may not be always possible
- Though the task didn't ask for mobile-optimization, I made sure the application was responsive and I did very basic mobile optimizations (removed the sidebar to allow for more screen space for the query and output). Given more time, I could definitely make it mobile optimized.



### 5. Screengrabs

| Main Page Layout  | Middle Section |
|---|---|
|![image](https://github.com/arizzaa13/ATLAN-Frontend-Coding-Challenge/assets/78647475/4d0d6b92-f1c9-428e-a43b-485ebc72ccc3) | ![image](https://github.com/arizzaa13/ATLAN-Frontend-Coding-Challenge/assets/78647475/91884b18-9c9c-4b96-96a9-59ef6da877a0) |

