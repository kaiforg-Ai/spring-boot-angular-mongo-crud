# Angular Student Management System

A comprehensive CRUD (Create, Read, Update, Delete) application built with Angular for managing student information. This project demonstrates best practices in Angular development including component architecture, routing, services, and authentication.

## Features

- User Authentication (Login/Logout)
- Student Management:
  - Add new students
  - View student details
  - Update student information
  - Delete students
  - List all students with filtering capabilities
- Responsive Design
- Custom Pipes for data formatting
- Route Guards for authentication
- Directive for student highlighting

## Technologies Used

- Angular
- TypeScript
- SCSS for styling
- W3.CSS Framework
- Angular Router for navigation
- Angular Services for state management

## Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── home/
│   │   ├── index/
│   │   ├── login/
│   │   └── student/
│   │       ├── add/
│   │       ├── details/
│   │       └── list/
│   ├── directives/
│   ├── pipes/
│   └── services/
│       ├── auth/
│       ├── config/
│       ├── student/
│       └── user/
└── assets/
```

## Getting Started

### Prerequisites

- Node.js (version 12.x or higher)
- npm (version 6.x or higher)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kaiforg-Ai/spring-angular-portfolio-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd spring-angular-portfolio-project
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   ng serve
   ```

5. Open your browser and navigate to `http://localhost:4200`

## Development

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Features in Detail

### Authentication

- Login system with route guards
- Session management
- Secure routing

### Student Management

- Complete CRUD operations
- Form validation
- Real-time filtering
- Detailed student profiles

### Custom Pipes

- Phone number formatting
- Search filtering

### Directives

- Student highlighting based on conditions

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
