# Journify - Reflect and Discover Yourself

<p align="center">
	<img width="100%" alt="logo" src="https://github.com/user-attachments/assets/6824ce96-6a8f-41a1-9dc8-3b922e53a62e">
</p>

### About Journify 

Journify is a Zen-inspired journal app designed to enhance personal reflection and mindfulness. The app features customizable entries with Notion-style formatting, Zen music, tailored journaling prompts, focus mode, mood tracking, and visualizations through pie charts and calendar views.

### Our Mission

-   Provide users with a serene and intuitive journaling experience
-   Encourage consistent journaling habits through features like streaks and calendar views
-   Help users track and visualize their moods and progress over time

## Development Journey 

---

### Introduction

As a full-stack engineer with expertise in both frontend and backend development, I led the development of Journify from concept to deployment. This involved building the app's core functionality, implementing the Notion-style block editor, integrating dashboards for insights, and ensuring a smooth user experience across all devices.

The Inspiration The inspiration for Journify came from a serendipitous meeting at the Collision Conference in Toronto. There, I met Candice, a talented UI/UX designer. We discovered our shared passion for mindful living and personal journaling, recognizing the value of self-reflection but feeling that existing tools lacked the aesthetic appeal and functionality to make the experience truly fulfilling.

Our Vision Drawing inspiration from Notion's block-style editor, we envisioned bringing this intuitive, flexible format to a dedicated journaling app. We aimed to create a digital space that not only facilitated easy, structured journaling but also resonated with users who appreciate a calm, Zen-inspired environment.

### Key Objectives

1. Encourage regular journaling habits
2. Support mental well-being
3. Appeal to yoga enthusiasts and mindful living practitioners

We believe Journify offers a unique solution for those seeking a more engaging and aesthetically pleasing journaling experience, combining the practicality of digital tools with the mindfulness of traditional journaling practices.

### **Key Features**

Highlight the main features of Journify, such as:

-   **Customizable Entries:** Notion-style formatting using "/" commands.
-   **Zen Music:** Curated playlists for focus, meditation, or relaxation.
-   **Journaling Prompts:** Tailored prompts to inspire reflection.
-   **Focus Mode:** Distraction-free journaling environment.
-   **Streaks and Calendar Views:** Track journaling habits and revisit past entries.
-   **Mood Tracking:** Record and visualize mood patterns with pie charts.
-   **Calendar View:** A comprehensive view of journaling activity over time.

## Design and User Experience 

![mood-board](https://github.com/user-attachments/assets/a86d6e8b-1b10-475e-8e50-e6529d901d14)

The design principles for Journify center around simplicity, elegance, and functionality. We created an intuitive and inviting interface to encourage regular journaling. The app features a clean, minimalist design with a calming color palette inspired by nature, promoting tranquility and focus.

<p align="center"><img height="350" alt="logo" src="https://github.com/user-attachments/assets/1ded6a90-eb6d-4858-9cf4-abb99258e7d4">
</p>

Typography was carefully selected for readability and warmth, while icons and visual elements feature soft, rounded edges to maintain a gentle aesthetic. The Zen vibe influences every aspect of the user interface, from soothing background animations to subtle ambient sounds and nature-themed illustrations.

A distraction-free writing interface, complete with an optional focus mode, allows users to immerse themselves fully in their journaling. Integrated Zen music playlists enhance the overall experience, creating a sanctuary for reflection and mindfulness.

### User Feedback and Iterations 

![research-1](https://github.com/user-attachments/assets/4c3541cc-1005-49a7-8a73-b0eb19f2657b)

Throughout development, we conducted multiple rounds of user testing to refine Journify's design and functionality. Users appreciated the clean interface, praising its ease of use and the positive impact of Zen music playlists on focus and reflection.

![research-2](https://github.com/user-attachments/assets/919f0e55-c03b-4096-a9e5-32fa32afb3b3)

Feedback on the block-style editor led to fine-tuning for improved responsiveness and additional formatting options. Users emphasized the importance of visual consistency, prompting refinements in our color palette and iconography. The focus mode received high praise for creating a distraction-free writing environment.

![research-3](https://github.com/user-attachments/assets/092f829b-951d-4ef6-9f34-945a3d634708)

![research-4](https://github.com/user-attachments/assets/ba5f26b9-8a36-4dc0-aa17-f15383580b2f)

By incorporating this feedback, we've created a user experience that meets and exceeds our target audience's expectations, making Journify a delightful and effective tool for mindful journaling.

## Technical Implementation

### **Technologies and Frameworks Used to Build Journify**

Journify is built using the MERN stack (MongoDB, Express, React, and Node.js). This stack was chosen for its efficiency, scalability, and flexibility in developing both the frontend and backend of the application.

#### **Frontend**

<div style="display: flex; justify-content: space-around; align-items: center; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/8ad7f9b4-df21-480a-8007-87fc5ee520af" alt="React Logo" style="height: 40px; width: auto;">
    <img src="https://github.com/user-attachments/assets/6ccceac2-17e7-41a8-ac40-f7efaa94a26c" alt="Ant Design Logo" style="height: 40px; width: auto;">
     <img src="https://github.com/user-attachments/assets/c2006721-e0f5-4509-881f-ed0e5ec5f70d" alt="Tailwind CSS Logo" style="height: 40px; width: auto;">
      <img src="https://github.com/user-attachments/assets/0ff9b104-f4a0-4ee9-a82f-10755d334c8a" alt="Blocknote Logo" style="height: 40px; width: auto;">
       <img src="https://github.com/user-attachments/assets/9872a0f1-1a9f-48f2-9079-c4fa37c20dbe" alt="Axios Logo" style="height: 40px; width: auto;">
</div>

-   **React:** Provides a robust framework for creating dynamic user interfaces with reusable components.
-   **Vite:** The project uses Vite as the build tool, which offers a faster and leaner development experience compared to traditional tools like Webpack.
-   **Ant Design:** For UI components, we used Ant Design and Ant Design Style. These libraries provide a wide range of pre-designed components, ensuring a consistent and professional look and feel throughout the app.
-   **Tailwind CSS:** Tailwind CSS is used for styling, providing utility-first CSS classes that allow for rapid and responsive design.
-   **@blocknote/react and @blocknote/mantine:** These libraries are used to implement the Notion-style block editor, allowing users to create and format journal entries with ease.
-   **React Router:** For handling navigation and routing within the app, React Router is utilized, ensuring smooth transitions between different views and pages.
-   **Axios:** Axios is used for making HTTP requests to the backend, ensuring efficient data fetching and submission.

#### **Backend**

**\[Logos Here\]**

-   **Node.js and Express:** Express is used to create API endpoints that handle CRUD operations for journal entries and user data.
-   **MongoDB and Mongoose:** MongoDB is used as the database, with Mongoose as the ODM (Object Data Modeling) library. This setup allows for flexible and efficient data modeling and querying.

##### **Database Schemas:**

###### **User Schema**

```
const mongoose = require('mongoose');

const userSchema = new mongoose.Schema(
	{
		name: {
			type: String,
			required: true,
		},
		email: {
			type: String,
			required: true,
			unique: true,
			trim: true,
			lowercase: true,
		},
		password: {
			type: String,
			required: false,
		},
		picture: {
			type: String,
		},
		googleId: String,
		preferences: {
			isDarkMode: {
				type: Boolean,
				default: false,
			},
			fontFamily: {
				type: String,
				default: 'JetBrains Mono, monospace',
			},
			onLoadLastJournalEntry: {
				type: Boolean,
				default: true,
			},
		},
		longestStreak: {
			type: Number,
			default: 0,
		},
		passwordReset: {
			token: String,
			expiryDate: {
				type: Date,
				default: Date.now() + 3600000, // 1 hour
			},
		},
	},
	{ timestamps: true }
);

const User = mongoose.model('User', userSchema);

module.exports = User;
```

##### \*\*Journal Entry Schema

\*\*

```
const mongoose = require('mongoose');

const journalEntrySchema = new mongoose.Schema(
	{
		userID: {
			type: mongoose.Schema.Types.ObjectId,
			ref: 'User',
			required: true,
		},
		title: {
			type: String,
			required: true,
		},
		content: {
			type: String,
			required: true,
		},
		mood: {
			type: String,
			enum: [
				'happy',
				'relaxed',
				'excited',
				'neutral',
				'stressed',
				'sad',
				'angry',
				'anxious',
			],
			required: true,
		},
	},
	{ timestamps: true }
);

const JournalEntry = mongoose.model('JournalEntry', journalEntrySchema);

module.exports = JournalEntry;
```

-   Authentication and Security: For authentication, JSON Web Tokens (JWT) are used, and `bcrypt`  is used for hashing passwords to ensure secure user authentication.
-   Additional Libraries: Other essential libraries include `dotenv`  for managing environment variables, `cookie-parser`  for handling cookies, and `nodemailer`  for sending emails.

#### **Hosting and Infrastructure**

**\[LOGOS Here\]**

-   **Frontend:** Hosted on AWS Amplify, providing a scalable and managed environment for the React application.
-   **Backend:** Hosted on AWS Elastic Beanstalk, ensuring a robust and scalable server environment for the Express application.
-   **Routing:** Managed through AWS Route 53, providing reliable and scalable DNS web service.
-   **HTTPS:** AWS Certificate Manager is used to manage SSL/TLS certificates, ensuring secure HTTPS communication across the application.

## Challenges Faced During Development

---

### **Implementing Notion-Style Formatting:**

One significant challenge was implementing the Notion-style block editor. While using the beta phase library, there was an issue where the editor would re-render completely upon any `onChange` event when it was made controlled, making it difficult to get the values to be typed efficiently.

#### **Solution**

-   Made the editor uncontrolled.
-   Implemented a reducer for central management of all journal data.
-   Developed debounced functions for APIs and state updates to ensure smooth user experience and efficient data handling.

**Journal Data Management:**

```
import React, { createContext, useReducer, useEffect, useContext, useCallback } from 'react';
import { createJournalEntry, getAllJournalEntries } from '../services/journalEntryService';
import { useUser } from '../contexts/UserContext';

// Initial state
const initialState = [];

// Action types
const ACTIONS = {
    ADD_ENTRY: 'ADD_ENTRY',
    UPDATE_ENTRY: 'UPDATE_ENTRY',
    DELETE_ENTRY: 'DELETE_ENTRY',
    SET_ENTRIES: 'SET_ENTRIES',
    RESET_ENTRIES: 'RESET_ENTRIES',
};

// Reducer function
const journalEntriesReducer = (state, action) => {
    switch (action.type) {
        case ACTIONS.ADD_ENTRY:
            return [action.payload, ...state];

        case ACTIONS.UPDATE_ENTRY:
            return state
                .map((entry) =>
                    entry._id === action.payload._id
                        ? { ...entry, ...action.payload }
                        : entry,
                )
                .sort((a, b) => new Date(b.updatedAt) - new Date(a.updatedAt));

        case ACTIONS.DELETE_ENTRY:
            return state.filter((entry) => entry._id !== action.payload);

        case ACTIONS.SET_ENTRIES:
            return action.payload.sort(
                (a, b) => new Date(b.updatedAt) - new Date(a.updatedAt),
            );

        case ACTIONS.RESET_ENTRIES:
            return [];

        default:
            return state;
    }
};

// Create context
const JournalEntriesContext = createContext();

// Provider component
export const JournalEntriesProvider = ({ children }) => {
    const [journalEntriesState, journalEntriesDispatch] = useReducer(
        journalEntriesReducer,
        initialState,
    );
    const { user, logout } = useUser();

    const fetchEntries = useCallback(async () => {
        if (!user?._id || !journalEntriesState?.length === 0) {
            return;
        }
        // Fetch journal entries from the database
        try {
            const journalEntries = await getAllJournalEntries();
            if (journalEntries.length === 0) {
                const firstJournalEntry = await createJournalEntry();
                journalEntries.push(firstJournalEntry);
            }
            journalEntriesDispatch({
                type: ACTIONS.SET_ENTRIES,
                payload: journalEntries,
            });
        } catch (error) {
            console.error('Failed to fetch journal entries:', error);
            if (error?.status === 401) {
                await logout();
            }
        }
    }, [user?._id]);

    useEffect(() => {
        fetchEntries();
    }, [fetchEntries]);

    const journalEntriesCleanup = () => {
        journalEntriesDispatch({ type: ACTIONS.RESET_ENTRIES });
    };

    return (
        <JournalEntriesContext.Provider
            value={{
                journalEntriesState,
                journalEntriesDispatch,
                ACTIONS,
                journalEntriesCleanup,
            }}
        >
            {children}
        </JournalEntriesContext.Provider>
    );
};

export const useJournalEntries = () => {
    const context = useContext(JournalEntriesContext);
    if (!context) {
        throw new Error(
            'useJournalEntries must be used within a JournalEntriesProvider',
        );
    }
    return context;
};
```

### **Token-Based Authentication**

Implementing cookie-based authentication for the first time presented challenges, particularly in understanding and configuring all the cookie options correctly. However, this process significantly enhanced the security and usability of the application.

#### **Auth Token Generation:**

```
function generateAuthToken(user) {
  if (!user || !user._id || !user.email) {
    throw new Error('User object is missing required properties');
  }

  return jwt.sign(
    {
      userId: user._id,
      email: user.email,
    },
    process.env.JWT_SECRET
  );
}
```

By overcoming these challenges, Journify provides a seamless, secure, and responsive journaling experience for its users.

### **Making Tour Component Responsive**

-   The tour component offered by Ant Design was not responsive across devices. Overwriting styles caused issues on cell phones.

    <img src="https://github.com/user-attachments/assets/89f634a5-3847-4631-aca4-4d758f48335e" alt="tour-desktop" style="display: inline-block; width: 350px;">

    <img src="https://github.com/user-attachments/assets/54db513b-ce38-4d87-82e2-1770e9ce6d8d" alt="tour-mobile" style="display: inline-block;">

-   Redesigned the entire tour workflow using @reactour/tour to ensure a seamless and responsive user experience.

## Reflection and Learnings

Working on Journify has been an enriching and transformative experience. This project not only deepened my technical skills but also honed my problem-solving abilities and introduced me to new technologies and best practices in full-stack development.

### **Technical Growth**

1. **Full-Stack Development:** Building Journify from the ground up allowed me to work on both frontend and backend aspects, providing a holistic understanding of web application development.
2. **React and State Management:** Implementing complex features like the Notion-style block editor and ensuring a seamless user experience required advanced knowledge of React and effective state management strategies.
3. **Authentication and Security:** Implementing secure user authentication using JSON Web Tokens (JWT) and bcrypt taught me the importance of robust security measures in web applications.
4. **Responsive Design:** Overcoming challenges with the responsiveness of components, particularly the tour component, enhanced my skills in creating user-friendly and adaptable interfaces.

### **Problem-Solving and Adaptability**

1. **Handling Beta Software:** Working with beta libraries, such as Blocknote, presented unique challenges. Adapting to these limitations and finding workarounds, such as switching to an uncontrolled editor, improved my ability to think on my feet and remain flexible.
2. **Complex Data Management:** Implementing a central reducer for managing journal data and using debounced functions for API calls and state updates taught me efficient ways to handle complex data flows in applications.

### **Collaboration and Communication**

1. **Cross-Functional Collaboration:** Coordinating with team members and understanding different perspectives helped in creating a more cohesive and functional application.
2. **Clear Documentation:** Writing comprehensive documentation and comments for the codebase ensured that the project could be easily understood and maintained by others in the future.

### Future Improvements and Features

As Journify continues to evolve, there are several enhancements and features I plan to add to improve the user experience and functionality:

1. **Advanced Analytics:** Implementing advanced analytics to provide users with insights into their journaling habits and mood patterns over time.
2. **Enhanced Customization:** Adding more customization options for themes, fonts, and layouts to allow users to personalize their journaling space.
3. **AI-Powered Features:** Integrating AI to provide personalized journaling prompts, sentiment analysis, and mood prediction based on journal entries.
4. **Offline Mode:** Implementing offline capabilities to allow users to access and create journal entries without an internet connection, syncing data once connectivity is restored.
5. **Notifications and Reminders:** Adding features for setting reminders and notifications to encourage consistent journaling habits.

Reflecting on this project, I am proud of the progress made and excited about the potential future enhancements. Journify has been a significant milestone in my journey as a developer, and I look forward to continuing to refine and expand its capabilities.

## Conclusion

![low-fedality](https://github.com/user-attachments/assets/43ff2011-7ebd-4d8e-8062-43fa6525d93c)

Throughout this presentation, we explored the development and features of Journify, a comprehensive journaling app designed to enhance user experience and encourage consistent journaling habits. Key highlights include:

1. **Technological Framework:** Journify is built using the efficient and scalable MERN stack, ensuring robust performance and flexibility.
2. **Innovative Features:** From the Notion-style block editor to the responsive design and seamless navigation, Journify offers a rich, user-friendly interface.
3. **Challenges Overcome:** We navigated complex issues, such as integrating beta libraries, managing state efficiently, and ensuring component responsiveness, to create a polished final product.
4. **Security and Authentication:** Implementing secure, token-based authentication and best practices in data protection ensures a safe environment for users' personal entries.

Journify isn't just a journaling app; it's a tool designed to foster mindfulness, self-reflection, and personal growth. By providing users with a versatile and intuitive platform, Journify encourages regular journaling, helping individuals track their moods, document their thoughts, and reflect on their experiences. The app's user-centric design and advanced features make it a valuable addition to anyone's daily routine, promoting mental well-being and productivity.

I invite you to experience the benefits of Journify firsthand. Whether you're looking to improve your journaling habits, track your moods, or simply have a dedicated space for reflection, Journify is the perfect companion. Try the app today and see how it can transform your journaling practice.

For further discussion, collaboration, or feedback, feel free to connect with me. Let's explore how Journify can continue to evolve and meet your needs. Thank you for your time and interest in Journify. Together, let's make mindfulness and reflection a seamless part of everyday life.
