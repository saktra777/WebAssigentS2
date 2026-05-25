### For Frontend 
* * create a **.env.local** file
```
VITE_STRIPE_PK="pk_test_51PspJwFtTKweNYCI84TL7PeV0qN6YECcM5vKaBvPecd2PanNCLqDmmm7xeOeOzKOupxb9iAIoVfCXHR6FrFvEMlQ00CO1HnLuq"
```
+ Then run `` npm install `` commend to install node dependencies.
- Finally, to run the project, use ``npm run dev`` command.

### For Backend
+ Run `` npm install ``
* create a **.env** file 
```
MONGODB_URL = ''

JWT_SECRET_KEY = ""

STRIPE_SECRET_KEY="sk_test_51Po3X5LV8UbWx9Ij1HIwJYniRLps8gZmfOFXrBcwQk1BH204TvdKiV4U0odayxpetPKNfxyGz0nacOLMTQobNg0H00bxcsoqEY"

CLOUDINARY_CLOUD_NAME="dn2gccqlw"
CLOUDINARY_API_KEY="791369242134249"
CLOUDINARY_API_SECRET="zH4Ix2R_WM-DWG_Vr3ZAECUPlmE"

Note: Please setup mongodb and change the MongoDB url and set your jwt secret key above.
- Finally, to run the project, use ``npm run start:dev`` command.
