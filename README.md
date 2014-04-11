AutoRotationiOS6-7
==================

How to handle autorotation in iOS 6 and iOS 7

After iOS 5, the orientation is handled got changed. 

I came across following scenario

                                               
NavigationController-----Root----->HomeViewController(Portrait)----------Child-------->DetailViewController(Landscape)


I wanted root HomeController to be in portrait but when I push DetailViewController, it should open in Landscape. When I come back from DetailViewController to HomeViewController, HomeViewController should open in portrait again.

