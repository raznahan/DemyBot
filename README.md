<h1 align="center">
  <br>
  <a href="https://t.me/demybot?start=lan_en">
  <img src='https://github.com/raznahan/DemyBot/blob/main/extras/readme/demybot-logo.jpg'/>
  </a>
  <br>
  Demybot
  <br>
</h1>


Demybot is a [Telegram][Telegram] chatbot that provides photo utilities such as editing, creating stickers, applying effects and many more. Demybot was first launched in 2015, and it has constantly been improving ever since. A total of 2 million users have used Demybot so far. Its monthly active users, aka MAU, has reached up to 50k. There are more than 20 features built in this chatbot. 

You can start working with [Demybot][Demybot] if you have a [Telegram][Telegram] account. The English version of the bot is not 100% complete and needs more translations and modifications. 

> I have not shared the source code yet since I need to clean up the codebase. In fact, I am switching to a new architecture; that's why it might take a while before the code is ready to be shared here.

### Bot Preview
<h2 align='center'>
<img src='https://github.com/raznahan/DemyBot/blob/main/extras/readme/Demybot-PreveiwGif.gif'/>
</h2>


## About the **Project**

Demybot is basically a chatbot written in C# as a console application. The idea behind this goes back to when Telegram first introduced chatbot feature within its platform. At the time, I was running a website called [demy.ir][demy] where we would get orders from people to create stickers with their pictures. All the work was done manually and with Photoshop. After realizing the capabilities of the Telegram chatbot feature, I then decided to make this bot so all the sticker making process would be done automatically. 

Now, five years have gone by, and Demybot has become very famous among the Persian language community.

There are a variety of online cloud libraries that have been incorporated into this chatbot. [FFMPEG][FFMPEG], [Cloudinary][Cloudinary], [Pho.to][Photo], and [Remove.bg][Removebg] are among those. Apart from those libraries, I have done a ton of meticulous code optimization in order to tackle some challenges along the way, from sticker format adjustment, to changing specific parameters in C# image libraries. Honestly, If I want to document important details about this project, it'd take me a good number of days. Yeah, unfortunately, I haven't done much documentation and source code sharing during these years, which I regret now. I hope I can finish code overhauling soon so the code will be ready for GitHub.

## Here are some features you can find in Demybot:

* Watermarking photos with texts/images.
* Removing background of images.
* Adding text on images.
* Cool and funny effects for images.
* Creating stickers with text or images.
* Creating custom sticker packs.
* Searching through a database of over 10,000 transparent PNG images in different categories.
* Convert stickers to images.
* Convert images to PNG format.
* Reducing the size of images for sticker creation.
* Creating a surprise image out of your profile pictures.
* Ability to chat with other Demybot users




[Demybot]: https://t.me/demybot?lan_en
[Telegram]: https://telegram.org
[FFMPEG]:https://ffmpeg.org/
[Cloudinary]:https://cloudinary.com/
[Photo]:https://pho.to
[Removebg]: https://remove.bg
[demy]:https://demy.ir