
**Agenda:**
- Explanation of the System Architecture
- Server Components and Their Functions
- Use of React Native for Communication
- Overview of Pro App and Admin Portal
- Utilization of Intercom, Twilio, Segment, Postmark
- Low-Level Diagram and Server Setup
- 10 Key Features and Approach

**Discussion Highlights:**

1. **System Architecture:**
   - The discussion started with an overview of the entire system architecture, emphasizing its complexity and interconnections.
   - The system is built using various server components that collaborate to provide the desired functionality.

2. **Server Components and Functions:**
   - The server components include the new group server, load-balanced groomy server, restful API server managed by Nginx, and more.
   - Nginx repositories handle routing and distribution of requests.

3. **React Native Communication:**
   - React Native is utilized for communication with the private server.
   - The app functions like Uber, where one side is the client and incoming requests, and the new approach is discussed.

4. **Priv App and Admin Portal:**
   - The Priv App serves as a platform similar to Uber for job assignments and communication.
   - Admin Portal was mentioned as a tool to manage various aspects of the system.

5. **Intercom, Twilio, and Other Services:**
   - Intercom is used for real-time customer service and communication.
   - Twilio is employed for communication services.
   - Segment is used for tracking values and analytics between sources and providers.
   - Postmark is utilized for mail transfer.

6. **Server Setup and Low-Level Diagram:**
   - A low-level diagram was shared, illustrating the distinct servers such as S3, MongoDB, Lambda, etc.
   - The Lambda function is dedicated to serving clients, and the digital ocean is used for data storage.

7. ** Key Features and Approach:**
   - Essential features were discussed, focusing on the approach for their implementation.
   - Example was given, such as a frontend button for a particular feature.

**Action Items:**

1. Further refine the low-level diagram to ensure clarity.
2. Explore options to enhance the scalability of the system.
3. Collaborate with the development team to outline the specifics of each feature's implementation.
