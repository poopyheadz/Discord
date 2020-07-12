var Discord = require("discord.js");
var bot = new Discord.Client();

bot.on("ready", () => {
  console.log("You are connected to " + bot.guilds.size + " servers!");
  bot.user.setGame("Hey There", "https://www.twitch.tv/yourgay")
});



bot.login('NjI2NjIyMzY1MDE4NjE5OTA0.Xvrd1A.npMPxs503FocZwMB_SPxCr9ln3o'); 
