# Project-4- The Good-HairDAY app


## Objective

This app has the purpose of planning hair salon services to customers via appointments & also providing information to customes about 
diffrent types of hairservice that is offered and the prices.

## User Stories 

1. As a user I want to be able to create an account or login 
2. As a user I want to land on a page that has info on all the diffrent types of hairservices that is offered
3. As a user I want to be able to select a hair style and land of a details page
4. As a user I want to be able to hsve a button on the details page that takes me to another page to set up appointment 
5. As a user i want a message that desplayes that the appointment was made
6. As a user I want appointment info to be sent to the hair stylist 
7. As a user I want to have a page that shows the appointment I made

## Technologies Used 
- Django & Django rest framework (Backend)
- Sql database (backend)
- React Framework (frontend)
- Css 
- Html
- BootStrap


## Models 

1. User 
-id -Name -email -password [appointmet] [Hair style]

2. Appointment
-id -Date -time -Location [Hair Style]

3. HairStyle
-id -name -photo -Description 


## Wireframes 

![Landing Page](https://user-images.githubusercontent.com/99228361/188244497-9bbd880b-a2e4-4e47-937c-8e39127def0e.png)

![Index Page](https://user-images.githubusercontent.com/99228361/188244415-ab8631c1-98fe-4548-bc8f-7bf6909653d8.png)

![Details Page (1)](https://user-images.githubusercontent.com/99228361/188244521-81185534-0a89-4474-911f-6dc946bb6fc5.png)

![My Appointments](https://user-images.githubusercontent.com/99228361/188244547-aeea00a3-4831-4dab-b9c4-f99cc8e29f5e.png)


## MVP's

-CRUD across app


## Stretch Goals

1. The ability to not only set apponitments but also take payment
2. The ability to add more than one hair stylist 
3. The ability to have reminders as appointmnet date approches 
4. The ability to have membership plans and payment plans according to membership status 

## Additional Info
- I plan to use my Django app as the backnd api as well as the google calandar Api to plan the appointments in the app.





