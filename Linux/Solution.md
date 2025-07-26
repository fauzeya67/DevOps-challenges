### Create two directories with name linux and Aws in /.
<img width="1910" height="180" alt="linux-practice1" src="https://github.com/user-attachments/assets/2d5ddecb-9d1c-4046-89b3-cf3c42fb00ec" />

''' bash
mkdir Aws
mkdir linux
'''
### Inside the folder2 directory,Create one empty file named file1.txt
<img width="1901" height="170" alt="linux-practice2" src="https://github.com/user-attachments/assets/6c4422a2-c9a8-45d2-9b15-a3a253b38109" />

'''bash
touch file1.txt
'''
### Create a file named notes.txt using the cat command
<img width="1899" height="138" alt="linux-practice3" src="https://github.com/user-attachments/assets/fcd5be5f-87cf-4a54-8bf4-c8a88a863ce4" />

'''bash
cat > notes.txt
'''
### Create a file named index.html using the echo command
<img width="1895" height="153" alt="linux-practice4" src="https://github.com/user-attachments/assets/2966aa83-71f1-4903-b575-9a94840080ed" />

'''bash
echo "Hello,This is my file" > index.html
'''
### Copy the content of notes.txt into file1.txt
<img width="1898" height="285" alt="linux-practice5" src="https://github.com/user-attachments/assets/af5a866f-6b92-4267-b58e-3d53f2852b6b" />

'''bash
cp notes.txt /home/ubuntu/folder2/file1.txt
'''
### Move file1.txt into the /Aws directory
<img width="1896" height="144" alt="linux-practice6" src="https://github.com/user-attachments/assets/3ad44dcd-c828-49e9-89be-f5ca710dca0f" />

'''bash 
mv /home/ubuntu/folder2/file1.txt Aws
'''
### Rename index.html to error.html
<img width="1894" height="142" alt="linux-practice7" src="https://github.com/user-attachments/assets/7d88e8e6-fff8-4763-ab9c-e76ae87b11ff" />

'''bash
mv index.html error.html
'''
