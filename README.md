# MAT_NETWORK
MAT NETWORK Bot is discord ( python )
========================================================================================
import disocrd
import asyncio
from discord.ext import commands

intents = discord.Intents.default()
bot = discord.Client(intents=intents)
bot = commands.Bot(command_prefix= "/" , intents= discord.Intents.all())
token = ("token bot")
@bot.event
async def on_ready():
    print("[ Hello Bro ]")
    print("[ Bot Is Run ]")

bot.run("token")
========================================================================================
