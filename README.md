# soundsensepack
unofficial soundpack update for jecowa's SoundSense pack

I wanted to play the new shiny OST in my classic Dorf Fortress game, so I made this

steps to get this working
1. you must buy and provide the OST files yourself
buy them here:
https://dabuaudio.bandcamp.com/album/dwarf-fortress-official-steam-soundtrack
2. you must download the ost as mp3 V0 files, if you want to download them as other mp3 formats you'll have to fork it yourself
3. place the files into the seasons/ost directory
4. replace all ampersands (&) with dashes (-), except for the ampersand in track 10, Drink & Industry, replace that with an underscore (_), I kept the filename as close to the bandcamp downloaded filenames so they're a little verbose
you can use the linux rename utility as such:

`
rename -iv '&' '-' Dabu\ -\ Águeda\ Macias\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 03\ Craftsdwarfship.mp3 Dabu\ -\ Águeda\ Macias\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 11\ Mountainhome.mp3 Dabu\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 02\ First\ Year.mp3 Dabu\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 05\ Strange\ Moods.mp3 Dabu\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 12\ Death\ Spiral.mp3 Dabu\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 13\ Winter\ Entombs\ You.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 01\ Dwarf\ Fortress\ \(Main\ Theme\).mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 04\ Strike\ The\ Earth\!.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 06\ Hill\ Dwarf.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 07\ Vile\ Force\ of\ Darkness.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 08\ Expansive\ Cavern.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 09\ Forgotten\ Beast.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 10\ Drink\ \&\ Industry.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 14\ Another\ Year.mp3 Dabu\ \&\ Simon\ Swerwer\ -\ Dwarf\ Fortress\ \(Official\ Steam\ Soundtrack\)\ -\ 15\ Koganusan.mp3
`

5. (optional) I added the entire OST to every season, if you want certain songs in certain seasons, just delete the entire line in seasons/seasons.xml
e.g. delete this entire line
		<soundFile name="Dabu - Simon Swerwer - Dwarf Fortress (Official Steam Soundtrack) - 04 Strike The Earth!.mp3" />


unofficial update of zwei's "Official soundpack" for SoundSense
from http://df.zweistein.cz/soundsense/


Credits for help for to [tyrspawn](http://www.krauselabs.net/) and Rainseeker :). Music from following sources was also used:

 * [Simon Swerwer](http://www.reverbnation.com/simonswerwer) - OST
 * [Roguelike Bard](http://roguebard.eptalys.net/)
 * [Kevin MacLeod](http://incompetech.com/m/c/royalty-free/index.html)
