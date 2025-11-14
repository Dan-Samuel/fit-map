# FitMap 🏋️‍♂️

A modern, user-friendly fitness platform that helps users discover nearby gyms, track their fitness goals, and manage their workout routines.

![FitMap Logo](./Resources/Resource%20Images/53819-removebg-preview.png)

## 📱 About FitMap

FitMap is a comprehensive fitness companion application designed to make finding and booking gyms easier than ever. Whether you're looking to lose weight, gain muscle, or maintain your fitness, FitMap connects you with the best gym centers in your area.

## ✨ Features

### 🔐 User Authentication
- **Sign Up**: Create a new account with email and password
- **Sign In**: Secure login with remember me option
- **Password Reset**: Easy password recovery with verification code
- **Profile Management**: Edit personal information and fitness goals

### 🏢 Gym Discovery
- **Nearby Gyms**: Find gyms close to your location
- **Interactive Map**: Visual representation of gym locations
- **Gym Details**: View gym information, facilities, and ratings
- **Filter & Search**: Filter gyms by category and distance

### 💪 Fitness Tracking
- **Weight Tracking**: Monitor your weight progress
- **Goal Setting**: Set and track fitness goals (Lose Weight, Gain Muscle, Stay Fit, etc.)
- **Activity Monitoring**: Keep track of your workout routines

### 🗺️ Location Services
- **Location Search**: Search gyms by area
- **Distance Calculation**: See how far gyms are from you
- **Multiple Locations**: Switch between different areas in Port Harcourt

### ⚙️ Account Settings
- **Personal Information**: Update your profile details
- **Password Management**: Change your password securely
- **Language Options**: Multi-language support (coming soon)
- **Privacy & Security**: Manage your privacy settings

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with custom properties and animations
- **JavaScript (ES6+)**: Interactive functionality and logic
- **LocalStorage API**: Client-side data persistence
- **Responsive Design**: Mobile-first approach (optimized for 480px max-width)

## 📂 Project Structure

```
Fit-Map/
│
├── fit-map splash.html              # Landing/splash screen
├── fit-map onboarding.html          # Onboarding carousel
├── fit-map signup.html              # User registration
├── fit-map signin.html              # User login
├── fit-map reset password.html      # Password reset request
├── fit-map code verification.html   # OTP verification
├── fit-map create new password.html # New password creation
├── fit-map home dashboard.html      # Main dashboard
├── fit-map nearby gyms.html         # Gym listings
├── fit-map map location.html        # Map view of gyms
├── fit-map user profile.html        # User profile page
├── style.css                        # Global stylesheet
├── README.md                        # Project documentation
│
└── Resources/
    ├── Resource Images/             # Image assets
    ├── Resource Icons/              # Icon assets
    └── Resource Fonts/              # Custom fonts
        ├── Lora/                    # Lora font family
        └── Inter/                   # Inter font family
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, but recommended)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/yourusername/fitmap.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd fitmap
   ```

3. **Open with a local server**
   - Using VS Code Live Server extension
   - Using Python: `python -m http.server 8000`
   - Using Node.js: `npx serve`

4. **Access the application**
   - Open your browser and go to `http://localhost:8000`
   - Or simply open `fit-map splash.html` directly in your browser

## 💾 Data Storage

FitMap uses browser LocalStorage for data persistence:
- **User Accounts**: Stored in `fitMapUsers`
- **Current User**: Active session in `currentUser`
- **Fitness Data**: Personal fitness info in `fitnessData_[userId]`
- **Preferences**: User location and settings

> **Note**: All data is stored locally in your browser. Clearing browser data will remove all stored information.

## 🎨 Design System

### Color Palette
- **Primary**: `#271c65` - Deep purple
- **Secondary**: `#b8acfa` - Light lavender
- **Background**: `#f8f7fa` - Off-white
- **Surface**: `#fcfcfc` - Pure white
- **Text Primary**: `#0a0a0a` - Near black
- **Text Secondary**: `#333333` - Dark gray
- **Accent**: `#666666` - Medium gray

### Typography
- **Primary Font**: Lora (Regular, Medium, SemiBold, Bold)
- **Secondary Font**: Inter (Various weights)

### Spacing
- Small: `8px`, `12px`
- Medium: `16px`, `20px`
- Large: `24px`, `30px`, `40px`

## 📱 Responsive Design

FitMap is optimized for mobile devices with a maximum width of 480px. The application features:
- Touch-friendly buttons and controls
- Mobile-optimized navigation
- Responsive images and layouts
- Smooth transitions and animations

## 🔒 Security Features

- Password strength validation
- Email format verification
- Session management with localStorage
- Verification code system for password reset
- Secure password reset flow

## 🌟 Key Features Breakdown

### Authentication System
1. **Sign Up Flow**
   - Full name, email, and password validation
   - Terms and conditions acceptance
   - Duplicate email checking
   - Automatic login after registration

2. **Sign In Flow**
   - Email and password verification
   - Remember me functionality
   - Error handling for invalid credentials

3. **Password Reset Flow**
   - Email verification
   - 6-digit OTP generation
   - Code expiration (10 minutes)
   - Resend code functionality
   - Password strength requirements

### Dashboard Features
- **Profile Display**: User initials and information
- **Location Selection**: Choose from multiple Port Harcourt areas
- **Notifications**: Badge counter for new alerts
- **Search**: Find gyms and workouts
- **Feature Cards**: Quick access to main features

### Gym Features
- **Gym Cards**: Visual display with images and details
- **Distance Sorting**: Nearest gyms appear first
- **Category Filters**: Filter by gym type
- **Gym Details**: Name, location, distance, description, facilities

## 🐛 Known Issues

- Social login (Google, Apple) not yet implemented
- Map integration uses placeholder (ready for Google Maps API)
- Some workout features are placeholders ("Coming Soon")

## 🚧 Future Enhancements

- [ ] Backend integration with real database
- [ ] Google Maps API integration
- [ ] Social media login (Google, Apple, Facebook)
- [ ] Push notifications
- [ ] Workout plan generation
- [ ] Personal trainer booking
- [ ] In-app gym booking and payment
- [ ] Activity tracking with charts
- [ ] Community features (reviews, ratings)
- [ ] Multi-language support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@Dan-Samuel](https://github.com/Dan-Samuel)
- Email: samueldan.ij@gmail.com

## 🙏 Acknowledgments

- Font families: Lora and Inter
- Icons: Custom icon set
- Images: Fitness stock photos
- Inspiration: Modern fitness applications

## 📞 Support

For support, email support@fitmap.com or open an issue in the GitHub repository.

---

**Made with 💪 by:
[Samuel Ifiok Daniel]
[Saviour Koki]
[Wilson Albert]
[Ugopadou Ebi]
[Oritom Braide]**

*Last Updated: November 2025*
