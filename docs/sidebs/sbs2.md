![Side by Side 2 logo](https://web.archive.org/web/19971012061831im_/http://www.taito.co.jp/sbs2/title.gif)

*Nice to see ya again.*

The second game in the series, [releasing in May 1997 in Japan](https://archive.org/details/ArcadeGameList1971-2005/page/n46/mode/1up?view=theater) with the RR update releasing several months later.

!!! note 
    If you are emulating any Taito JC System game in MAME, you should be running version 0.266 with `-cheat` switch and overclock the `maincpu`, `sub`, and `dsp` CPUs to at least 200%. [Properly overclocked, it should run like this.](https://www.youtube.com/watch?v=BN6cwDzq0fg) Currently, Taito JC games suffer from a slowdown due to imperfect CPU emulation. [Starting from version 0.267,](https://github.com/mamedev/mame/commit/3d357c07c0ca824868bbe7586839c8caae236571#diff-2fc8ed920c6dc8de6019a9cde02d47e52e622912f49e6e03a5544471103b32d4) changes in Motorola 68000 FPU emulation has made the performance worse, even overclocked.

WIP

# Builds

Build Tag | Language/Region | Dump Status | Notes
------ | ------ | ------ | ------ |
Unknown | Japanese, original | Undumped | Earlier builds are known to exist with swapped month labels for the Professional (July) and Ace Driver (October) courses, [as shown on the flyer,](../../images/etc/sbs2_flyer.jpg) although they were either location testing or internal use builds. Although this mistake was fixed for all known arcade versions, it was never fixed in any version of *Side by Side Special.*
`SIDE BY SIDE2 VER 2.4 J 1997/ 5/26 3:06:37` | Japanese, original | In MAME (`sidebs2ja`) | Earliest known base Japanese version. This build has the month labels for the July and October tracks in the correct position.<br>Added in MAME version 0.124u2.
`SIDE BY SIDE2 VER 2.6 OK 1997/ 6/ 4 17:27:37` | English | In MAME (`sidebs2`) | International English version; `K` in region tag probably means South Korea ("Overseas + Korea"?)<br>Honda cars are available, but trim badges were removed from them.<br>A cabinet with this ROM has not been spotted in the wild, although PCBs do exist given how it is dumped and present in MAME.<br>Added in MAME version 0.175.
`SIDE BY SIDE2 VER 2.6 A  1997/ 6/19 09:39:22` | English, US | In MAME (`sidebs2u`)  | US English version with [Honda cars disabled](..\other\honda.md) (an issue not mentioned in the flyer) and "Winners Don't Use Drugs"/"Recycle It, Don't Trash It" PSAs.<br>Unknown how many cabinets were actually distributed with this ROM as the game is not mentioned in the US list of the 2005 edition of *Domestic and Overseas Arcade Game List*, [but PCBs do exist.](https://www.youtube.com/watch?v=RVvNLj7oVek)<br>Added in MAME version 0.81u4; despite the rarity, this version was the first one to be dumped and added to MAME.
`SIDE BY SIDE2 RR VER 3.1 J 1997/10/ 7 13:55:38` | Japanese, RR | In MAME (`sidebs2j`) | *Evoluzione RR* update, only released for the Japanese version. Adds reverse courses (shift when selecting cars) and post-race replays, adjusts shift points for AT users, and more.<br>Most known cabinets are of this revision.<br>Added in MAME version 0.181.

# Cabinets

WIP

# Cars

See the [SBS2 Cars page.](../sidebs/sbs2_car.md)

# Tracks

See the [SBS Tracks page.](../sidebs/tracks.md)

!!! tip
    Hold View button after coining up to temporaily unlock the Special course, if the track has not yet been permanently unlocked. (Getting a high score will unlock the track permanently.)

# Version Differences

WIP

# Others

- When in attract demo, pressing the View Change button will change currently focused car.
