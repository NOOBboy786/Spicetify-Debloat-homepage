# Spicetify-Debloat-homepage

OVERVIEW

This css snipit enhances your Spotify experience by removing unnecessary UI sections and elements, allowing for a more streamlined and personalized interface. Built on the popular Spicetify framework, this project enables users to customize their Spotify client effectively, ensuring that only the most relevant features are accessible.

FEATURES

Remove Unwanted Sections.

Adds Cleanliness

only leaves the songs of the artist which were played by user (you)

INSTALLATION

To get started, ensure you have Spicetify installed on your system. Follow these steps to install Spicetify-Debloat-homepage 

Step 1: Install spotify and hook it with spicetify 

Step 2: Go to marketplace click snippets 

step 3: Click +Add CSS and then on Custom CSS copy past this:

    
     section[aria-label^='Recommended for today'] {
     display: none;
     }
     section[aria-label^='Recommended for you'] {
     display: none;
     }
     section[aria-label^='Throwback'] {
     display: none;
     }
     section[aria-label^='Suggested artists'] {
     display: none;
     }
     section[aria-label^='Try something else'] {
     display: none;
     }
     section[aria-label^='Fresh new music'] {
     display: none;
     }
     section[aria-label^='Featured Charts'] {
     display: none;
     }
     section[aria-label='Today\'s biggest hits'] {
     display: none;
     }
     section[aria-label='Mood'] {
     display: none;
     }

Now give it a name and press Save CSS
the script will load and the home page Will look clean.

ISSUE

spotify being a online music platform it updates the sections each day which means new sections will get it's way to the home screen. To remove them you have to manually add the the line that has been added

     section[aria-label^='Name of section you want to remove'] {
     display: none;
     }

  


