# MindfulMeme Designer Bot 🤖

A completely serious Bot that gives design advice that's dipped and steeped in a satirical, designer stew —Yum! 
MMD Bot is powered by [Tracery](https://github.com/galaxykate/tracery). 

## How to use Tracery

Go [here to galaxykate's tracery](https://github.com/galaxykate/tracery) to understand how to use & modify Tracery

Go [here to @HeyDesignerBot](https://twitter.com/HeyDesignerBot) to see the end output of Tracery on Twitter.com

or go [here to cheapbotsdonequick.com](https://cheapbotsdonequick.com/source/DesignAdviceBot) to see how to design a Tracery bot of your own!

### Write grammar objects, get generative stories

#### An example grammar
```
{
	"name": ["Arjun","Yuuma","Darcy","Mia","Chiaki","Izzi","Azra","Lina"],
	"animal": ["unicorn","raven","sparrow","scorpion","coyote","eagle","owl","lizard","zebra","duck","kitten"],
	"mood": ["vexed","indignant","impassioned","wistful","astute","courteous"],
	"story": ["#hero# traveled with her pet #heroPet#.  #hero# was never #mood#, for the #heroPet# was always too #mood#."],
	"origin": ["#[hero:#name#][heroPet:#animal#]story#"]
}
```

#### Output of that grammar.
Of course, many grammars are more complex!
```
Lina traveled with her pet duck. Lina was never indignant, for the duck was always too indignant.
Yuuma traveled with her pet unicorn. Yuuma was never wistful, for the unicorn was always too indignant.
Azra traveled with her pet coyote. Azra was never wistful, for the coyote was always too impassioned.
Yuuma traveled with her pet owl. Yuuma was never wistful, for the owl was always too courteous.
Azra traveled with her pet zebra. Azra was never impassioned, for the zebra was always too astute.
```

An example of a tweet from [@HeyDesignerBot](https://twitter.com/HeyDesignerBot) using this grammar

![@HeyDesignerBot](https://github.com/nnekannagbo/nnekannagbo.github.io/blob/master/images/Mindful%20Designer%20Bot%20Tweet.png?raw=true)
