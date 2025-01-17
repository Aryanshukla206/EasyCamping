
# Easy Camping 🌲🏕️  

**Easy Camping** is a responsive and user-friendly web application designed to provide a seamless platform for campers to discover, explore, and review campgrounds. Whether you're a seasoned camper or a first-timer, Easy Camping simplifies your camping experience by offering a curated list of campgrounds along with user-generated reviews, ratings, and recommendations.

## Features ✨  

- 🌟 **Explore Campgrounds**: Discover beautiful camping spots with detailed descriptions, images, and pricing information.  
- ⭐ **User Reviews and Ratings**: View and contribute reviews and ratings for campgrounds.  
- 🖼️ **Dynamic Carousel**: Showcase multiple images of campgrounds using a dynamic image carousel.  
- 📍 **Integrated Map**: Locate campgrounds easily with a fully functional map integration.  
- 🔐 **Authentication**: Secure user registration and login functionality.  
- 🛠️ **CRUD Operations**: Users can create, edit, and delete their campgrounds and reviews.  
- 🌐 **Responsive Design**: Works seamlessly across all devices.  

## Technologies Used 💻  

- **Frontend**:  
  - HTML5, CSS3, JavaScript  
  - Bootstrap for UI components and responsiveness  
- **Backend**:  
  - Node.js with Express.js  
  - EJS for server-side templating  
- **Database**:  
  - MongoDB Atlas for storing campground and user data  
- **Map Integration**:  
  - Mapbox API for interactive maps  
- **Authentication**:  
  - Passport.js for user authentication  
- **Hosting**:  
  - Vercel for deployment  

## Screenshots 📸  

### Home Page  
![Home Page]([https://drive.google.com/file/d/11k42u5EzZxSazfJC6s1X547qcLgu8id4/view?usp=sharing](https://imgur.com/a/CaoVjxX))  

### Campground Details  
![Campground Details](https://via.placeholder.com/800x400)  

### Leave a Review  
![Leave a Review](https://via.placeholder.com/800x400)  

## Getting Started 🚀  

Follow these steps to run the project locally:  

### Prerequisites  
- Node.js and npm installed  
- MongoDB Atlas account for database setup  
- Mapbox API key for map integration  

### Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/username/easy-camping.git
   cd easy-camping
   ```  

2. Install dependencies:  
   ```bash
   npm install
   ```  

3. Set up environment variables:  
   Create a `.env` file in the root directory and add the following:  
   ```env
   MAPBOX_TOKEN=your_mapbox_api_key  
   MONGODB_URI=your_mongodb_connection_string  
   SESSION_SECRET=your_secret_key  
   ```  

4. Seed the database (optional):  
   Run the provided seed script to populate the database with sample data:  
   ```bash
   node seeds/index.js
   ```  

5. Start the server:  
   ```bash
   npm start
   ```  

6. Visit the application at:  
   ```  
   http://localhost:3000  
   ```  

## Contributing 🤝  

Contributions are welcome! Please fork this repository and submit a pull request with your changes.  

## License 📜  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

## Live Demo 🌐  

Check out the live demo of the application: [Easy Camping](https://easy-camping.vercel.app/)  

---

Feel free to customize this based on the specifics of your project. Let me know if you'd like me to include more details!
