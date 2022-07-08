# Perforce-User-Instructions

### 1) Install [P4V](https://www.perforce.com/products/helix-core-apps/helix-visual-client-p4v)

### 2) On opening P4V, this window will show up.

<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/177272559-e8777425-a0e9-4395-add0-29527b09ab63.png" width=50% height=50%>
</p>

Enter the Details as given by your Admin.

### 3) You will have to create a new Workspace for your self as sharing a Workspace with multiple users can create issues.
To do this, Inline to the Workspace section, click on the new Button. This window will pop up.

<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/177273127-7b0d443d-cda8-4aeb-a7b3-eb51853c66ac.png" width=50% height=50%>
</p>

The 2 Checkboxes may or may not be there. If they are available make sure to enable both of them.

For your Workspace name Follow the naming convention of your Organization

For those in the MIT Gaming Club use this naming Convention: UserName_Dev

Leave the Workspace root as is

Choose the Stream Assigned For you (MIT Gaming Club members select the Dev Stream)

### 4) In the top left corner, Click on the Advanced Tab. The window should now change to this: 

<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/177274267-111f528a-19b9-4a1e-be73-f899a29f31e6.png" width=50% height=50%>
</p>

Enable Rmdir

Change 'On Submit' to 'Revert Unchanged Files'

Hit OK

### 4.5) Go to your Terminal and Enter this Command to get the P4Ignore file working properly.(This has to be done by all users)
```
p4 set P4IGNORE=.p4ignore
```

### 5) When you open P4V now, it should look similar to this: 

<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/177275940-922792c0-a171-45d2-9131-0b061ac42af6.png" width=75% height=75%>
</p>

Go to the Workspace tab, Select the Folder and then click on the "Get Latest" Icon to ensure that you get the latest project files.

<p align="center">
  <img src="https://user-images.githubusercontent.com/65004578/177276235-eead9331-e740-4117-af17-124a6ee2e839.png" width=90% height=90%>
</p>

### 6) (Optional for those in the Blender Dept) From this point on, You can follow along this [Video](https://youtu.be/7PRo8gK6SNM)
 This will show you how to connect to the server through UE5 and some of the other basic ways to use Helix Core
