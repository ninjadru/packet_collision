# 00_prologue

ls
nothing
ls -al
nothing
Jane typed the command again. The blank line came back. Expecting a differnt outcome she typed again. it took a full seocnd for he brain to comprehend. The command ls or list returned the contents of the directory that she was in. But there was nothing in this directory. She must be in the wrong directory she thought. She deftly moved her fingers over the keys not looking at the letters affixed to the cheap plastic keyboard. This keyboard was squishy compaired to her usual keyboard. She perfered the IBM model M. She had sought after the older model keyboard that had resigned to ebay autions. The keys of the model m clicked when you typed. It helped her with her rythem. The keys required to be pressed with more force becasue each key had a mechnical switch. The keyboard she was using now employed a rubber membrane with a small glod contact that registered the keypress. The finger pressed the key, the key pressed a black rubber pad, the black rubber pad pressed a gold contact. The contact registered to the button matrix, the matrix went through a usb cable that entered into the port of the server. The operating system registered the keypress and displayed the letter on the black screen.
pwd
Print working directory. This let her know exactly where she was in file system. It let her know which directory she was in. It let her know that there should be a long list of files in this directory. Lots of files, each starting with a numeric time stamp. There should be a list of files. That is how her brain saw it. She no longer thought of the directory as a tree with folders and subfolders. She had gotten past that. She saw it for what it was.
/backups/
Slash backups slash. This was the directory that contained the backups of the servers. This was the directory where a long numeric list of files from each server lived. Yet it was empty there was nothing here. It place of the files was just the . and .. of an empty directory. Placeholders to allow her to navigate up a directory and out of the current directroy. 

She was typing this command from a cheap plastic keyboard perched on a small cart that help a monitor and lifeless mouse. The cart wheeled around a data center. It was called a crash cart. You used it to provide i/o for a server that needed fixed. From a crash that needed fixed. This was not the comfortble wok environment of her desk with the beige IBM model m that she had paid to much on ebay for. The was a data center, you only came here to tuch the metal to fix issues that could not be resolved remotley. You came her to recover from the crash. You came here becasue it was the last resort. 



She had been through this exercise before from her desk. She had typed these commands before, from the comfort of her chair and model m. Now she was standing in the warm row of a dark nosie data center, getting the same results. Her mind was having trouble comprehending this. There were supposed to be backups in this directory. 

She had left her desk for what seemed like an oddity. A small intrigue in her brain. THe thrill of the puzzle. That was probably why she did this work. The puzzle of it. As a child she enjoyed riddles and the cryptogram in the paper. It seemed so long ago to her. The anaconistic nature of the daily paper with its puzzles hit her as she stood up from her desk. She walked out of her dimmly lite office into the hall the floreset lights temporarly blinding her. Down the hall to the stair well. Down the stairs out the side door. Across the grass. The soles of her feet hitting the concret sidewalk of a perfectly maniqured lawn. To building C. Through the doors. Sign in. Badge in. Though several sets of doors. In to the mantrap, then on to the data center.

THe datacenter was dark. Servers did not need to see to do what they were doing. Motion sensore followed Jane's movments and turned over head lights on as she passed row after row. The din was deafing. THere were eight fans in each server on average. Each rack contained ten servers on average. Each row contained fifteen racks on average. This resulted in a dull white noise that downed out sound. Converstation past five feet was pointless. She was not here to talk to the servers however. Well she was in a manner of speaking.  

In 1987 Paul Vixie wrote a modern version of a utility called cron. It was short for chronos, the greek god of time. It allowed an administrator to create a series of commands that would be intiated at a specfic interval of time. These commands were called cronjobs. The way cronjobs were scheduled looked like this:
```
# ┌───────────── minute (0 - 59)
# │ ┌───────────── hour (0 - 23)
# │ │ ┌───────────── day of month (1 - 31)
# │ │ │ ┌───────────── month (1 - 12)
# │ │ │ │ ┌───────────── day of week (0 - 6) (Sunday to Saturday;
# │ │ │ │ │                                       7 is also Sunday on some systems)
# │ │ │ │ │
# │ │ │ │ │
# * * * * *  command to execute
```
This diagram confused and intimidated new users. Many websites exsisted to provide cheatsheets and help understanding the format. They aided junior admins in the fine art of knowing that 
```
*/5 * * * * /home/admin/my_cool_script.sh 
```
Would run every the cool script the admin deemed cool every 5 minutes. Likewise:
```
1,2,3,5,20-25,30-35,59 23 31 12 * *
```
Would run On the  last day of year, at 23:01, 23:02, 23:03, 23:05,23:20, 23:21, 23:22, 23:23, 23:24, 23:25, 23:30,23:31, 23:32, 23:33, 23:34, 23:35, 23:59
Jane knew all this because she was not a junior admin, she was not someone who needed cheatsheets and help understanding the idosancriaces of cron. If for some reason she couldn't remeber a patricular detail she used the built in man.

man cron

She knew all this because she was not a junior admin. She was the senior systems adminrator for GTAC bioengineering. She knew all this beacuse it made sense to her. She saw it in her head. She spoke this archanaine language. She did not translate like some rosetta stone. She did not need to translate it. Slash etsie was the directory in which system configurations were held. /etc. She did not think the directory where system configs are held ten translate that to /etc. She just knew you went to /etc. She knew the same way she knew her native tongue english. It just was. The signifer stood in place of the sign. She knew cron and she knew that had written cronjobs across all the servers. Her script would execute at the time she persribed. A time illustrated by five * signs. Signifed equallys sign. She knew that she had written these cron jobs to stager the backups not to flood the pipe. She knew that if every server tried to write a rather large system back up all at once the amount of data flowing through the network would be to great. There was a bottleneck and she had deftly written around it. Her backups did not flood the pipe they did not exhust available tcp connections. Her backup moved smoothly and cascaded throughout the datacenter resulting in a nightly backup that worked like clockwork. Like cron work. She knew all this. And as she slammed her hand to the crashcart knocking it over, the crash barely audible over the din of hundreds of servers. She slid to the ground the warm air hitting her face. She knew all this. She knew that there was supposed to be a list of files each starting with a numeric datestamp in this directoy. She knew all this. She knew it was all gone.  

