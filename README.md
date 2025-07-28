# Linux basics course
## Basic Linux commands 


<img width="1000" height="380" alt="image" src="https://github.com/user-attachments/assets/e0f78580-8ee9-4c03-b042-a0201664ff96" />


pwd (present working directory)

    pwd
    /home/michael

Ls (List Contents)

    ls

mkdir (make a new directory)

    mkdir Asia

mkdir (multiple directory)

    mkdir Europe Africa America

ls (List contents)

    ls
    Asia Europe Africa America

cd (change directory)

    cd Asia

    pwd
    /home/michael/Asia

    mkdir India?Mumbai

    mkdir -p India/Mumbai

Goto Home Directory 

    cd ..
or

    cd

or

    cd /home/michael


### Absolute and Relative Path

    pwd
    /home/michael

Absolute Path

    cd /home/michael/Asia

Relative Path

    cd Asia

### Pro Tip- pushd/popd

    [~] pushd /etc
    /etc ~

    [/etc] cd /var
    [/var] cd /tmp

    [/tmp] popd
    [~]

 ![homw](assets/image-2.png)
 ![push](assets/image-1.png)
 ![pop](assets/image-3.png)