- create app by using create-react-app app_name
- Dependencies: Import necessary libraries and components like react-router-dom and react-toastify.
- Component Structure: App function component serves as the entry point.
- Toast Notifications: Integration of toast notifications using ToastContainer.
- Routing: Setup routes with BrowserRouter and Routes.
- Navbar: Includes navigation links via Navbar component.
- Routes Configuration: Configure routes for pages (Login, Registration, TicketList).
- Styling: Apply CSS classes from App.css.
- Export: Export App as default for use.
- Login component handles user authentication.
- Navigation:
  Uses useNavigate hook from react-router-dom to navigate between pages.
- Context Integration:
- Utilizes context API through useUser custom hook to access and update user data.
- Effect Hook:
- Utilizes useEffect hook to clear session storage on component mount.
- Validation:
- Implements a validation function to ensure both username and password are provided.
- Form Submission:
- Submits user credentials to the server for authentication using Axios.
- User Interface:
  Renders a table displaying ticket information with options for editing, removing, and assigning tickets based on user roles.