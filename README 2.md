You can use this to begin converting your midterm files to Sass.

You will need a GitHub Repository for the Final. You can either use your midterm repository, or, if you named it something like midterm, then create a new repository.

## Starting with an Existing Repository

### Step 1: Commit
You should have done this already, but, BEFORE you begin, make sure you've commited any past work.

### Step 2: Add the Sass files
Copy the **scss** folder from this repository (240-final-starter folder) into your repository's folder.

### Step 3. Start a Sass Application
Start Scout, PrePros or whatever you're using, and make sure it is watching your final project folder

### Step 4. Copy your CSS into the _midterm.scss file
Go into the .css file you used on your midterm and Select all, cut and paste into _midterm.scss.

If you cut here, it will be very clear that the next step works because Sass will write in new CSS.

### Step 5. Rename your Sass files to match your CSS
In this repository the main stylesheet is named screen.scss. If your midterm's main stylesheet was named something else, like mystyle.css, then change screen.scss to mystyle.scss.

So you should now have a Sass .scss file in the scss folder with the same name as your midterm's css file.

Also Sass should rewrite your css file in the css folder after you make the change.

**Remove reset in your HTML files**  
Now that you're linking to the Sass created CSS file (which already has reset in it), you don't need to link to reset.css with a `<link rel="stylesheet" href="css/reset.css">` element in the HTML files. You should delete it.

### Step 6. Check to see if your Page Renders
Your page should now show how it was on the midterm. If it doesn't then you have something to fix somewhere.

### Step 7. Move Your CSS from `_midterm.scss` to Separate Partial Files
Do this as you see fit and where it makes sense. You might want to move your navigation to _navigation.scss, or your page specific css to one the the files in the pages folder.

You are not required to move everything. Move what makes sense to you and create new _partial files if that makes sense too (remember to add @import for them if you do).

## Starting with a New Repository
If you are creating a new repository then:

### Step 1: Start Your Own GitHub Repository for the Final
Go to GitHub.com and create, and initialize a new repository.

### Step 2. Clone the Repo to Your Local Computer
Also open up the folder the clone created when you're done.

### Step 3: Move Your Midterm HTML, Image and JavaScript Files in Place
Copy those files from your midterm folder and paste them into the new repo you just created in the previous step.

We won't deal with the __css__ folder for a few steps. Leave it for now

**Remove reset in your HTML files**  
Now that you will link to the Sass created CSS file (which already has reset in it), you don't need to link to reset.css with a `<link rel="stylesheet" href="css/reset.css">` element in the HTML files. You should delete it.

### Step 4. Move the `scss folder` from into the new Repo
Copy the scss folder from the 240-final-starter and paste it into the new Repository.

### Step 5. Start a Sass Application
Start Scout, PrePros or whatever you're using, and make sure it is watching your final project folder

### Step 6. Rename your Sass files to match your CSS
In this repository the main stylesheet is named screen.scss. If your midterm's main stylesheet was named something else, like mystyle.css, then change screen.scss to mystyle.scss.

So you should now have a Sass .scss file in the scss folder with the same name as your midterm's css file.

Also Sass should rewrite your css file in the css folder after you make the change.

### Step 7. Copy your CSS into the _midterm.scss file
Go into the .css file you used on your midterm and Select all, copy and paste into _midterm.scss. Remember to save.

### Step 8. Check to see if your Page Renders
Your page should now show how it was on the midterm. If it doesn't then you have something to fix somewhere.

### Step 9. Move Your CSS from `_midterm.scss` to Separate Partial Files
Do this as you see fit and where it makes sense. You might want to move your navigation to _navigation.scss, or your page specific css to one the the files in the pages folder.

You are not required to move everything. Move what makes sense to you and create new _partial files if that makes sense too (remember to add @import for them if you do).






