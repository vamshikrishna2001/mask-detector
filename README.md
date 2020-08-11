# mask-detector #Pytorch #openCV

This is a simple mask detector trained with minimal number of examples eventhough
it works fine in bright light if it is night make sure you got torchlight with you.
You can make more robust my collecting more data,adding more convolutional layers and using reguralizations like 
dropout and batchnormalization etc..
dataset used is https://github.com/prajnasb/observations/tree/master/experiements/data
Make sure after getting the dataset sort the dataset according to torch requirements as
train -->1.with mask
         2.without mask
test -->1.with mask
         2.without mask         
make sure you have named the folders properly.
