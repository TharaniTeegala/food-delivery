# Lessons:



## 2. Creating React App
## 3. Adding Header
## 4. Adding Thumbnails
## 5. Adding Search
## 6.Adding Tags Bar

### Showing The Tags
### Showing Foods By Tag
## 7. Food Page
## 8. Cart Page

- [x] Create Cart Page Component
  - [x] Create css
- [x] Add cart route to the Routes
- [x] Create useCart Hook
  - [x] Add CartProvider to index.js
  - [x] Initialize cart with sample foods
- [x] Update Cart Page Compnent
  - [x] useCart hook
  - [x] Add Title Component
  - [x] Add JSX
  - [x] Add CSS
- [x] Update useCart Hook
  - [x] Add to cart
  - [x] Remove from cart
  - [x] Change quantity
  - [x] Saving To LocalStorage
- [x] In Food Page useCart for Add to cart buttons
- [x] In Header useCart for cart total count

## 9.Not Found!

- [x] Create NotFound Component
  - [x] Add CSS
- [x] Add Not Found To:
  - [x] Home Page
  - [x] Food Page
  - [x] Cart Page
- [x] Fixing Search Issue

## 10. Connect To Backend

- [x] Create backend folder
- [x] Initializing NPM Project
- [x] Copy data.ts to backend/src
- [x] npm install express cors
- [x] Create .gitignore
- [x] Create server.js
  - [x] Add & Config Express
    - [x] Add & Config Cors
  - [x] Add Food Router
    - [x] Add jsconfig.json
    - [x] Add Apis
- [x] npm install nodemon
  - [x] Add dev Script into the package.json
  - [x] npm run dev
- [x] Add axios package
  - [x] axiosConfig.js file
- [x] Connect food service to the Apis

## 11. Login Page

### Backend
### Frontend

- [x] Create user service
  - [x] Add getUser function
  - [x] Add login function
  - [x] Add logout function
- [x] npm install react-toastify
- [x] Create useAuth hook
  - [x] Add user state
  - [x] Add Login function
  - [x] Add logout function
- [x] Create LoginPage component
  - [x] Add to AppRoutes.js
  - [x] Create Custom Components
    - [x] Input Container
      - [x] CSS
    - [x] Input
      - [x] CSS
    - [x] Button
      - [x] CSS
- [x] Add useAuth to the Header component

## 12. Connecting MongoDB

### Installation

- [x] Install Mongo Db Community
  - [x] Windows
  - [x] Macos

### Coding

- [x] Install mongoose
  - [x] Add User Model
  - [x] Add Food Model
- [x] Add .env file
  - [x] Install dotenv
  - [x] Add MONGO_URI
  - [x] Add to .gitignore
- [x] Add database.config.js
  - [x] Connect to mongodb
  - [x] Seed Users
    - [x] Install bcryptjs for password hashing
  - [x] Seed Foods
- [x] Update user.router ( Using UserModel)
  - [x] Install express-async-handler
  - [x] Login Api
  - [x] generateTokenResponse
- [x] Update food.router (Using FoodModel):
  - [x] Root Api ( Loading all foods )
  - [x] Tags api
  - [x] Search Api
  - [x] FoodId api ( Finding food by id )
- [x] Fix Image url in:
  - [x] Thumnails compnent
  - [x] Food Page component
  - [x] Cart Page component

## 13. Register Page

- [x] Add Register Page Component
  - [x] Add to AppRoutes
  - [x] Add Link to login page
  - [x] CSS
- [x] Add '/register' api to user.router.js
- [x] Add register function in userService
- [x] Add register function in useAuth hook
  - [x] Add to Register page

## 14. Loading

- [x] Create useLoading hook
  - [x] Add LoadingProvider to index.js
- [x] Create Loading component
  - [x] Add to App.js
  - [x] Add Image
  - [x] CSS
- [x] Create Loading Interceptor

## 15. Checkout Page

- [x] Fixing Loading problem
- [x] Create Checkout Page component
  - [x] Create AuthRoute
  - [x] Add to Routes
  - [x] Add css
  - [x] Create Order Items List
  - [x] Create Maps Component
    - [x] Install leaflet & react-leaflet
    - [x] Adding images to public folder
    - [x] Fixing header menu problem with map
- [x] Create Order router

  - [x] Create auth middleware
    - [x] Add UNAUTHORIZED http statuss
    - [x] Add to Order router
  - [x] Create Order Model
    - [x] Create Order Status
  - [x] Add to server.js

- [x] Connecting Frontend to Backend
  - [x] Create order service
    - [x] Add create function
  - [x] Create Auth interceptor
    - [x] Add to index.js

## 16. Payment Page

- [x] Create PaymentPage component
  - [x] Add to Routes
  - [x] CSS
- [x] Update Order Router
  - [x] Add newOrderForCurrentUser
  - [x] Add pay api
- [x] Create PaypalButtons Component
  - [x] npm install @paypal/react-paypal-js
  - [x] Add clearCart to useCart
  - [x] Get clientId
  - [x] Create Sandbox user for testing

## 17. Order Track Page

- [x] Create Order Track Page
  - [x] Add To Routes
  - [x] CSS
  - [x] Create DateTime Component
    - [x] Complete
  - [x] Map
    - [x] Fixing Marker Icon Issue
  - [x] Complete
- [x] Order Router
  - [x] Add ‘track/:id’ api
    - [x] Add to orderService

## 18.Profile Page

- [x] Create ProfilePage Component
  - [x] CSS
  - [x] Update Profile
  - [x] ChangePassword component
- [x] Update useAuth hook
  - [x] Add updateProfile function
  - [x] Add changePassword function
- [x] Update userService
  - [x] Add updateProfile funciton
  - [x] Add changePassword function
- [x] Update User Router
  - [x] Add updateProfile api
  - [x] Add changePassword api

## 19. Orders Page

- [x] Create Orders Page
  - [x] Add To Routes
  - [x] CSS
- [x] Update Order Service
  - [x] Add getAll function
  - [x] Add getAllStatus function
- [x] Update Order Router
  - [x] Add `/:status?`
  - [x] Add `/allStatus/:id`
