---
layout: post
title: "Fillerati"
author: "Alex Kestner"
date: 2014-01-31 00:52:43 -0500
comments: false
categories:
  - "Cities of Gold"
  - Thundercats
  - "Ah-ah-ah-ah-ah.."
---
##This is my boss
__Jonathan Hart__, a self-made millionaire, he's quite a guy. This is
Mrs H., she's gorgeous, she's one lady who knows how to take care of herself. By the way,
my name is Max. I take care of both of them, which ain't easy, 'cause when they met
it was *MURDER!*

Children of the sun, see your time has just begun, searching for your ways, through
adventures every day. Every day and night, with the condor in flight, with all your
friends in tow, you search for the Cities of Gold. _Ah-ah-ah-ah-ah..._ wishing for The
Cities of Gold. _Ah-ah-ah-ah-ah..._ <!-- more --> some day we will find The Cities of Gold.
> _Do-do-do-do ah-ah-ah, do-do-do-do, Cities of Gold. Do-do-do-do, Cities of Gold. Ah-ah-ah-ah-ah..._
> some day we will find The Cities of Gold.

```php
foreach($outputs as &$output) {
/** @var Output $output */
$presetId = $output->getPresetId();
$outputPreset = $output->requestPresetById($presetId);
$inputFilePath = $this->getInput()->getInputFilePath();

$explodedInputFilePath = explode('/', $inputFilePath);
$inputFilename = end($explodedInputFilePath);

// only explode inputFilename by '.' if it contains a '.'
if(strpos($inputFilename, '.') === false) {
    $filename = $inputFilename;
} else {
    $explodedInputFilename = explode('.', $inputFilename, -1);
    if(count($explodedInputFilename) > 1) {
        $filename = implode('.', $explodedInputFilename);
    } else {
        $filename = $explodedInputFilename[0];
    }
}
```

### **Thunder, thunder, thundercats, Ho! Thundercats are on the move, Thundercats are loose.**
> Feel the magic, hear the roar, Thundercats are loose. Thunder, thunder, thunder, Thundercats!
> Thunder, thunder, thunder, Thundercats! Thunder, thunder, thunder, Thundercats! Thunder,
> thunder, thunder, Thundercats! Thundercats!

Mutley, you snickering, floppy eared hound. When courage is needed, you're never around.
Those medals you wear on your moth-eaten chest should be there for bungling at which you
are best. So, stop that pigeon, stop that pigeon, stop that pigeon, stop that pigeon, stop
that pigeon, stop that pigeon, stop that pigeon. Howwww! Nab him, jab him, tab him, grab him,
stop that pigeon now.