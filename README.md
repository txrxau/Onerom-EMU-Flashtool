# Ostrich-compatible protocol serial emulation device for One ROM flashtool
<p>
    One ROM EMU Flashtool for Fire 28 (A or B)
</p>
<p>
    Flashes a custom Ostrich-compatible protocol serial emulator on a One ROM Fire 28 for realtime ECU/PCM tuning.<br>
    Compatible with TunerPro RT.<br>
    Released as is, where is.<br>
    For OFFroad use only<p>
    Bank switching is disabled, UART uses the One ROM SELA and SELB pins.
</p>
<p>
<p>
    <img src="onerom_emu_flashtool.jpg" width="520"/>
</p>
<p>
    <b>Choose Eprom type.</b><p>
    <b>Serial Port 2:</b> NORMAL is enabled 115200 8N1 or Disabled (Use DISABLED for GM/Holden, I don't think normal will work but I could be wrong).<p>
    <b>Select .bin file.</b><p>
    <b>Build image.</b><p>
    <b>STOP</b> (If OneROM is running, Should auto detect but may need to press Refresh).<p>
    <b>FLASH</b><p>
    <b>RUN</b> starts the Emu.
</p>
<p>
    <img src="EMU.jpg" width="320"/><br>
    Emus can run up to 50 km/h (31 mph).
</p>
<p>
    Once uploaded with this firmware use TunerPro RT to edit/upload different tunes.<br>
    Only need to use the flashtool to change Eprom type or 2nd COM port settings after initial flashtool use.
<p>
<p>
    Information about the original One ROM Project can be found here<br>
    https://onerom.org/ or https://github.com/piersfinlayson/one-rom
</p>
