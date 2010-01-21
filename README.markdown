Herd Fire - Firefox profile helper
==================================

A simple Python script to help you set up separate Firefox apps for
different profiles, making it possible to run several profiles
side-by-side.

#### Basic instructions ####

1. Start with setting up a named copy of Firefox (in this case, we'll
   call it “example”):  
   `$ cd /Applications`  
   `$ cp -r Firefox.app Firefox-example.app`  
2. Run herdfile: `$ ./herdfile` (from the folder where herdfile is
   located).
3. Launch Firefox-example.app via double-click or your faviorite way
   launching applications.
4. If there is not a Firefox profile with the extra name you gave your
   Firefox.app copy (in this case “example”), the profile manager will appear.
   In that case, use it to create a new profile with the correct name.
5. Firefox-example.app will now always start with the “example” profile
   activated. Firefox auto updater might break this. In that case, all
   you need to do is to run `$ ./herdfile` again.

P.S.: Firefox.app will be set to start with the profile named “default”.
If you have not been using multiple profiles before, this should be the
name of your original profile.

