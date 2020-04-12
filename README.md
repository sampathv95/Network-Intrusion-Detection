# Network-Intrusion-Detection
Autoencoder approach to detect attacks/intrusions in a network
For detailed explanation of the approach, please refer to my medium article: https://medium.com/@sampathv95/network-intrusion-detection-using-autoencoders-b276b674e15a?sk=076209f356972bd3e12fe51bc617aa28

Data sets can be downloaded from the links below
1. training data: http://kdd.ics.uci.edu/databases/kddcup99/kddcup.data.gz
2. test data: http://kdd.ics.uci.edu/databases/kddcup99/corrected.gz
3. column names: http://kdd.ics.uci.edu/databases/kddcup99/kddcup.names
4. unlabeled data (a.k.a production data): http://kdd.ics.uci.edu/databases/kddcup99/kddcup.newtestdata_10_percent_unlabeled.gz

After downloading the training and test data set, rename them as 'kdd_train.csv', 'kdd_test.csv', 'column_names.txt' and 'kdd_prod.csv' respectively and place them in the same directory as the notebook and saved model.

For some reason if you don't want to have them in the same directory, please specify the appropriate path in the notebook.
