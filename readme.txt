Pixel Stenography Tool

pixel stenography is an interesting subject, by editing the least important binary values of a pixel you can hide text inside images.
for example, if you base64 encoded an entire .zip folder you could hide it inside a .png file and it would not exit the file size.
you can hide essentially anything that can be converted into text inside images, this is essentially a way to hide payloads inside images.
the payloads are completely undetectable and un-findable unless this tool is used.
if you want to completely hide a .zip and stop anyone from accessing it, do the following:
make a .zip with all the contents you desire, use 7zip to add a password with AES256 encryption.
use https://www.base64encode.org/ and upload the file and download the encoded .txt
copy all of the contents and encode them inside an image for perfect storage.
beware that 4 pixels equals one letter so make sure your image is high enough quality to store all of the characters.
there is a sample image to mess around with, the output formats are: .png and .bmp
enjoy and have fun learning!