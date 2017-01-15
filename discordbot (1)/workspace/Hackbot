=begin
Run Instructions:
command line:
$ruby Discordbot.rb
=end

require 'byebug'
require 'discordrb'
#require 'date'
#date = DateTime.now
Discordrb::Channel
# This statement creates a bot with the specified token and application ID. After this line, you can add events to the
# created bot, and eventually run it.
#
# If you don't yet have a token and application ID to put in here, you will need to create a bot account here:
#   https://discordapp.com/developers/applications/me
# If you're wondering about what redirect URIs and RPC origins, you can ignore those for now. If that doesn't satisfy
# you, look here: https://github.com/meew0/discordrb/wiki/Redirect-URIs-and-RPC-origins
# After creating the bot, simply copy the token (*not* the OAuth2 secret) and the client ID and put it into the
# respective places.
bot = Discordrb::Commands::CommandBot.new token: 'MjY5OTc5MTI1MzIwNTE1NTg0.C1xNKg.IM0yXfznoM5U0Nb4_ws4wggYcIc', client_id: 168123456789123456, prefix: '!'
# Here we output the invite URL to the console so the bot account can be invited to the channel. This only has to be
# done once, afterwards, you can remove this part if you want
puts "This bot's invite URL is #{bot.invite_url}."
puts 'Click on it to invite it to your server.'

bot.message(content: '!help') do |event|
    event.respond "Command List:\n!kelpyg: links you to Kelpy (6 hours)\n!nintendoswitch: links you to the Nintendo Switch homepage\n!switchlaunch: links you to a site that counts down to March 3rd. HYPE\n!ping: Pong!\n!gwff#: Golf With Friends Guide (Forest) Hole (#)\n!gwfo#: Golf With Friends Guide (Oasis) Hole (#)\n!ezsong: playlist of easy-listening music\n!sweet victory: Links you to Sweet Victory\n!botinfo: Tells you information about the bot\n!botwtrailers: Links you to a playlist with all the Breath of the Wild trailers\n!tijpics: Tijmen's Pictures\n!never use this tag: NEVER use it. Ever.\n!do a barrel roll!: Instructinos from Peppy Hare himself\n!random # #: Generates a random number between the two given numbers\n!wearenumber1: We are Number One but it's We are Number One\n!we are literally the worst: We are Number One but it's Opposite Day\n!Gabe: Gabe."
end

=begin
        template
bot.message(content: '!') do |event|
  event.respond ''
end
=end

#version
bot.message(content: '!version') do |event|
    event.respond 'BWMRD Bot is in version 1.1.1'
end

#kelpy g 6 hours
bot.message(content: '!kelpyg') do |event|
  event.respond 'https://www.youtube.com/watch?v=g72A9dVV18M'
end

=begin
        template
bot.message(content: '!') do |event|
  event.respond ''
end
=end

#golf with friends forest guide
bot.message(content: '!gwff1') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266143308/A3CEE02F27A8B7210B3500B6B334EAD870BEDD69/'
end
bot.message(content: '!gwff2') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266144551/2DBAFCB5083374F51CF9A60B0B95195191241BCE/'
end
bot.message(content: '!gwff3') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219621863853516/771BC224448BD8D520486C643EE1F969655E4B0D/'
end
bot.message(content: '!gwff4') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266148475/0FB64A137EDB8B88086BDD079EB3E3260A02A541/'
end
bot.message(content: '!gwff5') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266149267/0C73C7ADF38E272185E3C2AB74E2A4C20BA683B8/'
end
bot.message(content: '!gwff6') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266149768/3E8B28A3E60B74620CF9C3FAEA990730347A491A/'
end
bot.message(content: '!gwff7') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266150347/88860D3C1AD4528B40515110F73A78410DFB393C/'
end
bot.message(content: '!gwff8') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266152371/F2D31269E181155F611FA4182B6C45FFA0C9A07B/'
end
bot.message(content: '!gwff9') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266152972/47F0CC8F6A890E54A0895C2F358D89D3D6B1DB7C/'
end
bot.message(content: '!gwff10') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266171813/7F40E71940F1E320AECE1C272D0091D7346E0A71/'
end
bot.message(content: '!gwff11') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266153591/6C5A281D753E52AFE1E9DA8DDA58258F84BBDB91/'
end
bot.message(content: '!gwff12') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266161747/B00B8C6DA7A1AFF9F11C0822DF4616C6B48D6CA9/  http://images.akamai.steamusercontent.com/ugc/267219116266162319/4A32EC6093B036C81B11C18464C1F6350F741D1B/'
end
bot.message(content: '!gwff13') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266164035/C097677451C8DBA1E4BA4D4C5308EFEDBA4953E7/'
end
bot.message(content: '!gwff14') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266164599/B4555F0DC5982ADE06C606B260FFDD93E1CA2D02/'
end
bot.message(content: '!gwff15') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116269839341/8A56C4FE0D75F3A204C373C71F46D6AC7802AFDE/'
end
bot.message(content: '!gwff16') do |event|
  event.respond 'Block must be all the way right when shot is taken: http://images.akamai.steamusercontent.com/ugc/267219116266167682/64CD17DE54ECEFCA65AC447FE53C2C82007D66F9/'
end
bot.message(content: '!gwff17') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266168321/91F2446897E1608F7C3AA78D790055EC82D62A3E/'
end
bot.message(content: '!gwff18') do |event|
  event.respond 'http://images.akamai.steamusercontent.com/ugc/267219116266169063/C1A41A55ABAB39CF850F712F2BAF9AB87C60C2A7/'
end

#golf with friends oasis guide
bot.message(content: '!gwfo1') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/267219621863855697/D233E52F77B57AF8AA0E02E704C8F5A18997859D/    http://images.akamai.steamusercontent.com/ugc/267219621863856299/F1537700EE0653A4A195A442A113E0486100BE21/'
end
bot.message(content: '!gwfo2') do |event|
    event.respond 'Full power perfectly straight.'
end
bot.message(content: '!gwfo3') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/262719480210179679/F2C2980658F5852333F6CBC3EA9E9FA60F1DBEA8/'
end
bot.message(content: '!gwfo4') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/268345649792992253/6F9478311F145438D1521FDFB1EC9E0C07DCF9CE/'
end
bot.message(content: '!gwfo5') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/1617176207582905773/D29590C2F439265FB2F15844A588B80DBF6A29A7/    http://images.akamai.steamusercontent.com/ugc/1617176207582906397/78DEA6515D9248030F38B017DD982F83FC484F9B/'
end
bot.message(content: '!gwfo5alt') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/262719480210180208/7A34C61463618C9C68B0312B2E374F4047DF3AFC/    http://images.akamai.steamusercontent.com/ugc/262719480210181071/7568BBE2A44E22A86888722477A7129A59959090/'
end
bot.message(content: '!gwfo6') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/268345649780567292/40BCA4CE01191C95447EADB4C229941F1B555D85/'
end
bot.message(content: '!gwfo7') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/262719480210181854/100B069F0FD415397873065365C0BEA17957E0D2/'
end
bot.message(content: '!gwfo8') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/1617176207582907068/4C275844203F684455020A1261AD72819B4511D4/'
end
bot.message(content: '!gwfo9') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/1617176207582908304/CD8F6290DFCC2D0918D0E9CA33951313917D3AC9/    http://images.akamai.steamusercontent.com/ugc/1617176207582908947/D94AEEF123F3C17921ED546ADB20FC6C77B57DB3/'
end
bot.message(content: '!gwfo10') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/268345649780573676/E6FFCC1F4DE3E2E9FBB2A649252835660FDE9F96/    http://images.akamai.steamusercontent.com/ugc/268345649780574492/ACC340EE37040D96D45C1C9F55555F5723B76CA4/'
end
bot.message(content: '!gwfo11') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/268345649780577207/F9914BBB72EB4B3A9E08149EECDE53D16A885239/    Jump 1: http://images.akamai.steamusercontent.com/ugc/268345649780578308/95CEA50CBE8A5CC535C8E942E770147ED74E9019/eventJump 2: http://images.akamai.steamusercontent.com/ugc/268345649780578749/12DF8DCC2D79B8A0C6A02131E21E0F18F81189BF/'
end
bot.message(content: '!gwfo11alt') do |event|
    event.respond 'Spam left click after you hit the tree: http://images.akamai.steamusercontent.com/ugc/262719480210279612/506E95729AC3C3A5B308B91A79204202B0081F33/'
end
bot.message(content: '!gwfo12') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/262719480210280491/8A27715F5121A796FAA8D25CB91D79C52A2525F2/    http://images.akamai.steamusercontent.com/ugc/262719480210281156/0D351B5DAB6EDE6358F20BBED5DF528464C180E6/'
end
bot.message(content: '!gwfo13') do |event|
    event.respond 'Coming Soon!'
end
bot.message(content: '!gwfo14') do |event|
    event.respond 'Coming Soon!'
end
bot.message(content: '!gwfo15') do |event|
    event.respond 'Coming Soon!'
end
bot.message(content: '!gwfo16') do |event|
    event.respond 'Coming Soon!'
end
bot.message(content: '!gwfo17') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/268345649780583845/40E0E6283265FDA9A69D6D26E2289CB6DAF0C593/'
end
bot.message(content: '!gwfo18') do |event|
    event.respond 'http://images.akamai.steamusercontent.com/ugc/268345649792993162/5B67883A0DA6A5D61D1919C0BA5B8DC72475B905/    http://images.akamai.steamusercontent.com/ugc/268345649792993723/F887C8561F217C16894B3B79E3DC25197423B516/'
end



#easy listening songs
bot.message(content: '!ezsongs') do |event|
  event.respond 'https://www.youtube.com/watch?v=dvH-nbindvk&index=1&list=PLTVjPAw118GfBbGrOva0NUDft7VmvWdUW&t=234s'
end

#sweet victory
bot.message(content: '!sweet victory') do |event|
    event.respond 'https://www.youtube.com/watch?v=tVm7LOHNA24'
end

bot.message(content: '!botinfo') do |event|
    event.respond "Hi, I'm BWMRD Bot. I was written by Jason Odell and Kevin Lane."
end

#links to Switch homepage
bot.message(content: '!nintendoswitch') do |event|
  event.respond 'http://www.nintendo.com/switch/'
end

#links to date calculator until March 3rd
bot.message(content: '!switchlaunch') do |event|
  event.respond 'https://days.to/until/3-march'
end

#responds 'Pong!' to '!ping'
bot.message(content: '!ping') do |event|
  event.respond 'Pong!'
end

#links to a playlist with all Breath of the Wild trailers
bot.message(content: '!botwtrailers') do |event|
    event.respond 'https://www.youtube.com/playlist?list=PLTVjPAw118GdIs0x1GyxzIUYpcXY0jfis'
end

#secret
#links to Tijmen's photoshopped Shrewsbury pictures
bot.message(content: '!tijpics') do |event|
    event.respond 'https://drive.google.com/open?id=0B4VoCVirkB_xa3N4M2JoY0V6MFE'
end

#secret
#secret WALUIGI tag
bot.message(content: '!hoysmallfrywaluigiwilldrawyourmap') do |event|
    event.respond 'WAAAAAAAAAAAAAAAAAAAAAAAAA    https://www.youtube.com/playlist?list=PLTVjPAw118Ge0C2gmnNPwlts8peE5MZNe'
end

#secret
#konamicode
bot.message(content: '!up up down down left right left right B A start') do |event|
    event.respond 'Congratulations, you found a secret tag! There are still more to find. Can you find them all?'
end

#secret
#another secret tag
bot.message(content: '!never use this tag') do |event|
    event.respond 'You dumbass.'
end

#secret
#secret to everybody
bot.message(content: '!secret to everybody') do |event|
  event.respond 'https://media.giphy.com/media/kuGxJyTQQAUw0/giphy.gif'
end

#secret
#Big Wiz and the Mauraders
bot.message(content: '!BWMRD') do |event|
  event.respond 'Eyyyyyyyyyyyyyyyyyy :smirk:'
end

#stfu Gabe
bot.message(content: 'oh yes daddy') do |event|
    event.respond 'Shut the fuck up Gabe'
end
#do a barrel roll
bot.message(content: '!do a barrel roll!') do |event|
    event.respond 'Press Z or R Twice!'
end

#do a barrel roll
bot.message(content: '!ZZ') do |event|
    event.respond 'Did a barrel roll!'
end

#do a barrel roll
bot.message(content: '!RR') do |event|
    event.respond 'Did a barrel roll!'
end

#random number generator
bot.command :random do |event, min, max|
  rand(min.to_i .. max.to_i)
end

bot.mention do |event|
  # The `pm` method is used to send a private message (also called a DM or direct message) to the user who sent the
  # initial message.
  event.user.pm('You have mentioned me!')
end

bot.command :user do |event|
  # Commands send whatever is returned from the block to the channel. This allows for compact commands like this,
  # but you have to be aware of this so you don't accidentally return something you didn't intend to.
  # To prevent the return value to be sent to the channel, you can just return `nil`.
  event.user.name  
end

bot.command(:connect) do |event|
  # The `voice_channel` method returns the voice channel the user is currently in, or `nil` if the user is not in a
  # voice channel.
  channel = event.user.voice_channel

  # Here we return from the command unless the channel is not nil (i. e. the user is in a voice channel). The `next`
  # construct can be used to exit a command prematurely, and even send a message while we're at it.
  next "You're not in any voice channel!" unless channel

  # The `voice_connect` method does everything necessary for the bot to connect to a voice channel. Afterwards the bot
  # will be connected and ready to play stuff back.
  bot.voice_connect(channel)
  "Connected to voice channel: #{channel.name}"
end
bot.command(:play_mp3) do |event|
  # `event.voice` is a helper method that gets the correct voice bot on the server the bot is currently in. Since a
  # bot may be connected to more than one voice channel (never more than one on the same server, though), this is
  # necessary to allow the differentiation of servers.
  #
  # It returns a `VoiceBot` object that methods such as `play_file` can be called on.
  voice_bot = event.voice
  voice_bot.play_file('discordrb-master/Waluigi- YAAAAAAAA.mp3')
end
bot.command(:play_mpwaa) do |event|
  # `event.voice` is a helper method that gets the correct voice bot on the server the bot is currently in. Since a
  # bot may be connected to more than one voice channel (never more than one on the same server, though), this is
  # necessary to allow the differentiation of servers.
  #
  # It returns a `VoiceBot` object that methods such as `play_file` can be called on.
  voice_bot = event.voice
  voice_bot.play_file('discordrb-master/Carol of the WAA.mp3')
end

bot.command(:play_victory) do |event|
  # `event.voice` is a helper method that gets the correct voice bot on the server the bot is currently in. Since a
  # bot may be connected to more than one voice channel (never more than one on the same server, though), this is
  # necessary to allow the differentiation of servers.
  #
  # It returns a `VoiceBot` object that methods such as `play_file` can be called on.
  voice_bot = event.voice
  voice_bot.play_file('discordrb-master/SpongeBob SquarePants Production Music - Sweet Victory 1.mp3')
end

#we are number one but it's opposite day
bot.message(content: '!we are literally the worst') do |event|
    event.respond 'https://www.youtube.com/watch?v=fb4xGirFOq8'
end

#this code gives it up for days 15 and 23 of every month... hopefully
#bot.message(content: '!day') do |event|
#    if date.day == 15 then
#        event.respond 'Day 15! Give it up for Day 15!'
#elsif date.day == 23 then
#        event.respond 'Day 23! Give it up for Day 23!'
#    end
#end

    #gabe's tag
#bot.member_join(channel) do |event, username|
    #event.respond('Welcome to the server, username')
#end
bot.message(content: '!Gabe') do |event|
    event.respond('https://www.youtube.com/watch?v=OtZ961RK1us Gabe makes 26 pizzas')
end
bot.message(content: '!wearenumber1') do |event|
    event.respond('https://www.youtube.com/watch?v=PfYnvDL0Qcw')
end
bot.message(contains: 'kevin') do |event|
    event.user.pm('Kevin helped develop this bot, you meme')
end
bot.message(contains: 'jason') do |event|
    event.user.pm('Jason heleped develop this bot, you meme')
end
bot.message(contains: 'Kevin') do |event|
    event.user.pm('Kevin helped develop this bot, you meme')
end
bot.message(contains: 'Jason') do |event|
    event.user.pm('Jason heleped develop this bot, you meme')
end

#waluigi map
bot.message(content: '!will waluigi draw my map?') do |event|
    event.respond 'Hoy small fry! Waluigi will draw your map!\nhttps://scontent-atl3-1.xx.fbcdn.net/v/t1.0-9/16105509_1856729664573730_5455019170746287959_n.jpg?oh=c8d574130383287bacf885c4d43a4fb0&oe=5914FA8D'
end

#waa ball
bot.message(content: '!magic WAA ball') do |event|
    event.respond 'https://scontent-atl3-1.xx.fbcdn.net/v/t1.0-9/15977456_1856734931239870_8032741172962276225_n.jpg?oh=11bc6a705c988eef226ed93dfe02405a&oe=58DE3C3B'
end

#waa ball 2
bot.message(content: 'what is the one true religion?') do |event|
    event.respond 'YOU ARE UGLY'
end

#waa ball 3
bot.message(content: 'who will I marry?') do |event|
    event.respond "STOP SHAKING ME. I'M FILLED WITH NITROGLYCER- \nhttp://rs651.pbsrc.com/albums/uu236/416o/explosion.gif~c200"
end

#changelog
bot.message(content: '!changelog') do |event|
    event.respond "Ha, we aren't that organized.\n-Kevin & Jason"
end

#upside down L
bot.message(content: 'can I get an upside down L?') do |event|
    event.respond 'Waluigi has secret symbol: Г'
end

#WAA
#bot.message(contains: 'waa') do |event|
    #event.respond 'Time to kick it up a WAA! Г'
#end

#salty
bot.message(contains: 'salt') do |event|
    event.respond "Well, SOMEONE's salty."
end

#libsodium
bot.message(contains: 'libsodium') do |event|
    event.respond "Oh HELL no."
end
#PM the bot
bot.pm(contains:' ') do |event|
    event.user.pm('I am a robot do not message me, if you have questions ask Kevin or Jason.')
end
bot.message(contains:"!tag") do |event|
    event.respond'Silly Discrank Waluigi time OH YEAAAAAAAAAAAAA'
end
# This method call has to be put at the end of your script, it is what makes the bot actually connect to Discord. If you
# leave it out (try it!) the script will simply stop and the bot will compulsively masturbate and/or not appear online.
bot.run