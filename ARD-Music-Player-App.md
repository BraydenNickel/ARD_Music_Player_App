ARD For Music Player App
Brayden Nickel


Issue: The issue for this music player application is deciding on which technology stack is used for the applications back end.

Decision: The backend architecture of the Music Player App will include the following 

Status: Approved

Group: Backend Architecture 

Assumptions: 
The backend needs to support user registration, user login, music library management and playlist management
The backend needs to be scalable to handle potential growth in users
The backend need to ensure data security and privacy for users data

Constraints: 
Time and resources may impact the choice of backend
Backend should be capable of being integrated with the selected NoSQL database
Backend technologies should align with the selected technology stack 

Positions: 
Use Node.js for backend 
Use MongoDB as the NoSQL database for user storage

Argument: 
Node.js is the selected backend technology because of its event-driven nature and is good at handling real-time operations. Node.js is compatible with front-end frameworks such as Xamarin providing smooth integration
MongoDB is selected as the NoSQL database because of capabilities in handling unstructured data. MongaDB is scalable therefore it can handle future user growth

Implications: The use of Node.js and MongoDB requires a deep understanding for smooth development and long term maintenance 

Related decisions: None

Related requirements: Make sure the backend is responsive and scalable to support user activities and data.

Related artifacts: None created

Related principles: These decisions align with the principle of selecting technologies that promote scalability, performance and smooth development

Notes: None
