# Description

The code for the discord bot
@bot.event
async def on_message(message):
    if message.author.id == "Replace the user id here":
        if "Uptime" in message.content:
            await message.channel.send("True")
    
    await bot.process_commands(message)

for botghost
CMD_545748aa-6341-4eab-85a8-a9afdcaf13f2
