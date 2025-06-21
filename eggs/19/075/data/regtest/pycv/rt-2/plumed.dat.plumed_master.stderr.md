**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmxyh4eaekms:11253] *** Process received signal ***
[pkrvmxyh4eaekms:11253] Signal: Aborted (6)
[pkrvmxyh4eaekms:11253] Signal code:  (-6)
[pkrvmxyh4eaekms:11253] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c06245330]
[pkrvmxyh4eaekms:11253] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c0629eb2c]
[pkrvmxyh4eaekms:11253] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c0624527e]
[pkrvmxyh4eaekms:11253] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c062288ff]
[pkrvmxyh4eaekms:11253] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c066a5ff5]
[pkrvmxyh4eaekms:11253] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c066bb0da]
[pkrvmxyh4eaekms:11253] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c066a5a55]
[pkrvmxyh4eaekms:11253] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c066a5a6f]
[pkrvmxyh4eaekms:11253] [ 8] plumed_master(+0x146dd)[0x564e1aa2d6dd]
[pkrvmxyh4eaekms:11253] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c0622a1ca]
[pkrvmxyh4eaekms:11253] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c0622a28b]
[pkrvmxyh4eaekms:11253] [11] plumed_master(+0x15365)[0x564e1aa2e365]
[pkrvmxyh4eaekms:11253] *** End of error message ***
</pre>
{% endraw %}
