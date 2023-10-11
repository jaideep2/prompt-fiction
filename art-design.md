# Advanced Midjourney prompts

## Aspect Ratio

--ar 16:9

`/prompt a cinematic still of a woman in a sci-fi world, pink hair, surrounded by robots, neon lights, nighttime, raining --ar 16:9`

2:1 = Cinematic

16:9 = HD

## Style

--s 625

Pick a number from 0 to 1000

625 is the default style number.

Less style = more control

More style = more creativity

Generally you want more control, so you can even use the 'Raw' mode setting which will set the style to 0.

200-300 is ideal for cinematic

## Subtractive Prompts

--no horse

Use this prompt to specify which objects you don't want to see in your scene.

List out multiple things by simply placing a space between the words.

`/prompt a cinematic still of a man in a western movie --seed 1234567890 --no hat horse`

## Seed

--seed 828028590

Pulls the art direction from a previously rendered image block.

Find the seed by applying the ✉️ emoji to a 4-block rendered image or a single upresed image.

The seed number will be sent to your inbox.

`/prompt a cinematic still of a woman in a sci-fi world --seed 12343567890`

## Prompt Weighting

::4

Pick any number between 0 and 5, Default weight is 1.

Adds more or less weight to certain elements of your prompt. 

`/prompt a cinematic still of birthday party:: chocolate cake ::2 pink party hats:: dinosaurs::.5`

## /settings keep remix on

## quality 0.1-5 (impact compute power) 3 is enough

--q 3

## prefer option set [key]JJ [value]in the style of JJ Abrams, shot on Arriflex, cinematic color grading, light film grain

`/prompt a cinematic still of a desert scifi world --JJ`

## See all set options

`/prefer option list`

## Other examples

```
cinematic still, set design (who the person is, what are they doing[foreground], where are they [background]), time of day, weather patterns, cinematography (medium, over the shoulder etc), director style
good: a cinematic still of a woman at a cafe, wearing a brown sweater, blonde hair, drinking coffee, paris cafe background 8k --seed 1234567890
better: a cinematic still of a blonde woman at a parisian cafe wearing a brown sweater, drinking coffee, 8k --seed 1234567890
better: a cinematic still of a blonde woman at a parisian cafe wearing a brown sweater at night, drinking coffee, 8k, ultra wide shot of the cafe --seed 1234567890
better: a cinematic still of a blonde woman at a parisian cafe wearing a brown sweater at night, drinking coffee, 8k, medium shot --seed 1234567890
better: a cinematic still of a blonde woman at a parisian cafe wearing a brown sweater at night, drinking coffee, 8k, close up of face --seed 1234567890
better: an asymmetrical cinematic still of a blonde woman at a parisian cafe wearing a brown sweater at night, drinking coffee, 8k, ultra wide shot of the cafe --seed 1234567890
better: an asymmetrical cinematic still of a blonde woman having a conversation at a parisian cafe wearing a brown sweater at night, drinking coffee, 8k, over-the-shoulder --seed 1234567890
better: a cinematic still of a blonde woman having a conversation at a parisian cafe wearing a brown sweater at night in the style of David Fincher, drinking coffee, 8k, over-the-shoulder --seed 1234567890
```
