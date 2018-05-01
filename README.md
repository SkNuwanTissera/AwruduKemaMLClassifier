# AwruduKemaMLClassifier
This is a trained classifier used to identify Awrudu food e.g : kokis,kewun . Dataset is also included in the repository

#Sk Nuwan Tissera
#IT15120212

dataset : https://drive.google.com/file/d/1ea1sTcsIRjk0JYW69-bnELqHW7DdNmR-/view?usp=sharing
download from this link and paste inside awrudu_kema folder

then
#for retrainnig
run

python retrain.py
\
--bottleneck_dir=tf_files/bottlenecks
\
--how_many_training_steps=500
\
--model_dir=tf_files/models/
\
--summaries_dir=tf_files/training_summaries/"${ARCHITECTURE}"
\
--output_graph=tf_files/retrained_graph.pb
\
--output_labels=tf_files/retrained_labels.txt
\
--image_dir=tf_files/awrudu_kema

#How to Run
go inside scripts folder
run 'python my.py <input image path>'

