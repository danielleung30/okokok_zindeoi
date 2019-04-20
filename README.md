Take a Fucking Look pls


pip3 install tensorflow/ run in anaconda
 (I don't use shit like Anaconda so I don't know it's work or not.)
 
terminal cd to cloned folder

run python3 -m scripts.label_image \
    --graph=tf_files/retrained_graph_star_wars.pb  \
    --label=tf_files/retrained_labels_star_wars.txt \
    --image=tf_files/star_wars/darth_vader/test.jpeg(or whatever darth varder/stormtrooper picture,only accept jpeg,png,gif)

Expected result:

darth vader (score=0.80737)
stormtrooper (score=0.19263)

using Google Codelabs
modify project-- https://github.com/googlecodelabs/tensorflow-for-poets-2


