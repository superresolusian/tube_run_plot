Hello! Here is a (hopefully) handy guide to downloading Strava data and using it to create a map of all of the London Underground stations that you have run to.

# Getting data from Strava
I manually downloaded all of my run files from Strava about four months after completing the runs. This was very boring so I recommend doing it as you go along!
You need to download your run files from Strava on a computer (not mobile) - you'll need to go to each activity, press the three dots on the left, and then press Export original. This should download a file with extension .fit

<img width="1041" height="449" alt="image" src="https://github.com/user-attachments/assets/5d27f3a5-663e-40ff-a964-0e0d120b4503" />

You should organise them by tube line (i.e. which colour you want that run plotted as - obviously loads of stations are more than one line, so just pick one). My folder structure looks like this:

<img width="501" height="316" alt="image" src="https://github.com/user-attachments/assets/8a7ca9ee-344d-49d1-8eda-ca936f1a8fb9" />

Try and keep the folder names the same as in my example so the code doesn't break :-)
I also put them all into an 'all' folder as well for versatility when I was messing around with plotting.

# Running the code
I've provided the code as a jupyter notebook, but it can be easily changed to a python fit. Your python environment will need jupyter (if using), numpy, matplotlib and a library called fitdecode (https://pypi.org/project/fitdecode/) which reads the files. 

To run the jupyter notebook, just put it into the same folder as you have the line name subfolders where you've saved all the files and run each cell. If you uncomment (delete the # from) "#plt.savefig('runderground.png', dpi=600)" it should save as a png for you.

Drop me a message if you need a hand getting the code running!!
