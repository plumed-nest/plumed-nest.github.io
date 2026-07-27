**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmvrwv9:10336] *** Process received signal ***
[runnervmvrwv9:10336] Signal: Aborted (6)
[runnervmvrwv9:10336] Signal code:  (-6)
[runnervmvrwv9:10336] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1704645330]
[runnervmvrwv9:10336] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f170469eb2c]
[runnervmvrwv9:10336] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f170464527e]
[runnervmvrwv9:10336] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17046288ff]
[runnervmvrwv9:10336] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1704aa5ff5]
[runnervmvrwv9:10336] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1704abb0da]
[runnervmvrwv9:10336] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1704aa5a55]
[runnervmvrwv9:10336] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1704aa5a6f]
[runnervmvrwv9:10336] [ 8] plumed(+0x146dd)[0x5587206876dd]
[runnervmvrwv9:10336] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f170462a1ca]
[runnervmvrwv9:10336] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f170462a28b]
[runnervmvrwv9:10336] [11] plumed(+0x15365)[0x558720688365]
[runnervmvrwv9:10336] *** End of error message ***
</pre>
{% endraw %}
