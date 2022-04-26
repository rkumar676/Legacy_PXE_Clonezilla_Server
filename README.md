# Legacy_PXE_Clonezilla_Server
Here, I'm creating a clonezilla script for Legacy systems for PXE boot. 

Purpose of this:-
Like if you have to clone 100 of systems at once. So you can setup a clonezilla server on 1 or 2 machines and clones 98 systems via it..

When I started my carrier in IT industry.. A man from US, Yes of course he was of my office "Dzmitry" setup a PXE Clonezilla server in our premises. That time I got to know that there are such things like this which exist..Yup!! I don't have any idea of pxe server prior to this.. Who cares?? Ha ha.. and When I tried to make this by my own I end up with some confusions..

After researches I make this clonezilla server finally. Yes, It takes 10 days to understand logics. 

When I created and deployed this in production.. one issue was there for me..we have some hardware (Motherboard) which supports legacy only or UEFI bios. 

So UEFI bios devices didn't support legacy os or legacy clonezilla setup.. So they won't boot up in PXE mode.. (I modified some settings to make it work with UEFI devices too,)....

If you have old systems like core-2-duo, may be some i3 or if you are using leagcy supported OS .. So if you want to clone same leagcy os on 100 systems ..you can do this with legacy_PXE_Clonezilla_Server..

You just need a machine .. have to install debian 10.* (buster) version. and have to run the script this will install required settings onto that machine.. and if you put 100 of your machines into network boot. It will automatically boots up in cloezilla mode.. 


This will keep on updating by me.. If you read this or need help feel free to reach out to me on ravikumar11136@gmail.com.. 
