# KHInsider CLI Album Downloader
This repository contains a simple script for the purpose of downloading all songs of an album in [KHInsider](https://downloads.khinsider.com/) without the need of an account or permission to download all at once.

It also gives normalized names to the songs in the form of "XX Name of song.format", with XX being a 2 digit number. If there are more than 99 songs, the order in the download directory may not be ideal.

## Usage
Clone the repository in your desired location, create a dotenv file and set the `ROOT_DOWNLOAD_DIR` variable to the desired root directory for your downloads

Make the file executable with

 **`chmod +x ./khicad`**

Execute the script using the `-u` flag for the full url of the album you want to download hosted on [KHInsider](https://downloads.khinsider.com/), the `-n` flag for the Album name, which will be the folder in the `albumdir`, and the `-f` flag for the song format.

And you are good to go, enjoy!

## Example

![image](https://user-images.githubusercontent.com/121802206/210231663-85b6cd05-afc6-4c06-93b2-e32faacb35c4.png)

# Missing Features

```
- Propperly identify total album size for selected format
- Summary and -y flag to ignore confirmation
```