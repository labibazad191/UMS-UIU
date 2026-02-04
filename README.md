🏛️ University Management System - UIUDeveloped by Labib Azad📝 Project OverviewThe University Management System (UIU) is a comprehensive academic platform built with Angular. It offers a streamlined interface for managing student records, course enrollments, and academic operations. Leveraging a modular architecture and Firebase integration, the system ensures real-time data synchronization and secure access control.✨ Key FeaturesStudent Management: Full CRUD operations (Create, Read, Update, Delete) for student profiles.Course Management: Efficient handling of course catalogs and academic details.Secure Authentication: Robust login and registration powered by Firebase Auth.Responsive Design: A mobile-first UI that adapts seamlessly to any screen size.Scalable Architecture: Built with Angular best practices for future maintainability.🛠️ Tech StackLayerTechnology UsedFrontendAngular (vLatest), TypeScript, RxJSBackend/DBFirebase Realtime Database / FirestoreAuthenticationFirebase AuthStylingSCSS / Angular MaterialTestingJasmine & Karma📂 Project StructurePlaintextUniversity-Management-System-UIU/
├── src/
│   ├── app/                # Core logic, components, and services
│   ├── assets/             # Static images and global styles
│   └── environments/       # Firebase configuration keys
├── angular.json            # Angular CLI configuration
├── firebase.json           # Firebase hosting settings
├── package.json            # Dependencies and scripts
└── tsconfig.json           # TypeScript compiler settings
🚀 Installation & Setup1. Clone the repositoryBashgit clone <your-repository-url>
cd University-Management-System-UIU
2. Install Dependencies Bash npm install
3. Configure FirebaseCreate a src/environments/environment.ts file and add your Firebase credentials:TypeScriptexport const environment = {
  production: false,
  firebase: {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
    appId: "YOUR_APP_ID"
  }
};
4. Run the ApplicationBashng serve
Navigate to http://localhost:4200/ in your browser.🧪 TestingTo run the unit tests via Karma:Bashng test
👨‍💻 AuthorLabib AzadPortfolio: labibazad.vercel.appRole: Full Stack Developer (Angular & PHP)Open to collaborations and professional opportunities.