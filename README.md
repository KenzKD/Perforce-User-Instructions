# Perforce-User-Instructions

### 1) Install [P4V](https://www.perforce.com/products/helix-core-apps/helix-visual-client-p4v)

### 2) On opening P4V, this window will show up.

![image](https://user-images.githubusercontent.com/65004578/177272559-e8777425-a0e9-4395-add0-29527b09ab63.png)

Enter the Details as given by your Admin.

### 3) You will have to create a new Workspace for your self as sharing a Workspace with multiple users can create issues.
To do this, Inline to the Workspace section, click on the new Button. This window will pop up.

![Screenshot 2022-07-05 104844](https://user-images.githubusercontent.com/65004578/177273127-7b0d443d-cda8-4aeb-a7b3-eb51853c66ac.png)

The 2 Checkboxes may or may not be there. If they are available make sure to enable both of them.

For your Workspace name Follow the naming convention of your Organization

For those in the MIT Gaming Club use this naming Convention: UserName_Dev

Leave the Workspace root as is

Choose the Stream Assigned For you (MIT Gaming Club members select the Dev Stream)

### 4) In the top left corner, Click on the Advanced Tab. The window should now change to this: 

![image](https://user-images.githubusercontent.com/65004578/177274267-111f528a-19b9-4a1e-be73-f899a29f31e6.png)

Enable Rmdir

Change 'On Submit' to 'Revert Unchanged Files'

Hit OK

### 4.5) Go to your Terminal and Enter this Command to get the P4Ignore file working properly.(This has to be done by all users)
```
p4 set P4IGNORE=.p4ignore
```

### 5)
