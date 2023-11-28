# shubtitle
Add subtitle to video (bash/imagemagick/ffmpeg)

```bash
Program : shubtitle  by p.forret@brightfish.be
Version : v0.1.0 (2023-11-28 10:22)
Purpose : add/replace subtitles on video
Usage   : shubtitle [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] 
			[-W <width>] [-H <height>] [-Y <vertical>] [-F <font>] [-S <start>] [-E <end>] [-T <title>] [-P <points>] 
			<action> <input?> <output?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /home/pforret/log/shubtitle]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/shubtitle]
    -W|--width <?>   : [option] subtitle width  [default: 1100]
    -H|--height <?>  : [option] subtitle height  [default: 50]
    -Y|--vertical <?>: [option] Y position  [default: 975]
    -F|--font <?>    : [option] font to use  [default: Helvetica]
    -S|--start <?>   : [option] start at N seconds  [default: 0]
    -E|--end <?>     : [option] end at N seconds  [default: 500]
    -T|--title <?>   : [option] subtitle text  [default: Bier met liefde gebrouwen, drink je met verstand]
    -P|--points <?>  : [option] subtitle size  [default: 32]
    <action>         : [choice] action to perform  [options: subtitle,check,env,update]
    <input>          : [parameter] input file (optional)
    <output>         : [parameter] output file (optional)
```