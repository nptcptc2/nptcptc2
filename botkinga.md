#Libraries#
from ast import Global
from pyexpat.errors import messages
import random
from sys import prefix
from tkinter import E
from unittest import case
import discord
from discord.ext import commands
import discord.utils
import asyncio
from discord.ext.commands import command
from discord.ext.commands import Cog


#variables#
TOKEN = 'OTY5Mzc3MzQ5NDcwNjc5MTEw.YmshAg.PpSgABcBAGyFYVeSF84N-VU0NhE'
intents = discord.Intents.default()
intents.members = True
client = commands.Bot(command_prefix='.', intents=discord.Intents.all())
seif = 864449253099044875
Azure = 623971190603644940
kingu=352544654899806218
Nat=586553213507862578
global exmsg;
global Mentions;
global FunMsg;
prefi='&'
exmsg=1
Mentions=1
FunMsg=1
print(exmsg)
print(Mentions)
print(FunMsg)






#Self awnser prevention#
@client.event
async def on_message(message):
  print(message.author)
  print(message.content)
  if message.author == client.user:
        return

  message.content=message.content.lower()
  
  
    

       #Exclusive messages only#
  
     
  if message.author.id==Azure and message.content.startswith('sigh'):
          msg = '*headpats azure*'
          msg1= 'https://cdn.discordapp.com/attachments/963032814209597440/970381153292922920/061cbbe4-aa15-48c2-8869-3ab88a2148f3.gif'
          await message.channel.send(msg)
          await message.channel.send(msg1)
  if message.author.id==Azure and message.content.startswith('dies'):
          msg = '*Revives azure*'
          msg1= 'https://tenor.com/view/dream-hunter-rem-skeleton-resurrection-undead-living-dead-girl-gif-24580441'
          await message.channel.send(msg)
          await message.channel.send(msg1)

  if message.author.id==seif and message.content.startswith('shut'):
        msg = 'no u'.format(message)
        await message.channel.send(msg)
  if message.author.id==kingu and message.content.startswith('dies'):
    msg='**KINGU IS FUCKING DEAD, FINALLY**'
    msg2='https://tenor.com/view/anime-dance-party-gif-18960088'
    await message.channel.send(msg)
    await message.channel.send(msg2)
  if message.author.id==kingu and message.content.startswith('time to sleep'):
    msg='**Kingu will go to sleep, may he not wake up tomorrow, Bot terminated, till tomorrow**'
    msg2='https://tenor.com/view/anime-girl-anime-girl-cute-girl-cute-gif-24599519'
    await message.channel.send(msg)
    await message.channel.send(msg2)
      
    
      
      #Fun Mesages#
  
  if message.content.startswith(prefi+'seggs'):
        ran = random.randint(1,3)
        msg= '**UWWWWOOGGHHHH SEEEGGSSSS!**'
        await message.channel.send(msg)
        if ran==1:
          msg1='https://cdn.discordapp.com/attachments/970275789809532948/970318877261189130/SEEEEEGGGSSSSSS.gif'
          await message.channel.send(msg1)
        if ran==2:
          msg1='https://tenor.com/view/guilty-gear-sol-badguy-dragon-install-dragon-install-but-seggs-gif-25208316'
          await message.channel.send(msg1)
        if ran==3:
          msg1='https://cdn.discordapp.com/attachments/970275789809532948/970794752398209075/chasing-car-seggs.gif'
          await message.channel.send(msg1)
  if message.content.startswith(prefi+'teri'):
          msg = 'sekai de ichi ban no kawaii'
          msg1 = 'https://tenor.com/view/teridan-derpteridance-honkaiimpact-honkaiteri-gif-20217613'
          await message.channel.send(msg)
          await message.channel.send(msg1)
  if message.content.startswith(prefi+'yatta'):
          msg='***YATTA!!***'
          msg1='https://tenor.com/view/hos-honkai-hos-herrscher-of-sentience-fu-hua-yatta-gif-24923243'
          await message.channel.send(msg)
          await message.channel.send(msg1)
  if ' well' in message.content.lower():
          msg='https://cdn.discordapp.com/attachments/943189627622264913/970632584331665448/th_8.jpeg'
          await message.channel.send(msg)
  if 'Im bad' in message.content.lower() :
          msg='https://cdn.discordapp.com/attachments/943189627622264913/970327807433535508/unknown-25.jpg'
          await message.channel.send(msg)
  if 'lost 50/50' in message.content.lower() :
          print('lost 50/50 lmao')
          msg='https://youtu.be/HwTR4gTEwzw'
          await message.channel.send(msg)
  if 'pulled qiqi' in message.content.lower() :
          print('lost 50/50 lmao')
          msg='https://youtu.be/HwTR4gTEwzw'
          await message.channel.send(msg)
  if message.content.startswith(prefi+'longming'):
          msg='https://cdn.discordapp.com/attachments/963032814209597440/970344690417295370/A6C5AF46-5672-4533-8445-5F2A162F6A78.png'
          await message.channel.send(msg)
  if message.content.startswith(prefi+'vibing'):
        ran = random.randint(1,5)
        if ran==1:
          msg='https://tenor.com/view/ya-boy-zhuge-liang-gif-25361322'
          await message.channel.send(msg)
        if ran==2:
          msg='https://tenor.com/view/paripi-koumei-anime-girl-dance-paripi-koumei-gif-25332149'
          await message.channel.send(msg)
        if ran==3:
          msg='https://tenor.com/view/dragon-girls-documentay-dragon-girl-cute-dragon-girl-anime-nana-dragon-dragon-maid-gif-22616227'
          await message.channel.send(msg)
        if ran==4:
          msg='https://tenor.com/view/girl-music-head-shaking-eyes-close-chill-gif-17828830'
          await message.channel.send(msg)
        if ran==5:
          msg='https://tenor.com/view/gojos-vibe-jujutsu-kaisen-vibe-gojo-dance-gif-20625837'
          await message.channel.send(msg)
  if message.content.startswith('there will be blood-shed'):
          msg='The man in the mirror nods his head'
          msg1='https://tenor.com/view/samuel-smile-reverse-reverse-metal-gear-metal-gear-rising-gif-21248744'
          await message.channel.send(msg)
          await message.channel.send(msg1)
  if message.content.startswith(prefi+'nobitches'):
          msg='**No bitches?**'
          msg1='https://cdn.discordapp.com/attachments/970275789809532948/970743355950657656/61vugl.jpg'
          await message.channel.send(msg)
          await message.channel.send(msg1)
  if message.content.startswith(prefix+'bored'):
          msg='https://cdn.discordapp.com/attachments/971360467597537321/971498854073659413/redditsave.com_ce12smpq5gx81_1.gif'
          await message.channel.send(msg)
  
      #Mentions#
  
  if message.content.startswith('<@969377349470679110>'):
            msg = 'Did someone call me??'
            await message.channel.send(msg)
  if message.content.startswith(prefi+'kinguhelp'):
            msg= '<@579692927022792704>'
            await message.channel.send(msg)      
      
     
      #Help#
  if message.content.startswith(prefi+'help'):
        print('utility')
        msg9 = '**The prefix is: '+prefi+'**'
        msg = 'Here is a list of commands:'
        msg1 = '**Yatta** Sentience'
        msg2='**seggs** UWWOOOGGHHHHH'
        msg3=' **teri teri** the cutest in the world'
        msg6='**.kinguhelp** mention mommy to prevent kingu from doing something stupid'
        msg7='Alongside these, other secret messages will be auto replied'
        msg8='To see utility commands say **'+prefi+'utility**'
        msg4='To see exclusive commands say **'+prefi+'exclusive**'
        await message.channel.send(msg9)
        await message.channel.send(msg)
        await message.channel.send(msg1)
        await message.channel.send(msg2)
        await message.channel.send(msg3)
        await message.channel.send(msg6)
        await message.channel.send(msg7)
        await message.channel.send(msg4)
        await message.channel.send(msg8)
  if message.content.startswith(prefi+'exclusive'):
      msg='Exclusive commands use discord ID to track users'
      msg2='**seif:shut** the bot replies no u'
      msg3='**azure:sigh**the bot headpats azure'
      msg4='for an exclusive command DM **Kingu#2507**'
      msg5='for normal commands say .help'
      await message.channel.send(msg)
      await message.channel.send(msg2)
      await message.channel.send(msg3)
      await message.channel.send(msg4)
      await message.channel.send(msg5)
  if message.content.startswith(prefi+'utility'):
      msg='Utility commands:'
      msg2='**.creator** to see who created the bot'
      msg3='**.changelog**to see what was added on the new update'
      msg4='**.download** Ive decided to make the bot open-source for anyone to have a base'
      msg6='**.changeprefix** to change prefix'
      msg7='**.support** + your problem and the bot will send a DM to Kingu'
      msg5='for normal commands say .help'
      await message.channel.send(msg)
      await message.channel.send(msg2)
      await message.channel.send(msg3)
      await message.channel.send(msg4)
      await message.channel.send(msg6)
      await message.channel.send(msg7)
      await message.channel.send(msg5)    
      #Configurations#
  if message.content.startswith('.DisableFun') and message.author.id==kingu:
        msg= 'Fun replies disabled'
        if FunMsg>0:
          FunMsg =0
        await message.channel.send(msg)
  if message.content.startswith('.DisableExclusive') and message.author.id==kingu:
        msg= 'Exclusive replies disabled'
        if exmsg >0:
          exmsg =0
        await message.channel.send(msg)
  if message.content.startswith('.DisableMentions') and message.author.id==kingu:
        msg= 'Mentions replies disabled'
        if Mentions>0:
          Mentions =0
        await message.channel.send(msg)
  if message.content.startswith('.DisableAll') and message.author.id==kingu:
      msg='disabled all replies'
      if FunMsg and exmsg and Mentions>0:
        FunMsg =0
        exmsg =0
        Mentions =0
        print(FunMsg,exmsg,Mentions)
  
      await message.channel.send(msg)
  if message.content.startswith('.EnableAll') and message.author.id==kingu:
      msg='Enabled all replies'
      if FunMsg and exmsg and Mentions<=0:
        FunMsg =1
        exmsg =1
        Mentions =1
        
      await message.channel.send(msg)
      return
  if message.content.startswith('.EnableMentions') and message.author.id==kingu:
        msg= 'Mentions replies enabled'
        if Mentions<=0:
          Mentions =1
        await message.channel.send(msg)
      
  if message.content.startswith('.EnableExclusive') and message.author.id==kingu:
        msg= 'Exclusive replies enabled'
        if exmsg<=0:
          exmsg =1
        await message.channel.send(msg)
       
  if message.content.startswith('.EnableFun') and message.author.id==kingu:
        msg= 'Fun replies enabled'
        if FunMsg<=0:
          FunMsg =1
          print(FunMsg)
        await message.channel.send(msg)
        
  if message.content.startswith('.DisableFun') and message.author.id==Nat:
        msg= 'Fun replies disabled'
        FunMsg =0
        await message.channel.send(msg)
        
  if message.content.startswith('.DisableExclusive') and message.author.id==Nat:
        msg= 'Exclusive replies disabled'
        exmsg =0
        await message.channel.send(msg)
        
  if message.content.startswith('.DisableMentions') and message.author.id==Nat:
        msg= 'Mentions replies disabled'
        Mentions =0
        await message.channel.send(msg)
        
  if message.content.startswith('.DisableAll') and message.author.id==Nat:
      msg='disabled all replies'
      FunMsg =0
      exmsg =0
      Mentions =0
      await message.channel.send(msg)
      
  if message.content.startswith('.EnableAll') and message.author.id==Nat:
      msg='Enabled all replies'
      FunMsg =1
      exmsg =1
      Mentions =1
      await message.channel.send(msg)
      
  if message.content.startswith('.EnableMentions') and message.author.id==Nat:
        msg= 'Mentions replies enabled'
        Mentions =1
        await message.channel.send(msg)
        
  if message.content.startswith('.EnableExclusive') and message.author.id==Nat:
        msg= 'Exclusive replies enabled'
        exmsg =1
        await message.channel.send(msg)
       
  if message.content.startswith('.EnableFun') and message.author.id==Nat:
        msg= 'Fun replies enabled'
        FunMsg=1
        await message.channel.send(msg)
  if message.content.startswith(prefi+'say')and message.author.id==kingu:
    say = message.content.split(",",4)[1:]
    saytext= say[0]
    print(saytext)
    channel=message.channel_mentions[0]
    await channel.send(saytext)     


      #utility#
  if message.content.startswith(prefix + "changelog"):
      msg='Added changelog'
      msg1='Added send help exclusive'
      msg2='Hosting from pc'
      msg3='added utility commands'
      msg4='updated send help'
      msg5='made bot case insensitive'
      version='Beta 0.1.2'
      await message.channel.send(msg)
      await message.channel.send(msg1)
      await message.channel.send(msg2)
      await message.channel.send(msg3)
      await message.channel.send(msg4)
      await message.channel.send(msg5)
      await message.channel.send(version)
  if message.content.startswith('.download'):
      download='https://mega.nz/file/w2h22IwK#G54lCjjR-BSQDLqpCDtLcrhi_qlJR9UeWUOifpEp8DI :pinched_fingers:'
      await message.channel.send(download)
  if message.content.startswith(prefix+'changeprefix'):
      msg='This command is yet to be added'
      await message.channel.send(msg)
  if message.content.startswith(prefix+'creator'):
      msg='my creator is <@352544654899806218>'
      await message.channel.send(msg)
  if message.content.startswith(prefix+'support'):
      msg='feature yet to be added please DM Kingu#2507'
      await message.channel.send(msg)
  if message.content.startswith(prefix+'invite'):
      msg='Want to invite the bot to your server? here is the link https://discord.com/api/oauth2/authorize?client_id=969377349470679110&permissions=8&scope=bot'
      await message.channel.send(msg)

      

#Login in confirmer and status#    
@client.event
async def on_ready():
    await client.change_presence(activity=discord.Game('say ".help" for commands'))
    print('Logged in as')
    print(client.user.name)
    count = len(client.guilds)
    print(count)
    print('Servers connected to:')
    for guild in client.guilds:
        print(guild.name)
    print('------')
#Bot login#
client.run(TOKEN)
