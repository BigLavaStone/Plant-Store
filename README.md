        <Route path="/plant-house" element={<Login />} />
        <Route path="/" element={<Login />} />
        <Route path="/profile" element={<PrivateRoute> <Profile /> </PrivateRoute>} />
        <Route path="/contactus" element={<PrivateRoute> <ContactUs /> </PrivateRoute>} />
        <Route path="/product/:id" element={<PrivateRoute> <UserRoleBasedRender /> </PrivateRoute>} />
        <Route path="/home" element={<PrivateRoute> <Home /> </PrivateRoute>} />


      "email": "admin@example.com",
    "password": "adminpass",


   email": "user1@example.com",
    "password": "user1pass",


    email": "user2@example.com",
    "password": "user2pass",



