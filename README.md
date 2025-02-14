## Web Portal for SME Business Listings, Reviews, and Consumer Insights (Mauritius)  
This repository contains the codebase for a **React-based web portal** designed to help SMEs in Mauritius list their businesses, receive user reviews, and gain consumer insights. The project also integrates an AI-powered chatbot for user interaction and assistance.  

### Features  
- **SME Business Listings**: Create and manage business profiles.  
- **User Reviews & Ratings**: Collect and display feedback from users.  
- **Consumer Insights Dashboard**: Analyze data to provide useful insights for SMEs.  
- **AI Chatbot Integration**: Offers instant support and guides users through the platform.

### Tech Stack  
- **Front-End**: React, Tailwind CSS  
- **Back-End**: Node.js, Express.js  
- **Database**: MongoDB  
- **AI Chatbot**: Dialogflow (or Python-based NLP with TensorFlow)  
- **API Testing**: Postman  

### Folder Structure  
```
├── public/                  # Static assets  
├── src/  
│   ├── components/          # React components  
│   ├── pages/               # Application pages  
│   ├── services/            # API calls and services  
│   ├── chatbot/             # Chatbot integration files  
│   ├── utils/               # Utility functions  
│   └── styles/              # Global styles  
├── package.json             # Project configuration  
└── README.md                # Project documentation  
```

### Key Functionalities  
1. **Business Registration & Listings**:  
   - SME owners can register and manage their listings.  
   - Includes categories, contact details, and service descriptions.  

2. **User Reviews & Ratings**:  
   - Registered users can leave reviews and rate SMEs.  
   - Displays average ratings and recent reviews on each business profile.  

3. **Consumer Insights Dashboard**:  
   - Interactive data visualization for SMEs.  
   - Provides information like user demographics and feedback trends.  

4. **Chatbot Integration**:  
   - Answers frequently asked questions.  
   - Helps users search for SMEs and navigate the platform easily.  

### Installation & Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/alfred-moyo/final-year-project.git
   ```  
2. Navigate to the project folder:  
   ```bash
   cd Final Year Project
   ```  
3. Install dependencies:  
   ```bash
   npm install
   ```  
4. Start the development server:  
   ```bash
   npm start
   ```  
   The web portal will be available at `http://localhost:3000`.  

5. (Optional) For chatbot integration, ensure your API key and configuration file are set up correctly in `chatbot/config.js`.  

### Future Enhancements  
- Advanced sentiment analysis for reviews.  
- Integration with payment gateways for premium business listings.  
- Multi-language support for chatbot and web portal.  
