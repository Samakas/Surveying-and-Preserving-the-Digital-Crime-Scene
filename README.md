# Surveying-and-Preserving-the-Digital-Crime-Scene

## Aim:
<p>Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.</p>

## Implementation Steps:
### 1.Copy Files to the Virtual Disk
<ul>Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk</ul>
<ul>Create a new folder (Autospy) and copy images or files into it.</ul>

### 2.Delete the Files
<ul>Select any one or two images → Press Delete.</ul>
<ul>Empty the Recycle Bin to permanently delete them.</ul>

### 3.Recover Deleted Files Using Autopsy
### Open Autopsy & Create a New Case
<ul>Launch Autopsy and Run as a administrator</ul>
<ul>Click Create New Case.</ul>
![alt text](img-1.png)

<ul>Enter a Case Name (e.g., Autopsy1).</ul>
<ul>Choose a Case Folder location.</ul>
<ul>Click Next → Click Finish.</ul>
![alt text](img-2.png)

### Add the Virtual Disk as an Evidence Source
<ul>Click Add Data Source → Select Host</ul>
![alt text](img-3.png)

<ul>Select Local Disk → next</ul>
![alt text](img-4.png)

<ul>Select Disk → Choose the VHD drive (Drive1)</ul>
![alt text](img-5.png)

<ul>Click Next → Keep default settings → Click Finish.</ul>
<ul>Wait for Autopsy to process the disk.</ul>

### Recover Deleted Files
<ul>Go to File Views (left panel).</ul>
![alt text](img-6.png)
![alt text](img-7.png)

<ul>Click Deleted Files → Find your deleted images.</ul>
<ul>Right-click an image → Click Extract File.</ul>
![alt text](img-8.png)

## Output:
### Folder before deleting the files

<ul>Folder after deleting the files</ul>
![alt text](img-9.png)
<ul>Folder after deleting the files</ul>
![alt text](img-10.png)

<ul>Folder after extracting the deleted images using autopsy</ul>
![alt text](img-11.png)


## Result:
<p>Successfully extracted the deleted files from unallocated space using the Autospy tool.</p>