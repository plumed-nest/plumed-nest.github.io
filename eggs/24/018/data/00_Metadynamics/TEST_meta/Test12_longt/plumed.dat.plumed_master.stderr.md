**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmxyh4eaekms:06491] *** Process received signal ***
[pkrvmxyh4eaekms:06491] Signal: Aborted (6)
[pkrvmxyh4eaekms:06491] Signal code:  (-6)
[pkrvmxyh4eaekms:06491] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8049645330]
[pkrvmxyh4eaekms:06491] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f804969eb2c]
[pkrvmxyh4eaekms:06491] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f804964527e]
[pkrvmxyh4eaekms:06491] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80496288ff]
[pkrvmxyh4eaekms:06491] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8049aa5ff5]
[pkrvmxyh4eaekms:06491] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8049abb0da]
[pkrvmxyh4eaekms:06491] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8049aa5a55]
[pkrvmxyh4eaekms:06491] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8049aa5a6f]
[pkrvmxyh4eaekms:06491] [ 8] plumed_master(+0x146dd)[0x557b1f0226dd]
[pkrvmxyh4eaekms:06491] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f804962a1ca]
[pkrvmxyh4eaekms:06491] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f804962a28b]
[pkrvmxyh4eaekms:06491] [11] plumed_master(+0x15365)[0x557b1f023365]
[pkrvmxyh4eaekms:06491] *** End of error message ***
</pre>
{% endraw %}
