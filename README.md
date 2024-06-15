
# summerinternship2024_D23IT177


## 4th Sem Summer Internship
🌟Summer Internship - Project 🌟

Welcome to my GitHub repository for the Summer Internship 2024! This file showcases the work done during the internship.

## 🚀 Introduction
## 10𝘵𝘩 𝘔𝘢𝘺 2024  
Joining the internship was an exhilarating experience. Learning about the projects was inspiring. I'm excited to gain valuable skills and knowledge during my time here.

# Start of Internship

## 1️⃣week 1

𝟏𝟎𝙩𝙝 𝙢𝙖𝙮 𝟐𝟎𝟐𝟒 

* The project expense management system allows users to track their income and expenses over customizable time periods, from the last week to a month or a year. Users can view their financial data in table and graph formats for a clear understanding of their transactions.

## 📝 Day-by-Day Progress
### Day 1: Environment Setup and Project Initialization
- **Tasks:**
  - Set up the project environment for the expense management system.
  - Installed necessary dependencies for React development.
  - Used Vite for the application setup.
- **Commands:**
  - Initialized the application using: `npm create vite .`

### Day 2: Development of Signup Page with Ant Design
- **Tasks:**
  - Developed the signup page using React.
  - Integrated Ant Design components for the signup form.
  - Implemented form validation.
  - Gained new experience using Ant Design UI library.
  - Ant Design is a React.js UI library with easy-to-use components for building interactive user interfaces.

### Day 3: Creation of Login Page and Client-side Validation
- **Tasks:**
  - Created the login page using React.
  - Integrated Ant Design for consistent UI.
  - Implemented client-side validation for login credentials.

### Day 4: Server-side Setup with Express.js and MongoDB
- **Tasks:**
  - Installed Express.js for server-side setup.
  - Configured the server to handle user signup requests.
  - Set up interaction with MongoDB for data storage.
- **Commands:**
  - For server-side setup, used: `npm init -y` to create `package.json`.

### Day 5: Integration with MongoDB and User Authentication
- **Tasks:**
  - Integrated MongoDB to store user data securely.
  - Implemented user authentication and login functionality on the server using Node.js and Express.
- **Integration Details:**
  - Created a `.env` file to store environment variables.
  - Accessed environment variables in server-side files using: `process.env.URL_name`.
  - For authentication, used `jsonwebtoken` library and `bcrypt` for password encryption.

### Day 6: Testing, Debugging, and Integration Testing
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
#### Day 1: Planning and Initial Setup
- **Tasks:**
  - Plan the overall structure of the home page layout.
  - Set up the initial project environment.
  - Integrate basic components for the tabular representation of data.
- **Commands:**
  - `npx create-react-app ems-project` - Create a new React project.
  - `npm install antd` - Install Ant Design for UI components.
  - `npm install react-table` - Install necessary packages for tabular representation.

#### Day 2: Tabular Representation Implementation
- **Tasks:**
  - Continue work on the tabular representation of data using Ant Design's Table component.
  - Ensure data is correctly fetched and displayed in tables.
- **Commands:**
  - `npm install axios` - Install Axios for data fetching.
  - `import { Table } from 'antd';` - Use Ant Design's Table component.

#### Day 3: Graphical Representation Integration
- **Tasks:**
  - Complete the integration of graphical representation using charts.
  - Start working on the Modal component for user interactions.
- **Commands:**
  - Imported Analytics components from antd for graphical representation.
  - `import { Modal } from 'antd';` - Use Ant Design's Modal component.
  - Use `toFixed()` to format numerical values for better precision in charts.

#### Day 4: Modal Enhancements
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

#### Day 5: Testing and Debugging
- **Tasks:**
  - Conduct thorough testing of all components implemented so far.
  - Debug any issues found during testing.
- **Commands:**
  - `npm run dev` - Run the test suite.

#### Day 6: Documentation and Conclusion
- **Tasks:**
  - Document the progress made during the week.
  - Summarize key achievements, challenges, and lessons learned.
