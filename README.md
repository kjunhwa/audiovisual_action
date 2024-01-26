# audiovisual_action
Update soon

This repository is the implementation of "Audio-visual Action Recognition using Transformer Fusion Network". 
This code is based on the GitHub repository of the "Swin Transformer" paper.
(https://github.com/microsoft/Swin-Transformer)

Dataset preparation

1. UCF-sound(The subset of UCF-101)
   1) Download UCF-101 dataset
   2) The class list provided below includes audio files within video data. Please separate these classes from the UCF-101 dataset.
(CliffDiving/Rafting/SoccerPenalty/BabyCrawling/LongJump/Hammering/HandstandWalking/CuttingInKitchen/StillRings/BoxingPunchingBag/PlayingDhol/Surfing/BrushingTeeth/Archery/IceDancing/MoppingFloor/PlayingFlute/BoxingSpeedBag/ParallelBars/UnevenBars/Typing/PlayingCello/TableTennisShot/BasketballDunk/ApplyLipstick/BalanceBeam/PlayingDaf/SumoWrestling/CricketShot/Knitting/FloorGymnastics/Shotput/WritingOnBoard/ShavingBeard/Haircut/BlowingCandles/PlayingSitar/HeadMassage/FrontCrawl/BodyWeightSquats/BandMarching/FrisbeeCatch/FieldHockeyPenalty/HandstandPushups/BlowDryHair/Bowling/WallPushups/CricketBowling/SkyDiving/HammerThrow)
2. Kinetics-sound(The subset of Kinetics-400)
   1) Download Kinetics-400 dataset
   2) The class list provided below includes audio files within video data. Please separate these classes from the Kinetics-400 dataset.
(playingtrumpet/stompinggrapes/shovelingsnow/playingclarinet/strummingguitar/blowingnose/playingxylophone/blowingoutcandles/rippingpaper/tapdancing/bowling/laughing/playingbassguitar/playingviolin/playingkeyboard/playingtrombone/tappingpen/dribblingbasketball/playingdrums/choppingwood/singing/playingbagpipes/mowinglawn/playingorgan/playingpiano/shufflingcards/playingguitar/playingaccordion/tickling/playingharmonica/tappingguitar/playingsaxophone)

3.  Extract the frames from the video.
4.  Extract the WAV file from the video.

