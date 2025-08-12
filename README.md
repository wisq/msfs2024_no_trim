# No Trim

_**IMPORTANT: This mod does not currently work.**  While I could get my new aircraft preset to show up in MSFS2024, I could not seem to actually disable the trim tab.  If you can get this working, let me know!  For now, I'm focusing my efforts on [harware trimming](https://github.com/wisq/dp_trim) instead._

This is a simple MSFS2024 mod that seeks to remove the trim functionality from select aircraft.  The trim wheel will still work, but the trim tab will not actually deflect to any meaningful degree.

I wrote this because I use a force feedback yoke with software that can read the trim setting on the aircraft and set the simulated yoke forces accordingly, in order to simulate how trim really works on small aircraft.

Unfortunately, MSFS assumes yokes will always revert to a set neutral point.  Thus, the only reasonable way for them to simulate trim is to have the trim tab act as a secondary (additive) pitch control.  This disables that.
