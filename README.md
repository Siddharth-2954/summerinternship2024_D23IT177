
# summerinternship2024_D23IT177


## 4th Sem Summer Internship
Summer Internship - Project

Welcome to my GitHub repository for the Summer Internship 2024! This file showcases the work done during the internship.

## 🚀 Introduction
## 10𝘵𝘩 𝘔𝘢𝘺 2024  
Joining the internship was an exhilarating experience. Learning about the projects was inspiring. I'm excited to gain valuable skills and knowledge during my time here.

# Start of Internship

## 1️⃣week 1

𝟏𝟎𝙩𝙝 𝙢𝙖𝙮 𝟐𝟎𝟐𝟒 

* The project expense management system allows users to track their income and expenses over customizable time periods, from the last week to a month or a year. Users can view their financial data in table and graph formats for a clear understanding of their transactions.

## 📝 Day-by-Day Progress
#### ╰┈➤Day 1: Environment Setup and Project Initialization
- **Tasks:**
  - Set up the project environment for the expense management system.
  - Installed necessary dependencies for React development.
  - Used Vite for the application setup.
- **Commands:**
  - Initialized the application using: `npm create vite .`

#### ╰┈➤Day 2: Development of Signup Page with Ant Design
- **Tasks:**
  - Developed the signup page using React.
  - Integrated Ant Design components for the signup form.
  - Implemented form validation.
  - Gained new experience using Ant Design UI library.
  - Ant Design is a React.js UI library with easy-to-use components for building interactive user interfaces.

#### ╰┈➤Day 3: Creation of Login Page and Client-side Validation
- **Tasks:**
  - Created the login page using React.
  - Integrated Ant Design for consistent UI.
  - Implemented client-side validation for login credentials.

#### ╰┈➤Day 4: Server-side Setup with Express.js and MongoDB
- **Tasks:**
  - Installed Express.js for server-side setup.
  - Configured the server to handle user signup requests.
  - Set up interaction with MongoDB for data storage.
- **Commands:**
  - For server-side setup, used: `npm init -y` to create `package.json`.

#### ╰┈➤Day 5: Integration with MongoDB and User Authentication
- **Tasks:**
  - Integrated MongoDB to store user data securely.
  - Implemented user authentication and login functionality on the server using Node.js and Express.
- **Integration Details:**
  - Created a `.env` file to store environment variables.
  - Accessed environment variables in server-side files using: `process.env.URL_name`.
  - For authentication, used `jsonwebtoken` library and `bcrypt` for password encryption.

#### ╰┈➤Day 6: Testing, Debugging, and Integration Testing
- **Tasks:**
  - Conducted thorough testing and debugging.
  - Ensured seamless interaction between the React frontend, Express backend, and MongoDB database.

### Note:
* https://www.npmjs.com/package/jsonwebtoken
* https://www.npmjs.com/package/bcrypt
* https://www.npmjs.com/package/antd

## 2️⃣ week 2
𝟏8𝙩𝙝 𝙢𝙖𝙮 𝟐𝟎𝟐𝟒

* Beginning week two, our primary objective is to enhance the home page interface for our EMS project. We are keen on creating a customized transaction display and improving visual representation with graphics.

## 📝 Day-by-Day Progress
#### ╰┈➤Day 1: Planning and Initial Setup
- **Tasks:**
  - Plan the overall structure of the home page layout.
  - Set up the initial project environment.
  - Integrate basic components for the tabular representation of data.
- **Commands:**
  - `npx create-react-app ems-project` - Create a new React project.
  - `npm install antd` - Install Ant Design for UI components.
  - `npm install react-table` - Install necessary packages for tabular representation.

#### ╰┈➤Day 2: Tabular Representation Implementation
- **Tasks:**
  - Continue work on the tabular representation of data using Ant Design's Table component.
  - Ensure data is correctly fetched and displayed in tables.
- **Commands:**
  - `npm install axios` - Install Axios for data fetching.
  - `import { Table } from 'antd';` - Use Ant Design's Table component.

#### ╰┈➤Day 3: Graphical Representation Integration
- **Tasks:**
  - Complete the integration of graphical representation using charts.
  - Start working on the Modal component for user interactions.
- **Commands:**
  - Imported Analytics components from antd for graphical representation.
  - `import { Modal } from 'antd';` - Use Ant Design's Modal component.
  - Use `toFixed()` to format numerical values for better precision in charts.

#### ╰┈➤Day 4: Modal Enhancements
- **Tasks:**
  - Improve the Modal component with additional features such as form inputs or interactive elements.
  - Refine the graphical representation for better visualization.
- **Commands:**
  - Enhance the Modal component:
    ```javascript
    // Example of Modal with form inputs
    <Modal title="User Interaction" open={isModalVisible} onOk={handleOk} onCancel={handleCancel}>
      <Form>
        <Form.Item label="Input" name="input">
          <Input />
        </Form.Item>
      </Form>
    </Modal>
    ```

#### ╰┈➤Day 5: Testing and Debugging
- **Tasks:**
  - Conduct thorough testing of all components implemented so far.
  - Debug any issues found during testing.
- **Commands:**
  - `npm run dev` - Run the test suite.

#### ╰┈➤Day 6: Documentation and Conclusion
- **Tasks:**
  - Document the progress made during the week.
  - Summarize key achievements, challenges, and lessons learned.


 ## 3️⃣ week 3
27𝙩𝙝 𝙢𝙖𝙮 𝟐𝟎𝟐𝟒

* From the third week of my internship, I have been tasked with a new project titled "Product Management System" using the MERN stack.This application allows you to manage products through CRUD operations (Create, Read, Update, Delete) and provides a user-friendly interface for browsing and managing products.

## 📝 Day-by-Day Progress

#### ╰┈➤ Day 1 : Builting Signup and Login Page
- **Task :**
  - Build and Signup Page in react using antd components.
  - Making of backend for signup using express and node js, learned about new libraries like, jsonwebtoken and bcrypt for token generation and password encryption 
  - Learned about establishing connection between node js and mongodb using config file by making database.js file.
  - Built knowledge about api making and authentication and routes. 
#### ╰┈➤ Day 2 : Optimizing Signup and Login Handler
* **Task :**
  * Initializing the Auth.js file for making handlers.
  * Learn about hashing function of npm used for hasing password using .hash()
  * Checking for existing user and creating new user using api routes.
  * Validating data filled by user for authenticating.
  * Verifiying password for logging in.


#### ╰┈➤ Day 3 : Initializing middlewares and creating evironment for frontend work in React⚛️
 * **Task :**
   * Checking for client role and building routes according to client's input.
   * Initializing signup and login page in `.jsx` file.
   * Fetching Information from backend about the details filled by user.
   * Learn about `Axios` library in react, and started using postman for various request send from backend and converting it in react for seamless use.
   * Used `POST` method for signing in.
   * Used Ant Design for some styling and required components such as Form, Input, etc..

#### ╰┈➤ Day 4 : Completion of Dashboard and Add/Edit/Delete Operations
 * **Task :**
    *  Initialized dashboard.jsx
    * Initialized header, content, and footer components
    * Header includes user name, project name, and logout button
    * Initialized footer component
    * In this format, the "add edit product" has been implemented with the following fields:
      - Title: ''
      - Description: ''
      - Price: ''
      - Category: ''
    * After adding the product, it is then mapped on the screen using the `.map` function in JavaScript.
    * Useful Links :
      * https://react.dev/reference/react/useEffect 

#### ╰┈➤ Day 5 : Displaying the user added products 
 * **Task :**
    *  Initialized ProductCard.jsx, ProductList.jsx
    * ProductList.jsx is used for displaying added products, while ProductCard.jsx is that products user defined.
    * ProductCard.jsx contains product Id which redirct to the product current status.
    * Were user can add the product to cart.
    * This is the progress made for the day.

#### ╰┈➤ Day 6 : Documenting and debugging day 
 * **Task :**
    *  Document the progress made during the week.
    * Summarize key achievements, challenges, and lessons learned.
    * Debugged the login and signup page more user friendly.

## 4️⃣ week 4
3𝙧𝙙 𝙟𝙪𝙣𝙚 𝟐𝟎𝟐𝟒
  * Completion of the remaining stuff for the project such as making the routes and api's arranging products details according to the required css making the website responsive and debugging.

## 📝 Day-by-Day Progress

#### ╰┈➤ Day 1: Website Checking and Learning Start
* **Task :**

  * Checked the website to ensure that items are being properly added
  - Identified that the product image is not showing and started working on solving the error
  - Began learning about React components and Express
 
    
#### ╰┈➤ Day 2: Troubleshooting and System Review
- Continued troubleshooting and working on solving the product image error
- Explored more about React components and practiced implementing them
- Reviewed the expense management system and noted areas for improvement
- Made some changes in Bootstrap CSS for the product management system
