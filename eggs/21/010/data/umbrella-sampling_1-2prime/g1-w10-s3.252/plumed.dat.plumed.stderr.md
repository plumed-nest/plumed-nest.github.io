**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w10-s3.252/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:06408] *** Process received signal ***
[runnervmvrwv9:06408] Signal: Aborted (6)
[runnervmvrwv9:06408] Signal code:  (-6)
[runnervmvrwv9:06408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6285645330]
[runnervmvrwv9:06408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f628569eb2c]
[runnervmvrwv9:06408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f628564527e]
[runnervmvrwv9:06408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62856288ff]
[runnervmvrwv9:06408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6285aa5ff5]
[runnervmvrwv9:06408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6285abb0da]
[runnervmvrwv9:06408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6285aa5a55]
[runnervmvrwv9:06408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6285aa5a6f]
[runnervmvrwv9:06408] [ 8] plumed(+0x146dd)[0x55c3ca6656dd]
[runnervmvrwv9:06408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f628562a1ca]
[runnervmvrwv9:06408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f628562a28b]
[runnervmvrwv9:06408] [11] plumed(+0x15365)[0x55c3ca666365]
[runnervmvrwv9:06408] *** End of error message ***
</pre>
{% endraw %}
