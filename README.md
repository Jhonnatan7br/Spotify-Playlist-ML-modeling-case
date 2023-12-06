# Project	 

### Context	

Music streaming services have changed the way we listen to music. Platforms like Apple Music and Spotify allow us to enjoy music anytime and anywhere. You can create your own playlists, share them with your friends, and even share your subscriptions with family.
As a data analyst team at Spotify, you are responsible for managing multi-user accounts, also known as family accounts. These accounts are associate with a single subscription for multiple users, who retain the ability to create their own playlists and access personal music statistics.
On the morning of November 21, Spotify's servers were attacked by hackers. The hackers deleted users' Top-of-the-Year playlists from family accounts. These users find themselves faced with a huge playlist that mixes everything. If users on the same family account have exactly the same musical taste, that's fine. But who would listen to exactly the same thing as their parents or roommates?
Fortunately, you were able to recover some of the deleted data from Spotify's servers. The recovered data contains parts of the Top-of-the-Year playlists of different users. But some songs from the huge mixed playlist are still missing from the recovered data.
Your mission is to reconstruct each user's Top-of-the-Year playlists for each year.

### Data
	 
First, you have the single playlist that mixes everything:
mixed_playlist.csv
Some songs in this CSV file have already been labeled with the corresponding user and top year according to the recovered data.
Some songs are missing from the recovered data, so the user and top year remain unkown.
Then, you have the recovered parts of the Top-of-the-Year playlists of different users.
CSV files in the recovered_data folder.

These playlists are not complete.
You need to reconstruct each playlists.
For each song, your team created a number of characteristics to describe this song. These characteristics can also be found in every CSV file.

### Tasks

Reconstruct the Top-of-the-year playlists for different users.
As a data analyst, your team also need to develop algorithms that recommend the next song to users. The song the user is currently listening to is an important reference. The user's music taste in previous years can also be used as a basis for recommendations. Please suggest several characteristics of song that can be used as input features for the recommendation algorithm and justify your proposal.

### Note: Before starting
It is important to notice that every single data extraction from mixed playlist were made taking into account the following location of the file, inside of a folder called 'data'

mixed_playlist = pd.read_csv('data/mixed_playlist.csv')

#### Note: Before starting 

It is important to notice that every single data extraction from mixed playlist were made taking into account the following location of the file, inside of a folder called 'data'

mixed_playlist = pd.read_csv('data/mixed_playlist.csv')

![image.png](attachment:image.png)

The distribution of this Jupiter Notebook is the following

![image-2.png](attachment:image-2.png)

![image-3.png](attachment:image-3.png)

The final output will be a folder called 'Playlists' with all the playlists for each user and each year, with the same structure as 'recovered_data' folder

At the end it was proposed an accesing to the users playlist throught dictionaries 


The distribution of this Jupiter Notebook is the following

image-2.png

image-3.png

The final output will be a folder called 'Playlists' with all the playlists for each user and each year, with the same structure as 'recovered_data' folder

At the end it was proposed an accesing to the users playlist throught dictionaries
