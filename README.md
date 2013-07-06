Arduino Pronto Hex Sender
=========================

Arduino sketch to send Pronto Hex commands with an infrared LED attached to pin D9.

To send Sony12, device = 1, obc = 47, send the following command over the serial line withg 9600 N 1:
<pre>
SEND 0000 0067 0000 000d 0060 0018 0030 0018 0030 0018 0030 0018 0030 0018 0018 0018 0030 0018 0018 0018 0030 0018 0018 0018 0018 0018 0018 0018 0018 03de
</pre>

Make sure you send a newline character at the end of the line.
