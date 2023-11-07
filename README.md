# Pod Go Patches

## About

This repo contains a couple of handy tweaked preset config files for the Line 6 Pod Go.

By default, all of the presets available on the Pod Go, whether factory or user defined, only allow for 4 fully assignable effects block per preset
across the 6 footswitch blocks on the physical device. This is because 2 of these 6 are 'fixed' to:

- Send/Return FX Loop (mono or stereo options)

- EQ (with 7 available devices within this category of FX)

If you don't have a need for either of these in your chain, it's a little annoying that you can't decide to do something else with the blocks of your
own choosing.

Whilst it seems at this time you can't free up the EQ block for any category of effect, this can at least be achieved for the Send/Return loop, and also 
one of the fixed expression pedal blocks (see further notes below) by importing these patches into your device via the Pod Go Edit software.


## Provided patches

### NoSendBlock.pgp

This patch erases the Send/Return FX Loop device, giving 1 additional fully assignable block.

### NoSendOrVolumeBlock.pgp

This patch does as the first, but also clears out the non-footswitch assignable Volume expression block. This will provide
a total of 6 fully assignable blocks, with the caveat that the last block you assign an effect to will be cast to the expression
pedal block, and is not footswitch controllable. This suits an 'always on' effect, maybe a compressor or similar.

## Note

There will be some chain configurations where adding demanding effects will exceed the available processing power of the Pod Go DSP. In this case, devices which would 
exceed the DSP limits become grayed out (you can observe this even with the regular number of blocks if you're using multiple resource 
intensive effects).

Whilst I've not had any issues at all with the Pod Go crashing during use, I'll add that you use these patches at your own risk :-)

### Tested and working with versions:

```
POD Go Edit: 2.00
POD Go Firmware 2.00 (Build 9e51b97b)
````

