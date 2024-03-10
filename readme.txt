The modules were move to a modules folder
Modules:
notify.py
result.py
sites.py

the files that host the main functionality is sherlock.py which is imported in main file and ran

In __main__.py there is a main function that is called and executed, that function is in sherlock.py

flow of the code

__main__ get executed first it calls the main function in sherlock.py and in there the modules and function in them are called and executed there

sherlock.py isn't easy to understand because
1. the files is way too long, there are hundreds of lines of code in each line almost
2. There isn't enough docoummentation 
3. There isn't a readme file that texplain what the code is supposed to do
4. There isn't any type hinting to tell us what type of variable each function takes
for example this code on line 100 in sherlock.py def get_response(request_future, error_type, social_network):
5. The code isn't organized properly, should split the code into more files