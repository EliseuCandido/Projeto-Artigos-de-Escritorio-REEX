
___
## Group #5
### Members: 
- Eliseu Caixeiro Candido
- Esther Caixeiro Candido
- Ruben Filipe Alves
- Xavier dos Rodrigues
### Project theme: Office material shop
___
## General Remarks
- The project should have:
    - **Frontend**: a website with 3 or more pages and a navigation bar that allows to navigate between them;
    - **Backend**: a ``node js`` project with a an ``express js api``;
    - **Database**: a ``json`` file in the filesystem containing the data;
- When delivering the project:
    - The ``json database`` should have some data so the application doesnt look empty;
    - **Do not** send the ``/node_modules`` folder generated by the node js project (takes a lot of space and can be reconstructed using the command ``npm install``);
- A `.zip` file containing the code should be attached to the MS Teams assignment until **03/07 at 23:59h** (only 1 group member should send the project);
- During the last class on **06/07** each group will make a small demonstration of their application (**20min**), all group members should talk and showcase their contribution to the project;

<br/>

## Business Requirements
- Create an application that manages data in the context of a **Office material shop**;
- The app should have at least 3 pages: home page, about us, contact us;
    - The ``home`` page should have the data management operations 
        - It is encouraged to have more than 1 page for this or to use popups\modals for the forms, however having everything in the same page is also ok
    - The ``about us`` page should contain information about the group members and the website (static content is ok);
    - The ``contact us`` page should contain some information regarding the members' emails and atecs address (static content is ok);
- The app's pages should consider the business of the application in the theme's design;
- When entering the page it should be possible see a list or grid of the respective entries (products);
- It should be possible to add entries, a form should be displayed (either on a popup modal or in the same page), this form should contain the fields that need to be inserted;
- Before adding a new entry, the fields should be validated (required check, minimum character length check)
- It should be possible to update the fields and save the changes of existing entries;
- It should be possible to delete existing entries;

## Technical Requirements
- The entries should have at least 4 fields (eg: name, description, category, image, etc..);
- In case you add images to your products (it is encouraged), use public images' URLs (there is no need to add any image upload feature)
- It should be possible to manage the respective data by inserting\updating\listing\deleting the entries;
- The express js api needs at least 4 endpoints (one for each **CRUD** operation);
- The backend should have 2 files: one for the api (`api.js`) and another for the database operations (`db-repo.js`);
- The `json` database file should be named ``database.json``;
- External libraries are allowed for both backend and frontend; (eg. [bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/));

___

## Suggested Resources
[Github repo](https://github.com/ATEC-ORG/TPSI-PL0922-5414)
<br/>
