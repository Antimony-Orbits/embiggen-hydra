# Introduction

What is this guide about? This is a collection of advice, and things that can trip you up, if you're looking to make your own scaled up head or sculpt using the Customize+ plugin, that I've collected in my experience doing the same. If you want to do the same or similar, hopefully this will help you too.

Please note that this is *not* a tutorial on how to use the Customize+ plugin, and assumes you have a basic level of understanding on how it works and what it does. There are various guide videos available that explain how to use C+ that would be a useful place to start if you've never used it before.

Details about the Customize+ plugin can be found here: https://github.com/Aether-Tools/CustomizePlus, as well as details about their discord server on which you can ask for general help in using the plugin.



# General Advice

Mirror mode is a *huge* time saver. Seriously, do not overlook this feature.

If there's an existing upscale preset for the same face you want to edit, or for one that's based on the same sculpt/face, test those options before beginning work. Starting from scratch takes hours longer than starting from something else that's already close to what you want - that's part of the reason I originally made them, after all.

You can click and drag on a bone's axis number in C+ to adjust it while editing a template. The mouse scroll wheel works in a similar way while mousing over the same numbers.

Clicking and dragging the numbers of a bone's position is a good way to discover where it is on the face, and what direction that axis is aligned for that bone.

If you're making more than just a few templates, it can help to sort your C+ templates and profiles into folders. Future you will thank you for doing so.

## Checking for Inconsistencies and Distortions

There are several emotes that are good to use to check for distortions, facial weirdness, and clipping. I commonly use the following to do such checks:

- pucker up (this is by far the worst offender when it comes to emote distortion as it sometimes looks bad even on a sculpt or vanilla face; if you can get it looking good, you've done a good job with the lips)
- ouch
- big grin
- content

Also using emotes that change the eyelid shape, while looking to the side at sharp angles, helps a lot in catching weird eyelid and eyeball clipping (more on that in the Gotchas section).
What looks good on a resting face will not necessarily look good on the same face when emoting.

While editing a face, pick a haircut that doesn't obscure the facial features or shape, so you can see your changes more easily.

Facial features, tattoos, and face paints are helpful to enable on most heads and sculpts (if they have them) to check for any distortions in appearance on an upscaled head. Whether any particular distortion is acceptable or not is subjective.

Look at your upscaled face, as you work on it, from many different angles, to spot any weirdness in the face shape. Sharp angles from the side, above, and below help a lot in picking out weird distortions, and 3/4 angles are good for checking the cheeks, brows, and eyelids at the edge of the face. Moving or scaling bones may look good from one angle, but might look terrible from another, so it's always good to check your work before committing to it.

Hats like the Varsity Flat Cap, and YorHa Type-55 Cap of Fending/Maiming are good hats to test visor and hat adjustments with respect to whether visors and facial accessories will clip through or align with the face, because you can easily toggle the visor on and off while working. Be aware that when you put these on, or activate an upscale, visors *may not necessarily* apply scaling values correctly the first time. You may have to disable and enable scaling, or preset editing, to get them to display properly.

## Other Useful Tools

Cammy, by UnknownX, is a fantastic third party plugin that lets you use freecam to get up close and personal with your sculpt as you work on it, to get a much better look at changes you make.

Make up and eye texture mods help a *lot* to make a face look good when it's been made bigger. This is especially true of vanilla faces.

If you prefer or are more familiar with the likes of Brio, Ktisis, or Anamnesis for posing, you may find it easier to use them to edit faces, and then export the pose from them, to be imported into C+ as a new template.

If you're using something like Izumi's Ultimate Height Mod, turn it off while editing sculpts; it makes it easier to see what's going on with the head when your character is full size.

# How To

There are no strict guidelines, or step by step guide to making heads bigger with C+. Most of it is just tinkering with bones little by little until you're satisfied with the shape of the head, and looking at it from a lot of different angles to check if it's unsatisfactory of there are things you want to change.

The easiest way to get started, after learning how C+ works, is to tinker by making small incremental changes. Shift or resize a bone just a little, in a direction you think will make it look better, or more like your goal. It's vastly easier to slowly move parts of the whole face little by little towards your ideal, so you can see the whole thing gradually changing, than it is to try and force each bone into position one by one - I've found the process of upscaling heads is more like sculpting clay than building a lego set, if that makes sense.

While I've been basing the rough head sizes I use on existing head mods for smols, that doesn't mean you have to. If you *want* to, though, I recommend about 1.2 scale increase for the head for roughly the same size as "small" head mods (what I use for all Faithful small sized heads), and 1.3 head bone scale increase for "big" head mod equivalent size (what I use for all Cherubs). Admittedly these scales are slightly smaller than the head mods I refer to, but I've encountered a lot of trouble with emotes when going larger than 1.3 scale on the head bone.

Whether an upscaled head looks good, or correct, is a matter of subjective opinion; it really is up to you to decide if you're satisfied with what you've made. While my Faithful series of upscales attempts to recreate the same look as the faces the upscale is based on (with the exception of slightly bigger eyes for the vanilla heads), that doesn't mean you have to; I made them initially because it was the easiest way to check and experiment to see if I could accurately reproduce the look at larger scales by turning the scale on and off to check for inaccuracies, and in the hopes that they'd make good bases from which to make more creative and expressive upscales.

This is more art than science, so the best place to start is finding inspiration! Is there a face, or look, you'd love to have in game that doesn't exist for smols yet? You could be the one to bring it to life!

# Gotchas and Things to Look out for

## Axes and Bone Variation

Axes for various bones do not align with one another; you move one bone in one axis, and it's neighbour will not necessarily move along the same path the same distance when you adjust the same axis. This is especially obvious in the lips and eyelids.

Different faces often, but not always, have different skeletons; the bones are matched to slightly different positions on the facial model in plenty of cases. Difference in race, sex, and even just face number can often mean different skeletons. E.g. while one upscale may work for all female Miqo'te faces, this is not true for female Au'ra.

Most of the facial features do not move, or scale, when you adjust the head bone. Even if you use a plugin like Brio, Ktisis, or a program like Anamnesis, with parenting enabled, to adjust the head bone, the facial features will not move or scale together with it in a sensible manner (at least last time I tried this in 2025).

The further a bone is moved from it's original position, scale and rotation, the more distorted it will become when other things, like emotes, move or warp it. The more you test, like in the Advice section, the more you can mitigate these distortions.

## Bigger Heads

The bigger you make the head, the worse distortions will get for expressions, and facial bone adjustments you will need to make to get a nice looking face. 1.2 times scale is manageable and can still look good with emotes. 1.3 times scale needs a lot more adjustment to still look passable. Above that you'll be sacrificing a lot of emotes, and side glances are going to look worse and worse.

Head scales in each dimension do not change the head size uniformly; i.e. 1.2 X is not the same amount of change as 1.2 Y or 1.2 Z. This warps the shape of the head the more you upscale it. I've found Z and X usually need lower scale numbers than the Y axis, when upscaling, but the difference is slight, and is only strongly felt at 1.3 and higher scales. Whether you want a uniform head shape is up to you though, but it's something to be mindful of.

Scaling up the head also moves it in such a way that will distort emotes if you just leave it where it goes and then adjust all the facial bones to match it. I've found moving the head -0.008 X, regardless of how big the head has been scaled to, and adjusting the facial bones to match, produces a lot less emote distortion and other problems; this is because it brings the front of the face a lot closer to where it was before the head was scaled up. The trade-off with this is that you get a bit of a protrusion visible at the base of the neck where it meets the skull, but you can shrink the head in the X axis to mitigate this, though it isn't visible or noticeably a bad thing for most people's tastes.

Some bones look better when scaled up along with the head, others do not. Sometimes it's sculpt/head-dependent. I've found it useful to increase the scale of the following bone groups along with the head size (usually the same amount of scale in all axes, but not always, and again it's sculpt-dependent);

- Lips (in X and Y axes, but not usually Z, and not always by as much as the head)
- Eyes (more details about eyes and their specific issues below), eyelids, and eyebrows
- Cheeks
- Ears
- Earrings (up to your own taste, but it helps to not have to reposition them as much to compensate for ear and head size changes)
- Teeth
- Tongue sometimes (depends on what the sculpt does to the teeth, if anything)
  
  ## Facial Feature Variation
  
  Remember that some sculpts, and all vanilla heads, come with facial feature options. If you have the time and energy, test all of these to make sure they look satisfactory to you when scaled up; e.g. one set of positions and scales may not look good on all elezen ears, or noses, or insert-bone-group-here, etc.
  
  ## Noses
  
  The tip of the nose is attached to the root head bone, not the nose bones (which are actually just the nostrils). The X and Y positions and scales of the head bone play the biggest role in influencing the nose, so you may need to adjust the entire head position and shape to improve the nose itself. This can be mitigated somewhat by making the head a little thinner in the X axis, as well as adjusting the nose bone position and rotation, and the bridge bone position and rotation (these vary based on the head shape, as to what will look nice). If the nose is still protruding a lot, and you can't sacrifice more of the head depth to fix it without breaking other things, you may benefit from reducing the bridge X scale way way down (I've had to go as low as 0.225 on some heads).
  
  ## Eyeballs
  
  Eyeballs aren't spherical; the bigger the eyeball, the worse the effects of this get when looking to the side. Making the eyeball thicker in depth (X axis) than in the other dimensions helps mitigate this. I've found about 10% greater than the other axes is good most of the time.

Eyeballs don't rotate around the centre of the hypothetical sphere they *should* be. Instead the point around which they rotate seems to be offset on the X and and Z axes, towards the middle and front of the face. This creates the most obvious problems when looking to the side or up and down; the eyes tend to clip through the eyelids at the corners of the eyes on one side, and create gaps between the eyeballs and the eyelids on the other. This gets worse and worse the bigger the head gets, and the further the eyes get from their original size and position. Making the eyes thicker on the X axis helps one of these, but the other can be mitigated by making the eyelids much thicker (1.5 to 1.8 X scale depending on head size and how thick the eyelids already are on the head/sculpt) and adjusting their position accordingly to avoid problems. However, the thicker you make the eyelids, the worse they'll distort, and the more adjustments you'll need to make to make them look nice again.

## Mouths and Lips

The very corners of the mouth are also attached to the cheeks in such a way that has an influence on mouth shape; specifically the middle cheek bones. With some faces you can therefore adjust the resting appearance of a smile or a frown, or a straight face, by positioning the middle cheek bones accordingly, usually vertically, on the Y axis.

Remember that the inside of the mouth exists; you will likely need to adjust the position and scale of the teeth and tongue to get it looking nice after making the head bigger. Don't ignore or overlook this, otherwise you're going to get some weird looking open-mouthed gposes in the future.

## Chins

Some head sculpts get weird around the chin and lower jaw when the head bone is scaled up; you can end up with a second chin on some of them. The aforementioned moving of the head by -0.008 X helps mitigate this, but it's sometimes not enough for every head. Some need the head to be moved upwards, or shrunken, in the Y axis to help with this (though this can create other problems), while others you can adjust the dimensions and position of the lower jaw bone to compensate. A different mitigation method is to move the neck bone downwards a little, and to thicken it (I've never had to use more than an extra 10% neck thickness to fix it); this smooths out the curve from jaw to neck, reducing the appearance of a second chin. Which mitigation method works for the head you're working on, and you're willing to use, is up to you.

## Visors

Visors do not scale in line with the head scaling; e.g. 1.2 scale in all dimensions for the visor is smaller than 1.2 scale in all dimensions for the head. X and Z axes scales play a bigger role in fitting a visor to the face than the Y axis, for some visors. The use of glasses face accessories, or the Varsity Flat Cap head gear with the glasses displayed, will help you test and fix this issue.

Not all visor bones behave the same way. You may have to pick and choose which visors you want to look good on your upscaled head, because their bones and axes aren't all oriented or weighted the same.

## Ears and Earrings

Ears often need repositioning and increases in scale, to stay looking good on a bigger head, at least for races whose heads have ear bones (Hyur get a free pass).

Last time I checked, mirror mode was broken in C+ for earring position; turn it off when you adjust earring position, and remember to turn it back on after.

### Viera Heads

Viera ears do not have the same earring positions for different ear types; be careful editing these and know that you probably can't achieve a good earring position for all viera ears in the same upscale.

Viera ears types do not share the same bones; you will need to adjust scaling and position for all viera ear types if you want them to look good with your head upscale.

## Hair

Different hairstyles have different bones, and this can vary with modded hair too. You will not be able to adjust the hair for every style and expect that it will still look good if someone then uses a mod that replaces any of those hairstyles.

The bigger a head gets, the worse the clipping with certain hairstyles gets. A common offender is the fringe.

# Conclusion

Good luck on your head upscaling! I know it's a lot to take in all at once, but this stuff was discovered over the course of almost a year of messing with upscales, so there's been many bits and pieces to stumble upon in that time. I've tried to include as much of it as I could remember, without overwhelming you with all the details (I hope).

Remember that there are plenty of people in the community that you can ask questions of if you get stuck or have trouble, when it comes to making your own upscales.