# How to Cove Your Project Blog from Azure ➡️ GitHub


## Prerequisite Steps (REQUIRED)
<div>
  <ul>
    <li>Download Filezilla from <a href="https://filezilla-project.org/download.php?type=client">here</a> and install it!</li>
    <li>Log into Azure Portal.</li>
  </ul>
</div>

## Step 1: 
### In Azure, navigate to ```App Services```

<img src="./Images/Step1.png"/>

## Step 2: 
### Navigate to your Web App

<img src="./Images/Step2.png"/>

## Step 3: 
### Navigate to the ```SSH``` tab and press ```Go```

<img src="./Images/Step3.png"/>

## Step 4: 
### Enter the following exactly as it appears:
```cp -R /var/www/html /home/site/wwwroot/MySite```

<img src="./Images/Step4.png"/>

## Step 5: 
### In Azure, navigate to ```App Services``` and your Web App

<img src="./Images/Step5.png"/>

## Step 6: 
### Press ```Download Publish Profile``` on the upper bar

<img src="./Images/Step6.png"/>

## Step 7: 
### Navigate to your ```Downloads``` folder
### Open the new file with Notepad. What you're looking for is the url, username, and password for FTP.
### This will be located right after ```publishMethod="FTP"``` (There are multiple url/user/pwd combos, you only want the one for FTP)
#### Use the image below as a reference:

<img src="./Images/Step7.png"/>

## Step 8: 
### Copy the username, pwd, and url into another empty text file

<img src="./Images/Step8.png"/>

## Step 9: 
### Open Filezilla, paste in the info at the top, and press ```QuickConnect```
### (The ```publishUrl``` is used for the ```host``` field)

<img src="./Images/Step9.png"/>

## Step 10: 
### On the right half of Filezilla, navigate to the ```MySite``` folder
### (Located at ```/site/wwwroot/MySite```)
### You'll see your site's ```index.html``` file

<img src="./Images/Step10.png"/>

## Step 11:
### Right click your ```index.html``` and press ```Download```

<img src="./Images/Step11.png"/>

## Step 12:
### You've successfully downloaded your index file!

<img src="./Images/Step12.png"/>

## Step 13:
### Head to GitHub and log in
### Press the ➕ icon at the top right, and press ```New repository```

<img src="./Images/Step13.png"/>

## Step 14:
### Give the repo a name and a description
### Make sure the repo is public, and press ```Create repository```

<img src="./Images/Step14.png"/>

## Step 15: 
### Press ```uploading an existing file```

<img src="./Images/Step15.png"/>

## Step 16:
### Press ```choose your files```, and upload your ```index.html``` 
### Make sure to press ```Commit changes```

<img src="./Images/Step16.png"/>

## Step 17: 
### Congrats, you've successfully copied your site files to a Github Repo!

<img src="./Images/Step17.png"/>
