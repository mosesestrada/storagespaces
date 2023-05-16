<p align="center">
 <img src="https://i.imgur.com/NPUtikU.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Create a storage pool using Windows storage spaces</h1>


<h2>Description</h2>
Get ready to revolutionize your storage game with Windows Storage Spaces! This amazing technology lets you combine multiple physical hard drives to create a virtual drive, giving you massive storage capacity without the need to replace any hardware. Not only that, but Storage Spaces also provides data redundancy, ensuring that your precious files are always safe and accessible even if one of the drives fails.

When using Storage Spaces, you can choose from three resiliency types: Simple, which provides the most storage but no data protection, Mirror, which offers excellent protection against drive failure at the expense of some storage capacity, and Parity, which provides the best storage efficiency and protection against drive failure.

In our exciting demonstration today, we will show you how to set up a parity storage pool using Storage Spaces. Get ready to take your storage to the next level!
<br />

<h2>Environments Used </h2>

 <b>Windows 10</b> <p>


<h2>Program walk-through:</h2>

<p align="center">


<br />
In the search field on the taskbar, enter Storage Space. Under Best match, select Manage Storage Spaces.

 <br/>
<img src="https://i.imgur.com/w2PPisz.png" height="80%" width="80%" alt="storage"/>
<br />
<br />
Select Create a new pool and storage space.
 <br/>
<img src="https://i.imgur.com/Uege3zt.png" height="80%" width="80%" alt="storage"/>
<br />
<br />
Add all your drives you wish to add to storage pool the select "Create Pool".

 <br/>
<img src="https://i.imgur.com/WKOADVL.png" height="80%" width="80%" alt="storage"/>
<br />
<br />
1)In the Name field, enter the name of your storage space. In the Drive letter drop-down list, select the drive you wish to use.
2)In the Resiliency type drop-down list, select Parity.
3)In the Size (maximum) field, enter how much space you wish to use. Don't forget some space will be reserved for the parity block. 
4) Select Create storage space.
<br/>
<img src="https://i.imgur.com/attEcEw.png" height="80%" width="80%" alt="storage"/>
<br />
<br />
That's it! We are finished. As you can see our storage pool has been created using the drives we assigned.

 <br/>
<img src="https://i.imgur.com/E8Rv3UU.png" height="80%" width="80%" alt="storage"/>
<br />
<br />
I hope you enjoyed this demonstration.
 <br/>
<img src="https://i.imgur.com/KH2UNtq.jpg" height="80%" width="80%" alt="storage"/>
<br />
<br />

 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
